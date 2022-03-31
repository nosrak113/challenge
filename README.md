# Squads Challenge
Thanks for you interest in joining the Squads dev team!
V2UndmUgaGlkZGVuIGEgMTIgY2hhcmFjdGVyIHBocmFzZSBpbiB0aGUgYWNjb3VudCA4QUd2dHgyS2FFODI5TW56d1VTVXFCQmtLRlZIRWpyUWV6R1lhY1U4Vmo4WSBTb2xhbmEncyBkZXZuZXQuIENhbiB5b3UgdGVsbCB1cyB3aGF0IHRoZSBwaHJhc2UgaXM/

# Solution
1. Convert to UTF from base64, https://www.base64decode.org/ , "We've hidden a 12 character phrase in the account 8AGvtx2KaE829MnzwUSUqBBkKFVHEjrQezGYacU8Vj8Y Solana's devnet. Can you tell us what the phrase is?" 
2. View the wallet, https://solanabeach.io/address/8AGvtx2KaE829MnzwUSUqBBkKFVHEjrQezGYacU8Vj8Y/transactions?cluster=devnet
3. View the only transaction, https://solanabeach.io/transaction/uCS68Q7kzHhnqnGVuAjNNhxEL7fvbdMcEUnCdouXff5Wkgpoby3Fo8EQ6Le8LBJTVapCG9ZRDMBPs7WFE9KMSzM?cluster=devnet
4. View the Program output
```
Program 11111111111111111111111111111111 invoke [1]

Program 11111111111111111111111111111111 success

Program FCD9btrGUSm4XNiwnCxEXFvCNfH35qjjqfUVjgX5x5Nm invoke [1]

Program log: INSTRUCTION DATA [1]

Program log: Interview secret account AccountInfo { key: 8AGvtx2KaE829MnzwUSUqBBkKFVHEjrQezGYacU8Vj8Y, owner: FCD9btrGUSm4XNiwnCxEXFvCNfH35qjjqfUVjgX5x5Nm, is_signer: false, is_writable: true, executable: false, rent_epoch: 0, lamports: 1002240, data.len: 16, data: 00000000000000000000000000000000, .. }

Program log: Properly encoded string AccountInfo { key: 8AGvtx2KaE829MnzwUSUqBBkKFVHEjrQezGYacU8Vj8Y, owner: FCD9btrGUSm4XNiwnCxEXFvCNfH35qjjqfUVjgX5x5Nm, is_signer: false, is_writable: true, executable: false, rent_epoch: 0, lamports: 1002240, data.len: 16, data: 0c00000073517541645363306433725a, .. }

Program FCD9btrGUSm4XNiwnCxEXFvCNfH35qjjqfUVjgX5x5Nm consumed 63055 of 200000 compute units

Program FCD9btrGUSm4XNiwnCxEXFvCNfH35qjjqfUVjgX5x5Nm success
```
5. pull out the data from the 2nd log `0c00000073517541645363306433725a`
6. convert the hex to ascii, `sQuAdSc0d3rZ`
