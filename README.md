# locale-fonts

## Abstract

```font-family: Helvetica, 'Hiragino Sans GB', 'Heiti SC', ..., sans-serif;
```

Got tired for this? Let it be solved more easily. Simply write:

```font-family: Helvetica, zh-hans-sans, ja-sans;
```

... So what is `zh-hans-sans`?

```@font-face {
	font-family: 'zh-hans-sans';
	font-style: normal;
	font-weight: 300;
	src:	local('NotoSansCJKsc-Light'),
			local('SourceHanSansCN-Light'),
			local('HiraginoSansGB-W3'),
			local('STHeitiSC-Light'),
			local('Microsoft YaHei');
}
```

## Contributing

Users of different platforms and languages are welcomed to add fonts that your platforms have.

## Copyright

This project is released and contributed under **MIT License**.