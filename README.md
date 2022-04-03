cg_terrain_project_team9
저희 조는 p5.js web editor 로 WEBGL로 프로젝트를 진행하였으며 먼저 지난번 terrain 예제 소스코드를 이용하여 3차원 지형을 생성하였습니다.

3차원 지형의 변형에서 주제는 밤바다와 바다를 비추는 등대로 구성하였습니다.

noise와 색을 수정하여 3차원 지형을 바다형태로 만들기
image

Camera()를 이용해 마우스를 누를 시 바다중앙을 확대하여 포커스를 맞추기
image

ambientLight와 pointLight를 이용해 마우스에 움직임 따라 등대불빛 비추기
image image

사물의 색 그대로 빛반사가 되어지는 ambientMaterial로 3D등대와 군함 상어지느러미 만들기
image

군함은 왼쪽에서 오른쪽으로 움직이며 끝에 도착할 시 처음부터 다시 출발, 상어지느러미는등대불빛과 함께 마우스의 움직임에 따라 따라다니게 만듦.
