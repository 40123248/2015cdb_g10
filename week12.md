# week12

這週我們起先先研究出上次期中報告沒辦法畫出的第二個齒輪的問題

問題

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
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
