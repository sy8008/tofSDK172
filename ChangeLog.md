# �汾�ţ�1.72

## ����ʱ�䣺2019/8/23

### �̼����� �̼��汾��172

- [**Bugfix**] �޸��˶�ģʽͼ���쳣����

### SDK�������
- dmcam lib
  - [**New**] ���ӡ�����˲�ǿ�ȡ� ������֧��
    - ���ᴫ��������
      - [**Enhance**] �Ż�Ƶ���л��߼�
      - [**Bugfix**] �޸�ԭʼ���ͼqi_shift��������
      - [**Bugfix**] �޸���У׼���ݵ�˫Ƶ����У׼���ݵĵ�Ƶ�л�������
  - [**Enhance**] �Ż�dev_open�ٶȣ�PARAM_INFO_CAPABILITY��ȡ����get_info
  - [**Bugfix**] �޸����߳̽��вɼ���ֹͣʱ��usb cancle���µ��޷��ɼ�����
- tools
  - smarttofviewer
    - [**New**] ����binning���õ�basic setting�� fmt ���õ�adv setting
    - [**New**] UI֧��FILTER_STRENGTH , offset���÷���߼�����
    - [**Enhance**] �Ż�viewer���ٶȺ�scan�豸�Ŀ���
    - [**Bugfix**] �޸��豸�л���Ч����
    - [**Bugfix**] �޸��״��豸��ѡ����ȷ������
    - [**Bugfix**] �޸�binning�ؼ���������
- ros
  - [**Bugfix**] �޸�����ʱ��·������
- samples
  - [**Enhance**] ��Android��ؿ������
  - [**Enhance**] ����OpenNI����



# �汾�ţ�1.70

## ����ʱ�䣺2019/8/5

### �̼����� �̼��汾��170

- [**New**] Binning����֧�� 
- [**New**] ����EPC635֧��
- [**New**] �̼������޸�
- [**New**] ����binning���ã���ͨ��ROI������binning�������ã�ͳһROI��������
- [**Bugfix**] �޸�ROI ������
- [**Bugfix**] �޸��ʼǱ��ɼ���ʱ����

### SDK�������
- dmcam lib
  - [**New**] ����binning���ù���
  - [**New**] �޸�EPC����roi��row���ã�ROI�������ú������
  - [**New**] ����EPC635��֧��
    - ���ᴫ��������
      - [**New**] imx˫Ƶ����ģʽ֧��
      - [**New**] ����bpf�˲�ǿ��
      - [**New**] 
  - [**Enhance**] �Ż�dm_stream��TRACE��ӡ
  - [**Enhance**] ����roi��صĴ�ӡ��Ϣ
  - [**Bugfix**] ����������API:dmcam_cmap_float
  - [**Bugfix**] �޸�EPC��binning¼������
  - [**Bugfix**] �޸���ʼ����ΪHDRģʽ¼��طŵ�����
- tools
  - smarttofviewer
    - [**New**] ���·���ͼƬ
    - [**New**] ����binning���ù���
    - [**New**] ����dmcam_dist_u16 ¼��
    - [**Bugfix**] �޸�binningģʽ�ط�����
    - [**Bugfix**] �޸�У׼��ϲ���ȷ�����⣬����У׼ֵУ����޸�����
    - [**Bugfix**] �޸�pclviewer��smarttofviewer�ӽǲ�һ�µ�����
  - smarttof_cli
    - [**New**] ֧��-u��ʽָ��device_uri,֧��ONI¼���豸��ʹ��
    - [**Enhance**] �޸�ROI���ø���
    - [**Bugfix**] �޸�capture������file replayʱ��Ĳ�������
- ros
  - [**New**] ros���Ӳ���dmcam���cmake
  - [**Enhance**] ����ʹ����ط����ӿڣ�ͬ�������µĿ�
- samples
  - [**Enhance**] ��Android��ؿ������
  - [**Enhance**] ����OpenNI����



# �汾�ţ�1.68

## ����ʱ�䣺2019/3/30

### �̼����� �̼��汾��168

- [**Bugfix**] ��MCU����������
- [**Bugfix**] �޸�ʱ���������ͺ�����
- [**Bugfix**] E3�̼�֡�������޸�
- [**Bugfix**] �˶�ģʽ�Ҷ�֡��С��������

### SDK�������
- dmcam lib
  - [**New**] ����dmcam_frame_get_pcl_xyzi�ӿڻ�ð����Ҷ�����ĵ���
  - [**New**] ����dmcam_cap_seek_frame�ӿ��Ա��ڲ���¼���ļ�ʱ����֡
  - [**New**] ����dmcam_frame_get_dist_raw�ӿڻ��ԭʼ�Ĳ���У׼���ݵ��������
    - ���ᴫ��������
      - [**New**] Ϊ���ᴫ��������ѹ��֧��
      - [**New**] �������ᴫ�������˲����Ż�
      - [**New**] ���Ჿ��У׼
  - [**Enhance**] �ӹ̼�164�汾��¼��֧�ֻ�����У׼�ĻҶ�֡
  - [**Enhance**] ¼��֧��HDRģʽ����ͨģʽ���л�
  - [**Enhance**] �������豸dmcam_dev_get_uri���ش�token��־��URI
  - [**Enhance**] ���dmcam_frame_get_pcl_xyzd��dmcam_frame_get_pcl_xyzi�ļ�������
  - [**Bugfix**] �޸���ͷ�����ļ��򿪺�δ�رյ�����
  - [**Bugfix**] �޸�¼���ļ�û��ʱ���������
  - [**Bugfix**] ��Թ̼�164�汾�豸��ʱ���������رյ�����
- tools
  - smarttofviewer
    - [**New**] �������ӿ���������ʾѡ��
    - [**New**] �������ӡ����·�תѡ���ȥ���������ż�⡱
    - [**New**] �������ͼ-ԭʼ��ͼ����ʾraw��ʽ
    - [**New**] ���ӡ��ظ����š�ѡ��ط�ʱ��Ĭ��ѡ��
    - [**Enhance**] �Ż�֡�ʽ������÷�ʽ
    - [**Bugfix**] �޸�HDR������¼�񲥷�����
- ros
  - [**Enhance**] ����ʹ����ط����ӿڣ�ͬ�������µĿ�
- samples
  - [**New**] ����python������ʹ�����µĽӿ�
  - [**Enhance**] ��Android��ؿ������
  - [**Enhance**] ����OpenNI����
- doc
  - [**Enhance**] ���°�SmartToF SDK User Guide ,��readthedoc���й�


# �汾�ţ�1.62

## ����ʱ�䣺2019/1/30

### �̼����� �̼��汾��164

- [**New**] ������ROI֧��
- [**New**] ���ӻ����ⲹ��֧��
- [**NEW**] ��������RAM����
- [**Bugfix**] �޸�ʱ������벿�ִ���
- [**Bugfix**] ֧���¶ȸ��Զ���֡

### SDK�������
- dmcam lib
  - [**New**] �ɼ�����API�ӿڱ��������dmcam_cap_config_set()�ӿڣ���ͳһ����֡������Ƿ���¼��
  - [**New**] ���ӻ����ⲹ��
  - [**Enhance**] ����Ż����㴦���ٶ�
  - [**Enhance**] ����get_pcl�ӿ���������ͼһ���Ļ�����һһӳ�䣩�������ֵ��Ч��Ϊ��0,0,0����0,0,0,0��
  - [**Enhance**] ����ϵͳУ׼����
  - [**Bugfix**] �޸����ýӿڸ�λʱusb��ס����
  - [**Bugfix**] �޸�get_frames�ڴ���ƽ̨�ٶȽ�����ʱ�������ֻ֡����1֡�����⡣
  - [**Bugfix**] �޸�TC-E3¼�ƺͻط�֡�����Ե�����
- tools
  - smarttofviewer
    - [**New**] ¼������֧��OpenNI����ģʽ
    - [**Enhance**] �Ż�linux��ʾ����
    - [**Bugfix**] �޸�����·�����⣬�޸��л��豸��¼��֮��״̬������������
    - [**Bugfix**] �޸��̼��ļ�����·����������
    - [**Bugfix**] �޸�����ƫ������ʱ�����µ�����
  - smarttof_cli
    - [**New**] ����HDR����ʱ�����ã��ɼ��洢����ɨ��洢
    - [**New**] info�������Ӵ�ӡURI��Ϣ
    - [**New**] ����filter���ɼ�������
    - [**New**] ��λ������ʾ��Ϣ
    - [**Bugfix**] �޸�������쳣���������������
- ros
  - [**Bugfix**] �޸�ros����ʱ���ͼ�͵���ͼ��ʾʱ��������
- Openni
  - [**New**] ����Openni֧��ģ��������Դ��
- samples
  - [**New**] ����C#����get/set param ����Ƭ��
  - [**New**] ����python������ʹ�����µĽӿ�
  - [**Enhance**] ��Android��ؿ������
  - [**Enhance**] ����OpenNI����
- doc
  - [**New**] �İ�SmartToF SDK User Guide ,��readthedoc���й�
  - [**New**] �����˶�ģʽ����˵��

# �汾�ţ�1.60

## ����ʱ�䣺2018/9/23

### �̼�����

- [**New**] ֡������Ϣ����ʱ�����Ϣ����ȷ��0.1ms
- [**New**] ֧��ϵͳУ׼�����洢����ȡ
- [**Enhance**]  �˶�ģʽ�Ż�
- [**Bugfix**] �޸��ϵ�������˸һ������

### SDK�������
- dmcam lib
  - [**New**] �ɼ�����API�ӿڱ��������dmcam_cap_config_set()�ӿڣ���ͳһ����֡������Ƿ���¼��
  - [**New**] ����dmcam_dev_open_by_uri�� ��ͨ��URI ��ָ����USB��ETHERNET��¼���ļ��豸
  - [**New**] ֧��¼��Ͳ���¼���ļ�����
  - [**New**] ����Ӧ�ö�ϵͳУ׼������ȡ
  - [**New**] ����֡��ȡʱ�����ʱ���λ��dmcam_frame_info_t
  - [**New**] �޸Ļ�ȡ��ȺͻҶ����ݽӿ�(dmcam_frame_get_dist/gray_u16/f32�����Ӹ������ɫת���ӿ�(dmcam_cmap_dist_u16/f32_to_RGB, dmcam_cmap_gray_u16/f32_to_IR)
  - [**Enhance**] �Ż��˶�ģʽ�ӿ�
  - [**Enhance**] gray��֧���˶�ģʽ
- tools
  - smarttofviewer
    - [**New**] ����¼��Ͳ���¼����
    - [**New**] ����֧�ֶ��豸ѡ�� 
  - smarttof_cli
    - [**New**] ����rx replay������Խ���dmcam¼��Ļ�ȡ
    - [**Enhance**] �Ż�help����
    - [**Bugfix**] �޸��̼��ļ�����·����������
- samples
  - [**Enhance**] ����c/c++�ɼ��ӿ���������������sample_save_replayչʾ¼�������
  - [**Enhance**] ����java�ɼ��ӿ�����
  - [**Enhance**] ����C#�ɼ��ӿ�����
  - [**Enhance**] ��Android��ؿ������
  - [**Enhance**] ����OpenNI����
- doc
  - [**New**] ����SmartToF SDK User Guide ,�ϴ������й�



# �汾�ţ�1.56

## ����ʱ�� �� 2018/09/21

### �̼�����
- [**Bugfix**] �޸��¶ȼ�֡���л��ϲ�missing frame����
- [**Bugfix**]�޸����õ�֡���Զ���֡����
- [**New**]�����˶�ģʽ֧��
- [**New**]�ӿ��¶ȸ���Ƶ��

### SDK�������

- dmcam lib
  - [**New**] ֧���˶�ģʽ0��1������������������˶�ʱ����Ӱ���⡣
  - [**New**] ֧��UDP cap
  - [**Enhance**] ��־��ӡ�Ż�
  - [**Enhance**] ����Ż�HDRЧ��
  - [**Bugfix**] �޸�����ģʽHDR����
  - [**Bugfix**] �޸�filter_enable�ӿ���ЧID����true������
  - [**Bugfix**] �޸�dmcam_get_frames���ܳ�ʱ������
- C#��չ
  - [**New**] �ṩC#��������Ҫ�Ŀ�
- tools
  - smarttofviewer
    - [**New**] �����˶�ģʽ0��1����֧��
    - [**New**] �Ҷ�ģʽ��ʾƽ����ֵ
  - smartofcli
    - [**New**] CLI���߸�Ϊ��̬����
- samples
  - c#
    - [**New**] ����c#ʹ��dmcam��ӿ�����

# �汾�ţ�1.54

## ����ʱ�� �� 2018/08/28

### �̼�����

- [**Bugfix**] �޸�ͼ��������ص��λ���⣬�ɰ汾150����ĳ����������⡣
- [**Bugfix**] �ָ�֡����У��

### SDK�������

- dmcam lib
  - [**New**] ֧��TCM-E3�ͺŵ�120fps�ɼ�ģʽ
  - [**Enhance**] �Ż�����˲�����
  - [**Enhance**] API�ӿ��̰߳�ȫģʽ֧��
  - [**Enhance**] ����У׼��������
  - [**Bugfix**] �޸��¶Ȳɼ�����ʱ�����20�������ҵ����
  - [**Bugfix**] �޸�dmcam_cap_get_frame�ӿڵ���һ����յ�ǰframe buffer����
  - [**Bugfix**] �޸��״μ���У׼����offset����
  - [**Bugfix**] �޸���У׼����������ͼ������
- cli
  - [**Enhance**] rx�����Ż�
  - [**Enhance**] regrd/regwr �����ַ֧��16 ��������
  - [**Enhance**] ��ǿ��ӡ˵��
- tools
  - smarttofviewer
    - [**New**] ����֡�ʡ��¶ȡ���ֵ������ƫ�����ʾ
    - [**Enhance**] ��ߵ�����ʾЧ����ƽ��ƽ����

# �汾�ţ�1.50

## ����ʱ�� �� 2018/08/10
## ע��
��ģ��У׼���ݸ�ʽ�������޸ģ�ʹ���°�SDK��Ҫģ��̼�ȫ�����µ�1.50

### �̼�����
- �޸�����36MHZ����Ķ�ȡ֡�ʲ�������
- bootloaderУ�������޸������ӹ̼��Ϸ��Լ��
- �޸�ͼ��ϲ�����
- �޸�ͼ�񶪲�������������

### SDK�������
- dmcam lib
  - �Ż�У׼���ݼ��ؼ��洢��ʽ
  - ����dm_gausfilterģ�飬dm_convģ��
  - ֧��2�鲻ͬƵ��У׼�����л���Ĭ��ʹ�õ�һ��У׼����
  - �Ż������νṹ���Ż��ڴ棬�Ż�����ִ��Ч��
- ros
  - �޸�������ʾ������
- tools
  - smarttofviewer
    - ���ӹ̼��汾����143�ĵ��򾯸�
    - �Ż�UI���֣�����waring��ʾ
    - ����Ƶ���л�֧��

# �汾�ţ�1.43
## ����ʱ�䣺2018/07/26
## ע��
��ģ��̼��������޸�������ģ�����ȫ�����µ�SDK V1.43�еĹ̼���

### �̼�����
- �޸�0�����»���IB���¶Ȳɼ�����
- �޸�ϵͳ�¶ȸ��»���
- �޸�ADC�ɼ���ʱͼ�񿨶�����
- �޸��̼���GPIO��ʼ�����ڳ�ͻ����
- ��ǿ�������ԣ�PC����USB�豸��εĸ��ţ�

### SDK�������
- dmcam lib
  - �޸�drnu���ܵ��ڴ���ʴ���
  - �޸�Ĭ�ϲ�����pix calib������
  - �޸�У׼���ݲ���У׼Ƶ�ʵ��µ�simple calib��������
  - ����javaʹ��simple calib
- tools 
  - Smarttof cli
    - �޸��ɼ����ݶ�ʧ����
  - Smarttofviewer
    - �޸�smarttofviewer���������˳�������


# �汾�ţ�1.42

## ����ʱ�䣺2018/07/13

## ע��
��linux��ʹ��SDK V1.31���Ժ�汾����Ҫ����ģ��̼���ģ�������ļ�λ��SDK�е�firmwareĿ¼��

### �̼�����
- ͬSDK V1.40�汾

### SDK�������
- dmcam lib
  - �����Ż���filter��gauss��flynoise��fillhole
  - ��һ���Ż�����Ч��
  - �޸�����cap_start���µ�����
  - �Ľ�ʵ�����ƫС����
  - �Ľ������㷨���Ż��ڴ�ռ��
  - �޸��ڴ�й©
# �汾�ţ�1.40

## ����ʱ�䣺2018/07/05

## ע��
��linux��ʹ��SDK V1.31���Ժ�汾����Ҫ����ģ��̼���ģ�������ļ�λ��SDK��firmwareĿ¼��

### �̼�����
- ͬSDK V1.32�汾��û�и���

### SDK�������
- dmcam lib
  - ���ӵ����Ż�����Ĭ��ʹ��fliter_idΪDMCAM_FILTER_ID_MEDIAN,�û��������йر�
  - �޸�HDR��ʾ����
  - �޸��Ҷ�ͼʱ�ڴ�й©����
- tools
  - SmarttofViewer
    - �������ͼ�˲���ѡ��
    - ����Ż�������ʾЧ��
- firmware
  - ����firmware�ļ��У���Ź̼���������ļ�




# �汾�ţ�1.32

## ����ʱ�䣺2018/06/21

## ע��

SDK v1.31�������ϰ汾��linux�²�������ǰ��ģ��̼���������linux��ʹ��SDK v1.31����Ҫ����ģ��̼���ִ��fw_upgrade.bat�ű�����ģ��������

## ��Ҫ�޸ģ�

### �̼�����

- �޸�CB���¶ȸ��»���
- �汾��132

### SDK�������

- dmcam lib
  - �޸�HDR�Ҷ�ͼ����
  - ���ӽ���DRNU����У׼֧��
  - �����ǿUSB���俹���Ŵ���
  - �Ż��¶Ȳ���ϵ��
- Android
  - ͬ������SmartTofViewer apk
- Samples
  - ����C++����
- tools 
  - SmartTofViewer
    - �������ӡ�����У׼����ѡ��
    - �޸��ײ�stall����viewer�쳣��������
  - SmartTofCli
    - ���ӹ̼���ģ��Ӳ���Ƿ�ƥ����

# �汾�ţ�1.31

## ����ʱ�䣺2018/05/25

## ע��

SDK v1.31�汾��linux�²�������ǰ��ģ��̼���������linux��ʹ��SDK v1.31����Ҫ����ģ��̼�������HDR���¶ȱ����������� windows��linux�¶���Ҫ����ģ��̼����̼�λ����SmarttofCli��

## ��Ҫ�޸ģ�

### �̼�����

- �¶ȱ�����ͽ���1֡���¶Ƚ�������֧���Զ���֡��
- ��ǿ�л�֡���ȶ���

### SDK�������

- dmcam lib
  - �޸���֡��timeout����
  - �޸�HDR�;�ͷУ׼ͬʱʹ������
  - ����Ż�����ת���ӿڣ�raw2dist,raw2gray������
  - �޸�frame_get_xyzd�ӿ������ɫ���ܲ���������
  - Ĭ�Ͼ�ͷ����ʹ�þ�ͷTRC-2150D2(122��)�Ĳ���
  - �޸�ƽ���������ͼ���������⣬�Ż�������ʾЧ��
- tools 
  - PCLViewer
    - �Ż���ʾ������Ч��

# �汾�ţ�1.30

## ����ʱ�䣺2018/05/21

## ��Ҫ�޸ģ�

### �̼�����
  - ����HDR֧��
  - �޸�USB�쳣�Ͽ����ư�δ�ر�����
  - �����¶ȱ�������
  - ����֡����У��
  - �޸�����֡����padding�󣬵�֡�ʲɼ�����
  - �޸���Դָʾ�Ʋɼ���Ϩ������

### SDK�������
- dmcam lib
  - ����HDR֧��
  - ��������֡ͷ���Ż������ٶ�
  - ����֡����У��֧��
  - �޸�android ���豸����
  - �޸����������������
- Android
  - ����Androidƽ̨֧��
    - �ṩAndroidƽ̨����Ҫ�Ŀ�
    - �ṩAndroidƽ̨smarttofviewer���ߺ�Դ��
- Samples
  - ����windows��Openni2��������
  - ����ʹ��Openni2����
- tools 
  - SmartTofViewer
    - ��������HDRѡ���HDR�ع�ʱ�������
  - SmartTofCli
    - �޸��ɼ�ʱ��ȡ���ݴ����bug
- doc
  - ����
  - README_OpenNI2.md
  - Ӧ��ָ��
  - ��SmartTof FAQ �ֲᡷ
  - ��SmartTof SDK ��顷
  - ��SmartTof_Cli ˵���ĵ���
  - ��SmartTof����������ģ��ͬʱʹ��ʱ�Ĵ��š�
- ����
  - ��linux������ʹ��ģ���豸��Ȩ�����õĽű�




# �汾�ţ�1.20

## ����ʱ�䣺2018/04/13

## ��Ҫ�޸ģ�

- dmcam lib
  - �Ż��¶�У׼����
  - �����¶ȱ�������
  - ���Ӷ�ģ���������˲�֧��
- ROS
  - ����ROSƽ̨֧��
    - �ṩ��ȡ��Ҷȡ����ơ��������4��topic
    - �ṩ�޸Ĳ���service
    - �ṩROS��չ������
- Android
  - ����Androidƽ̨֧��
    - �ṩAndroidƽ̨smarttofviewer���߼�Դ��
    - �ṩAndroidƽ̨����Ҫ�Ŀ�
- samples
  - ��������readme
- tools
  - SmartToFCli
    - ���ӱ���Ҷȡ���ȡ�������������֧��
    - ���ӹ̼����½ű�
  - SmartToFViewer 
    - �������Ӷ�ģ���˲����Ÿ�ѡ��
- doc
  - ����readme
    - README_C_sample.md
    - README_Python_sample.md
    - README_sample.md
  - Ӧ��ָ��
    - ��SMARTTof_SDK_ROS�û��ֲ�.pdf��
    - ��TCM-Exģ��̼�����˵��.pdf��
    - ��SmartTof������ò�����������ͼ��.pdf��
    - ��SmartTof����������ͼ��.pdf��

# �汾�ţ�1.15

## ����ʱ�䣺2018/03/09
## ��Ҫ�޸ģ�
- dmcam lib
  - ���Ӿ�̬�����(.a)��visual studio��(.lib)
  - ֧���Զ��ع�ʱ��ģʽ
- python
  - ����python��չ�ȶ���
  - ����windows 64bit python֧��
    - win��Ŀǰ֧�� python 2.7/3.4/3.5/3.6 ��32bit��64bit�汾
    - Linux��Ŀǰ֧�� python 2.7/3.4/3.5 ��64bit�汾
- java
  - ����linux java��չ
    - win��֧��java 32bit, 64bit
    - Linux��֧��java 64bit
- samples
  - Ϊc/c++ sample����CMakelist.txt����ֱ���ڷ���Ŀ¼�±���
- tools
  - SmartToFCli
    - Ĭ�Ͻ���interactiveģʽ��-h��ʾ����
  - SmartToFViewer 
    - �Ż��Ҷ�ͼ��ʾ
    - ֧���Զ��ع�ʱ��ģʽ

# �汾�ţ�1.12
## ����ʱ�䣺2018/02/28
## ��Ҫ�޸ģ�
 * �����¶Ȳ���
 * ֧��֡������
 * �Ż��Ҷ�ͼ��ʾ
