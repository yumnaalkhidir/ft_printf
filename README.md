# ft_printf

A reimplementation of the standard `printf` function, supporting the conversions `%c %s %d %i %u %x %X %p %%`.

## Concepts covered
- Variadic functions (`va_list`, `va_arg`)
- Format-string parsing and per-specifier dispatch
- Building a small static library (`libftprintf.a`)

## Build & run
```sh
make        # builds libftprintf.a
make clean  # remove object files
make fclean # remove object files and the library
```
Link `libftprintf.a` and include `ft_printf.h` in your own project to use `ft_printf`.

---
Part of the 42 School curriculum.
