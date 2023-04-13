# DocuMemo (Debian)

## SetUp: https://github.com/yforku/docusaurus/ (CHECKED)

## Install debian package nodejs and npm:
```
sudo aptitude install nodejs npm -y

```

## Check if NODE version > v.8
```
node -v

```

## Yarn is in package "cmdtest"
```
dpkg-query --listfiles cmdtest | grep yarn
sudo aptitude install cmdtest -y

```



