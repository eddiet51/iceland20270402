---
{"dg-publish":true,"permalink":"/@A行動現在/custom-style/","dg-note-properties":{}}
---


<style>
  /* 【全域生效】優化所有網頁表格的外層容器，強制在手機版開啟流暢的左右滑動 */
  .prose table, .content table, table, .block-language-dataviz table {
    display: block !important;
    width: 100% !important;
    max-width: 100% !important;
    overflow-x: auto !important;
    -webkit-overflow-scrolling: touch !important; /* 讓 iPhone 滑動更柔順 */
    margin: 1.5rem 0 !important;
    border-collapse: collapse !important;
  }

  /* 【全域生效】美化表格內部欄位，設定合理的最小寬度，防止文字被嚴重擠壓 */
  .prose table th, .prose table td, table th, table td {
    min-width: 130px !important; /* 確保每個欄位至少有 130px 寬度，在手機上滑動才好看 */
    padding: 12px 16px !important; /* 增大字體間距，提升旅遊行程可讀性 */
    text-align: left !important;
    vertical-align: top !important;
    word-break: break-word !important; /* 遇到超長英文單字會自動斷行 */
    white-space: normal !important;    /* 允許中文正常自動換行 */
  }

  /* 【加碼美化】幫全站所有表格加上極簡現代風的淡淡橫線與灰白相間背景 */
  .prose table tr, table tr {
    border-bottom: 1px solid rgba(128, 128, 128, 0.2) !important;
  }
  .prose table tr:nth-child(even), table tr:nth-child(even) {
    background-color: rgba(128, 128, 128, 0.05) !important; /* 雙數行自動帶有微弱底色，方便對齊閱讀 */
  }
</style>
