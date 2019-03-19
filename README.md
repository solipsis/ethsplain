# ethsplain
ethdenver2019 Hackathon project

Tool for interactively exploring raw Ethereum transactions. Supports variable levels of parsing granularity

## small tx with simple parsing
![simple tx](/images/simple.png?raw=true "")
Highlighting on mouseover
![simple tx highlight](/images/simple-mouseover.png?raw=true "")

## tx with verbose rlp parsing
![verbose](/images/verbose.png?raw=true "")
![verbose continued](/images/verbose-continued.png?raw=true "")






Run the server with
```
go build
./ethsplain
```

run the front-end with
```
yarn dev
```
