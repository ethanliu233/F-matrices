The algorithm is based on the paper: https://doi.org/10.1016/S0550-3213(99)00125-X.(https://www.sciencedirect.com/science/article/pii/S055032139900125X)
The F-matrices are also normalized as in the above paper.
To see a full list of conformal dimension of the existing fields, use Hlist.
To see what is the index for a primary field with Kac index (r,s), use orderer[r,s].
With the index obtained as above:
To check the fusion rule among fields a,b,c, use Fusion[[a,b,c]]
To obatin the value of such F-mattrix element:
$$
\mathrm{~F}_{\mathrm{pq}}\left[\begin{array}{cc}
j & k \\
i & \ell
\end{array}\right]
$$
use F[[j,k,i,l,p,q]]
