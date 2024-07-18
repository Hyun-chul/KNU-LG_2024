2024 KNU-LG Summer Education



=== 코랩 환경에서 한글 사용하기 


!sudo apt-get install -y fonts-nanum


!sudo fc-cache -fv


!rm ~/.cache/matplotlib -rf

import matplotlib.pyplot as plt


plt.rc('font', family='NanumBarunGothic') 


plt.rcParams['axes.unicode_minus'] =False
