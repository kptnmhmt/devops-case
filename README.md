# DevOps Case Study

Prosedür

Lütfen bu görev için bir github reposu açın ve adresini bizimle paylaşın.
Tercih ettiğiniz tool, framework'ü kullanabilirsiniz.
Dilediğiniz dış kaynaklardan faydalanabilirsiniz. Lütfen kullandığınız dış kaynak ve kodları görev içerisinde yorum olarak belirtin.

Bu görevde herhangi bir zaman sınırlaması bulunmamaktadır.

Gorev: CI / CD pipeline olusturma

Aşağıda belirtilen repo örnek bir PHP blog projesidir. Asagida belirtilen adimlara gore bir pipeline olusturularak projenin deploy edilmesi gerekmektedir. Istenilen teknoloji / tool vb. kullanabilirsiniz.

Proje URL: https://github.com/symfony/demo/archive/refs/tags/v2.0.2.zip

Adimlar:

Clone project
Build project  ( composer install )
Run unit tests ( __PROJECT_PATH_/bin/phpunit )
Run SonarQube
Dockerize and push the image to docker hub
Deploy in a test environment (Docker etc.)
Deploy to Kubernetes 
