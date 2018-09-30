# utl-using-triple-letter-tokens-for-naming-projects-variables-folderss-and-self-locating-files
Using triple letter tokens for naming projects variables folders and self locating files.

    Using triple letter tokens for naming projects variables folders and self locating files

    Many exceptions gladly accepted, this is not a rigid guideline.

    We have Systolic and Diastolic blood pressure measurements taken sitting and laying down
    at many dates.

    Think of  Kingdom, Phylum, Class and Order hierarchy

    For sitting systolic blood pressure, why not use

       BpsSitDte instrad of 'SPBDATESIT'

            Bp    Blood Pressure                  Kingdom
             s    s - systolic, d-diastolic       Phylum
           Sit    Lay - Supine, Sit - Sitting     Class
           Dte    Dte, WekAve, WekMax DteMax ..   Order

    I have seen clinical trials tha use 'SPBDATESIT'

      Some Possble BP names using TLA building blocks)

          BpdLayDte
          BpdLayWekAve  ( same number of lettters as SPBDATESUPN )

          BpsLayDte
          BpsLayDteMax

          BpdSitDte
          BpdSitWekMin

          BpsSitDte
          BpsSitMthMax

    I also use TLA hierachies with my filenames and folders.

    rtf reports for project dna are in

    dns/rtf

    dna/rtf/dna_BasExpSex.rtf
    dna/rtf/dna_BasExpAge.rtf
    dna/rtf/dna_BasExpBsa.rtf
    dna/rtf/dna_BasExpStg.rtf

    Self Locating files

    If I send the expossure report by sex to Joe

       dna_BasExpSex.rtf

    and a year later Joe sensd the name of the
    file and asks me to resens

    I can instantly locate the report using the tokens
    in the filename

    root folder is
        dna
    subfolder
        rtf

    the report is located at

    /dna/rtf/dna_BasExpAge.rtf



