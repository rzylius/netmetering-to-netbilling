# netmetering-to-netbilling
ESO namų ūkio realių duomenų perskaičiavimas į netbillingo modelį

Smaugliokodas išbandytas ant google colabboratory ( https://colab.research.google.com/ ) 

# Eiga
1. ataisiųsti iš ESO valandinį suvartojimą
2. uploadinti į collab aplinką (turėtų būti standartinė vieta kai atidarote "Files". Pats failas turi atsidurti vienoje direktorijoje su direktorija "sample_data" ()
![image](https://user-images.githubusercontent.com/25814/201207979-bfc1314a-d0d7-42ff-9587-e114a0045a99.png)
3. pačioje skripto pradžioje nustatote jūsų norimo periodo skaičiavimo datas, žr šitą kodo dalį
    # SVARBU:
    # nustatome datas tarp kuriu norime atlikti analize
    start_date = pd.to_datetime(date(2021, 11, 1))
    end_date = pd.to_datetime(date(2022, 11, 1))
    
paleidžiame. Palikau tarpinius žingsnius, kad galėtumėt pasitikrinti ar atitinka jūsų norimą logiką.
