# arrow-convert-example
A really simple example of using arrow_convert to write structs to parquet, and to then read parquet back to structs.

Currently, the `main` function writes out hardcoded data to a parquet file of your choosing. The file will be in the project root. There is then a test that will attempt to read a file (hardcoded to "test.parquet") and convert it to the same structure vec that the `main` function used, and assert that they are equal.

This isn't pretty, and I'm not quite sure that I will improve it at this point. This was used to figure out how to write complex structs to parquet and then to be able read them back into the same structs.
