# Function: <code>mpi_read_raw_from_sgl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
MPI mpi_read_raw_from_sgl(struct scatterlist *sgl, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff814170f0)
Location: lib/mpi/mpicoder.c:437
Inline: False
```
**Symbols:**

```
ffffffff814170f0-ffffffff81417398: mpi_read_raw_from_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
MPI mpi_read_raw_from_sgl(struct scatterlist *sgl, unsigned int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff8145ed30)
Location: lib/mpi/mpicoder.c:330
Inline: False
Direct callers:
  - crypto/rsa.c:rsa_verify
  - crypto/rsa.c:rsa_sign
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff8145ed30-ffffffff8145ef34: mpi_read_raw_from_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
MPI mpi_read_raw_from_sgl(struct scatterlist *sgl, unsigned int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff8147d800)
Location: lib/mpi/mpicoder.c:330
Inline: False
Direct callers:
  - crypto/rsa.c:rsa_verify
  - crypto/rsa.c:rsa_sign
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff8147d800-ffffffff8147da04: mpi_read_raw_from_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
MPI mpi_read_raw_from_sgl(struct scatterlist *sgl, unsigned int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff81486950)
Location: lib/mpi/mpicoder.c:330
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
ffffffff81486950-ffffffff81486b53: mpi_read_raw_from_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
MPI mpi_read_raw_from_sgl(struct scatterlist *sgl, unsigned int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff814c2ad0)
Location: lib/mpi/mpicoder.c:330
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
ffffffff814c2ad0-ffffffff814c2cd3: mpi_read_raw_from_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
MPI mpi_read_raw_from_sgl(struct scatterlist *sgl, unsigned int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff814f3a00)
Location: lib/mpi/mpicoder.c:330
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
ffffffff814f3a00-ffffffff814f3c22: mpi_read_raw_from_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
MPI mpi_read_raw_from_sgl(struct scatterlist *sgl, unsigned int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff81507d30)
Location: lib/mpi/mpicoder.c:330
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
ffffffff81507d30-ffffffff81507f52: mpi_read_raw_from_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
MPI mpi_read_raw_from_sgl(struct scatterlist *sgl, unsigned int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff81535ec0)
Location: lib/mpi/mpicoder.c:330
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff81535ec0-ffffffff815360b1: mpi_read_raw_from_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
MPI mpi_read_raw_from_sgl(struct scatterlist *sgl, unsigned int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff81556cd0)
Location: lib/mpi/mpicoder.c:330
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff81556cd0-ffffffff81556ec1: mpi_read_raw_from_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
MPI mpi_read_raw_from_sgl(struct scatterlist *sgl, unsigned int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff815e05a0)
Location: lib/mpi/mpicoder.c:330
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff815e05a0-ffffffff815e0789: mpi_read_raw_from_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
MPI mpi_read_raw_from_sgl(struct scatterlist *sgl, unsigned int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff81601be0)
Location: lib/mpi/mpicoder.c:437
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff81601be0-ffffffff81601dce: mpi_read_raw_from_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
MPI mpi_read_raw_from_sgl(struct scatterlist *sgl, unsigned int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff815e4980)
Location: lib/mpi/mpicoder.c:437
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff815e4980-ffffffff815e4b6e: mpi_read_raw_from_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
MPI mpi_read_raw_from_sgl(struct scatterlist *sgl, unsigned int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff81650bb0)
Location: lib/mpi/mpicoder.c:437
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff81650bb0-ffffffff81650d9e: mpi_read_raw_from_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
MPI mpi_read_raw_from_sgl(struct scatterlist *sgl, unsigned int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff81767d40)
Location: lib/mpi/mpicoder.c:437
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff81767d40-ffffffff81767f47: mpi_read_raw_from_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
MPI mpi_read_raw_from_sgl(struct scatterlist *sgl, unsigned int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff81896e20)
Location: lib/mpi/mpicoder.c:437
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff81896e20-ffffffff81897047: mpi_read_raw_from_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
MPI mpi_read_raw_from_sgl(struct scatterlist *sgl, unsigned int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff818d92e0)
Location: lib/mpi/mpicoder.c:437
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff818d92e0-ffffffff818d951c: mpi_read_raw_from_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
MPI mpi_read_raw_from_sgl(struct scatterlist *sgl, unsigned int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/mpi/mpicoder.c (ffffffff8186fe40)
Location: lib/crypto/mpi/mpicoder.c:437
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff8186fe40-ffffffff8187007c: mpi_read_raw_from_sgl (STB_GLOBAL)
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
MPI mpi_read_raw_from_sgl(struct scatterlist *sgl, unsigned int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffff800010663300)
Location: lib/mpi/mpicoder.c:330
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffff800010663300-ffff800010663524: mpi_read_raw_from_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
MPI mpi_read_raw_from_sgl(struct scatterlist *sgl, unsigned int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (c080c024)
Location: lib/mpi/mpicoder.c:330
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
c080c024-c080c220: mpi_read_raw_from_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
MPI mpi_read_raw_from_sgl(struct scatterlist *sgl, unsigned int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (c000000000817d10)
Location: lib/mpi/mpicoder.c:330
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
c000000000817d10-c000000000817fb8: mpi_read_raw_from_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
MPI mpi_read_raw_from_sgl(struct scatterlist *sgl, unsigned int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffe00048f9da)
Location: lib/mpi/mpicoder.c:330
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffe00048f9da-ffffffe00048fbb4: mpi_read_raw_from_sgl (STB_GLOBAL)
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
MPI mpi_read_raw_from_sgl(struct scatterlist *sgl, unsigned int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff8154f2b0)
Location: lib/mpi/mpicoder.c:330
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff8154f2b0-ffffffff8154f4a1: mpi_read_raw_from_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
MPI mpi_read_raw_from_sgl(struct scatterlist *sgl, unsigned int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff8153f590)
Location: lib/mpi/mpicoder.c:330
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff8153f590-ffffffff8153f781: mpi_read_raw_from_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
MPI mpi_read_raw_from_sgl(struct scatterlist *sgl, unsigned int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff8154aff0)
Location: lib/mpi/mpicoder.c:330
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff8154aff0-ffffffff8154b1e1: mpi_read_raw_from_sgl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
MPI mpi_read_raw_from_sgl(struct scatterlist *sgl, unsigned int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff81564e40)
Location: lib/mpi/mpicoder.c:330
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff81564e40-ffffffff81565031: mpi_read_raw_from_sgl (STB_GLOBAL)
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
<b>Param added. </b>
<code>unsigned int nbytes</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int len</code>
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
