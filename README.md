<h1>ft_printf</h1>
<h2>Project description</h2>
<div>
<!--  <a href="https://github.com/JaeSeoKim/badge42">
    <img align="center" src="https://badge42.herokuapp.com/api/project/samoreno/ft_printf"/>
  </a> -->
  <p>This is the second project at 42 Madrid. The aim is to learn about variadic functions in C. The goal is to recode the printf() function from libc with the following prototype <b>int ft_printf(const char *, ...);</b><br/>
  The requirements are:
  <ul>
    <li>Don’t implement the buffer management of the original printf()</li>
    <li>The function has to handle the following conversions: cspdiuxX%</li>
    <li>The aim is to create a libftprintf.a file</li>
  </ul>
  </p>
  <p>
  The detailed conversions are:
  <ul>
    <li>%c Prints a single character</li>
    <li>%s Prints a string (as defined by the common C convention)</li>
    <li>%p The void * pointer argument has to be printed in hexadecimal format</li>
    <li>%d Prints a decimal (base 10) number</li>
    <li>%i Prints an integer in base 10</li>
    <li>%u Prints an unsigned decimal (base 10) number</li>
    <li>%x Prints a number in hexadecimal (base 16) lowercase format</li>
    <li>%X Prints a number in hexadecimal (base 16) uppercase format</li>
    <li>%% Prints a percent sign</li>
  </ul>
  </p>
</div>
<h2>Usage</h2>
<div>
    <p>
        With the Makefile you can compile directly. The rules that it allows are:
        <ul>
         <li>Make: it compiles directly</li>
         <li>Make re: if the project is already compiled, it does it again</li>
         <li>Make clean. Deletes all .o files but the executable remains</li>
         <li>make fclean: deletes all .o files and the executable</li>
    </ul>
    </p>
</div>
