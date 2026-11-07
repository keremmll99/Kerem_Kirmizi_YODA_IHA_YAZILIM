github  nedir : projemize ait tüm dosya ve değişikliklerin bulunduğu alan 	web tabanlı bir araçtır
neden github kullanırız : bilgisayarımızda oluşabilecek sorunlar yüzünden ilerlememizi kaybetmemek , önemli değşikliklerden önce kayıt almak için. github artık endüstri standartı olmuştur daha çok kullanılır . open source bir proje yayınladığımızda dünyanın 4 bir yanından geliştiricilerin ilgisin çekebiliriz.
 
Git bash kullanımına alışmam gerektiği söylendi ben de onu kullanıyorum mkdir diyerek yeni dosya oluşturuluyor cd yazarak da bu dosyanın içerisine giriyoruz

git remote add origin : bilgisayarımız git reposuna webdeki repoya bağlanmasını söylüyoruz

git push pull : kodları uzak repoya gönderme ve ordan almak içni gerekli komutlar 

git add "file name " ile dosyaya eklediğim şeyi tanımlıyorum 

dosyamın içine html yükledikten sonra git push ile webdeki repoya gönderdim 
 
git repo içinde commits e basarak istediğimiz commitde neler eklenmiş ("+" ile gösteriyor) neler çıkarılmış ("-" ile gösteriliyor) onları görüntüleyebilİRZ.
 

download. zip yaptığımızda starter-master gibi bir dosya iniyor burda starter dosyanın ismi master ise branch in ismi 

 

repo oluştururken: git . gitignore = olmasını istemediğimiz dosyaları belrittiğimiz kısım  
lisans da oluşturabiliriz lisans insanların kodu ne kadar nasıl kullanacağını belirlememizi sağlıyor. 


download ve clonlama arasındaki fark anladığım kadarıyla klonlarsak git özelliklerini de klonluyoruz 	

push etmeden önce commit etmemiz lazımmış yoksa gözükmüyor pushdan önceki tüm değişiklikleri alıyor push

github üzerinden de proje üzerinde değişiklikler yapabiliriz . 


şu ana kadar öğrendiklerimle alakalı örnekler vermek gerekirse: 

mkdir githubprojects ile githubprojects diye bir klasör oluşturuyorum 
cd githubprohects ile içine giriyorum 
mkdir starter ile githubprojects klasörü içinde starter diye bir klasör oluşturuyorum 
git add . ile şu ana kadar o dosya içine eklediğim her şeyi tanımlıyorum 
git commit -m "YORUM" ile commit ekleyip yorum yerine açıklama yazıyorum 
git push ile bunu web reposuna aktarıyorum 

web reposunda değişiklik yaptıktan sonra pcdeki repoda değişiklik yapıp push yapmak istersem hata alıyorum önce webdeki repodaki değişikliği almam lazım 

git pull = Git fetch + git merge yaparak bu değişiklikleri alıyoruz 

git merge yapınca açılan ekranda :wq yapıyoruz 

git push ve git pull yazdığımızda bir değişiklik yoksa bunu bize bildiriyor already up to date

biz git push ile şimdi göstersek bile bu commit ekranında bizim bilgisayarda değişikliği yaptığımız zamanda gösteriyor örneğin ben şimdi gönderdim ancak 8 dk önce commit edilmiş gözüküyor.


dosyanın aynı kısmına hem webde hem localde düzenleme yaptıktan sonra push uygularsak conflict uyarısı alıyoruz. 
hangisinin geçerli olmasını istiyorsak mesela local değişikliği korumak istiyorum , dosyayı açıp remote değişikliği ordan siliyorum. git status dersem dosyanın hem localde hem remote da değiştirildiğini belirten  both modified uyarısını alıyorum. sonra git add . ile tüm değişiklikleri tanımlayıp git commit -m "local değişikliği korudum" yazıp git push ile webe localdeki dosyayı dikte ettiriyorum . ( bu kısımda hatalı yerler olabilir kafam karıştı ancak temel mantığı kavradığıma inanıyorum).

yeni branch oluşturmak: 

git checkout -b isim  

git push origin branch ismi ile değişikliği remote a gönderebiliyoruz 

git branch ile branchleri görüntüleyebiliyoruz 

git branch -d branchadı ile branch silebilirzi 


açık kodlu yazılım : kullanıcılara değişiklik yapmak üzere açılması bazıları dağıtım hakkı vermeyebilirmiş

clear ile chati temizleyebiliyoruz . 