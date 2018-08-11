# nim-example

> An example nim project developed in SpaceVim

## Features

- compile and run file

the default key bindings is `SPC l r`

![2018-08-11-11-57-19](https://user-images.githubusercontent.com/13142418/43988039-34124c9a-9d5f-11e8-97e6-dcd6a2658ea4.gif)

- REPL support 

Start a `nim secret` inferior REPL process with `SPC l s i`.

Send code to inferior process commands:

| Key Binding | Description                                      |
| ----------- | ------------------------------------------------ |
| `SPC l s b` | send buffer and keep code buffer focused         |
| `SPC l s l` | send line and keep code buffer focused           |
| `SPC l s s` | send selection text and keep code buffer focused |

![nimrepl](https://user-images.githubusercontent.com/13142418/43988888-96d64aae-9d71-11e8-8117-664e6e4fb886.gif)
