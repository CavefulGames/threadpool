# 한국어

## threadpool
별도의 스레드에서 지정된 함수를 실행하게 할 수 있으며 스레드를 풀링하여 재사용가능하게 만듭니다.

### 특징
- 매우 작고 단순한 모듈이며 `task.spawn`을 스레드를 재사용하여 최적화하여 사용하기에 유용합니다.
- 원본: [util.luau/threadpool](https://github.com/lukadev-0/util.luau/blob/main/packages/threadpool/init.luau)
- 원본에서 `pure luau`, `lune` 지원 기능을 제거하였습니다. 덕뿐에 별도의 모듈(std.task)가 필요없어 간소화 되었습니다.
- 별도의 스레드에서 함수 실행 및 스레드 재사용 지원

### 설치
#### pesde
```sh
pesde add caveful_games/threadpool
```
