                                                   Bootstrap
1.Ϊʲôʹ��bootstrap?
���ƶ��豸���ȣ��� Bootstrap 3 �𣬿�ܰ����˹ᴩ����������ƶ��豸���ȵ���ʽ��
    ��Ӧʽ��ƣ�Bootstrap ����Ӧʽ CSS �ܹ�����Ӧ��̨ʽ����ƽ����Ժ��ֻ���
Bootstrap �ṩ��һ����Ӧʽ���ƶ��豸���ȵ���ʽ����ϵͳ��������Ļ���ӿڣ�viewport���ߴ�����ӣ�ϵͳ���Զ���Ϊ���12�С�
2.����������ṹ
 <div class="container">
     <div class="row">
        <div class="col-xs-2"></div>/*���ֻ���Ļ�Ϸ�Ϊ���У���һ��ռ12���е����У��ڶ���ռ12���е�10��*/
        <div class="col-xs-10"></div>
     </div>
     <div class="row">
        ...
     </div>
 </div>
   "col-xs-*":��С�豸�ֻ���<768px��    "col-sm-*":С���豸ƽ����ԣ�>=768px��
   "col-md-*":�����豸̨ʽ���ԣ�>=992px��  "col-lg-*":�����豸̨ʽ���ԣ�>=1200px��
3.�Ű�
   (1)�������帱��  <p class="lead">���������ǿ���ı�</p>  /*����Ϊlead,���õ�������֡��и߸��ߵ��ı�*/
   (2)ǿ��  <small>�����������ڱ�ǩ��</small>   /*�����ı�Ϊ���ı���С�� 85%*/
            <strong>�����������ڱ�ǩ��</strong>  /*�����ı�Ϊ���ֵ��ı�*/
            <p class="text-left">��������ı�</p>
            <p class="text-center">���ж����ı�</p>
            <p class="text-right">���Ҷ����ı�</p>
            <p class="text-muted">���������Ǽ�����</p>   /*��ʾ��ʹ��ǳ��ɫ��#999��*/
            <p class="text-primary">�������ݴ���һ�� primary class</p>   /*��Ҫ��ʹ����ɫ��#428bca��*/
            <p class="text-success">�������ݴ���һ�� success class</p>   /*�ɹ���ʹ��ǳ��ɫ(#3c763d)*/
            <p class="text-info">�������ݴ���һ�� info class</p>    /*֪ͨ��Ϣ��ʹ��ǳ��ɫ��#31708f��*/
            <p class="text-warning">�������ݴ���һ�� warning class</p>   /*֪ͨ��Ϣ��ʹ��ǳ��ɫ��#31708f��*/
            <p class="text-danger">�������ݴ���һ�� danger class</p>   /*Σ�գ�ʹ�ú�ɫ��#a94442��*/
   (3)�б�    <h4>�����б�</h4>
              <ul class="list-inline">
                  <li>Item 1</li>
                  <li>Item 2</li>
                  <li>Item 3</li>
                  <li>Item 4</li>
              </ul>
4.��ť
 .btn   /*Ϊ��ť�����ʽ*/
 .active /*��ť�����*/
 .disabled  /*��ֹ��ť*/
 .btn-default  /*Ĭ��/��׼��ť*/
5.ͼƬ
   .img-rounded����� border-radius:6px �����ͼƬԲ�ǡ�
   .img-circle����� border-radius:50% ��������ͼƬ���Բ�Ρ�
   .img-thumbnail�����һЩ�ڱ߾ࣨpadding����һ����ɫ�ı߿�
   .img-responsive:ͼƬ��Ӧʽ�����ܺõ���չ����Ԫ�أ�
6.����Ԫ�أ��Դ���classΪnav�������б�ʼ
  ��1����ǩʽ����
 <ul class="nav nav-tabs">   /*��ǩʽ�ĵ���*/
    <li class="nav-item">    /*��ʾli�ǵ���*/
       <a href="#" class="nav-link active">Active</a>  /*��ʾ�ǵ�����active��ѡ��*/
    </li>
 </ul>
  
  ��2����״����
 <ul class="nav nav-pills"> 
   <li class="nav-item">
     <a href="#" class="nav-link active">Active</a>
   </li>
 </ul>
  ��3���ѵ���״����
 <ul class="nav nav-pills nav-stacked">
   <li class="nav-item">
     <a href="#" class="nav-link active">Active</a>
   </li>
 </ul>
7.������:��<nav>��ǩ�����classΪ.navbar
(1)Ĭ�ϵĵ�����
   ��<nav>��ǩ�����.navbar-default:Ĭ�ϵĵ�����
   ��Ӵ���.nav navbar-nav�������б�:�򵼺����������
   ��<div>Ԫ�����һ������classΪnavbar-header,�ڲ������˴���classΪnavbar-brand��<a>Ԫ�أ������ı�����������һ��
��2����Ӧʽ�ĵ�����
   �۵������ĵ�����ʵ������һ������ class .navbar-toggle ������ data- Ԫ�صİ�ť����һ���� data-toggle�����ڸ��� JavaScript ��Ҫ�԰�ť��ʲô���ڶ����� data-target��ָʾҪ�л�����һ��Ԫ�ء��������� class .icon-bar �� <span> ������ν�ĺ�����ť��
��3���������еı�
     .navbar-form class����ȷ���˱��ʵ��Ĵ�ֱ������ڽ�խ���ӿ����۵�����Ϊ










