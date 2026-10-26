# [SAR Imaging] Point Target Simulation, Matched Filtering, CS/RD Imaging, and Motion Compensation [with MATLAB Code]

This experiment utilizes the raw data from RADARSAT-1, collected on June 16, 2002, in the Vancouver area of Canada. The data is stored in the file dat_01.001 and comprises nearly 19,400 records, each containing a transmission pulse's copy signal. Each distance line has 9,288 echo sample points, stored as uint type. Excluding the copy signal, this record totals 18,818 bytes, which are first 192 bytes of header information and 50 bytes of auxiliary information, followed by 18,576 bytes of echo data.
3. Run the 'specify_parameters.m' file to obtain two SAR echo data (modify the parameters to obtain data from different areas for imaging).
4. The data is stored in the CD_run_params.mat file. For detailed explanation, refer to the 'Extracting_SAR_Data_from_the_CD.pdf' document.
Normally, running SAR_RADARSAT1_CSA.m will yield simulation results transformed into the 2D frequency domain, achieving RC, SRC, consistent RCMC, azimuth compression, and additional phase correction. (Note: Make sure to modify the dataset directory to your own directory.)
Results

## Images

![(SAR Imaging)Point Target Simulation, Matched Filtering, CS/RD Imaging, Motion Compensation [with MATLAB Code]](01.jpg)
![(SAR Imaging)Point Target Simulation, Matched Filtering, CS/RD Imaging, Motion Compensation [with MATLAB Code]](02.jpg)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
