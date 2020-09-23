# pythonlearnin
# Python learning on a public computer 
# Init funkce nemusí brát jako parametr počet životů, ten je pokaždé 9 
class Kocka:
  def __init__(self):
    self.pocet_zivotu = 9 
  def zamnoukej(self):
    print("Mnau, mnau")
  def je_ziva(self): 
    return self.pocet_zivotu > 0 
  def uber_zivot(self)
    if not self.je_ziva():
      print("Nemůžeš zabít už mrtvou kočku")
    else: 
      self.pocet_zivotu -= 1
  def snez(self, jidlo) 
    if not self.je_ziva():
      print("Je zbytečné krmit už mrtvou kočku")
      return
    if jidlo == "ryba" and self.pocet_zivotu <9:
      self.pocet_zivotu += 1
      print("Kočka spapala rybu a tím se jí obnovil jeden život")
    else: 
      print("Kočka se krmí")
