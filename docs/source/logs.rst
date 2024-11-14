Latest Logs From Latest Build
==============================

Generated On: 2024-11-14 21:02:51 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/navdeeptura/raspberrypi/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-11-14_21:00:10] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-11-14_21:00:16] STEP 2: Create topics started

  [INFO 2024-11-14_21:00:31] STEP 2: Completed

  [INFO 2024-11-14_21:00:42] STEP 3: producing data started

  [INFO 2024-11-14_21:00:46] MQTT connection established...

  [INFO 2024-11-14_21:00:47] STEP 4: Preprocessing started

  [INFO 2024-11-14_21:00:50] STEP 4: Preprocessing started

  [INFO 2024-11-14_21:00:52] STEP 7: Visualization started

  [INFO 2024-11-14_21:00:58] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-11-14_21:01:06] STEP 9: Starting privateGPT

  [INFO 2024-11-14_21:01:16] STEP 8: Starting docker push for: navdeeptura/navdeepproject14nov2-11f8-amd64

  [INFO 2024-11-14_21:01:25] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --env PORT=8001 --env GPU=0 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-no-gpu-amd64

  [INFO 2024-11-14_21:01:44] STEP 8: Docker Container created.  Will push it now.  Here is the commit command: docker commit 1c109e875262 navdeeptura/navdeepproject14nov2-11f8-amd64 - message=0

  [INFO 2024-11-14_21:02:26] STEP 8: Successfully ran Docker push: docker push navdeeptura/navdeepproject14nov2-11f8-amd64 - message=0

  [INFO 2024-11-14_21:02:50] STEP 10: Started to build the documentation

  [INFO 2024-11-14_21:02:52] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


