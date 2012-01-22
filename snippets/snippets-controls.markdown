##Controls


**Switch Controls: On State:**

    <switchcontrol class="on" id="switch_01" ui-value="Value Here">
        <label ui-implements="on">ON</label>
        <thumb><thumbprop></thumbprop></thumb>
        <label ui-implements="off">OFF</label>
    </switchcontrol>
    
    
    <switchcontrol class="on" id="switch_02" ui-value="Value Here!" ui-implements="attention">
        <label ui-implements="on">ON</label>
        <thumb><thumbprop></thumbprop></thumb>
        <label ui-implements="off">OFF</label>
    </switchcontrol>


**Switch Controls: Off State:**

    <switchcontrol class="off" id="switch_03" ui-value="Value Here!">
        <label ui-implements="on">ON</label>
        <thumb><thumbprop></thumbprop></thumb>
        <label ui-implements="off">OFF</label>
    </switchcontrol>
    
    
    <switchcontrol class="off" id="switch_04" ui-value="Value Here!" ui-implements="attention">
        <label ui-implements="on">ON</label>
        <thumb><thumbprop></thumbprop></thumb>
        <label ui-implements="off">OFF</label>
    </switchcontrol>



**Sliders:**

    <slider id="slider_01" style="width: 255px;">
        <thumb><thumbprop></thumbprop></thumb>
    </slider>
    
    <slider id="slider_02" style="width: 255px;" class="media-player">
        <thumb><thumbprop></thumbprop></thumb>
    </slider>

**Tab Bar**

    <tabbar ui-selected-tab="0">
        <uibutton implements="tab" class="selected">
            <icon style="-webkit-mask-box-image: url(icons/refresh.svg);"></icon>
            <label>Refresh</label>
        </uibutton>
        <uibutton implements="tab">                
            <icon style="-webkit-mask-box-image: url(icons/add.svg);"></icon>
            <label>Add</label>                
        </uibutton>
        <uibutton implements="tab">                
            <icon style="-webkit-mask-box-image: url(icons/info.svg);"></icon>
            <label>Info</label>                
        </uibutton>
        <uibutton implements="tab">                
            <icon style="-webkit-mask-box-image: url(icons/downloads.svg);"></icon>
            <label>Downloads</label>                
        </uibutton>
    </tabbar>