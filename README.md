# mini-synth

A synth but you can only play frequencies received from light, humidity, and temperature sensors.

Schematic:

two of the buttons are upside down for easier routing :P

<img width="1289" height="902" alt="image" src="https://github.com/user-attachments/assets/fa6adade-36ce-4f0f-9f5e-d8ee88afce7f" />


PCB:

<img width="757" height="787" alt="image" src="https://github.com/user-attachments/assets/411b4998-4171-4325-8d9c-887c3c178661" />

3D View:

<img width="757" height="787" alt="image" src="https://github.com/user-attachments/assets/930adf40-978c-4325-98fa-a25e4d38cffc" />

BOM:

|Id|Designator|Footprint|Quantity|Designation|Supplier and ref|
|-|-|-|-|-|-|
|1|U4|QFN-20-1EP_4x4mm_P0.5mm_EP2.7x2.7mm|1|MCP23008-xML|https://www.lcsc.com/product-detail/C144211.html?spm=wm.gwc.xh.4.tp___wm.sxq.ssl.gwc&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1ZfUF1TR1BYVDsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhADEA4cHktQQlBADxALGw%3D%3D|
|2|C10|C_0402_1005Metric|1|2.2uF|https://www.lcsc.com/product-detail/C170151.html?s_z=n_q_t_capacitor%25200402&spm=wm.fly.bg.0.xh___wm.ssy.tc.0.tz&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1laVVVURlVcXjsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhYS|
|3|SW3|RotaryEncoder_Alps_EC12E-Switch_Vertical_H20mm|1|volume|https://www.lcsc.com/product-detail/C255515.html?s_z=n_q_t_ec12e&spm=wm.fly.bg.3.stp___wm.ssy.tc.0.tz&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1laVFdVQ1BcVTsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhADEA4cHktQR1BADxALGw%3D%3D|
|4|J4|PinHeader_1x04_P2.54mm_Vertical|1|weaker pins|no part|
|5|"C31|C32|C17|C3|C2|C4|C13|C18|C1|C19|C16|C6"|C_0402_1005Metric|12|100nF|https://www.lcsc.com/product-detail/C60474.html?s_z=n_q_t_capacitor%25200402&spm=wm.fly.bg.0.xh___wm.ssy.tc.0.tz&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1laVVVURlVcXjsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhYS|
|6|"R19|R5|R11|R8|R6"|R_0402_1005Metric|5|10K|https://www.lcsc.com/product-detail/C60490.html?s_z=n_q_t_resistor%25200402&spm=wm.fly.bg.0.xh___wm.ssy.tc.0.tz&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1laVFFRTlRWUDsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhADEA4cHktXRlVcSQwSGg0%3D|
|7|"C8|C9|C7"|C_0402_1005Metric|3|1uF|https://www.lcsc.com/product-detail/C87145.html?s_z=n_q_t_capacitor%25200402&spm=wm.fly.bg.0.xh___wm.ssy.tc.0.tz&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1laVVVURlVcXjsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhYS|
|8|"REF**|REF**|REF**"|capacitive touch button 10mm|3|capacitive touch button 10mm|no part|
|9|R21|SW-TH_PRS11R-415F-S103B1|1|20K|https://www.lcsc.com/product-detail/C17371045.html?spm=wm.gwc.xh.9.cbm___wm.sxq.ssl.gwc&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1ZfUF1TR1BYVDsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhADEA4cHktQQlBADxALGw%3D%3D|
|10|R1|R_LDR_5.1x4.3mm_P3.4mm_Vertical|1|R_Photo|https://www.lcsc.com/product-detail/C125630.html?spm=wm.gwc.xh.10.cbm___wm.sxq.ssl.gwc&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1ZfUF1TR1BYVDsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhADEA4cHktQQlBADxALGw%3D%3D|
|11|U7|WQFN-16-1EP_3x3mm_P0.5mm_EP1.6x1.6mm_ThermalVias|1|TPA6132A2RTE|https://www.lcsc.com/product-detail/C69901.html?s_z=n_q_TPA6132A2RTE&spm=wm.fly.bg.0.xh&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1hcUFRSTlNfUjsOAxUeFF5JWBYZEEoKFBINSQcJGk4eFQsCAgIaSgADAwAHC0slQlRfV1xfR1RADxALGw%3D%3D|
|12|SW2|RotaryEncoder_Alps_EC12E-Switch_Vertical_H20mm|1|pitch|https://www.lcsc.com/product-detail/C255515.html?s_z=n_q_t_ec12e&spm=wm.fly.bg.3.stp___wm.ssy.tc.0.tz&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1laVFdVQ1BcVTsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhADEA4cHktQR1BADxALGw%3D%3D|
|13|SW14|SW-TH_RKJXL100401V|1|SW_Rotary_1x8_MP|https://www.lcsc.com/product-detail/C160838.html?spm=wm.gwc.xh.3.tp___wm.sxq.ssl.gwc&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1ZfUF1TR1BYVDsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhADEA4cHktQQlBADxALGw%3D%3D|
|14|"C11|C12|C5"|C_0402_1005Metric|3|4.7uF|https://www.lcsc.com/product-detail/C368809.html?s_z=n_q_t_capacitor%25200402&spm=wm.fly.bg.2.xh___wm.ssy.tc.0.tz&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1laVVVURlVcXjsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhYS|
|15|C25|C_0402_1005Metric|1|4.7uF|https://www.lcsc.com/product-detail/C368809.html?s_z=n_q_t_capacitor%25200402&spm=wm.fly.bg.2.xh___wm.ssy.tc.0.tz&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1laVVVURlVcXjsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhYS|
|16|SW7|SW-SMD_L6.1-W3.7-LS8.0-1|1|BOOT|https://www.lcsc.com/product-detail/C49234126.html?spm=wm.gwc.xh.0.tp___wm.sxq.ssl.gwc&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1ZfUF1TR1BYVDsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhADEA4cHktQQlBADxALGw%3D%3D|
|17|"R13|R12|R9|R7"|R_0402_1005Metric|4|15K|https://www.lcsc.com/product-detail/C2909322.html?s_z=n_q_t_resistor%25200402&spm=wm.fly.bg.0.stp___wm.ssy.tc.0.tz&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1laVFFRTlRWUDsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhADEA4cHktXRlVcSQwSGg0%3D|
|18|"D8|D3|D1|D5|D4|D7|D6|D2"|LED-SMD_4P-L3.2-W2.8-LS5.9_SK6812MINI-E|8|SK6812|https://www.lcsc.com/product-detail/C5149201.html?s_z=n_q_l_SK6812%2520mini%2520e&spm=wm.fly.bg.9.stp___wm.ssy.ml.0-0.ent&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1hcUV1XQ1ZdUzsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhADEA4cHktSR1dADxALGw%3D%3D|
|19|U6|TSSOP-14_L5.0-W4.4-P0.65-LS6.4-BL|1|"74HCT125PW|118"|https://www.lcsc.com/product-detail/C131316.html?spm=wm.gwc.xh.10.cbm___wm.sxq.ssl.gwc&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1hcUVNRQVZYUTsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhYS|
|20|J1|USB-C-SMD_G-SWITCH_GT-USB-7010ASV|1|USB_C_Receptacle_USB2.0_14P|https://www.lcsc.com/product-detail/C2988369.html?spm=wm.gwc.xh.2.cbm___wm.sxq.ssl.gwc&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1ZfUF1TR1BYVDsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhADEA4cHktQQlBADxALGw%3D%3D|
|21|SW1|KEY-TH_L12.0-W3.3-P5.00|1|reset|https://www.lcsc.com/product-detail/C2888728.html?spm=wm.gwc.xh.8.tp___wm.sxq.ssl.gwc&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1ZfUF1TR1BYVDsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhADEA4cHktQQlBADxALGw%3D%3D|
|22|R20|R_0402_1005Metric|1|330|https://www.lcsc.com/product-detail/C105875.html?s_z=n_q_t_resistor%25200402&spm=wm.fly.bg.0.xh___wm.ssy.tc.0.tz&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1laVFFRTlRWUDsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhADEA4cHktXRlVcSQwSGg0%3D|
|23|"D10|D16|D9|D11|D14|D12|D13|D17|D15"|D_0402_1005Metric|9|D|https://www.lcsc.com/product-detail/C28646371.html?s_z=n_q_t_diode&spm=wm.fly.bg.0.stp___wm.ssy.tc.1.tz&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1hcX1NVT1ldXjsOAxUeFF5JWBYZEEoKFBINSQcJGk4eFQsCAgIaSgADAwAHC0slRlVeUFxUWQkaCgg%3D|
|24|R22|R_0402_1005Metric|1|1K|https://www.lcsc.com/product-detail/C106235.html?s_z=n_q_t_resistor%25200402&spm=wm.fly.bg.0.xh___wm.ssy.tc.0.tz&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1laVFFRTlRWUDsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhADEA4cHktXRlVcSQwSGg0%3D|
|25|SW9|SW-TH_XKB5858-Z-E|1|loop 2|https://www.lcsc.com/product-detail/C780038.html?spm=wm.gwc.xh.7.cbm___wm.sxq.ssl.gwc&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1ZfUF1TR1BYVDsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhADEA4cHktQQlBADxALGw%3D%3D|
|26|CN1|AUDIO-TH_HOOYA_PJ-320|1|trs headphone jack|https://www.lcsc.com/product-detail/C2939180.html?s_z=n_q_C2939180&globalKeyword=C2939180|
|27|U5|LQFP-48_7x7mm_P0.5mm|1|CH32V203C8T6|https://www.lcsc.com/product-detail/C3001172.html?spm=wm.gwc.xh.11.cbm___wm.sxq.ssl.gwc&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1hcUVNRQVZYUTsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhYS|
|28|"C30|C29"|C_0402_1005Metric|2|10uF|https://www.lcsc.com/product-detail/C315248.html?s_z=n_q_t_capacitor%25200402&spm=wm.fly.bg.0.xh___wm.ssy.tc.0.tz&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1laVVVURlVcXjsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhYS|
|29|C23|C_0402_1005Metric|1|10uF|https://www.lcsc.com/product-detail/C315248.html?s_z=n_q_t_capacitor%25200402&spm=wm.fly.bg.0.xh___wm.ssy.tc.0.tz&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1laVVVURlVcXjsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhYS|
|30|U2|Sensirion_DFN-4_1.5x1.5mm_P0.8mm_SHT4x_NoCentralPad|1|SHT4x|https://www.lcsc.com/product-detail/C55108905.html?s_z=n_q_t_sht4&spm=wm.fly.bg.0.xh___wm.ssy.tc.0.tz&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1hcUVdfRVdZUDsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhADEA4cHktQR1RADxALGw%3D%3D|
|31|"C24|C21"|C_0402_1005Metric|2|560pF|https://www.lcsc.com/product-detail/C315248.html?s_z=n_q_t_capacitor%25200402&spm=wm.fly.bg.0.xh___wm.ssy.tc.0.tz&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1laVVVURlVcXjsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhYS|
|32|"C14|C15"|C_0402_1005Metric|2|47uf|https://www.lcsc.com/product-detail/C140782.html?s_z=n_q_t_47%2520uF%2520capacitor&spm=wm.fly.bg.5.xh___wm.ssy.tc.0.tz&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1hcUFJXQ1VfUDsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhADEA4cHktXRlVeSQwSGg0%3D|
|33|"R16|R15"|R_0402_1005Metric|2|27|https://www.lcsc.com/product-detail/C2100055.html?s_z=n_q_t_resistor%25200402&spm=wm.fly.bg.0.xh___wm.ssy.tc.0.tz&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1laVFFRTlRWUDsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhADEA4cHktXRlVcSQwSGg0%3D|
|34|U3|SOT-23|1|MCP1700x-330xxTT|https://www.lcsc.com/product-detail/C144211.html?spm=wm.gwc.xh.4.cbm___wm.fly.ssl.gwc&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1hcUVdWTlZWVTsOAxUeFF5JWBYZEEoKFBINSQcJGk4eFQsCAgIaSgADAwAHC0slT1VXUVdIHxUDCw%3D%3D|
|35|SW10|SW-TH_XKB5858-Z-E|1|record|https://www.lcsc.com/product-detail/C780038.html?spm=wm.gwc.xh.7.cbm___wm.sxq.ssl.gwc&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1ZfUF1TR1BYVDsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhADEA4cHktQQlBADxALGw%3D%3D|
|36|"R4|R18|R17"|R_0402_1005Metric|3|4.7K|https://www.lcsc.com/product-detail/C105871.html?s_z=n_q_t_resistor%25200402&spm=wm.fly.bg.0.xh___wm.ssy.tc.0.tz&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1laVFFRTlRWUDsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhADEA4cHktXRlVcSQwSGg0%3D|
|37|SW12|KEY-TH_L12.0-W3.3-P5.00|1|free1|https://www.lcsc.com/product-detail/C2888728.html?spm=wm.gwc.xh.8.tp___wm.sxq.ssl.gwc&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1ZfUF1TR1BYVDsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhADEA4cHktQQlBADxALGw%3D%3D|
|38|SW11|KEY-TH_L12.0-W3.3-P5.00|1|delay|https://www.lcsc.com/product-detail/C2888728.html?spm=wm.gwc.xh.8.tp___wm.sxq.ssl.gwc&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1ZfUF1TR1BYVDsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhADEA4cHktQQlBADxALGw%3D%3D|
|39|"R3|R2"|R_0402_1005Metric|2|5.1K|https://www.lcsc.com/product-detail/C105872.html?s_z=n_q_t_resistor%25200402&spm=wm.fly.bg.0.xh___wm.ssy.tc.0.tz&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1laVFFRTlRWUDsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhADEA4cHktXRlVcSQwSGg0%3D|
|40|SW13|KEY-TH_L12.0-W3.3-P5.00|1|free2|https://www.lcsc.com/product-detail/C2888728.html?spm=wm.gwc.xh.8.tp___wm.sxq.ssl.gwc&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1ZfUF1TR1BYVDsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhADEA4cHktQQlBADxALGw%3D%3D|
|41|R14|R_0402_1005Metric|1|100K|https://www.lcsc.com/product-detail/C60491.html?s_z=n_q_t_resistor%25200402&spm=wm.fly.bg.0.xh___wm.ssy.tc.0.tz&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1laVFFRTlRWUDsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhADEA4cHktXRlVcSQwSGg0%3D|
|42|"FB2|FB1"|L0402|2|FerriteBead_Small|https://www.lcsc.com/product-detail/C17701320.html?spm=wm.gwc.xh.5.tp___wm.sxq.ssl.gwc&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1ZfUF1TR1BYVDsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhADEA4cHktQQlBADxALGw%3D%3D|
|43|C22|C_0402_1005Metric|1|10nF|https://www.lcsc.com/product-detail/C15195.html?s_z=n_q_t_capacitor%25200402&spm=wm.fly.bg.0.stp___wm.ssy.tc.0.tz&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1laVVVURlVcXjsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhYS|
|44|U1|DIP-16_W7.62mm|1|PT2399|https://www.lcsc.com/product-detail/C84963.html?s_z=n_q_x_pt2399&spm=wm.ssy.em.0.tz&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1hcUVZSQFlfVDsOAxUeFF5JWBYZEEoKFBINSQcJGk4eFQsCAgIaSgADAwAHC0slRVheUFRWT08GEwkK|
|45|"C20|C26"|C_0402_1005Metric|2|5.6nF|https://www.lcsc.com/product-detail/C281760.html?s_z=n_q_t_capacitor%25200402&spm=wm.fly.bg.0.xh___wm.ssy.tc.0.tz&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1laVVVURlVcXjsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhYS|
|46|J2|PinHeader_1x02_P2.54mm_Vertical|1|analog|no part|
|47|SW8|SW-SMD_L6.1-W3.7-LS8.0-1|1|RESET|https://www.lcsc.com/product-detail/C49234126.html?spm=wm.gwc.xh.0.tp___wm.sxq.ssl.gwc&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1ZfUF1TR1BYVDsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhADEA4cHktQQlBADxALGw%3D%3D|
|48|"C28|C27"|C_0402_1005Metric|2|12pF|https://www.lcsc.com/product-detail/C26406.html?s_z=n_q_t_capacitor%25200402&spm=wm.fly.bg.0.xh___wm.ssy.tc.0.tz&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1laVVVURlVcXjsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhYS|
|49|Y1|CRYSTAL-SMD_4P-L3.2-W2.5-BL|1|8MHz|https://www.lcsc.com/product-detail/C2682775.html?spm=wm.gwc.xh.1.cbm___wm.sxq.ssl.gwc&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1ZfUF1TR1BYVDsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhADEA4cHktQQlBADxALGw%3D%3D|
|50|SW4|SW-SMD_L6.1-W3.7-LS8.0-1|1|reset2|https://www.lcsc.com/product-detail/C49234126.html?spm=wm.gwc.xh.0.tp___wm.sxq.ssl.gwc&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1ZfUF1TR1BYVDsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhADEA4cHktQQlBADxALGw%3D%3D|
|51|R10|R_0603_1608Metric|1|2.7K|https://www.lcsc.com/product-detail/C2907008.html?s_z=n_q_t_resistor%25200603%25202.7k&spm=wm.fly.bg.0.xh___wm.ssy.tc.0.tz&lcsc_vid=FVhWX1RURVBYAgACFQRfXlEDQ1RbBFYDRQNYU1ZfRgQxVlNeT1hcUVZWT1haVjsOAxUeFF5JWBYZEEoKFBINSQcJGk4NBhADEA4cHktXRlhXSQwSGg0%3D|
|52|J3|PinHeader_1x04_P2.54mm_Vertical|1|debug header|no part|
