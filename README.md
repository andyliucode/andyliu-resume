# andyliu-resume
LaTeX source for Andy Liu's [curriculum vitae](AndyLiuResume.pdf)

## How to use
My resume uses a XeLaTeX template and therefore must be compiled with XeLaTeX.

XeLaTeX is packaged with MacTex - I recommend following [this guide](https://www.wellesley.edu/lts/techsupport/latex/latexmac#:~:text=To%20install%20LaTeX%20applications%20on,a%20bit%20while%20it%20downloads.) for installing MacTex.

There appears to be a bug where sometimes the header (containing your name) does not appear after typesetting, but this is resolved by simply typesetting again.

## Attribution
Originally, I based my resume off of the the Friggeri Resume/CV XeLaTeX Template, Version 1.0 (5/5/13). Since then, I have made modifications to the template and `.cls` file, so do not consider this to be a faithful preservation of the template.

## Caveats
As [others](https://tex.stackexchange.com/questions/248399/transform-friggeri-cv-to-a4) [have](https://github.com/Nadorrano/cv-friggeri-x) [noticed](https://github.com/depressiveRobot/friggeri-cv-a4), the Friggeri-CV has a few bizarre flaws, mainly that it does not produce an A4-sized document and it uses the Helvetica font, which is commercial (i.e. not free). I didn't know about this when I first started using the template in undergrad and I'm too lazy to switch now.
