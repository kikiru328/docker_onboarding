---
240430 
---

**<u>[Backend Development Terms]</u>**

 
<font size='2'>1. CI/CD</font>  
><font size='2'>지속적 통합 (Continuous Integration, CI): 지속적 통합은 개발자들이 <span style='color:skyblue'>코드 변경 사항</span> 을 <span style='color:#skyblue'>중앙 저장소</span>에 자주 (일반적으로는 하루에 여러 번) 병합 (merge)하는 것을 말한다. 각 병합시마다 코드를 자동으로 빌드하고 테스트하여, 개발 초기 단계에서 문제를 발견하고 수정할 수 있게 한다. 이 과정은 통합 과정에서 발생할 수 있는 문제를 최소화하여, 소프트웨어의 품질을 향상시킨다.</font>
  
><font size='2'>지속적 배포 (Continuous Development, CD): 지속적 배포는 모든 코드 변경 사항이 테스트를 통과한 후 자동으로 운영 환경에 배포되는 것을 의미한다.</font>

><font size='2'>지속적 전달 (Continuous Delivery) : 지속적 전달은 지속적 배포의 한 단계 전 과정으로, 모든 ㅗㅋ드 변경 사항이 테스트를 통과하면 운영 환경에 배포될 준비가 되는 것을 의미한다.</font>

<font size='2'>2. ECR</font>  
><font size='2'>ECR (Elasti Container Registry) 은 AWS 에서 제공하는 도커 컨테이너 이미지를 저장, 관리, 배포할 수 있는 <span style='color:skyblue'>완전 관리형 컨테이너 이미지 레지스트리</span>서비스이다. 개발자는 ECR을 사용하여 컨테이너 이미지를 쉽게 업로드하고, 버전 관리를 진행하며, 배포작업을 보다 효율적으로 수행할 수 있다.</font>


<font size='2'>3. Process</font>  
><font size='2'>프로세스는 운영 체제에서 실행 중인 프로그램의 인스턴스. 컴퓨터의 CPU 시간과 메모리 자원을 할당받아 실행되며, 최소 하나 이상의 실행 흐름 (thread)를 가진다. 운영체제는 멀티태스킹을 통해 여러 프로세스를 동시에 관리하고 실행한다.</font>

<font size='2'>3. instance</font>  
><font size='2'>`프로그램의인스턴스` 라는 표현은 프로그램이 메모리에 로드되어 실행 상태에 있는 데이터의 정적인 집합. 사용자나 시스템에 의해 실행될 때, 운영 체제는 해당 프로그램의 코드와 데이터를 메모미로 로드하고 실행을 시작한다. 이 때 메모리에 로드되어 실행하는 프로그램을 <span style='color:skyblue'>인스턴스</span>라고 한다.</font>

<font size='2'>4. kernel</font>  
><font size='2'>커널과 프로세스는 운영 체제 내에서 밀접하게 연관된 두 요소이다. 커널은 운영체제의 핵심 부분으로, 하드웨어와 소프트웨어 간의 통신을 관리하며, 시스템 자원과 다양한 컴퓨터 작업을 효율적으로 조정하고 제어한다. 프로세스는 실행중인 프로그램의 인스턴스로, 커널에 의해 생성되고 관리된다. 프로세스와 커널의 관계는 다음과 같다.
>> 1. 프로세스 생성과 관리
>>> <font size='1'> 커널은 프로세스의 생성, 실행, 중지 및 종료와 같은 샘명 주기를 관리한다. 사용자나 다른 프로그램에 의해 프로그램이 실행되면, 커널은 해당 프로그램에 대한 프로세스를 생성하고, 필요한 시스템 자원(CPU, 메모리공간)을 할당한다.</font>  
>> 2. 자원 할당  
>>> <font size='1'> 커널은 여러 프로세스 간에 하드웨어 자원 (CPU, 메모리, I/O 장치 등)을 공정하게 분배한다. 이는 멀티태스킹 환경에서 중요한 역할을 하며 각 프로세스가 필요한 자원을 효율적으로 사용할 수 있게 한다.</font>
>>3. 프로세스 간 통신
>>> <font size='1'> 프로세스들이 서로 정보를 교환하거나 동기화할 필요가 있을 시, 커널은 이러한 통신을 가능하게 하는 메커니즘 (IPC : Inter-Process Communication)을 제공한다.  
>>4. 보안과 격리  </font>
>>> <font size='1'> 커널은 프로세스 간의 격리를 유지. 하나의 프로세스가 다른 프로세스의 메모리나 자원에 무단으로 접근하는 것을 방지. 이는 시스템의 안정성과 보안을 유지하는데 중요.</font>
>>5. 스케쥴링
>>> <font size='1'> 커널은 프로세스 스케쥴러를 통해 어떤 프로세스가 CPU를 사용할 차례인지 결정. 이는 시스템의 반응 시간과 처리량을 최적화하는데 중요한 역할을 진행한다.</font>  

> 따라 커널은 프로세스의 생성부터 종료까지 전 생명 주기에 걸쳐 관리하는 역할을 수행하며, 프로세스들이 시스템 자원을 효율적으로 사용하도록 조정한다. 이러한 관리와 조정을 통해 사용자와 앱은 안정적이고 효율적인 시스템 환경에서 작업을 수행한다.

 
  

```This Documents are cited from Wanted Backend Devleopment Course```
