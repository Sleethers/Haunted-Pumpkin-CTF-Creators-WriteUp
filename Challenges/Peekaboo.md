
# Resources

```
WeirdlyLargeFile.png
```

Flag Hints

```
hpCTF{<ZIP>_<City>_<Street>_<Number>}
```

# Steps

Analyze the metadata of the file

![](/PNG/Pasted%20image%2020251022204151.png)

Use binwalk or something similar to check that there are actually two pngs inside this one file

![](/PNG/Pasted%20image%2020251022204452.png)

Or use unroll.img

![](/PNG/Pasted%20image%2020251022204550.png)

Find the barcode

![](/PNG/Pasted%20image%2020251022204635.png)

Scan the bar code

```
https://online-barcode-reader.inliteresearch.com/
```

![](/PNG/Pasted%20image%2020251022204700.png)
![](/PNG/Pasted%20image%2020251022204728.png)

```
CHE-274.572.141
```

Look up the newly found number and find pekabo on moneyhouse

![](/PNG/Pasted%20image%2020251022204823.png)

# !!! DONE !!!
