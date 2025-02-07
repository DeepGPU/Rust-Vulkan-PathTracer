# 자기소개(자유형식)
2001년에 게임 제작을 처음 시작한 이후, 렌더링과 물리 분야에서 독보적인 커리어를 쌓고 싶다는 열망에 전공을 수학으로 선택했습니다. 처음에는 수학을 단순히 프로그래밍을 위한 도구로만 여겼지만, 수학을 깊이 이해하려면 순수하게 수학 자체에 몰두해야 한다는 것을 깨달았습니다. 그렇게 수학에 대한 깨달음을 얻기 위해 오랜 시간을 투자했고, 결국 박사 학위까지 이르게 되었습니다.

2017년 시그래프 학회에서 레이트레이싱과 리얼타임 패스트레이싱의 가능성을 보고 큰 영감을 받았고, 그때부터 틈나는 대로 패스트레이싱에 대한 R&D를 진행했습니다. 첫 직장이자 국내유일의 자체제작 게임엔진을 보유하고 있던 P사에서 레이트레이싱의 중요성에 대해 여러차례 설득했었지만, 당시 RTX 기술이 등장하기 전이고 게임 제작에서 레이트레이싱이 적용된 사례가 거의 없었기에 회사에서는 크게 관심을 안보이고 관련 작업을 진행할 수 없었습니다. 이후에도 개인적으로 패스트레이싱을 고도화하려 했지만, 시간과 비용의 제약으로 언리얼 엔진과 리얼타임 렌더링에 집중하며 커리어를 쌓아왔습니다.

가장 최근에는 회사에서 WebGPU를 활용해 패스트레이서를 웹에서 구현하는 프로젝트를 주도했습니다. 이를 통해 ***리얼타임 패스트레이싱*** 기술이 제가 소홀했던 지난 6년간 엄청난 발전을 이루었다는 사실을 알게 되었고, 특히 NVIDIA의 패스트레이서 연구진이 CD Projekt와 협업해 Cyberpunk 2077에 ***리얼타임 패스트레이싱***을 적용한 사례를 보고 큰 충격을 받았습니다. 이 경험을 계기로 최소한 한국에서는 최초로 대규모 씬을 지원하는 ***리얼타임 패스트레이싱***를 제작하고자 팀을 꾸려 사이드 프로젝트를 시작했습니다.

위에서 말씀드린 것처럼, 저는 렌더링에 대한 남다른 열정을 가지고 있습니다. 그리고 렌더링에 필요한 핵심 전문지식은 두 가지, 바로 GPU에 대한 깊은 이해와 탄탄한 수학적 기반을 바탕으로 한 렌더링 지식이라고 생각합니다. 네이티브 구현 방식을 선호하는 저는 DirectX 12, Vulkan, CUDA, OptiX, DXR 등에 익숙하며, 관련 프로젝트 경험도 풍부합니다. 렌더링 이론에 대해서는 감히 국내 최고 수준이라고 자부합니다. 그동안 여러 커뮤니티, 학계, 회사 생활을 거치며 렌더링 이론으로 깊이 있는 대화를 나눌 상대를 만나본 적이 없었습니다.

이제 앞으로의 목표는 한국을 넘어 글로벌 무대에서도 인정받는 리얼타임 패스트레이싱 기술을 선도하는 것입니다. 단순히 기술 구현에 그치지 않고, 렌더링 기술로 새로운 시각적 경험을 제공하는 혁신을 이끌고자 합니다. 또한, 렌더링 이론과 실무 경험을 바탕으로 다음 세대 개발자들에게 영감을 주고, 함께 성장하는 커뮤니티를 만드는 것이 저의 꿈입니다. 이를 통해 국내 그래픽스 기술 수준을 한 단계 끌어올리는 데 기여하고, 세계 무대에서 당당히 경쟁할 수 있는 개발 문화를 구축하고 싶습니다.

<br>
<br>

# 경력기술서
### *<p style="color: orange;">Video editor based on WebGPU Path Tracer</p>*
#### (RebuilderAI)  2024.06 - 2024.12  
#### 직무: 프로젝트 전체 총괄 및 핵심 구현  
    (요약)
    · Photo-realistic renderer on web, aimed at visualizing scanned object  
    · Auto video recording for product advertisement 

    (내용상세) 
    기획자 2명, 디자이너 2명, 개발자 본인포함 2명으로 이루어진 프로젝트로 웹의 그래픽스 신기술인 webgpu를 사용해서 웹브라우저에서 구동되는
        1. 프로덕션 퀄리티의 패스트레이서를 구현하고, 
        2. 이를 응용해 비디오 에디터를 만드는 것
    과 같은 프로젝트를 진행하였습니다. 2025 CES 박람회 출품을 데드라인으로 작업을 해서 완료하였고, 이후로는 비지니스 모델을 찾지 못해서 현재는 중단되었습니다. 주로 사용된 언어는 자바스크립트와 타입스크립트, glsl 그리고 약간의 rust가 사용되었습니다
<br>

### *<p style="color: pink;">인버스 렌더링 R&D 및 기타 업무</p>*
#### (RebuilderAI)  2023.10 - 2024.05  
#### 직무: 프로젝트 전체 총괄 및 핵심 구현  
    (요약)
    1. Glossy object capture (RebuilderAI) 
        · Using SOTA neural inverse rendering techniques 
        · Capturing glossy objects 
        · With high performance (within a few minutes) 

    2. Mitsuba3 appearance capture (RebuilderAI) 
        · Aimed at refine mesh from output of photogrammetry’s result 
        · Aimed at capturing PBR materials 

    3. Synthetic data generation using nVidia's Omniverse
        · Generation of vast synthetic data for training

    (내용상세)
    회사의 요구에 따라 주로 pbr재질 복원을 위한 인버스 렌더링에 대한 r&d를 진행했었습니다. 이 외에도 수많은 잡일 들이 많이 있는데 내용에는 포함하지 않았습니다.
    주로 논문을 구현하는 일이거나 기존 오픈소스들을 테스트 하는 일이었고 대부분 파이썬을 사용했지만, 종종 c++, cuda, 언리얼도 사용해서 문제들을 해결 했습니다.
<br>

### *<p style="color: lime;">Facial Appearance Capture 시스템 설계 및 구현</p>*
#### (Metaverse entertainment)  2022.10 - 2023.05  
#### 직무: 프로젝트 전체 총괄 및 핵심 구현  
    (요약)
    · Designed high-resolution 60fps facial appearance capture system 
    · Supervised total pipeline 
    · Implemented a specialized renderer for face using DirectX Raytracing 
    · Implemented a inverse renderer based on google’s Ceres solver 

    (내용상세세)
    회사 내 두 팀(약 10명)이 진행했던 프로젝트로, 배우의 얼굴 표정 연기를 캡쳐하여 게임이나 메타버스에 들어갈 배우의 리얼한 모습이 그대로 담긴 메타 휴먼을 제작하는 프로젝트였습니다. 꽤 장기 프로젝트로 캡쳐 장비 및 시스템 설계부터 관련된 multiview-stereo기술 구현, optical flow를 이용해 frame간 mesh topology consistency 맞추기, 인버스렌더링을 통한 pbr복원 및 잔 주름 및 모공 수준의 micro geometry 복원 등의 모든 survey를 담당했고 core알고리즘들은 제가 prototype으로구현해서 배포 하였습니다. 주로 사용한 언어 및 api는 python, cuda, c++, directx12 입니다.
<br>

### *<p style="color: cyan;">Overprime 게임 제작</p>*
#### (Netmarble F&C)  2021.03 - 2021.10  
#### 직무: 개임 내 라이팅 정책 결정 및 최적화 
    (요약)
    · 3D TPS MOBA game project targeting PC 
    · Performance optimization 
    · Global lighting decision & Lighting build 
    · VFX R&D using Niagara

    (내용상세)
    빌드 업 중인 팀에 첫 프로그래머로 들어갔지만, 결국 빌드 업이 되지 않고 타 팀에 helper로 들어가서 주로 최적화 관련 일을 맡았습니다. 그 팀의 프로젝트는 언리얼을 커스터마이징을 하진 않기로 해서, 엔진프로그래머서의 역활이 많이 제한적이었습니다. 
<br>

### *<p style="color: brown;">Project EVE(현 Stellar Blade)  게임 제작</p>*
#### (ShiftUp)  2020.03 - 2021.02  
#### 직무: 엔진 커스터마이징 및 렌더링 관련 이슈 해결 
    (요약)
    · AAA soul-like action game project targeting PS4/5 and PC 
    · Customized UE4 engine for the requests of artists 
    · Researched new real-time rendering techniques 
    · Improved the rendering results of the game 
    · Applied DLSS and DDGI to the customized UE4 engine

    (내용상세)
    주로 아티스트와 소통하며 필요한 기능들을 엔진 커스터마이징을 통해 제공하였고, 렌더링 피쳐들을 제대로 잘 사용하게 하기 위한 아티스트 지도도 많이 하였으며, 렌더링 관련한 이슈나 버그들을 전부 해결 하였습니다. 또한 당시 aaa게임에 거의 필수로 포함되었던 dlss를 nvidia의 도움없이 테스트 해보길 원했는데, 그러기 위해서는 두 개의 완전히 다른 언리얼 커스트마이징 버전(nvidia의 공식 언리얼 커스트마이징 버전과 회사의 언리얼 커스트마이징 버전)을 합쳐야만 했습니다. 제가 단독으로 진행해서 결국 2주만에 성공적으로 dlss테스트를 진행 할 수 있었고, 생각보다 별로였던 dlss의 성능에 회사에서는 채택하지 않는 결정을 함으로서 많은 비용을 절감 할 수 있었습니다.
<br>

### *<p style="color: green;">AI in Game Engine</p>*
#### (PearlAbyss)  2018.05 - 2020.03   
#### 직무: 개임 내 적용 될 AI기술 R&D 
    (요약)
    1. DXR Path Tracer (PearlAbyss)  
        · Implemented a brute force Monte Carlo path tracer using DirectX Raytracing  
        · Implemented material-specific Monte Carlo importance sampling techniques  
        · Implemented light-specific Monte Carlo importance sampling techniques  

    2. Face Customization from Image (PearlAbyss)  
        · Built entire solution for auto-customization for in-game character  
        · Head pose estimation using face alignment technique and POSIT algorithm  
        · Mesh reconstruction using 3D face morphable model and solving linear system of PCA  
        · Customization parameter searching for actual in-game character  

    3. Deep Learning Super Resolution (PearlAbyss)  
        · Implemented several papers on the subject using PyTorch  
        · Customized the neural networks for real time rendering  
        · Implemented a DLSR up-sampling technique in a game engine 

    (내용상세)
    ai에 대한 관심이 커지면서 게임 회사에서도 ai에 대한 기대와 필요에 의해 관련된 업무들을 맡아서 스스로 계획해서 진행하고 게임 엔진팀과 게임 내 적용에 대해 소통하는 업무를 맡아 진행하였습니다.
