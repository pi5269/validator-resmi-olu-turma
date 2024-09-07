# validator-resmi-olu-turma
Validator Resmi Nasıl Oluşturulur? 

1-https://keybase.io gir ve uyelik oluştur. kullanıcı adı, mail gir ve şifre belirle 
2-Sol üstte bulunan profil oluştururken kullandığımız yerden VALİDATOR resmini yukle. 
3-Resim eklediğimiz yerin aynında add a PGB Key tıkla 
4-Açılan sayfadan I need a public Key seç 
5-isim gir, ilk satıra mail gir 2. ve 3. maili boş bırak, şifreni gir devam et 
6-Biraz bekledikten sonra size 16 haneli bir ID verecek 
7-Verilen ID ve girdiğini butun herşeyi kopyalayın ve kaydedin. 

Şimdi biz bu ID yi nerede kullanacağız. 

Validator oluştururken girdiğimiz bir kod vardı, Örneğin; 
babylond tx staking create-validator \
--amount=1000000ubbn \
--pubkey=$(babylond tendermint show-validator) \
--moniker="Moniker" \
--identity=FFB0AA51A2DF5955 \
--details="I'm sexy and I know it😉" \
--chain-id=bbn-test-2 \
--commission-rate=0.10 \
--commission-max-rate=0.20 \
--commission-max-change-rate=0.01 \
--min-self-delegation=1 \
--from=wallet \
--gas-prices=0.1ubbn \
--gas-adjustment=1.5 \
--gas=auto \
-y 

bu kodta bulunan identitity nin karşısına 16 haneli kodu yazdığınızda validator adınızın yanında resminiz çıkacaktır. 

Mevcut kurulmuş validatorlere bu resmi yukleyebilirmiyiz? EVET; Örnek veriyorum. 
babylond tx staking edit-validator \
--new-moniker="Moniker" \
--identity=FFB0AA51A2DF5955 \
--details="I'm sexy and I know it😉" \
--chain-id=bbn-test-2 \
--commission-rate=0.1 \
--from=wallet \
--gas-prices=0.1ubbn \
--gas-adjustment=1.5 \
--gas=auto \
-y
yine identity karşısına 16 haneli kodu yazıyoruz. 
kodların diğer bölümlerini kendinize göre düzenlemeyi unutmayın.
hadi kolay gelsin :))) 

Dileyen aşağıdaki linktende bakabilir.
https://www.bulbapp.io/p/5b5e79c3-d0e4-447e-bd81-6b3ebbb1b3d7/validator-resmi-nasl-oluturulurhttps://www.bulbapp.io/p/5b5e79c3-d0e4-447e-bd81-6b3ebbb1b3d7/validator-resmi-nasl-oluturulur


Corenode(salomon75) telegram grubundan alınmıştır.
