��������� �� ������ � ��������� �������� � GIT

#���������� � ��������� �������.
���� �� ������������ macOS ��� Linux, ��������� ��������� Terminal. Ÿ ����� ����� ����� ���� ������ ������������ �������. � ����� ������������ ���������� ������� ������:
��� Linux � Ctrl+Alt+T;
��� macOS � Cmd+Space, ����� ������ terminal.
���� �� ������������ Windows, ���������� � ��������� ��������� [Git Bash]:https://gitforwindows.org/ "��������� � ��.�����".
� ����������� ���� �� �������:
��� ������ ����������;
���, ��� ������� �� �������������� � ����������;
������ ������� ($) � �� ��������, ��� ��������� ��� ����� ������.
## ������� ��� ������ � �������(�����������, ����������, ����������)
� ����������� �� ������������ ������� ������� ����������� � ������� ��� ������ ����� ������� �����������.
� ��������� ������ �� ����� ��� ���������� � ������ ������! ���� ���� ������������. � ����� ������ ���������� ��������� ���������� ��� ����������.
��� ����� ���������� ������ �������:

pwd (print working directory - "�������� ������� �����")

������������ ������� Windows, Linux � macOS ���������� ���� �� �����. � ��� ����� � ���, ��� �������� �� �������� �������. 
��������, ��� Windows ���� ���������� � ����� ����� C � /c/ ��� c:/. � Linux ��� ���� ������, � �������� ���������� ��������� � /home ������ /Users. � macOS ���� ����� /Users, �� ��� ���� ������.

**��� �������� ����� ������������(�������) ������������ �������:**

cd (change directory - "������� ����������")

���������� ����� ����: �/1_directory/2_directory/3_directory/4_directory

cd ~ - ��������� � ��������� ����������
cd 1_directory/ - ��������� � 1 ����������
cd 1_directory/2_directory/ - ��������� ����� �� 2 ����������
cd .. - ��������� �� ������� ����, �.�. � ����� 1_directory

**��� ��������� ����������� ���������� ������������ �������:**

ls (list directory contents)- ���������� �� ������� ���������� ����������

ls -a - ���������� ��� �����(���� �������)

ls ~ - ���������� ��� ����� �������� ����������, ���������� �� ���������� � ������ �����

ls .. - ���������� ���������� ������������ ����������

## �������� � ������� � �������.

touch my-new-file.txt - �������� � ������� ���������� ����� � ����������� .txt

mkdir new_folder - �������� ����������(�����) new_folder

mkdir -p new_folder/1_folder/2_folder ������� ����� 2_folder � ����� 1_folder � ����� new_folder

**����������� �����(��)**

cp - (copy) - �����������

cp ���_�������� ����_�������� 

cp index.html src/ (�������� ���� index.html � ����� src/)

����� ����� ��������� ������ �����������:

cp ���_�������� ���_�������� ���_�������� ����_�������� 

cp index.html style.css script.js src/ (�������� 3 ����� index.html, style.css, script.js � ����� src/)

**����������� ������**

mv (move) - �����������

mv ���_���������� ����_����������

mv file_1.txt ./folder_2

**������ ������**

cat (concatenate and print) - ���������� � �����������

cat my_file.txt

������� �������� ������ � ���������� �������!

**�������� ������ � �����**

rm (remove) - ��������

rm my_file.txt

rmdir  (remove directory) - �������� �����

���� ����� �� ����� �� ������ �������������� � �������� ����� ��������

rm -r ( -r recursive) - ������� ��������� � ����� �����, � ����� ���� �����.

**���������� ���������� ������ �����**

������� ����� ������� �������, � �� �� �����.

mkdir second_project && cd sekond_project && touch index.html style.css

mkdir second_project - ������� ����� second_project 
cd second_project - ��������� � ����� second_project 
touch index.html style.css - ������� � ����� 2 �����

**����� ������� �� ������**

� ��������� ���� ���� ������. ����� ���������� �������� ����� ������� �� �������� ��������������� ��������� �� ����������(����� � ����)

**�������������� � ��������� ������**

��� ������ ��������� �������� ������� ����� ������ tab � ��������� ������ ���� �������� ���� ������� ���� ��� ���� ��������� ������ ���������� �� ��� ������� - �� ������� ������ ������ ��� ������� ������� tab.
��� �� ���������� � � ������� � �������. 

#GIT

Git � ��� ������� �������� ������, ������� �������� ����������� ��������� � �������. ���� ���������� ����� ������������ ��� ��� ��������������, ��� � ��� ��������� ������.
Git ��������� ��������� ��������� �������� � ��� ������������� ������������ � ���������� ������� �������. ����� ����� ������� �������� ����� �� �������-���������, ������� �������� � Git, � ���������� ����������� � �������.

**������������� �����������**

����� Git ����� ����������� ��������� � �������, ����� � ������� ����� ������� ����� ������� Git-������������ (�� ����. repository � ����������). ��� ����� ������� ������������� ��� � ������ ������� git init (�� ����. initialize � ������������������).

**������ ������������� �����������**

���� �� �������� ������� Git-������������ �� �� �����, � ����� �����������. ��� ����� ����� ������� ������� �������� .git.

$ cd <����� � ������������> # ������� � �����

$ rm -rf .git # ������� �������� .git 
������� ���������, ��� ����� -rf:
���� -r (�� ����. recursive � �����������) ��������� ������� ����� ������ � �� ����������;
���� -f (�� ����. force � �����������) ������� ��� �� �������� ����� ��� ����� ������ ������� ���� ����? � ����? � ���� ����?�.

**�������� ��������� �����������**

��� �������� � ����� ���������� ����� ��������� � ������ ����������� ���������� ������ ������� git status

**���������� ������ � �����������**

����� ����������� ��������� � ������ �������, ���������� ������������ ������� git add --all (�� ����. add � ���������� + �� ����. all � ���). ����, ��� ����, --all ��������� ����������� � ���������� ��� ����� � �����������.
$ git add --all # ����������� � ���������� ��� ����� � �����������
$ git status # ��������� ������ 
��������� ����� ����� � �� ������, ��� ����� --all.
$ git add todo.txt
$ git add readme.txt
$ git status 
����� ����� �������� ������� ����� ������� � � ���� ������ ��� ����� � ��� ���� ����� ���������. ���������� � ������� ����� � Bash ��������� ����� (.).
$ git add . # �������� ��� ������� �����
$ git status 
�� ������ ������������ ����� �� ���� ��������� � ��������� ����� ����������.
������� git add �� ��������� ���������� ������ � �����������. ���� ����������, ��� �������� ��������� ������, �������� �������� (�� ����. commit � �����������, �������������). �������� ������ ������ ��������� ������� ������ �����. 
���� �������� ��������, ������� git add ����� �������� � ����������� ������� � ������� � ��������-��������, � ������ � � ����������� � ������� ������.

**������ ������ ������**

����� ��������� ��������� � ������ ���������� ��������������� �������� git commit. ��� ���� ����� �������� ��� ���� ��������  ����� ��������������� ������ -m.
git commit -m "��������� ������ ������"

#GitHub

GitHub � ��������� ��� �������� IT-�������� � ���������� ������ ��� ���� � �������������� Git. �� ����, ��� ����, ���� ����� ��������� ����� ������ ������� ��� ������ � ������� ������.
� ����������� ����� ����� hub ����������� ��� �������� ��������. � �������������, GitHub ���� ����� ���������� ������ ��� �������� Git-������������. ������ ������� ��������, ����� ��� Google, Apple, Valve, ����������GitHub ��� ����� ��������. 
GitHub ��������, ����� �������� ������ ������ �Git. ����� ����� ������� ������� � ������ �� ����� �������� �������� ��� ������ ��������. ����� ��������� ������� ������ �����: 
��������� � ������ ��� ���;
��������� � ������ ��� ������ �������;
��������� � ����� ����� ����.

**SSH-�����**

����� ���������� ������������ ������� � ����, ��� ������� ������� ���������� (����. network protocols) � �������� ������ ������� ����� ������������.
���� �� �������� ���������������� ������� ���������� � SSH (�� ����. Secure Shell Protocol). �� ������������ ���������� ����� ������� � ����. � ������� ����� ��������� ����� �������� ������ � ��������� ���������� ��� ���������� �� �� ����. ������ ���������, ������� �������� ���������.
SSH ���������� ���� ������ ��� ����������� ������������ � ��������� � ���������: 
��������� ���� (����. private key) �������� ������ �� ����� ���������� � �� ������ ������������ ����-���� ���. �� ������������ ��� ����������� ������.
��������� ���� (����. public key) �������� ���� � ������������ ��� ���������� ������. ��� ����� ���� ������������ ������ ��������� ������.

**�������� ������� SSH-�����**

������ ��� ������������ SSH-�����, ���������, ��� � ��� �� ��� ���. �� ��������� ���������� � SSH-������� ��������� � �������� ���������� ������������. ��������� � ��.

$ cd ~ # ������� � �������� ���������� 
������ SSH-����� ��������� � ���������� .ssh/. ��������� ������� ���� ���������� � ������ � ��� ����� � ������� ��������� �������.

$ ls -la .ssh/ # ������ ������ ��������� ������ 
���� ����� ������ ��� � ���, �� � �������. 
���� ���� ����� � �������� ����������, SSH-����� ��� �����������:
id_dsa.pub;
id_ecdsa.pub;
id_ed25519.pub;
id_rsa.pub.
���� �� �� ��������� ��� �����, ������� �� ���.

**��������� SSH-������**

��� ��������� SSH-���� ����� ������������ ��������� ssh-keygen. �������� �������� � ������� ��������� �������.
$ ssh-keygen -t ed25519 -C "����������� �����, � ������� �������� ��� ������� �� GitHub" 
����� ��������� ������ ���������� �� �������� ��  GitHub.

**���������� ���������� � ���������� ������������**

������ �� ���������� ��������� ����������� �� ����� ��������� � ���������� ����� � ��������� ����������� �� GitHub. ��� ����� �� ��������� ����������� ���������� ����������� URL � ����� ����������� ����� ������� git remote add origin git@github.com:%���_��������%/%���_�������%.git

**�������� ����� ������������**

�������� ������������ �������� git remove -v
origin    git@github.com:%���_��������%/%���-�������%.git (fetch)
origin    git@github.com:%���_��������%/%���-�������%.git (push) 
� ������ �� ������ ������� ��� �������, ����������� ���, ��� �������� ����.
**��������� ������ � ���������� �����������**
��� ������ � ������� ������� ��������� �� ��������� �����������(��� ������� ������������������ ������������) � ���� �������� ��� ����� ��� ���������� �������� ����� ������ ������ � ������� ������� git pull
**�������� ���������� ������ �� ��������� �����������**
������� ���� �� ��������� ����������� ��� ���������� ��������� �� ��������� �����������. ��� ����� ���������� ������ ������� git push
� ������ ��� ��� ������� ����� ������� � ������ -u � ����������� origin (��� ��������� �����������) � main ��� master (�������� ������� �����). ���� -u ������ ��������� ����� � ���������� ��������. ��� �� ��������� ��������� � �������� ����������� � ���������� �����, ��� �� � ����� ����� ������������� ������� �����.
