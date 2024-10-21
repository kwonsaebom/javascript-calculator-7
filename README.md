## 🎯 기능 요구사항

#### 문자열 입력

- [x] 사용자에게 문자열을 입력 받는다.

#### 구분자 처리

- [x] `,` 또는 `:` 를 구분자로 각 숫자를 분리한다.
- [x] 빈 문자열 처리 (`"" => 0`)

#### 커스텀 구분자 처리

- [x] 문자열이 `//`로 시작하고 `\n` 사이에 위치한 문자를 커스텀 구분자로 사용한다.
- [x] 커스텀 구분자를 기준으로 각 숫자를 분리한다.

#### 숫자 합산

- [x] 분리된 숫자를 합산한다.

#### 결과 출력

- [x] 합산한 결과를 출력한다.

#### 오류 처리 (`[Error]`)

- [ ] 입력 값에 숫자외의 값이 포함된 경우 (`"1,a,3" => [Error] Invalid input`)
- [ ] 커스텀 구분자 형식이 올바르지 않은 경우 (`"//;\n1;2,3" => [Error] Invalid custom format`)
- [ ] 입력 값에 음수가 포함된 경우 (`"1, -2, 3" => [Error] Negative numbers not allowed: -2`)
- [ ] 애플리케이션을 종료한다.
