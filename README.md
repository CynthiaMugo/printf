Printf collaboration between Cynthia Mugo and Elias Macharia.


 _PRINTF.C  

Contains:
	

	 _printf which is the main printing fxn. 
	print_buffer - prints the content of the buffer


 FUNCTIONS.C 

Contains:

	print_char for printing characters
	print_string for printing strings
	print_percent for printing a percent
	print_int for printing integers
	print_binary for printing unsigned numbers


 FUNCTIONS1.C 

Contains:

	print_unsigned for printing unsigned numbers
	print_octal for printing unsigned numbers in octal
	print_hexadecimal for printing unsigned number in hex
	print_hexa_upper prints unsigned number in upper hex
	print_hexa prints hex numbers in lower and uppercase


 FUNCTIONS2.C 

Contains:

	print_pointer for printing the value of pointers' variables
	print_non_printable for printing ASCII code for non-printable chars
	print_reverse for printing reversed string
	print_rot13string for printing a string in rot13

 GET_FLAGS.C 

Contains:

	get_flags which calculates active flags
	

 GET_PRECISION.C 

Contains:

	get_precision for calculating precision for printing

 GET_SIZE.C 

Contains: 

	get_size for calculating size to cast to the argument

 GET_WIDTH.C 

Contains:

	get_width calculating width of printing

 HANDLE_PRINT.C 

Contains:

	handle_print prints the argument based on its type

 MAIN.H 

Contains:

	prototypes for all functions
	MACROS are defined
	structs are defined
	c libraries are called

 UTILS.C 

Contains:

	is_printable which evaluates whether a char is printable
	append_hexa_code which includes the ASCII code in hexa form to the buffer
	is_digit to verify if a char is a digit
	convert_size_number to cast a number to the specified size
	covert_size_unsigned to cast unsigned number to the specified size

 WRITE_HANDLERS.C 

Contains:

	handle_write_char which prints a string
	write_number which prints a no as string
	write_num for writing a num using a buffer
	write_unsgnd for writing an unsigned int
	write_pointer for writing memory address


