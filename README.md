Usage:

Add a <textarea><div /> </textarea>with params in your QWEB template where you want to inert the barcode.

Example:
<textarea>
<div class="dd_barcode" t-att-dd_value="o.name" 
    dd_type="code128" dd_output="css" 
    dd_showHRI="false" dd_barWidth="2"
    dd_fontSize="18" dd_barHeight="60"/>
</textarea>
