Questions: 
1.What is the knowledge point of the test? Where is the official document to the knowledge point?
2.Why the test failed at first?
3.Why you corrected the test that way?
4.Do you have further questions on this knowledge point?

-- BooleanOperatorsTest --
TEST1 - should_perform_logical_boolean_operations
1. to check whether youre understanding logical operators is right. official document : https://www.dummies.com/programming/java/logical-operators-in-java/
2. wrong answers in the expected out of logical operands
3. to match the expected output to the actual true result
4. none

TEST2 - should_do_bitwise_and_boolean_operation
1. To check how will you apply bitwise operation in hex value and know to convert values to apply logical operands https://www.programiz.com/c-programming/bitwise-operators
2. wrong answer due to applying bitwise operation in 2 binaries -> hex was converted to binary to answer easily the value
3. to correct the expected result base on the calculated bitwise operation
4. None

TEST3 - should_do_bitwise_or_boolean_operation
1. To check how will you apply bitwise operation in hex value and know to convert values to apply logical operands https://www.programiz.com/c-programming/bitwise-operators
2. wrong answer due to applying or bitwise operation in 2 binaries -> hex was converted to binary to answer easily the value
3. to correct the expected result base on the calculated bitwise operation
4. None

TEST4 - should_do_bitwise_not_operation
1. to compute the value of the converted value of hex to binary and adding not that will reverse the value of the answer https://stackoverflow.com/questions/2513525/bitwise-not-operator
2. wrong answer due to wrong conversion of hex -> decimal value and didnt get the application of not operator
3. i can sense that by solving the real answer, i can understand how to apply bitwise not operator in the value given decimal.
4. None

-- CharTypeTest --
TEST 1 should_describe_escaped_chars
1. to check whether we know what is escaped characters that is used in text https://stackoverflow.com/questions/1367322/what-are-all-the-escape-characters
2. wrong answer due to some escaped characters that didn't know its real value
3. tried to correct the answer base from the understanding of what escaped character is
4. None

-- FloatingTypeTest --
TEST 1 should_not_get_rounded_result_if_convert_floating_number_to_integer
1. to know how to convert float to integer without rounding https://stackoverflow.com/questions/17061375/converting-float-to-int-without-rounding
2. didn't know how to convert float to int without rounding
3. to pass the test and to test whether the real value is correct to the expected value
4. None

TEST 2 should_judge_special_double_cases
1. to know the difference of finite and infinite and not a number https://stackoverflow.com/questions/8311604/check-if-a-double-is-infinite-in-java/8311657 | https://www.geeksforgeeks.org/double-isnan-method-in-java-with-examples/
2. didn't what is finite & inifinity and not a number
3. to check and validate is double is infinite and not a number
4. None

TEST 3 should_not_round_number_when_convert_to_integer
1. to know how to convert float to integer without rounding https://stackoverflow.com/questions/17061375/converting-float-to-int-without-rounding
2. didn't know how to convert float to int without rounding
3. to pass the test and to test whether the real value is correct to the expected value
4. None

TEST 4 should_round_number
1. to know if the value will be rounded up and converted to long
2. no test error happened
3. no correction happened since i only run the test once
4. None

-- IntegerTypeTest --
TEST 1 should_get_range_of_primitive_int_type
1. to know a property that identify max and min limit of integer
2. no test error happened
3. no correction happened since i only run the test once
4. None

TEST 2 should_get_range_of_primitive_short_type
1. to know a property that identify max and min limit of Short
2. no test error happened
3. no correction happened since i only run the test once
4. None

TEST 3 should_get_range_of_primitive_long_type
1. to know a property that identify max and min limit of Long
2. no test error happened
3. no correction happened since i only run the test once
4. None

TEST 4 should_get_range_of_primitive_byte_type
1. to know a property that identify max and min limit of Byte
2. no test error happened
3. no correction happened since i only run the test once
4. None

TEST 5 should_overflow_silently
1. to know the logic of overflow silently for Integer Type
2. didn't know that the logic of it is resets to the minimum value of Integer
3. correct and set the expected result to min value using property
4. None

TEST 6 should_underflow_silently
1. to know the logic of underflow silently for Integer Type
2. no test error happened
3. no correction happened because the solutions is basically the invert solution for overflow silent 
4. None

TEST 7 should_throw_exception_when_overflow  && TEST 8 just_prevent_lazy_implementation
1. to know how to create checking when overflowing happen and return value if no overflow happens
2. error happened since i have wrong implementation of throw exception
3. replace throw exception to correct the expected result
4. None

TEST 9 should_take_care_of_number_type_when_doing_calculation
1. to know what is delta in assert and how double cast value to given result https://stackoverflow.com/questions/33274030/why-is-assertequalsdouble-double-deprecated-in-junit/33274179#33274179
2. error happened when conversion of operation is not compatible to primitive double
3. corrected the test to the right result
4. None

TEST 10 should_truncate_number_when_casting
1. to know the 16bit conversion of 32bit value
2. didn't know how to convert 32 to 16 bit value
3. calculated and test the value if it will be correct
4. None

TEST 11 should_increment
1. to know if the value will not increment when increment happens on the right side of the value
2. error happened because i taught value would be incremented
3. i test some values if value will not increment when increment is put on the right side of the value
4. None

TEST 12 should_increment_2
1. to know if the value will increment when increment happens on the left side of the value
2. no test error happened
3. no correction happened because i run the test once, understanding the failures in test 11
4. None