> Push :ֱ��������ǡ��ơ�����˼��ʲô��˼�أ�����㱾�ش����и����ˣ���ô����Ҫ�ѱ��ش����Ƶ�Զ�ֿ̲⣬�������زֿ��Զ�ֿ̲�Ϳ��Ա���ͬ���ˡ�

> ����ʾ���� git push origin master

> Pull��ֱ��������ǡ���������˼����������ύ���뵽Զ�ֿ̲⣬���ʱ������Ҫ��Զ�ֿ̲�����´�����������Ȼ��֤���˴����ͬ����


> ����ʾ���� git pull origin master

> ��˼���ǰ�Զ�����µĴ�����µ����ء�һ�������� push ֮ǰ������ pull �����������׳�ͻ��

> �������ѣ����ύ����֮ǰ��Ҫ�������Լ����û��������䣬��Щ��Ϣ����������е� commit ��¼�ִ�����´���Ϳ������ã�

> git config --global user.name "stormzhang"

> git config --global user.email "stormzhang.dev@gmail.com"

> Log �鿴
>  git log --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit --date=relative  

> �� Git �����ɫ��������������ɣ�

> git config --global color.ui true

> git config --global core.quotepath false # ������ʾ�����ļ���

> git diff <$id1> <$id2>   # �Ƚ������ύ֮��Ĳ���

> git diff <branch1>..<branch2> # ��������֧֮��Ƚ� 

> git diff --staged   # �Ƚ��ݴ����Ͱ汾�����

> ����֪�� checkout һ�������л���֧ʹ�ã������л��� develop ��֧������ִ�У�

> git checkout develop

> ����֪�� merge ��֧�Ǻϲ�����˼��������һ�� featureA ��֧��������һ�����ܣ����ʱ����Ҫ�ϲ�������֧ master ��ȥ������ֻ��Ҫ�������²�����


> git checkout master

> git merge featureA

> �鿴���ط�֧�б�

> git branch 

> �鿴Զ�̷�֧�б�

> git branch -r 

> ɾ�����ط�֧

> git branch -d develop

> git branch -D develop (ǿ��ɾ��) 

> ɾ��Զ�̷�֧

> git push origin :develop

> ���Զ�̷�֧�и� develop ��������û�У������Զ�̵� develop ��֧Ǩ�����أ�

> git checkout develop origin/develop

> ͬ���İ�Զ�̷�֧Ǩ������˳���л����÷�֧�� 

> git checkout -b develop origin/develop


