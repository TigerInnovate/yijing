1. jdk1.6,��������		java_home=D:\java_project\sdk\jdk1.6;  path=%java_home%\bin;
2. maven3����������   maven_home=D:\java_project\sdk\maven3; path=%maven_home%\bin;


3. git
	Git��һ��������١���Ч���ֲ�ʽ�汾����ϵͳ��������Эͬ���������
	���CVS/SVN��Git �����ƣ�
		�� ֧�����߿���������Repository
		�� ǿ��ķ�֧���ܣ��ʺ϶������������Э��
		�� �ٶȿ�

	GitHub��������Эͬ��������÷��������͹��������еĹ�����˽�е�git�ֿ⡣
	GitHub��һ���й�Git ����Դ���Դ����Ŀ����վ����Դ�շѣ����7$/������ѵ�300G�ռ䡣

4. ʹ��GitHub���裺
	1)������GitHub�ʻ� vandh ��������Ϊyijing����Repository 
	2)����װGit�ͻ��ˣ�Linux��,windows : Git-1[1].7.9-preview20120201.exe
		#yum install git git-gui
	3)�� ������Կ�ԣ�������Ŀ����push�� GitHub��
		#ssh-keygen -t rsa -C "vandh@163.com"
	4)����.ssh/id_rsa.pub������GitHub��վ
	5) Global setup:
		git config --global user.name "vandh"
		git config --global user.email vandh@163.com
	6) ����������Ŀ
		����D:\java_project\myself\jyijing
		�һ�jyijingĿ¼��ѡ��git bash here
		git init
		git add --all
		git commit -m 'first commit'
		git remote add simon git@github.com:vandh/yijing.git
		git push -u simon master
      Existing Git Repo?
  cd existing_git_repo
  git remote add origin git@github.com:vandh/yijing.git
  git push -u origin master
      Importing a Subversion Repo?
  Check out the guide for step by step instructions.

5. 