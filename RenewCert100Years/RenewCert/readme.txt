

SYNTAX

renewcert <OldCertificate>.pfx <NewCertificate>.pfx CN=<NewCertificateName> <Password> 

EXAMPLE

renewcert a.pfx My_TemporaryKeyPfx.pfx CN=Name Password

经测试旧证书名称有下划线的时候会失败 如 Ar_ERP_3_TemporaryKey
