# Kong API Gateway Opensource Version (Free)
# ทดแทน API Gateway Java Spring Boot

# deploy
docker-compose -f CICD/DEV.yml down
docker-compose -f CICD/DEV.yml build
docker-compose -f CICD/DEV.yml up
