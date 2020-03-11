# imxrt-tool-flash-algo
Build tool (IAR, Keil, J-Link) flash algo for i.MXRT | 收集i.MXRT主流开发工具的flash算法源工程

> * IAR EWARM v8.40.2  
> * Keil MDK v5.27  
> * J-Link v6.52e  
> * MCUXpresso IDE v11.0.0_2495_alpha  

<table><tbody>
    <tr>
        <th>RT</th>
        <th>IDE</th>
        <th>Board</th>
        <th>Flash</th>
        <th>Status</th>
        <th>Comments</th>
    </tr>
    <tr>
        <td rowspan="5">i.MXRT600<br>
                        A0</td>
        <td>IAR</td>
        <td>/</td>
        <td>/</td>
        <td>/</td>
        <td>/</td>
    </tr>
    <tr>
        <td rowspan="3">Keil<br>
                        J-Link</td>
        <td>NXP RT600-EVB_Rev.0</td>
        <td>U8<br>
            W25Q64FW</td>
        <td>Done</td>
        <td>PIO1[23:20]<br>
            QSPI_PortA</td>
    </tr>
    <tr>
        <td>NXP RT600-EVK_Rev.B</td>
        <td>U19<br>
            MX25UM51345</td>
        <td>/</td>
        <td>PIO1[27:20]<br>
            QSPI_PortA</td>
    </tr>
    <tr>
        <td>MSFT xProject_V1</td>
        <td>W25Q16FW<br>
            (no SFDP)</td>
        <td>Done</td>
        <td>PIO1[23:20]<br>
            QSPI_PortA</td>
    </tr>
    <tr>
        <td>MCUX</td>
        <td>/</td>
        <td>/</td>
        <td>/</td>
        <td>/</td>
    </tr>
    <tr>
        <td rowspan="5">i.MXRT600<br>
                        B0</td>
        <td>IAR</td>
        <td>/</td>
        <td>/</td>
        <td>/</td>
        <td>/</td>
    </tr>
    <tr>
        <td rowspan="3">Keil<br>
                        J-Link</td>
        <td>NXP RT600-EVB_Rev.C</td>
        <td>/</td>
        <td>/</td>
        <td>/</td>
    </tr>
    <tr>
        <td>NXP RT600-EVK_Rev.E</td>
        <td>U19<br>
            MX25UM51345</td>
        <td>Done</td>
        <td>PIO1[14:11],PIO2[23:22,18:17]<br>
            FLEXSPI_PortB</td>
    </tr>
    <tr>
        <td>MSFT xProject_V2</td>
        <td>W25Q16FW<br>
            (no SFDP)</td>
        <td>Done</td>
        <td>PIO1[23:20]<br>
            FLEXSPI_PortA</td>
    </tr>
    <tr>
        <td>MCUX</td>
        <td>/</td>
        <td>/</td>
        <td>/</td>
        <td>/</td>
    </tr>
    <tr>
        <td rowspan="4">i.MXRT1060</td>
        <td>IAR</td>
        <td>/</td>
        <td>/</td>
        <td>/</td>
        <td>/</td>
    </tr>
    <tr>
        <td rowspan="3">Keil<br>
                        J-Link</td>
        <td>NXP RT1060-EVK_Rev.A1</td>
        <td>U33<br>
            IS25WP064</td>
        <td>Done</td>
        <td>GPIO_SD_B1[11:08]<br>
            FLEXSPI_PortA</td>
    </tr>
    <tr>
        <td>HON xProject_V1<br>
            HON xProject_V2</td>
        <td>IS25WP512<br>
            IS25LP256</td>
        <td>Done</td>
        <td>GPIO_SD_B1[11:08]<br>
            FLEXSPI_PortA</td>
    </tr>
    <tr>
        <td>HON yProject_V1</td>
        <td>IS25LP064</td>
        <td>Done</td>
        <td>GPIO_AD_B1[13:10]<br>
            FLEXSPI_PortA</td>
    </tr>
    <tr>
        <td>MCUX</td>
        <td>/</td>
        <td>/</td>
        <td>/</td>
        <td>/</td>
    </tr>
</table>
