### Scripts
Addition for 2020 event. 

path|usage
---|---
scripts/fetchers/cmd-inputs | go run scripts/fetches/cmd-inputs/inputs.go <br>-cookie flag for session cookie from AOC website (required to be set via flag OR on ENV) <br> -day flag defaults to today<br>-year flag defaults to current year
scripts/fetchers/cmd-prompts | go run scripts/fetches/cmd-prompts/prompts.go<br>same flags as inputs script
scripts/template/template.go | go run scripts/template/template.go<br> same -day and -year flags, quickly templates up files for the given day's solutions.<br> Note that functions can be run using `go test -run PartX .` or via `go run main.go -part <1 or 2>`