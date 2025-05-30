<details>
  <summary><strong>`==`과 `===`의 차이가 무엇인가요?</strong></summary>

<br>

## ==
"=="는 동등 연산자로, 두 값을 비교할 때 형변환(type coercion)을 수행합니다.
즉, **비교하는 값의 데이터 타입이 다르더라도 자동으로 형변환을 수행한 후**에 비교합니다.
이러한 형변환은 때로 예측하지 못한 결과를 초래할 수 있으므로, "=="를 사용할 때는 조심해야 합니다.

## ===
"==="는 일치 연산자로, 두 값이 데이터 타입과 값이 모두 같은지 비교합니다.
따라서 "==="를 사용하면 **형변환 없이 정확한 값**을 비교할 수 있습니다.
이러한 일치 연산자를 사용하는 것이 더 안전하고 예측 가능한 결과를 얻을 수 있습니다.
  
</details>
