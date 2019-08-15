
SpringBootCodeGenerator
----
基于SpringBoot2+Freemarker的代码生成器，用DDL SQL语句生成JPA/JdbcTemplate/Mybatis/BeetlSQL相关代码，支持mysql/oracle/pgsql等三大数据库。以释放双手为目的，各大模板也在陆续补充和优化。欢迎大家Issue提交模板和交流想法，也欢迎提交PullRequest！
<br><br>
<table><tbody>
<tr><td>访问路径</td> <td>http://127.0.0.1:1234/generator</td></tr>
<tr><td>在线地址</td> <td>http://java.bejson.com/generator</td></tr>
<tr><td></td> <td></td></tr>
<tr><td>更新日期</td> <td>更新内容</td></tr>
<tr><td>20190518<td>1.优化注释 2.修改 mybatis模板中 controller注解 3.修改 mybatis模板中 dao文件使用为 mapper文件 4.修改 mybatis模板中 service实现类中的一个 bug 5.修改 index.ftl文件中 mybatis模板的 dao -> mapper（感谢@unqin的pull request）</td></tr>
</tbody></table>

<table><tbody>
<tr><td>字段名</td> <td>说明</td></tr>
<tr><td>packageName</td> <td>自定义的包名</td></tr>
<tr><td>authorName</td> <td>自定义的作者名</td></tr>
<tr><td>returnUtil</td> <td>自定义的返回Util</td></tr>
<tr><td>tableName</td> <td>sql中的表名</td></tr>
<tr><td>className</td> <td>java类名</td></tr>
<tr><td>classComment</td> <td>sql表备注/java类备注</td></tr>
<tr><td>fieldName</td> <td>字段名</td></tr>
<tr><td>fieldComment</td> <td>字段备注</td></tr>
</tbody></table>

<img src="./codegenerator1.png">
<img src="./codegenerator2.png">
<img src="./codegenerator3.png">
<img src="./codegenerator4.png">
<img src="./donate.jpg">
<table>
