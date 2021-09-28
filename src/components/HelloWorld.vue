<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
     An NFT is a unit of data stored on a digital ledger, called a blockchain, which can be sold and traded. 
     The NFT can be associated with a particular digital or physical asset (such as a file or a physical object) and a license to use the asset for a specified purpose.
     NFTs (and the associated license to use, copy or display the underlying asset) can be traded and sold on digital markets.
     NFTs function like cryptographic tokens, but, unlike cryptocurrencies like Bitcoin, NFTs are not mutually interchangeable, hence not fungible. 
     While all bitcoins are equal, each NFT may represent a different underlying asset and thus have a different value.
     NFTs are created when blockchains string records of cryptographic hash, a set of characters identifying a set of data, onto previous records therefore creating a chain of identifiable data blocks.
     This cryptographic transaction process ensures the authentication of each digital file by providing a digital signature that is used to track NFT ownership.
     However, data links that point to details like where the art is stored can die.
    </p>
   
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
