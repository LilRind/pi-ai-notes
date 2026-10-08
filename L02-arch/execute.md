// 使用PowerShell调用，可以看到Agent的回答

// $body = @{ question = "简单解释下ReAct agent？" } | ConvertTo-Json

// Invoke-RestMethod -Uri "http://localhost:3000/ask" -Method Post -Body ([System.Text.Encoding]::UTF8.GetBytes($body)) -ContentType "application/json; charset=utf-8"


