Here you can find some code examples showing how *easy* integrating the [Oraclize Ethereum API](https://github.com/oraclize/ethereum-api) is.

Thanks to our [Ethereum API helpers](https://github.com/oraclize/ethereum-api) using Oraclize in your Solidity/Serpent code is very easy.

In Solidity it is as simple as inheriting the `usingOraclize` contract: this will provide you some functions, like `oraclize_query`, which make it trivial to leverage our technology straight away.

If you are using Serpent just import `oraclizeAPI.se` and enjoy the same Oraclize helper functions via macros!
###### IMPORTANT NOTICE:

It is highly recommended to avoid using serpent, especially in production. The examples have been left for historical reasons but support for it is no longer maintained as serpent is considered outdated and audits have shown it to be flawed.


----------


More @ [docs.oraclize.it](http://docs.oraclize.it)

Gitter chan @
[![Join the chat at https://gitter.im/oraclize/ethereum-api](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/oraclize/ethereum-api)