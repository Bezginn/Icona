***********************************
Abracadabra
***********************************




Опаньки
=======================




Акт (ACT) отправляет розничная сеть поставщикам, в  нем указываются дополнительные услуги их стоимость.

| ----------------------------------------------------------- | ------- | ------------------- | ----------------------------------------------------- |
|                      **Название поля**                      | **Тип** |     **Формат**      |                     **Описание**                      |
|                              <ACT>                          |         |                     |                                                       |
|                      <NUMBER></NUMBER>                      |    М    |     Строка (16)     |                    Номер документа                    |
|                        <DATE></DATE>                        |    М    |  Дата (ГГГГ-ММ-ДД)  |                    Дата документа                     |
|                      <PERIOD></PERIOD>                      |    М    |  Дата (ГГГГ-ММ-ДД)  |                        Период                         |
|              <CAMPAIGNNUMBER></CAMPAIGNNUMBER>              |    М    |     Строка (16)     |              Номер договора на поставку               |
|             <POSITIONSAMOUNT></POSITIONSAMOUNT>             |    М    |  Число десятичное   |             Сумма по вем позициям без НДС             |
|                      <VATSUM></VATSUM>                      |    М    |  Число десятичное   |                       Сума НДС                        |
|                 <TOTALAMOUNT></TOTALAMOUNT>                 |    М    |  Число десятичное   |                   Общая сумма с НДС                   |
|                    <CURRENCY></CURRENCY>                    |    М    |     Строка (3)      |                      Код валюты                       |
|                     <DOCTYPE></DOCTYPE>                     |    М    |     Строка (1)      | Тип документа: O — оригинал, R — замена, D — удаление |
|                        <INFO></INFO>                        |    О    |     Строка (70)     |                      Информация                       |
|                              <HEAD>                         |         |                     |                                                       |
|                   <PERFORMER></PERFORMER>                   |    М    |     Число (13)      |                    GLN исполнителя                    |
|               <PERFORMERNAME></PERFORMERNAME>               |    О    |     Строка (70)     |                 Название исполнителя                  |
|          <PERFORMERNDSNUMBER></PERFORMERNDSNUMBER>          |    О    |     Строка (35)     |              Номер свид. НДС исполнителя              |
|       <PERFORMERFISCALNUMBER></PERFORMERFISCALNUMBER>       |    О    |     Строка (35)     |                    ИНН исполнителя                    |
| <PERFORMERREGISTRATIONNUMBER></PERFORMERREGISTRATIONNUMBER> |    О    |     Строка (35)     |             Номер регистрации исполнителя             |
|           <PERFORMERDIRECTOR></PERFORMERDIRECTOR>           |    О    |     Строка (70)     |          Отвественный со стороны исполнителя          |
|            <PERFORMERACCOUNT></PERFORMERACCOUNT>            |    О    |     Строка (35)     |                    Код исполнителя                    |
|          <PERFORMERTELEPHONE></PERFORMERTELEPHONE>          |    О    |     Строка (35)     |                  Телефон исполнителя                  |
|             <PERFORMERADRESS></PERFORMERADRESS>             |    О    |     Строка (70)     |                   Адрес исполнителя                   |
|           <PERFORMERBANKNAME></PERFORMERBANKNAME>           |    О    |     Строка (35)     |              Название банка исполнителя               |
|         <PERFORMERBANKNUMBER></PERFORMERBANKNUMBER>         |    О    |     Строка (35)     |                 МФО банка исполнителя                 |
|        <PERFORMERBANKACCOUNT></PERFORMERBANKACCOUNT>        |    О    |     Строка (35)     |                 Номер р/с исполнителя                 |
|                    <CUSTOMER></CUSTOMER>                    |    М    |     Число (13)      |                     GLN заказчика                     |
|                <CUSTOMERNAME></CUSTOMERNAME>                |    О    |     Строка (70)     |                  Название заказчика                   |
|           <CUSTOMERNDSNUMBER></CUSTOMERNDSNUMBER>           |    О    |     Строка (35)     |                Номерсвид.НДС заказчика                |
|        <CUSTOMERFISCALNUMBER></CUSTOMERFISCALNUMBER>        |    О    |     Строка (35)     |                     ИНН заказчика                     |
|  <CUSTOMERREGISTRATIONNUMBER></CUSTOMERREGISTRATIONNUMBER>  |    О    |     Строка (35)     |              Номер регистрации заказчика              |
|            <CUSTOMERDIRECTOR></CUSTOMERDIRECTOR>            |    О    |     Строка (70)     |               Отвественный от заказчика               |
|             <CUSTOMERACCOUNT></CUSTOMERACCOUNT>             |    О    |     Строка (35)     |                     Код заказчика                     |
|           <CUSTOMERTELEPHONE></CUSTOMERTELEPHONE>           |    О    |     Строка (35)     |                   Телефон заказчика                   |
|              <CUSTOMERADRESS></CUSTOMERADRESS>              |    О    |     Строка (35)     |                    Адрес заказчика                    |
|            <CUSTOMERBANKNAME></CUSTOMERBANKNAME>            |    О    |     Строка (35)     |               Название банка заказчика                |
|          <CUSTOMERBANKNUMBER></CUSTOMERBANKNUMBER>          |    О    |     Строка (35)     |                  МФО банка заказчика                  |
|         <CUSTOMERBANKACCOUNT></CUSTOMERBANKACCOUNT>         |    О    |     Строка (35)     |                  Номер р/с заказчика                  |
|                      <SENDER></SENDER>                      |    М    |     Число (13)      |                    GLN отправителя                    |
|                   <RECIPIENT></RECIPIENT>                   |    М    |     Число (13)      |                    GLN получателя                     |
|                            <POSITION>                       |         |                     |                                                       |
|              <POSITIONNUMBER></POSITIONNUMBER>              |    М    |   Число *1, 100]    |                     Номер позиции                     |
|              <MATERIALASSETS></MATERIALASSETS>              |    О    |     Строка (70)     |                   Описание продукта                   |
|                    <QUANTITY></QUANTITY>                    |    O    | Число положительное |                   Количество товара                   |
|                <QUANTITYUNIT></QUANTITYUNIT>                |    O    | Число положительное |                 Количество в упаковке                 |
|          <QUANTITYFORSPECIAL></QUANTITYFORSPECIAL>          |    O    | Число положительное |              Количество в спец.упаковке               |
|                       <PRICE></PRICE>                       |    М    |  Число десятичное   |               Цена за единицу (без НДС)               |
|             <PRICEFORSPECIAL></PRICEFORSPECIAL>             |    O    | Число положительное |             Цена спец.укпаковки (без НДС)             |
|                      <AMOUNT></AMOUNT>                      |    М    |  Число десятичное   |                Сумма товара (без НДС)                 |
|               <PENALTYAMOUNT></PENALTYAMOUNT>               |    О    |  Число десятичное   |                     Сумма штрафа                      |
|                 <TOTALAMOUNT></TOTALAMOUNT>                 |    О    |  Число десятичное   |           Общая цена поставляемой продукции           |
|                     <TAXRATE></TAXRATE>                     |    М    |      Число (3)      |                Ставка налога (НДС, %)                 |
|                        <INFO></INFO>                        |    О    |     Строка (70)     |                      Информация                       |
|                        <DATE></DATE>                        |    О    |  Дата (ГГГГ-ММ-ДД)  |                         Дата                          |
|             <SERVICEMADEDATE></SERVICEMADEDATE>             |    О    |  Дата (ГГГГ-ММ-ДД)  |              Дата предоставления услуги               |
|                           </POSITION>                       |         |                     |                                                       |
|                             </HEAD>                         |         |                     |                                                       |
|                              <ACT>                          |         |                     |                                                       |
