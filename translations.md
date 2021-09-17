# Command Translations

Command Translations from Windows - macOS

Remember these need to be run in Terminal.app, or the VS Code terminal. Every command below looks for the file you want to work with in the current folder. Make sure you're in the correct folder with Terminal.app (using GoToShell in the Finder) or always opening the folder in VS Code before you start the terminal. (I mean always open the folder so VS Code knows which folder to open its terminal in, not open the folder right before you run a terminal or anything like that.)

```
bcc32c hello.cpp        # bcc32c is a "Clang-enhanced" compiler for Windows
clang++ hello.cpp       # On recent macOS we just use Clang

dir
ls                      # 'ls -l' is closer since dir shows file metadata

hello                   # Windows compilers name the output executable <filename>.exe
./a.out                 # Unix compilers name the output 'a.out'. You could run 'clang++ hello.cpp && mv a.out hello'

md
mkdir
```
