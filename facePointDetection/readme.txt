��������CVPR2013 ��Deep Convolutional Network Cascade for Facial Point Detection�� ��ҳ��ַ��http://mmlab.ie.cuhk.edu.hk/archive/CNN_FacePoint.htm

��һ������matlab������generateList.m����������[generateList ��../dataset/�ļ�����/blurry��]������[generateList '../dataset/vd001/blurry',�����������vd001Ϊ��]
�˲����ڱ��ļ������µġ�imagelist.txt���ļ�
�ڶ���������һ�����ļ��У�vd001���µ�����ͼƬ�ֱ𿽱���imgae��image/image�ļ����£������µ�·����vd002�����������и��ǲ���
���������ڱ�·���µ�Windows�����ִ������[FacePartDetect.exe data imagelist.txt bbox.txt]
�˲����֮����ڱ�·���������µ�bbox.txt����bbox�ļ���ɾ������һ��ͼƬ�м������������еĴ������ݣ���֤ÿ��ͼƬֻ��һ�����ݣ�4�����֣���ע��۲�ǰ��ͼƬ���ݲ�Ҫɾ������
���Ĳ���������Windows�����ִ������[TestNet.exe bbox.txt image Input result.bin]�������µ��ļ�result.bin
���岽����matlab��ִ��show_result.m����Ӧ��txt�ļ�������show_result�ļ�����
�������������岽���ɵ�ȫ��txt�ļ�������[dataset/�ļ�����/face]����