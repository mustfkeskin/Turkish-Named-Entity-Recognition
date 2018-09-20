# Turkish-Named-Entity-Recognition

1. Wikipedia Hiyerarşisini Çıkartabilmek için ilk olarak Categorylinks, Page ve category tabloları indirilir.

wget https://dumps.wikimedia.org/trwiki/latest/trwiki-latest-category.sql.gz
gunzip trwiki-latest-category.sql.gz

wget https://dumps.wikimedia.org/trwiki/latest/trwiki-latest-categorylinks.sql.gz
gunzip trwiki-latest-categorylinks.sql.gz

wget https://dumps.wikimedia.org/trwiki/latest/trwiki-latest-page.sql.gz
gunzip trwiki-latest-page.sql.gz

2) Wikipedia Hiyerarşisini elde etme

extract_wikipedia_hierarchy.ipynb notebook çalıştırılarak wikipedia hiyerarşisi çıkartılır.
https://github.com/niwatolli3/wikipedia-category-csv

3)Elde edilen hiyerarşiden graf çıkartılması ve tüm yaprak düğümlere ait bilgilerin toplanması

graph_analysis.ipynb notebook çalıştırılarak elde edilir.

4) Belli kategoriler ait ontolojiler çıkartılarak otomatik veri etiketleme altyapısının oluşturulması
coming soon...

5) Etiketli veri ile farklı modellerin eğitilmesi
coming soon...
