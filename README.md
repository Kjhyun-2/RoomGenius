<h1>
  <img src="https://github.com/user-attachments/assets/54e33ebc-a2e8-4c5c-bcbe-5884f31c970e" alt="Logo" width="35">
  RoomGenius
</h1>


## 📑 Content

1. [📖 About](#-about)
3. [🛠 Features](#-features)
4. [🎥 Demo](#-demo)
5. [Team](#team)
6. [Install](#install)
7. [Requirements](#requirements)
8. [Difference](#difference)
9. [AI](#ai)
10. [FullStack](#fullstack)
   	- [Front-End](#front-end)
   	- [Back-End](#back-end)
11. [기대효과](#기대효과 )
12. [WorkFlow](#-workflow)
---
   
## 🏡 AI 기반 개인 맞춤형 인테리어 디자인 플랫폼 

해당 프로젝트는 2024학년도 1학기 캡스톤 디자인 프로젝트 입니다.

### [Mainpage]


https://github.com/user-attachments/assets/acbcb6ce-a6dc-4879-bd1b-96509d83c9ba


최근 사람들의 개성과 취향을 반영한 맞춤형 공간 설계에 대한 관심이 꾸준히 늘어나고 있습니다. 특히 인테리어에 대한 열풍이 불면서, 많은이들이 자신의 공간을 직접 꾸미고 디자인하려는시도를 하고 있습니다. 그러나 디자인 경험이 부족한 사람들에게는 가구 배치나 색상 조합 같은 과정이 어렵게 느껴지기 마련입니다. 전문가의 도움을 받을 수도 있지만, 이는 시간과 비용 부담이 커서 선뜻 시도하기 어려운 경우가 많습니다. 이러한 이유로, 누구나 간편하게 자신의 취향을 반영한 인테리어를 계획할 수 있는 도구의 필요성이 증가하고 있습니다.   

## 📖 About
RoomGenius는 AI를 활용하여 개인 맞춤형 인테리어를 제공하는 플랫폼입니다.
텍스트 입력과 이미지를 업로드하면, AI가 공간의 특성을 분석하고 디자인 스타일에 맞는 인테리어 이미지를 생성합니다.

## 🛠 Features
1. 텍스트 기반 인테리어 이미지 생성: 사용자가 제공한 텍스트 프롬프트에 맞는 공간 이미지를 생성
2. 이미지 기반 인테리어 추천: 업로드된 이미지의 특성을 분석하고, 사용자의 스타일에 맞는 공간 설계를 제안
3. 가구 및 소품 추천: 생성된 디자인에 적합한 IKEA 가구와 소품 정보를 제공하여 현실적인 구매 현실화
4. 번역 및 다국어 지원: 텍스트를 자동으로 영어로 번역하여 글로벌 사용자를 지원

## 🎥 Demo
### [img와 프롬프트를 통한 방 이미지 생성]                                                                             
프롬프트 : 따뜻한 붉은색 벽난로와 어두운 회색 러그로 꾸며진 크리스마스 트리와 금색 장식의 인테리어(아랍어)

https://github.com/user-attachments/assets/c5ff8baf-8d9d-416d-94fe-123eb0fe0c17
<table align="center">
  <tr>
    <td align="center">
      <img width="330" src="https://github.com/user-attachments/assets/7a0c1d5f-3aa8-4082-933f-e8edbc084854" alt="이미지투원본">
      <br>
      <strong>이미지 원본</strong>
    </td>
    <td align="center">
      <img width="330" alt="이미지투결과" src="https://github.com/user-attachments/assets/7a50e314-50fa-4c5d-a4c8-ba141ee8421e">
      <br>
      <strong>생성된 결과</strong>
    </td>
  </tr>
</table>

 ----------------------------------------------------------------------------
  
### [text를 이용한 방 이미지 생성]                              
프롬프트 : 스타워즈 테마의 침실, 어두운 우주 배경 벽지와 LED 조명이 설치된 인테리어

https://github.com/user-attachments/assets/49c766fe-b80a-49f3-b214-8b82378ddca8

------------------------------------------------------------------------
### [Sketch된 이미지와 프롬프트를 통한 방 이미지 생성]                


https://github.com/user-attachments/assets/678f76a9-7f95-4c8f-a18e-a2cb9efe93a6


| ![스케치](https://github.com/user-attachments/assets/8ffa87e8-0e6c-429b-8c31-09cb07e882cc) | ![이미지1](https://github.com/user-attachments/assets/e566ed5d-9a15-40c8-b4a8-70f1b0cf4e78) | ![이미지2](https://github.com/user-attachments/assets/a4825b5a-4fab-4d36-9af4-bee0ecd3ed0f) | ![이미지3](https://github.com/user-attachments/assets/2c6d092f-e4c6-4c09-a52a-352190e48a2c) |
|---|---|---|---|
| 스케치 | 이미지 1 | 이미지 2 | 이미지 3 |

-----------------------------------------------------------------------
### [inpainting을 통한 방 이미지 생성]


https://github.com/user-attachments/assets/6460d9ae-ac98-4432-aa74-1dcded53cb7b

                                 
## Team

HaHaHa

|Name|Department|Contact|
|---|---|---|
| Kang Ji Hyun | Major of Bigdata | kangjihyunlo@naver.com|
| Hwang Seo Yeon | Major of Bigdata |cindyand1q2@gmail.com|
| Lee Gun Hee | Major of Smart IoT |sjwwiies2829@gmail.com|

coach 
|Name|Department|Contact|
|---|---|---|
| Sung Hoon Lim | Hallym Univ (Prof.) |shlim@hallym.ac.kr|


## Install

```python
conda install -c conda-forge pyngrok  
conda install -c conda-forge flask-socketio  
conda install -c anaconda flask  
conda install -c conda-forge diffusers  
conda install -c conda-forge pytorch torchvision torchaudio cudatoolkit=11.8  
```

## Requirements
```
Python Version: 3.7 ~ 3.9

CUDA Version: 11.8
cuDNN Version: 8.1.1

Core Libraries:
- flask==2.0.3
- flask-socketio==5.1.0
- pyngrok==5.1.0
- diffusers==0.31.0
- pytorch==2.3.1
- torchvision==0.18.1
- transformers==4.46.2

Optional Tools:
- einops==0.3.0
- pillow==10.4.0
- tqdm==4.66.6
```

## Difference
<p align="center">
    <img src="https://github.com/user-attachments/assets/e5de7d47-049a-4ebc-9211-980a44e57cc0" height="500" alt="image">
</p>

## AI
#### -이미지-텍스트 변환(img2img) -Stable Diffusion v1.5     
사용자가 업로드한 이미지를 기반으로 텍스트 프롬프트와 결합하여 새로운 공간 디자인 이미지를 생성합니다. 예를 들어, 방 사진에 특정 스타일(모던, 미니멀리즘 등)을 적용하여 변환된 결과를 제공하며, 사용자 요구에 따라 세부적으로 조정 가능합니다.

#### -텍스트-이미지 변환(txt2img) -stabilityai/stable-diffusion-2-1         
사용자가 입력한 텍스트 프롬프트를 기반으로 AI가 새로운 공간 이미지를 생성합니다. "따뜻한 색감의 벽난로와 금색 장식의 크리스마스 인테리어"와 같은 구체적인 프롬프트를 입력하면 이에 적합한 이미지를 제작합니다.

#### -인페인팅(Inpainting) -- Stable Diffusion XL (SDXL) Inpainting-1.0            
특정 이미지의 결함을 수정하거나 특정 영역을 선택적으로 재설계합니다. 이를 통해 사용자는 기존 공간 이미지를 기반으로 소품 추가, 배경 수정, 색상 변경 등 다양한 작업을 수행할 수 있습니다.

#### -프롬프트 분석 및 번역 (LLM) -- Stable Diffusion XL (SDXL) Inpainting-1.0               
사용자가 입력한 텍스트 프롬프트를 GPT 기반의 언어 모델(LLM)을 통해 분석하고 번역합니다. 다국어 지원을 통해 글로벌 사용자들이 플랫폼을 이용할 수 있도록 영어로 변환된 정확한 프롬프트를 제공합니다.

## FullStack 
### Front-End
- React 기반 UI 구성: 사용자 친화적인 UI 설계.
- 실시간 업데이트: 이미지 생성 상태 및 결과를 즉각적으로 반영.
- 반응형 디자인: 다양한 디바이스에서 최적화된 사용 경험 제공.
### Back-End
- 텍스트 또는 이미지 업로드: 사용자는 텍스트 프롬프트를 입력하거나 이미지를 업로드합니다.
- AI 모델 처리: 업로드된 데이터를 기반으로 AI가 새로운 공간 이미지를 생성합니다.
- IKEA 연동: 생성된 이미지와 관련된 추천 가구 및 소품 목록을 제공합니다.
- 결과 활용: 사용자는 결과물을 활용해 실제 인테리어 구현 계획을 세울 수 있습니다.


## 기대효과 
![image](https://github.com/user-attachments/assets/38f7bee0-d92b-45c6-b672-1f13a8816786)
![image](https://github.com/user-attachments/assets/bd0b5e53-77a0-4793-8219-27295381992e)





