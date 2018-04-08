---
cssname: work
layout: work
activeworks: active
logo: logo.png
title: "Система ЧПУ \"ДиаНа-CNC-СМ\""
tmb: Photo.png
description: "Описание современной системы ЧПУ ДиаНа-CNC-СМ"
---
<p><strong>"ДиаНа-CNC-СМ"</strong> является динамично развивающимся программно-аппаратным комплексом мирового уровня. Открытая модульная архитектура и постоянно расширяющийся набор программных опций позволяют реализовывать оптимальные по стоимости и максимальные по функциональным возможностям системы промышленной автоматики или числового программного управления.Система числового программного управления "ДиаНа-CNC" является мультипроцессорной системой. Основой архитектуры является промышленный компьютер платформы Raspberry Pi 3.</p>
<!--content--><p>
<p></p></p>
<div class="row">
  <div class="col-lg-4 col-md-4 col-sm-4">
    <div class="work-img">
     <img src="/static/img/works/cnc-03-2018/RaspBerry.png">
    </div>
  </div>
  <div class="col-lg-8 col-md-8 col-sm-8">
   <strong>Назначение: </strong> управление требуемой конфигурацией промышленных контроллеров<br>
   <strong>Особенности:</strong><br>
   <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> расширенный диапазон питающего напряжения промышленных контроллеров формфакторов A и B (18-36 Вольт);<br>
   <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> полное отсутствие трущихся механических узлов;<br>
   <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> сокращение до минимума числа разъёмных соединений за счёт широкого использования ПЛИС;<br>
   <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> интерфейс оператор-СЧПУ выполнен с использованием сенсорного монитора (диагональ 17 дюймов);<br>
   <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> оригинальная плата Raspberry Pi не имеет часовой микросхемы, поэтому на ряде контроллеров имеется разъём для подключения платы системного времени собственного производства;<br>
   <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> линейка промышленных контроллеров включает двадцать позиций, реализующих различные комбинации дискретных и аналоговых входов и выходов, выходов и входов индуктосинов и резольверов, входов инкрементальных и абсолютных энкодеров, выходов управления приводами шаговых двигателей;<br>
   <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> используются 7 формфакторов конструктивного исполнения промышленных контроллеров.<br>
  </div>  
</div>
<p>Конструктивные особенности системы ЧПУ позволяют легко и органично интегрировать её в технологическое оборудование любых форм и размеров.</p>
<p><strong>Контроллеры Формфакторов A и B</strong> реализованы в виде пластмассовых боксов с установкой на DIN-рейку с одним номиналом питающего напряжения расширенного диапазона 1:2 18-36 В (по специальному заказу возможно исполнение с диапазоном 1:4 9-36 В).
</p>
<div class="row">
  <div class="col-lg-4 col-md-4 col-sm-4">
    <div class="work-img">
      <img src="/static/img/works/cnc-03-2018/PS-4IN-4OUT-1UART.png">
    </div>
  </div>
  <div class="col-lg-8 col-md-8 col-sm-8">
    <h3><strong class="di-color">PS-4IN-4OUT-1UART</strong></h3>
    <p><strong>Вариантное исполнение:</strong> с PVG612 или с PVA3054<br>
    <strong>Питание: </strong>24В 50 мА<br>
    <strong>Число дискретных входов: </strong>4<br>
    <strong>Число дискретных выходов: </strong>4<br>
    <strong>Управление: </strong>RS-485<br>
    <strong>Число команд: </strong>8<br>
    <strong>Формфактор: </strong>A<br>
    <strong>Нагрузка выхода: 50 мА (для PVA3054) </strong>A<br>
    <strong>Назначение: </strong>связь с элементами электроавтоматики станков и систем промышленной автоматизации, системы мониторинга, цифровые фильтры сигналов электроавтоматики, управление сервоприводами (практически полное обнуление входного сигнала при нулевом задании).<br>
    <strong>Особенности:</strong><br>
    <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> дискретные входы разделены на 4 гальванически-развязанных сегмента;<br> 
    <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> дискретные выходы разделены на 4 гальванически-развязанных сегмента;<br>
    <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> светодиодная индикация;<br>
    <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> напряжение на дискретном выходе определяется пользователем из диапазона от -60 В до +60 В (для PVG612) или от 0 до 300 В постоянного и переменного тока (для PVA3054) путём коммутации соответствующего напряжения на один из двух контактов (отдельно для каждого сегмента);<br>
    <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> повышенная нагрузочная способность дискретных выходов (стандартно 1 А, по заказу до 2-х А), позволяющая без промежуточных реле управлять катушками магнитных пусктелей и исполнительных узлов пневматических и гидравлических систем (для PVG612);<br>
    <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> возможность расширения по внутренней шине (без RS-485).
    </p>
  </div>
</div>
<div class="row">
  <div class="col-lg-4 col-md-4 col-sm-4">
    <div class="work-img">
      <img src="/static/img/works/cnc-08-2016/01.png">
    </div>
  </div>
  <div class="col-lg-8 col-md-8 col-sm-8">
    <h3><strong class="di-color">PS-16IN-8OUT</strong></h3>
    <p><strong>Питание: </strong>24В 150 мА<br>
    <strong>Число дискретных входов: </strong>16<br>
    <strong>Число дискретных выходов: </strong>8<br>
    <strong>Управление: </strong>RS-485<br>
    <strong>Число команд: </strong>8<br>
    <strong>Формфактор: </strong>A<br>
    <strong>Назначение: </strong>связь с элементами электроавтоматики станков и систем промышленной автоматизации.<br>
    <strong>Особенности:</strong><br>
    <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> дискретные входы разделены на 2 гальванически-развязанных сегмента;<br> 
    <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> дискретные выходы разделены на 2 гальванически-развязанных сегмента;<br>
    <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> напряжение на дискретном выходе определяется пользователем из диапазона от -60 В до +60 В путём коммутации соответствующего напряжения на один из двух контактов (отдельно для каждого сегмента);<br>
    <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> повышенная нагрузочная способность дискретных выходов (стандартно 1 А, по заказу до 2-х А), позволяющая без промежуточных реле управлять катушками магнитных пускателей и исполнительных узлов пневматических и гидравлических систем.
    </p>
  </div>
</div>
<div class="row">
  <div class="col-lg-4 col-md-4 col-sm-4">
    <div class="work-img">
      <img src="/static/img/works/cnc-03-2018/PS-3ADC-12IN-8OUT.png">
    </div>
  </div>
  <div class="col-lg-8 col-md-8 col-sm-8">
    <h3><strong class="di-color">PS-3ADC-12IN-8OUT</strong></h3>
    <p><strong>Питание: </strong>24В 150 мА<br>
    <strong>Число дискретных входов: </strong>12<br>
    <strong>Число дискретных выходов: </strong>8<br>
    <strong>Управление: </strong>RS-485<br>
    <strong>Число команд: </strong>10<br>
    <strong>Формфактор: </strong>A<br>
    <strong>Назначение: </strong>связь с элементами электроавтоматики станков и систем промышленной автоматизации.<br>
    <strong>Особенности:</strong><br>
    <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> дискретные выходы разделены на 2 гальванически-развязанных сегмента;<br> 
    <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> напряжение на дискретном выходе определяется пользователем из диапазона от -60 В до +60 В путём коммутации
соответствующего напряжения на один из двух контактов (отдельно для каждого сегмента);<br>
    <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> повышенная нагрузочная способность дискретных выходов (стандартно 1 А, по заказу до 2-х А), позволяющая без 
промежуточных реле управлять катушками магнитных пускателей и исполнительных узлов пневматических и гидравлических систем.</p>
  </div>
</div>
<div class="row">
  <div class="col-lg-4 col-md-4 col-sm-4">
    <div class="work-img">
      <img src="/static/img/works/cnc-03-2018/PS-3ADC-2QE-8OUT.png">
    </div>
  </div>
  <div class="col-lg-8 col-md-8 col-sm-8">
    <h3><strong class="di-color">PS-3ADC-2QE-8OUT</strong></h3>
    <p><strong>Питание: </strong>24В 150 мА<br>
    <strong>Число входов АЦП: </strong>3<br>
    <strong>Число каналов квадратурных энкодеров: </strong>2<br>
    <strong>Число дискретных выходов: </strong>8<br>
    <strong>Управление: </strong>RS-485<br>
    <strong>Число команд: </strong>10<br>
    <strong>Формфактор: </strong>A<br>
    <strong>Назначение: </strong>связь с элементами пультов оператора станков и систем промышленной автоматизации.<br>
    <strong>Особенности:</strong><br>
    <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> режимы работы квадратурных энкодеров x1 (A+B), x2 (A,B), x4 (A,~A,B,~B);<br> 
    <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> дискретные выходы разделены на 2 гальванически-развязанных сегмента;<br> 
    <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> напряжение на дискретном выходе определяется пользователем из диапазона от -60 В до +60 В путём коммутации
соответствующего напряжения на один из двух контактов (отдельно для каждого сегмента);<br>
    <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> повышенная нагрузочная способность дискретных выходов (стандартно 1 А, по заказу до 2-х А), позволяющая без 
промежуточных реле управлять катушками магнитных пускателей и исполнительных узлов пневматических и гидравлических систем.
   </p>
  </div>
</div>
<p></p><br>
<div class="row">
  <div class="col-lg-4 col-md-4 col-sm-4">
    <div class="work-img">
      <img src="/static/img/works/cnc-03-2018/PS-3QE-8OUT.png">
    </div>
  </div>
  <div class="col-lg-8 col-md-8 col-sm-8">
    <h3><strong class="di-color">PS-3QE-8OUT</strong></h3>
    <p><strong>Питание: </strong>24В 150 мА<br>
    <strong>Число каналов квадратурных энкодеров: </strong>2<br>
    <strong>Число дискретных выходов: </strong>8<br>
    <strong>Управление: </strong>RS-485<br>
    <strong>Число команд: </strong>8<br>
    <strong>Формфактор: </strong>A<br>
    <strong>Назначение: </strong>связь с элементами пультов оператора станков и систем промышленной автоматизации.<br>
    <strong>Особенности:</strong><br>
    <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> режимы работы квадратурных энкодеров x1 (A+B), x2 (A,B), x4 (A,~A,B,~B);<br> 
    <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> дискретные выходы разделены на 2 гальванически-развязанных сегмента;<br> 
    <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> напряжение на дискретном выходе определяется пользователем из диапазона от -60 В до +60 В путём коммутации соответствующего напряжения на один из  двух контактов (отдельно для каждого сегмента);<br>
    <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> повышенная нагрузочная способность дискретных выходов (стандартно 1 А, по заказу до 2-х А), позволяющая без промежуточных реле управлять катушками магнитных пускателей и исполнительных узлов пневматических и гидравлических систем.</p>
  </div>
</div> 
<div class="row">
  <div class="col-lg-4 col-md-4 col-sm-4">
    <div class="work-img">
      <img src="/static/img/works/cnc-03-2018/PS-16IN-3DAC.png">
    </div>
  </div>
  <div class="col-lg-8 col-md-8 col-sm-8">
    <h3><strong class="di-color">PS-16IN-3DAC</strong></h3>
    <p><strong>Питание: </strong>24В 150 мА<br>
    <strong>Число дискретных входов: </strong>16<br>
    <strong>Число выходов ЦАП: </strong>3<br>
    <strong>Управление: </strong>RS-485<br>
    <strong>Число команд: </strong>8<br>
    <strong>Формфактор: </strong>A<br>
    <strong>Назначение: </strong>управление приводами неразмерных перемещений станков и систем промышленной автоматизации (дискретная шкала регулирования).<br>
    <strong>Особенности:</strong><br>
    <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> дискретные выходы разделены на 2 гальванически-развязанных сегмента.</p> 
  </div>
</div>   
<div class="row">
  <div class="col-lg-4 col-md-4 col-sm-4">
    <div class="work-img">
      <img src="/static/img/works/cnc-03-2018/PS-SRV3.png">
    </div>
  </div>
  <div class="col-lg-8 col-md-8 col-sm-8">
    <h3><strong class="di-color">PS-SRV3</strong></h3>
    <p><strong>Питание: </strong>24В 250 мА<br>
    <strong>Число дискретных входов: </strong>6<br>
    <strong>Число каналов квадратурных энкодеров: </strong>3<br>
    <strong>Число дискретных выходов: </strong>3<br>
    <strong>Число выходов ЦАП: </strong>3<br>
    <strong>Управление: </strong>RS-485<br>
    <strong>Число команд: </strong>15<br>
    <strong>Формфактор: </strong>B<br>
    <strong>Назначение: </strong>управление приводами размерных перемещений станков и систем промышленной автоматизации 
(сервоуправление).<br>
    <strong>Особенности:</strong><br>
    <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> режимы работы квадратурных энкодеров x1 (A+B), x2 (A,B), x4 (A,~A,B,~B);<br> 
    <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> автоматический поиск индексной метки;<br>
    <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> напряжение на дискретном выходе определяется пользователем из диапазона от -60 В до +60 В путём коммутации
соответствующего напряжения на один из двух контактов (отдельно для каждого сегмента);<br>
    <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> повышенная нагрузочная способность дискретных выходов (стандартно 1 А, по заказу до 2-х А), позволяющая без 
промежуточных реле управлять катушками магнитных пускателей и исполнительных узлов пневматических и гидравлических систем.
    </p>
  </div>
</div>
<p>
 <strong>Контроллеры формфакторов C-G (эконом вариант)</strong> реализованы в виде открытых печатных плат с установкой на пластмассовые стойки (для формфакторов D, E, G возможна установка на DIN-рейку). Число и номиналы питающих напряжений зависят от типа промышленного контроллера.
</p>
<div class="row">
  <div class="col-lg-4 col-md-4 col-sm-4">
    <div class="work-img">
      <img src="/static/img/works/cnc-03-2018/PS-80IN-32OUT.png" />
    </div>
  </div>
  <div class="col-lg-8 col-md-8 col-sm-8">
    <h3><strong class="di-color">PS-80IN-32OUT</strong></h3>
    <p><strong>Питание: </strong>5В 500 мА; 24В 100 мА<br />
    <strong>Число дискретных входов: </strong>80<br />
    <strong>Число дискретных выходов: </strong>32<br />
    <strong>Управление: </strong>RS-485<br />
    <strong>Число команд: </strong>8<br />
    <strong>Формфактор: </strong>C<br />
    <strong>Назначение: </strong>связь с элементами электроавтоматики станков и систем промышленной автоматизации.
    </p>
  </div>
</div>
<div class="row">
  <div class="col-lg-4 col-md-4 col-sm-4">
    <div class="work-img">
      <img src="/static/img/works/cnc-03-2018/PS-4QE-4DAC.png" />
    </div>
  </div>
  <div class="col-lg-8 col-md-8 col-sm-8">
    <h3><strong class="di-color">PS-4QE-4DAC</strong></h3>
    <p><strong>Питание: </strong>5В 500 мА (цифровая часть);  5 В 100 мА (аналоговая часть); +15 В 50 мА (аналоговая часть); -15 В 50 мА (аналоговая часть)<br />
    <strong>Число каналов квадратурных энкодеров: </strong>4<br />
    <strong>Число выходов ЦАП: </strong>4<br />
    <strong>Управление: </strong>RS-485<br />
    <strong>Число команд: </strong>12<br />
    <strong>Формфактор: </strong>C<br />
    <strong>Назначение: </strong>Управление приводами размерных перемещений станков и систем промышленной автоматизации 
(сервоуправление).<br />
    <strong>Особенности: </strong><br>
    <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> режимы работы квадратурных энкодеров x1 (A+B), x2 (A,B), x4 (A,~A,B,~B);<br>
    <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> автоматический поиск индексной метки.<br>
    </p>
  </div>
</div>
<div class="row">
  <div class="col-lg-4 col-md-4 col-sm-4">
    <div class="work-img">
      <img src="/static/img/works/cnc-03-2018/PS-4RS-4DAC.png" />
    </div>
  </div>
  <div class="col-lg-8 col-md-8 col-sm-8">
    <h3><strong class="di-color">PS-4RS-4DAC</strong></h3>
    <p><strong>Питание: </strong>5В 500 мА (цифровая часть);  5 В 100 мА (аналоговая часть); +15 В 50 мА (аналоговая часть); -15 В 50 мА (аналоговая часть)<br />
    <strong>Число каналов резольвера/индуктосина: </strong>4<br />
    <strong>Число выходов ЦАП: </strong>4<br />
    <strong>Управление: </strong>RS-485<br />
    <strong>Число команд: </strong>12<br />
    <strong>Формфактор: </strong>C<br />
    <strong>Назначение: </strong>Управление приводами размерных перемещений станков и систем промышленной автоматизации 
(сервоуправление).<br />
    <strong>Особенности: </strong><br>
    <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> программная блокировка датчиков обратной связи.<br>
    </p>
  </div>
</div>
<div class="row">
  <div class="col-lg-4 col-md-4 col-sm-4">
    <div class="work-img">
      <img src="/static/img/works/cnc-03-2018/PS-8IN-3QE-8OUT-3STEP.png" />
    </div>
  </div>
  <div class="col-lg-8 col-md-8 col-sm-8">
    <h3><strong class="di-color">PS-8IN-3QE-8OUT-3STEP</strong></h3>
    <p><strong>Питание: </strong>5В 500 мА; 24В 100 мА<br />
    <strong>Число дискретных входов: </strong>8<br />
    <strong>Число каналов квадратурных энкодеров: </strong>3<br />
    <strong>Число дискретных выходов: </strong>17 (8+9)<br />
    <strong>Управление: </strong>RS-485<br />
    <strong>Число команд: </strong>15<br />
    <strong>Формфактор: </strong>C<br />
    <strong>Назначение: </strong>комплексное управление станком или системой промышленной автоматизации с шаговыми двигателями (3 оси).<br />
    <strong>Особенности: </strong><br>
    <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> режимы работы квадратурных энкодеров x1 (A+B), x2 (A,B), x4 (A,~A,B,~B);<br>
    <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> автоматический поиск индексной метки.<br>
    </p>
  </div>
</div>
<div class="row">
  <div class="col-lg-4 col-md-4 col-sm-4">
    <div class="work-img">
      <img src="/static/img/works/cnc-03-2018/PS-1ABS-1DAC.png" />
    </div>
  </div>
  <div class="col-lg-8 col-md-8 col-sm-8">
    <h3><strong class="di-color">PS-1ABS-1DAC</strong></h3>
    <p><strong>Питание: </strong>5В 500 мА (цифровая часть);  5 В 100 мА (аналоговая часть); +15 В 50 мА (аналоговая часть); -15 В 50 мА (аналоговая часть)<br />
    <strong>Число каналов абсолютного энкодера: </strong>1<br />
    <strong>Число выходов ЦАП: </strong>1<br />
    <strong>Управление: </strong>RS-485<br />
    <strong>Число команд: </strong>15<br />
    <strong>Формфактор: </strong>D<br />
    <strong>Назначение: </strong>управление приводами размерных перемещений станков и систем промышленной автоматизации 
(сервоуправление).<br />
    <strong>Особенности: </strong><br>
    <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> программное управление направлением счёта;<br>
    <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> программная установка нулевого положения.<br>
    </p>
  </div>
</div>
<div class="row">
  <div class="col-lg-4 col-md-4 col-sm-4">
    <div class="work-img">
      <img src="/static/img/works/cnc-03-2018/PS-10PWM.png" />
    </div>
  </div>
  <div class="col-lg-8 col-md-8 col-sm-8">
    <h3><strong class="di-color">PS-10PWM</strong></h3>
    <p><strong>Питание: </strong>5В 100 мА<br />
    <strong>Число каналов ШИМ: </strong>10<br />
    <strong>Управление: </strong>RS-485<br />
    <strong>Число команд: </strong>3<br />
    <strong>Формфактор: </strong>E<br />
    <strong>Назначение: </strong>управление серводвигателями постоянного тока (например, серии BLM).<br />
    <strong>Особенности: </strong><br>
    <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> раздельное включение/выключение каналов.<br>
    </p>
  </div>
</div>
<div class="row">
  <div class="col-lg-4 col-md-4 col-sm-4">
    <div class="work-img">
      <img src="/static/img/works/cnc-03-2018/PS-RASPBERRY-1UART.png" />
    </div>
  </div>
  <div class="col-lg-8 col-md-8 col-sm-8">
    <h3><strong class="di-color">PS-RASPBERRY-1UART</strong></h3>
    <p><strong>Питание: </strong>5В 100 мА; 3.3В 50мА<br />
    <strong>Число каналов UART: </strong>1<br />
    <strong>Физический интерфейс: </strong>RS-485<br />
    <strong>Максимальная скорость: </strong>115.2 КБод<br />
    <strong>Формфактор: </strong>F<br />
    <strong>Назначение: </strong>связь с промышленными контроллерами в простых системах числового программного управления и системах промышленной автоматизации.<br />
    </p>
  </div>
</div>
<div class="row">
  <div class="col-lg-4 col-md-4 col-sm-4">
    <div class="work-img">
      <img src="/static/img/works/cnc-03-2018/PS-RASPBERRY-2UART.png" />
    </div>
  </div>
  <div class="col-lg-8 col-md-8 col-sm-8">
    <h3><strong class="di-color">PS-RASPBERRY-2UART</strong></h3>
    <p><strong>Питание: </strong>5В 100 мА; 3.3В 50мА<br />
    <strong>Число каналов UART: </strong>2<br />
    <strong>Физический интерфейс: </strong>RS-485<br />
    <strong>Максимальная скорость: </strong>1.5 МБод<br />
    <strong>Формфактор: </strong>F<br />
    <strong>Назначение: </strong>связь с промышленными контролkерами в сложных системах числового программного управления и системах промышленной автоматизации.<br />
    </p>
  </div>
</div>
<div class="row">
  <div class="col-lg-4 col-md-4 col-sm-4">
    <div class="work-img">
      <img src="/static/img/works/cnc-03-2018/PS-RASPBERRY-8IN.png" />
    </div>
  </div>
  <div class="col-lg-8 col-md-8 col-sm-8">
    <h3><strong class="di-color">PS-RASPBERRY-8IN</strong></h3>
    <p><strong>Питание: </strong>5 В 100 мА (от Raspberry Pi); 3.3 В 50 мА (от Raspberry Pi)<br />
    <strong>Число дискретных входов:  </strong>8<br />
    <strong>Формфактор: </strong>F<br />
    <strong>Назначение: </strong>системы комплексного мониторинга парка промышленного оборудования.<br />
    <strong>Особенности: </strong><br>
    <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> дискретные входы разделены на 2 гальванически-развязанных сегмента;<br>
    <span class="glyphicon glyphicon-chevron-right di-color" aria-hidden="true"></span> разъём для подключения системных часов.<br>
    </p>
  </div>
</div>
