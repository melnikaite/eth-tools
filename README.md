### Demo

https://eth-tools.s3.eu-central-1.amazonaws.com/decodeEvent.html

https://eth-tools.s3.eu-central-1.amazonaws.com/decodeTransaction.html

https://eth-tools.s3.eu-central-1.amazonaws.com/generateTimestamp.html

https://eth-tools.s3.eu-central-1.amazonaws.com/encodeABI.html

https://eth-tools.s3.eu-central-1.amazonaws.com/createAccount.html

https://eth-tools.s3.eu-central-1.amazonaws.com/replaceTransaction.html

### Deploy

`aws s3 sync . s3://eth-tools --acl public-read --exclude "*" --include "*.html" --include "*.js"`
