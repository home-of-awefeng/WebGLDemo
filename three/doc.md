# 几何体 Geometry
threejs 的长方体 BoxGeometry、球体 SphereGeometry 等几何体都是基于 BufferGeometry (opens new window) 类构建的，BufferGeometry 是一个没有任何形状的空几何体，可以通过 BufferGeometry 自定义任何几何形状，具体一点说就是定义顶点数据。

- 长方体 BoxGeometry
- 圆柱体 CyliderGeometry
- 球体 SphereGeometry
- 圆锥 ConeGeometry
- 矩形平面 PlaneGeometry
- 圆平面 CircleGeometry

# 材质 Material
- 不受光照影响
  - 网格基础材质 MeshBasicMaterial
- 受光照影响
  - 网格漫反射材质 MeshLambertMaterial
  - 网格高光材质 MeshPhongMaterial
  - 物理材质 MeshStandardMaterial/MeshPhysicalMaterial
- 点材质 PointsMaterial
- 线基础材质 LineBasicMaterial
- 精灵材质 SpriteMaterial

# 光源 Light
- 环境光 AmbientLight
- 点光源 PointLight
- 聚光灯光源 SpotLight
- 平行光 DirectionalLight


