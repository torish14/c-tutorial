# Basic C lang Command

## Build(analyze statically + compile + link) and Run machine language

- `gcc file_name.c -o file_name`
- `./file_name`

## Output normal assembly language to compile

- `gcc -S file_name.c`

## Output optimized assembly language to compile

- `gcc -S -O3 file_name.c`


## Build and Research the executable file(header + executable program) to disassemble

- `gcc file_name.c -o file_name`
- `objdump -D ./file_name`
