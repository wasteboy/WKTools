



![image](https://github.com/AngleHony/WKTools/blob/main/Process_en.bmp)

˵����

������Ŀǰʵ�ֹ������£������������ڣ���
1 ����:
	�鿴ģ��
	�鿴����
	�鿴�ڴ�
	�鿴�ȼ�
	�鿴��ʱ��
	�鿴Ring3 HOOK
	�鿴ProceeKernelCallBack
	�鿴.......
	�رս���
	�ر��߳�
	ж��ģ��
	���������ڴ�
	���ҽ���ģ�飻
	�������̵���DUMP��
	ע��ģ�飻
	��������
	..........

2 �ں�����
	�鿴�ں�ģ�����
	�鿴�ں�ģ��������ʽ
	�ں�����ģ����ڴ濽��
	ж�������ں�ģ��
	�޸�����������ʽ
	......
3 ����
	SSDT �鿴��ָ�
	SSSDT �鿴��ָ�
	FSD �鿴��ָ�
	���� �鿴��ָ�
	��� �鿴��ָ�
	Disk �鿴��ָ�
	Atapi �鿴��ָ�
	ACPI �鿴��ָ�
	TCPIP �鿴��ָ�
	IDT �鿴��ָ�
	OBJECT �鿴��ָ�
	Kernel �鿴��ָ�
	MessageHook �鿴��ָ�
	
4 Notify
	CreateProcess ,Ex,Ex2�鿴��ɾ����
	CreateThread 		 �鿴��ɾ����
	LoadImage 			 �鿴��ɾ����
	Registry 			 �鿴��ɾ����
	Shutdown			 �鿴��ɾ����
	
5 	DPC��IO��ʱ�����ں˶�ʱ���Ĳ鿴��ɾ����
6	ϵͳ�̵߳Ĳ鿴�ͽ�����
7	���̡��������̡������ȹ���������ö�٣�
8	MiniFilter �鿴��ɾ����
9	ע����༭��
10	�ļ�������
11	ϵͳ�����ö�ٺͲ�����
12  ��������, LSP, WFP ......
13  Other..............


������־��
1.0.0.2�汾��2021-12-26��
		1.�޸�����bug
		2.����Win11 22000 ϵͳ����
		3 ����Windows Process KernelCallBack hook ���
		4 ����minifilter���
		
1.0.0.1�汾��2021-10-06��
		1.�޸�����bug
		2.����Win10 xxxx ϵͳ����
0.0.0.5beta�汾��2021-09-19��
		1.�޸�����bug
		2.����Win10 xxxx ϵͳ����
0.0.0.4beta�汾��2020-11-7��
		1.�޸�����bug

0.0.0.3beta�汾��2020-07-23��
		1.�޸�����bug

0.0.0.2beta�汾��2020-03-15��
		1.�޸�����bug

0.0.0.1beta�汾 (2019-09-16)
		1.�װ汾

EN:



*Process Manager
	Display system process and thread basic informations.
	Detect hidden processes,threads,process modules.
	Terminate, suspend and resume processes and threads.
	View and manipulate process handles,windows and memory regions.
	View and manipulate process hotkeys,privileges,and timers.
	Detect and restore process hooks incluing inline hooks,patches,iat and eat hooks, ProcessKernelCallBack hook.
	Inject dll,dump process memory.
	Create debug dump,inclue mini dump and full dump.

*Kernel Module Viewer
	Display kernel module basic information,include image base,size,driver object,and so on.
	Detect hidden kernel modules.
	Unload kernel modules.
	Dump kernel image memory.
	Display and delete system driver service informations.

*Hook Detector
	Detect and restore SSDT,Shadow SSDT,sysenter and int2e hooks.
	Detect and restore FSD and keyboard disptach hooks.
	Detect and restore kernel code hooks including kernel inline hooks,patches,iat and eat hooks.
	Detect and restore message hooks,both global and local.
	Detect and restore kernel ObjectType hooks.
	Display Interrupt Descriptor Table(IDT).

*Other Kernel Information Viewer
	View and remove kernel notifications.
	View filters for common devices include disk,volume,keyboard and network devices. 
	View IO timers,DPC timers,system threads,and so on.

*Registry Manager
	View and edit system registry.
	Detect hidden registry entries using live registry hive analysis.

*File Manager
	Display file basic information,include file name,size,attributes,and so on.
	Detect hidden files.
	View and delete locked files and folders.

*Service Manager
	Display system services basic informations.
	Control services status.
	Modify services startup type.

*Autorun Manager
	Display almost all kinds of system autorun types.
	Enable,disable or permanently delete autoruns.

*Network Viewer
	Display current network connections,include TCP and UDP informations.
	View and delete IE plugins and context menu.
	Display winsock providers(LSP).
	View and edit hosts file.
	View WfpCallout

Change log��
V1.0.0.2��2021-12-26��
		1.fix some bug
		2.Add Win11 22000 System support
		3 Add Windows ProcessKernelCallBack hook check
		4 Add minifilter check
		
V1.0.0.1��2021-10-06��
		1.fix some bug
		2.Add Win10 xxxx System support
V0.0.0.5bet(2021-09-19��
		1.fix some bug
		2.Add Win10 xxxx System support
V0.0.0.4beta��2020-11-7��
		1.fix some bug

V0.0.0.3beta��2020-07-23��
		1.fix some bug

V0.0.0.2beta��2020-03-15��
		1.fix some bug

V0.0.0.1beta (2019-09-16)
		1.first version
		