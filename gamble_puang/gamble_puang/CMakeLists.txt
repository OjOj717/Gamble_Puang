cmake_minimum_required(VERSION 3.10)
project(GamblePuang)

# 현재 폴더(.)에 있는 모든 .cpp 파일을 찾음
file(GLOB SOURCES "*.cpp")

# 실행 파일 생성
add_executable(gamble_puang ${SOURCES})