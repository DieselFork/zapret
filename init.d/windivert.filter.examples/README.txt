���� ���� �������� - �������� �������� �������� � ������ ����, �� ������� ��������� ���������������� ������ ������ �� winws.
������������� ����� `winws --wf-raw=@filename`.
������, ���� �������� windivert �� �������� �������� � �������� ������, ������� � ��������� ������.
������� ������� ���������� ����� �������, ���������� ���������� ������������ ��������.
������������ ������������ ������ winws.

������ �������� ��� �������� ������������ � discord : `winws --wf-raw=@windivert.discord_media+stun.txt --dpi-desync=fake`

These filters are invoked using `winws --wf-raw=@filename`.
Filters are kernel mode and save great amount of CPU.
However windivert cannot filter by bit fields, lacks shift and bitwise logic operations.
Filters are relaxed and can pass wrong payloads. Finer filtering is done by winws.
