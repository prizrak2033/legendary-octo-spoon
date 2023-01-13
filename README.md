# legendary-octo-spoon
Generate valid IPs by country.
Generates all possible public IPs and writes them into a file or prints them in the stdout written in go  
⚠️Warning⚠️ Output file will be 52Gb!
## Usage
```
go build
./generator [flags]
```
### Flags
`-w={filename}`  Outputs to filename provided, If no name is given it won't write to a file. `Default: ""`  
`-o` Outputs generated IPs to stdout separated with newline. `Default: False`  
`-t` Prints time it took to generate IPs once finished. `Default: True`  
