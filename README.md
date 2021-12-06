npm install truffle -g
npm install -g ganache-cli
npm install sol-merger -g
npm i @uniswap/v2-core
npm i @uniswap/sdk

sol-merger contracts/PancakeFactory.sol ./build
sol-merger contracts/PancakePair.sol ./build
sol-merger contracts/PancakeERC20.sol ./build