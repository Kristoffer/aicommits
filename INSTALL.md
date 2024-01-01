### Install test-kristoffer-aicommits (this seems not to work for node 21.5 - works with 18.4)
npm install -g test-kristoffer-aicommits

### Install from git repository
npm install -g ./

### set openai key
aicommits config set OPENAI_KEY=<your token>

### to deploy
npm adduser
npm publish https://github.com/Kristoffer/aicommits.git
