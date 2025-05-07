# CLion Error / Warning Display Issue reproducer
Demonstrate issue where compiler errors and warnings are not shown in problems view or inline.

# Reproduction steps
1. Import project into CLion.
2. Ensure Meson project loads (click Reload Meson project)
3. Configure clang or gcc based toolchain.
4. Build via Meson (click hammer icon in top right)
5. View "Messages" window to see compiler outputs an error (due to implicit conversion)
6. View "Problems" window and see it is blank.
7. View "main.cpp" and see compiler errors aren't shown inline.

Demonstration video:
https://drive.google.com/file/d/1AjpANbHYshYF5tR8KDtVQn9shEdfuFNO/view?usp=sharing
