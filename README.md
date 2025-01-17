Contains test code to reproduce the S3 RMT issue with FastLED.

See issue https://github.com/FastLED/FastLED/pull/1652

**this codebase now tests the fix in the fastled branch, see pull request https://github.com/FastLED/FastLED/pull/1652 which links in the fix at https://github.com/FastLED/FastLED/tree/fix-esp32-s3-rmt-esp-idf-5**

This is what you'll need to do to test this repo:

  1. Install VSCode
  2. Open up the extensions panel and install platformio
  3. `git clone https://github.com/zackees/fastled_bug_s3_idf5x`
  4. Open up `fastled_bug_s3_idf5x` directory in VSCode
  5. Wait a couple of minutes for the dependencies to install. If things take longer than 10 mins then cancel the update terminal (it's safe) and hit the compile button, it's the check mark button on the bottom menu bar:
  
  
<img width="192" alt="image" src="https://github.com/user-attachments/assets/bb3b8046-ecde-4008-b16f-19e572852b94">

Now you should see that your project compiles fine. If the dependencies weren't completely installed it will do it now then compile your program.

  6. Hit the right arrow (see picture above) which will upload the firmware to your s3 device.
  7. Verify that it works (or doesn't) and report back to here, tagging me with the @zackees symbol so that i get a notification.


  
