应用表
INSERT INTO advertis_application 
(name,code,from_platform)
VALUES
("有成报销","youchengcaiwu", "yccw_manage"), 
("有成财务","youchengbaoxiao","yccw_manage");


页面表

INSERT INTO advertis_page 
(application_code,name,code,from_platform)
VALUES
("youchengbaoxiao","报销增值服务", "reimbursement.valueAdded"), 