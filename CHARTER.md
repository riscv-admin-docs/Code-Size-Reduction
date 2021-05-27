### Charter

The code size reduction TG will propose one ISA extension to reduce code size. The primary target is embedded cores as they often have very constrained memory sizes and so code size reduction is most important for cost reduction. A subset of the ISA extension will also be applied to larger, higher performance cores but the TG will not do any work on competitive analysis for anything other than embedded cores.

### Output

The output will be at one ISA extension to reduce code size with toolchain support in both GCC and LLVM. Embedded cores will benefit from the whole ISA extension, higher performance cores will also benefit from a subset.

Proposals which have been analysed but not accepted in the ISA proposal will be archived on Github, with reasons why they weren’t accepted.

Additional output from the TG could include toolchain recommendations (e.g. improved –msave-restore) and coding recommendations to improve code size.

### Initial Roadmap

- Build a benchmark / application suite for measuring code size
- Collect existing proposals for code size reduction ISA extensions
- Add a new code size reduction ISA extension using encodings in line with the Instruction Encoding Allocation Policy, to address cases where the toolchain improvements alone cannot solve the code size problem

### Other TGs

The B-extension, Zfinx, EABI, Fast Interrupts and the J-extension have related work, but other tasks groups may as well so this is not a complete list.
