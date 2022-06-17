# COMP20008-A2

**Co-authors:** Ron Chen <br />
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Aoxiang Xiao <br />
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Un Leng Kam <br />

Programmes used: Python and Excel<br />
Libraries used: pandas, NumPy, re, matplotlib, sklearn, math and statistics

Suggested code order and file requirements (input/output) for code produced
1. Chen1-process_suburb_1.ipynb<br />
Input: School.csv<br />
Output: lgapostcode_draft.csv<br />

2. Chen2-process_lga.ipynb<br />
Input: lgapostcode_draft.csv<br />
Output: lga_draft2.csv<br />

3. Chen3-process_keys.ipynb<br />
Input: lga_draft2.csv; School.csv<br />
Output: lga_postcode.csv<br />

4. Chen4-new_lga.ipynb<br />
Input: lga_draft2.csv<br />
Output: new_lgas.csv<br />

5. Chen5-new_keys.ipynb<br />
Input: lga_postcode.csv<br />
Output: new_keys.csv<br />

6. Chen-process_ambo.ipynb<br />
Input: new_keys.csv; new_lgas.csv; LGA-Response-Time-Performance-FY-2019.csv<br />
Output: response_time_tally.csv<br />

7. Chen-process_Facility.ipynb<br />
Input: new_keys.csv; new_lgas.csv; Sport_and_recreation.csv<br />
Output: facility_tally.csv<br />

8. Chen-process_openspace.ipynb<br />
Input: new_keys.csv; new_lgas.csv; VPA_Open_Space.csv<br />
Output: open_space_tally.csv<br />

9. Chen-process_violence_rate.ipynb<br />
Input: new_lgas.csv; Ambulance Victoria Data Tables - 2019-20.xlsx' [Table 3]<br />
Output: crime_rate.csv<br />

10. Kam-process_housprice_to_stats.ipynb<br />
Input: new_keys.csv; Suburb_House_final.csv; lga_fill_Median_House_Price-2019.csv <br />
Output: Median_House_Price-2019.csv; LGA_House_Price-2019+stats.csv<br />

11. Kam-process_living_standard_NMI.ipynb<br />
Input: Compilation_normalised.csv; Crime_noout.csv; Facility_noout.csv; Greena_noout.csv; ResponseTime_noout.csv; School_noout.csv<br />
Output: HPvsLSnmi_nolabels.png; HPvsLSnmi_labels.png; house_price+stats+lsscore.csv<br />

12. AoXiang-NMI-plot_5attributes.ipynb<br />
Input: Compilation_normalised.csv<br />
Output: NMI values of MHP to Attributes; HPvsCR.png; HPvsFT.png; HPvsOA.png; HPvsRT.png; HPvsST.png<br />


13. AoXiang-create-table.ipynb<br />
Input:house_price+stats+lsscore.csv<br />
Output:liveability table;lga_attributes table<br />

14. Chen-compilation.ipynb<br />
Input: LGA_House_Price-2019+stats.csv; crime_rate.csv; facility_tally.csv; open_space_tally.csv; response_time_tally.csv; school_tally.csv; LGA_area_population.csv<br />
Output: Compilation.csv; Compilation_normalised.csv<br />

15. Calc_Outlier.ipynb<br />
Input: house_price+stats+lsscore.csv<br />
Output: calculated which of the LGAs were outliers with respect to the linear regression<br />
