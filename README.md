Use linux operating system

II. Compile and run the program using NASM.

    Save the program in a file, e.g., hello.asm.

    Compile the program using NASM:
    bash
      nasm -f elf32 hello.asm -o hello.o

    Link the object file to create an executable:
    bash
        ld -m elf_i386 hello.o -o hello

    Run the executable:
    bash
        ./hello
       output:
       Hello, World!
