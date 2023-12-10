<h1 align="center"><b>DEMO</b></h1>

This is the Aries Framework Javascript demo. Walk through the AFJ flow yourself together with agents Alice and Faber.

Alice, a former student of Faber College, connects with the College, is issued a credential about her degree and then is asked by the College for a proof.

## Features

- ✅ Creating a connection
- ✅ Offering a credential
- ✅ Requesting a proof
- ✅ Sending basic messages

### Usage

```sh
nvm use 18
npm install
```

on one terminal:

```sh
npm run alice
```

on another terminal

```sh
npm run faber
```

To set up a connection:

- Select 'receive connection invitation' in Alice and 'create connection invitation' in Faber
- Faber will print a invitation link which you then copy and paste to Alice
- You have now set up a connection!

To offer a credential:

- Select 'offer credential' in Faber
- Faber will start with registering a schema and the credential definition accordingly
- You have now send a credential offer to Alice!
- Go to Alice to accept the incoming credential offer by selecting 'yes'.

To request a proof:

- Select 'request proof' in Faber
- Faber will create a new proof attribute and will then send a proof request to Alice!
- Go to Alice to accept the incoming proof request

To send a basic message:

- Select 'send message' in either one of the Agents
- Type your message and press enter
- Message sent!

Exit:

- Select 'exit' to shutdown the agent.

Restart:

- Select 'restart', to shutdown the current agent and start a new one
# hyperledger_aries_working_demo
