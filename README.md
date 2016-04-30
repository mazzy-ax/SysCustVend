# SysCustVend

класс, который позволяет создать объект один раз при инициализации какой-либо обработки.
при инициализации программист указывает с чем он работает - с клиентами или с поставщиками.
в дальнейшем объект быстро (очень быстро возвращает) таблицы, типы для диалогов, enum'ы, поля в конкретных таблицах
относящиеся либо к клиентам, либо к поставщикам.

Причем важно, что для того, чтобы возвратить код таблицы клиентов, объекту не нужно выполнять сравнение или другие вычисления
объект просто возвращает константу

Пример:

```javascript
  SysCustVend    cv     = SysCustVend::constuct(ModuleCustVend::Cust);
  CustVendTrans  trans  = cv.table().trans();
  Dialog         dialog = new Dialog();

  dialog.AddField(cv.type().account());
  dialog.AddField(cv.type().rContractAccount());
```

mazzy, v0.4-ax5, proof of concept
TODO завершить fields, завершить enum. Пока работают только table, tableId, type

