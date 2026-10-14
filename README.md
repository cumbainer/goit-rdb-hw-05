# goit-rdb-hw-05

ДЗ 5. Узагальнені табличні вирази (CTE), Materialized View.

- **Датасет:** Olist Brazilian E-Commerce, https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce
- **Отримання:** `kagglehub.dataset_download('olistbr/brazilian-ecommerce')` у notebook (публічний датасет).
- **Таблиці:** customers 99 441, orders 99 441, order_items 112 650, products 32 951, sellers 3 095.
- **Зміст:** CTE-pipeline з 8 stages, recursive CTE для referral chain, `mv_olist_customer_features` з `REFRESH CONCURRENTLY`, EXPLAIN (ANALYZE, BUFFERS).

## Запуск

Відкрити `hw_t5.ipynb` у Google Colab і виконати Runtime → Restart and run all. PostgreSQL 16 запускається через `pgserver`.
