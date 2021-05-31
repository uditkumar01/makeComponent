# MakeComponent For React v0.0.1

A cool shell script to make React component templates at ease

### Installation and Setup

-   Open terminal on linux OS.
-   Then clone the repo using `git clone https://github.com/uditkumar01/makeComponent.git`
-   Then type the following commands:

    -   `sudo apt install tree`
    -   `cd makeComponent`
    -   `sudo mv mkcomp ~/../../bin`
    -   `sudo chmod +x ~/../../bin/mkcomp`

-   Open a new terminal and try running the command `mkcomp`

### How to use?

-   Usage: `mkcomp --gui`

    **OR**

-   Usage: `mkcomp component-name -ct extension`

    -   `-c` => Do you need a css file?
    -   `-t` => Do you need a test file?
    -   extension => `-ts` / `--typescript` / `-js` / `--javascript`

### Features

-   You can create components with just a single command.
-   GUI interface is also supported for ease of use.
-   You can choose if you wish to create test file, css file for that component.
-   If you made css file then it will automatically be imported in the jsx/tsx file.
-   Will automatically create boiler plate code for the component generated.
-   Will automatically export the file from `index.js`

### Demo Usage

https://user-images.githubusercontent.com/55291327/120177430-0e561380-c226-11eb-8f08-71066d01b656.mp4
