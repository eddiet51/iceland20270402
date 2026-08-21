---
{"dg-publish":true,"permalink":"/custom-style/","dg-note-properties":{}}
---


<style>
  /* 這是之前幫您寫好的全域基礎優化（所有表格通用） */
  .table-wrapper {
    display: block !important;
    width: 100% !important;
    overflow-x: auto !important;
  }

  /* 🎯 這裡新增一組：當筆記被標註為「冰島超市」時，啟動的超精準寬度分配 */
  .iceland-market .table-wrapper th:nth-child(1), .iceland-market .table-wrapper td:nth-child(1) { min-width: 100px !important; } /* 類別 */
  .iceland-market .table-wrapper th:nth-child(2), .iceland-market .table-wrapper td:nth-child(2) { min-width: 160px !important; } /* 商品名稱 */
  .iceland-market .table-wrapper th:nth-child(3), .iceland-market .table-wrapper td:nth-child(3) { min-width: 180px !important; } /* 價格 */
  .iceland-market .table-wrapper th:nth-child(4), .iceland-market .table-wrapper td:nth-child(4) { min-width: 250px !important; } /* 備註 */

  /* 🎯 這裡可以再準備一組：當筆記被標註為「行程時間表」時的寬度分配 */
  .iceland-schedule .table-wrapper th:nth-child(1), .iceland-schedule .table-wrapper td:nth-child(1) { min-width: 80px !important; }  /* 日期 */
  .iceland-schedule .table-wrapper th:nth-child(2), .iceland-schedule .table-wrapper td:nth-child(2) { min-width: 100px !important; } /* 時間 */
  .iceland-schedule .table-wrapper th:nth-child(3), .iceland-schedule .table-wrapper td:nth-child(3) { min-width: 350px !important; } /* 景點與自駕路線 */
</style>
