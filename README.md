# Swisstronik Tesnet Techinal Task 6 (Deploy Proxy)

## Steps

### 1. Clone Repository

```bash
git clone https://github.com/tin0503/swisstronik-task6.git
```

```bash
cd swisstronik-task6
```

### 2. Install Dependency

```bash
npm install
```

### 3. Set .env File

create .env file in root project

```bash
touch .env
```

add this to your .env file

```bash
PRIVATE_KEY="your private key"
```

### 4. Compile Smart Contract

```bash
npm run compile
```

### 5. Deploy Smart Contract

```bash
npm run deploy
```

### 6. Initialize Owner

```bash
npm run initialize
```

### 7. Add Issuer

```bash
npm run add-issuers
```

### 8. Get Issuers list

```bash
npm run list-issuers
```

### 9. Upgrade Smart Contract

```bash
npm run upgrade
```

### 10. Finsihed

- Open the deployed-adddress.ts file (location in utils folder)
- Select SWTRProxy
- Copy the address and paste the address into testnet dashboard - line 1
- Open tx-hash.txt file (location in utils folder)
- Copy the transaction hash link and paste the address into testnet dashboard - line 3
- push this project to your github and paste your repository link in testnet dashboard - line 2

Ignore this!!!

```
SWTRProxy = '0xea65D3f80d2253293a64e2f8DdF4CEC401823053'
ProxyAdmin = '0x6a0baE5CF96d14e39FA9F5AdB4fadABb55B22E17'
SWTRImplementation = '0xE4e93a474734E22A4f660EF1fE7aC3fc096E856c'
```