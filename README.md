# PhoenixZip

Windows용 무료 압축·해제 프로그램입니다. (Windows 10/11, 64비트)

- ZIP · 7Z 만들기와 풀기 (AES-256 암호, 분할 압축, 여러 코어 사용)
- RAR · TAR · GZ · BZ2 · XZ · ZST · CAB · ISO 등 열기와 풀기
- 압축 파일 안에서 바로 편집, 이미지·텍스트·PDF 미리보기, 형식 변환, 자동 풀림 .exe
- 탐색기 우클릭: 각각 압축 · 각각 이름 폴더에 풀기 · 압축 후 메일 보내기 (설정에서 켤 때만)

이 저장소는 **공식 배포처**입니다. 프로그램 파일만 올리며, 소스 코드는 공개하지 않습니다.

## 받기
[Releases](https://github.com/NovacoreWorks/PhoenixZip-Release/releases)에서 `PhoenixZip-버전.zip`을 받아 원하는 곳에 압축을 풀고 `PhoenixZip.exe`를 실행하세요.
설치 과정은 없습니다. 폴더 안의 파일(7z.dll 등)은 함께 두어야 합니다.

## 정품 확인 (SHA-256)
받은 zip 파일의 해시값이 각 Release에 적힌 값과 같은지 확인하세요. PowerShell에서:

```
Get-FileHash .\PhoenixZip-버전.zip -Algorithm SHA256
```

프로그램도 실행할 때 스스로 파일이 바뀌지 않았는지 검사합니다 (인터넷 연결 없이 이 컴퓨터 안에서만).
**이곳이 아닌 곳에서 받은 파일은 누군가 고쳤을 수 있으니 쓰지 마세요.**

## 사용 조건
- 무료 프로그램입니다. 개인·가정·회사 어디서든 쓸 수 있고, 받은 그대로라면 나눠 줘도 됩니다.
- 판매, 끼워 팔기, 고쳐서 배포, 만든이 표시 삭제는 금지합니다.
- 프로그램은 있는 그대로 제공되며, 사용 중 생긴 손해에 대해 만든이는 책임지지 않습니다. 중요한 파일은 미리 백업하세요.
- 자세한 내용은 zip 안의 `사용조건.txt`, 함께 들어 있는 오픈소스(7-Zip 등)의 라이선스는 `오픈소스 고지.txt`를 보세요.
- 인터넷으로 아무 정보도 보내지 않습니다.

## 만든이
NovacoreWorks(LJY) · novacoreworks@gmail.com

© 2026 NovacoreWorks(LJY)
