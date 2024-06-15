# Air Drawing Using OpenCV

> Prerequisities
* Install python 3.6 from python [website.](python.org)
* Install python environment using the following command

        $: pip install pipenv


> Installation necessary Libraries

* Download the files from the given [link.](https://github.com/UthejD/airdrawing/archive/refs/heads/master.zip)
* Unzip the downladed file into your projects work directory
* Open command promt and navigate to the **"airdrawing/windows"**  folder
* Install all the necessary library by using the following command

        $: pipenv install --python=3.6
* Then activate python virtual environment by using following command

        $: pipenv shell
* Change the directory form **"airdrawing-master/windows"** to **"airdrawing-master/windows/src"**

* Then run the following command to excute the code which will open a video feed and a canvas which is used to write

                $: python airdrawing.py

![video feed](../output_img/1.png)

* Show Green color which acts as pen tip which will trigger the drawing.
![Drawing](../output_img/2.png)

* You can close or terminate the code by pressing ***'q'***

**Node:** Please close the program as mention above which will make sure all windows are closed and camera modules is made free. If this method is not used camera might get stuck or will go into unrecoved mode.

