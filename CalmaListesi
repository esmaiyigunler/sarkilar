class Sarki:
    def __init__(self,baslik,sanatci):
        self.baslik=baslik
        self.sanatci=sanatci
    def bilgi(self):
        print(f"Şarkı: {self.baslik}, Sanatçı: {self.sanatci}")
class CalmaListesi:
    def __init__(self):
        self.sarkilar=[]
    def sarkiEkle(self,sarki):
        self.sarkilar.append(sarki)
    def sarkiCikar(self,baslik):
        self.sarkilar=[sarki for sarki in self.sarkilar if sarki.baslik!=baslik]
    def sarkilariGoster(self):
        if self.sarkilar:
            print("Çalma listenizdeki şarkılar:")
            for sarki in self.sarkilar:
                sarki.bilgi()
        else:
            print("Çalma listenizde şarkı yok")
sarki1=Sarki("Shape of you","Ed Sheeran")
sarki2=Sarki("Blinding Lights","The Weekend")
calmaListesi=CalmaListesi()
calmaListesi.sarkiEkle(sarki1)
calmaListesi.sarkiEkle(sarki2)
calmaListesi.sarkilariGoster()
calmaListesi.sarkiCikar("Shape of you")
calmaListesi.sarkilariGoster()
