<?xml version="1.0" encoding="UTF-8"?>
<mdclass:InformationRegister xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:core="http://g5.1c.ru/v8/dt/mcore" xmlns:mdclass="http://g5.1c.ru/v8/dt/metadata/mdclass" uuid="f84be77f-a1c4-4808-9dc7-093709e87a05" name="СостояниеВходящихПисем" editType="InDialog" dataLockControlMode="Managed">
  <synonym key="ru" value="Состояние входящих писем"/>
  <producedTypes>
    <selectionType typeId="25da68f6-fa47-48af-a9f9-51ec171fa92b" valueTypeId="5fc65a8c-5ecc-473c-b215-4c370494d390"/>
    <listType typeId="a0c9bd07-79ef-4fc8-8896-97d96020c0cc" valueTypeId="8820582d-b256-4755-a9d8-ce5e61454651"/>
    <managerType typeId="0a1e7a8f-bc29-40e4-a343-7761b9b34700" valueTypeId="d3306b28-8f6b-412e-aa06-0a00b9120b0f"/>
    <recordSetType typeId="6eb0e940-a371-40e3-947a-00f19793bbdb" valueTypeId="db218434-72ca-4c6d-bb83-29da3c649196"/>
    <recordKeyType typeId="ad6be69c-ed9e-4845-907b-1d9991155941" valueTypeId="069a214b-de3e-4120-9ad5-77c5feb298c2"/>
    <recordType typeId="14903eed-d5f4-4e41-851f-bd772641e05c" valueTypeId="331f7054-eed4-40e6-9dd8-beaea6d895dd"/>
    <recordManagerType typeId="502f5c40-d4cd-4a06-8b33-ff0baaf7d5d9" valueTypeId="ca929924-5e6e-4b86-a055-a846d8c1916c"/>
  </producedTypes>
  <resources uuid="a32a1d54-a99e-4216-86b5-cfa5eaeb2e99" name="Прочитано" fullTextSearch="Use">
    <synonym key="ru" value="Прочитано"/>
    <type>
      <types>Boolean</types>
    </type>
    <minValue xsi:type="core:NullValue"/>
    <maxValue xsi:type="core:NullValue"/>
    <fillValue xsi:type="core:NullValue"/>
  </resources>
  <dimensions uuid="a9234923-b95c-487a-a6e5-6a77495af739" name="Письмо" fillChecking="ShowError" denyIncompleteValues="true" fullTextSearch="Use" fillFromFillingValue="true" master="true" mainFilter="true">
    <synonym key="ru" value="Письмо"/>
    <type>
      <types>CatalogRef.ВходящиеПисьма</types>
    </type>
    <minValue xsi:type="core:NullValue"/>
    <maxValue xsi:type="core:NullValue"/>
    <fillValue xsi:type="core:NullValue"/>
  </dimensions>
</mdclass:InformationRegister>
