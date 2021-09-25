# archiveweb
Fetch all the URLs that Google and Wayback Machine knows of the target except:
- for image, css and other static files
- urls with same path but parameter value difference

Usage:

```
▶ git clone https://github.com/g0ttfrid/archiveweb && cd archiveweb

▶ pip3 install -r requirements.txt

▶ python3 archiveweb.py -t example.com -o output-example.txt
```


### Inspired by

[dorks-eye](https://github.com/BullsEye0/dorks-eye)\
[waybackurls](https://github.com/tomnomnom/waybackurls)\
[uro](https://github.com/s0md3v/uro)
