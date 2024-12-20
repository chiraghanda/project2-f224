Latest Logs From Latest Build
==============================

Generated On: 2024-12-05 17:01:34 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/chiraghanda/raspberrypi/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-12-05_16:55:59] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-12-05_16:56:03] STEP 2: Create topics started

  [INFO 2024-12-05_16:56:20] STEP 2: Completed

  [INFO 2024-12-05_16:56:28] STEP 3: producing data started

  [INFO 2024-12-05_16:56:32] MQTT connection established...

  [INFO 2024-12-05_16:56:32] STEP 4: Preprocessing started

  [INFO 2024-12-05_16:56:36] STEP 4: Preprocessing started

  [INFO 2024-12-05_16:56:37] STEP 7: Visualization started

  [INFO 2024-12-05_16:56:44] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-12-05_16:56:51] STEP 9: Starting privateGPT

  [INFO 2024-12-05_16:56:59] STEP 8: Starting docker push for: chiraghanda/project2-f224-amd64

  [INFO 2024-12-05_16:57:42] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --env PORT=8001 --env GPU=0 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-no-gpu-amd64

  [INFO 2024-12-05_16:57:47] STEP 8: Docker Container created.  Will push it now.  Here is the commit command: docker commit 71f0e8c4b600 chiraghanda/project2-f224-amd64 - message=0

  [INFO 2024-12-05_17:01:22] STEP 8: Successfully ran Docker push: docker push chiraghanda/project2-f224-amd64 - message=0

  [INFO 2024-12-05_17:01:33] STEP 10: Started to build the documentation

  [INFO 2024-12-05_17:01:34] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


