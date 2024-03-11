# Web Scrape address & parse address into structured data
## method one:
    step 1: search [university name] + [dorimtory keywords] in google and pull the URL from first page results
    step 2: scrape and parse the address from URL in step 1
## method two:
    search [university name] + [dorimtory keywords] in google map and parse the address from google map result page

## Address parsing method:
    use regular expression to extract potential address text and use the package usaaddress to parse it into structed dataset
    