# Configuring Remix Legacy

**To use this, simply open the GitHub Pages GUI as described in the description of this repo.**

Since the maintainers of the well-known [Remix IDE](https://remix.ethereum.org/) are focused on providing Remix features that are build for the public Ethereum chain ( Ethereum 2.0 ), using the on-line version of Remix in conjunction with the Legacy Geth node ( v1.10.14 ) seems to work in a sub-optimal way. This is why it is recommended to use the legacy Remix locally.

* Head on to the github repo where Remix is located:

https://github.com/ethereum/remix-live

* Change the branch to:

```
0.10.10
```

* Download the zip file:

```sh
wget https://github.com/ethereum/remix-live/raw/refs/heads/0.10.10/remix-da955628a.zip
```

* Unzip it and remove the the archive after:

```sh
unzip *.zip && rm *.zip
```

* To run the off-line copy just start a web server in the directory where you unzipped it:

```
python -m http.server 8000
```

* Open your browser and go to:

http://localhost:8000

---
