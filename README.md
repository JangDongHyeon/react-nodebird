db 생성.
npx sequelize db:create

pm2
sudo npx pm2 monit 실시간 보기
sudo npx pm2 logs --error
sudo npx pm2 reload all

front
npm run build
sudo npx pm2 start npm  -- start

git pull error 날 경우
git stash
git pull origin master

lamda
zip -r aws-upload.zip ./*
curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"

unzip awscliv2.zip

sudo ./aws/install

aws configure -> key 입력 위치입력 json으로

aws s3 cp "aws-upload.zip" s3://react-bu  // s3 뒤에는 s3 내 저장소 이름

aws s3에서 aws-upload.zip 확인

aws 가서 llamda 생성-> 생성후 s3에서 파일업로드 클릭 -> https://react-bu.s3.ap-northeast-2.amazonaws.com/aws-upload.zip

기본설정가서 메모리 256 정도 제한시간 30초 정도

AWS 정책 템플릿에서 새 역활 생성 ,S3객체 읽기 전용 권한 선택

트리거 추가 s3선택,접두사에 original/ 입력 밑에 다 체크



//https
내 서버 및 프론트 위치가서
 apt-get install nginx
wget https://dl.eff.org/certbot-auto
chmod a+x certbot-auto

admin
react-admin
core-ui
adminLTE
forestadmin
