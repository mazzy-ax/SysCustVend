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

  dialog.AddField(cv.typeid().account());
  dialog.AddField(cv.typeid().rContractAccount());
```

mazzy, v0.4-ax5, proof of concept

TODO ��������� fields, ��������� enum. ���� �������� ������ table, tableId, type

