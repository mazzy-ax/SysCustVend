# SysCustVend

�����, ������� ��������� ������� ������ ���� ��� ��� ������������� �����-���� ���������.
��� ������������� ����������� ��������� � ��� �� �������� - � ��������� ��� � ������������.
� ���������� ������ ������ (����� ������ ����������) �������, ���� ��� ��������, enum'�, ���� � ���������� ��������
����������� ���� � ��������, ���� � �����������.

������ �����, ��� ��� ����, ����� ���������� ��� ������� ��������, ������� �� ����� ��������� ��������� ��� ������ ����������
������ ������ ���������� ���������

������:

```javascript
  SysCustVend    cv     = SysCustVend::constuct(ModuleCustVend::Cust);
  CustVendTrans  trans  = cv.table().trans();
  Dialog         dialog = new Dialog();

  dialog.AddField(cv.type().account());
  dialog.AddField(cv.type().rContractAccount());
```

mazzy, v0.4-ax5, proof of concept
TODO ��������� fields, ��������� enum. ���� �������� ������ table, tableId, type

