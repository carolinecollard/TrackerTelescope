# TrackerTelescope

cmsrel CMSSW_9_2_13

cd CMSSW_9_2_13/src/

git init

git clone https://github.com/carolinecollard/TrackerTelescope.git

mv TrackerTelescope/RecoTracker .

mv TrackerTelescope/Configuration .

scramv1 b

cmsenv

cmsRun TrackerTelescope/test_caro/Config_reco.py
