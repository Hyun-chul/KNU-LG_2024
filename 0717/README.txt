
=== Vector를 raw-wise concatenation 방법 == 

import numpy as np

# 예제 벡터
vector1 = np.array([1, 2, 3])
vector2 = np.array([4, 5, 6])

# 행으로 연결
concatenated = np.vstack((vector1, vector2))

print("Concatenated Vectors as Rows:\n", concatenated)
