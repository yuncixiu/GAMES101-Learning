# GAMES101-Learning
该项目是我看闫令琪老师的games101的笔记整理，如有错误，请改正
## lecture1 Rodrigues's Rotation Formula(罗德里格斯公式)
用法 : 已知绕哪一个单位轴n和旋转角度α，求对应的3 × 3矩阵R
公式 : **R(n,α) = I*cosα + (1-cosα)nn^T + sinα*N**
变量含义 ； n->旋转轴，是一个三维列向量(nx,ny,nz)^T，并且它是一个单位向量
           I->一个3×3的单位矩阵
           N->旋转轴n对应的叉积矩阵，具体形式为[0 -nz ny]
                                            [nz 0 -nx]
                                            [-ny nx 0]
            作用；用矩阵乘法代替向量的叉积，比如对任意的向量 v ，都有 Nv = n×v
                                                
