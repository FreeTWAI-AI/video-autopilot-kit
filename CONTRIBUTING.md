# 一起把底層疊起來

我們以 Hao 的公開剪輯框架為起點，讓開發、測試、影音、音樂、文件、行銷與銷售夥伴都能找到明確的貢獻入口。這是工坊 Fork；上游作者仍保有自己的原始 repo，回送上游的 PR 另外協調。

## 一次完成一張任務

1. 從 [GitHub Issues](https://github.com/FreeTWAI-AI/video-autopilot-kit/issues) 選一張，閱讀完成條件與討論。
2. 留言說明「我能做什麼／這次範圍／需要誰協助」。維護者確認後再認領，沒有人被平台自動派單。
3. 用自己的 GitHub 身分 Fork，或使用已有 Fork 加上工坊 remote；從工坊的最新 main 開工作分支。不要把密碼或 token 貼到 Issue。
4. 讓 Agent 讀 AGENTS.md 和 Issue；小幅實作、自己看差異，執行相關檢查。
5. 提交到 **FreeTWAI-AI/video-autopilot-kit** 的 PR，描述 `Closes #任務編號`、測試與限制；請維護者 review。

## 可使用的既有檢查

先閱讀相關檔案與環境要求，再選與修改有關的命令；以下是上游既有入口，不代表本次協作文件已替你跑過：

```sh
python src/system_health.py --quick
python examples/02_caption_broll_match.py
python examples/04_shorts_gate.py
```

影音與字型依賴以 README／SETUP 為準。缺工具就記 `not_run` 與原因，不自動安裝、不補造 render。當前工坊 Fork 的 Actions 尚未啟用；本階段由作者附本機測試，維護者審查。

## 貢獻與機會

GitHub 的作者、review、PR 和合併 SHA 是可追溯紀錄；協作者依實際參與列出。文件、測試、設計、需求回饋與推廣也可提交成果。平台先顯示已合併 PR 的 GitHub 作者，不把自填帳號變成已驗證會員資歷。

自願開源貢獻不保證報酬；若形成客戶案，當事人另定範圍、分工、報酬及收款方式。平台不壟斷分配機會、不代收錢。受助者可以透過修文件、補測試、回覆問題、分享可公開成果回饋社群，並非強制勞務或換取基本存取的條件。
