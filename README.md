# DevOps Case Study

## Prosedür

Lütfen bu görev için bir github reposu açın ve adresini bizimle paylaşın.

Tercih ettiğiniz tool, framework'ü kullanabilirsiniz.

Dilediğiniz dış kaynaklardan faydalanabilirsiniz. Lütfen kullandığınız dış kaynak ve kodları görev içerisinde yorum olarak belirtin.


## Görev

Aşağıda belirtilen repo örnek bir PHP blog projesidir. Asagida belirtilen adimlara gore bir CI / CD pipeline olusturularak projenin deploy edilmesi gerekmektedir. Istenilen teknoloji / tool vb. kullanabilirsiniz.

Proje URL: https://github.com/symfony/demo/archive/refs/tags/v2.0.2.zip

## Zaman

Bu görevde herhangi bir zaman sınırlaması bulunmamaktadır.

## Adimlar:

<ol>
<li>Proje Git ile klonlanır</li>
<li>composer install ile paketlerin yükleme işlemi yapılır</li>
<li>__PROJECT_PATH_/bin/phpunit ile birim testler çalıştırılır</li>
<li>SonarQube ile kod kalite testi yapılır</li>
<li>Kod uygun bir Dockerfile ile dockerize edilir ve imaj Docker Hub'a gönderilir</li>
<li>Üretilen konteyner imajı seçilen bir Kubernetes cluster'ına Helm chart kullanılarak deploy edilir</li>
</ol>
