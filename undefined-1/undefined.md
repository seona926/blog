# 프로그래머스 - 서울에서 김서방찾기

```text
function solution(seoul) {
    var answer = '';
    
    for (let x of seoul) {
        if (x === "Kim") {
            let i = seoul.indexOf(x)
            answer = `김서방은 ${i}에 있다`
        }
    }
    return answer;
}
```

