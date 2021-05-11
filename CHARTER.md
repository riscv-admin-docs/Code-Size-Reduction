### Charter

The code size reduction TG will develop a holistic solution to reducing code size, covering different profiles to be competitive with other core implementations of other architectures of a similar class.

Priority is given to small embedded cores which often have very constrained memory sizes and so code size reduction is most important for cost reduction. Larger/higher performance cores will also benefit from reduced code size.

### Output

The output will be improved toolchain technology to reduce code size, and also at least one ISA extension to reduce code size with toolchain support in both GCC and LLVM. If any part of any future ISA extension risks complicating the design of high performance cores, then those instructions will be in a different subset so that they can be excluded. Therefore high performance cores will also benefit from improved toolchain technology and also an ISA extension.

Output from the TG could include coding recommendations to improve code size.

### Initial Roadmap

- Build a benchmark / application suite for measuring code size

- Collect existing proposals for code size reduction ISA extensions

- Improve compiler support in known weak areas, such as function call prologue/epilogue

- Add a new code size reduction ISA extension using encodings in line with the Instruction Encoding Allocation Policy, to address cases where the toolchain improvements alone cannot solve the code size problem

### Other TGs

This TG will handle all aspects of making RISC-V code-size competitive.  CMO, B-extension, Zfinx, EABI, Fast Interrupts and the J-extension all already have related work, but other tasks groups may as well so this is not a complete list.

New TGs may be spawned as required to complete the objective.

The TG will report to the software standing committee, and will work with the unprivileged standing committee to ratify any ISA extensions.
