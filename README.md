# Supported Japanese fonts on ZebraDesigner3 
 ZebraDesigner3でサポートされているフォント一覧リスト


| SKU | File Name | Font Name | Description |
| --- | --- | --- | --- |
| 56068-001 | ANMDJ.TTF | Zebra Andale J | JA Scaleble Gothic font |
| 77840* | GOTHIC24.FNT | Zebra Japanese Gothic | JA Bitmap Gothic font for 203dpi |
| 77840* | MINCHO24.FNT | Zebra Japanese Mincho | JA Bitmap Mincho font for 203dpi |
| 77841* | GOTHIC35.FNT | Zebra Japanese Gothic | JA Bitmap Gothic font for 300dpi |
| 77841* | MINCHO35.FNT | Zebra Japanese Mincho | JA Bitmap Mincho font for 300dpi |
| 77848**** | GOTHIC.FNT | Cannot use on ZD3 | JA Scalable HGP Gothic font - Provided by floppy disk |
| Downloadable** | SGMTJ.TTF | Zebra MS Gothic | JA Scaleble Gothic font |
| Downloadable** | NOTOMRJ.TTF | Noto Sans | JA Scaleble Gothic font |
| Downloadable** | TT0003M.TTF | Swiss Fonts | EMEA Scalable font - Non-Japanese |

<pre>
\* Cannot install to old printers simultainiously. Latest installed font is valid.    
\** Pre-installed to mobile printer.  
    Download Link https://www.zebra.com/us/en/support-downloads/printer-software/printer-fonts.html   
\*** Pre-installed to Link-OS printers.   　
    Download Link https://www.zebra.com/us/en/support-downloads/printer-software/printer-fonts.html  
\**** Unsupported on ZebraDesigner 3  
</pre>

------  
# Sampels Codes to print Japanese fonts / ZPL   

<pre>
^XA   
^FT39,105^A@N,21,21,ANMDJ.TTF^FH\^CI28^FDZ Andale J^FS^CI27  
^FPH,1^FT39,171^AJN,50,50^FH\^CI28^FDZ Ja Gothic^FS^CI27  
^FPH,1^FT42,239^AJN,50,50^FH\^CI28^FDZ Ja  Mincho^FS^CI27  
^FPH,1^FT49,329^A@N,50,50,SGMTJ.TTF^FH\^CI28^FDZ MS Gothic^FS^CI27  
^FPH,1^FT49,418^A@N,50,50,NOTOMRJ.TTF^FH\^CI28^FDZ Noto Sans^FS^CI27  
^FPH,1^FT42,562^A@N,50,49,TT0003M_^FH\^CI28^FDZ Swiss Fonts^FS^CI27  
^XZ  
</pre>


------

# 免責事項   

以下の内容について一切その責任を負いません。あらかじめご了承ください。   
  
1. 本ファイルは利用者の責任において本規約に基づき利用されるものとし、情報配信元は本規約に明示的に定められている場合を除き、本ファイルの利用について責任を負いません。   
2. 情報配信元は提供する本ファイルが正常に作動することおよび将来にわたり正常に作動すること、ならびに、本ファイルが全てのプリンタや運用環境において利用できることを保証しません。   
3. 本ファイルが正常に作動しないことおよび本ファイルが利用できないことによりお客様が損害を被った場合、情報配信元は当該損害に関して一切責任を負いません。   
5. 利用者の本ファイルの利用にあたり、運用データが破壊、消失または変更された場合、情報配信元は一切責任を負いません。   
7. 情報配信元は、利用者が本ファイルを通じて得た情報等につき、その正確性および特定の目的への適合性等について、いかなる保証もしません。   
7. 情報配信元は、利用者が他の利用者あるいは第三者との間に本ファイルを通じて提供された情報によって生じた権利侵害等の紛争に関して一切責任を負いません。   




