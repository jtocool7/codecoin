const crypto = require("crypto"), SHA256 = message => crypto.createHash('sha256').update(message).digest('hex');


class block {

    constructor(timestamp="", data=[]){
        this.timestamp = timestamp;
        this.data = data;
        this.hash = this.getHash();
        this.prevHash = "";
    }

    getHash(){
        return SHA256(this.prevHash + this.timestamp + JSON.stringify(this.data));
    }

}


class blockchain {
    constructor(){
        this.chain = [new block()];
    }

    getlastblock(){
        if(this.chain.length > 0){
            return this.chain[this.chain.length - 1];
        }
    }

    addBlock(newBlock){
        if(this.isValid()){
            newBlock.prevHash = newBlock.prevHash = this.getlastblock().hash;
            newBlock.hash = newBlock.getHash();
            newBlock.timestamp = Date.now().toString();
            this.chain.push(newBlock);
        }else{
            console.log("invalid block")
        }
    }

    isValid(){
  
        for(let i = 1; i < this.chain.length; i++){
            const currentBlock = this.chain[i];
            const prevBlock = this.chain[i-1];
            if(currentBlock.prevHash !== prevBlock.hash){
                console.log("prevhashbad")
                return false;
            }

        }
        return true;
    }

    }


const mysterCoin = new blockchain();
 mysterCoin.addBlock(new block(Date.now().toString, {from: "codeMyster", to: "fireship.io", ammount: 5}));
 mysterCoin.addBlock(new block(Date.now().toString, {from: "codeMyster", to: "Jeff Delany", ammount: 90}));
 mysterCoin.addBlock(new block(Date.now().toString, {from: "codeMyster", to: "Code With Mosh", ammount: 5}));
console.log(mysterCoin.chain);


