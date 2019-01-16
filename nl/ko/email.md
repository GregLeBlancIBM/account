---

copyright:

  years: 2015, 2018
lastupdated: "2018-11-28"


---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:tip: .tip}
{:note: .note}
{:screen: .screen}
{:new_window: target="_blank"}


# 이메일 환경 설정 지정
{: #email-prefs}

{{site.data.keyword.Bluemix}} 계정 유형에 따라, {{site.data.keyword.Bluemix}} 플랫폼 미계획 이벤트 및 계획된 이벤트에 대한 이메일 알림의 수신 여부나 미계획 이벤트, 유지보수 및 공지사항에 대한 인프라 이메일 알림의 수신 여부를 선택할 수 있습니다. 클래식 인프라 이벤트에 대한 알림 구독을 설정하도록 선택할 수도 있습니다.
{: shortdesc}

## 플랫폼 알림 설정
{: #setting-platform-notifications}

Lite 계정 소유자는 {{site.data.keyword.Bluemix}} 플랫폼 미계획 이벤트(예: 가동 중단) 및 계획된 이벤트(예: 유지보수)에 대한 이메일 알림 수신 여부를 선택할 수 있습니다. {{site.data.keyword.Bluemix_notm}} 플랫폼 알림을 설정하면 {{site.data.keyword.Bluemix_notm}} 플랫폼과만 연관된 이메일 알림을 수신합니다. {{site.data.keyword.Bluemix_notm}} 서비스와 연관된 이벤트에 대해서는 이메일 알림을 수신하지 않습니다. 

계정이 아닌 프로파일에 대해서만 플랫폼 이메일 알림을 설정할 수 있습니다. 즉, 다른 계정으로 전환하는 경우 작성된 플랫폼 알림 업데이트의 범위는 전환된 계정이 아닌 프로파일로 한정됩니다. 

미계획 플랫폼 이벤트 수신을 선택하면 가동 중단(Sev 1)을 유발할 수 있는 문제에 대해서만 이메일을 받습니다. [상태 ![외부 링크 아이콘](../icons/launch-glyph.svg "외부 링크 아이콘")](https://cloud.ibm.com/status){: new_window} 페이지에서 언제든지 모든 계획된 이벤트와 계획되지 않은 이벤트를 볼 수 있습니다. 

1. 아바타 아이콘 ![아바타 아이콘](../icons/i-avatar-icon.svg) &gt; **프로파일 및 설정**으로 이동하십시오. 
2. **알림**을 클릭하십시오.
3. 업데이트할 각 카테고리에 대해 플랫폼 알림을 수신하는지 여부를 선택하십시오. 

  기본적으로 모든 {{site.data.keyword.Bluemix_notm}} 플랫폼 알림은 꺼져 있습니다. {: tip}

4. **저장**을 클릭하십시오.

## 인프라 알림 설정

종량과금제 또는 구독 계정 소유자는 미계획 이벤트, 유지보수 및 공지사항에 대한 {{site.data.keyword.Bluemix_notm}} 인프라 이메일 알림의 수신 여부를 선택할 수 있습니다. 인프라 알림의 범위는 전환되는 계정으로 한정됩니다. 다른 계정으로 전환하여 해당 계정에 대한 알림을 관리할 수 있습니다. 

1. 아바타 아이콘 ![아바타 아이콘](../icons/i-avatar-icon.svg) &gt; **프로파일 및 설정**으로 이동하십시오. 
2. **알림**을 클릭하십시오.
3. 업데이트할 각 카테고리에 대해 인프라 알림을 수신하는지 여부를 선택하십시오. 

  기본적으로 모든 {{site.data.keyword.Bluemix_notm}} 인프라 알림은 켜져 있습니다.
  {: tip}

4. **저장**을 클릭하십시오.

## 사용자 알림 설정
{: #setting-user-notifications}

사용자 알림 설정은 클래식 인프라 리소스에만 사용 가능합니다. 계정 소유자는 계정의 사용자에 대한 알림 구독을 설정할 수 있습니다. 구독은 {{site.data.keyword.autoscaling}} 및 Raid 경보 모니터링 등의 특정 개발자 서비스 세트용입니다. 사용자가 서비스를 구독하면 사용자는 해당 서비스에 대한 이메일을 수신합니다.   

계정의 사용자는 다음 유형의 중요 운영 이벤트에 대한 알림을 받습니다. 

  * 계획되지 않은 인프라 문제 또는 가동 중단: 특정 고객에 대해 특정 조건을 기반으로 가동 중단을 유발할 수 있는 문제. 
  * 계획된 서비스 또는 스케줄된 유지보수: 최적의 상태로 인프라 작동을 유지하는 데 필요한 유지보수. 
  * 보안 취약점: 영향을 받은 영역이 격리됩니다. 취약성을 차단하기 위해 패치가 작성되며 부수적 기능이 영향을 받지 않도록 패치에 대해 테스트가 수행됩니다.  
  * 열린 지원 케이스: 해당 계정에서 열린 케이스에 대해 사용자에게 경보를 보냅니다. 

알림의 타이밍은 이벤트가 계획되지 않음, 계획됨 또는 스케줄됨 상태인지 여부에 따라 다릅니다. {{site.data.keyword.BluSoftlayer_notm}} 인프라 정책은 더 큰 영향을 줄 수 있는 추가 문제 발생의 위험성을 제거하거나 최소화하기 위해 가능한 빨리 문제점을 해결하는 것입니다. 종종 계획된 유지보수의 경우에도 짧은 사전 알림으로만 수행됩니다. 

사용자의 구독 알림을 설정하려면 다음 단계를 완료하십시오.  

  1. **관리 > 계정**으로 이동하여 **알림**을 선택하십시오.  
  2. 테이블에서 서비스를 선택하십시오.  
  3. 구독 열에서 알림 수신을 원하는 사용자에 대해 **예**를 선택하십시오.  

    손쉽게 원하는 사용자를 찾으려면 **필터**를 클릭하고 성, 이름 또는 사용자 이름으로 필터링하십시오.
    {: tip}
