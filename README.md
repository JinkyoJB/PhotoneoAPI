# PhotoneoAPI
PhotoneoAPI motioncam3D용 레파지토리입니다.

### build 방법
<p>PhotoneoAPI$ mkdir dev</p>
<p>PhotoneoAPI$ cd dev</p>
<p>PhotoneoAPI/dev$ cmake .. -DCMAKE_BUILD_TYPE=Release</p>
<p>PhotoneoAPI/dev$ make</p>

### 실행방법
<p>포토네오 센서를 랜선으로 연결한 후, IP address를 할당하세요.</p>
<p>할당한 IP adress 및 장비모델명(ID)을 config.txt에 수정하세요. 해당 내용을 바탕으로 API가 장비 연결을 시도합니다.</p>
<p> dev를 root디렉토리로 해서 아래 명령어로 API를 실행하세요.</p>
<p>PhotoneoAPI/dev$ ./FullAPIExample_Release </p>


