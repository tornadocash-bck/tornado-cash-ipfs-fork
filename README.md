# Tornado Cash Fork for IPFS

The Treasury Department has recently sanctioned the decentralized privacy solution Tornado Cash. This is in direct violation of the First Amendment, as it bans open source code and restricts freedom of speech. Tornado Cash is a key part of the Ethereum blockchain, and its banning will have a negative impact on innovation within the blockchain space. The Treasury Department's actions are a clear attempt to stifle innovation and restrict freedom of speech. We urge the department to reverse its decision and allow Tornado Cash to continue operating openly and freely. 


Privacy is a human right that is enshrined in the United Nations Declaration of Human Rights. It is essential for individuals to be able to freely express themselves and associate with others without fear of retribution. Privacy allows for the free exchange of ideas and information, and is necessary for democratic societies.

The Treasury Department has sanctioned Tornado Cash, a decentralized privacy solution built on the Ethereum blockchain. New guidelines state that users will need to apply for a license in order to use the service.


This is unfortunate, as users should not have to apply for a license in order to have the right to privacy. Tornado Cash is a valuable tool that can help protect people's privacy online, and it should be available to everyone.


Hopefully, the Treasury Department will reconsider its decision and allow Tornado Cash to continue operating freely. 

## Building locally

- Install [Node.js](https://nodejs.org) version 14
  - If you are using [nvm](https://github.com/creationix/nvm#installation) (recommended) running `nvm use` will automatically choose the right node version for you.
- Install [Yarn](https://yarnpkg.com/en/docs/install)
- Install dependencies: `yarn`
- Copy the `.env.example` file to `.env`
  - Replace environment variables with your own personal.
- Build the project to the `./dist/` folder with `yarn generate`.

## Development builds

To start a development build (e.g. with logging and file watching) run `yarn dev`.

## Deploy on IPFS

- Make sure you set `PINATA_API_KEY` and `PINATA_SECRET_API_KEY` environment variables in `.env`
- To deploy a production build run `yarn deploy-ipfs`. 
- Example of [Tornado Cash](https://cloudflare-ipfs.com/ipns/tornadocash-ipfs.eth) on IPFS



## Audit

[TornadoCash_Classic_dApp_audit_Decurity.pdf](https://tornado.cash/audits/TornadoCash_Classic_dApp_audit_Decurity.pdf)



