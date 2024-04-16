이 글의 댓글로 중간고사 시험 문항을 출제 해 주시고, SmartLMS에도 제출 하시오. (개인별 3문항)

다른 학생의 문항과 중복된 문항은 올리지 마세요.

​

[4문 1택 문항]

이 수업에서 활용한 컴퓨터 언어는?

1) C++

2) Rust

3) JavaScript

4) Java

답) 3)

​

[괄호 메우기]

p5js에서 3차원을 활용하려면 다음에 적합한 단어를 적으시오.

createCanvas(800,600, [#]);

답) WEBGL

​

[단답형]

p5.js에서 부드러운 지형을 만들기 위해 활용 가능한 노이즈 함수는 ( )함수 이다.

답) noise

프로필 사진심재창님의 게시글 더보기 
좋아요0
이 글을 '좋아요'한 멤버 리스트 댓글10
 공유
신고
클린봇이 악성 댓글을 감지합니다.
설정
댓글
등록순최신순새로고침
관심글 댓글 알림
등록
프로필 사진
김준영
[4문 1택 문항]

재질과 관련 없는 것은?
1) normalMaterial()

2) ambientMaterial()

3) emissiveMaterial()

4) planeMaterial()

답) 4)

​

[괄호 메우기]

ANU글자 출력하기 위해 빈칸을 채우시오

function setup() {
createCanvas(800, 800);
textSize(100);}

function draw() {
background(220);
_____("ANU",100,250);
}

답) text

​

[단답형]

( )은 웹 브라우저에서 GPU 가속을 이용한 3D 그래픽을 그리기 위한 JavaScript API입니다. 이것은 무엇인가

답) WebGL

2024.04.16. 15:16 답글쓰기
프로필 사진
20191126 손정우
[4문 1택 문항]

opengl을 활용한 것이 아닌것은?



1)opengl directX

2)opengl WEBGL

3)opengl WEBGPU

4)opengl WEBCPU


답: 4)opengl WEBCPU





[괄호 메우기]

마우스로 펜만들기를 하는 코드이다 ㄱ,ㄴ,ㄷ,ㄹ에 알맞은 코드를 적으시오

function setup()

{ createCanvas(windowWidth, windowHeight);
stroke(0,125,0);
strokeWeight(8);

}

function draw()

{ if(mouseIsPressed)

line(ㄱ,ㄴ,ㄷ,ㄹ);

}

답: ㄱ :pmouseX, ㄴ: pmouseY, ㄷ: mouseX, ㄹ:mouseY


[단답형]

perspective는 어떤 것을 나타내는 단어인가?


답: 광원



2024.04.16. 15:59 답글쓰기
프로필 사진
20180684 오예준
[4문 1택 문항]

다음 중 WebGL에 대한 설명으로 옳은 것은

1) 웹페이지에서 2D와 3D 그래픽을 구현할 수 있다.

2) 서버 구축을 위한 프로그래밍 언어다.

3) 하드웨어를 조작하기 위한 라이브러리다.

4) 2D만 구현 가능하다.

답) 1)

​

[괄호 메우기]

p5js에서 타원을 생성하려면 다음에 적합한 단어를 적으시오.

#(0,50, 33,33);

답) ellipse

​

[단답형]

웹브라우저에서 사용자의 GPU를 사용할 수 있는 기술은?

답) WebGPU

2024.04.16. 15:13 답글쓰기
프로필 사진
20191124 박준범
1. 이 수업에서 웹 기반 3D 그래픽을 만들기 위한 JavaScript 라이브러리는?
1) three.js
2) jQuery
3) React.js
4) TensorFlow

정답 : 1) three.js

2. ​Three.js에서 가장 일반적으로 사용되는 두 가지 카메라 유형은 무엇입니까?

정답: PerspectiveCamera와 OrthographicCamera

3. 다음은 three.js에서 3D 객체에 적용되는 속성 중 하나로, 객체의 외관을 결정합니다. 이것은 객체의 표면을 채우는데 사용되며, 색상, 질감 및 광택과 같은 특성을 제어합니다. 빈칸에 들어갈 말은 무엇입니까?

three.js에서 _____(을)를 사용하여 3D 객체의 외관을 결정할 수 있습니다.

정답: Material

2024.04.16. 15:15 답글쓰기
프로필 사진
20191125박형민
1. p5.js에서 정육면체를 만들려고 한다 다음중 맞는것은? 답 1)

1) box
2) square
3) sphere
4) torus


2. p5.js에서 키보드를 통해 조작하는 부분을 넣을려고 한다 다음에 적합한 단어를 적으시오. 답 keyPressed)

function ___________(){
s = key - '0';
}


3. p5.js에서 조명에 영향을 받지않는 기본 재질을 나타내는 것은 ________ Material()이다. 답 normal)

2024.04.16. 16:00 답글쓰기
프로필 사진
18김성현
4문1택
다음 중 선행 초기화 코드가 필요한 광원을 고르시오.
1) DirectionalLight
2) SpotLight
3) AmbientLight
4) RectAreaLight

정답: 4

괄호 채우기
다음 코드에서 '금속성'을 조정하기 위해 추가할 코드를 적으시오.
const material = new THREE.MeshStandardMaterial({
roughness: 0.5,
( ): 0.5
});

정답: metalness


단답

물체간의 거리감(원근감)을 적용하지 않고 크기를 그대로 표현하여 렌더링 하고 싶을 때 사용하는 카메라는 ''" 이다.

정답: OrthographicCamera

2024.04.16. 15:18 답글쓰기
프로필 사진
전찬빈
[4문 1택 문항]
three.js 에서 Object3D의 파생 클래스가 아닌 것은?
1. Points
2. Line
3. Mesh
4. Scene
답) 4. Scene

[괄호 메우기]
three.js에서 Scene를 구성하는 기본 요소는 ____와 ____ 로 구성되어 있다.
답) Mesh(Object3D), Light

[단답형]
p5.js에서 키보드를 사용하기 위해 입력하는 명령어는?
답) keyIsPressed

2024.04.16. 16:05 답글쓰기
프로필 사진
김태훈
WebGPU 와 WebGL의 대해서 알맞은 것은?

1) WebGL은 최신 GPU 기능을 광범위하게 활용하고 , 높은 성능 및 효율성을 제공한다.
2) WebGPU는 현재 대부분 웹브라우저에서 지원이 되고 널리 사용되고 있다.
3) WebGL은 GPU 활용이 WebGPU에 비해 제한적이다.
4) WebGL은  더 부드럽고 빠르며 효율적인 그래픽 렌더링을 보장합니다.

정답 : 3



2024.04.16. 15:23 답글쓰기
프로필 사진
이재경
[4문 1택 문항]
p5js에서 윤곽선을 그리지 않도록 설정하는 함수는?
1) noStroke() 2) noFill() 3) stroke() 4) erase()
답) 1) noStroke()

[괄호 메우기]
사용자가 지정한 각도 매개변수에 따라 도형을 회전하려고 한다 빈칸을 채우시오

translate(width / 2, height / 2);
_______(PI / 3.0);
rect(-26, -26, 52, 52);

답) rotate

[단답형]
p5js에서 사용자가 지정한 반지름과 튜브 반지름으로 원환을 그리는 함수는?
답) torus()

2024.04.16. 16:06 답글쓰기
프로필 사진
김태윤
[4문 1택 문항]
다음중 기본 Geometry가 아닌것은 -4-

1- **BoxGeometry**: 직육면체 형태의 Geometry.

2- **SphereGeometry**: 구 형태의 Geometry.

3- **CylinderGeometry**: 원통 형태의 Geometry.

4- **TorusRingGeometry**: 도넛링 모양의 Geometry.

[괄호 메우기]
Three.js에서 `Scene`, @@@,`Mesh` (Object3D의 하위 클래스), `Material`, `Geometry`는 3D 장면을 만들기 위해 상호작용하는 핵심 구성 요소들입니다.
@@은 무엇인가요.

-`Light`-

[단답형]
**Three.js에서 빛의 영향을 받지 않고 단순한 색상이나 텍스처만을 가지는 재질의 이름은 무엇인가요?**

- 답: MeshBasicMaterial
