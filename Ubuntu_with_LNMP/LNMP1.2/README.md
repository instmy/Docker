# Ubuntu-with-lnmp

## һ��Ubuntu��
��������SSH��½����**ROOT_PASS**����

*ROOT_PASS��Password*

������Ϊ�Զ�����**ROOT_PASS**��½����

��ϸ��־�в鿴

## �������ù�����lnmpһ����
### 1)����SSH
### 2)��װ��
`screen -S lnmp`

���SSH�����˿����ٴε�¼SSHʹ�ã�`screen -r lnmp`���ָ��鿴����

`cd lnmp1.2-full && ./install.sh lnmp`

(��ʵ�����������MySQL��*root*��������ȫ����**�س�**������)

------------------------------

��Ҫ����MySQL��root���루������ֱ�ӻس���������Ϊroot���������س�������һ��

������Ҫȷ���Ƿ�����MySQL InnoDB�������ȷ���Ƿ����ÿ������� y ������ y ��ʾ���ã����� n ��ʾ�����á�Ĭ��Ϊy���ã������س�������һ��ѡ��MySQL�汾

����PHP�汾����ţ��س�������һ����ѡ���Ƿ�װ�ڴ��Ż�������ѡ�񲻰�װ��Jemalloc��TCmalloc�������Ӧ��Żس���

��ʾ"Press any key to install...or Press Ctrl+c to cancel"�󣬰��س���ȷ�Ͽ�ʼ��װ��LNMP�ű��ͻ��Զ���װ����Nginx��MySQL��PHP��phpMyAdmin��Zend Optimizer�⼸�������

------------------------------

��װʱ����ܻἸʮ���ӵ�����Сʱ���ȣ���Ҫ�ǻ������������ٵ�ԭ������Ӱ�졣

������������뵽������<http://lnmp.org/install.html>�鿴ͼ�Ľ̡̳�

### ��װ���
�����ʾNginx: OK��MySQL: OK��PHP: OK����Nginx��MySQL��PHP����running��80��3306�˿ڶ����ڣ���Install lnmp V1.2 completed! enjoy it.�Ļ���˵���Ѿ���װ�ɹ���

## �����������
ֱ���Ϲ����Ľ̳̣�����Ͳ��ٽ�̫���ˣ�����������ϸ��
+ [��ӡ�ɾ������������α��̬����](http://lnmp.org/faq/lnmp-vhost-add-howto.html "��ӡ�ɾ������������α��̬����")
+ [eAccelerator��xcache��memcached��imageMagick��ionCube��redis��opcache�İ�װ](http://lnmp.org/faq/addons.html "eAccelerator��xcache��memcached��imageMagick��ionCube��redis��opcache�İ�װ")
+ [LNMP������Ŀ¼���ļ�λ��](http://lnmp.org/faq/lnmp-software-list.html "LNMP������Ŀ¼���ļ�λ��")
+ [LNMP״̬��������](http://lnmp.org/faq/lnmp-status-manager.html "LNMP״̬��������")
