# javascript-calculator-precourse
# 문자열 덧셈 계산기


## 기능 목록
1. 빈 문자열 또는 null 값을 입력할 경우 0을 반환한다.
   - 예: `""`, `null` => 0
2. 쉼표(,) 또는 콜론(:)을 구분자로 사용하여 문자열의 숫자를 더한다.
   - 예: `"1,2,3"` => 6, `"1:2:3"` => 6
3. 커스텀 구분자를 지정할 수 있으며, "//[구분자]\n[숫자...]" 형식으로 구분자를 지정한다.
   - 예: `"//;\n1;2;3"` => 6
4. 음수가 입력될 경우 예외를 발생시킨다.
   - 예: `"1,-2,3"` => [ERROR] 음수는 허용되지 않습니다.
5. 구분자로 구분된 숫자의 합계를 반환한다.
