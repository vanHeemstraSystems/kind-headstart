# 200 - Installation of KinD on MacOS

## On MacOS via Homebrew:

```
brew install kind
```

## On MacOS via MacPorts:

```
sudo port selfupdate && sudo port install kind
```

## On MacOS via Bash:

```
curl -Lo ./kind https://kind.sigs.k8s.io/dl/v0.11.1/kind-darwin-amd64
chmod +x ./kind
mv ./kind /some-dir-in-your-PATH/kind
```
