1. city_code_cn �� DDL��
CREATE TABLE `city_code_cn` (
  `ID` smallint(5) unsigned NOT NULL AUTO_INCREMENT COMMENT '����',
  `CITY_CODE` char(4) NOT NULL COMMENT '���д��롷��λ����������',
  `CITY_JB` tinyint(3) unsigned NOT NULL COMMENT '���м��𡷷ǿա�1��ʡ����2���ؼ���3���ؼ�',
  `PROVINCE_CODE` char(4) NOT NULL COMMENT '����ʡ�ݴ��롷�ǿ�',
  `STATE` char(1) NOT NULL DEFAULT '1' COMMENT '����״̬���ǿա�0����Ч���У�1����Ч����',
  `CITY_NAME` varchar(50) NOT NULL COMMENT '��������',
  `CITY` varchar(50) NOT NULL COMMENT '���ڵؼ�������',
  `PROVINCE` varchar(50) NOT NULL COMMENT '����ʡ������',
  PRIMARY KEY (`ID`)
) ENGINE=InnoDB AUTO_INCREMENT=2324 DEFAULT CHARSET=utf8 COMMENT='ȫ�����б�';
2. ��Ŀ���Կ��Ը��� CityController ��ض���ӿڽ������������ JMeter ����ʹ�� jmeter Ŀ¼�еĽű���