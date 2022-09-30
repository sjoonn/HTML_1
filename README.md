# <div align="center"> HTML_1(게임 클라이언트 화면) </div>

## <div align="center"> 👋🏻실행 화면 👋🏻</div>

![image](https://user-images.githubusercontent.com/102125786/187585182-6f94198b-3e26-4d65-81da-3f848fdf5e21.png)

## <div align="center"> 📱화면 설명📱  </div>

### 오른쪽 사진은 ```background-image```로 사진을 넣어주었습니다.

![image](https://user-images.githubusercontent.com/102125786/187585567-f2927243-123d-4589-ac3f-907370633166.png)

<br>

### 드롭다운 메뉴를 만들었습니다.

![image](https://user-images.githubusercontent.com/102125786/187585698-bf93cd41-6226-45a2-95a3-82cefe425ce8.png)

<br>

### 제목을 적어주고 위치를 지정해주었습니다.

![image](https://user-images.githubusercontent.com/102125786/187585885-aae7ad5e-cdc3-4c7b-8375-425668e1f68b.png)

<br>

### 소제목을 적어주고 위치를 지정해주었습니다.

![image](https://user-images.githubusercontent.com/102125786/187585948-1e9b2b3e-96a4-4d5a-9245-624c718a637a.png)

<br>

### 아이디를 적어줄 ```textbox```를 만들어주었습니다.

![image](https://user-images.githubusercontent.com/102125786/187586076-7bb15e9f-22e6-45bc-b8c8-a50d65d86d3f.png)

<br>

### 비밀번호를 적어줄 비밀번호 형식에 ```textbox```를 만들어주었습니다.

![image](https://user-images.githubusercontent.com/102125786/187586196-3e959ed8-7b69-4c62-98cc-99103a4cd52b.png)

<br>

### 체크박스를 만들어주었습니다.

![image](https://user-images.githubusercontent.com/102125786/187586282-afb15701-1bb0-4144-9507-ec1ec3f018b6.png)

<br>

### 이미지를 전송 버튼으로 만들어주었습니다.

![image](https://user-images.githubusercontent.com/102125786/187586399-93e4b0ef-7029-4779-a1c1-98c913e50b69.png)

<br>

### 링크가 걸린 글을 만들어주었습니다.

![image](https://user-images.githubusercontent.com/102125786/187586480-5983e714-dfdd-4dae-9dd0-f6cb1a30a48a.png)
![image](https://user-images.githubusercontent.com/102125786/187586487-3f5d40f9-21a7-4e0f-9253-bdff681f6102.png)

## <div align="center"> ✍🏻중요한 내용✍🏻 </div>

### 드롭다운 css코드
```css 
  .dropbtn {
        background-color: #76b2ff;
        color: white;
        padding: 16px;
        font-size: 16px;
        border: none;
        border-radius: 12px;
        }
        
        .dropdown {
        position: absolute;
        top: 10px;
        left: 10px;
        display: inline-block;
        }
        .dropdown-content {
        display: none;
        position: absolute;
        background-color: #f1f1f1;
        min-width: 160px;
        box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
        z-index: 1;
        border-radius: 12px;
        }
        .dropdown-content a {
        color: black;
        padding: 12px 16px;
        text-decoration: none;
        display: block;
        border-radius: 12px;
        }
        .dropdown-content a:hover {background-color: #ddd;}
        .dropdown:hover .dropdown-content {display: block;}
        .dropdown:hover .dropbtn {background-color: #3e8e41;}
```

### 이미지를 전송버튼으로 만든 코드

```html
  <div class="submit">
        <input type="image" src="/img/images.png" id="submit1" alt="전송 버튼" style="width: 70px; height:70px;">
    </div>
```

## <div align="center"> 😅부족한 내용😅</div>
### 화면 크기를 움직이면 화면이 깨진다.
### 위치 조정을 하나하나 다 해주었다.
### 드롭다운에 링크를 안 걸어주었다.




