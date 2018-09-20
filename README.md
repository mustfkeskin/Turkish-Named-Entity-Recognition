# Turkish-Named-Entity-Recognition


1. Wikipedia Hiyerarşisini Çıkartabilmek için Categorylinks, Page ve category tabloları indirilir.
wget https://dumps.wikimedia.org/trwiki/latest/trwiki-latest-category.sql.gz
gunzip trwiki-latest-category.sql.gz
wget https://dumps.wikimedia.org/trwiki/latest/trwiki-latest-categorylinks.sql.gz
gunzip trwiki-latest-categorylinks.sql.gz
wget https://dumps.wikimedia.org/trwiki/latest/trwiki-latest-page.sql.gz
gunzip trwiki-latest-page.sql.gz

2) Wiki_page_category_links
Wiki_page_category_links.ipynb notebook’un çalıştırılması.
https://github.com/niwatolli3/wikipedia-category-csv
