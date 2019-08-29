# React Eğitim Video Serisi
Bu repository React hakkında hazırlamış ve YouTube kanalımda(**Mehmet Ali FIRAT**) yayınlamış olduğum *__React-Redux Eğitim__* serisinde hazırladığım proje dosyalarını içermektedir.

## -> Ders-11
Spread operatörü ile(**[...]**) dizi ve elemanları birleştirip yeni dizi yapma işlemi yapıldı ve ***setState*** metodu ile state güncelleme işlemi yapıldı.

    let tUsers = [...this.state.users,user]
    this.setState({
      users:tUsers,
      idx: id+1
    })

### Ders-10
Ekleme işlemi için Form yapısı eklendi. App içerisinde oluşturulan _addUser_ metodu props olarak **AddUser** bileşenine gönderildi.

### Ders-9
Liste ile çalışıldı. App bileşeni içerisindeki bir listeyi UserList bileşenine props olarak gönderildi. UserList içerisinde map fonskiyonu sayesinde her bir elemanı User bileşenine props olarak gönderildi.

    array.map(item=> {
      return(...)
    })



### Ders-8
props ile bileşenler arası veri aktarımı yapıldı.

    <User name="Mehmet" state="online" metod={ConsoleLog} />

### Ders-7
create-react-app scripti kullanılarak geliştirme ortamı oluşturuldu ve çalıştırıldı.

    npx create-react-app user-app
    cd user-app
    npm start

### Ders-6
DOM olayları ile State güncellendi.

### Ders-5
Sınıf tipinde bileşene State(Durum) nesnesi eklendi

### Ders-4
Sınıf, Fonksiyon ve Lambda Fonksiyonlar ile Bileşenler oluşturuldu.

### Ders-3
CDN linkleri eklendi ve ilk element oluşturuldu.