# Easy-Game_Algorithms
# RandomColor

TR=>Bu kod, her Space tuşuna basıldığında oluşan renklerin temel renkle olan benzerliğini artırır. Oluşan renk belirli açıklık olmasını sağlar. minBrightness ve maxBrightness değişkenleri, oluşan renklerin açıklık değerinin minimum ve maksimum aralığını ayarlar. Eğer minBrightness değeri 0.3 ve maxBrightness değeri 0.7 ise, oluşan renkler 0.3 ile 0.7 arasında bir açıklıkta olacaktır.

EN=>This code increases the similarity of the colors produced each time the Space key is pressed to the base color. The resulting color ensures certain clarity. The minBrightness and maxBrightness variables set the minimum and maximum range of the lightness value of the resulting colors. If the minBrightness value is 0.3 and the maxBrightness value is 0.7, the resulting colors will be between 0.3 and 0.7.

# Gizmos

TR=>Sadece editörde gizmolarla çalışılan bir sistem.Scriptin atıldığı objenin etrafında random yerlerde dairesel şekilde sphereler çizdiriyor.Bir parametre değiştiği an da randomluk güncelleniyor.Oluşacak daire sayısını,oluşan dairelelerin radisunu,kullanılabilir alanın radius değişkendir.Boolun açık olduğu durumda her sphereden kendisi hariç diğer bütün spherelere kendi renginde line çizebiliyor.

EN=>A system that works only with gizmos in the editor. It draws spheres in a circular manner in random places around the object where the script is thrown. The moment a parameter changes, the randomness is updated. The number of circles to be formed, the radius of the circles formed, the radius of the usable area are variable. He can draw lines in his own color.

# Pixel Object Creat

TR=>Scripte herhangi bir 3D obje verilebilir. Bu obje kullanılarak pixel textureda yer alan resmi oluşturur.

EN=>Any 3D object can be given to the script. Using this object, it creates the picture in the pixel texture.

# Cube Roll

TR=>A,S,D,W tuşlarını kullanarak küpü zeminden dönerek ilerletiliyor.

EN=>Using the A, S, D, W keys, the cube is advanced by rotating from the ground.

# Cube Rotat

TR=>Dokunduğun noktadan parmağını hareket ettirdiğin noktaya doğru kupün dönmesini sağlar.

EN=>Allows the cube to rotate from the point you touch to the point where you move your finger.

# Security Camera

TR=>Oyun içi ekranlar (CCTV, güvenlik kamerası) birliğe nasıl eklenir? Bunun için renderer texture kullanılır. Renderer texture kameramıza eklediğimizda kameranın gördüğü bu texture çizilir. Bu texture bir material atayıp, obje üstünde gösterebiliriz.

EN=>How to add in-game screens (CCTV, security camera) to unity? For this, renderer texture is used. When we add the renderer texture to our camera, this texture that the camera sees is drawn. We can assign this texture a material and display it on the object.
