# week12

40123248

這週我們起先先研究出上次期中報告沒辦法畫出的第二個齒輪的問題

發現問題

1.

```
ctx.save()
ctx.translate(400, 400)
ctx.rotate(pi/2)
gear(0, 0,''' + str(total) + ',' + str(b) +  ''',"blue")
ctx.restore()
ctx.save()
ctx.translate(400 + ''' + str(2*total) + ''',400)
ctx.rotate(-(pi/2) -pi/ '''  + str(b) + ''')
gear(0, 0,''' + str(total) + ',' + str(b) +  ''',"blue")
ctx.restore()
```

發現 直接寫上
```
gear(400,400 + ''' + str(2*total) +','+ str(b) +  ''',"blue")
```
即可劃出另一齒輪 此程式碼的意思是 在x軸上兩個半徑後的點劃出一個齒輪 不過無法咬合

之後參考旋轉的指令 我們先`ctx.translate`到400 400 再旋轉Pi/2的角度後 以0 0畫出齒輪
接下來重新 一次步驟 `ctx.translater` 到400+兩倍節圓半徑
再逆時針轉`Pi/2 + 一齒的角度` 一樣以0 0畫出齒輪

    
即可得到旋轉的同樣齒輪相嚙合   完成
    
    
開始進行   w12 功課

組員們已全員進行過手動組立的練習並上傳至vimeo

40123248

40123240

40123237

40123234

40123247

40123143


    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
