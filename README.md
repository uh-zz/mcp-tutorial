# mcp-tutorial

> [!WARNING]
> ここで扱っている内容は、2025/04/11 現在のものです。


MCP サーバの Go 実装です。

[mcp-go](https://github.com/mark3labs/mcp-go)のチュートリアルを元に作成しています。

AIアシスタントは[Cline](https://github.com/cline/cline)を使います。

## Tools

- 四則演算
- UUID 生成

## Demo

https://github.com/user-attachments/assets/3a2170b7-8441-4c54-b0b1-b66563cbcc29

## QuickStart

リポジトリをクローンしてビルドします。

```
git clone git@github.com:uh-zz/mcp-tutorial.git
cd mcp-tutorial && go build -o tools
```

ビルドしたMCPサーバをClineに設定します。

<img width="358" alt="" src="https://github.com/user-attachments/assets/9ac552c6-6c22-4a3e-a003-b0b71f612402" />

`Configure MCP Servers` をクリックすると `cline_mcp_settings.json`が開きます。

`sample_cline_mcp_settings.json`をもとに編集してください。

`command`はビルドしたプログラムのパスにしてください。

<img width="959" alt="" src="https://github.com/user-attachments/assets/a3a440ab-4938-4b26-a94c-dc506ad477d9" />

## Slide


