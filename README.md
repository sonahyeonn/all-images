# 이미지의 갯수가 작게 나올때는 새로고침하면 이미지가 로드 된다
![image](https://github.com/sonahyeonn/all-images/assets/147791395/036e94de-86d1-4a76-be0d-4c2e336c53c8)
↓
![image](https://github.com/sonahyeonn/all-images/assets/147791395/2f7755b6-d871-4bd0-b3bf-c356c6663d58)

# console에 복사 붙여넣기가 안될때는 allow pasting을 써서 초기화 해준다
# console창에 변수를 만든다 

```
var har =
```

# = 뒤에 위에 복사한 내용을 붙여넣는다 그 값은 객체이다

# 객체가 har이라는 변수에 할당되었고 그 아래에

```
var imageUrls = [];
har.log.entries.forEach(function (entry) {
  if (entry.response.content.mimeType.indexOf("image/") !== 0) return;
  imageUrls.push(entry.request.url);
});
console.log(imageUrls.join('\n'));
```

# download.js 안에 내용을 복사하여 console 붙여넣으면 전체 이미지 주소가 일괄적으로 나타난다
![image](https://github.com/sonahyeonn/all-images/assets/147791395/d9a575d8-a06e-42c6-9c77-356eb36ef45f)

# url 주소 이미지 대량 다운 받기
![image](https://github.com/sonahyeonn/all-images/assets/147791395/a35002ca-d8cb-4557-b6a5-0c8ca7020f77)

# vscode에서 적용하는 법
![image](https://github.com/sonahyeonn/all-images/assets/147791395/ecb5cf4e-2fca-46e7-b275-c11c5a748bb0)
