# DevOps Case Study

## Prosedür

Lütfen bu görev için bir github reposu açın ve adresini bizimle paylaşın.

Tercih ettiğiniz tool, framework'ü kullanabilirsiniz.

Dilediğiniz dış kaynaklardan faydalanabilirsiniz. Lütfen kullandığınız dış kaynak ve kodları görev içerisinde yorum olarak belirtin.

Bu görevde herhangi bir zaman sınırlaması bulunmamaktadır.

Eğer görevde net olmayan noktalar olduğunu düşünüyorsanız, lütfen bizimle iletişime geçmekten çekinmeyin.

## Görev

Aşağıda belirtilen repo örnek bir PHP blog projesidir. Asagida belirtilen adimlara gore bir CI / CD pipeline olusturularak projenin deploy edilmesi gerekmektedir. Istenilen teknoloji / tool vb. kullanabilirsiniz.

Proje URL: https://github.com/symfony/demo/archive/refs/tags/v2.0.2.zip

## Adimlar:

<ol>
<li>Clone project</li>
<li>Build project  ( composer install )</li>
<li>Run unit tests ( __PROJECT_PATH_/bin/phpunit )</li>
<li>Run SonarQube</li>
<li>Dockerize and push the image to docker hub</li>
<li>Deploy in a test environment (Docker etc.)</li>
<li>Deploy to Kubernetes</li>
</ol>
