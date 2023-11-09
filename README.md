# lukso-foundry    
     

A lightweight library that makes it easier to work with LSP7 and LSP8 smart contracts in Foundry.    
    
Install:    
```forge install useloopso/lukso-foundry```    
     
Create a ```remappings.txt``` file in your project root, and add the following line:     
```@lukso/=lib/lukso-foundry/src/```
     

Now you can use the library like this:     
```import "@lukso/LSP7/LSP7DigitalAsset.sol";```     