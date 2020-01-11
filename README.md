# easy_test_fraig
very simple test case of fraig's basic command

Put simXX.aag , optXX.aag, strash.aag, opt66.aag, opt67.aag, opt68.aag and your ./fraig in the same folder

## how to use ##
./fraig -f CheckOp > myOp
./fraig -f CheckOp > ReOp
diff myOp ./ref/ReOp
