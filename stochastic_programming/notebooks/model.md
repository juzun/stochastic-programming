$$
\begin{align} 
    & \max \\
    & 0.5  \left( 210  \left( build\_now[1] + build\_later[s1,1] \right)  - 220 build\_later[s1,1] + 210  \left( build\_now[2] + build\_later[s1,2] \right)  - 660 build\_later[s1,2] \right) + \\
    & 0.5  \left( 1250  \left( build\_now[1] + build\_later[s2,1] \right)  - 220 build\_later[s2,1] + 1250  \left( build\_now[2] + build\_later[s2,2] \right)  - 660 build\_later[s2,2] \right) - \\
    & \left( 200 build\_now[1] + 600 build\_now[2] \right)  -  \left( 600 develop\_land[1] + 100 develop\_land[2] \right)
    & \tag{1} \\
    & \text{s.t.} \\
    & build\_now[1] + build\_later[s1,1] \leq 1 & \tag{2} \\
    & build\_now[2] + build\_later[s1,2] \leq 1 & \tag{3} \\
    & build\_now[1] + build\_later[s2,1] \leq 1 & \tag{4} \\
    & build\_now[2] + build\_later[s2,2] \leq 1 & \tag{5} \\
    & build\_now[1] + build\_later[s1,1] \leq develop\_land[1] & \tag{6} \\
    & build\_now[2] + build\_later[s1,2] \leq develop\_land[2] & \tag{7} \\
    & build\_now[1] + build\_later[s2,1] \leq develop\_land[1] & \tag{8} \\
    & build\_now[2] + build\_later[s2,2] \leq develop\_land[2] & \tag{9} \\
    & \text{w.b.} \\
    & develop\_land & \qquad \in \left\{ 0 , 1 \right \} \tag{10} \\
    & build\_now & \qquad \in \left\{ 0 , 1 \right \} \tag{11} \\
    & build\_later & \qquad \in \left\{ 0 , 1 \right \} \tag{12} \\
\end{align}
$$