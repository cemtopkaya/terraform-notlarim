```shell
terraform version

terraform -chdir=<calisacak/dizinin/yolu> <ikinci_komut>

terraform <init> # dizini terraforma uygun başlatır npm init gibi

terraform plan # Execution plan oluşturur

terraform apply

# her seye bastan baslamak icin tum planlanmıs altyapıyı silmek için
terraform destroy

Daha sonra execute edilecek planları bir dosyaya yazdırmak için (-out <dosya adı>)
terarform plan -out <plan_adı>

terraform apply <plan_adı>. # Belirli bir planı uygulamak için
terraform plan -destroy

# Değişimleri sadece belirli bir hedefe uygulamak istersek
terraform apply -target=<hedef_kaynaklar>
terraform apply -var degisken_adı=degeri  # Bir değişkeni dışarında geçirmek istersek

terraform providers. # Sağlayıcıları çekmek için

```

<img width="745" alt="image" src="https://user-images.githubusercontent.com/261946/202872108-91a003be-9f8c-4fa8-b6b8-6541192e948f.png">
