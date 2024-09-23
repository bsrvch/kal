| № **п/п** | **Параметр** | **Кратность** | **Тип** | **Описание** |
   | --- | --- | --- | --- | --- |
   |  | id | 0\..0 <br /> | id | Идентификатор ресурса Location. Присваивается СЗПВ после получения от клиента СЗПВ запроса создания заявки на вызов врача на дом (метод «Создание заявки на вызов врача на дом ($createhomecallrequest)»). Передается в формате guid |
   |  | identifier | 1\..1 | Identifier | Адрес места вызова в соответствии с классификатором ФИАС |
   |  | identifier.system | 1\..1 | uri | Пространство имен идентификатора. Указывается значение «[https://fias.nalog.ru/FiasInfo»](https://fias.nalog.ru/FiasInfo%C2%BB) |
   |  | identifier.value | 1\..1 | string | GUID адресного объекта ФИАС (поле таблицы ФИАС addrobj.aoguid) |
   |  | description | 0\..1 | string | Комментарий к адресу |
   |  | physicalType | 1\..1 | CodeableConcept | Тип ресурса Location |
   |  | coding.system | 1\..1 | uri | Указывается значение «[http://terminology.hl7.org/CodeSystem/location-physical-type»](http://terminology.hl7.org/CodeSystem/location-physical-type%C2%BB) |
   |  | coding.code | 1\..1 | code | Указывается значение «ho» (обозначение того, что данный ресурс Location - жилой дом (место, где проживает пациент - адрес места вызова)) |
   |  | coding.display | 1\..1 | string | Указывается значение «House» |
   |  | address | 1\..1 | Address | Информация об адресе места вызова |
   |  | address.text | 1\..1 | string | Адрес места вызова. Указывается строкой |
   |  | address.district | 0\..1 | string | Район места вызова. Указывается строкой |
