How to Debug FrontEnd
=====================

PC웹, 모바일 웹, 웹뷰에서 FrontEnd 작업을 디버깅하는 효율적인 방법에 대해 살펴봅니다.

보편적인 디버깅 작업 방식에는 많은 시간을 소요하기 때문에 시간을 최소화해 디버깅할 수 있는 방법을 제시합니다. 여러분이 프로젝트를 진행함에 있어, 보다 빠른 디버깅 방법을 찾을 수 있다면, 빠른 디버깅을 통해 줄어든 시간을 다른 곳에 투자할 수 있을 것이며, 수정에 대한 피드백 시간이 줄어듬으로 타 부서의 업무 시간도 줄여 줄 수 있을 것입니다.

이 문서에서 제시된 일렬의 작업 방식이 가장 효율적인 방법이 아닐 것입니다. 그러나 반복적인 작업의 시간을 줄일 수 있는 좋은 방법 중 하나 일 것입니다. 업무의 효율을 높일 수 있는 여러 작업 방법에 대하여 함께 논의하고 연구해보세요.

> "부지런한 개발자 말고 게으른 개발자가 되세요."
>
> 비교적 작은 노동으로 큰 일을 할 수 있는 게으른 게발자가 되어보세요. 우리는 비교적 작은 노동으로도 정말 훌륭한 것을 만들 수 있는 창조적 활동을 하는 지식 노동자입니다.

**우리 업무는?**

프런트 엔드 작업자의 디버깅 업무는 디자인 스타일이 잘 적용되어 있는지, 웹 표준에 맞춰 알맞은 요소와 문법은 정확한지, 웹 접근성에 근거하여 작업이 되었는지, 스크립트의 오작동과 오류는 없는지 등을 확인해야 합니다. 내용 상으로는 그렇게 많은 작업처럼 느껴지지 않지만 크로스 브라우징과 모바일 디스플레이까지 대응하며 디버깅하는 작업은 대단히 고단하고 시간이 많이 소요되는 업무입니다.

**하지만?**

많은 프론트 엔드 개발자는 로컬 작업물을 파일 경로로 브라우저에 접속해 확인을 합니다. 하지만 Ajax를 이용한 비동기 통신 작업은 로컬에서 실행되지 않는 경우가 있어 별도의 웹 서버가 필요하기도 합니다. 또한 모바일 작업의 경우 실제 디바이스에서 확인을 하려면 도메인이 있는 웹 서버에 파일을 올려 확인해야 합니다. 그러나 프로젝트를 진행하다 보면 프론트 엔드 개발 산출물이 나오는 시점에도 웹 서버나 도메인 세팅이 되지 않은 경우가 종종 있습니다. 아니 항상 그렇습니다. 그래도 우리는 개발을 진행해야 됩니다.

**어떻게?**

로컬에 웹 서버를 설정해 작업을 진행할 것입니다. 로컬에 웹 서버를 설정해 놓으면 많은 작업 시간을 줄일 수 있습니다. 파일 수정 후 브라우저를 새로고침 하지 않아도 자동으로 새로고침 되며, 도메인 없이 로컬에서 작업한 파일을 디바이스에서 실시간 확인하고 디버깅할 수 있습니다.

**그래서~**

개발하기 위하여 기본 적으로 사전 준비가 필요합니다. 많은 프로그램을 설치할 것이며, 여러 가지 설정이 필요합니다. 하지만 앞으로 우리가 불필요하게 소비하는 많은 시간과 에너지 보다 적은 노력일 것입니다.
