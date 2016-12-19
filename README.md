#SSproject

★ssproject.sql을 이용하여 데이터베이스 구축

★./include/conf.php 내용을 수정하여 서버환경 셋팅

★../key/ 폴더에 쓰기권한 부여 [사용자 인증 및 공개키 저장을 위함]

★./file_tmp/ 폴더에 쓰기권한 부여 [임시파일 생성 및 삭제를 위함]

암호화 스펙
 - RSA 1024를 통한 파일 암호화
 - AES 256을 통한 RSA 개인키 암호화
 
사용자 인증
 - 암호화된 개인키를 업로드하고, AES 대칭키를 입력하여 사용자 인증 수행
 
메일링 기능
 - 채용서류 열람(다운로드) 시 등록된 이메일에 알람기능 제공
 - 채용서류 파기 시 등록된 이메일에 알람기능 제공
