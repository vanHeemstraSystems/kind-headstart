# 200 - Installation of KinD on MacOS

## On macOS via Homebrew:

```
brew install kind
COPY
brew install kind
```

## On macOS via MacPorts:

```
sudo port selfupdate && sudo port install kind
COPY
sudo port selfupdate && sudo port install kind
```

## On macOS via Bash:

```
curl -Lo ./kind https://kind.sigs.k8s.io/dl/v0.11.1/kind-darwin-amd64
chmod +x ./kind
mv ./kind /some-dir-in-your-PATH/kind
COPY
curl -Lo ./kind https://kind.sigs.k8s.io/dl/v0.11.1/kind-darwin-amd64
chmod +x ./kind
mv ./kind /some-dir-in-your-PATH/kind
```
