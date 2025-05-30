<h1>Active Directory Users and Computers (ADUC) - Give Delegation Of Control To A User Or Group To Have Administrative Privileges (EX: To Be Able To Reset Passwords For Other Users)</h1>


<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;">
⏹️ Description</h2>

<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
This project goes over how to give delegation of control to a user or group using Active Directory Users and Computers. Giving delegation of control using Active Directory Users and Computers (ADUC) allows administrators to grant specific users or groups the authority to perform administrative tasks on a limited scope, without granting them full domain administrative privileges.
</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;">
⏹️ Utilities Used</h2>
  
<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
 
 - <b>Active Directory Users and Computers</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;"> 
⏹️ Environments Used </h2>

<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
 
- <b>Windows 10 & Windows Server 2016</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;"> 
<h2>
⏹️ Project Walk-Through:</h2>
 <br/>

<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>NOTE: Delegation Control = give someone limited access on active directory.</b></span>  
<br/><br/><br/><br/>

<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Open: Active Directory Users and Computers.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/txb6Mot.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/AcOJlQA.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Right-Click: The domain name  (OR) an organizational unit  (OR) folder.  Ex: The domain name.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/Oy3lcjx.png" height="100%" width="100%" /></td>
    <td><img src="https://imgur.com/j6kM8yy.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/QTxjWoo.png" height="100%" width="100%" /></td>
    <td><img src="https://imgur.com/ViSwngX.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Next.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/0JJbApS.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/FiBzNWx.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Add.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/j5ZJTGr.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/ojhQgcf.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Type: The user or groups name in the bottom box: Enter the object names to select.  Click: Check Names.  Click: OK.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/l23mqPh.png" height="100%" width="100%" /></td>
    <td><img src="https://imgur.com/GrMpTqe.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/K7vgIwP.png" height="100%" width="100%" /></td>
    <td><img src="https://imgur.com/q8xRmN3.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/eV3EQML.png" height="50%" width="50%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Next.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/Otfoped.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/irpJt20.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Select: What access you want the user or group to have (click: the correct box(es)), (ex: reset user passwords…).</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/7b7OgLd.png" height="100%" width="100%" /></td>
    <td><img src="https://imgur.com/kOdn5q6.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/PwvgI6l.png" height="50%" width="50%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Finish.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/g5EGGxc.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/TMbpJnV.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />
