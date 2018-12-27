# spectrometer
based on ad9959 and display in stm32f429  oscilloscope

四川师范大学计算机科学学院2018届毕业生毕业设计《基于STM32/AD9959的频谱/幅频特性测试仪的研究与设计》

**Abstract**：

  The multi-function measuring instrument designed in this paper mainly has two functions: the display of high-frequency signal spectrum and display of the amplitude-frequency curve in a circuit.
  
  In a high-frequency signal, its’ information is mainly reflected in the frequency domain, so it is important to analysis a particular signal in spectrum. In order to select an appropriate solution in industry, spectrum analyzer can be used to obtain the proportion of each frequency component or noise component of a signal in real time.  This design implements an analog scanning heterodyne spectrum analyzer, which is mainly based on a stm32-controlled DDS (direct frequency synthesizer)—the AD9959 is a vibration source-based frequency sweeper. After matching the impedance between the measured signal and sweep signal, it is mixed by the multiplier AD835 and sent to the bandpass filtering, after feedback gain and detection processing, the processed signal is input to oscilloscope which performs an scan model of XY to obtain a spectrum of original signal.
  
  The amplitude-frequency curve is an important curve in a circuit network, through which we can obtain its working frequency range. It is also similar to the phase-frequency curve. The network analyzer can obtain the amplitude-frequency characteristic and phase-frequency characteristic curve of the network by inputting the frequency sweep signal, that is, the Bode diagram. The main aim of this design is to get the amplitude-frequency curve of a given network, the measured network is programmable filter based on max262, which controller is stm32f103c8t6.

**Key words**: Multi-function measuring instrument  Direct frequency digital synthesizer  Frequency spectrum  Amplitude frequency characteristic curve  Oscilloscope  XY scan

##  some pics
![](https://github.com/xdr940/spectrometer/raw/master/pics/overview.jpg)
![](https://github.com/xdr940/spectrometer/raw/master/pics/overview2.jpg)
![](https://github.com/xdr940/spectrometer/raw/master/pics/programmable_filter_and_its_controllor.jpg)
![](https://github.com/xdr940/spectrometer/raw/master/pics/pic2.png)
![](https://github.com/xdr940/spectrometer/raw/master/pics/pic3.png)
![](https://github.com/xdr940/spectrometer/raw/master/pics/pic6.png)
![](https://github.com/xdr940/spectrometer/raw/master/pics/pic8.png)


射频模块资源

vca821：链接： https://pan.baidu.com/s/1wADx1TkH376WdBm3dHEpcQ  
提取码：m1oc 
ad637：链接： https://pan.baidu.com/s/1-tXFXszYEmewGh8tx90AgA  
提取码：zwa3 
ad8367：链接： https://pan.baidu.com/s/1pRKGAxD8JTbfN1X19uOJhg  
提取码：hzaf 
ad835：链接： https://pan.baidu.com/s/131-jncVA0o0PrxdgvLrUzA  
提取码：8sym 
5430：链接： https://pan.baidu.com/s/1FaLzc5xipcgazgWVWtmltg  
提取码：d6yq 

