# mecabInstallGuide
mecab install guide



# 1. 본인의 C:/ 드라이브에 mecab폴더 생성 -> C:/mecab


# 2. mecab-ko-msvc 설치(c 기반인 mecab이 윈도우에서 실행 될 수 있도록)
아래 링크에서 본인의 윈도우 32bit/64bit 확인 후 선택하여  최신 버전 다운로드
 https://github.com/Pusnow/mecab-ko-msvc/releases/tag/release-0.9.2-msvc-3

2021/07/04 기준 release-0.9.2-msvc-3
다운 받은 zip파일을 mecab폴더에 압축을 푼다. (하위 폴더가 생기지 않고, 파일만 풀어지도록)


# 3. mecab-ko-dic-msv 설치
아래 링크에서 본인의 윈도우 32bit/64bit 확인 후 선택하여 최신 버전 다운로드
https://github.com/Pusnow/mecab-ko-dic-msvc/releases/tag/mecab-ko-dic-2.1.1-20180720-msvc-2


2021/07/04 기준 mecab-ko-dic-2.1.1-20180720-msvc-2
다운 받은 zip파일을 mecab폴더에 압축을 푼다. (하위 폴더가 생기지 않고, 파일만 풀어지도록)


# 4. python wheel 설치하기
아래 링크에서 본인의 python 버전을 확인 후 32비트/64비트 선택하여 최신다운로드
https://github.com/Pusnow/mecab-python-msvc/releases/tag/mecab_python-0.996_ko_0.9.2_msvc-3


파이썬 3.8에 윈도우 64bit 이므로 -> mecab_python-0.996_ko_0.9.2_msvc-cp38-cp38-win_amd64.whl

다운로드 받은 파일을 site-package 폴더에 옮긴다.
(아나콘다 사용자 경우 base) C:\Users\사용자명\Anaconda3\Lib\site-packages) 
(가상환경 사용 경우)           C:/Users/사용자명/Anaconda3/envs/가상환경명/Lib/site-packages
아나콘다를 쓰면 anaconda prompt를 킨 후/ 가상환경을 안쓰면 cmd 창을 킨 후 site-package 폴더로 이동 후 pip로 설치
