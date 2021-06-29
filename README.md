# Certificate

HM University Certificate


## Usage

Fork the repo and replace your name in `cert.tex`, then open `Github Actions` to download your certificate!

## Compile

1. **makesure** you have `LaTeX` environment installed!

2. clone git repository

```bash
git clone https://github.com/HMUniversity/Certificate.git
```

3. replace your name in `cert.tex`, then run 

```bash
xelatex -synctex=1 -interaction=nonstopmode -file-line-error -pdf cert.tex 
```

4. get `cert.pdf`!
