Project PCN Network Automation using Ansible.  
---
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Ansible เป็น Open Source Software ที่ทำหน้าที่เป็น Automation Engine โดยตัว Ansible สามารถเข้าไปควบคุมอุปกรณ์ปลายทางที่เรียกว่า Managed Node โดยตัว
Ansible ถูกออกแบบให้ทำงานแแบ Angentless ทำให้ไม่ต้องติดตั้ง Software อื่นใดๆที่ Managed Node เลย

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Ansible Network Automation เป็นการเอาตัว Ansible นี้มาช่วยในการทำ Network Automation ซึ่งหลักๆก็คือการส่งชุดคำสั่ง Config ไปให้ตัวอุปกรณ์ Network เพื่อจะได้ไม่ต้องไป Config มือเอง ทำให้สามารถจัดการตัวอุปกรณ์ได้หลายตัวในเวลาที่รวดเร็ว และลดการผิดพลาดที่เกิดจากมนุษย์ นอกจากนี้ยังสามารถอ่านค่าจากตัวอุปกรณ์ Network และนำข้อมูลที่ได้มาเขียนลงไฟล์ ได้อีกด้วย

Information. 
---
Document link: https://docs.google.com/document/d/1bxVOGRxbVvuRqnpdpGyNQNP8ZbLCYMNlfIG3CF5Um1I/edit?usp=sharing  
Youtune link: www.youtube.com  

Authors 
---
<table cellspacing="0"><thead>
<th scope="col">#</th>
<th scope="col">Firstname</th>
<th scope="col">Lastname</th>
<!-- Language currently disabled: GitHub returns 'Shell' for most users <th scope="col">Language</th> -->
<th scope="col">STD.code</th>
<th scope="col" width="150">Picture</th>
</thead><tbody>
<tr>  <th scope="row">#1</th>  <td> นาย ฟุ้งเกียรติ</td>  <td>เผด็จตะคุ</td> <td>60070069</td>  <td><img width="100" height="100" src="https://scontent.fbkk22-4.fna.fbcdn.net/v/t1.0-9/75392681_2784770338252567_5489999090928320512_n.jpg?_nc_cat=109&_nc_sid=7aed08&_nc_eui2=AeHrnhMjGOhc6qtvOk9-YOSYzxmYQsTcVpPPGZhCxNxWk9A9lAzRioID37EDlLi0IRfY7ywuH8T8LwOqw6SBEH6e&_nc_oc=AQmPGGIHvfFVmHyGzakm_GCL_ZxLM6rFigUw-LIyN39LdG7fSIla8OGyjdNn6BK8V-I&_nc_ht=scontent.fbkk22-4.fna&oh=323c3d902d78d32d6c6de2b6d1482290&oe=5EE793F0"></td></tr>
  <tr>  <th scope="row">#2</th>  <td> นาย ภัคพล</td>  <td>ตันวัฒนา</td> <td>61070153</td>  <td><img width="100" height="100" src="https://scontent.fbkk22-4.fna.fbcdn.net/v/t1.0-9/15037210_584062761785106_4397154544504754833_n.jpg?_nc_cat=111&_nc_sid=85a577&_nc_eui2=AeHeL6ZYFQy7OuD_vadTohR-qb_pVpCYl96pv-lWkJiX3jxSVpkKU_JqfSjgQQA4U2wmZR-IsjEfJ674RWH-De7l&_nc_oc=AQl_GfCWPk-bPY92QvpC4jVbGHNynX2P2XeFHYjs2GqmDmqVehncqnWpyAb2FCdot8E&_nc_ht=scontent.fbkk22-4.fna&oh=37c7b475c33185cb290f9cc2203d17ea&oe=5EE7F329"></td></tr>
  <tr>  <th scope="row">#3</th>  <td> นาย ภูริณัฐ</td>  <td>จิตมนัส</td> <td>61070171</td>  <td><img width="100" height="100" src="https://scontent.fbkk22-2.fna.fbcdn.net/v/t1.0-9/38448264_1956734931038221_3840491221290057728_n.jpg?_nc_cat=107&_nc_sid=85a577&_nc_eui2=AeHXKUPTDLeRhvsFgvDuZuhoZfNuXO7Hkjhl825c7seSOCQt9cuS5FKYuMMQwrRCXkQ7aLIF0MgMD7ms4-HEVNtJ&_nc_oc=AQlab0qg1GYQFy9J8SX5IcYyVv9F686aQbnrRB6Sqq53lojQo1HgwWT8vz55t00mjnY&_nc_ht=scontent.fbkk22-2.fna&oh=c357c71cecc50dc750bbf581583cac1e&oe=5EE879E4"></td></tr>
  <tr>  <th scope="row">#4</th>  <td> นาย นาย วัฒนวิชญ์</td>  <td>มิ่งเชื้อ</td> <td>61070153</td>  <td><img width="100" height="100" src="https://scontent.fbkk22-4.fna.fbcdn.net/v/t1.0-9/75439242_2349027521893036_2721607280964403200_n.jpg?_nc_cat=111&_nc_sid=7aed08&_nc_eui2=AeFO0VYfA6sM6JALoJ0juPOkPFbGoWze_ds8VsahbN7921fhqi6B_CvFYXuN0I7v8GERcx3Qf36oIhvEPVlEIiHE&_nc_oc=AQm-meVzu5h084tQ_0AlJoCV96lJwh_EU2RQtjzpcBDyuDMhBoTpwFTm_ctRhp-Xszc&_nc_ht=scontent.fbkk22-4.fna&oh=4e016a2be836ea6199f16fbfbf623d6d&oe=5EE8CC55"></td></tr>
  <tr>  <th scope="row">#5</th>  <td> นาย วิศรุต</td>  <td>แก้วงาม</td> <td>61070210</td>  <td><img width="100" height="100" src="https://scontent.fbkk22-2.fna.fbcdn.net/v/t31.0-8/p960x960/22424170_1475444652532736_7000814947367213850_o.jpg?_nc_cat=105&_nc_sid=85a577&_nc_eui2=AeHcCiwqJlQg8ql8yPr4WGFoXegJgGbZ1Rpd6AmAZtnVGu5qAsMh4PnPLjo1mkBdKLL3rCqOzMZoZGO7AJUsLL_F&_nc_oc=AQkNfBGSrMsfvd2pmI2iTQ-XwJYguEJ_NSqk0jvbSXyv67zflqgtsdoMRwWQ7Gsk9pM&_nc_ht=scontent.fbkk22-2.fna&_nc_tp=6&oh=ca152602ef2dae19cb13d7307e51207a&oe=5EE6D354"></td></tr>
</tbody></table>

