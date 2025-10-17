# HelloWorld #

A dummy repository on GitHub for testing.

Not supposed to actually do anything.

## Badges ##

![Static Badge](https://img.shields.io/badge/any_text-you_like-blue "ALT TEXT")

![Static Badge](https://img.shields.io/badge/MCU-PIC32-green "MCU:PIC32")

![Static Badge](https://img.shields.io/badge/CPU-MC68000-blue "CPU:MC68000")

## Mermaid ##

```mermaid
  graph TD;
      A-->B;
      A-->C;
      B-->D;
      C-->D;
      D-->A;
```

Text text text text.

```mermaid
stateDiagram-v2
    [*] --> Still
    Still --> [*]

    Still --> Moving
    Moving --> Still
    Moving --> Crash
    Crash --> [*]
 ```
 
 Text text text text.
 
 ```mermaid
stateDiagram-v2
    [*] --> Idle

    Idle --> Busy: enter
    Busy --> Busy
    Busy --> Idle: exit
 ```
 
 Text text text text.
 
## WaveDrom ##
 
Example waveform using WaveDrom:

![6502 timing diagram](https://svg.wavedrom.com/github/anachrocomputer/HelloWorld/develop/timing.json5))

End of waveform example.
