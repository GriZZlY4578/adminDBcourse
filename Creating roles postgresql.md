# Создание ролей в PostgreSQL

Для создания ролей можно использовать два метода, используя учетную запись postgres и с помощью sudo. Мы рассмотрим оба этих способа:

1. С использованием учетной записи postgresql:
> sudo -i -u postgres

Этой командой мы входим в учетную запись. Далее в этом окне можем создавать роли:
> createuser --administrator

2. С использованием sudo:
> sudo -u postgres createuser --administrator