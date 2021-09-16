Task: Design and add Stock Model.

- Attributes name, ticker-symbol and price.
- Automate looking up stock(currently only possible through rails console)
- Automate API key insertion(instead to having to key it in everytime we look up a stock)
- This will expose us to secure credentials in Rails apps:
    credentials.yml.enc (encryted file)
    master.key (key to decryt credentials file)