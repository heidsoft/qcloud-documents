<style rel="stylesheet">
table th:nth-of-type(1){
width:200px;
}</style>
<style rel="stylesheet">
table th:nth-of-type(2){
width:200px;
}</style>
<style rel="stylesheet">
table th:nth-of-type(3){
width:200px;
}</style>
<style rel="stylesheet">
table th:nth-of-type(4){
width:200px;
}</style>
<style rel="stylesheet">
table tr:hover {
background: #efefef; 
</style>
## API 概览
您可以使用命令行或 API 操作来设置和管理专线网关，有关 VPC API 的更多内容可以参考 <a href="" target="_blank"></a>[私有网络所有 API 概览](https://www.qcloud.com/doc/product/215/4954)。

| 接口功能 | Action ID |  功能描述 |
|---------|---------|---------|
| 创建专线网关 | [CreateDirectConnectGateway](https://www.qcloud.com/doc/api/245/4824) | 创建专线网关。 |
| 修改专线网关属性 | [ModifyDirectConnectGateway](https://www.qcloud.com/doc/api/245/4825) | 修改专线网关属性。|
| 删除专线网关 | [DeleteDirectConnectGateway](https://www.qcloud.com/doc/api/245/4826) | 删除专线网关。 |
| 查询专线网关 | [DescribeDirectConnectGateway](https://www.qcloud.com/doc/api/245/4827) | 查询专线网关。 |
| 添加专线网关本端 IP 转换 | [CreateLocalIPTranslationNatRule](https://www.qcloud.com/doc/api/245/5185) | 添加专线网关本端 IP 转换。 |
| 删除专线网关本端 IP 转换 | [DeleteLocalIPTranslationNatRule](https://www.qcloud.com/doc/api/245/5186) | 删除专线网关本端 IP 转换。 |
| 修改专线网关本端 IP 转换 | [ModifyLocalIPTranslationNatRule](https://www.qcloud.com/doc/api/245/5187) | 修改专线网关本端 IP 转换。 |
| 查询专线网关本端 IP 转换 | [DescribeLocalIPTranslationNatRule](https://www.qcloud.com/doc/api/245/5188) | 查询专线网关本端 IP 转换。 |
| 添加专线网关本端源 IP 端口转换 | [CreateLocalSourceIPPortTranslationNatRule](https://www.qcloud.com/document/product/215/5190) | 添加专线网关本端源 IP 端口转换。 |
| 删除专线网关本端源 IP 端口转换 | [DeleteLocalSourceIPPortTranslationNatRule](https://www.qcloud.com/document/product/215/5191) | 删除专线网关本端源 IP 端口转换。 |
| 修改专线网关本端源 IP 端口转换 | [ModifyLocalSourceIPPortTranslationNatRule](https://www.qcloud.com/document/product/215/5192) | 修改专线网关本端源 IP 端口转换。 |
| 添加专线网关本端目的 IP 端口转换 | [CreateLocalDestinationIPPortTranslationNatRule](https://www.qcloud.com/document/product/215/5195) | 添加专线网关本端目的 IP 端口转换。 |
| 删除专线网关本端目的 IP 端口转换 | [DeleteLocalDestinationIPPortTranslationNatRule](https://www.qcloud.com/document/product/215/5196) | 删除专线网关本端目的 IP 端口转换。 |
| 修改专线网关本端目的 IP 端口转换 | [ModifyLocalDestinationIPPortTranslationNatRule](https://www.qcloud.com/document/api/215/5197) | 修改专线网关本端目的 IP 端口转换。 |
| 查询专线网关本端目的 IP 端口转换 | [DescribeLocalDestinationIPPortTranslationNatRule](https://www.qcloud.com/document/product/215/5198) | 查询专线网关本端目的 IP 端口转换。 |
| 添加专线网关对端 IP 转换 | [CreatePeerIPTranslationNatRule](https://www.qcloud.com/doc/api/245/5190) | 添加专线网关对端 IP 转换。 |
| 删除专线网关对端 IP 转换 | [DeletePeerIPTranslationNatRule](https://www.qcloud.com/doc/api/245/5191) | 删除专线网关对端 IP 转换。 |
| 修改专线网关对端 IP 转换 | [ModifyPeerIPTranslationNatRule](https://www.qcloud.com/doc/api/245/5192) | 修改专线网关对端 IP 转换。 |
| 查询专线网关对端 IP 转换 | [DescribePeerIPTranslationNatRule](https://www.qcloud.com/doc/api/245/5193) | 查询专线网关对端 IP 转换。 |
| 添加本端 IP 转换 ACL 策略 | [CreateLocalIPTranslationAclRule](https://www.qcloud.com/doc/api/245/5205) | 添加本端 IP 转换 ACL 策略。 |
| 删除本端 IP 转换 ACL 策略 | [DeleteLocalIPTranslationAclRule](https://www.qcloud.com/doc/api/245/5206) | 删除本端 IP 转换  ACL 策略。 |
| 修改本端 IP 转换 ACL 策略 | [ModifyLocalIPTranslationAclRule](https://www.qcloud.com/doc/api/245/5207) | 修改本端 IP 转换 ACL 策略。 |
| 查询本端 IP 转换 ACL 策略 | [DescribeLocalIPTranslationAclRule](https://www.qcloud.com/doc/api/245/5208) | 查询本端 IP 转换  ACL 策略。 |
| 添加本端IP端口转换 ACL 策略 | [CreateLocalSourceIPPortTranslationAclRule](https://www.qcloud.com/doc/api/245/5211) | 添加本端 IP 端口转换  ACL 策略。 |
| 删除本端 IP 端口转换 ACL 策略 | [DeleteLocalSourceIPPortTranslationAclRule](https://www.qcloud.com/doc/api/245/5212) | 删除本端 IP 端口转换  ACL 策略。 |
| 修改本端 IP 端口转换 ACL 策略 | [ModifyLocalSourceIPPortTranslationAclRule](https://www.qcloud.com/doc/api/245/5213) | 修改本端 IP 端口转换 
ACL 策略。 |
| 查询本端 IP 端口转换 ACL 策略 | [DescribeLocalSourceIPPortTranslationAclRule](https://www.qcloud.com/doc/api/245/5214) | 查询本端 IP 端口转换  ACL 策略。 |