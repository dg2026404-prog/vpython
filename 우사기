Web VPython 3.2
b=box(texture="https://r2.chiikawawallpaper.com/wallpaper/20260914/ec3d5229a19aa61e0489586e3c1a6947.png")
a=box(texture="https://i.postimg.cc/NjbrTZ5B/tpdlfps.png")


while True :
    rate(100)
    k = keysdown()
    if abs(a.pos.x - b.pos.x) < 0.1 :
        a.color = color.red
    else :
        a.color = color.white
    if ' ' in k :
        x.pos = vec(0,0,0)
    if 'r' in k :
        b.color = color.red
        b.opacity = 0.5
    if 'd' in k :
        b.pos.x = b.pos.x + 0.1
    if 'a' in k :
        b.pos.x = b.pos.x - 0.1
    if 'w' in k :
        b.pos.y = b.pos.y + 0.1
    if 's' in k :
        b.pos.y = b.pos.y - 0.1
    
    
    
    
