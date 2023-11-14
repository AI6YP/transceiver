
AT86RF215


GW2AR-LV18-QN88C8/I7

IOB14A
IOB14B

IOB6A
IOB6B

IOB8A
IOB8B

IOL47A/LPLL2_T_fb
IOL47B/LPLL2_C_fb

IOL49A
IOL49B

IOL51A
IOL51B

https://github.com/cariboulabs/cariboulite/tree/main/firmware

https://github.com/maribu/at86rf215-breakout



1   PIN73_HSPI_DIN2         IOT40A
2   PIN74_HSPI_DIN3         IOT34B
3   PIN75_HSPI_DIR          IOT34A                  SPI_DIR 
4   PIN85_SDIO_D1           IOT4B                               SDIO_D1
5   PIN77_LCD_CK            IOT30A/GCLKT_1                                  LCD_CK
6   PIN15_SYS_LED0          IOL47A/LPLL2_T_fb       LED0
7   PIN16_SYS_LED1          IOL47B/LPLL2_C_fb       LED1
8   PIN27_LCD_B7            IOB8A                                           LCD_B7
9   PIN28_LCD_B6            IOB8B                                           LCD_B6
10  PIN25_LCD_HS            IOB6A                   DVI_CEC
11  PIN26_LCD_VS            IOB6B                   DVI                     LCD_VS
12  PIN29_LCD_B5            IOB14A                                          LCD_B5
13  PIN30_LCD_B4            IOR14B                                          LCD_B4
14  PIN31_LCD_B3            IOB18A                                          LCD_B3
15  PIN17_SYS_LED2          IOL49A                  LED2                    LCD_INIT3
16  PIN20_SYS_LED5          IOL51B                  LED5                    LCD_INIT2
17  PIN19_SYS_LED4          IOL51A                  LED4                    LCD_INIT1
18  PIN18_SYS_LED3          IOL49B                  LED3                    LCD_INIT0
19  +3V3
20  GND

1   +5V
2   GND
3   PIN76_HSPI_DAT          IOT30B/GCLKC_1          SPI_DAT
4   PIN80_SDIO_D2           IOT27A/GCLKT_0                      SDIO_D2
5   PIN42_LCD_R3            IOB42B                                          LCD_R3
6   PIN41_LCD_R4            IOB43A                                          LCD_R4
7   PIN56_I2S_BCLK          IOR36A/SO/D1                                                I2S_BCLK
8   PIN54_I2S_DIN           IOR38A/DIN/CLKHOLD_N                                        I2S_DIN     
9   PIN51_PA_~{SD}/EN       IOR45A/RPLL2_T_in                                           PA_~{SD}/EN
10  PIN48_LCD_DE            IOR49B                                          LCD_DE
11  PIN55_I2S_LRCK          IOR36B/SSPI_CS_N/D0                                         I2S_LRCK
12  PIN49_LCD_BL            IOR49A                                                                  DSI_LCD_BL BACKLIGHT
13  PIN86_HSPI_CSN          IOT4A                   SPI_~{CS}
14  PIN79_WS2812            IOT27B/GCLKC_0                                                          WS2812     
15  GND
16  +3V3
17  PIN72_HSPI_DIN1         IOT40B      
18  PIN71_HSPI_DIN0         IOT44A
19  PIN53_EDID_CLK          IOR38B/DOUT/WE_N                                DDC_CLK
20  PIN52_EDID_DAT          IOR39A/SCLK                                     DCD_DAT

