TOEIC MASTER PWA – 배포 패키지

[구성]
- index.html: 앱 본체
- manifest.json: PWA 설치 정보
- service-worker.js: 오프라인 캐시
- icons/: 앱 아이콘

[배포]
1. ZIP 압축을 해제합니다.
2. 폴더 안의 파일과 icons 폴더를 통째로 HTTPS 정적 호스팅에 업로드합니다.
   예: GitHub Pages, Netlify, Cloudflare Pages 등
3. 배포된 HTTPS 주소를 iPhone Safari에서 엽니다.
4. Safari 공유 버튼 → '홈 화면에 추가' → 추가를 누릅니다.
5. 홈 화면의 TOEIC MASTER 아이콘으로 실행합니다.

중요:
- PWA 설치에는 HTTPS 또는 localhost가 필요합니다.
- index.html 파일을 아이폰에서 직접 여는 방식(file://)으로는 PWA 설치 및 서비스 워커가 동작하지 않습니다.
- 앱 데이터는 기본적으로 해당 iPhone 브라우저의 로컬 저장소에 저장됩니다.
- Safari 웹사이트 데이터 삭제 또는 기기 변경 전에 앱의 설정에서 '학습 데이터 백업 내보내기'를 이용하세요.
- 이 버전은 초기 콘텐츠 20개 단어, 12개 자체 제작 Part 5 문항을 포함한 작동형 초기 버전입니다. 최근 4개년 전체 기출 DB나 공식 기출문제는 아닙니다.
- 로그인/클라우드 동기화/앱스토어 등록은 포함하지 않습니다.
