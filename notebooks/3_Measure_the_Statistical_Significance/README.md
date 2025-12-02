# Measure the Statistical Significance

## Download the required data from GWOSC

```bash
pycwb gwosc-data user_parameters.yaml
```

## Submit the job

For HTCondor submission, run:

```bash
pycwb batch-setup user_parameters.yaml -c condor -d . -e pycwb-0.30.1 -j 1 -m 12G -g ligo.dev.o4.burst.allsky.cwboffline 
```

> At the moment, you need to remove 

## Explaination to the real world example