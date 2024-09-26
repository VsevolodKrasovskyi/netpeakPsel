# NetpeakPsel
— is a tool for extracting external links from specific sections of web pages such as header, footer, nav and aside.

## Install

You can install the package via `pip`:

## Как пользовать? 

## Initialising components
request_handler = netpeakPsel.RequestHandler(delay=1) #default delay 1s
cache_manager = netpeakPsel.CacheManager(cache_file='cache.txt') #name file 'cache.txt'
crawler = netpeakPsel.Crawler(request_handler, cache_manager)

# Parsing a single URL
crawler.parse_url('example.com')

# Parsing a list of domains from a file
crawler.parse_list_domain('domains.txt')
