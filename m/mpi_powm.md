# Function: <code>mpi_powm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mpi_powm(MPI res, MPI base, MPI exp, MPI mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-pow.c (ffffffff81418b30)
Location: lib/mpi/mpi-pow.c:36
Inline: False
Direct callers:
  - crypto/asymmetric_keys/rsa.c:RSA_verify_signature
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff81418b30-ffffffff8141953f: mpi_powm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mpi_powm(MPI res, MPI base, MPI exp, MPI mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-pow.c (ffffffff814607a0)
Location: lib/mpi/mpi-pow.c:36
Inline: False
Direct callers:
  - security/keys/dh.c:keyctl_dh_compute
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff814607a0-ffffffff8146129f: mpi_powm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mpi_powm(MPI res, MPI base, MPI exp, MPI mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-pow.c (ffffffff8147f270)
Location: lib/mpi/mpi-pow.c:36
Inline: False
Direct callers:
  - security/keys/dh.c:keyctl_dh_compute
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff8147f270-ffffffff8147fdb1: mpi_powm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mpi_powm(MPI res, MPI base, MPI exp, MPI mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-pow.c (ffffffff814885f0)
Location: lib/mpi/mpi-pow.c:36
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff814885f0-ffffffff8148906b: mpi_powm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mpi_powm(MPI res, MPI base, MPI exp, MPI mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-pow.c (ffffffff814c4770)
Location: lib/mpi/mpi-pow.c:37
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff814c4770-ffffffff814c51a6: mpi_powm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mpi_powm(MPI res, MPI base, MPI exp, MPI mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-pow.c (ffffffff814f5600)
Location: lib/mpi/mpi-pow.c:37
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff814f5600-ffffffff814f6090: mpi_powm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mpi_powm(MPI res, MPI base, MPI exp, MPI mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-pow.c (ffffffff81509960)
Location: lib/mpi/mpi-pow.c:37
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff81509960-ffffffff8150a486: mpi_powm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mpi_powm(MPI res, MPI base, MPI exp, MPI mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-pow.c (ffffffff81537af0)
Location: lib/mpi/mpi-pow.c:24
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff81537af0-ffffffff81538540: mpi_powm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mpi_powm(MPI res, MPI base, MPI exp, MPI mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-pow.c (ffffffff81558910)
Location: lib/mpi/mpi-pow.c:24
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff81558910-ffffffff81559360: mpi_powm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mpi_powm(MPI res, MPI base, MPI exp, MPI mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-pow.c (ffffffff815e21c0)
Location: lib/mpi/mpi-pow.c:24
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_is_pubkey_valid
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff815e21c0-ffffffff815e2c0b: mpi_powm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mpi_powm(MPI res, MPI base, MPI exp, MPI mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-pow.c (ffffffff816061d0)
Location: lib/mpi/mpi-pow.c:24
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_is_pubkey_valid
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
```
**Symbols:**

```
ffffffff816061d0-ffffffff81606c19: mpi_powm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mpi_powm(MPI res, MPI base, MPI exp, MPI mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-pow.c (ffffffff815e8f10)
Location: lib/mpi/mpi-pow.c:24
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
```
**Symbols:**

```
ffffffff815e8f10-ffffffff815e9973: mpi_powm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mpi_powm(MPI res, MPI base, MPI exp, MPI mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/mpi-pow.c (0)
Location: lib/mpi/mpi-pow.c:24
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
```
**Symbols:**

```
ffffffff81cde584-ffffffff81cde5a1: mpi_powm.cold (STB_LOCAL)
ffffffff816552b0-ffffffff81655d1c: mpi_powm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mpi_powm(MPI res, MPI base, MPI exp, MPI mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/mpi-pow.c (0)
Location: lib/mpi/mpi-pow.c:24
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
```
**Symbols:**

```
ffffffff81ea48c3-ffffffff81ea490c: mpi_powm.cold (STB_LOCAL)
ffffffff8176c7c0-ffffffff8176d383: mpi_powm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mpi_powm(MPI res, MPI base, MPI exp, MPI mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/mpi-pow.c (0)
Location: lib/mpi/mpi-pow.c:24
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
```
**Symbols:**

```
ffffffff8208d4be-ffffffff8208d507: mpi_powm.cold (STB_LOCAL)
ffffffff8189bea0-ffffffff8189ca63: mpi_powm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mpi_powm(MPI res, MPI base, MPI exp, MPI mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/mpi-pow.c (0)
Location: lib/mpi/mpi-pow.c:24
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
```
**Symbols:**

```
ffffffff8210d85c-ffffffff8210d8a5: mpi_powm.cold (STB_LOCAL)
ffffffff818de490-ffffffff818df028: mpi_powm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mpi_powm(MPI res, MPI base, MPI exp, MPI mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/crypto/mpi/mpi-pow.c (0)
Location: lib/crypto/mpi/mpi-pow.c:24
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - lib/crypto/mpi/ec.c:mpi_ec_curve_point
  - lib/crypto/mpi/ec.c:mpi_ec_curve_point
  - lib/crypto/mpi/ec.c:add_points_weierstrass
  - lib/crypto/mpi/ec.c:add_points_weierstrass
  - lib/crypto/mpi/ec.c:add_points_weierstrass
  - lib/crypto/mpi/ec.c:dup_point_weierstrass
```
**Symbols:**

```
ffffffff821d727a-ffffffff821d72c3: mpi_powm.cold (STB_LOCAL)
ffffffff81875090-ffffffff81875c30: mpi_powm (STB_GLOBAL)
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
int mpi_powm(MPI res, MPI base, MPI exp, MPI mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-pow.c (ffff800010665118)
Location: lib/mpi/mpi-pow.c:24
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
```
**Symbols:**

```
ffff800010665118-ffff8000106659e8: mpi_powm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mpi_powm(MPI res, MPI base, MPI exp, MPI mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-pow.c (c080db58)
Location: lib/mpi/mpi-pow.c:24
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
c080db58-c080e4f0: mpi_powm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mpi_powm(MPI res, MPI base, MPI exp, MPI mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-pow.c (c00000000081a460)
Location: lib/mpi/mpi-pow.c:24
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
c00000000081a460-c00000000081b160: mpi_powm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mpi_powm(MPI res, MPI base, MPI exp, MPI mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-pow.c (ffffffe0004913f8)
Location: lib/mpi/mpi-pow.c:24
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
```
**Symbols:**

```
ffffffe0004913f8-ffffffe000491be2: mpi_powm (STB_GLOBAL)
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
int mpi_powm(MPI res, MPI base, MPI exp, MPI mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-pow.c (ffffffff81550ef0)
Location: lib/mpi/mpi-pow.c:24
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff81550ef0-ffffffff81551940: mpi_powm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mpi_powm(MPI res, MPI base, MPI exp, MPI mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-pow.c (ffffffff815411d0)
Location: lib/mpi/mpi-pow.c:24
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff815411d0-ffffffff81541c20: mpi_powm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mpi_powm(MPI res, MPI base, MPI exp, MPI mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-pow.c (ffffffff8154cc30)
Location: lib/mpi/mpi-pow.c:24
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff8154cc30-ffffffff8154d680: mpi_powm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mpi_powm(MPI res, MPI base, MPI exp, MPI mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-pow.c (ffffffff81566a80)
Location: lib/mpi/mpi-pow.c:24
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff81566a80-ffffffff815674d0: mpi_powm (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
