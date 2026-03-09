# betik5_hafta
5.hafta betik dilleri 
io.py:

#f=open("melek2.txt","x") #dosya oluşturma

dizi=[]
with open("melek.txt",'r', encoding="utf-8") as f:
    a=f.readline
    dizi.append(a)
    b=f.readline()
    dizi.append(b)
    c=f.readline()
    dizi.append(c)
    d=f.readline()
    dizi.append(d)
    y=dizi[]
    for i in dizi:
        son=i.split(' ')
        k=(son[0])
        m=son[1])
        x=son[2])
        n(x[1:])
        y=son[3]
        yy=y[0:5]
        print(yy)
        dizilim='{} {} {} {}$'.format(k,m,n,yy)
        ydizi.append(dizilim)
        
        with open ("melek2.txt",'a',encoding="utf-8") as f:
            print(print(......)..)
            print(.......)

**************************************************

melek.py:

ayberk korkmaz $25 100000
melek varol $22 150000
nihal özturan $21 200000
nergıs boz $23 250000
        
***************************************************        
    
 xyz.py:

def duzgunlestir(arr):
    for i in arr:
        x=(i.split(' '))
        isim= ''
        for parca in x:
            isim+=(parca.strip()) #boşluk siler
        print('=======')
        print(isim)

**********************************************************

xyz2.py:

from xyz import duzgunlestir

iller=['Anka   - ra  ', 'istan   -  bul','iz - mir','bur- sa', 'eski  - şehir']
duzgunlestir(iller)
for i in iller:
    print(i)
    
    
for i in iller:
    k=i.split('-')
    ayberk=''
    for j in k:
        ayberk+=j.strip()
        print(ayberk)



**********************************************************
kim.py:

url='https://www.milligazete.com.tr/arsiv/2021-07-27'
def tarih_yaz(gun):
    for i in range(1,gun+1,):
        if i<10:
            print(url+'0'+str(i))
        else:
            print(url+str(i))
tarih_yaz(28)

*****************************************

main:

A=[
"15:26 Ateşkes umurların da mı?! Terörist İsrail ordusu Lübnan'a yine saldırı düzenledi!",
"15:25 Dem Parti’den çift taraflı İran açıklaması… Dışardan müdahale olmasın, içeriden rejim değiştirilsin!",
"15:01 Bakan Uraloğlu'ndan açıklama! Hürmüz Boğazı'ndaki Türk gemilerinin durumu belli oldu",
"14:37 Yaşadıkları hezi̇meti̇n görüntülenmesi̇ni̇ i̇stemi̇yorlar…. CNN Türk muhabi̇ri̇ ve kameramanı gözaltına alındı",
"14:36 Shamdasani: İran'da 153 öğrenci ve öğretmenin hayatını kaybettiği saldırıyla ilgili soruşturma çağrısında bulunuyoruz",
"14:23 Maneviyat herkesi heyecanlandırdı! Gaziantep'te 'Mukaddes Emanetler Sergisi' ziyarete açıldı",
"14:12 Hangi il kaç vekil çıkaracak! İl il milletvekili sayıları...Artan ve azalan iller",
"14:07 ABD dezenformasyon çabasında! Bekayi, ABD Özel Temsilcisi Witkoff'u yalanladı",
]


esd:

from main import A
for i in A:
    son=i.split(' ') //split: ayırmak, listeye çevirmek 
    for i in range(len(son)):
        if j==0:
            print(son[j])
        else:
            pass
            

