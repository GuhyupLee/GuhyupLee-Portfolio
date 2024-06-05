# 이구협(Guhyup Lee) 포트폴리오
 <br />

# 소개

	> 안녕하세요! 저는 ESTSoft AI 모델 개발자 양성과정 2기를 수료하여 인공지능 영역으로의 발돋움을 시작했습니다.
	> 저의 강점은 ***"향상심"***이라고 생각합니다. 항상 최선의 방법을 생각하고, 가능한한 최고가 되고싶어하는 마음입니다.
	> 제가 진행한 프로젝트들을 아래에 기록하였습니다. 많은 참고 바랍니다.
	
	<br />
	
# 프로젝트

	ESTSoft의 6개월 과정동안 진행한 3개의 프로젝트들입니다.
	두번의 조장과, 세번의 핵심적인 역할을 수행하였습니다.
	조장을 하면서 ***리더십***과 ***조직관리***에 대한 인사이트를 얻었고,
	그 밖에 프로젝트 일정 관리 및 ML/DL 이외에도 프론트엔드/백엔드에 대한 지식을 알 수 있었습니다.
	
	## 첫번째 프로젝트 - 서울시 아파트 시세 예측
	
	> - 개발 기간 :  2024년 2월 21일 ~ 2024년 3월 7일 (총 16일)
	> - 제약 사항 : 정형데이터와 ML을 이용한 프로젝트
	> - 핵심 역할 : 팀장, 발표, 프로젝트 기획, 데이터 분석, 모델링
	> - 프로젝트 결과 : 8개 조에서 1위를 달성
	
	> ***배경***
	> 코로나 19 사태 이후 서울시의 아파트의 시세가 요동치면서, 시민들의 아파트의 매매에 대한 고민거리가 늘어나고 있다. 이러한 상황에서 머신러닝을 이용해 아파트의 미래 적정 시세를 예측함으로서 도움을 주고자 하였다.
	>
	> ***프로젝트 요약***
	> 인근 지하철 역 수, 학교의 수, 한강 인접 여부 등의 다양한 요소들을 고려해 데이터를 분석하고 모델링을 작성하였으며, 예측 결과 가격대별로 차이가 있지만 전체적인 평균으로는 20%가 넘지않는 범위내에서 예측을 성공하였다.
	>
	> [프로젝트 상세 설명 및 리포지토리] (https://github.com/ESTsoft-first-project-2jo/2jo)
	
	<br />
	
	## 두번째 프로젝트 - 알약 인식
	
	> - 개발 기간 :  2024년 3월 27일 ~ 2024년 4월 15일 (총 19일)
	> - 제약 사항 : 시계열 데이터 혹은 시퀀스 데이터를 이용한 ML/DL 프로젝트
	> - 핵심 역할 : 팀장, 발표, 프로젝트 기획, 데이터 분석, 모델링, Flask를 통한 서비스 일부 구현
	> - 프로젝트 결과 : 8개 조에서 2위를 달성
	
	> ***배경***
	> 최근 약물의 오남용과 과대처방에 의해서 현대인들은 다양한 약물을 복용하면서도, 자신이 먹는 약이 무슨 약인지 모르는 경우가 있다. 하지만 현재의 시스템상으로는 일일이 약의 모양과 색상, 글자를 대조하면서 자신이 먹는 약이 무엇인지 찾아야한다. 이를 해결하기 위해 이미지를 통한 알약 검출 서비스를 구현하려한다.
	>
	> ***프로젝트 요약***
	> ML/DL을 이용하여 알약의 색상, 모양을 검출하는데는 성공하였지만 만족스러운 결과의 OCR을 만들지 못하였다. 하지만 OCR은 OPEN AI API를 사용하여 처리함으로서 60%의 가까운 인식률을 얻어낼 수 있었다.
	> 하지만 알약이라는 특성상 100%에 가까운 신뢰도가 필요한데, 이를 달성하지 못한데에 아쉬움이 존재한다.
	>
	> [프로젝트 상세 설명 및 리포지토리] (https://github.com/iamrosy20/WASSUP_Project2_team6)
	> [프로젝트 서비스 부분 리포지토리] (https://github.com/GuhyupLee/pill-identifier)
	
	<br />
	
	## 두번째 프로젝트 - 감정 일기 Facelog
	
	> - 개발 기간 :  2024년 5월 9일 ~ 2024년 6월 5일 (총 27일)
	> - 제약 사항 : 객체인식 모델을 활용한 안면 분류 모델 구현과 그를 통한 서비스 구현
	> - 핵심 역할 : 발표, 모델링, API 연결, 프롬프트 엔지니어링, 프로젝트 기획
	> - 프로젝트 결과 : 7개 조에서 1위를 달성
	
	> ***배경***
	> 최근 SNS는 과대한 자기과시 및 허영심으로 인한 문제점과 개인정보 유출에 대한 불안감으로 인해 피로감을 느끼는 늘어나고 있는 실정이다. 이러한 배경에서 SNS를 대체하기위해 AI가 댓글을 달아주는 기밀성 SNS 일기 서비스를 구축하고자 하였다.
	>
	> ***프로젝트 요약***
	> 짧은 기간안에 상당히 높은 퀄리티의 서비스를 구현할 수 있었으며, 딥러닝 모델들의 정확도도 준수하게 나왔다.
	> 하지만 모델링에서 더 나은 성능을 구현하고, 더 많은 데이터 셋을 통해 학습 및 예측을 수행했으면 어땠을까 하는 아쉬움이 남는다.
	>
	> [프로젝트 상세 설명 및 리포지토리] (https://github.com/zooodung/Face_Image_Emotion_Classification)
	
	<br />
	
# 연락처 및 링크
 - 이메일 : LSN.Autumn@gmail.com
 - 링크드인 : https://www.linkedin.com/in/guhyup-lee-884a992b7/