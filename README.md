# Day9-images-download
以正確的副檔名下載網頁中的圖片

範例網頁:https://www.ptt.cc/bbs/Beauty/M.1556291059.A.75A.html



Note：因為 PTT 會詢問「是否滿 18 歲」，這邊可以用 cookies 繞過

requests.get(URL, cookies={'over18': '1'})
