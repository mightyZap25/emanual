

# 1. 제품 소개

mightyZap Total Manager는 다양한 운영체제에서 MIghtyZap을 관리 및 제어할수 있는 Software입니다.

- MightyZap의 Parameter를 설정하고, 동작 테스트를 할 수 있습니다.
- 간단한 동작 Motion 을 테스트하고 시간에 따라 변경되는 Data를 확인할 수 있습니다.
- 다양한 Protocol을 기반으로 MightyZap을 상태확익 및 제어 할 수 있습니다.
- 모든 Smart mightyZap의 펌웨어를 업데이트 할 수 있습니다.

![Untitled](mightyZAP%20Total%20Manager%20Manual%20a9697154663145308f2fb9c43f4cdbec/Untitled.png)

MightyZap Total Manager  Software를 구동하기 위해서는 MightyZap 서보 인터페이스 모듈(IR-USB0x 별매)를 추천드립니다. <USB Interface Board는 링크>

## 1.2 지원 Protocol

- Protocol 1.0
- Modbus-RTU (FC-Only)
- CAN Protocol (BLDC Only)

## 1.3 지원 운영체제

- Windows : windows 7(32bit)
- Mac OS(지원예정)
- Linux(지원예정)
- DeskTop & lapTop에서만 테스트 되었습니다.

## 1.4 Firmware Update

- Firmware는 서보모터를 구동하기위해 설치하는 Software  입니다.
- Firmware는 아래와 같은 상황에 따라 Update 되며, **동작의 안정성을 위해 가급적 최신상태로 유지할것을 권장합니다.**
    - 새로운 기능이 추가되거나 수정되었을 경우, 새로운 firmware가 배포됩니다.
    - Bug 수정이 있을 경우, 새로운 Firmware가 배포됩니다.
    - 제품이 정상적으로 동작하지 않거나, 통신이 원할하지 않을경우, 최신  Firmware를 통해 문제가 해결 될수 있습니다.

# 2. Software Install

## **2.1 윈도우에서 설치하기**

1. 윈도우즈 전용 패키지를 다운도르 합니다.
    - Windows Software 다운로드
2. 다운받은 설치 파일을 실행합니다.
    
    ![Untitled](mightyZAP%20Total%20Manager%20Manual%20a9697154663145308f2fb9c43f4cdbec/Untitled%201.png)
    
3. Next 버튼을 클릭하여 설치를 진행합니다.
    
    ![Untitled](mightyZAP%20Total%20Manager%20Manual%20a9697154663145308f2fb9c43f4cdbec/Untitled%202.png)
    

## 2.2 Mac os에서 설치하기

## 2.3 linux에서 설치하기

# 3 MightyZap Total Manager 제거하기

## 2.1 Uninstall : Windows

1. Windows 설정 창에서 앱을 선택합니다.
    
    ![Untitled](mightyZAP%20Total%20Manager%20Manual%20a9697154663145308f2fb9c43f4cdbec/Untitled%203.png)
    
2. 앱 창에서 MightyZap Total Manager를 찾은 후 Uninatall을 선택합니다.
    
    ![Untitled](mightyZAP%20Total%20Manager%20Manual%20a9697154663145308f2fb9c43f4cdbec/Untitled%204.png)
    
3. Uninstall 프로그램이 동작하면   제거  버튼을 선택하여 Software를 제거합니다.

![Untitled](mightyZAP%20Total%20Manager%20Manual%20a9697154663145308f2fb9c43f4cdbec/Untitled%205.png)

## 2.2 Mac os에서 설치하기

## 2.3 linux에서 설치하기

# 3. 매뉴 설명

### 3.1 화면 구성

![그림3.png](mightyZAP%20Total%20Manager%20Manual%20a9697154663145308f2fb9c43f4cdbec/%25EA%25B7%25B8%25EB%25A6%25BC3.png)

**① Main Toolbar** 

Actuator의 Reset, Restart, Data Undo/Redo 등을 수행하는 메뉴입니다.

**② SCAN**

Software의 통신을 연결하고 MightyZap을 검색하는데 사용 됩니다. 

**③ Main Menu**

Information, Control, Update, Manager Setting 등 Manager에서 제공하는 기능을 선택하는 메뉴 입니다.

**④ Actuator List**

검색된 MightyZap의 이름이 통신 속도와 Protocol에 따라 분류되어 표시 됩니다.

**⑤ Main Contents**

매니저에 제공하는 Main  기능을 표시합니다.

**⑥ Actuator Information**

선택된 Actuator의 모델명, Firmware Version, 통신 방식 등이 표기 됩니다.

**⑦ 통신 상태**

통신 Protocol 및 송수신 Error 등 통신 상태를 나타냅니다.

**⑧ Manager Status**

Manager의 버전 및 Language 를 표시합니다.

### 3.2 Information 화면

서보모터의 정보를 표시하는 창입니다. 선택된 서보모터의 모델명, 모터 타입, 최대속도, 펌웨어 버전등을 확인할 수 있습니다. 

또한 해당 서보보터의 Datasheet 및 사용자 매뉴얼등을 확인 할 수 있습니다.  [추후 제고]

![Untitled](mightyZAP%20Total%20Manager%20Manual%20a9697154663145308f2fb9c43f4cdbec/Untitled%206.png)

### 3.3 Control 화면

Parameter  화면은 MightyZap 서보 모터의 제어값을 설정하거나 동작을 테스트 할 수 있습니다.

또한, 실시간 변화 Data를 그래프로 볼 수 있습니다.

![Untitled](mightyZAP%20Total%20Manager%20Manual%20a9697154663145308f2fb9c43f4cdbec/Untitled%207.png)

### 3.4 Update 화면

Update  창은 서보모터의 펌웨어 버전을 변경하거나, 검색되지 않는 서보모터를 복구하는데 사용됩니다.

![Untitled](mightyZAP%20Total%20Manager%20Manual%20a9697154663145308f2fb9c43f4cdbec/Untitled%208.png)

# 4.기본기능

## 4.1 통신 Port 확인

## 4.2통신 연결 및 검색

1. 통신 연결을 위해 아래의 그림과 같이 Software를 실행한 후 우측 상단의 SCAN 버튼을 클릭합니다.
    
    ![Untitled](mightyZAP%20Total%20Manager%20Manual%20a9697154663145308f2fb9c43f4cdbec/Untitled%209.png)
    
2. 연결할 통신 Port를 선택한 후 Open 버튼을 눌러 통신을 연결합니다.
    
    ![Untitled](mightyZAP%20Total%20Manager%20Manual%20a9697154663145308f2fb9c43f4cdbec/Untitled%2010.png)
    
3. 검색할 Protocol과  Baudrate를 선택한 후 SCAN 버튼을 눌러 연결된 서보모터를 검색합니다.
    
    ![Untitled](mightyZAP%20Total%20Manager%20Manual%20a9697154663145308f2fb9c43f4cdbec/Untitled%2010.png)
    
4. 검색된 MightyZap은 해당 ID와 Protocol이 표시되면 나열됩니다.
    
    ![Untitled](mightyZAP%20Total%20Manager%20Manual%20a9697154663145308f2fb9c43f4cdbec/Untitled%2011.png)
    
5. 검색 중 중지를 원할경우 STOP 버튼을 누르게 되면 검색이 종료 됩니다.
Stop 버튼을 누르지 않을경우 모든 Option을 검색한 후 자동 종료 됩니다.
6. Close 버튼을 누르면 검색이 종료되고 해당  창이 사라집니다.

## 4.3 MightyZap 선택

1. 검색 된 MightyZap을 제어하기 위한 방법 중 하나는 아래의 Actuator List에서 제어하고자 하는  MightyZap을 선택해야 합니다.
    
    ![Untitled](mightyZAP%20Total%20Manager%20Manual%20a9697154663145308f2fb9c43f4cdbec/Untitled%2012.png)
    
2. 다른 방법으로는 프로그램 우측상단의 ‘▼’ 버튼을 클릭하면 그림과 같이 검색된 Actutaor의 List가 나타납니다.
    
    ![Untitled](mightyZAP%20Total%20Manager%20Manual%20a9697154663145308f2fb9c43f4cdbec/Untitled%2013.png)
    
3. 해당 버튼은 Software의 창 크기를 줄일 경우 Actuator List 창이 사라지게 되며 이때 주로 사용합니다.
    
    ![Untitled](mightyZAP%20Total%20Manager%20Manual%20a9697154663145308f2fb9c43f4cdbec/Untitled%2014.png)
    
4. 제어하기 위한 MightyZap 을 선택하면 그림과 같이 해당 MightyZap에 대한 정보가 표시되며 우측상단에 선택된 MightyZap의 Model 명이 표시됩니다.
    
    ![Untitled](mightyZAP%20Total%20Manager%20Manual%20a9697154663145308f2fb9c43f4cdbec/Untitled%2015.png)
    

# 5. Contents(가칭)

## 5.1 Information

## 5.2 Control Page

Control Page는 MightyZap의 Parameter를 수정  하고 동작 Test를 위한 제어 Page 입니다.
Control Page는 크게 Non-Volatile Memory( 비 휘발성 메모리)와 Volatile Memory(휘발성 메모리) 영역을 나뉘어 표시됩니다.

![Untitled](mightyZAP%20Total%20Manager%20Manual%20a9697154663145308f2fb9c43f4cdbec/Untitled%2016.png)

### 5.2.1 기초설명(가칭)

- **Non-Volatile Parameter**
    
    비휘발성 Parameter를 제어하는 영역으로 해당  Parameter는 변경된 Data가 내부 Memory에 저장되어 전원이 Off 되어도 해당 내용을 기억할 수 있습니다.
    
    Non-Volatile Parameter는 제어하기 전 Actuator의 기본 환경을 설정하는 Parameter 로 초기 설정에 많이 사용되어지는 Parameter로 이루어져 잇습니다.
    
    Non-Volatile Parameter는 Save 버튼을 누리기 전 까지는 수정된 내용이 적용되지 않습니다.
    (자세한 내용은 각 모델의 사용자 매뉴얼을 참조해 주시기 바랍니다.) 
    
- **Volatile Parameter**
    
    휘발성 Parameter를 제어하는 영역으로 해당 Parameter는 변경된 Data가 내부 RAM에 저장되어 전원이 Off 되면 Data는 초기화 됩니다.
    
    Volatile Parameter는 MightyZap의 동작을 제어하거나 실시간 동작 상태를 확인하는데 사용되는 Parameter들로 이루어져 있습니다.
    (자세한 내용은 각 모델의 사용자 매뉴얼을 참조해 주시기 바랍니다.) 
    
- **Main Toolbar**
    
    Parameter의 Data 변경 내역을 되돌리거나 Parameter Reset 및 MightyZap 시스템 재부팅 등을 실행 할 수 있습니다.
    

### 5.2.2 Parameter Control

![Untitled](mightyZAP%20Total%20Manager%20Manual%20a9697154663145308f2fb9c43f4cdbec/Untitled%2017.png)

- **Address**
    
    Parameter의 Memory Address 가 10진수로 표시됩니다. 
    
- **Name**
    
    Prameter의 이름이 표시됩니다.
    
- **Tooltip**
    
    Parameter 에 대한 간단한 사용 정보가 표시됩니다. 자세한 정보는 해당 모델의 사용자 매뉴얼을 참조해 주시기  바랍니다.
    
- **Control Tool**
    
     Parameter에 따라 Slide Bar, Text 창, Select 버튼 등으로 Parameter를 수정 또는 각 값을 확인 할 수있도록 Display 됩니다.
    수정 중일 때는 해당 Data는 강조 표시되며, Non-volatile Parameter는 해당 값을 수정해도 즉시 반영되지 않습니다. 수정 내용을 적용하기 위해서는 Save 버튼을 눌러야 합니다.
    Save 버튼을 누르지 않고 다른 Parameter를 수정할 경우 수정된 내용이 이전 상태로 돌아갑니다.
    
- **Save**
    
    해당 Parameter를  수정된 데이터로 저장합니다. Save 버튼을 누르면 해당 데이터가 MightyZap에 통신을 이용하여 해당 Parameter를 변경합니다. 적용 시간은 모델이 따라 다르며 최대 250msec가 소요됩니다. 
    Volatile Parameter의 경우 저장 버튼없이 실시간으로 제어가 됩니다.
    
- **Monitor**
    
    Monitor는 실시간으로 Data를 확인할 때 사용합니다. 사용가능한 Parameter는 각 모델이 따라 다르며, Read Time은 통신속도에 따라 25msec, 50msec로 나위며 Monitor Graph 상단 우측에 표시됩니다.
    
    ![Untitled](mightyZAP%20Total%20Manager%20Manual%20a9697154663145308f2fb9c43f4cdbec/Untitled%2018.png)
    
    측정 된 Data에 Mouse Pointer를 가져다 대면 해당 Data의 값이 상세히 표시됩니다.
    
    ![Untitled](mightyZAP%20Total%20Manager%20Manual%20a9697154663145308f2fb9c43f4cdbec/Untitled%2019.png)
    

### 5.5 Firmware Update

### 5.6 MightyZap Recovery