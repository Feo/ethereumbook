```beam.assembly
function () public payable {}
```

payable function is a so-called fallback or default function which is not familiar with other language.It is called if the transaction that triggered  the contract didn’t name any of the declared functions in the contract, or  any function at all, or didn’t contain data. It should be public. Because it is use to receive ether. Every contract should have one.