# Demo outputs:
1. 我愛你

https://user-images.githubusercontent.com/23226987/230714939-130cea33-f393-4b9b-ae72-703ba8ae8ea7.mp4



# Instructions
1. Create a virtual environment
python -m venv ./venv

2. open demo.ipynb and install the dependencies

3. move files to opencc lib after installing opencc
    1. mv ./opencc/jyutjyu.json ./venv/lib/site-packages/opencc/clib/share/opencc/jyutjyu.json
    2. mv ./opencc/jyutjyu.ocd2 ./venv/lib/site-packages/opencc/clib/share/opencc/jyutjyu.ocd2

4. build cpython codes
cd vits/monotonic_align
python setup.py build_ext --inplace

5. download models

    1. https://huggingface.co/xiaomaiiwn/vits-cantonese/blob/main/model/G.pth

# Acknowledgement
I do not own the models and you should follow the license of the models.
