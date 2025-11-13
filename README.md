# Zynq-7020-UART-to-1553B-to-Aurora-Data-Pipeline
本项目在Xilinx Zynq-7020 FPGA上实现了一个完整的数据通路系统：PC通过CH340串口芯片发送数据，经UART接收、1553B协议处理、8B/10B编码后，通过自实现的Aurora协议以高速串行方式输出。
