# BLDC_Motor_driver
STM32F446RET7 MCU' lu drv8302dca akıllı mosfet sürücülü Motor sürücü kartı tasarımı 
Kartımızda temel olarak atm32f446re mikrodenetleyicisi kullanılmıştır.
Mosfet sürücüsü olarak drv8302dca akıllı mosfet sürücüsü kullanılmıştır.
Her fazın akımı, batarya gerilimi ve kart gerilimi, ESD ve ters gerilim koruması,
aşırı akım ve kısa devre akım koruması, Adc pinleri için bariyer koruması, 
Mcu ve Sürücü için buck dönüştürücüsü, Motor için filtrelenmiş 12V çıkış gibi 
Temel devre üzerinde çalışma yapılmıştır.
