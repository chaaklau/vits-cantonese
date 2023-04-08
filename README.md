# Demo outputs:
1. 我愛你

https://user-images.githubusercontent.com/23226987/230714939-130cea33-f393-4b9b-ae72-703ba8ae8ea7.mp4



# Instructions
1. Create a virtual environment
python -m venv ./venv

2. open demo.ipynb and install the dependencies

3. move files to opencc lib after installing opencc
mv ./opencc/jyutjyu.json ./venv/lib/site-packages/opencc/clib/share/opencc/jyutjyu.json
mv ./opencc/jyutjyu.ocd2 ./venv/lib/site-packages/opencc/clib/share/opencc/jyutjyu.ocd2

4. build cpython codes
cd vits/monotonic_align
python setup.py build_ext --inplace

5. download models

    1. https://drive.google.com/file/d/1E1ZnHs13mGmtn_NNQR2fxauxpGxJZnPh/view?usp=share_link
taken from https://huggingface.co/xiaomaiiwn/vits-cantonese/blob/main/model/G.pth

    2. https://drive.google.com/file/d/1XneBFAywWiNGh5Ff3spyTNlLNu7yvDLF/view?usp=share_link
taken from https://sjtueducn-my.sharepoint.com/personal/cjang_cjengh_sjtu_edu_cn/_layouts/15/onedrive.aspx?ga=1&id=%2Fpersonal%2Fcjang%5Fcjengh%5Fsjtu%5Fedu%5Fcn%2FDocuments%2Fvits%2Fvits%5Fmodels%2Fchinese%5Fdialects

# Acknowledgement
I do not own the models and you should follow the license of the models.
