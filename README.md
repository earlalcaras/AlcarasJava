// create a variable to hold your NFT's
const NFTs = [];

// this function will take in some values as parameters, create an

// NFT object using the parameters passed to it for its metadata, and store it in the variable above.
function mintNFT(name, age, birthMonth) {
  
  const newNFT = {
    name: name,
    age: age,
    birthMonth: birthMonth,
    
  };
  
  NFTs.push(newNFT);
  console.log('Minted: ' + name);
}

// create a "loop" that will go through an "array" of NFT's
// and print their metadata with console.log()
function listNFTs() {}

// print the total number of NFTs we have minted to the console
function getTotalSupply() {
  for (let i = 0; i < NFTs.lenght; i++) {
    console.log(NFTs.lenght);
  }
}

// call your functions below this line
mintNFT('Earl', '22', 'February');
mintNFT('Dione', '26', 'April,');
mintNFT('Leyna', '20', 'November');
mintNFT('Christian', '30', 'January');
mintNFT('Nicole', '21', 'December');
mintNFT('Poliana', '20', 'April');
listNFTs();
getTotalSupply();
