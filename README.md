# PISTAR
My first custom development board. I plan to made it as a part of my drone project

## 3D View
Front

<img width="402" height="681" alt="Screenshot 2026-03-21 at 07 20 37" src="https://github.com/user-attachments/assets/c149c8dd-8666-4ec8-8852-5e56782cb66d" />


Back

<img width="94" height="190" alt="Screenshot 2026-03-21 at 18 49 06" src="https://github.com/user-attachments/assets/3aa22ce2-fa49-4865-a6a3-126af7fe582c" />


## PCB
My PCB is made in KiCad These are the footprints I used
- Capacitor_SMD:C_0603_1608Metric
- Capacitor_SMD:C_0402_1005Metric
- LED_SMD:LED_WS2812B_PLCC4_5.0x5.0mm_P3.2mm
- Connector_USB:USB_C_Receptacle_HRO_TYPE-C-31-M-12
- Connector_PinHeader_2.54mm:PinHeader_1x20_P2.54mm_Vertical
- Connector_PinHeader_2.54mm:PinHeader_1x03_P2.54mm_Vertical
- Resistor_SMD:R_0402_1005Metric
- Button_Switch_SMD:SW_Push_SPST_NO_Alps_SKRK
- RP2040: Package_DFN_QFN:QFN-56-1EP_7x7mm_P0.4mm_EP3.2x3.2mm
- W25Q128JVS: Package_SON:Winbond_USON-8-1EP_3x2mm_P0.5mm_EP0.2x1.6mm
- Package_TO_SOT_SMD:SOT-23
- Crystal:Crystal_SMD_3225-4Pin_3.2x2.5mm_HandSoldering

Here is my schematic:

<img width="740" height="520" alt="Screenshot 2026-03-21 at 07 23 57" src="https://github.com/user-attachments/assets/dd6c55b7-b2c1-4f94-aba5-e601bf29cad8" />


and my PCB:

<img width="320" height="620" alt="Screenshot 2026-03-21 at 07 24 26" src="https://github.com/user-attachments/assets/0f77e4ee-6894-46e9-b853-8eae447484ab" />


## BOM

| Name                | Purpose                               | Cost Per Item (USD) | Quantity | Total (USD) | Link | Distributor |
|---------------------|----------------------------------------|----------------------|----------|--------------|------|-------------|
| UPS Shipping        | Shipping the JLCPCB                   | 2.48                 | 1        | 2.48         | [Link](https://cart.jlcpcb.com/shopcart/cart) | JLCPCB |
| Pin Header Delivery | Delivering the pin header             | 0.83                 | 1        | 0.83         | [Link](https://www.tokopedia.com/cart/checkout?t_id=1774050616052&t_st=3&t_pp=cart&t_efo=cart&t_ef=goods_search&t_sm=&t_spt=cart) | Tokopedia |
| Pin Header 1x40 2x  | For the GPIO pins                     | 0.11                 | 1        | 0.11         | [Link](https://www.tokopedia.com/parts-shop/pin-header-male-1-x-40-pin-254mm-single-row?extParam=ivf%3Dfalse%26keyword%3Dpin+header%26search_id%3D2026032023494534ED066DF378EF117KRL%26src%3Dsearch&t_id=1774050616052&t_st=1&t_pp=search_result&t_efo=search_pure_goods_card&t_ef=goods_search&t_sm=&t_spt=search_result) | Tokopedia |
| PCB / PCBA          | PCB printing and component assembly   | 78.06                | 1        | 78.06        | [Link](https://cart.jlcpcb.com/shopcart/cart) | JLCPCB |

## Additional Thingy
Thankyou for HackClub and  KiCad for making this project possible
