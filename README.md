# EDNtuple
Dumping ground for a quick EDNtuple proposal

## Installation

From your source directory:
```
git cms-merge-topic ikrav:egm_id_phys14
git clone https://github.com/CMSRA2Tau/EDNtuple.git BSM3GAna/EDNtuple
cd ..
scram b -j 10
```

## Running

The CMSSW configuration lives at `EDNtuple/test/bsm_3g_tuple.py`. It accepts
miniAOD and emits an EDNtuple
