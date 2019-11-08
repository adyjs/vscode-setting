# vscode 

vscode 編輯器設定

* install plugin pkgs
```

C/C++
ms-vscode.cpptools


C/C++ Snippets
hars.cppsnippets


Easy LESS
mrcrowl.easy-less


HTML Snippets
abusaidm.html-snippets


Live Server
ritwickdey.liveserver


Markdown Preview Enhanced
shd101wyy.markdown-preview-enhanced


Simple React Snippets
burkeholland.simple-react-snippets


```


* .vscode 檔案結構
```
project folder
└── vscode
    └── settings.json

```

1. 設定位置
    建立一個名稱為 『.vscode』 的目錄，在專案的根目錄，
    裡面再建立一個名稱為『settings.json』的檔案，這樣在此目錄所做的動作就會依照這個檔案內的設定規則
    
    PS. 如果檔案都有建立，規則也沒有寫錯，但卻都沒有效用的時候，
        可以檢查一下，目錄 .vscode , settings.json 的檔案名稱有沒有錯誤，有沒有前後多一個空格，
        這都會影響參照失效



2. settings.json 格式

```json


// Easy LESS
{    
    "less.compile": {
        "out": "${workspaceRoot}/src/css/"
    }
}

```
    