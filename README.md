# Getting Started

### 1. Install dependencies

```shell
yarn
```

### 2. Generate types

```shell
yarn codegen
```

### 3. Build the project

```shell
yarn build
```

### 4. Start Indexer Manager
```shell
yarn start:manager

```

### 5. Deploy the project

```shell
yarn deploy
```

### 6. After indexer starting, run GraphQL query service
```shell
yarn start:query
```

### 7. Example query

```shell
query{
  transfers(first: 3){
    nodes{
      id
      amount
      blockNumber
      to{
        id
      }
      }
    }
  }
```

