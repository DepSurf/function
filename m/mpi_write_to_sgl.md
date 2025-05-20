# Function: <code>mpi_write_to_sgl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mpi_write_to_sgl(MPI a, struct scatterlist *sgl, unsigned int *nbytes, int *sign);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff81416ec0)
Location: lib/mpi/mpicoder.c:350
Inline: False
```
**Symbols:**

```
ffffffff81416ec0-ffffffff814170ee: mpi_write_to_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mpi_write_to_sgl(MPI a, struct scatterlist *sgl, unsigned int nbytes, int *sign);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff8145eb80)
Location: lib/mpi/mpicoder.c:247
Inline: False
Direct callers:
  - crypto/rsa.c:rsa_verify
  - crypto/rsa.c:rsa_sign
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff8145eb80-ffffffff8145ed27: mpi_write_to_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mpi_write_to_sgl(MPI a, struct scatterlist *sgl, unsigned int nbytes, int *sign);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff8147d650)
Location: lib/mpi/mpicoder.c:247
Inline: False
Direct callers:
  - crypto/rsa.c:rsa_verify
  - crypto/rsa.c:rsa_sign
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff8147d650-ffffffff8147d7f7: mpi_write_to_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mpi_write_to_sgl(MPI a, struct scatterlist *sgl, unsigned int nbytes, int *sign);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff81486b60)
Location: lib/mpi/mpicoder.c:247
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_verify
  - crypto/rsa.c:rsa_sign
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff81486b60-ffffffff81486cf8: mpi_write_to_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mpi_write_to_sgl(MPI a, struct scatterlist *sgl, unsigned int nbytes, int *sign);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff814c2ce0)
Location: lib/mpi/mpicoder.c:247
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_verify
  - crypto/rsa.c:rsa_sign
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff814c2ce0-ffffffff814c2e78: mpi_write_to_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mpi_write_to_sgl(MPI a, struct scatterlist *sgl, unsigned int nbytes, int *sign);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff814f3c30)
Location: lib/mpi/mpicoder.c:247
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_verify
  - crypto/rsa.c:rsa_sign
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff814f3c30-ffffffff814f3dba: mpi_write_to_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mpi_write_to_sgl(MPI a, struct scatterlist *sgl, unsigned int nbytes, int *sign);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff81507f60)
Location: lib/mpi/mpicoder.c:247
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_verify
  - crypto/rsa.c:rsa_sign
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff81507f60-ffffffff8150810e: mpi_write_to_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mpi_write_to_sgl(MPI a, struct scatterlist *sgl, unsigned int nbytes, int *sign);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff815360c0)
Location: lib/mpi/mpicoder.c:247
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff815360c0-ffffffff81536268: mpi_write_to_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mpi_write_to_sgl(MPI a, struct scatterlist *sgl, unsigned int nbytes, int *sign);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff81556ed0)
Location: lib/mpi/mpicoder.c:247
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff81556ed0-ffffffff81557078: mpi_write_to_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mpi_write_to_sgl(MPI a, struct scatterlist *sgl, unsigned int nbytes, int *sign);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff815e0790)
Location: lib/mpi/mpicoder.c:247
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff815e0790-ffffffff815e091c: mpi_write_to_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mpi_write_to_sgl(MPI a, struct scatterlist *sgl, unsigned int nbytes, int *sign);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff81601dd0)
Location: lib/mpi/mpicoder.c:354
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff81601dd0-ffffffff81601f61: mpi_write_to_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mpi_write_to_sgl(MPI a, struct scatterlist *sgl, unsigned int nbytes, int *sign);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff815e4b70)
Location: lib/mpi/mpicoder.c:354
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff815e4b70-ffffffff815e4d03: mpi_write_to_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mpi_write_to_sgl(MPI a, struct scatterlist *sgl, unsigned int nbytes, int *sign);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff81650da0)
Location: lib/mpi/mpicoder.c:354
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff81650da0-ffffffff81650f33: mpi_write_to_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mpi_write_to_sgl(MPI a, struct scatterlist *sgl, unsigned int nbytes, int *sign);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff81767b90)
Location: lib/mpi/mpicoder.c:354
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff81767b90-ffffffff81767d40: mpi_write_to_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mpi_write_to_sgl(MPI a, struct scatterlist *sgl, unsigned int nbytes, int *sign);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff81896c40)
Location: lib/mpi/mpicoder.c:354
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff81896c40-ffffffff81896e0b: mpi_write_to_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mpi_write_to_sgl(MPI a, struct scatterlist *sgl, unsigned int nbytes, int *sign);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff818d9100)
Location: lib/mpi/mpicoder.c:354
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff818d9100-ffffffff818d92cb: mpi_write_to_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mpi_write_to_sgl(MPI a, struct scatterlist *sgl, unsigned int nbytes, int *sign);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/mpi/mpicoder.c (ffffffff8186fc60)
Location: lib/crypto/mpi/mpicoder.c:354
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff8186fc60-ffffffff8186fe2b: mpi_write_to_sgl (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int mpi_write_to_sgl(MPI a, struct scatterlist *sgl, unsigned int nbytes, int *sign);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffff800010663528)
Location: lib/mpi/mpicoder.c:247
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffff800010663528-ffff8000106636d4: mpi_write_to_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mpi_write_to_sgl(MPI a, struct scatterlist *sgl, unsigned int nbytes, int *sign);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (c080c220)
Location: lib/mpi/mpicoder.c:247
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
c080c220-c080c3a0: mpi_write_to_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mpi_write_to_sgl(MPI a, struct scatterlist *sgl, unsigned int nbytes, int *sign);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (c000000000817fc0)
Location: lib/mpi/mpicoder.c:247
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
c000000000817fc0-c000000000818234: mpi_write_to_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mpi_write_to_sgl(MPI a, struct scatterlist *sgl, unsigned int nbytes, int *sign);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffe00048f834)
Location: lib/mpi/mpicoder.c:247
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffe00048f834-ffffffe00048f9da: mpi_write_to_sgl (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int mpi_write_to_sgl(MPI a, struct scatterlist *sgl, unsigned int nbytes, int *sign);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff8154f4b0)
Location: lib/mpi/mpicoder.c:247
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff8154f4b0-ffffffff8154f658: mpi_write_to_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mpi_write_to_sgl(MPI a, struct scatterlist *sgl, unsigned int nbytes, int *sign);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff8153f790)
Location: lib/mpi/mpicoder.c:247
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff8153f790-ffffffff8153f938: mpi_write_to_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mpi_write_to_sgl(MPI a, struct scatterlist *sgl, unsigned int nbytes, int *sign);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff8154b1f0)
Location: lib/mpi/mpicoder.c:247
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff8154b1f0-ffffffff8154b398: mpi_write_to_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mpi_write_to_sgl(MPI a, struct scatterlist *sgl, unsigned int nbytes, int *sign);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff81565040)
Location: lib/mpi/mpicoder.c:247
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff81565040-ffffffff815651e8: mpi_write_to_sgl (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int *nbytes</code> ➡️ <code>unsigned int nbytes</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
