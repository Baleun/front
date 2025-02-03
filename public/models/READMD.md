# Insert 3D Model

```
1.
https://poly.pizza/ 와 같은 3D 모델 제공 사이트에서 GLB 형태의 모델을 다운한다. 여기서는 예시로 Skyscraper.glb 파일을 다운받겠다

2.
public/models 에 저장한다

3.
glftjsx를 사용해서 모델을 컴포먼트화 시킨다
Command: npx gltfjsx@6.2.3 public/models/Skyscraper.glb -o src/components/Skyscraper.jsx -r public

4. 
src/components/Skyscraper.jsx 위치에 파일이 생성된 것을 확인한다
원하는 위치에서 불러온다
<Skyscraper.jsx>
```