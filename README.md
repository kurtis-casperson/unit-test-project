# unit-test-project

Create a jest test to test that the ATM is able to correctly read each account, and perform the correct deposit and withdraw functions.

This is good use for a jest test because it is performing a repetative task that is slow to produce (creating files)


Mock the read Filesystem to test that each account has a balance and name.

Create an Account helper function to be able to mock a balance for each account, since balance is private.

There are three tests.  Corect deposits, corect withdraw, and testing that an error throws when the withdraw amount is larger than the account balance.
