# Универсальный контроллер автоматизации #

![](https://github.com/intel-1/GreenBox/tree/master/docs/TOP_0573_.jpg "")

### Описание контроллера ###
GreenBox - это универсальный контроллер для теплиц или других объектов где необходима автоматизация управления по датчикам или таймерам. 



### Особенности: ###
+	Поддерживает 7 цифровых выходов подключенных через силовые ключи. Суммарный ток всех каналов будет зависеть от можности источника питания.
+	13 портов для подключения исполнительных модулей. Ими могут быть моторы (шаговый, коллекторный, серво мотор), реле, устройства поддерживающие PWM управление.
+	5 аналоговых портов (влажность почвы, освещенность, напряжение питания,...).
+	9 входных каналов для концевиков. К ним могут быть подключены концевики форточек, концевики для подсчета количества оборотов (для управления коллекторными моторами в режиме пропорционального управления).
+	Поддерживает 12 различных датчиков:
    *	Датчика температуры, влажности воздуха или атмосферного давления:
        * DS18B20 (температура)
        * AM2302 (температура и влажность воздуха)
        * Si7013, Si7020, Si7021, HTU21D, SHT21 (разные названия датчика HTU21D)
        * BME280 (температура и влажность воздуха)
        * BMP280 (температура, влажность воздуха и атмосферное давление)
        * LM75 (температура)
        * INA219 (напряжение и ток)
        * INA3221 (3 независимых канала для измерения напряжения и тока)	
    * Аналоговые измерения.
    * Датчики освещенности:
        * TSL2561
        * BH1750
        * MAX44009
+	Часы реального времени DS3231. С из помощью можно настраивать таймеры для различных исполнительных модулей.
+	GSM модуль. Может отправлять настраиваемые СМС уведомления при возникновении нештатной ситуации, например неисправен один и датчиков или значение одного из датчиков (например температуры) вышли за рамки установленных границ. Так же можно настроить управление контроллера по СМС командам, например можно направить СМС контроллеру и в ответ он вышлет измеренные значения выбранных датчиков.
+	SD карта. На нее так же могут писаться логи работы контроллера, датчиков, исполнительных модулей.
+   LCD экран. Можно отображать разлиные параметры, например значения датчиков.

