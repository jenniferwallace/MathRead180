# MathRead180








<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN">
<html>
  <head>
    <LINK REL="SHORTCUT ICON" HREF="/slms/images/gateway_assets/favicon.ico">
    <title>Scholastic Student Access</title>
<link type="text/css" href="css/educatorGateway.css" rel="stylesheet" />
<link type="text/css" href="css/gatewayBanner.css" rel="stylesheet" /> 
<script type='text/javascript'>

function getBaseUrlWithUCN() {
  var DUBSLASH = "://";
  var baseUrl  = "";
  var url      = (location.href);

  if(url.indexOf(DUBSLASH)>=0) {
    var cutIndex = url.indexOf(DUBSLASH)+DUBSLASH.length;
    baseUrl      = url.substring(0,cutIndex);
    url          = url.substring(cutIndex,url.length);
  }
  var elems = url.split('/',3);
  baseUrl  += elems[0] + '/' + elems[1];
  return baseUrl;
}

function openpopup1(pageUrl){
  var d = new Date().getTime();
  var r = Math.random();
  var dr = d + ";" + r;
  var url = pageUrl + "?cb=" + dr;
  winpops=window.open(url,"","width=screen.width,height=screen.height,top=0,left=0,scrollbars,location=no,");
}

function openpopup(pageUrl,winname)
{
	var d = new Date().getTime();
        var r = Math.random();
        var dr = d + ";" + r;
	var winurl = pageUrl + "?cb=" + dr;
    var winfeatures = "directories=no,menubar=no,status=no,titlebar=no,toolbar=no,top=0,left=0,resizeable=0,location=0,statusbar=0";
    winfeatures += ",height=" + screen.height + ",width=" + screen.width;

    // open a new window everytime a student app is launched
	// from the gateway.
	//samsus story 193 -- no chromeless browser for SRI so check url (in this case: '/sri/loader') for 'sri' and open 
	//non chromess browser then; open chromeless browser for all others
	if (pageUrl.indexOf('sri') > -1) {
		newwin = window.open(winurl,'');		
	} else {
	    newwin = window.open(winurl,'',winfeatures);	
	}
    
    if (window.focus) 
    {
    	newwin.focus()
    }
    if (!newwin.closed) 
    {
    	newwin.focus()
    }
}

function openAuthZonePopup(pageUrl,winname)
{
	var d = new Date().getTime();
        var r = Math.random();
        var dr = d + ";" + r;
	var winurl = pageUrl;
    var winfeatures = "directories=no,menubar=no,status=no,titlebar=no,toolbar=no,top=0,left=0,resizeable=no,location=no,statusbar=no";
    winfeatures += ",height=" + screen.height + ",width=" + screen.width;
    newwin = window.open(winurl,'',winfeatures);
}

function submitForm(url,parentId,headerArt,displayTitle){
	document.pageForm.action=url;
	document.pageForm.parentId.value=parentId;
	document.pageForm.headerArt.value=headerArt;
	document.pageForm.displayTitle.value=displayTitle;
	document.pageForm.submit();

}


</script>
<!--Added by - Dhanumjaya Makana for SAMSUS-488 bug fix.  -->

<meta name="robots" content="noindex">
  </head>

  <body>
  	<form name="pageForm" id="pageForm" method="post">

	<input type="hidden" name="parentId">
	<input type="hidden" name="headerArt">
	<input type="hidden" name="displayTitle">

	<div id="container">
		<div align="center" id="header">
			<!-- Header -->
			








<meta http-equiv="Expires"      content="Mon, 01 Feb 1999 22:00:00 GMT">
<meta http-equiv="Pragma"       content="NO-CACHE">
<table  width="1002"  background="/slms/images/gateway_assets/ban_studentAccess.png"  border="0" align="center" cellspacing="0" cellpadding="0" >
	<tr colspan="4" height="87">
		<td align="center"></td>
	</tr>
	<tr align="center" colspan="4">
		<td width="308"></td>
		<td colspan="3" align="left">
		<p class="header">
		
  			
				District: Jackson Public Schools &nbsp;&nbsp;&nbsp;
  			
  		

		
  			
				Server: HOSTED
  			
  		
  		</p>
  		</td>
	</tr>
<tr align="center" colspan="4" height="10"><td></td></tr>
</table>

		</div>
		</br></br>
		<div align="center" id="body">
    			<!-- Page Body -->
			






<meta http-equiv="Expires"      content="Mon, 01 Feb 1999 22:00:00 GMT">
<meta http-equiv="Pragma"       content="NO-CACHE">
<meta http-equiv="refresh" 		content="1800"/>


<table align="center" width="997" border="0" cellspacing="0" cellpadding="0">
<tr><td align="center">
<table border="0" cellspacing="0" cellpadding="0">
  	
	  
	  

		
	        	<tr colspan="7">
	         		 
	            			<td align="center">
								
						              
						            		<a href="javascript:submitForm('/slms/studentaccess/read180ng','4','images/gateway_assets/ban_r180ng.png','READ 180 Next Generation Student Access')"
						            		onmousedown="document.images.item4.src='/slms/images/gateway_assets/btn_r180ng_dn.png';"
				   							onmouseup="document.images.item4.src='/slms/images/gateway_assets/btn_r180ng.png'"
				   							onmouseout="document.images.item4.src='/slms/images/gateway_assets/btn_r180ng.png'">
						            			<IMG SRC="/slms/images/gateway_assets/btn_r180ng.png" BORDER="0" ID="item4"  title="READ 180 Next Generation Program Page"/>
						            		</a>
						            
						             
						             
						            
				         	
						</td>
						
							<td style="padding-right:35px"></td>
						
	         		 
	            			<td align="center">
								
						              
						            		<a href="javascript:submitForm('/slms/studentaccess/m180','43','images/gateway_assets/ban_M180.png','M180 Student Access')"
						            		onmousedown="document.images.item43.src='/slms/images/gateway_assets/btnM180_Dn.png';"
				   							onmouseup="document.images.item43.src='/slms/images/gateway_assets/btnM180.png'"
				   							onmouseout="document.images.item43.src='/slms/images/gateway_assets/btnM180.png'">
						            			<IMG SRC="/slms/images/gateway_assets/btnM180.png" BORDER="0" ID="item43"  title="M180 Program Page"/>
						            		</a>
						            
						             
						             
						            
				         	
						</td>
						
	         		 
	        	</tr>
	        	<tr colspan="7">
	         		<td align="center" style="padding-bottom:20px"></td>
	        	</tr>
	      	
	  
	

	</table>
	</td></tr>
	<tr><td align="center">
	<table border="0" cellspacing="0" cellpadding="0">
	
	  
		<tr><td colspan="8"><img src="/slms/images/gateway_assets/hrule.png"/></td></tr>
	  
	

	<tr><td style="padding-bottom:20px"></td></tr>

	</table>
	</td></tr>
	<tr><td align="center">
	<table border="0" cellspacing="0" cellpadding="0">
	<tr>
		
			<td align="center" style="padding-right:21px;padding-left:21px">
				
				    
				   		<a href="javascript:openpopup('/sri/loader','Scholastic Reading Inventory')"
				   			onmousedown="document.images.item11.src='/slms/images/gateway_assets/btnSM_sri_dn.png';"
				   			onmouseup="document.images.item11.src='/slms/images/gateway_assets/btnSM_sri.png'"
				   			onmouseout="document.images.item11.src='/slms/images/gateway_assets/btnSM_sri.png'">
				    			<IMG SRC="/slms/images/gateway_assets/btnSM_sri.png" BORDER="0" ID="item11" title="Scholastic Reading Inventory"/>
				   		</a>
				    
				    
				
			</td>
			
				<td style="padding-left:16px;padding-right:16px">
				<img src="/slms/images/gateway_assets/vrule.png" style="align=center"/>
				</td>
			


   		
			<td align="center" style="padding-right:21px;padding-left:21px">
				
				    
				   		<a href="javascript:openpopup('/src/loader/','Scholastic Reading Counts')"
				   			onmousedown="document.images.item12.src='/slms/images/gateway_assets/btnSM_src_dn.png';"
				   			onmouseup="document.images.item12.src='/slms/images/gateway_assets/btnSM_src.png'"
				   			onmouseout="document.images.item12.src='/slms/images/gateway_assets/btnSM_src.png'">
				    			<IMG SRC="/slms/images/gateway_assets/btnSM_src.png" BORDER="0" ID="item12" title="Scholastic Reading Counts"/>
				   		</a>
				    
				    
				
			</td>
			
				<td style="padding-left:16px;padding-right:16px">
				<img src="/slms/images/gateway_assets/vrule.png" style="align=center"/>
				</td>
			


   		
			<td align="center" style="padding-right:21px;padding-left:21px">
				
				    
				   		<a href="javascript:openpopup('/slms/../spi/loader/','Scholastic Phonics Inventory')"
				   			onmousedown="document.images.item13.src='/slms/images/gateway_assets/btnSM_spi_dn.png';"
				   			onmouseup="document.images.item13.src='/slms/images/gateway_assets/btnSM_spi.png'"
				   			onmouseout="document.images.item13.src='/slms/images/gateway_assets/btnSM_spi.png'">
				    			<IMG SRC="/slms/images/gateway_assets/btnSM_spi.png" BORDER="0" ID="item13" title="Scholastic Phonics Inventory"/>
				   		</a>
				    
				    
				
			</td>
			
				<td style="padding-left:16px;padding-right:16px">
				<img src="/slms/images/gateway_assets/vrule.png" style="align=center"/>
				</td>
			


   		
			<td align="center" style="padding-right:21px;padding-left:21px">
				
				    
				   		<a href="javascript:openpopup('/smi/loader/index.html','Scholastic Math Inventory')"
				   			onmousedown="document.images.item14.src='/slms/images/gateway_assets/btnSM_smi_dn.png';"
				   			onmouseup="document.images.item14.src='/slms/images/gateway_assets/btnSM_smi.png'"
				   			onmouseout="document.images.item14.src='/slms/images/gateway_assets/btnSM_smi.png'">
				    			<IMG SRC="/slms/images/gateway_assets/btnSM_smi.png" BORDER="0" ID="item14" title="Scholastic Math Inventory"/>
				   		</a>
				    
				    
				
			</td>
			


   		
   	</tr>
   	</table>
   	</td></tr>
   	<tr><td align="center">
   	<table border="0" cellspacing="0" cellpadding="0">
	   	<tr>
		   	<td align="center" style="padding-bottom:20px"></td>
	   	</tr>
		<tr>
			<td align="center">
				<style type="text/css">

p.copyright
{
   font-size: 10px;
   font-family:Arial,san-serif;
   color: #000000;
}

</style>

<p class="copyright">TM &reg; & &copy; 2013&ndash;1999 Scholastic Inc. All Rights Reserved.</p>
			</td>
		</tr>
	</table>
	</td></tr>
</table>
		</div>
		</div>
	</form>
  </body>
</html>
