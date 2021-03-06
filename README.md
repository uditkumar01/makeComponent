# 🌟 MakeComponent For React `v1.1.0` 🌟

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

### Updating your existing `mkcomp` script

-   Open terminal on linux OS.
-   Go to github repo https://raw.githubusercontent.com/uditkumar01/makeComponent/main/mkcomp copy the code of `mkcomp`.
-   Then type the following commands:
    -   `sudo gedit ~/../../bin/mkcomp`
-   A gedit editor will open
-   Replace the currect code with the copied one.
-   Press save button.. wait for 2-3 secs.
-   Boom!!! you are ready to go.

### How to use?

-   Usage: mkcomp `--clean`
    `--clean` will help you to remove unwanted files/folders and structure them properly. Everything is automated.

-   Usage: `mkcomp --gui`

    **OR**

-   Usage: `mkcomp component-name -ct extension`

    -   `-c` => Do you need a css file?
    -   `-t` => Do you need a test file?
    -   extension => `-ts` / `--typescript` / `-js` / `--javascript`

### Features v1.0.0

-   You can create components with just a single command.
-   GUI interface is also supported for ease of use.
-   You can choose if you wish to create test file, css file for that component.
-   If you made css file then it will automatically be imported in the jsx/tsx file.
-   Will automatically create boiler plate code for the component generated.
-   Will automatically export the file from `index.js`

### Features v1.1.0

-   You can clean your create react app initial template using `-clean` command easily.
-   Now the imports exports in index file will be properly formatted 👌.

### Demo Usage

https://user-images.githubusercontent.com/55291327/120177430-0e561380-c226-11eb-8f08-71066d01b656.mp4
