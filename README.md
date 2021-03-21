# CICD_hw

- CI
  - build
    - Commit和Push到github後，透過github action進行整合，在統一的環境自動建置程式。
  - 程式測試
    - 在本機端就測試,驗證自己的程式碼。
- CD
  - 透過Heroku，將github的專案部署到Heroku上，在每一次github action執行完後，Heroku便會同步出結果。
heroku連結 https://davidxwangxcicd.herokuapp.com/
