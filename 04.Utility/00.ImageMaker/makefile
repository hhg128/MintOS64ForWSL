# brief		디스크 이미지를 생성하는 프로그램을 빌드하는 make 파일

# 기본적으로 빌드를 수행할 목록
all: ImageMaker.elf

# ImageMaker 빌드
ImageMaker.elf: ImageMaker.c
	gcc -o $@ $<
	
# 소스 파일을 제외한 나머지 파일 정리	
clean:
	rm -f ImageMaker.elf
