<a id="idtext"></a> 
# SEPE 8K Dataset Location
Please feel free to [**view and download the dataset here**](https://drive.google.com/drive/folders/1geFicEJeRD7dhmBlb0CHSQyrvIkYwp5Y?usp=sharing) \
For comments, feedback, or question please [Contact Us](mailto:Tariq.AlShoura@ucalgary.ca) at: [Tariq.AlShoura@ucalgary.ca](mailto:Tariq.AlShoura@ucalgary.ca)

Please cite the following paper if using the dataset:
> Tariq Al Shoura, Ali Mollaahmadi Dehaghi, Reza Razavi, Behrouz Far, and Mohammad Moshirpour. 2023. SEPE Dataset: 8K Video Sequences and Images for Analysis and Development. In Proceedings of the 14th ACM Multimedia Systems Conference (MMSys ’23), June 7–10, 2023, Vancouver, BC, Canada. 

## Table of Contents
  * [Bitrates used for each video codec and resolution combination.](#bitrates-used-for-each-video-codec-and-resolution-combination)
  * [Spatial and Temporal Perceptual Information Distribution.](#spatial-and-temporal-perceptual-information-distribution)
  * [Video Sequences Details and Encoding Evaluation.](#video-sequences-details-and-encoding-evaluation)

<table class="boarderless">
<tr><td>&#9900; <a href='#sequence-001'>Sequence 001</a></td><td>&#9900; <a href='#sequence-002'>Sequence 002</a></td><td>&#9900; <a href='#sequence-003'>Sequence 003</a></td><td>&#9900; <a href='#sequence-004'>Sequence 004</a></td></tr>
<tr><td>&#9900; <a href='#sequence-005'>Sequence 005</a></td><td>&#9900; <a href='#sequence-006'>Sequence 006</a></td><td>&#9900; <a href='#sequence-007'>Sequence 007</a></td><td>&#9900; <a href='#sequence-008'>Sequence 008</a></td></tr>
<tr><td>&#9900; <a href='#sequence-009'>Sequence 009</a></td><td>&#9900; <a href='#sequence-010'>Sequence 010</a></td><td>&#9900; <a href='#sequence-011'>Sequence 011</a></td><td>&#9900; <a href='#sequence-012'>Sequence 012</a></td></tr>
<tr><td>&#9900; <a href='#sequence-013'>Sequence 013</a></td><td>&#9900; <a href='#sequence-014'>Sequence 014</a></td><td>&#9900; <a href='#sequence-015'>Sequence 015</a></td><td>&#9900; <a href='#sequence-016'>Sequence 016</a></td></tr>
<tr><td>&#9900; <a href='#sequence-017'>Sequence 017</a></td><td>&#9900; <a href='#sequence-018'>Sequence 018</a></td><td>&#9900; <a href='#sequence-019'>Sequence 019</a></td><td>&#9900; <a href='#sequence-020'>Sequence 020</a></td></tr>
<tr><td>&#9900; <a href='#sequence-021'>Sequence 021</a></td><td>&#9900; <a href='#sequence-022'>Sequence 022</a></td><td>&#9900; <a href='#sequence-023'>Sequence 023</a></td><td>&#9900; <a href='#sequence-024'>Sequence 024</a></td></tr>
<tr><td>&#9900; <a href='#sequence-025'>Sequence 025</a></td><td>&#9900; <a href='#sequence-026'>Sequence 026</a></td><td>&#9900; <a href='#sequence-027'>Sequence 027</a></td><td>&#9900; <a href='#sequence-028'>Sequence 028</a></td></tr>
<tr><td>&#9900; <a href='#sequence-029'>Sequence 029</a></td><td>&#9900; <a href='#sequence-030'>Sequence 030</a></td><td>&#9900; <a href='#sequence-031'>Sequence 031</a></td><td>&#9900; <a href='#sequence-032'>Sequence 032</a></td></tr>
<tr><td>&#9900; <a href='#sequence-033'>Sequence 033</a></td><td>&#9900; <a href='#sequence-034'>Sequence 034</a></td><td>&#9900; <a href='#sequence-035'>Sequence 035</a></td><td>&#9900; <a href='#sequence-036'>Sequence 036</a></td></tr>
<tr><td>&#9900; <a href='#sequence-037'>Sequence 037</a></td><td>&#9900; <a href='#sequence-038'>Sequence 038</a></td><td>&#9900; <a href='#sequence-039'>Sequence 039</a></td><td>&#9900; <a href='#sequence-040'>Sequence 040</a></td></tr>
</table>


* [FFmpeg Commands](#ffmpeg-commands)
    * [Video Encoding Commands](#video-encoding-commands)
    * [Image Transforming Commands](#image-transforming-commands)
* [Video Sequences Average RBG Histogram over time](#video-sequences-average-rbg-histogram-over-time)
* [Images Histogram over time](#images-histogram-over-time)

___
## Bitrates used for each video codec and resolution combination.
*__Table  1__. Bitrates used for each video codec and resolution combination*
<table> 
    <tr>
        <td align="center" colspan="2"><b>Resolution</td>
        <td align="center"><b>Codec</td>
        <td align="center"><b>Bitrate</b><br>(Mbps)</td>
    </tr>
    <tr>
        <td align="center" rowspan="3"><b>8K</td>
        <td align="center" rowspan="3">8192 × 4320</td>
        <td align="center">HEVC</td>
        <td align="center">150</td>
    </tr>
    <tr>
        <td align="center">H.264<sup>1</td>
        <td align="center">150</td>
    </tr>
    <tr>
        <td align="center">AV1</td>
        <td align="center">65</td>
    </tr>
    <tr>
        <td align="center" rowspan="3"><b>4K</td>
        <td align="center" rowspan="3">4096 × 2160</td>
        <td align="center">HEVC</td>
        <td align="center">45</td>
    </tr>
    <tr>
        <td align="center">H.264</td>
        <td align="center">45</td>
    </tr>
    <tr>
        <td align="center">AV1</td>
        <td align="center">17.5</td>
    </tr>
    <tr>
        <td align="center" rowspan="3"><b>2K</td>
        <td align="center" rowspan="3">2731 × 1440</td>
        <td align="center">HEVC<sup>2</td>
        <td align="center">20</td>
    </tr>
    <tr>
        <td align="center">H.264</td>
        <td align="center">20</td>
    </tr>
    <tr>
        <td align="center">AV1</td>
        <td align="center">8.5</td>
    </tr>
    <tr>
        <td align="center" rowspan="3"><b>1K</td>
        <td align="center" rowspan="3">2048 × 1080</td>
        <td align="center">HEVC</td>
        <td align="center">10</td>
    </tr>
    <tr>
        <td align="center">H.264</td>
        <td align="center">10</td>
    </tr>
    <tr>
        <td align="center">AV1</td>
        <td align="center">4.5</td>
    </tr>
    <tr>
        <td align="center" rowspan="3"><b>720p</td>
        <td align="center" rowspan="3">1365 × 720</td>
        <td align="center">HEVC<sup>3</td>
        <td align="center">6.5</td>
    </tr>
    <tr>
        <td align="center">H.264</td>
        <td align="center">6.5</td>
    </tr>
    <tr>
        <td align="center">AV1</td>
        <td align="center">3</td>
    </tr>
    <tr>
        <td align="center" rowspan="3"><b>480p</td>
        <td align="center" rowspan="3">910 × 480</td>
        <td align="center">HEVC</td>
        <td align="center">5</td>
    </tr>
    <tr>
        <td align="center">H.264</td>
        <td align="center">5</td>
    </tr>
    <tr>
        <td align="center">AV1</td>
        <td align="center">2</td>
    </tr>
</table>
<sup>1</sup> <i>No Hardware acceleration support</i><br>
<sup>2</sup> <i>(2732 × 1440) for HEVC due to nvenc library constrictions</i><br>
<sup>3</sup> <i>(1366 × 720) for HEVC due to nvenc library constrictions</i>
<br><br>

[Back to Top](#idtext)
___


## Spatial and Temporal Perceptual Information Distribution.
![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/SI_TI.png)
*__Figure 1.__ Spatial and Temporal Information Distribution*

[Back to Top](#idtext)
___


## Video Sequences Details and Encoding Evaluation.
Full frame-by-frame of the evaluation metrics is available **[Here](https://github.com/talshoura/SEPE-8K-Dataset/tree/main/data_description_and_analysis/frame_by_frame_encoding_analysis)**\
The video sequences are available **[Here](https://drive.google.com/drive/folders/1EF0w8KGKXO24eG1znpgr2XJYYOzBZUGo?usp=sharing)**\
The encoded video files are available **[Here](https://drive.google.com/drive/folders/1EvDYl2AYktNyiXnseTfHFZziX5fjXQ3E?usp=sharing)**

Size of all sequences: ~472 GB\
Size of encoded videos: ~302 MB

[Back to Top](#idtext)
___

### Sequence 001
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/001_480p.png)](https://drive.google.com/drive/folders/1wX3zV3zAJcS7l59DykFUdKLYP6daCkDd?usp=sharing)\
*__Figure  2__. First Frame of Sequence 001*

Raw Sequence Size:  9.97 GB\
Source: [HERE](https://drive.google.com/drive/folders/1wX3zV3zAJcS7l59DykFUdKLYP6daCkDd?usp=sharing)

<br>

*__Table 2__. Description of encoded videos using sequence 001 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">001_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   4.97<td>   3.97<td>1<td>299<td>0<td>37.75<td>31.96<td>230.19<td>  0.861</tr>
<tr><td align="left">001_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>  10.46<td>   8.36<td>1<td>299<td>0<td>38.30<td>31.82<td>230.72<td>  0.852</tr>
<tr><td align="left">001_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.01<td>   1.60<td>1<td>299<td>0<td>39.73<td>32.38<td>230.64<td>  0.851</tr>
<tr><td align="left">001_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  24.26<td>  19.39<td>1<td>299<td>0<td>40.46<td>31.73<td>230.81<td>  0.861</tr>
<tr><td align="left">001_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   3.12<td>   2.49<td>1<td>299<td>0<td>37.72<td>32.15<td>230.77<td>  0.852</tr>
<tr><td align="left">001_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td> 106.44<td>  85.07<td>1<td>299<td>0<td>49.84<td>31.56<td>231.24<td>  0.856</tr>
<tr><td align="left">001_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  12.75<td>  10.19<td>2<td>76<td>222<td>37.81<td>31.78<td>230.68<td>  0.860</tr>
<tr><td align="left">001_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  26.78<td>  21.40<td>2<td>77<td>221<td>38.26<td>31.63<td>231.06<td>  0.852</tr>
<tr><td align="left">001_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   5.62<td>   4.49<td>2<td>76<td>222<td>39.64<td>32.16<td>230.32<td>  0.850</tr>
<tr><td align="left">001_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  60.25<td>  48.15<td>2<td>78<td>220<td>40.44<td>31.59<td>231.27<td>  0.860</tr>
<tr><td align="left">001_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   7.99<td>   6.39<td>2<td>76<td>222<td>37.68<td>31.88<td>230.81<td>  0.851</tr>
<tr><td align="left">001_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 199.20<td> 159.20<td>2<td>259<td>39<td>49.71<td>31.59<td>231.48<td>  0.856</tr>
<tr><td align="left">001_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  13.17<td>  10.53<td>2<td>76<td>222<td>37.69<td>31.81<td>230.64<td>  0.860</tr>
<tr><td align="left">001_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  26.38<td>  21.08<td>2<td>76<td>222<td>36.10<td>31.56<td>231.89<td>  0.850</tr>
<tr><td align="left">001_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   5.73<td>   4.58<td>2<td>76<td>222<td>39.44<td>32.19<td>230.19<td>  0.851</tr>
<tr><td align="left">001_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  59.80<td>  47.79<td>2<td>76<td>222<td>40.30<td>31.62<td>231.22<td>  0.860</tr>
<tr><td align="left">001_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   8.46<td>   6.76<td>2<td>76<td>222<td>33.73<td>31.66<td>232.70<td>  0.848</tr>
<tr><td align="left">001_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 199.13<td> 159.15<td>2<td>76<td>222<td>49.82<td>31.51<td>231.48<td>  0.856</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 002
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/002_480p.png)](https://drive.google.com/drive/folders/1J6EYEN6rjyiHzX5Hf9_wMHrQcRB5f1j3?usp=share_link)\
*__Figure  3__. First Frame of Sequence 002*

Raw Sequence Size:  6.31 GB\
Source: [HERE](https://drive.google.com/drive/folders/1J6EYEN6rjyiHzX5Hf9_wMHrQcRB5f1j3?usp=share_link)

<br>

*__Table 3__. Description of encoded videos using sequence 002 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">002_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   5.57<td>   4.45<td>1<td>299<td>0<td>79.92<td>41.35<td>23.44<td>  0.976</tr>
<tr><td align="left">002_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>  10.44<td>   8.34<td>1<td>299<td>0<td>78.96<td>41.36<td>23.50<td>  0.974</tr>
<tr><td align="left">002_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.41<td>   1.93<td>1<td>299<td>0<td>80.78<td>41.56<td>23.29<td>  0.974</tr>
<tr><td align="left">002_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  18.18<td>  14.53<td>1<td>299<td>0<td>77.89<td>41.40<td>23.52<td>  0.976</tr>
<tr><td align="left">002_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   3.61<td>   2.88<td>1<td>299<td>0<td>80.83<td>41.44<td>23.38<td>  0.974</tr>
<tr><td align="left">002_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  77.00<td>  61.54<td>1<td>299<td>0<td>76.35<td>41.32<td>23.58<td>  0.975</tr>
<tr><td align="left">002_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>   9.14<td>   7.30<td>2<td>76<td>222<td>79.69<td>40.79<td>23.60<td>  0.975</tr>
<tr><td align="left">002_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  16.94<td>  13.54<td>2<td>76<td>222<td>78.70<td>40.85<td>23.70<td>  0.974</tr>
<tr><td align="left">002_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   2.70<td>   2.15<td>2<td>76<td>222<td>79.91<td>40.81<td>23.58<td>  0.973</tr>
<tr><td align="left">002_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  41.10<td>  32.84<td>2<td>76<td>222<td>77.89<td>40.95<td>23.63<td>  0.976</tr>
<tr><td align="left">002_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   4.71<td>   3.76<td>2<td>76<td>222<td>80.29<td>40.81<td>23.58<td>  0.973</tr>
<tr><td align="left">002_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 194.86<td> 155.73<td>2<td>75<td>223<td>76.23<td>41.21<td>23.65<td>  0.975</tr>
<tr><td align="left">002_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>   8.13<td>   6.50<td>2<td>76<td>222<td>79.42<td>40.95<td>23.57<td>  0.975</tr>
<tr><td align="left">002_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  13.73<td>  10.97<td>2<td>76<td>222<td>76.44<td>40.93<td>23.95<td>  0.973</tr>
<tr><td align="left">002_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   2.39<td>   1.91<td>2<td>76<td>222<td>79.74<td>40.84<td>23.60<td>  0.973</tr>
<tr><td align="left">002_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  30.40<td>  24.30<td>2<td>76<td>222<td>77.68<td>41.11<td>23.60<td>  0.976</tr>
<tr><td align="left">002_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   4.15<td>   3.32<td>2<td>76<td>222<td>73.98<td>40.67<td>24.54<td>  0.971</tr>
<tr><td align="left">002_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 125.21<td> 100.07<td>2<td>76<td>222<td>76.23<td>41.15<td>23.64<td>  0.975</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 003
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/003_480p.png)](https://drive.google.com/drive/folders/1veJuOduzKV0UUrrx_Rk2zRwDhOp7UOHn?usp=share_link)\
*__Figure  4__. First Frame of Sequence 003*

Raw Sequence Size:  7.56 GB\
Source: [HERE](https://drive.google.com/drive/folders/1veJuOduzKV0UUrrx_Rk2zRwDhOp7UOHn?usp=share_link)

<br>

*__Table 4__. Description of encoded videos using sequence 003 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">003_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   5.53<td>   4.42<td>1<td>299<td>0<td>11.93<td>35.13<td>474.33<td>  0.694</tr>
<tr><td align="left">003_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>  10.50<td>   8.39<td>1<td>299<td>0<td> 9.39<td>35.10<td>475.78<td>  0.700</tr>
<tr><td align="left">003_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.47<td>   1.97<td>1<td>299<td>0<td>18.86<td>35.30<td>460.28<td>  0.695</tr>
<tr><td align="left">003_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  19.20<td>  15.35<td>1<td>299<td>0<td> 6.55<td>35.00<td>476.06<td>  0.696</tr>
<tr><td align="left">003_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   3.71<td>   2.96<td>1<td>299<td>0<td>15.35<td>35.12<td>471.23<td>  0.697</tr>
<tr><td align="left">003_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  74.66<td>  59.67<td>1<td>299<td>0<td> 4.06<td>35.04<td>476.63<td>  0.699</tr>
<tr><td align="left">003_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  12.17<td>   9.73<td>2<td>76<td>222<td>11.79<td>35.02<td>474.23<td>  0.694</tr>
<tr><td align="left">003_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  23.98<td>  19.16<td>2<td>76<td>222<td> 9.32<td>34.95<td>475.77<td>  0.700</tr>
<tr><td align="left">003_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   5.77<td>   4.61<td>2<td>76<td>222<td>18.69<td>35.29<td>460.65<td>  0.695</tr>
<tr><td align="left">003_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  53.49<td>  42.75<td>2<td>76<td>222<td> 6.54<td>34.85<td>476.74<td>  0.696</tr>
<tr><td align="left">003_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   8.19<td>   6.55<td>2<td>76<td>222<td>15.15<td>35.11<td>470.33<td>  0.697</tr>
<tr><td align="left">003_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 190.72<td> 152.42<td>2<td>76<td>222<td> 4.05<td>34.97<td>477.01<td>  0.698</tr>
<tr><td align="left">003_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  12.66<td>  10.12<td>2<td>76<td>222<td>11.81<td>35.03<td>474.23<td>  0.695</tr>
<tr><td align="left">003_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  25.58<td>  20.44<td>2<td>76<td>222<td> 8.07<td>34.90<td>478.07<td>  0.696</tr>
<tr><td align="left">003_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   5.73<td>   4.58<td>2<td>76<td>222<td>18.71<td>35.25<td>461.05<td>  0.695</tr>
<tr><td align="left">003_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  58.22<td>  46.53<td>2<td>76<td>222<td> 6.52<td>34.89<td>476.50<td>  0.696</tr>
<tr><td align="left">003_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   8.24<td>   6.58<td>2<td>76<td>222<td>13.12<td>35.04<td>475.87<td>  0.689</tr>
<tr><td align="left">003_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 200.12<td> 159.93<td>2<td>76<td>222<td> 4.05<td>34.90<td>476.97<td>  0.698</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 004
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/004_480p.png)](https://drive.google.com/drive/folders/1qP8jLVDdv1xSiWFZk7WiMmilzpxBWZxR?usp=sharing)\
*__Figure  5__. First Frame of Sequence 004*

Raw Sequence Size:  6.27 GB\
Source: [HERE](https://drive.google.com/drive/folders/1qP8jLVDdv1xSiWFZk7WiMmilzpxBWZxR?usp=sharing)

<br>

*__Table 5__. Description of encoded videos using sequence 004 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">004_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   5.53<td>   4.42<td>1<td>299<td>0<td>72.83<td>36.29<td>215.01<td>  0.920</tr>
<tr><td align="left">004_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>  10.48<td>   8.38<td>1<td>299<td>0<td>74.26<td>36.44<td>215.12<td>  0.914</tr>
<tr><td align="left">004_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.43<td>   1.94<td>1<td>299<td>0<td>67.88<td>36.28<td>215.12<td>  0.914</tr>
<tr><td align="left">004_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  19.21<td>  15.35<td>1<td>299<td>0<td>75.87<td>36.39<td>215.15<td>  0.920</tr>
<tr><td align="left">004_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   3.69<td>   2.95<td>1<td>299<td>0<td>70.61<td>36.57<td>215.14<td>  0.914</tr>
<tr><td align="left">004_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  75.61<td>  60.43<td>1<td>299<td>0<td>77.49<td>36.39<td>215.34<td>  0.917</tr>
<tr><td align="left">004_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  10.95<td>   8.75<td>2<td>76<td>222<td>72.64<td>36.02<td>215.37<td>  0.919</tr>
<tr><td align="left">004_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  20.97<td>  16.76<td>2<td>76<td>222<td>74.15<td>36.22<td>215.23<td>  0.914</tr>
<tr><td align="left">004_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   3.41<td>   2.73<td>2<td>76<td>222<td>67.63<td>36.05<td>215.07<td>  0.913</tr>
<tr><td align="left">004_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  46.38<td>  37.06<td>2<td>76<td>222<td>75.87<td>36.19<td>215.43<td>  0.920</tr>
<tr><td align="left">004_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   6.44<td>   5.15<td>2<td>76<td>222<td>70.42<td>36.23<td>215.32<td>  0.914</tr>
<tr><td align="left">004_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 190.99<td> 152.64<td>2<td>78<td>220<td>77.30<td>36.35<td>215.43<td>  0.917</tr>
<tr><td align="left">004_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  11.99<td>   9.58<td>2<td>76<td>222<td>72.56<td>36.09<td>215.34<td>  0.919</tr>
<tr><td align="left">004_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  23.21<td>  18.55<td>2<td>76<td>222<td>69.26<td>36.20<td>216.38<td>  0.914</tr>
<tr><td align="left">004_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   3.26<td>   2.61<td>2<td>76<td>222<td>67.59<td>36.09<td>215.03<td>  0.913</tr>
<tr><td align="left">004_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  48.00<td>  38.36<td>2<td>76<td>222<td>75.79<td>36.25<td>215.41<td>  0.920</tr>
<tr><td align="left">004_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   5.94<td>   4.75<td>2<td>76<td>222<td>62.89<td>36.14<td>218.72<td>  0.911</tr>
<tr><td align="left">004_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 164.67<td> 131.61<td>2<td>76<td>222<td>77.46<td>36.27<td>215.45<td>  0.917</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 005
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/005_480p.png)](https://drive.google.com/drive/folders/10ArGk3Synyx9gXd2CHl6VXt9EFD7zQtC?usp=sharing)\
*__Figure  6__. First Frame of Sequence 005*

Raw Sequence Size: 17.17 GB\
Source: [HERE](https://drive.google.com/drive/folders/10ArGk3Synyx9gXd2CHl6VXt9EFD7zQtC?usp=sharing)

<br>

*__Table 6__. Description of encoded videos using sequence 005 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">005_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   6.03<td>   4.82<td>1<td>299<td>0<td>12.43<td>33.88<td>131.55<td>  0.695</tr>
<tr><td align="left">005_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>  11.59<td>   9.26<td>1<td>299<td>0<td>10.04<td>33.43<td>135.89<td>  0.706</tr>
<tr><td align="left">005_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.73<td>   2.18<td>1<td>299<td>0<td>24.77<td>35.34<td>109.96<td>  0.705</tr>
<tr><td align="left">005_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  23.94<td>  19.13<td>1<td>299<td>0<td> 7.88<td>33.06<td>139.23<td>  0.693</tr>
<tr><td align="left">005_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   4.06<td>   3.25<td>1<td>299<td>0<td>17.11<td>34.57<td>122.95<td>  0.706</tr>
<tr><td align="left">005_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  92.75<td>  74.13<td>1<td>299<td>0<td> 5.84<td>32.63<td>141.49<td>  0.699</tr>
<tr><td align="left">005_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  13.90<td>  11.11<td>2<td>76<td>222<td>12.20<td>34.02<td>130.79<td>  0.694</tr>
<tr><td align="left">005_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  27.95<td>  22.34<td>2<td>76<td>222<td> 9.95<td>33.63<td>135.70<td>  0.706</tr>
<tr><td align="left">005_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   7.25<td>   5.79<td>2<td>76<td>222<td>24.49<td>35.27<td>110.48<td>  0.701</tr>
<tr><td align="left">005_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  62.56<td>  50.00<td>2<td>76<td>222<td> 7.82<td>33.15<td>139.34<td>  0.693</tr>
<tr><td align="left">005_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   9.30<td>   7.44<td>2<td>76<td>222<td>16.85<td>34.72<td>122.58<td>  0.705</tr>
<tr><td align="left">005_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 210.06<td> 167.88<td>2<td>76<td>222<td> 5.76<td>32.78<td>141.30<td>  0.699</tr>
<tr><td align="left">005_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  13.19<td>  10.54<td>2<td>76<td>222<td>12.28<td>33.90<td>131.28<td>  0.694</tr>
<tr><td align="left">005_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  26.31<td>  21.03<td>2<td>76<td>222<td>10.14<td>33.49<td>134.44<td>  0.710</tr>
<tr><td align="left">005_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   7.00<td>   5.60<td>2<td>76<td>222<td>24.52<td>35.24<td>110.59<td>  0.702</tr>
<tr><td align="left">005_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  59.11<td>  47.24<td>2<td>76<td>222<td> 7.84<td>33.03<td>139.30<td>  0.693</tr>
<tr><td align="left">005_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   9.05<td>   7.23<td>2<td>76<td>222<td>17.75<td>34.61<td>120.42<td>  0.713</tr>
<tr><td align="left">005_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 197.01<td> 157.45<td>2<td>76<td>222<td> 5.84<td>32.57<td>141.66<td>  0.699</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 006
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/006_480p.png)](https://drive.google.com/drive/folders/1hkZd8n7F7iTMkahTHW2aZyTZiRaXktDi?usp=share_link)\
*__Figure  7__. First Frame of Sequence 006*

Raw Sequence Size: 16.86 GB\
Source: [HERE](https://drive.google.com/drive/folders/1hkZd8n7F7iTMkahTHW2aZyTZiRaXktDi?usp=share_link)

<br>

*__Table 7__. Description of encoded videos using sequence 006 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">006_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   5.03<td>   4.02<td>1<td>299<td>0<td> 5.25<td>35.06<td>229.88<td>  0.920</tr>
<tr><td align="left">006_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>  10.43<td>   8.33<td>1<td>299<td>0<td> 7.70<td>34.73<td>230.79<td>  0.917</tr>
<tr><td align="left">006_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.40<td>   1.92<td>1<td>299<td>0<td> 3.70<td>35.55<td>229.44<td>  0.916</tr>
<tr><td align="left">006_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  20.18<td>  16.13<td>1<td>299<td>0<td>11.29<td>34.41<td>231.05<td>  0.920</tr>
<tr><td align="left">006_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   3.01<td>   2.41<td>1<td>299<td>0<td> 3.50<td>35.25<td>230.11<td>  0.916</tr>
<tr><td align="left">006_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  68.53<td>  54.77<td>1<td>299<td>0<td>29.24<td>33.87<td>232.39<td>  0.918</tr>
<tr><td align="left">006_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  12.99<td>  10.38<td>2<td>294<td>4<td> 5.26<td>34.76<td>230.09<td>  0.920</tr>
<tr><td align="left">006_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  26.54<td>  21.21<td>2<td>298<td>0<td> 7.71<td>34.51<td>230.84<td>  0.917</tr>
<tr><td align="left">006_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   4.93<td>   3.94<td>2<td>167<td>131<td> 3.69<td>35.30<td>229.46<td>  0.916</tr>
<tr><td align="left">006_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  59.45<td>  47.51<td>2<td>298<td>0<td>11.31<td>34.16<td>231.14<td>  0.920</tr>
<tr><td align="left">006_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   8.08<td>   6.45<td>2<td>233<td>65<td> 3.46<td>35.15<td>229.95<td>  0.916</tr>
<tr><td align="left">006_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 222.55<td> 177.86<td>2<td>298<td>0<td>30.14<td>33.76<td>232.88<td>  0.918</tr>
<tr><td align="left">006_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  13.13<td>  10.49<td>2<td>76<td>222<td> 5.25<td>34.85<td>229.98<td>  0.920</tr>
<tr><td align="left">006_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  26.50<td>  21.18<td>2<td>76<td>222<td> 7.50<td>34.59<td>230.74<td>  0.917</tr>
<tr><td align="left">006_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   3.72<td>   2.97<td>2<td>76<td>222<td> 3.68<td>35.33<td>229.40<td>  0.916</tr>
<tr><td align="left">006_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  59.15<td>  47.27<td>2<td>76<td>222<td>11.33<td>34.24<td>231.13<td>  0.920</tr>
<tr><td align="left">006_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   7.17<td>   5.73<td>2<td>76<td>222<td> 3.21<td>35.15<td>229.87<td>  0.916</tr>
<tr><td align="left">006_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 198.74<td> 158.84<td>2<td>76<td>222<td>30.17<td>33.70<td>232.78<td>  0.918</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 007
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/007_480p.png)](https://drive.google.com/drive/folders/1-crbTwtjwLnkPu5OW4gL6em0o3_Tn3pp?usp=share_link)\
*__Figure  8__. First Frame of Sequence 007*

Raw Sequence Size:  7.99 GB\
Source: [HERE](https://drive.google.com/drive/folders/1-crbTwtjwLnkPu5OW4gL6em0o3_Tn3pp?usp=share_link)

<br>

*__Table 8__. Description of encoded videos using sequence 007 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">007_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   5.41<td>   4.32<td>1<td>299<td>0<td> 8.66<td>34.28<td>213.60<td>  0.777</tr>
<tr><td align="left">007_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>  10.15<td>   8.12<td>1<td>299<td>0<td> 7.69<td>34.13<td>215.72<td>  0.771</tr>
<tr><td align="left">007_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.42<td>   1.94<td>1<td>299<td>0<td>13.84<td>34.73<td>204.59<td>  0.770</tr>
<tr><td align="left">007_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  20.86<td>  16.67<td>1<td>299<td>0<td> 6.96<td>34.12<td>216.91<td>  0.777</tr>
<tr><td align="left">007_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   3.65<td>   2.92<td>1<td>299<td>0<td>10.81<td>34.52<td>209.93<td>  0.771</tr>
<tr><td align="left">007_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  85.78<td>  68.56<td>1<td>299<td>0<td> 7.94<td>33.99<td>218.02<td>  0.774</tr>
<tr><td align="left">007_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  12.97<td>  10.36<td>2<td>76<td>222<td> 8.63<td>34.12<td>214.21<td>  0.776</tr>
<tr><td align="left">007_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  26.79<td>  21.41<td>2<td>76<td>222<td> 7.66<td>34.06<td>215.99<td>  0.771</tr>
<tr><td align="left">007_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   5.28<td>   4.22<td>2<td>76<td>222<td>13.75<td>34.66<td>204.32<td>  0.770</tr>
<tr><td align="left">007_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  60.31<td>  48.20<td>2<td>76<td>222<td> 6.94<td>33.97<td>217.61<td>  0.776</tr>
<tr><td align="left">007_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   8.04<td>   6.42<td>2<td>76<td>222<td>10.75<td>34.43<td>209.89<td>  0.770</tr>
<tr><td align="left">007_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 195.68<td> 156.39<td>2<td>76<td>222<td> 7.89<td>33.99<td>218.35<td>  0.774</tr>
<tr><td align="left">007_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  12.88<td>  10.29<td>2<td>76<td>222<td> 8.62<td>34.15<td>213.85<td>  0.777</tr>
<tr><td align="left">007_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  26.19<td>  20.93<td>2<td>76<td>222<td> 7.44<td>34.03<td>215.71<td>  0.771</tr>
<tr><td align="left">007_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   4.94<td>   3.95<td>2<td>76<td>222<td>13.74<td>34.66<td>204.01<td>  0.771</tr>
<tr><td align="left">007_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  58.80<td>  46.99<td>2<td>76<td>222<td> 6.94<td>34.01<td>217.32<td>  0.777</tr>
<tr><td align="left">007_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   7.78<td>   6.22<td>2<td>76<td>222<td>10.26<td>34.34<td>209.84<td>  0.770</tr>
<tr><td align="left">007_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 197.76<td> 158.05<td>2<td>76<td>222<td> 7.92<td>33.92<td>218.25<td>  0.774</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 008
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/008_480p.png)](https://drive.google.com/drive/folders/1I1FJ5gMShqGPSmxBVGmogbO2RkVdyxEN?usp=share_link)\
*__Figure  9__. First Frame of Sequence 008*

Raw Sequence Size: 15.32 GB\
Source: [HERE](https://drive.google.com/drive/folders/1I1FJ5gMShqGPSmxBVGmogbO2RkVdyxEN?usp=share_link)

<br>

*__Table 9__. Description of encoded videos using sequence 008 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">008_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   4.98<td>   3.98<td>1<td>299<td>0<td>13.37<td>30.59<td>386.52<td>  0.724</tr>
<tr><td align="left">008_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>   9.02<td>   7.21<td>1<td>299<td>0<td>11.23<td>30.42<td>389.65<td>  0.726</tr>
<tr><td align="left">008_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.21<td>   1.76<td>1<td>299<td>0<td>22.66<td>31.13<td>371.81<td>  0.723</tr>
<tr><td align="left">008_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  18.48<td>  14.77<td>1<td>299<td>0<td> 8.49<td>30.29<td>391.56<td>  0.726</tr>
<tr><td align="left">008_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   3.28<td>   2.62<td>1<td>299<td>0<td>17.80<td>30.88<td>381.08<td>  0.724</tr>
<tr><td align="left">008_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  82.33<td>  65.79<td>1<td>299<td>0<td> 5.23<td>30.08<td>392.92<td>  0.727</tr>
<tr><td align="left">008_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  12.81<td>  10.24<td>2<td>76<td>222<td>13.17<td>30.60<td>386.23<td>  0.725</tr>
<tr><td align="left">008_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  25.95<td>  20.74<td>2<td>76<td>222<td>11.08<td>30.43<td>389.24<td>  0.726</tr>
<tr><td align="left">008_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   6.25<td>   4.99<td>2<td>76<td>222<td>22.35<td>31.16<td>370.84<td>  0.723</tr>
<tr><td align="left">008_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  59.06<td>  47.20<td>2<td>76<td>222<td> 8.40<td>30.29<td>391.85<td>  0.726</tr>
<tr><td align="left">008_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   8.43<td>   6.74<td>2<td>76<td>222<td>17.50<td>30.83<td>380.17<td>  0.724</tr>
<tr><td align="left">008_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 203.21<td> 162.40<td>2<td>77<td>221<td> 5.16<td>30.17<td>393.58<td>  0.727</tr>
<tr><td align="left">008_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  12.93<td>  10.33<td>2<td>76<td>222<td>13.21<td>30.60<td>386.05<td>  0.725</tr>
<tr><td align="left">008_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  25.98<td>  20.76<td>2<td>76<td>222<td> 9.82<td>30.33<td>391.00<td>  0.724</tr>
<tr><td align="left">008_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   6.33<td>   5.06<td>2<td>76<td>222<td>22.40<td>31.15<td>370.85<td>  0.723</tr>
<tr><td align="left">008_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  58.84<td>  47.02<td>2<td>76<td>222<td> 8.40<td>30.27<td>391.44<td>  0.726</tr>
<tr><td align="left">008_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   8.29<td>   6.62<td>2<td>76<td>222<td>15.18<td>30.69<td>384.43<td>  0.718</tr>
<tr><td align="left">008_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 197.35<td> 157.73<td>2<td>76<td>222<td> 5.20<td>30.06<td>393.03<td>  0.727</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 009
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/009_480p.png)](https://drive.google.com/drive/folders/1C0Cjke5SXXei92v64JNL_GxGWfSP9mb6?usp=sharing)\
*__Figure 10__. First Frame of Sequence 009*

Raw Sequence Size: 15.00 GB\
Source: [HERE](https://drive.google.com/drive/folders/1C0Cjke5SXXei92v64JNL_GxGWfSP9mb6?usp=sharing)

<br>

*__Table 10__. Description of encoded videos using sequence 009 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">009_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   5.24<td>   4.19<td>1<td>299<td>0<td>13.03<td>40.17<td>149.91<td>  0.707</tr>
<tr><td align="left">009_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>   9.61<td>   7.68<td>1<td>299<td>0<td>10.48<td>39.75<td>153.02<td>  0.723</tr>
<tr><td align="left">009_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.37<td>   1.90<td>1<td>299<td>0<td>25.32<td>41.17<td>134.11<td>  0.717</tr>
<tr><td align="left">009_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  19.22<td>  15.36<td>1<td>299<td>0<td> 8.84<td>39.36<td>155.09<td>  0.711</tr>
<tr><td align="left">009_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   3.49<td>   2.79<td>1<td>299<td>0<td>17.99<td>40.71<td>143.57<td>  0.720</tr>
<tr><td align="left">009_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  70.09<td>  56.01<td>1<td>299<td>0<td> 8.96<td>38.74<td>156.26<td>  0.719</tr>
<tr><td align="left">009_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  13.69<td>  10.94<td>2<td>76<td>222<td>12.86<td>39.65<td>149.20<td>  0.709</tr>
<tr><td align="left">009_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  26.91<td>  21.51<td>2<td>76<td>222<td>10.40<td>39.55<td>152.63<td>  0.724</tr>
<tr><td align="left">009_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   6.67<td>   5.33<td>2<td>76<td>222<td>25.05<td>40.73<td>133.56<td>  0.718</tr>
<tr><td align="left">009_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  58.65<td>  46.87<td>2<td>76<td>222<td> 8.82<td>39.08<td>155.20<td>  0.711</tr>
<tr><td align="left">009_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   9.10<td>   7.27<td>2<td>76<td>222<td>17.76<td>40.39<td>142.67<td>  0.721</tr>
<tr><td align="left">009_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 200.91<td> 160.57<td>3<td>76<td>221<td> 8.99<td>38.57<td>156.44<td>  0.719</tr>
<tr><td align="left">009_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  13.26<td>  10.60<td>2<td>76<td>222<td>12.89<td>39.78<td>149.16<td>  0.709</tr>
<tr><td align="left">009_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  26.52<td>  21.19<td>2<td>76<td>222<td>11.17<td>39.66<td>150.26<td>  0.729</tr>
<tr><td align="left">009_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   6.48<td>   5.18<td>2<td>76<td>222<td>25.09<td>40.71<td>133.81<td>  0.718</tr>
<tr><td align="left">009_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  59.82<td>  47.81<td>2<td>76<td>222<td> 8.82<td>39.21<td>154.87<td>  0.711</tr>
<tr><td align="left">009_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   8.98<td>   7.18<td>2<td>76<td>222<td>19.88<td>40.33<td>138.70<td>  0.731</tr>
<tr><td align="left">009_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 198.07<td> 158.29<td>2<td>76<td>222<td> 8.93<td>38.61<td>156.03<td>  0.719</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 010
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/010_480p.png)](https://drive.google.com/drive/folders/1t7G9eImxwUE94KxYuRuhk5h5UJohL5ZA?usp=share_link)\
*__Figure 11__. First Frame of Sequence 010*

Raw Sequence Size: 19.83 GB\
Source: [HERE](https://drive.google.com/drive/folders/1t7G9eImxwUE94KxYuRuhk5h5UJohL5ZA?usp=share_link)

<br>

*__Table 11__. Description of encoded videos using sequence 010 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">010_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   4.86<td>   3.89<td>2<td>298<td>0<td>76.95<td>38.57<td>327.39<td>  0.956</tr>
<tr><td align="left">010_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>   9.26<td>   7.40<td>2<td>298<td>0<td>77.07<td>37.80<td>329.46<td>  0.956</tr>
<tr><td align="left">010_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.18<td>   1.74<td>2<td>298<td>0<td>76.31<td>40.56<td>325.79<td>  0.956</tr>
<tr><td align="left">010_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  18.98<td>  15.17<td>2<td>298<td>0<td>76.98<td>36.81<td>331.19<td>  0.956</tr>
<tr><td align="left">010_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   3.17<td>   2.53<td>2<td>298<td>0<td>75.60<td>39.63<td>327.24<td>  0.956</tr>
<tr><td align="left">010_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  70.46<td>  56.31<td>1<td>299<td>0<td>72.55<td>35.54<td>335.42<td>  0.956</tr>
<tr><td align="left">010_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  10.26<td>   8.20<td>2<td>81<td>217<td>76.65<td>37.74<td>328.53<td>  0.956</tr>
<tr><td align="left">010_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  21.09<td>  16.86<td>2<td>105<td>193<td>76.82<td>37.14<td>328.88<td>  0.956</tr>
<tr><td align="left">010_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   4.42<td>   3.53<td>2<td>77<td>221<td>76.12<td>39.23<td>324.83<td>  0.956</tr>
<tr><td align="left">010_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  51.77<td>  41.37<td>2<td>151<td>147<td>76.48<td>36.32<td>332.73<td>  0.956</tr>
<tr><td align="left">010_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   6.62<td>   5.29<td>2<td>80<td>218<td>75.22<td>38.59<td>327.75<td>  0.956</tr>
<tr><td align="left">010_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 229.48<td> 183.40<td>5<td>77<td>218<td>70.90<td>35.24<td>336.31<td>  0.956</tr>
<tr><td align="left">010_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  12.26<td>   9.79<td>2<td>76<td>222<td>76.78<td>37.91<td>328.48<td>  0.956</tr>
<tr><td align="left">010_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  25.23<td>  20.17<td>2<td>76<td>222<td>67.84<td>36.09<td>332.48<td>  0.955</tr>
<tr><td align="left">010_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   4.48<td>   3.58<td>2<td>76<td>222<td>76.13<td>39.33<td>324.89<td>  0.956</tr>
<tr><td align="left">010_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  57.35<td>  45.84<td>2<td>76<td>222<td>76.64<td>36.43<td>332.71<td>  0.956</tr>
<tr><td align="left">010_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   6.64<td>   5.31<td>2<td>76<td>222<td>64.81<td>36.88<td>333.26<td>  0.951</tr>
<tr><td align="left">010_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 196.09<td> 156.72<td>2<td>76<td>222<td>71.92<td>35.27<td>336.22<td>  0.956</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 011
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/011_480p.png)](https://drive.google.com/drive/folders/1jMto-6myikzWCoCo5Y0FrdPDxAuF6V1k?usp=share_link)\
*__Figure 12__. First Frame of Sequence 011*

Raw Sequence Size:  5.78 GB\
Source: [HERE](https://drive.google.com/drive/folders/1jMto-6myikzWCoCo5Y0FrdPDxAuF6V1k?usp=share_link)

<br>

*__Table 12__. Description of encoded videos using sequence 011 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">011_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   5.28<td>   4.22<td>2<td>298<td>0<td>24.44<td>34.45<td>875.28<td>  0.736</tr>
<tr><td align="left">011_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>  10.48<td>   8.38<td>2<td>298<td>0<td>22.60<td>34.30<td>878.09<td>  0.735</tr>
<tr><td align="left">011_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.42<td>   1.94<td>3<td>297<td>0<td>31.99<td>34.98<td>872.05<td>  0.732</tr>
<tr><td align="left">011_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  23.26<td>  18.59<td>1<td>299<td>0<td>20.93<td>34.22<td>876.69<td>  0.737</tr>
<tr><td align="left">011_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   3.63<td>   2.90<td>3<td>297<td>0<td>27.34<td>34.66<td>874.14<td>  0.734</tr>
<tr><td align="left">011_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  92.24<td>  73.72<td>1<td>299<td>0<td>20.30<td>34.12<td>877.98<td>  0.736</tr>
<tr><td align="left">011_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  12.52<td>  10.01<td>2<td>89<td>209<td>24.29<td>34.26<td>874.17<td>  0.736</tr>
<tr><td align="left">011_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  24.21<td>  19.35<td>2<td>90<td>208<td>22.48<td>34.21<td>879.15<td>  0.734</tr>
<tr><td align="left">011_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   4.76<td>   3.80<td>2<td>89<td>209<td>31.80<td>34.20<td>872.00<td>  0.732</tr>
<tr><td align="left">011_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  52.60<td>  42.04<td>2<td>90<td>208<td>20.89<td>34.13<td>876.04<td>  0.737</tr>
<tr><td align="left">011_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   7.77<td>   6.21<td>2<td>89<td>209<td>27.08<td>34.02<td>872.14<td>  0.734</tr>
<tr><td align="left">011_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 179.43<td> 143.40<td>3<td>82<td>215<td>20.30<td>34.12<td>878.02<td>  0.736</tr>
<tr><td align="left">011_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  11.71<td>   9.36<td>2<td>76<td>222<td>24.27<td>34.31<td>874.49<td>  0.736</tr>
<tr><td align="left">011_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  23.40<td>  18.70<td>2<td>76<td>222<td>22.18<td>34.20<td>878.92<td>  0.735</tr>
<tr><td align="left">011_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   4.12<td>   3.29<td>2<td>76<td>222<td>31.75<td>34.22<td>872.42<td>  0.732</tr>
<tr><td align="left">011_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  51.72<td>  41.34<td>2<td>76<td>222<td>20.87<td>34.16<td>876.11<td>  0.737</tr>
<tr><td align="left">011_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   7.03<td>   5.62<td>2<td>76<td>222<td>26.90<td>33.97<td>872.03<td>  0.735</tr>
<tr><td align="left">011_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 173.88<td> 138.96<td>2<td>76<td>222<td>20.30<td>34.07<td>878.26<td>  0.736</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 012
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/012_480p.png)](https://drive.google.com/drive/folders/1YLJP1JAUjifGtgSTnVL1Wlx2WPUendTd?usp=share_link)\
*__Figure 13__. First Frame of Sequence 012*

Raw Sequence Size:  5.78 GB\
Source: [HERE](https://drive.google.com/drive/folders/1YLJP1JAUjifGtgSTnVL1Wlx2WPUendTd?usp=share_link)

<br>

*__Table 13__. Description of encoded videos using sequence 012 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">012_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   5.59<td>   4.47<td>1<td>299<td>0<td>20.78<td>42.61<td>110.05<td>  0.780</tr>
<tr><td align="left">012_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>  10.24<td>   8.19<td>1<td>299<td>0<td>18.72<td>42.63<td>110.31<td>  0.782</tr>
<tr><td align="left">012_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.48<td>   1.98<td>1<td>299<td>0<td>27.18<td>42.84<td>108.60<td>  0.777</tr>
<tr><td align="left">012_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  20.78<td>  16.60<td>1<td>299<td>0<td>17.68<td>42.55<td>110.19<td>  0.781</tr>
<tr><td align="left">012_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   3.72<td>   2.97<td>1<td>299<td>0<td>23.30<td>42.71<td>110.20<td>  0.780</tr>
<tr><td align="left">012_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  71.72<td>  57.32<td>1<td>299<td>0<td>22.14<td>42.50<td>110.08<td>  0.782</tr>
<tr><td align="left">012_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  10.46<td>   8.36<td>2<td>76<td>222<td>20.71<td>42.11<td>110.24<td>  0.780</tr>
<tr><td align="left">012_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  18.31<td>  14.63<td>2<td>76<td>222<td>18.60<td>41.68<td>110.39<td>  0.782</tr>
<tr><td align="left">012_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   3.98<td>   3.18<td>2<td>76<td>222<td>26.91<td>42.09<td>108.13<td>  0.778</tr>
<tr><td align="left">012_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  37.37<td>  29.87<td>2<td>76<td>222<td>17.66<td>42.01<td>110.50<td>  0.781</tr>
<tr><td align="left">012_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   6.46<td>   5.16<td>2<td>76<td>222<td>23.03<td>42.18<td>109.99<td>  0.780</tr>
<tr><td align="left">012_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 188.63<td> 150.75<td>2<td>76<td>222<td>22.12<td>42.29<td>110.25<td>  0.782</tr>
<tr><td align="left">012_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  10.85<td>   8.67<td>2<td>76<td>222<td>20.71<td>42.21<td>110.06<td>  0.781</tr>
<tr><td align="left">012_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  17.70<td>  14.14<td>2<td>76<td>222<td>19.49<td>41.71<td>108.67<td>  0.787</tr>
<tr><td align="left">012_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   3.84<td>   3.07<td>2<td>76<td>222<td>26.91<td>42.06<td>108.09<td>  0.778</tr>
<tr><td align="left">012_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  32.96<td>  26.35<td>2<td>76<td>222<td>17.62<td>42.17<td>110.29<td>  0.781</tr>
<tr><td align="left">012_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   6.12<td>   4.89<td>2<td>76<td>222<td>25.09<td>42.23<td>106.90<td>  0.789</tr>
<tr><td align="left">012_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 102.88<td>  82.22<td>2<td>76<td>222<td>22.09<td>42.21<td>110.20<td>  0.782</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 013
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/013_480p.png)](https://drive.google.com/drive/folders/1BW78JWK1FURwVFlbO9wobWGxfvC5M-qt?usp=sharing)\
*__Figure 14__. First Frame of Sequence 013*

Raw Sequence Size:  9.86 GB\
Source: [HERE](https://drive.google.com/drive/folders/1BW78JWK1FURwVFlbO9wobWGxfvC5M-qt?usp=sharing)

<br>

*__Table 14__. Description of encoded videos using sequence 013 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">013_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   5.58<td>   4.46<td>1<td>299<td>0<td>54.46<td>35.38<td>175.29<td>  0.856</tr>
<tr><td align="left">013_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>  11.31<td>   9.04<td>1<td>299<td>0<td>53.43<td>35.12<td>175.35<td>  0.855</tr>
<tr><td align="left">013_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.37<td>   1.89<td>1<td>299<td>0<td>56.14<td>36.09<td>174.36<td>  0.853</tr>
<tr><td align="left">013_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  26.71<td>  21.35<td>1<td>299<td>0<td>52.27<td>34.95<td>175.62<td>  0.856</tr>
<tr><td align="left">013_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   3.48<td>   2.78<td>1<td>299<td>0<td>55.41<td>35.77<td>174.86<td>  0.854</tr>
<tr><td align="left">013_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  95.54<td>  76.36<td>1<td>299<td>0<td>54.33<td>34.69<td>176.14<td>  0.854</tr>
<tr><td align="left">013_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  14.09<td>  11.26<td>2<td>76<td>222<td>54.17<td>34.99<td>175.84<td>  0.855</tr>
<tr><td align="left">013_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  28.32<td>  22.63<td>2<td>76<td>222<td>53.22<td>34.85<td>175.97<td>  0.854</tr>
<tr><td align="left">013_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   6.83<td>   5.46<td>2<td>76<td>222<td>55.94<td>35.70<td>174.76<td>  0.852</tr>
<tr><td align="left">013_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  63.59<td>  50.82<td>2<td>76<td>222<td>52.28<td>34.70<td>176.35<td>  0.855</tr>
<tr><td align="left">013_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   9.11<td>   7.28<td>2<td>76<td>222<td>55.18<td>35.39<td>175.43<td>  0.853</tr>
<tr><td align="left">013_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 202.74<td> 162.03<td>2<td>180<td>118<td>54.32<td>34.62<td>176.58<td>  0.854</tr>
<tr><td align="left">013_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  13.17<td>  10.53<td>2<td>76<td>222<td>53.99<td>35.04<td>175.69<td>  0.855</tr>
<tr><td align="left">013_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  26.20<td>  20.94<td>2<td>76<td>222<td>49.75<td>34.81<td>176.76<td>  0.853</tr>
<tr><td align="left">013_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   6.74<td>   5.39<td>2<td>76<td>222<td>55.86<td>35.77<td>174.58<td>  0.852</tr>
<tr><td align="left">013_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  58.83<td>  47.02<td>2<td>76<td>222<td>52.15<td>34.72<td>176.24<td>  0.855</tr>
<tr><td align="left">013_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   9.10<td>   7.28<td>2<td>76<td>222<td>48.39<td>35.30<td>179.26<td>  0.848</tr>
<tr><td align="left">013_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 199.43<td> 159.38<td>2<td>76<td>222<td>54.30<td>34.56<td>176.59<td>  0.854</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 014
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/014_480p.png)](https://drive.google.com/drive/folders/1Jjdrihc_lPh_ABPRZVbvOGJaPsLwYji5?usp=share_link)\
*__Figure 15__. First Frame of Sequence 014*

Raw Sequence Size: 11.99 GB\
Source: [HERE](https://drive.google.com/drive/folders/1Jjdrihc_lPh_ABPRZVbvOGJaPsLwYji5?usp=share_link)

<br>

*__Table 15__. Description of encoded videos using sequence 014 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">014_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   5.98<td>   4.78<td>1<td>299<td>0<td>10.06<td>31.85<td>584.60<td>  0.547</tr>
<tr><td align="left">014_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>  10.93<td>   8.73<td>1<td>299<td>0<td>10.06<td>31.96<td>585.51<td>  0.527</tr>
<tr><td align="left">014_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.59<td>   2.07<td>1<td>299<td>0<td>11.02<td>32.06<td>580.63<td>  0.526</tr>
<tr><td align="left">014_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  24.18<td>  19.32<td>2<td>298<td>0<td>11.47<td>31.67<td>587.41<td>  0.544</tr>
<tr><td align="left">014_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   4.03<td>   3.22<td>1<td>299<td>0<td>10.31<td>32.00<td>582.10<td>  0.528</tr>
<tr><td align="left">014_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  86.86<td>  69.42<td>1<td>299<td>0<td>18.48<td>31.48<td>587.95<td>  0.534</tr>
<tr><td align="left">014_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  12.75<td>  10.19<td>2<td>183<td>115<td>10.16<td>31.84<td>584.48<td>  0.548</tr>
<tr><td align="left">014_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  25.68<td>  20.53<td>2<td>214<td>84<td>10.11<td>31.89<td>584.93<td>  0.527</tr>
<tr><td align="left">014_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   6.54<td>   5.22<td>2<td>101<td>197<td>11.11<td>32.06<td>580.39<td>  0.525</tr>
<tr><td align="left">014_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  57.97<td>  46.33<td>2<td>244<td>54<td>11.55<td>31.65<td>587.61<td>  0.544</tr>
<tr><td align="left">014_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   8.44<td>   6.74<td>2<td>135<td>163<td>10.37<td>32.04<td>582.46<td>  0.528</tr>
<tr><td align="left">014_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 191.13<td> 152.75<td>32<td>208<td>60<td>18.69<td>31.55<td>588.04<td>  0.534</tr>
<tr><td align="left">014_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  13.28<td>  10.61<td>2<td>76<td>222<td>10.23<td>31.80<td>585.24<td>  0.546</tr>
<tr><td align="left">014_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  26.59<td>  21.25<td>2<td>76<td>222<td>10.20<td>31.82<td>585.55<td>  0.526</tr>
<tr><td align="left">014_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   6.84<td>   5.46<td>2<td>76<td>222<td>11.08<td>32.03<td>579.81<td>  0.525</tr>
<tr><td align="left">014_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  60.35<td>  48.23<td>2<td>76<td>222<td>11.58<td>31.60<td>587.92<td>  0.544</tr>
<tr><td align="left">014_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   8.93<td>   7.14<td>2<td>76<td>222<td>10.53<td>31.96<td>582.65<td>  0.527</tr>
<tr><td align="left">014_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 204.92<td> 163.77<td>2<td>76<td>222<td>18.72<td>31.43<td>588.46<td>  0.533</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 015
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/015_480p.png)](https://drive.google.com/drive/folders/1quWkHPelIIjqnNuEzBwE_PXGWTcGsRHj?usp=share_link)\
*__Figure 16__. First Frame of Sequence 015*

Raw Sequence Size:  9.66 GB\
Source: [HERE](https://drive.google.com/drive/folders/1quWkHPelIIjqnNuEzBwE_PXGWTcGsRHj?usp=share_link)

<br>

*__Table 16__. Description of encoded videos using sequence 015 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">015_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   5.39<td>   4.30<td>1<td>299<td>0<td> 4.10<td>30.94<td>558.17<td>  0.641</tr>
<tr><td align="left">015_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>  10.87<td>   8.69<td>1<td>299<td>0<td> 3.65<td>30.83<td>558.64<td>  0.629</tr>
<tr><td align="left">015_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.30<td>   1.84<td>1<td>299<td>0<td> 7.12<td>31.30<td>553.79<td>  0.626</tr>
<tr><td align="left">015_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  24.74<td>  19.77<td>1<td>299<td>0<td> 3.21<td>30.81<td>558.68<td>  0.641</tr>
<tr><td align="left">015_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   3.48<td>   2.78<td>1<td>299<td>0<td> 5.30<td>31.13<td>556.94<td>  0.628</tr>
<tr><td align="left">015_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  89.21<td>  71.29<td>1<td>299<td>0<td> 2.88<td>30.70<td>559.11<td>  0.634</tr>
<tr><td align="left">015_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  14.58<td>  11.65<td>2<td>81<td>217<td> 4.08<td>30.84<td>558.74<td>  0.640</tr>
<tr><td align="left">015_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  29.20<td>  23.34<td>2<td>89<td>209<td> 3.65<td>30.78<td>558.78<td>  0.628</tr>
<tr><td align="left">015_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   6.82<td>   5.45<td>2<td>76<td>222<td> 7.11<td>31.24<td>553.44<td>  0.624</tr>
<tr><td align="left">015_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  65.65<td>  52.47<td>2<td>92<td>206<td> 3.20<td>30.73<td>559.86<td>  0.640</tr>
<tr><td align="left">015_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   9.25<td>   7.39<td>2<td>77<td>221<td> 5.27<td>31.09<td>556.88<td>  0.627</tr>
<tr><td align="left">015_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 207.96<td> 166.20<td>5<td>85<td>210<td> 2.86<td>30.72<td>560.19<td>  0.633</tr>
<tr><td align="left">015_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  13.12<td>  10.49<td>2<td>76<td>222<td> 4.09<td>30.85<td>558.46<td>  0.640</tr>
<tr><td align="left">015_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  26.25<td>  20.98<td>2<td>76<td>222<td> 3.59<td>30.76<td>558.10<td>  0.629</tr>
<tr><td align="left">015_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   6.75<td>   5.39<td>2<td>76<td>222<td> 7.10<td>31.22<td>553.24<td>  0.625</tr>
<tr><td align="left">015_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  59.08<td>  47.22<td>2<td>76<td>222<td> 3.20<td>30.74<td>559.63<td>  0.640</tr>
<tr><td align="left">015_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   9.13<td>   7.29<td>2<td>76<td>222<td> 5.33<td>31.04<td>555.86<td>  0.628</tr>
<tr><td align="left">015_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 198.90<td> 158.96<td>2<td>76<td>222<td> 2.87<td>30.65<td>560.13<td>  0.633</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 016
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/016_480p.png)](https://drive.google.com/drive/folders/1Bvk4CJpKb820Iwje3RbnG0SoilaKO8lc?usp=share_link)\
*__Figure 17__. First Frame of Sequence 016*

Raw Sequence Size:  7.85 GB\
Source: [HERE](https://drive.google.com/drive/folders/1Bvk4CJpKb820Iwje3RbnG0SoilaKO8lc?usp=share_link)

<br>

*__Table 17__. Description of encoded videos using sequence 016 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">016_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   5.27<td>   4.21<td>1<td>299<td>0<td> 5.92<td>34.18<td>116.70<td>  0.718</tr>
<tr><td align="left">016_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>   9.79<td>   7.82<td>1<td>299<td>0<td> 4.59<td>34.09<td>116.99<td>  0.722</tr>
<tr><td align="left">016_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.41<td>   1.93<td>1<td>299<td>0<td>13.61<td>34.68<td>112.71<td>  0.717</tr>
<tr><td align="left">016_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  20.86<td>  16.67<td>1<td>299<td>0<td> 3.66<td>34.10<td>117.15<td>  0.719</tr>
<tr><td align="left">016_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   3.54<td>   2.83<td>1<td>299<td>0<td> 8.59<td>34.35<td>115.55<td>  0.719</tr>
<tr><td align="left">016_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  92.24<td>  73.72<td>1<td>299<td>0<td> 3.55<td>34.03<td>117.36<td>  0.721</tr>
<tr><td align="left">016_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  13.65<td>  10.91<td>2<td>76<td>222<td> 5.89<td>34.19<td>116.62<td>  0.718</tr>
<tr><td align="left">016_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  27.78<td>  22.20<td>2<td>76<td>222<td> 4.60<td>34.10<td>117.20<td>  0.722</tr>
<tr><td align="left">016_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   6.71<td>   5.37<td>2<td>76<td>222<td>13.45<td>34.70<td>112.56<td>  0.716</tr>
<tr><td align="left">016_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  60.62<td>  48.45<td>2<td>76<td>222<td> 3.68<td>34.00<td>117.61<td>  0.718</tr>
<tr><td align="left">016_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   9.01<td>   7.20<td>2<td>76<td>222<td> 8.54<td>34.49<td>115.25<td>  0.719</tr>
<tr><td align="left">016_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 196.63<td> 157.15<td>3<td>76<td>221<td> 3.55<td>34.04<td>117.60<td>  0.720</tr>
<tr><td align="left">016_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  13.24<td>  10.58<td>2<td>76<td>222<td> 5.89<td>34.14<td>116.50<td>  0.718</tr>
<tr><td align="left">016_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  26.48<td>  21.16<td>2<td>76<td>222<td> 4.28<td>34.06<td>115.91<td>  0.724</tr>
<tr><td align="left">016_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   6.64<td>   5.30<td>2<td>76<td>222<td>13.47<td>34.63<td>112.43<td>  0.717</tr>
<tr><td align="left">016_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  59.19<td>  47.31<td>2<td>76<td>222<td> 3.68<td>34.01<td>117.44<td>  0.719</tr>
<tr><td align="left">016_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   8.66<td>   6.92<td>2<td>76<td>222<td> 8.49<td>34.40<td>113.02<td>  0.724</tr>
<tr><td align="left">016_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 196.70<td> 157.20<td>2<td>76<td>222<td> 3.56<td>33.99<td>117.64<td>  0.720</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 017
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/017_480p.png)](https://drive.google.com/drive/folders/17sLpoKqUAQhiLmESB4niZ0b9vrQ51YHG?usp=share_link)\
*__Figure 18__. First Frame of Sequence 017*

Raw Sequence Size:  9.82 GB\
Source: [HERE](https://drive.google.com/drive/folders/17sLpoKqUAQhiLmESB4niZ0b9vrQ51YHG?usp=share_link)

<br>

*__Table 18__. Description of encoded videos using sequence 017 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">017_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   4.97<td>   3.97<td>1<td>299<td>0<td>67.31<td>38.93<td>40.24<td>  0.953</tr>
<tr><td align="left">017_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>  11.46<td>   9.16<td>1<td>299<td>0<td>65.74<td>38.42<td>40.73<td>  0.952</tr>
<tr><td align="left">017_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.43<td>   1.94<td>1<td>299<td>0<td>69.74<td>40.11<td>38.72<td>  0.952</tr>
<tr><td align="left">017_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  26.48<td>  21.16<td>1<td>299<td>0<td>63.45<td>38.18<td>41.05<td>  0.952</tr>
<tr><td align="left">017_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   3.04<td>   2.43<td>1<td>299<td>0<td>68.12<td>39.52<td>39.67<td>  0.952</tr>
<tr><td align="left">017_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  99.39<td>  79.43<td>1<td>299<td>0<td>60.38<td>37.96<td>41.37<td>  0.951</tr>
<tr><td align="left">017_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  14.05<td>  11.23<td>2<td>76<td>222<td>66.92<td>38.34<td>40.70<td>  0.952</tr>
<tr><td align="left">017_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  28.26<td>  22.58<td>2<td>76<td>222<td>65.51<td>38.19<td>41.04<td>  0.951</tr>
<tr><td align="left">017_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   6.42<td>   5.13<td>2<td>76<td>222<td>69.41<td>39.49<td>39.15<td>  0.951</tr>
<tr><td align="left">017_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  63.38<td>  50.66<td>2<td>76<td>222<td>63.48<td>37.98<td>41.28<td>  0.952</tr>
<tr><td align="left">017_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   9.07<td>   7.25<td>2<td>76<td>222<td>67.69<td>38.92<td>40.11<td>  0.951</tr>
<tr><td align="left">017_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 206.04<td> 164.67<td>3<td>78<td>219<td>60.30<td>37.83<td>41.67<td>  0.951</tr>
<tr><td align="left">017_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  13.17<td>  10.53<td>2<td>76<td>222<td>66.75<td>38.51<td>40.64<td>  0.952</tr>
<tr><td align="left">017_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  26.26<td>  20.98<td>2<td>76<td>222<td>61.38<td>38.21<td>41.72<td>  0.950</tr>
<tr><td align="left">017_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   6.48<td>   5.18<td>2<td>76<td>222<td>69.34<td>39.60<td>39.14<td>  0.951</tr>
<tr><td align="left">017_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  59.25<td>  47.36<td>2<td>76<td>222<td>63.24<td>38.05<td>41.23<td>  0.952</tr>
<tr><td align="left">017_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   8.89<td>   7.11<td>2<td>76<td>222<td>61.11<td>38.87<td>42.36<td>  0.946</tr>
<tr><td align="left">017_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 198.57<td> 158.69<td>2<td>76<td>222<td>61.11<td>38.87<td>41.67<td>  0.946</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 018
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/018_480p.png)](https://drive.google.com/drive/folders/1gpKwiGLZ03IV0PIWQlB5eEfxo-rsNlKN?usp=sharing)\
*__Figure 19__. First Frame of Sequence 018*

Raw Sequence Size:  9.73 GB\
Source: [HERE](https://drive.google.com/drive/folders/1gpKwiGLZ03IV0PIWQlB5eEfxo-rsNlKN?usp=sharing)

<br>

*__Table 19__. Description of encoded videos using sequence 018 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">018_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   5.46<td>   4.36<td>1<td>299<td>0<td> 3.53<td>43.35<td>147.74<td>  0.719</tr>
<tr><td align="left">018_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>  10.39<td>   8.30<td>1<td>299<td>0<td> 2.85<td>42.68<td>148.51<td>  0.721</tr>
<tr><td align="left">018_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.39<td>   1.91<td>1<td>299<td>0<td> 8.69<td>43.39<td>140.17<td>  0.716</tr>
<tr><td align="left">018_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  20.69<td>  16.53<td>1<td>299<td>0<td> 2.23<td>42.29<td>148.84<td>  0.721</tr>
<tr><td align="left">018_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   3.58<td>   2.86<td>1<td>299<td>0<td> 5.32<td>43.09<td>145.07<td>  0.720</tr>
<tr><td align="left">018_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  78.01<td>  62.35<td>1<td>299<td>0<td> 2.18<td>41.99<td>149.04<td>  0.721</tr>
<tr><td align="left">018_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  11.53<td>   9.22<td>2<td>76<td>222<td> 3.47<td>42.07<td>147.41<td>  0.720</tr>
<tr><td align="left">018_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  21.83<td>  17.45<td>2<td>76<td>222<td> 2.83<td>41.45<td>148.46<td>  0.721</tr>
<tr><td align="left">018_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   4.49<td>   3.59<td>2<td>76<td>222<td> 8.65<td>42.32<td>139.85<td>  0.716</tr>
<tr><td align="left">018_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  48.77<td>  38.98<td>2<td>76<td>222<td> 2.23<td>41.88<td>149.00<td>  0.721</tr>
<tr><td align="left">018_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   7.30<td>   5.83<td>2<td>76<td>222<td> 5.26<td>41.58<td>144.74<td>  0.720</tr>
<tr><td align="left">018_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 193.62<td> 154.74<td>2<td>77<td>221<td> 2.21<td>41.90<td>149.13<td>  0.721</tr>
<tr><td align="left">018_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  12.29<td>   9.82<td>2<td>76<td>222<td> 3.48<td>42.23<td>147.29<td>  0.720</tr>
<tr><td align="left">018_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  24.02<td>  19.20<td>2<td>76<td>222<td> 2.69<td>41.36<td>148.14<td>  0.721</tr>
<tr><td align="left">018_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   3.97<td>   3.17<td>2<td>76<td>222<td> 8.65<td>42.27<td>139.91<td>  0.717</tr>
<tr><td align="left">018_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  54.57<td>  43.61<td>2<td>76<td>222<td> 2.21<td>41.94<td>148.76<td>  0.721</tr>
<tr><td align="left">018_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   6.98<td>   5.58<td>2<td>76<td>222<td> 5.05<td>41.62<td>144.42<td>  0.721</tr>
<tr><td align="left">018_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 192.40<td> 153.76<td>2<td>76<td>222<td> 5.05<td>41.62<td>149.01<td>  0.721</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 019
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/019_480p.png)](https://drive.google.com/drive/folders/1cKPTbkDro_DCzgZKtirpv59T86NO0ZDv?usp=share_link)\
*__Figure 20__. First Frame of Sequence 019*

Raw Sequence Size: 15.04 GB\
Source: [HERE](https://drive.google.com/drive/folders/1cKPTbkDro_DCzgZKtirpv59T86NO0ZDv?usp=share_link)

<br>

*__Table 20__. Description of encoded videos using sequence 019 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">019_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   5.57<td>   4.45<td>1<td>299<td>0<td>22.77<td>35.25<td>90.84<td>  0.844</tr>
<tr><td align="left">019_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>  10.31<td>   8.24<td>1<td>299<td>0<td>19.43<td>34.90<td>93.77<td>  0.853</tr>
<tr><td align="left">019_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.27<td>   1.81<td>1<td>299<td>0<td>37.30<td>36.43<td>77.16<td>  0.850</tr>
<tr><td align="left">019_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  21.14<td>  16.90<td>1<td>299<td>0<td>14.73<td>34.57<td>95.96<td>  0.846</tr>
<tr><td align="left">019_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   3.59<td>   2.87<td>1<td>299<td>0<td>30.01<td>35.79<td>85.07<td>  0.851</tr>
<tr><td align="left">019_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  81.13<td>  64.84<td>1<td>299<td>0<td> 8.64<td>34.15<td>97.23<td>  0.851</tr>
<tr><td align="left">019_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  12.75<td>  10.19<td>2<td>76<td>222<td>22.45<td>35.19<td>90.40<td>  0.845</tr>
<tr><td align="left">019_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  26.01<td>  20.78<td>2<td>76<td>222<td>19.15<td>34.90<td>93.44<td>  0.853</tr>
<tr><td align="left">019_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   5.55<td>   4.43<td>2<td>76<td>222<td>36.91<td>36.25<td>77.12<td>  0.849</tr>
<tr><td align="left">019_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  59.04<td>  47.19<td>2<td>76<td>222<td>14.58<td>34.51<td>95.98<td>  0.846</tr>
<tr><td align="left">019_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   8.40<td>   6.71<td>2<td>76<td>222<td>29.52<td>35.73<td>84.69<td>  0.851</tr>
<tr><td align="left">019_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 209.55<td> 167.48<td>2<td>76<td>222<td> 8.51<td>34.22<td>97.44<td>  0.851</tr>
<tr><td align="left">019_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  12.81<td>  10.24<td>2<td>76<td>222<td>22.48<td>35.16<td>90.46<td>  0.845</tr>
<tr><td align="left">019_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  25.80<td>  20.62<td>2<td>76<td>222<td>19.53<td>34.83<td>93.70<td>  0.853</tr>
<tr><td align="left">019_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   5.50<td>   4.40<td>2<td>76<td>222<td>36.93<td>36.25<td>77.12<td>  0.850</tr>
<tr><td align="left">019_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  58.68<td>  46.90<td>2<td>76<td>222<td>14.59<td>34.49<td>95.87<td>  0.846</tr>
<tr><td align="left">019_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   8.30<td>   6.63<td>2<td>76<td>222<td>28.49<td>35.61<td>86.60<td>  0.848</tr>
<tr><td align="left">019_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 198.21<td> 158.41<td>2<td>76<td>222<td> 8.58<td>34.08<td>97.33<td>  0.851</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 020
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/020_480p.png)](https://drive.google.com/drive/folders/1Ss7JO2Do-UcA1uGSFQo-qp_InNCCihuu?usp=share_link)\
*__Figure 21__. First Frame of Sequence 020*

Raw Sequence Size:  6.48 GB\
Source: [HERE](https://drive.google.com/drive/folders/1Ss7JO2Do-UcA1uGSFQo-qp_InNCCihuu?usp=share_link)

<br>

*__Table 21__. Description of encoded videos using sequence 020 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">020_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   5.31<td>   4.24<td>1<td>299<td>0<td>73.82<td>44.28<td>18.59<td>  0.970</tr>
<tr><td align="left">020_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>   9.13<td>   7.30<td>1<td>299<td>0<td>70.52<td>44.20<td>18.75<td>  0.970</tr>
<tr><td align="left">020_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.48<td>   1.98<td>1<td>299<td>0<td>80.24<td>45.21<td>17.42<td>  0.970</tr>
<tr><td align="left">020_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  19.64<td>  15.70<td>1<td>299<td>0<td>65.74<td>44.24<td>18.91<td>  0.971</tr>
<tr><td align="left">020_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   3.25<td>   2.59<td>1<td>299<td>0<td>77.60<td>44.70<td>18.15<td>  0.970</tr>
<tr><td align="left">020_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  82.10<td>  65.62<td>1<td>299<td>0<td>59.28<td>44.07<td>19.07<td>  0.970</tr>
<tr><td align="left">020_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  12.08<td>   9.66<td>2<td>76<td>222<td>73.40<td>43.47<td>18.86<td>  0.970</tr>
<tr><td align="left">020_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  22.52<td>  17.99<td>2<td>76<td>222<td>70.24<td>43.59<td>18.96<td>  0.970</tr>
<tr><td align="left">020_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   3.70<td>   2.96<td>2<td>76<td>222<td>79.72<td>43.94<td>17.70<td>  0.969</tr>
<tr><td align="left">020_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  50.18<td>  40.11<td>2<td>76<td>222<td>65.68<td>43.58<td>19.14<td>  0.970</tr>
<tr><td align="left">020_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   7.14<td>   5.70<td>2<td>76<td>222<td>77.10<td>43.68<td>18.45<td>  0.970</tr>
<tr><td align="left">020_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 192.73<td> 154.03<td>2<td>76<td>222<td>59.28<td>43.80<td>19.17<td>  0.970</tr>
<tr><td align="left">020_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  12.70<td>  10.15<td>2<td>76<td>222<td>73.36<td>43.57<td>18.79<td>  0.970</tr>
<tr><td align="left">020_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  26.28<td>  21.00<td>2<td>76<td>222<td>66.38<td>43.60<td>19.82<td>  0.969</tr>
<tr><td align="left">020_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   4.10<td>   3.28<td>2<td>76<td>222<td>79.70<td>43.91<td>17.69<td>  0.969</tr>
<tr><td align="left">020_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  59.66<td>  47.68<td>2<td>76<td>222<td>65.59<td>43.77<td>19.06<td>  0.970</tr>
<tr><td align="left">020_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   7.35<td>   5.88<td>2<td>76<td>222<td>70.31<td>43.42<td>21.38<td>  0.965</tr>
<tr><td align="left">020_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 197.93<td> 158.18<td>2<td>76<td>222<td>59.24<td>43.73<td>19.16<td>  0.970</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 021
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/021_480p.png)](https://drive.google.com/drive/folders/1GN4c0wgolAYQr51oFJvyxQR2iAQCgWS7?usp=share_link)\
*__Figure 22__. First Frame of Sequence 021*

Raw Sequence Size:  8.72 GB\
Source: [HERE](https://drive.google.com/drive/folders/1GN4c0wgolAYQr51oFJvyxQR2iAQCgWS7?usp=share_link)

<br>

*__Table 22__. Description of encoded videos using sequence 021 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">021_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   5.10<td>   4.07<td>1<td>299<td>0<td> 8.72<td>34.30<td>457.92<td>  0.425</tr>
<tr><td align="left">021_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>   9.12<td>   7.29<td>1<td>299<td>0<td> 8.19<td>34.24<td>458.15<td>  0.420</tr>
<tr><td align="left">021_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.31<td>   1.84<td>1<td>299<td>0<td> 9.88<td>34.55<td>451.79<td>  0.412</tr>
<tr><td align="left">021_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  18.44<td>  14.74<td>1<td>299<td>0<td> 7.23<td>34.25<td>457.88<td>  0.427</tr>
<tr><td align="left">021_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   3.48<td>   2.78<td>1<td>299<td>0<td> 9.41<td>34.38<td>456.26<td>  0.416</tr>
<tr><td align="left">021_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  67.22<td>  53.72<td>1<td>299<td>0<td> 5.56<td>34.19<td>457.73<td>  0.423</tr>
<tr><td align="left">021_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  13.05<td>  10.43<td>2<td>78<td>220<td> 8.71<td>34.20<td>457.87<td>  0.425</tr>
<tr><td align="left">021_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  25.59<td>  20.45<td>2<td>80<td>218<td> 8.21<td>34.24<td>458.17<td>  0.420</tr>
<tr><td align="left">021_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   6.14<td>   4.91<td>2<td>76<td>222<td> 9.80<td>34.69<td>450.46<td>  0.413</tr>
<tr><td align="left">021_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  57.87<td>  46.25<td>2<td>85<td>213<td> 7.28<td>34.12<td>458.58<td>  0.426</tr>
<tr><td align="left">021_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   8.43<td>   6.74<td>2<td>76<td>222<td> 9.38<td>34.49<td>455.89<td>  0.417</tr>
<tr><td align="left">021_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 188.07<td> 150.31<td>4<td>78<td>218<td> 5.63<td>34.13<td>458.22<td>  0.423</tr>
<tr><td align="left">021_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  12.79<td>  10.22<td>2<td>76<td>222<td> 8.66<td>34.24<td>457.11<td>  0.426</tr>
<tr><td align="left">021_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  26.03<td>  20.81<td>2<td>76<td>222<td> 8.12<td>34.17<td>457.77<td>  0.420</tr>
<tr><td align="left">021_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   6.30<td>   5.04<td>2<td>76<td>222<td> 9.81<td>34.57<td>450.31<td>  0.414</tr>
<tr><td align="left">021_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  58.69<td>  46.91<td>2<td>76<td>222<td> 7.24<td>34.15<td>458.07<td>  0.426</tr>
<tr><td align="left">021_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   8.30<td>   6.63<td>2<td>76<td>222<td> 9.22<td>34.36<td>455.82<td>  0.416</tr>
<tr><td align="left">021_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 197.46<td> 157.81<td>2<td>76<td>222<td> 5.60<td>34.12<td>458.16<td>  0.423</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 022
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/022_480p.png)](https://drive.google.com/drive/folders/1yKmK7s2gx4roQmGLwitOnJn0Ouq4TCaA?usp=share_link)\
*__Figure 23__. First Frame of Sequence 022*

Raw Sequence Size:  5.13 GB\
Source: [HERE](https://drive.google.com/drive/folders/1yKmK7s2gx4roQmGLwitOnJn0Ouq4TCaA?usp=share_link)

<br>

*__Table 23__. Description of encoded videos using sequence 022 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">022_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   5.17<td>   4.13<td>1<td>299<td>0<td> 2.92<td>32.46<td>753.16<td>  0.692</tr>
<tr><td align="left">022_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>   9.78<td>   7.82<td>1<td>299<td>0<td> 3.06<td>32.34<td>753.35<td>  0.675</tr>
<tr><td align="left">022_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.30<td>   1.84<td>1<td>299<td>0<td> 4.33<td>32.40<td>754.37<td>  0.674</tr>
<tr><td align="left">022_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  20.06<td>  16.04<td>1<td>299<td>0<td> 4.83<td>32.44<td>753.29<td>  0.692</tr>
<tr><td align="left">022_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   3.45<td>   2.76<td>1<td>299<td>0<td> 3.32<td>32.42<td>753.93<td>  0.675</tr>
<tr><td align="left">022_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  74.14<td>  59.26<td>1<td>299<td>0<td>25.62<td>32.34<td>753.08<td>  0.683</tr>
<tr><td align="left">022_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  13.14<td>  10.50<td>2<td>78<td>220<td> 2.88<td>32.31<td>754.01<td>  0.692</tr>
<tr><td align="left">022_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  25.72<td>  20.55<td>2<td>78<td>220<td> 3.04<td>32.29<td>752.73<td>  0.675</tr>
<tr><td align="left">022_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   6.05<td>   4.83<td>2<td>76<td>222<td> 4.30<td>32.36<td>753.21<td>  0.672</tr>
<tr><td align="left">022_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  58.10<td>  46.44<td>2<td>105<td>193<td> 4.83<td>32.33<td>753.83<td>  0.691</tr>
<tr><td align="left">022_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   8.53<td>   6.81<td>2<td>77<td>221<td> 3.32<td>32.34<td>754.14<td>  0.674</tr>
<tr><td align="left">022_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 183.78<td> 146.88<td>3<td>252<td>45<td>25.69<td>32.36<td>753.23<td>  0.683</tr>
<tr><td align="left">022_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  13.17<td>  10.52<td>2<td>76<td>222<td> 2.89<td>32.32<td>753.59<td>  0.692</tr>
<tr><td align="left">022_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  26.37<td>  21.07<td>2<td>76<td>222<td> 3.01<td>32.28<td>752.62<td>  0.675</tr>
<tr><td align="left">022_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   5.54<td>   4.43<td>2<td>76<td>222<td> 4.29<td>32.34<td>752.55<td>  0.673</tr>
<tr><td align="left">022_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  56.80<td>  45.40<td>2<td>76<td>222<td> 4.84<td>32.34<td>753.69<td>  0.692</tr>
<tr><td align="left">022_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   8.26<td>   6.60<td>2<td>76<td>222<td> 3.20<td>32.31<td>753.81<td>  0.674</tr>
<tr><td align="left">022_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 170.60<td> 136.34<td>2<td>76<td>222<td>25.70<td>32.30<td>753.27<td>  0.683</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 023
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/023_480p.png)](https://drive.google.com/drive/folders/1_E4fP5i9RE3mQHtGA5vAcDDOQA2LESm1?usp=share_link)\
*__Figure 24__. First Frame of Sequence 023*

Raw Sequence Size:  7.48 GB\
Source: [HERE](https://drive.google.com/drive/folders/1_E4fP5i9RE3mQHtGA5vAcDDOQA2LESm1?usp=share_link)

<br>

*__Table 24__. Description of encoded videos using sequence 023 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">023_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   5.10<td>   4.08<td>1<td>299<td>0<td>15.36<td>38.99<td>152.77<td>  0.700</tr>
<tr><td align="left">023_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>  10.44<td>   8.34<td>1<td>299<td>0<td>12.70<td>38.97<td>153.01<td>  0.709</tr>
<tr><td align="left">023_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.15<td>   1.72<td>1<td>299<td>0<td>24.81<td>39.52<td>149.31<td>  0.703</tr>
<tr><td align="left">023_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  21.59<td>  17.25<td>1<td>299<td>0<td> 9.83<td>38.98<td>153.02<td>  0.702</tr>
<tr><td align="left">023_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   3.15<td>   2.52<td>1<td>299<td>0<td>19.75<td>39.17<td>152.05<td>  0.706</tr>
<tr><td align="left">023_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  74.61<td>  59.63<td>1<td>299<td>0<td> 7.46<td>38.87<td>152.90<td>  0.706</tr>
<tr><td align="left">023_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  12.12<td>   9.69<td>2<td>76<td>222<td>15.27<td>38.56<td>152.91<td>  0.700</tr>
<tr><td align="left">023_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  22.79<td>  18.22<td>2<td>76<td>222<td>12.60<td>38.78<td>153.00<td>  0.709</tr>
<tr><td align="left">023_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   5.34<td>   4.26<td>2<td>76<td>222<td>24.57<td>39.30<td>148.79<td>  0.703</tr>
<tr><td align="left">023_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  48.51<td>  38.77<td>2<td>76<td>222<td> 9.81<td>38.63<td>153.44<td>  0.702</tr>
<tr><td align="left">023_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   7.62<td>   6.09<td>2<td>76<td>222<td>19.58<td>38.97<td>151.88<td>  0.707</tr>
<tr><td align="left">023_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 188.43<td> 150.59<td>2<td>76<td>222<td> 7.43<td>38.76<td>153.12<td>  0.706</tr>
<tr><td align="left">023_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  11.99<td>   9.59<td>2<td>76<td>222<td>15.26<td>38.67<td>152.57<td>  0.701</tr>
<tr><td align="left">023_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  24.50<td>  19.58<td>2<td>76<td>222<td>12.67<td>38.79<td>153.93<td>  0.708</tr>
<tr><td align="left">023_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   5.28<td>   4.22<td>2<td>76<td>222<td>24.62<td>39.28<td>148.80<td>  0.703</tr>
<tr><td align="left">023_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  49.29<td>  39.39<td>2<td>76<td>222<td> 9.79<td>38.78<td>153.07<td>  0.702</tr>
<tr><td align="left">023_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   7.42<td>   5.93<td>2<td>76<td>222<td>19.50<td>38.84<td>154.75<td>  0.704</tr>
<tr><td align="left">023_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 149.82<td> 119.73<td>2<td>76<td>222<td> 7.44<td>38.76<td>153.01<td>  0.706</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 024
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/024_480p.png)](https://drive.google.com/drive/folders/1746B8UPJR77UmERnP9as62Z6PhSLq-3M?usp=share_link)\
*__Figure 25__. First Frame of Sequence 024*

Raw Sequence Size: 19.74 GB\
Source: [HERE](https://drive.google.com/drive/folders/1746B8UPJR77UmERnP9as62Z6PhSLq-3M?usp=share_link)

<br>

*__Table 25__. Description of encoded videos using sequence 024 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">024_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   4.62<td>   3.69<td>1<td>299<td>0<td>95.07<td>44.56<td> 9.04<td>  0.994</tr>
<tr><td align="left">024_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>  10.22<td>   8.17<td>1<td>299<td>0<td>94.39<td>42.93<td> 9.97<td>  0.994</tr>
<tr><td align="left">024_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.33<td>   1.86<td>1<td>299<td>0<td>95.67<td>48.20<td> 7.92<td>  0.994</tr>
<tr><td align="left">024_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  21.32<td>  17.04<td>1<td>299<td>0<td>92.63<td>41.01<td>11.76<td>  0.994</tr>
<tr><td align="left">024_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   2.99<td>   2.39<td>1<td>299<td>0<td>95.49<td>46.56<td> 8.32<td>  0.994</tr>
<tr><td align="left">024_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  88.90<td>  71.05<td>1<td>299<td>0<td>84.57<td>38.55<td>16.01<td>  0.994</tr>
<tr><td align="left">024_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  13.77<td>  11.01<td>2<td>76<td>222<td>94.59<td>43.05<td> 9.74<td>  0.993</tr>
<tr><td align="left">024_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  28.19<td>  22.53<td>2<td>76<td>222<td>93.72<td>41.83<td>10.74<td>  0.994</tr>
<tr><td align="left">024_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   4.36<td>   3.48<td>2<td>76<td>222<td>94.96<td>46.10<td> 8.33<td>  0.993</tr>
<tr><td align="left">024_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  63.10<td>  50.43<td>2<td>76<td>222<td>91.84<td>40.17<td>12.67<td>  0.993</tr>
<tr><td align="left">024_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   8.80<td>   7.03<td>2<td>76<td>222<td>94.89<td>44.70<td> 8.87<td>  0.993</tr>
<tr><td align="left">024_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 257.97<td> 206.17<td>2<td>227<td>71<td>82.64<td>38.22<td>17.23<td>  0.993</tr>
<tr><td align="left">024_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  12.99<td>  10.38<td>2<td>76<td>222<td>94.41<td>43.40<td> 9.61<td>  0.993</tr>
<tr><td align="left">024_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  26.29<td>  21.01<td>2<td>76<td>222<td>86.29<td>41.74<td>11.45<td>  0.993</tr>
<tr><td align="left">024_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   4.67<td>   3.73<td>2<td>76<td>222<td>94.89<td>46.46<td> 8.28<td>  0.993</tr>
<tr><td align="left">024_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  59.19<td>  47.30<td>2<td>76<td>222<td>91.72<td>40.33<td>12.55<td>  0.993</tr>
<tr><td align="left">024_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   8.70<td>   6.95<td>2<td>76<td>222<td>82.71<td>43.63<td>11.62<td>  0.990</tr>
<tr><td align="left">024_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 197.39<td> 157.75<td>2<td>76<td>222<td>83.68<td>38.10<td>17.05<td>  0.993</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 025
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/025_480p.png)](https://drive.google.com/drive/folders/1PQtP-u0U8sFXp384uS6vTRnnU8lxnf00?usp=share_link)\
*__Figure 26__. First Frame of Sequence 025*

Raw Sequence Size: 24.69 GB\
Source: [HERE](https://drive.google.com/drive/folders/1PQtP-u0U8sFXp384uS6vTRnnU8lxnf00?usp=share_link)

<br>

*__Table 26__. Description of encoded videos using sequence 025 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">025_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   4.97<td>   3.97<td>1<td>299<td>0<td>77.81<td>38.32<td>15.39<td>  0.974</tr>
<tr><td align="left">025_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>  10.35<td>   8.27<td>1<td>299<td>0<td>77.06<td>37.00<td>18.81<td>  0.974</tr>
<tr><td align="left">025_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.42<td>   1.93<td>1<td>299<td>0<td>71.91<td>41.06<td>11.30<td>  0.974</tr>
<tr><td align="left">025_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  19.47<td>  15.56<td>1<td>299<td>0<td>72.24<td>35.37<td>25.61<td>  0.973</tr>
<tr><td align="left">025_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   3.78<td>   3.02<td>1<td>299<td>0<td>76.40<td>39.85<td>12.76<td>  0.974</tr>
<tr><td align="left">025_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  71.63<td>  57.25<td>1<td>299<td>0<td>55.57<td>33.23<td>40.64<td>  0.972</tr>
<tr><td align="left">025_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  12.62<td>  10.09<td>2<td>290<td>8<td>77.26<td>37.90<td>15.96<td>  0.973</tr>
<tr><td align="left">025_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  25.87<td>  20.68<td>2<td>298<td>0<td>76.55<td>36.69<td>19.35<td>  0.974</tr>
<tr><td align="left">025_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   6.54<td>   5.23<td>2<td>148<td>150<td>71.62<td>40.49<td>11.60<td>  0.973</tr>
<tr><td align="left">025_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  58.67<td>  46.89<td>2<td>298<td>0<td>71.83<td>35.02<td>26.56<td>  0.971</tr>
<tr><td align="left">025_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   8.78<td>   7.02<td>2<td>152<td>146<td>76.00<td>39.32<td>13.22<td>  0.973</tr>
<tr><td align="left">025_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 275.36<td> 220.07<td>2<td>298<td>0<td>56.30<td>32.92<td>44.10<td>  0.971</tr>
<tr><td align="left">025_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  13.09<td>  10.46<td>2<td>76<td>222<td>77.36<td>37.97<td>16.06<td>  0.972</tr>
<tr><td align="left">025_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  26.38<td>  21.09<td>2<td>76<td>222<td>73.79<td>36.72<td>19.75<td>  0.973</tr>
<tr><td align="left">025_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   6.70<td>   5.36<td>2<td>76<td>222<td>71.59<td>40.71<td>11.52<td>  0.973</tr>
<tr><td align="left">025_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  58.88<td>  47.06<td>2<td>76<td>222<td>72.15<td>35.10<td>27.07<td>  0.971</tr>
<tr><td align="left">025_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   9.05<td>   7.23<td>2<td>76<td>222<td>70.73<td>39.44<td>13.40<td>  0.973</tr>
<tr><td align="left">025_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 200.60<td> 160.32<td>2<td>76<td>222<td>57.31<td>32.84<td>44.51<td>  0.971</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 026
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/026_480p.png)](https://drive.google.com/drive/folders/1acCPiOXh78ZKhw-OoVFBiNjKsDgxJn7t?usp=share_link)\
*__Figure 27__. First Frame of Sequence 026*

Raw Sequence Size: 21.45 GB\
Source: [HERE](https://drive.google.com/drive/folders/1acCPiOXh78ZKhw-OoVFBiNjKsDgxJn7t?usp=share_link)

<br>

*__Table 27__. Description of encoded videos using sequence 026 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">026_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   6.05<td>   4.84<td>1<td>299<td>0<td>34.07<td>30.91<td>310.38<td>  0.782</tr>
<tr><td align="left">026_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>  12.37<td>   9.89<td>1<td>299<td>0<td>35.31<td>30.55<td>312.48<td>  0.774</tr>
<tr><td align="left">026_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.64<td>   2.11<td>1<td>299<td>0<td>32.90<td>31.63<td>306.99<td>  0.773</tr>
<tr><td align="left">026_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  25.13<td>  20.08<td>1<td>299<td>0<td>33.03<td>30.04<td>315.92<td>  0.782</tr>
<tr><td align="left">026_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   4.01<td>   3.20<td>1<td>299<td>0<td>33.55<td>31.34<td>308.90<td>  0.774</tr>
<tr><td align="left">026_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td> 104.08<td>  83.18<td>1<td>299<td>0<td>30.20<td>29.24<td>324.59<td>  0.778</tr>
<tr><td align="left">026_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  15.09<td>  12.06<td>2<td>76<td>222<td>33.96<td>30.73<td>310.79<td>  0.781</tr>
<tr><td align="left">026_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  30.23<td>  24.16<td>2<td>76<td>222<td>35.23<td>30.39<td>313.33<td>  0.774</tr>
<tr><td align="left">026_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   7.44<td>   5.95<td>2<td>76<td>222<td>32.82<td>31.46<td>307.41<td>  0.771</tr>
<tr><td align="left">026_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  67.36<td>  53.84<td>2<td>76<td>222<td>33.06<td>29.86<td>317.18<td>  0.781</tr>
<tr><td align="left">026_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   9.91<td>   7.92<td>2<td>76<td>222<td>33.44<td>31.18<td>308.87<td>  0.773</tr>
<tr><td align="left">026_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 291.71<td> 233.14<td>2<td>283<td>15<td>29.95<td>29.30<td>326.49<td>  0.777</tr>
<tr><td align="left">026_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  13.10<td>  10.47<td>2<td>76<td>222<td>33.87<td>30.76<td>311.00<td>  0.781</tr>
<tr><td align="left">026_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  26.89<td>  21.49<td>2<td>76<td>222<td>33.33<td>30.41<td>313.60<td>  0.774</tr>
<tr><td align="left">026_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   7.26<td>   5.80<td>2<td>76<td>222<td>32.79<td>31.48<td>307.50<td>  0.772</tr>
<tr><td align="left">026_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  61.27<td>  48.97<td>2<td>76<td>222<td>33.06<td>29.91<td>317.52<td>  0.781</tr>
<tr><td align="left">026_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   9.85<td>   7.87<td>2<td>76<td>222<td>30.49<td>31.16<td>309.38<td>  0.771</tr>
<tr><td align="left">026_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 201.73<td> 161.22<td>2<td>76<td>222<td>30.82<td>29.17<td>326.81<td>  0.777</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 027
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/027_480p.png)](https://drive.google.com/drive/folders/1F8o_t2UhfEC8UnkEHO017jht2pYhKyjI?usp=share_link)\
*__Figure 28__. First Frame of Sequence 027*

Raw Sequence Size: 19.49 GB\
Source: [HERE](https://drive.google.com/drive/folders/1F8o_t2UhfEC8UnkEHO017jht2pYhKyjI?usp=share_link)

<br>

*__Table 28__. Description of encoded videos using sequence 027 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">027_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   4.97<td>   3.97<td>1<td>299<td>0<td>86.46<td>43.88<td> 5.18<td>  0.990</tr>
<tr><td align="left">027_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>   9.11<td>   7.28<td>1<td>299<td>0<td>86.03<td>42.83<td> 5.90<td>  0.989</tr>
<tr><td align="left">027_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.46<td>   1.97<td>1<td>299<td>0<td>87.53<td>46.14<td> 4.01<td>  0.989</tr>
<tr><td align="left">027_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  20.71<td>  16.55<td>1<td>299<td>0<td>84.67<td>41.47<td> 7.26<td>  0.990</tr>
<tr><td align="left">027_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   3.39<td>   2.71<td>1<td>299<td>0<td>87.00<td>45.12<td> 4.50<td>  0.989</tr>
<tr><td align="left">027_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  77.19<td>  61.69<td>1<td>299<td>0<td>78.95<td>39.67<td>10.10<td>  0.989</tr>
<tr><td align="left">027_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  13.28<td>  10.62<td>2<td>76<td>222<td>86.00<td>42.80<td> 5.71<td>  0.989</tr>
<tr><td align="left">027_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  26.86<td>  21.47<td>2<td>76<td>222<td>85.48<td>41.92<td> 6.48<td>  0.989</tr>
<tr><td align="left">027_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   3.65<td>   2.92<td>2<td>76<td>222<td>86.76<td>44.66<td> 4.36<td>  0.988</tr>
<tr><td align="left">027_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  62.50<td>  49.95<td>2<td>76<td>222<td>84.00<td>40.77<td> 8.00<td>  0.989</tr>
<tr><td align="left">027_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   8.11<td>   6.48<td>2<td>76<td>222<td>86.44<td>43.89<td> 4.92<td>  0.989</tr>
<tr><td align="left">027_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 251.44<td> 200.95<td>3<td>75<td>222<td>77.55<td>39.24<td>11.37<td>  0.989</tr>
<tr><td align="left">027_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  12.83<td>  10.25<td>2<td>76<td>222<td>85.91<td>43.05<td> 5.62<td>  0.989</tr>
<tr><td align="left">027_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  25.92<td>  20.72<td>2<td>76<td>222<td>77.88<td>41.69<td> 8.23<td>  0.987</tr>
<tr><td align="left">027_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   4.44<td>   3.55<td>2<td>76<td>222<td>86.72<td>44.80<td> 4.34<td>  0.988</tr>
<tr><td align="left">027_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  58.94<td>  47.10<td>2<td>76<td>222<td>83.85<td>40.91<td> 7.86<td>  0.989</tr>
<tr><td align="left">027_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   8.46<td>   6.77<td>2<td>76<td>222<td>77.34<td>43.07<td> 8.63<td>  0.982</tr>
<tr><td align="left">027_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 196.91<td> 157.37<td>2<td>76<td>222<td>77.81<td>39.20<td>11.00<td>  0.989</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 028
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/028_480p.png)](https://drive.google.com/drive/folders/1WxHTv7sT_R9Gend0IDZ2DIzQeCHg5WYV?usp=share_link)\
*__Figure 29__. First Frame of Sequence 028*

Raw Sequence Size: 11.88 GB\
Source: [HERE](https://drive.google.com/drive/folders/1WxHTv7sT_R9Gend0IDZ2DIzQeCHg5WYV?usp=share_link)

<br>

*__Table 29__. Description of encoded videos using sequence 028 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">028_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   6.11<td>   4.89<td>1<td>299<td>0<td> 9.80<td>33.48<td>905.82<td>  0.468</tr>
<tr><td align="left">028_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>  11.29<td>   9.02<td>1<td>299<td>0<td>10.81<td>33.37<td>905.92<td>  0.448</tr>
<tr><td align="left">028_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.66<td>   2.12<td>1<td>299<td>0<td> 8.91<td>33.73<td>899.97<td>  0.447</tr>
<tr><td align="left">028_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  23.07<td>  18.43<td>1<td>299<td>0<td>14.08<td>33.30<td>906.03<td>  0.468</tr>
<tr><td align="left">028_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   4.04<td>   3.23<td>1<td>299<td>0<td> 9.11<td>33.43<td>903.40<td>  0.448</tr>
<tr><td align="left">028_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  82.87<td>  66.23<td>1<td>299<td>0<td>25.69<td>33.12<td>906.42<td>  0.458</tr>
<tr><td align="left">028_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  15.30<td>  12.23<td>2<td>125<td>173<td> 9.84<td>33.29<td>904.39<td>  0.468</tr>
<tr><td align="left">028_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  30.49<td>  24.37<td>2<td>154<td>144<td>10.86<td>33.27<td>906.22<td>  0.448</tr>
<tr><td align="left">028_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   7.33<td>   5.86<td>2<td>78<td>220<td> 8.89<td>33.54<td>900.94<td>  0.445</tr>
<tr><td align="left">028_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  67.70<td>  54.10<td>2<td>203<td>95<td>14.16<td>33.23<td>905.76<td>  0.468</tr>
<tr><td align="left">028_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   9.94<td>   7.94<td>2<td>91<td>207<td> 9.12<td>33.36<td>902.43<td>  0.447</tr>
<tr><td align="left">028_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 222.02<td> 177.44<td>11<td>207<td>82<td>25.88<td>33.12<td>907.15<td>  0.457</tr>
<tr><td align="left">028_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  13.41<td>  10.72<td>2<td>76<td>222<td> 9.78<td>33.34<td>904.94<td>  0.468</tr>
<tr><td align="left">028_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  26.81<td>  21.43<td>2<td>76<td>222<td>10.85<td>33.29<td>906.82<td>  0.448</tr>
<tr><td align="left">028_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   7.18<td>   5.74<td>2<td>76<td>222<td> 8.88<td>33.51<td>901.17<td>  0.446</tr>
<tr><td align="left">028_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  60.26<td>  48.16<td>2<td>76<td>222<td>14.12<td>33.24<td>906.08<td>  0.468</tr>
<tr><td align="left">028_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>  10.10<td>   8.08<td>2<td>76<td>222<td> 9.04<td>33.31<td>903.72<td>  0.447</tr>
<tr><td align="left">028_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 200.76<td> 160.44<td>2<td>76<td>222<td>25.90<td>33.09<td>906.88<td>  0.457</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 029
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/029_480p.png)](https://drive.google.com/drive/folders/1Gmb-2hwoxd2TGwEaF1ePp4Ftrt0obBBe?usp=share_link)\
*__Figure 30__. First Frame of Sequence 029*

Raw Sequence Size: 14.94 GB\
Source: [HERE](https://drive.google.com/drive/folders/1Gmb-2hwoxd2TGwEaF1ePp4Ftrt0obBBe?usp=share_link)

<br>

*__Table 30__. Description of encoded videos using sequence 029 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">029_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   5.02<td>   4.01<td>1<td>299<td>0<td>75.42<td>39.61<td>58.13<td>  0.968</tr>
<tr><td align="left">029_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>   9.01<td>   7.20<td>1<td>299<td>0<td>75.59<td>39.25<td>58.55<td>  0.966</tr>
<tr><td align="left">029_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.32<td>   1.85<td>1<td>299<td>0<td>74.54<td>40.42<td>58.16<td>  0.965</tr>
<tr><td align="left">029_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  19.87<td>  15.88<td>1<td>299<td>0<td>75.50<td>38.77<td>58.78<td>  0.968</tr>
<tr><td align="left">029_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   3.66<td>   2.93<td>1<td>299<td>0<td>75.14<td>40.05<td>58.05<td>  0.966</tr>
<tr><td align="left">029_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  80.17<td>  64.07<td>1<td>299<td>0<td>74.65<td>38.06<td>59.25<td>  0.967</tr>
<tr><td align="left">029_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  10.76<td>   8.60<td>2<td>76<td>222<td>75.18<td>38.99<td>58.51<td>  0.967</tr>
<tr><td align="left">029_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  22.44<td>  17.93<td>2<td>76<td>222<td>75.31<td>38.70<td>58.68<td>  0.966</tr>
<tr><td align="left">029_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   2.40<td>   1.92<td>2<td>76<td>222<td>73.65<td>39.53<td>58.20<td>  0.964</tr>
<tr><td align="left">029_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  53.54<td>  42.79<td>2<td>76<td>222<td>75.25<td>38.32<td>59.05<td>  0.968</tr>
<tr><td align="left">029_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   5.41<td>   4.32<td>2<td>76<td>222<td>74.64<td>39.12<td>58.38<td>  0.965</tr>
<tr><td align="left">029_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 227.75<td> 182.02<td>3<td>192<td>105<td>74.24<td>37.91<td>59.53<td>  0.967</tr>
<tr><td align="left">029_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  12.33<td>   9.86<td>2<td>76<td>222<td>75.03<td>39.16<td>58.44<td>  0.967</tr>
<tr><td align="left">029_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  25.87<td>  20.67<td>2<td>76<td>222<td>70.72<td>38.56<td>58.93<td>  0.965</tr>
<tr><td align="left">029_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   2.10<td>   1.68<td>2<td>76<td>222<td>73.66<td>39.60<td>58.13<td>  0.964</tr>
<tr><td align="left">029_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  58.51<td>  46.76<td>2<td>76<td>222<td>75.16<td>38.43<td>58.99<td>  0.968</tr>
<tr><td align="left">029_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   4.81<td>   3.84<td>2<td>76<td>222<td>67.56<td>38.73<td>59.07<td>  0.963</tr>
<tr><td align="left">029_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 198.06<td> 158.29<td>2<td>76<td>222<td>74.38<td>37.83<td>59.42<td>  0.967</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 030
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/030_480p.png)](https://drive.google.com/drive/folders/1lgYq24zbyKTusHddLB9U4HsvvexC7Aht?usp=share_link)\
*__Figure 31__. First Frame of Sequence 030*

Raw Sequence Size: 18.30 GB\
Source: [HERE](https://drive.google.com/drive/folders/1lgYq24zbyKTusHddLB9U4HsvvexC7Aht?usp=share_link)

<br>

*__Table 31__. Description of encoded videos using sequence 030 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">030_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   5.43<td>   4.34<td>1<td>299<td>0<td>13.64<td>30.78<td>304.01<td>  0.552</tr>
<tr><td align="left">030_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>  10.18<td>   8.14<td>1<td>299<td>0<td>11.41<td>30.45<td>306.80<td>  0.560</tr>
<tr><td align="left">030_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.38<td>   1.90<td>1<td>299<td>0<td>21.64<td>31.76<td>285.70<td>  0.554</tr>
<tr><td align="left">030_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  20.16<td>  16.11<td>1<td>299<td>0<td> 8.65<td>30.23<td>308.38<td>  0.554</tr>
<tr><td align="left">030_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   3.59<td>   2.87<td>1<td>299<td>0<td>17.17<td>31.15<td>297.74<td>  0.557</tr>
<tr><td align="left">030_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  83.94<td>  67.08<td>1<td>299<td>0<td> 5.14<td>29.84<td>310.00<td>  0.558</tr>
<tr><td align="left">030_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  13.41<td>  10.72<td>2<td>76<td>222<td>13.50<td>30.88<td>302.97<td>  0.553</tr>
<tr><td align="left">030_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  27.18<td>  21.73<td>2<td>76<td>222<td>11.34<td>30.49<td>306.44<td>  0.561</tr>
<tr><td align="left">030_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   6.75<td>   5.40<td>2<td>76<td>222<td>21.36<td>31.89<td>283.63<td>  0.554</tr>
<tr><td align="left">030_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  63.08<td>  50.42<td>2<td>76<td>222<td> 8.64<td>30.23<td>308.85<td>  0.554</tr>
<tr><td align="left">030_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   8.85<td>   7.07<td>2<td>76<td>222<td>16.93<td>31.20<td>295.99<td>  0.558</tr>
<tr><td align="left">030_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 225.48<td> 180.20<td>2<td>76<td>222<td> 5.21<td>29.94<td>310.95<td>  0.558</tr>
<tr><td align="left">030_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  12.89<td>  10.30<td>2<td>76<td>222<td>13.53<td>30.84<td>302.76<td>  0.553</tr>
<tr><td align="left">030_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  26.09<td>  20.85<td>2<td>76<td>222<td>10.54<td>30.39<td>308.82<td>  0.554</tr>
<tr><td align="left">030_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   6.45<td>   5.16<td>2<td>76<td>222<td>21.42<td>31.83<td>284.28<td>  0.554</tr>
<tr><td align="left">030_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  59.24<td>  47.35<td>2<td>76<td>222<td> 8.62<td>30.19<td>308.24<td>  0.555</tr>
<tr><td align="left">030_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   8.46<td>   6.76<td>2<td>76<td>222<td>14.91<td>31.01<td>302.35<td>  0.543</tr>
<tr><td align="left">030_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 197.00<td> 157.44<td>2<td>76<td>222<td> 5.17<td>29.80<td>310.35<td>  0.558</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 031
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/031_480p.png)](https://drive.google.com/drive/folders/1-uBPcBo-lnnBb1uV04P5IywzH6563e7o?usp=share_link)\
*__Figure 32__. First Frame of Sequence 031*

Raw Sequence Size:  6.07 GB\
Source: [HERE](https://drive.google.com/drive/folders/1-uBPcBo-lnnBb1uV04P5IywzH6563e7o?usp=share_link)

<br>

*__Table 32__. Description of encoded videos using sequence 031 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">031_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   5.07<td>   4.05<td>1<td>299<td>0<td>52.16<td>31.27<td>501.89<td>  0.765</tr>
<tr><td align="left">031_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>   9.29<td>   7.42<td>1<td>299<td>0<td>54.02<td>31.26<td>502.01<td>  0.751</tr>
<tr><td align="left">031_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.24<td>   1.79<td>1<td>299<td>0<td>46.25<td>31.29<td>502.36<td>  0.750</tr>
<tr><td align="left">031_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  18.70<td>  14.95<td>1<td>299<td>0<td>59.28<td>31.35<td>501.76<td>  0.765</tr>
<tr><td align="left">031_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   3.39<td>   2.71<td>1<td>299<td>0<td>48.17<td>31.33<td>502.37<td>  0.750</tr>
<tr><td align="left">031_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  69.01<td>  55.15<td>1<td>299<td>0<td>71.18<td>31.31<td>502.10<td>  0.758</tr>
<tr><td align="left">031_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  12.61<td>  10.08<td>2<td>105<td>193<td>52.02<td>31.04<td>502.41<td>  0.764</tr>
<tr><td align="left">031_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  25.12<td>  20.07<td>2<td>119<td>179<td>53.93<td>31.13<td>502.22<td>  0.750</tr>
<tr><td align="left">031_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   5.51<td>   4.41<td>2<td>77<td>221<td>46.12<td>31.08<td>502.15<td>  0.749</tr>
<tr><td align="left">031_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  54.56<td>  43.61<td>2<td>161<td>137<td>59.29<td>31.20<td>502.41<td>  0.764</tr>
<tr><td align="left">031_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   8.03<td>   6.42<td>2<td>83<td>215<td>48.06<td>31.07<td>502.33<td>  0.750</tr>
<tr><td align="left">031_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 182.66<td> 145.99<td>2<td>176<td>122<td>71.13<td>31.28<td>502.32<td>  0.758</tr>
<tr><td align="left">031_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  12.67<td>  10.12<td>2<td>76<td>222<td>51.96<td>31.08<td>502.31<td>  0.765</tr>
<tr><td align="left">031_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  25.52<td>  20.40<td>2<td>76<td>222<td>52.06<td>31.04<td>502.62<td>  0.750</tr>
<tr><td align="left">031_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   5.09<td>   4.07<td>2<td>76<td>222<td>46.12<td>31.09<td>501.95<td>  0.749</tr>
<tr><td align="left">031_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  56.69<td>  45.31<td>2<td>76<td>222<td>59.21<td>31.22<td>502.32<td>  0.765</tr>
<tr><td align="left">031_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   7.70<td>   6.15<td>2<td>76<td>222<td>45.67<td>30.86<td>503.78<td>  0.748</tr>
<tr><td align="left">031_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 181.93<td> 145.40<td>2<td>76<td>222<td>71.23<td>31.23<td>502.33<td>  0.758</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 032
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/032_480p.png)](https://drive.google.com/drive/folders/1XNEH14stdG834bGYfk7Y9Cc_oOcUq0_J?usp=share_link)\
*__Figure 33__. First Frame of Sequence 032*

Raw Sequence Size: 22.35 GB\
Source: [HERE](https://drive.google.com/drive/folders/1XNEH14stdG834bGYfk7Y9Cc_oOcUq0_J?usp=share_link)

<br>

*__Table 33__. Description of encoded videos using sequence 032 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">032_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   4.82<td>   3.85<td>1<td>299<td>0<td>39.75<td>30.03<td>450.20<td>  0.772</tr>
<tr><td align="left">032_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>   9.55<td>   7.63<td>1<td>299<td>0<td>40.08<td>29.62<td>453.28<td>  0.765</tr>
<tr><td align="left">032_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.13<td>   1.70<td>1<td>299<td>0<td>35.54<td>30.83<td>446.02<td>  0.764</tr>
<tr><td align="left">032_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  19.82<td>  15.84<td>1<td>299<td>0<td>38.25<td>29.08<td>457.94<td>  0.772</tr>
<tr><td align="left">032_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   3.19<td>   2.55<td>1<td>299<td>0<td>37.00<td>30.51<td>449.05<td>  0.764</tr>
<tr><td align="left">032_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  80.63<td>  64.44<td>1<td>299<td>0<td>31.42<td>28.21<td>469.27<td>  0.768</tr>
<tr><td align="left">032_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  12.15<td>   9.71<td>2<td>76<td>222<td>39.39<td>29.80<td>451.47<td>  0.771</tr>
<tr><td align="left">032_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  24.83<td>  19.85<td>2<td>76<td>222<td>39.67<td>29.41<td>453.72<td>  0.765</tr>
<tr><td align="left">032_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   6.16<td>   4.92<td>2<td>76<td>222<td>35.43<td>30.64<td>445.90<td>  0.763</tr>
<tr><td align="left">032_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  56.17<td>  44.89<td>2<td>78<td>220<td>37.91<td>28.83<td>459.65<td>  0.771</tr>
<tr><td align="left">032_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   8.02<td>   6.41<td>2<td>76<td>222<td>36.75<td>30.30<td>449.37<td>  0.763</tr>
<tr><td align="left">032_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 266.68<td> 213.13<td>2<td>273<td>25<td>30.95<td>28.26<td>469.41<td>  0.768</tr>
<tr><td align="left">032_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  13.13<td>  10.49<td>2<td>76<td>222<td>39.39<td>29.83<td>451.54<td>  0.771</tr>
<tr><td align="left">032_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  26.21<td>  20.94<td>2<td>76<td>222<td>38.34<td>29.42<td>454.32<td>  0.765</tr>
<tr><td align="left">032_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   6.28<td>   5.02<td>2<td>76<td>222<td>35.40<td>30.66<td>445.78<td>  0.763</tr>
<tr><td align="left">032_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  58.68<td>  46.90<td>2<td>76<td>222<td>38.03<td>28.86<td>459.94<td>  0.771</tr>
<tr><td align="left">032_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   8.20<td>   6.55<td>2<td>76<td>222<td>33.69<td>30.27<td>452.59<td>  0.760</tr>
<tr><td align="left">032_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 196.16<td> 156.77<td>2<td>76<td>222<td>32.12<td>28.06<td>471.53<td>  0.768</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 033
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/033_480p.png)](https://drive.google.com/drive/folders/13Llz-BrpnPvflcVGEhvKYJxsSGt3VxZ-?usp=share_link)\
*__Figure 34__. First Frame of Sequence 033*

Raw Sequence Size: 15.76 GB\
Source: [HERE](https://drive.google.com/drive/folders/13Llz-BrpnPvflcVGEhvKYJxsSGt3VxZ-?usp=share_link)

<br>

*__Table 34__. Description of encoded videos using sequence 033 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">033_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   4.53<td>   3.62<td>1<td>299<td>0<td> 6.05<td>30.28<td>723.79<td>  0.774</tr>
<tr><td align="left">033_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>   8.60<td>   6.87<td>1<td>299<td>0<td> 8.38<td>30.15<td>724.71<td>  0.760</tr>
<tr><td align="left">033_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.12<td>   1.69<td>1<td>299<td>0<td> 3.74<td>30.50<td>723.85<td>  0.759</tr>
<tr><td align="left">033_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  22.06<td>  17.63<td>1<td>299<td>0<td>15.44<td>30.12<td>724.73<td>  0.774</tr>
<tr><td align="left">033_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   3.45<td>   2.76<td>1<td>299<td>0<td> 4.14<td>30.40<td>726.10<td>  0.760</tr>
<tr><td align="left">033_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  76.18<td>  60.88<td>1<td>299<td>0<td>33.98<td>29.83<td>725.81<td>  0.766</tr>
<tr><td align="left">033_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  13.37<td>  10.68<td>2<td>86<td>212<td> 6.05<td>30.20<td>724.30<td>  0.774</tr>
<tr><td align="left">033_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  26.68<td>  21.32<td>2<td>108<td>190<td> 8.43<td>30.10<td>724.87<td>  0.760</tr>
<tr><td align="left">033_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   4.83<td>   3.86<td>2<td>76<td>222<td> 3.74<td>30.43<td>724.14<td>  0.758</tr>
<tr><td align="left">033_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  60.47<td>  48.33<td>2<td>164<td>134<td>15.56<td>30.00<td>725.09<td>  0.774</tr>
<tr><td align="left">033_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   8.15<td>   6.51<td>2<td>77<td>221<td> 4.13<td>30.34<td>725.23<td>  0.759</tr>
<tr><td align="left">033_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 221.77<td> 177.24<td>3<td>291<td>6<td>34.53<td>29.89<td>726.38<td>  0.766</tr>
<tr><td align="left">033_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  13.05<td>  10.43<td>2<td>76<td>222<td> 6.04<td>30.22<td>724.14<td>  0.774</tr>
<tr><td align="left">033_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  26.18<td>  20.92<td>2<td>76<td>222<td> 8.34<td>30.11<td>724.72<td>  0.760</tr>
<tr><td align="left">033_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   4.19<td>   3.35<td>2<td>76<td>222<td> 3.75<td>30.43<td>723.79<td>  0.759</tr>
<tr><td align="left">033_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  59.26<td>  47.36<td>2<td>76<td>222<td>15.53<td>30.03<td>725.11<td>  0.774</tr>
<tr><td align="left">033_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   7.56<td>   6.04<td>2<td>76<td>222<td> 4.04<td>30.32<td>724.98<td>  0.759</tr>
<tr><td align="left">033_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 197.54<td> 157.88<td>2<td>76<td>222<td>34.52<td>29.80<td>726.15<td>  0.766</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 034
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/034_480p.png)](https://drive.google.com/drive/folders/1YmHT6kDsSb2a7yEOUgrhXhwvOGzzfcpA?usp=share_link)\
*__Figure 35__. First Frame of Sequence 034*

Raw Sequence Size: 14.67 GB\
Source: [HERE](https://drive.google.com/drive/folders/1YmHT6kDsSb2a7yEOUgrhXhwvOGzzfcpA?usp=share_link)

<br>

*__Table 35__. Description of encoded videos using sequence 034 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">034_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   5.62<td>   4.49<td>1<td>299<td>0<td>16.44<td>37.60<td>100.35<td>  0.753</tr>
<tr><td align="left">034_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>  10.55<td>   8.43<td>1<td>299<td>0<td>13.79<td>37.29<td>103.61<td>  0.760</tr>
<tr><td align="left">034_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.29<td>   1.83<td>1<td>299<td>0<td>28.63<td>38.89<td>85.89<td>  0.756</tr>
<tr><td align="left">034_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  21.62<td>  17.28<td>1<td>299<td>0<td>10.67<td>36.93<td>106.13<td>  0.755</tr>
<tr><td align="left">034_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   3.68<td>   2.94<td>1<td>299<td>0<td>21.72<td>38.20<td>94.31<td>  0.758</tr>
<tr><td align="left">034_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  78.89<td>  63.05<td>1<td>299<td>0<td> 7.33<td>36.50<td>107.34<td>  0.759</tr>
<tr><td align="left">034_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  12.73<td>  10.17<td>2<td>76<td>222<td>16.22<td>37.54<td>100.22<td>  0.754</tr>
<tr><td align="left">034_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  25.40<td>  20.30<td>2<td>76<td>222<td>13.62<td>37.21<td>103.44<td>  0.761</tr>
<tr><td align="left">034_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   5.17<td>   4.13<td>2<td>76<td>222<td>28.30<td>38.67<td>85.60<td>  0.756</tr>
<tr><td align="left">034_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  55.42<td>  44.29<td>2<td>76<td>222<td>10.54<td>36.86<td>106.19<td>  0.755</tr>
<tr><td align="left">034_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   8.03<td>   6.42<td>2<td>76<td>222<td>21.44<td>38.04<td>94.01<td>  0.758</tr>
<tr><td align="left">034_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 200.56<td> 160.29<td>2<td>76<td>222<td> 7.24<td>36.51<td>107.50<td>  0.759</tr>
<tr><td align="left">034_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  12.58<td>  10.06<td>2<td>76<td>222<td>16.28<td>37.53<td>100.11<td>  0.754</tr>
<tr><td align="left">034_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  25.20<td>  20.14<td>2<td>76<td>222<td>12.98<td>37.12<td>104.36<td>  0.758</tr>
<tr><td align="left">034_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   4.95<td>   3.96<td>2<td>76<td>222<td>28.32<td>38.66<td>85.56<td>  0.757</tr>
<tr><td align="left">034_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  56.73<td>  45.34<td>2<td>76<td>222<td>10.56<td>36.86<td>105.97<td>  0.755</tr>
<tr><td align="left">034_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   7.72<td>   6.17<td>2<td>76<td>222<td>19.96<td>37.92<td>96.25<td>  0.751</tr>
<tr><td align="left">034_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 191.90<td> 153.37<td>2<td>76<td>222<td> 7.27<td>36.42<td>107.28<td>  0.759</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 035
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/035_480p.png)](https://drive.google.com/drive/folders/1tsKQVAPpNB0gWcTf4YqSafH3Zy3EZMLg?usp=share_link)\
*__Figure 36__. First Frame of Sequence 035*

Raw Sequence Size: 16.50 GB\
Source: [HERE](https://drive.google.com/drive/folders/1tsKQVAPpNB0gWcTf4YqSafH3Zy3EZMLg?usp=share_link)

<br>

*__Table 36__. Description of encoded videos using sequence 035 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">035_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   5.43<td>   4.34<td>1<td>299<td>0<td>58.49<td>35.72<td>870.44<td>  0.888</tr>
<tr><td align="left">035_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>   9.55<td>   7.63<td>1<td>299<td>0<td>61.88<td>35.43<td>871.77<td>  0.881</tr>
<tr><td align="left">035_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.48<td>   1.98<td>1<td>299<td>0<td>46.72<td>36.27<td>874.45<td>  0.880</tr>
<tr><td align="left">035_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  21.87<td>  17.48<td>1<td>299<td>0<td>65.49<td>34.96<td>872.32<td>  0.888</tr>
<tr><td align="left">035_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   3.73<td>   2.98<td>1<td>299<td>0<td>52.91<td>36.09<td>873.10<td>  0.880</tr>
<tr><td align="left">035_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  78.64<td>  62.85<td>1<td>299<td>0<td>67.56<td>34.26<td>873.37<td>  0.884</tr>
<tr><td align="left">035_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  13.30<td>  10.63<td>2<td>116<td>182<td>58.42<td>35.55<td>870.38<td>  0.887</tr>
<tr><td align="left">035_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  26.83<td>  21.44<td>2<td>181<td>117<td>61.78<td>35.17<td>872.72<td>  0.880</tr>
<tr><td align="left">035_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   4.13<td>   3.30<td>2<td>83<td>215<td>46.48<td>35.94<td>873.95<td>  0.879</tr>
<tr><td align="left">035_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  59.71<td>  47.72<td>2<td>186<td>112<td>65.54<td>34.74<td>871.75<td>  0.888</tr>
<tr><td align="left">035_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   7.76<td>   6.21<td>2<td>104<td>194<td>52.85<td>35.88<td>871.82<td>  0.880</tr>
<tr><td align="left">035_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 218.11<td> 174.31<td>2<td>298<td>0<td>68.00<td>34.19<td>874.41<td>  0.884</tr>
<tr><td align="left">035_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  12.99<td>  10.38<td>2<td>76<td>222<td>58.54<td>35.64<td>870.48<td>  0.888</tr>
<tr><td align="left">035_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  26.35<td>  21.06<td>2<td>76<td>222<td>62.44<td>35.27<td>872.81<td>  0.881</tr>
<tr><td align="left">035_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   3.34<td>   2.67<td>2<td>76<td>222<td>46.72<td>36.03<td>874.02<td>  0.880</tr>
<tr><td align="left">035_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  59.61<td>  47.64<td>2<td>76<td>222<td>65.41<td>34.88<td>872.03<td>  0.888</tr>
<tr><td align="left">035_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   7.24<td>   5.79<td>2<td>76<td>222<td>54.03<td>35.99<td>872.01<td>  0.881</tr>
<tr><td align="left">035_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 199.49<td> 159.43<td>2<td>76<td>222<td>68.07<td>34.16<td>873.98<td>  0.884</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 036
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/036_480p.png)](https://drive.google.com/drive/folders/1sH0a5J9zXNoVUMxOQmAjE-CbUWHV_Oln?usp=share_link)\
*__Figure 37__. First Frame of Sequence 036*

Raw Sequence Size: 11.11 GB\
Source: [HERE](https://drive.google.com/drive/folders/1sH0a5J9zXNoVUMxOQmAjE-CbUWHV_Oln?usp=share_link)

<br>

*__Table 37__. Description of encoded videos using sequence 036 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">036_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   5.05<td>   4.03<td>1<td>299<td>0<td>54.31<td>35.11<td>304.54<td>  0.783</tr>
<tr><td align="left">036_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>  10.09<td>   8.07<td>1<td>299<td>0<td>57.83<td>34.87<td>305.15<td>  0.776</tr>
<tr><td align="left">036_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.35<td>   1.88<td>1<td>299<td>0<td>42.51<td>35.60<td>301.20<td>  0.775</tr>
<tr><td align="left">036_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  22.48<td>  17.97<td>1<td>299<td>0<td>62.12<td>34.84<td>305.68<td>  0.783</tr>
<tr><td align="left">036_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   3.33<td>   2.67<td>1<td>299<td>0<td>48.08<td>35.30<td>304.01<td>  0.775</tr>
<tr><td align="left">036_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  95.34<td>  76.19<td>1<td>299<td>0<td>65.24<td>34.55<td>306.58<td>  0.779</tr>
<tr><td align="left">036_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  13.49<td>  10.78<td>2<td>76<td>222<td>54.17<td>34.63<td>305.20<td>  0.783</tr>
<tr><td align="left">036_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  27.25<td>  21.77<td>2<td>76<td>222<td>57.67<td>34.55<td>305.89<td>  0.776</tr>
<tr><td align="left">036_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   6.22<td>   4.97<td>2<td>76<td>222<td>42.33<td>35.19<td>301.92<td>  0.774</tr>
<tr><td align="left">036_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  61.51<td>  49.16<td>2<td>76<td>222<td>61.92<td>34.52<td>306.39<td>  0.783</tr>
<tr><td align="left">036_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   8.84<td>   7.06<td>2<td>76<td>222<td>47.90<td>34.92<td>304.20<td>  0.775</tr>
<tr><td align="left">036_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 197.86<td> 158.13<td>2<td>76<td>222<td>64.83<td>34.43<td>307.21<td>  0.779</tr>
<tr><td align="left">036_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  13.13<td>  10.49<td>2<td>76<td>222<td>54.10<td>34.75<td>304.99<td>  0.783</tr>
<tr><td align="left">036_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  26.34<td>  21.05<td>2<td>76<td>222<td>47.35<td>34.52<td>317.03<td>  0.773</tr>
<tr><td align="left">036_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   6.31<td>   5.04<td>2<td>76<td>222<td>42.33<td>35.24<td>301.68<td>  0.774</tr>
<tr><td align="left">036_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  59.27<td>  47.37<td>2<td>76<td>222<td>61.77<td>34.59<td>306.26<td>  0.783</tr>
<tr><td align="left">036_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   8.66<td>   6.92<td>2<td>76<td>222<td>38.57<td>34.79<td>325.42<td>  0.765</tr>
<tr><td align="left">036_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 198.07<td> 158.30<td>2<td>76<td>222<td>64.88<td>34.44<td>307.08<td>  0.779</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 037
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/037_480p.png)](https://drive.google.com/drive/folders/1-uoD5UDSn9YXsUwF0RuAt-W84JLOm4OT?usp=share_link)\
*__Figure 38__. First Frame of Sequence 037*

Raw Sequence Size:  8.13 GB\
Source: [HERE](https://drive.google.com/drive/folders/1-uoD5UDSn9YXsUwF0RuAt-W84JLOm4OT?usp=share_link)

<br>

*__Table 38__. Description of encoded videos using sequence 037 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">037_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   5.53<td>   4.42<td>1<td>299<td>0<td>87.91<td>40.78<td>20.73<td>  0.988</tr>
<tr><td align="left">037_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>   9.90<td>   7.91<td>1<td>299<td>0<td>87.33<td>40.47<td>21.08<td>  0.988</tr>
<tr><td align="left">037_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.27<td>   1.81<td>1<td>299<td>0<td>85.99<td>41.46<td>20.30<td>  0.987</tr>
<tr><td align="left">037_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  22.43<td>  17.93<td>1<td>299<td>0<td>85.39<td>40.45<td>21.21<td>  0.988</tr>
<tr><td align="left">037_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   3.58<td>   2.86<td>1<td>299<td>0<td>87.46<td>41.14<td>20.38<td>  0.987</tr>
<tr><td align="left">037_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  95.40<td>  76.24<td>1<td>299<td>0<td>80.64<td>39.89<td>21.98<td>  0.987</tr>
<tr><td align="left">037_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  13.22<td>  10.56<td>2<td>76<td>222<td>87.73<td>40.26<td>20.92<td>  0.987</tr>
<tr><td align="left">037_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  26.12<td>  20.87<td>2<td>76<td>222<td>87.10<td>40.15<td>21.19<td>  0.987</tr>
<tr><td align="left">037_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   3.39<td>   2.71<td>2<td>76<td>222<td>85.91<td>40.83<td>20.51<td>  0.986</tr>
<tr><td align="left">037_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  59.97<td>  47.93<td>2<td>115<td>183<td>85.17<td>40.03<td>21.48<td>  0.987</tr>
<tr><td align="left">037_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   7.30<td>   5.83<td>2<td>76<td>222<td>87.08<td>40.54<td>20.69<td>  0.987</tr>
<tr><td align="left">037_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 204.64<td> 163.55<td>5<td>81<td>214<td>80.39<td>39.74<td>22.28<td>  0.987</tr>
<tr><td align="left">037_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  13.16<td>  10.52<td>2<td>76<td>222<td>87.63<td>40.41<td>20.91<td>  0.987</tr>
<tr><td align="left">037_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  26.07<td>  20.84<td>2<td>76<td>222<td>84.19<td>40.21<td>21.40<td>  0.987</tr>
<tr><td align="left">037_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   3.28<td>   2.62<td>2<td>76<td>222<td>85.90<td>40.95<td>20.51<td>  0.986</tr>
<tr><td align="left">037_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  58.94<td>  47.11<td>2<td>76<td>222<td>85.08<td>40.18<td>21.43<td>  0.987</tr>
<tr><td align="left">037_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   7.38<td>   5.89<td>2<td>76<td>222<td>83.80<td>40.42<td>21.22<td>  0.985</tr>
<tr><td align="left">037_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 194.92<td> 155.78<td>2<td>76<td>222<td>80.49<td>39.77<td>22.21<td>  0.987</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 038
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/038_480p.png)](https://drive.google.com/drive/folders/1H7AhvVj59Gv_FjkfNzLOLR3zAKskQj06?usp=share_link)\
*__Figure 39__. First Frame of Sequence 038*

Raw Sequence Size:  7.40 GB\
Source: [HERE](https://drive.google.com/drive/folders/1H7AhvVj59Gv_FjkfNzLOLR3zAKskQj06?usp=share_link)

<br>

*__Table 39__. Description of encoded videos using sequence 038 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">038_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   6.39<td>   5.11<td>1<td>299<td>0<td> 4.55<td>30.97<td>141.68<td>  0.682</tr>
<tr><td align="left">038_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>  11.71<td>   9.36<td>1<td>299<td>0<td> 4.86<td>30.90<td>142.13<td>  0.674</tr>
<tr><td align="left">038_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.69<td>   2.15<td>1<td>299<td>0<td> 4.33<td>31.12<td>139.54<td>  0.676</tr>
<tr><td align="left">038_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  24.01<td>  19.19<td>1<td>299<td>0<td> 6.93<td>30.94<td>142.08<td>  0.681</tr>
<tr><td align="left">038_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   4.10<td>   3.27<td>1<td>299<td>0<td> 4.03<td>31.04<td>141.17<td>  0.675</tr>
<tr><td align="left">038_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  88.12<td>  70.42<td>1<td>299<td>0<td>20.62<td>30.92<td>142.47<td>  0.676</tr>
<tr><td align="left">038_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  13.86<td>  11.08<td>2<td>107<td>191<td> 4.52<td>30.97<td>141.68<td>  0.682</tr>
<tr><td align="left">038_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  27.57<td>  22.04<td>2<td>85<td>213<td> 4.93<td>30.90<td>142.36<td>  0.673</tr>
<tr><td align="left">038_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   7.09<td>   5.67<td>2<td>76<td>222<td> 4.38<td>31.16<td>140.51<td>  0.671</tr>
<tr><td align="left">038_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  61.97<td>  49.53<td>2<td>76<td>222<td> 7.10<td>30.89<td>142.81<td>  0.680</tr>
<tr><td align="left">038_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   9.23<td>   7.38<td>2<td>76<td>222<td> 4.05<td>31.06<td>141.31<td>  0.673</tr>
<tr><td align="left">038_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 199.17<td> 159.18<td>3<td>173<td>124<td>20.75<td>30.96<td>142.81<td>  0.676</tr>
<tr><td align="left">038_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  13.09<td>  10.46<td>2<td>76<td>222<td> 4.53<td>30.96<td>141.72<td>  0.681</tr>
<tr><td align="left">038_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  26.35<td>  21.06<td>2<td>76<td>222<td> 4.78<td>30.89<td>142.28<td>  0.673</tr>
<tr><td align="left">038_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   7.19<td>   5.74<td>2<td>76<td>222<td> 4.39<td>31.14<td>140.23<td>  0.672</tr>
<tr><td align="left">038_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  59.74<td>  47.75<td>2<td>76<td>222<td> 7.06<td>30.91<td>142.65<td>  0.680</tr>
<tr><td align="left">038_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   9.37<td>   7.49<td>2<td>76<td>222<td> 3.86<td>31.03<td>141.30<td>  0.673</tr>
<tr><td align="left">038_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 196.77<td> 157.26<td>2<td>76<td>222<td>20.76<td>30.90<td>142.85<td>  0.676</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 039
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/039_480p.png)](https://drive.google.com/drive/folders/1jU6AUf1Vf8ge8Jn7OoCJMPazUiVhcM8F?usp=share_link)\
*__Figure 40__. First Frame of Sequence 039*

Raw Sequence Size: 18.38 GB\
Source: [HERE](https://drive.google.com/drive/folders/1jU6AUf1Vf8ge8Jn7OoCJMPazUiVhcM8F?usp=share_link)

<br>

*__Table 40__. Description of encoded videos using sequence 039 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">039_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   4.45<td>   3.56<td>1<td>299<td>0<td>81.67<td>42.00<td>17.49<td>  0.984</tr>
<tr><td align="left">039_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>   8.73<td>   6.98<td>1<td>299<td>0<td>83.41<td>41.19<td>17.93<td>  0.983</tr>
<tr><td align="left">039_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.16<td>   1.72<td>1<td>299<td>0<td>76.75<td>43.65<td>16.86<td>  0.982</tr>
<tr><td align="left">039_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  20.99<td>  16.78<td>1<td>299<td>0<td>84.62<td>40.14<td>18.75<td>  0.984</tr>
<tr><td align="left">039_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   3.74<td>   2.99<td>1<td>299<td>0<td>78.88<td>42.90<td>17.14<td>  0.983</tr>
<tr><td align="left">039_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  75.20<td>  60.10<td>1<td>299<td>0<td>81.85<td>38.67<td>20.66<td>  0.983</tr>
<tr><td align="left">039_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  12.24<td>   9.79<td>2<td>76<td>222<td>81.41<td>41.23<td>17.80<td>  0.983</tr>
<tr><td align="left">039_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  26.02<td>  20.79<td>2<td>76<td>222<td>83.11<td>40.57<td>18.18<td>  0.983</tr>
<tr><td align="left">039_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   3.50<td>   2.80<td>2<td>76<td>222<td>76.51<td>42.92<td>16.94<td>  0.982</tr>
<tr><td align="left">039_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  60.24<td>  48.14<td>2<td>150<td>148<td>84.23<td>39.58<td>19.19<td>  0.984</tr>
<tr><td align="left">039_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   7.65<td>   6.11<td>2<td>76<td>222<td>78.52<td>42.12<td>17.40<td>  0.983</tr>
<tr><td align="left">039_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 247.61<td> 197.89<td>2<td>280<td>18<td>81.18<td>38.41<td>21.26<td>  0.983</tr>
<tr><td align="left">039_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  12.67<td>  10.13<td>2<td>76<td>222<td>81.40<td>41.47<td>17.70<td>  0.983</tr>
<tr><td align="left">039_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  25.80<td>  20.62<td>2<td>76<td>222<td>76.67<td>40.63<td>18.43<td>  0.983</tr>
<tr><td align="left">039_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   3.15<td>   2.52<td>2<td>76<td>222<td>76.52<td>43.13<td>16.88<td>  0.982</tr>
<tr><td align="left">039_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  58.84<td>  47.03<td>2<td>76<td>222<td>84.19<td>39.71<td>19.14<td>  0.983</tr>
<tr><td align="left">039_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   7.76<td>   6.20<td>2<td>76<td>222<td>69.94<td>42.11<td>18.17<td>  0.981</tr>
<tr><td align="left">039_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 197.19<td> 157.59<td>2<td>76<td>222<td>81.59<td>38.34<td>21.16<td>  0.983</tr>
</tbody></table>

[Back to Top](#idtext)

__________



### Sequence 040
[![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/thumbnails/040_480p.png)](https://drive.google.com/drive/folders/19YXXi2zxCMBf5oJ_vSJPhDa6McoGf0_V?usp=share_link)\
*__Figure 41__. First Frame of Sequence 040*

Raw Sequence Size: 14.21 GB\
Source: [HERE](https://drive.google.com/drive/folders/19YXXi2zxCMBf5oJ_vSJPhDa6McoGf0_V?usp=share_link)

<br>

*__Table 41__. Description of encoded videos using sequence 040 and their performance evaluation*<table><tbody align="right"><tr><td rowspan="2" align="left"><b><i>File<td rowspan="2"><b><i>Codec<td rowspan="2"><b><i>Resolution<td rowspan="2"><b><i>Pixel Format<td rowspan="2"><b><i>File Size (MB)<td rowspan="2"><b><i>Bitrate (MB)<td colspan="3"><b><i># Frame Types<td rowspan="2"><b><i>VMAF<td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">PSNR</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">MSE</SPAN><td rowspan="2"><b><i><SPAN STYLE="text-decoration:overline">SSIM</SPAN></tr>
<tr><td><b><i>I<td><b><i>P<td><b><i>B</tr><tr><td align="left">040_av1_1K.mp4<td align="center">AV1<td align="center">2048x1080<td rowspan="18">yuv420p<td>   6.15<td>   4.91<td>1<td>299<td>0<td> 6.76<td>37.77<td>182.92<td>  0.627</tr>
<tr><td align="left">040_av1_2K.mp4<td align="center">AV1<td align="center">2731x1440<td>  11.53<td>   9.22<td>1<td>299<td>0<td> 5.58<td>37.45<td>184.69<td>  0.630</tr>
<tr><td align="left">040_av1_480p.mp4<td align="center">AV1<td align="center">910x480<td>   2.71<td>   2.17<td>1<td>299<td>0<td>12.55<td>38.59<td>173.44<td>  0.627</tr>
<tr><td align="left">040_av1_4K.mp4<td align="center">AV1<td align="center">4096x2160<td>  22.98<td>  18.36<td>1<td>299<td>0<td> 4.71<td>37.10<td>185.90<td>  0.627</tr>
<tr><td align="left">040_av1_720p.mp4<td align="center">AV1<td align="center">1365x720<td>   4.02<td>   3.21<td>1<td>299<td>0<td> 8.58<td>38.18<td>179.53<td>  0.629</tr>
<tr><td align="left">040_av1_8K.mp4<td align="center">AV1<td align="center">8192x4320<td>  80.12<td>  64.03<td>1<td>299<td>0<td> 3.82<td>36.70<td>186.81<td>  0.628</tr>
<tr><td align="left">040_h264_1K.mp4<td align="center">H264<td align="center">2048x1080<td>  13.56<td>  10.84<td>2<td>76<td>222<td> 6.69<td>37.78<td>182.58<td>  0.629</tr>
<tr><td align="left">040_h264_2K.mp4<td align="center">H264<td align="center">2731x1440<td>  26.82<td>  21.43<td>2<td>79<td>219<td> 5.56<td>37.54<td>184.69<td>  0.630</tr>
<tr><td align="left">040_h264_480p.mp4<td align="center">H264<td align="center">910x480<td>   7.04<td>   5.63<td>2<td>76<td>222<td>12.47<td>38.58<td>174.10<td>  0.625</tr>
<tr><td align="left">040_h264_4K.mp4<td align="center">H264<td align="center">4096x2160<td>  61.05<td>  48.79<td>2<td>77<td>221<td> 4.74<td>37.08<td>186.20<td>  0.627</tr>
<tr><td align="left">040_h264_720p.mp4<td align="center">H264<td align="center">1365x720<td>   9.02<td>   7.21<td>2<td>76<td>222<td> 8.55<td>38.24<td>179.63<td>  0.629</tr>
<tr><td align="left">040_h264_8K.mp4<td align="center">H264<td align="center">8192x4320<td> 195.90<td> 156.56<td>2<td>78<td>220<td> 3.87<td>36.67<td>187.01<td>  0.628</tr>
<tr><td align="left">040_hevc_1K.mp4<td align="center">HEVC<td align="center">2048x1080<td>  13.19<td>  10.54<td>2<td>76<td>222<td> 6.76<td>37.66<td>182.80<td>  0.628</tr>
<tr><td align="left">040_hevc_2K.mp4<td align="center">HEVC<td align="center">2732x1440<td>  26.35<td>  21.06<td>2<td>76<td>222<td> 5.48<td>37.36<td>184.82<td>  0.629</tr>
<tr><td align="left">040_hevc_480p.mp4<td align="center">HEVC<td align="center">910x480<td>   6.94<td>   5.54<td>2<td>76<td>222<td>12.47<td>38.45<td>173.84<td>  0.626</tr>
<tr><td align="left">040_hevc_4K.mp4<td align="center">HEVC<td align="center">4096x2160<td>  59.25<td>  47.36<td>2<td>76<td>222<td> 4.74<td>36.99<td>185.97<td>  0.627</tr>
<tr><td align="left">040_hevc_720p.mp4<td align="center">HEVC<td align="center">1366x720<td>   8.99<td>   7.18<td>2<td>76<td>222<td> 8.39<td>38.01<td>180.00<td>  0.628</tr>
<tr><td align="left">040_hevc_8K.mp4<td align="center">HEVC<td align="center">8192x4320<td> 197.32<td> 157.70<td>2<td>76<td>222<td> 3.85<td>36.58<td>186.91<td>  0.628</tr>
</tbody></table>

[Back to Top](#idtext)

__________




## FFmpeg Commands

### Video Encoding Commands
**Base video encoding script**
```
ffmpeg -framerate 30000/1001 -pattern_type glob -i "${sequenceID}/*.png" -vf scale=-1:${scale} -b:v ${bitrate}$ -c:v ${encoder} -preset ${preset} "${sequenceID}_${codec}_${resolution}.mp4"
```
<br>

*__Table  42__. Variable alternatives used in generating encoded videos*
<table>

  <tr>
    <th>Variable</th>
    <th>Alternative</th>
    <th>Value</th>
  </tr>

  <tr>
    <td><code>${sequenceID}</code></td>
    <td>-</td>
    <td>from 000 to 040</td>
  </tr>
  <tr>
    <td rowspan="6"><code>${scale}</code></td>
    <td>8K</td>
    <td><code>4320</code></td>
  </tr>
  <tr>
    <td>4K</td>
    <td><code>2160</code></td>
  </tr>
  <tr>
    <td>2K</td>
    <td><code>1440</code></td>
  </tr>
  <tr>
    <td>1K</td>
    <td><code>1080</code></td>
  </tr>
  <tr>
    <td>720p</td>
    <td><code>720</code></td>
  </tr>
  <tr>
    <td>480p</td>
    <td><code>480</code></td>
  </tr>
  <tr>
    <td><code>${bitrate}</code></td>
    <td>-</td>
    <td>Depends on the required value. <br>Refer to <a href='#bitrates-used-for-each-video-codec-and-resolution-combination'>Table 1 </a> for the values used.</td>
  </tr>
  <tr>
    <td rowspan="3"><code>${encoder}</code></td>
    <td>HEVC/H265</td>
    <td><code>hevc_nvenc</code></td>
  </tr>
  <tr>
    <td>AVC/H264</td>
    <td><code>h264_nvenc</code></td>
  </tr>
  <tr>
    <td>AV1</td>
    <td><code>libaom-av1</code></td>
  </tr>
  <tr>
    <td rowspan="3"><code>${presets}</code></td>
    <td>HEVC/H265</td>
    <td><code>18</code></td>
  </tr>
  <tr>
    <td>AVC/H264</td>
    <td><code>18</code></td>
  </tr>
  <tr>
    <td>AV1</td>
    <td><code>slow</code></td>
  </tr>
</table>


[Back to Top](#idtext)
___



### Image Transforming Commands
**Base image transforming script**
```
ffmpeg -i "${imageID}/*.tif" -vf scale=-1:${scale} "${imageID}_${codec}_${resolution}.${extention}"
```
<br>

*__Table  43__. Variable alternatives used in generating encoded videos*
<table>

  <tr>
    <th>Variable</th>
    <th>Alternative</th>
    <th>Value</th>
  </tr>

  <tr>
    <td><code>${imageID}</code></td>
    <td>-</td>
    <td>from 000 to 040</td>
  </tr>
  <tr>
    <td rowspan="6"><code>${scale}</code></td>
    <td>8K</td>
    <td><code>4320</code></td>
  </tr>
  <tr>
    <td>4K</td>
    <td><code>2160</code></td>
  </tr>
  <tr>
    <td>2K</td>
    <td><code>1440</code></td>
  </tr>
  <tr>
    <td>1K</td>
    <td><code>1080</code></td>
  </tr>
  <tr>
    <td>720p</td>
    <td><code>720</code></td>
  </tr>
  <tr>
    <td>480p</td>
    <td><code>480</code></td>
  </tr>
  <tr>
    <td rowspan="3"><code>${extention}</code></td>
    <td>PNG</td>
    <td><code>png</code></td>
  </tr>
  <tr>
    <td>JPEG</td>
    <td><code>jpg</code></td>
  </tr>
  <tr>
    <td>WEBP</td>
    <td><code>webp</code></td>
  </tr>
</table>

[Back to Top](#idtext)
___


## Video Sequences Average RBG Histogram over time.
![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/Seq_Hist.png)
*__Figure 42.__ Average RBG Histogram over time for all the sequences in the SEPE dataset*

[Back to Top](#idtext)
___


## Images Histogram over time.
![Seq# 1](https://raw.githubusercontent.com/talshoura/SEPE-8K-Dataset/main/assets/Images_Hist.png)
*__Figure 43.__ RBG Histogram for all images in the SEPE dataset*

[Back to Top](#idtext)
___

