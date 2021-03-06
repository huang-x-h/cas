# SSL证书限制说明 {#concept_pvp_3hp_ydb .concept}

申请证书的密钥和证书格式等存在一定的限制条件。

在使用阿里云SSL证书服务选购证书时，有如下限制：

-   暂时只支持两种服务器证书（专业、高级），每种服务器证书所对应的CA中心可能有不同产品（或者不提供相应证书），您可按照您的需求进行选择。
-   根据CA中心的要求，需要您提供您企业的真实合法的验证材料，阿里云会将这些材料提交至CA中心进行[审核](../../../../../intl.zh-CN/用户指南/申请和提交审核.md#)。审核过程中，CA中心会直接通过邮件或者电话的方式联系您。
-   对证书申请时的密钥加密位数限制为至少RSA 2048，哈希签名算法至少SHA 256，请您依据限制生成CSR文件。
-   云盾证书服务提供的[证书格式](../../../../../intl.zh-CN/常见问题/常见问题/主流数字证书都有哪些格式？.md#)为PEM格式。
-   [免费证书](intl.zh-CN/快速入门/步骤一：选配证书.md#ul_qsf_vmp_ydb)有效期为1年。

