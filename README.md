# united-thinkers-test-task
test task @ unitedthinkers.com

Задача:
Необходимо создать .zul страницу (форму обработки платежей), используя framework ZK (https://www.zkoss.org)
и наш Unicharge Realtime Processing API для работы этой формы, дабы через неё можно было провести Sale
транзакцию на Gateway. Форма должна валидировать введение обязательных полей согласно спецификации Gateway
и отображать ответ от сервера, в случае успешного проведения платежа должно быть только сообщение об успешном
платеже с кнопкой 'Return' для возврата к предыдущему состоянию, т.е. без полей ввода данных.


Перечень требуемых на странице полей:
Card/Account Information:
Card Number
Exp Date
CSC Code

Transaction Information:
Amount
Holder Name
Street
City
State
ZipCode

Документация по Unicharge Realtime Processing API: https://unipaygateway.info/processing-api/realtime/operations#operation-sale-realtime (необходима только Sale операция).
