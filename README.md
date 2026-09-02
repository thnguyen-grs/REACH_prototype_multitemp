An end-to-end Python script to be run every day at 6am (using Cron).

0 6 * * * /home/thnguyen/miniforge3/envs/climada_env/bin/python /home/thnguyen/gitlab/ewers/climada_workspace/climada_petals/REACH_basic.py >> /home/thnguyen/gitlab/ewers/climada_workspace/climada_petals/REACH_basic.log 2>&1
