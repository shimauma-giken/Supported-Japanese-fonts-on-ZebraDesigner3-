# Supported Japanese fonts on ZebraDesigner3 
 ZebraDesigner3でサポートされているフォント一覧


| SKU | File Name | Font Name | Description |
| --- | --- | --- | --- |
| 56068-001 | ANMDJ.TTF | Zebra Andale J | JA Scaleble Gothic font |
| 77840* | GOTHIC24.FNT | Zebra Japanese Gothic | JA Bitmap Gothic font for 203dpi |
| 77840* | MINCHO24.FNT | Zebra Japanese Mincho | JA Bitmap Mincho font for 203dpi |
| 77841* | GOTHIC35.FNT | Zebra Japanese Gothic | JA Bitmap Gothic font for 300dpi |
| 77841* | MINCHO35.FNT | Zebra Japanese Mincho | JA Bitmap Mincho font for 300dpi |
| 77848**** | GOTHIC.FNT | Cannot use on ZD3 | JA Scalable HGP Gothic font - Provided by floppy disk |
| Not for sales** | SGMTJ.TTF | Zebra MS Gothic | JA Scaleble Gothic font |
| Not for sales** | NOTOMRJ.TTF | Noto Sans | JA Scaleble Gothic font |
| Not for sales*** | TT0003M.TTF | Swiss Fonts | EMEA Scalable font - Non-Japanese |

\* Cannot install to singles printer simultainiously. Latest installed font is valid.  
\** Pre-installed to Link-OS Zebra mobile printers. 
\*** Pre-installed to Link-OS printers. 
\**** Unsupported on ZebraDesigner 3

------
# Sampels Codes to print Japanese fonts / ZPL 
^XA
^FT39,105^A@N,21,21,ANMDJ.TTF^FH\^CI28^FDZ Andale J^FS^CI27
^FPH,1^FT39,171^AJN,50,50^FH\^CI28^FDZ Ja Gothic^FS^CI27
^FPH,1^FT42,239^AJN,50,50^FH\^CI28^FDZ Ja  Mincho^FS^CI27
^FPH,1^FT49,329^A@N,50,50,SGMTJ.TTF^FH\^CI28^FDZ MS Gothic^FS^CI27
^FPH,1^FT49,418^A@N,50,50,NOTOMRJ.TTF^FH\^CI28^FDZ Noto Sans^FS^CI27
^FPH,1^FT42,562^A@N,50,49,TT0003M_^FH\^CI28^FDZ Swiss Fonts^FS^CI27
^XZ



kaigyou


