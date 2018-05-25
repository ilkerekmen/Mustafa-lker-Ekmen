# Mustafa-llker-EKMEN & # Mehmet ŞEN 
3 Eksen Robot Kol'un GUI'de kinematik hesapları, simulink ve solidworks entegresi yapılmıştır.
Matlab kodlarındaki kullanılan fonksiyonların açıklaması aşagıdaki gibidir;

function GUI_VSMP2O_OpeningFcn(hObject, eventdata, handles, varargin)
%OBJELER EVEN DATADA SAKLANDI.
%HOBJECT: O AN İÇİNDE BULUNDUĞUMUZ BİLEŞENE ULAŞMAK İÇİN KULLANIYORUZ.

% --- Bu fonksiyondan gelen çıktılar komut satırına döndürülür.
function varargout = GUI_VSMP2O_OutputFcn(hObject, eventdata, handles) 
% varargout Çıktı döndürmek için hücre dizisi (see VARARGOUT);
% eventdata  İlerde tanımlanacak dataları topluyor(Kullanıcıdan aldığı
% değerleri komut satırına biliriyoruz.
%Handles Bir nesneyi kendine bağlamış kaynak görevi görmektedir.

Solidworks ve Matlab'ı entegre etmek isteyen arkadaşlar aşağıdaki adımları takip ederek gerekli kurulumları gerçekleştirebilirsiniz: 
1.	http://www.mathworks.com/products/simmechanics/download_smlink.html adresinden smlink.r2009b.win32.zip ve install_addon.m isimli iki adet dosyayı indiriniz. 
2.	C:\ sürüsünde bir klasör oluşturunuz. Örneğin: C:\SimMechanicsLink_kurulum ve indirdiğiniz bu iki adet dosyayı bu klasör içerisine taşıyınız. 
3.	MATLAB’i çalıştırınız. MATLAB komut satırına aşağıdaki satırı yazınız (her bir satır sonrası ENTER tuşuna basınız ve işlemler bitene kadar bekleyiniz.): 
cd(‘C:\SimMechanicsLink_kurulum’) 
install_addon(' smlink.r2009b.win32.zip ') 
smlink_linksw 
4.	MATLAB’i kapatıp SolidWorks’ü çalıştırınız. 
5.	Tools menüsünden Add-Ins’i seçiniz ve SimMechanics Link’i seçiniz. OK düğmesine basıp kurulumu bitiriniz. 

https://www.youtube.com/watch?v=h9Uty22wxCY
