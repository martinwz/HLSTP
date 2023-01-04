# HLSTP

# The following two tables record the details of all reported bugs found by HLSTP (Update by 2023-01-03).

## Miscompile bugs

| No.  |                           Bug Report Title                            |     Buggy Pragmas      |    Status     |
| :--: | :---------------------------------------------------------: | :------------: | :-----------: | 
|  1  | [BUG REPORT: using pragmas makes Vitis HLS v2020.02 and v2022.02 synthesis the code incorrectly.](https://support.xilinx.com/s/question/0D54U00005wTKbcSAG/bug-report-using-pragmas-makes-vitis-hls-v202002-and-v202202-synthesis-the-code-incorrectly) | loop_merge, expression_balance, pipeine | Pending  |
|  2  | [BUG REPORT: both Vitis HLS v2020.02 and v2022.02 cannot synthesis the code correctly and report co-simulation failed when using by using loop_merge and allocation pragmas.](https://support.xilinx.com/s/question/0D54U00005wTHToSAO/bug-report-both-vitis-hls-v202002-and-v202202-cannot-synthesis-the-code-correctly-and-report-cosimulation-failed-when-using-by-using-loopmerge-and-allocation-pragmas)  |    loop_merge, allocation    | Pending |
|  3  | [BUG REPORT: both Vitis HLS v2020.02 and v2022.02 report co-simulation failed when using loop_merge and pipeline pragmas in two different functions.](https://support.xilinx.com/s/question/0D54U00005wTGlhSAG/bug-report-both-vitis-hls-v202002-and-v202202-report-cosimulation-failed-when-using-loopmerge-and-pipeline-pragmas-in-two-different-functions)  |    loop_merge, pipeline  | Pending |
|  4  | [BUG REPORT: Co-simulation failed in both Vitis HLS v2020.02 and v2022.02 caused by using pipeline, latency and allocation pragmas in one function at the same time.](https://support.xilinx.com/s/question/0D54U00005wTGYmSAO/bug-report-cosimulation-failed-in-both-vitis-hls-v202002-and-v202202-caused-by-using-pipeline-latency-and-allocation-pragmas-in-one-function-at-the-same-time) | pipeline, latency, allocation | Pending |
|  5  | [BUG REPORT: Co-simulation failed occurred in both Vitis HLS v2020.02 and v2022.02, when we apply array_partition pragma to a two-dimensional array.](https://support.xilinx.com/s/question/0D54U00005wSdnESAS/bug-report-cosimulation-failed-occurred-in-both-vitis-hls-v202002-and-v202202-when-we-apply-arraypartition-pragma-to-a-twodimensional-array)  |    array_partition    | **Confirmed** |
|  6  | [BUG REPORT: Co-simulation failed occurred in both Vitis HLS v2020.02 and v2022.02, when we use inline, pipeline and latency pragmas in two different functions at the time.](https://support.xilinx.com/s/question/0D54U00005wScWvSAK/bug-report-cosimulation-failed-occurred-in-both-vitis-hls-v202002-and-v202202-when-we-use-inline-pipeline-and-latency-pragmas-in-two-different-functions-at-the-time)  |    pipeline, latency, inline off  | Pending |
|  7  | [BUG REPORT: Co-simulation failed occurred in both Vitis HLS v2020.02 and v2022.02, when we use inline, pipeline and reset pragmas in two different functions at the time.](https://support.xilinx.com/s/question/0D54U00005wScF5SAK/bug-report-cosimulation-failed-occurred-in-both-vitis-hls-v202002-and-v202202-when-we-use-inline-pipeline-and-reset-pragmas-in-two-different-functions-at-the-time)  |   inline off, pipeline, reset  |  Pending |
|  8  | [BUG REPORT: Co-simulation failed occurred in both Vitis HLS v2020.02 and v2022.02, when we use pipeline and expression_balance pragmas in different two functions at the time.](https://support.xilinx.com/s/question/0D54U00005wRfsOSAS/bug-report-cosimulation-failed-occurred-in-both-vitis-hls-v202002-and-v202202-when-we-use-pipeline-and-expressionbalance-pragmas-in-different-two-functions-at-the-time)  |   pipeline, expression_balance  | **Confirmed** |
|  9  | [BUG REPORT: When using inline off pragma in two different functions at the same time, both Vitis HLS v2020.02 and v2022.02 report co-simulation failed.](https://support.xilinx.com/s/question/0D54U00005wRfpASAS/bug-report-when-using-inline-off-pragma-in-two-different-functions-at-the-same-time-both-vitis-hls-v202002-and-v202202-report-cosimulation-failed)  |   inline off  | Pending |
|  10  | [BUG REPORT: When using pipeline pragmas in different two functions at the time, co-simulation failed occurred in both Vitis HLS v2020.02 and v2022.02.](https://support.xilinx.com/s/question/0D54U00005wRfmRSAS/bug-report-when-using-pipeline-pragmas-in-different-two-functions-at-the-time-cosimulation-failed-occurred-in-both-vitis-hls-v202002-and-v202202)  |   pipeline pragmas in two functions  | **Confirmed** |
|  11  | [BUG REPORT: A pragma-related bug is triggered in both Vitis HLS v2022.02 and v2020.02 when expression_balance, array_partition and pipeline pragmas are applied to the code.](https://support.xilinx.com/s/question/0D54U00005zHZjVSAW/bug-report-a-pragmarelated-bug-is-triggered-in-both-vitis-hls-v202202-and-v202002-when-expressionbalance-arraypartition-and-pipeline-pragmas-are-applied-to-the-code)  |  expression_balance, array_partition, pipeline   | Pending |
|  12  | [Pragma-Related BUG REPORT: using pipeline, reshape and inline off pragmas at the same times makes Vitis HLS v2022.02 report co-simulation failed.](https://support.xilinx.com/s/question/0D54U000064Y75GSAS/pragmarelated-bug-report-using-pipeline-reshape-and-inline-off-pragmas-at-the-same-times-makes-vitis-hls-v202202-report-cosimulation-failed)  |  pipeline, array_reshape, inline off   | Pending |
|  13  | [Pragma-Related BUG REPORT: Vitis HLS v2022.02 reports co-simulation failed when we insert some pragmas into our code.](https://support.xilinx.com/s/question/0D54U000064Y7RwSAK/pragmarelated-bug-report-vitis-hls-v202202-reports-cosimulation-failed-when-we-insert-some-pragmas-into-our-code)  |  pipeline, latency, inline off, function_instantiate   | Pending |
|  14  | [Pragma-Related BUG REPORT: RTL output is inconsistent with its golden output when we insert some pragmas into our code.](https://support.xilinx.com/s/question/0D54U000064Y7qSSAS/pragmarelated-bug-report-rtl-output-is-inconsistent-with-its-golden-output-when-we-insert-some-pragmas-into-our-code)  |  reset off, latency   | Pending |
|  15  | [Pragma-Related BUG REPORT: when we turn off inline, pipeline in some functions and reshape an array at the same times, RTL verilog simulation output is inconsistent with its golden output in Vitis HLS v2022.02.](https://support.xilinx.com/s/question/0D54U000064Y80mSAC/pragmarelated-bug-report-when-we-turn-off-inline-pipeline-in-some-functions-and-reshape-an-array-at-the-same-times-rtl-verilog-simulation-output-is-inconsistent-with-its-golden-output-in-vitis-hls-v202202)  |  array_reshape, pipeline off, inline off, pipeline off   | Pending |
|  16  | [Pragma-Related Issue: both Vitis HLS v2020.02 and v2022.02 report co-simulation failed when we prevent a function be inlined and apply allocation pragma to it.](https://support.xilinx.com/s/question/0D54U000064bq5xSAA/pragmarelated-issue-both-vitis-hls-v202002-and-v202202-report-cosimulation-failed-when-we-prevent-a-function-be-inlined-and-apply-allocation-pragma-to-it)  |  inline off, allocation   | Pending |
|  17  | [Co-simulation failed Issue: the simulation result doesn’t match the golden output in Vitis HLS v2022.02 when we use some pragmas.](https://support.xilinx.com/s/question/0D54U000067nmCCSAY/cosimulation-failed-issue-the-simulation-result-doesnt-match-the-golden-output-in-vitis-hls-v202202-when-we-use-some-pragmas)  |  array_reshape, pipeline, latency, allocation  | Pending |
|  18  | [Pragma-related Issue: Using reset off and inline off in one function causes Vitis HLS cannot synthesis the code correctly.](https://support.xilinx.com/s/question/0D54U000067oli4SAA/pragmarelated-issue-using-reset-off-and-inline-off-in-one-function-causes-vitis-hls-cannot-synthesis-the-code-correctly)  |  inline off, reset off  | Pending |

## Crash bugs

| No.  |                           Bug Report Title                            |     Buggy Pragmas      |    Status     |
| :--: | :---------------------------------------------------------: | :------------: | :-----------: |
|  1  | [Pragma-Related BUG REPORT: Vitis HLS v2022.02 crashed when we apply some pragmas to the code.](https://support.xilinx.com/s/question/0D54U000064Y8CJSA0/pragmarelated-bug-report-vitis-hls-v202202-crashed-when-we-apply-some-pragmas-to-the-code) | pipeline, loop_merge protocol, dependence  | **Confirmed** |
|  2  | [Pragma-Related BUG REPORT: Vitis HLS v2022.02 stop synthesis process abnormally when we apply some pragmas to the code.](https://support.xilinx.com/s/question/0D54U000064Y8PJSA0/pragmarelated-bug-report-vitis-hls-v202202-stop-synthesis-process-abnormally-when-we-apply-some-pragmas-to-the-code)  |  pipeline loop_merge, protocol, inline off  | Pending |
|  3  | [Crash Issue: Vitis HLS v2020.02 and v2022.02 stop synthesis process abnormally when we apply some pragmas to the code.](https://support.xilinx.com/s/question/0D54U000064a0k9SAA/crash-issue-vitis-hls-v202002-and-v202202-stop-synthesis-process-abnormally-when-we-apply-some-pragmas-to-the-code)  |  inline off, function_instantiate  | **Confirmed** |
|  4  | [Abnormal program termination Issue: Vitis HLS v2022.02 cannot finish the synthesis process.](https://support.xilinx.com/s/question/0D54U000064bZ3ZSAU/abnormal-program-termination-issue-vitis-hls-v202202-cannot-finish-the-synthesis-process)  |  pipeline, protocol  | **Duplicated**  |
|  5  | [Pragma-related Crash Issue: using protocol pragma cause Vitis HLS v2022.02 crash.](https://support.xilinx.com/s/question/0D54U000064bZLJSA2/pragmarelated-crash-issue-using-protocol-pragma-cause-vitis-hls-v202202-crash)  |  protocol  | **Confirmed** |
|  6  | [Vitis v2022.02 Crash Issue: Vitis HLS v2022.02 crashed when using some pragmas.](https://support.xilinx.com/s/question/0D54U000067prMRSAY/vitis-v202202-crash-issue-vitis-hls-v202202-crashed-when-using-some-pragmas)  |  pipeline, allocation, function_instantiate and inline off  | Pending |


## Performance bugs
| No.  |                           Bug Report Title                            |     Buggy Pragmas      |    Status     |
| :--: | :---------------------------------------------------------: | :------------: | :-----------: | 
|  1  | [Performance Issue: Vitis HLS v2022.02 hung on synthesis process more than 10 minutes when we apply some pragmas to the code.](https://support.xilinx.com/s/question/0D54U000064ZHSSSA4/performance-issue-vitis-hls-v202202-hangs-on-synthesis-process-more-than-10-minutes-when-we-apply-some-pragmas-to-the-code) | allocation, pipeline  | Pending |
|  2  | [Hanging on "Using interface defaults for 'Vivado' flow target." Issue: Vitis HLS v2022.02 hangs on the synthesis process when we apply some pragmas to the code.](https://support.xilinx.com/s/question/0D54U000064ZJVFSA4/hanging-on-using-interface-defaults-for-vivado-flow-target-issue-vitis-hls-v202202-hangs-on-the-synthesis-process-when-we-apply-some-pragmas-to-the-code)  |    pipeline, array_reshape    | Pending |
|  3  | [Endless synthesis process Issue: Vitis HLS v2022.02 unable to end the synthesis process when we apply array_partition pragma to the code.](https://support.xilinx.com/s/question/0D54U000064ZMr7SAG/endless-synthesis-process-issue-vitis-hls-v202202-unable-to-end-the-synthesis-process-when-we-apply-arraypartition-pragma-to-the-code)  |  array_partition  | Pending |
|  4  | [Non-termination Issue: Vitis HLS hang on “Exploring resource sharing” for hours.](https://support.xilinx.com/s/question/0D54U000067on4jSAA/nontermination-issue-vitis-hls-hang-on-exploring-resource-sharing-for-hours?language=en_US)  |  protocol  | Pending |
