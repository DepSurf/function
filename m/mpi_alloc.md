# Function: <code>mpi_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
MPI mpi_alloc(unsigned int nlimbs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff814195b0)
Location: lib/mpi/mpiutil.c:30
Inline: False
Direct callers:
  - crypto/asymmetric_keys/rsa.c:RSA_verify_signature
  - lib/mpi/mpicoder.c:mpi_read_raw_data
  - lib/mpi/mpicoder.c:mpi_read_from_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff814195b0-ffffffff81419630: mpi_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
MPI mpi_alloc(unsigned int nlimbs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff81461310)
Location: lib/mpi/mpiutil.c:30
Inline: False
Direct callers:
  - security/keys/dh.c:keyctl_dh_compute
  - crypto/rsa.c:rsa_verify
  - crypto/rsa.c:rsa_sign
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_data
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff81461310-ffffffff81461390: mpi_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
MPI mpi_alloc(unsigned int nlimbs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff8147fe30)
Location: lib/mpi/mpiutil.c:30
Inline: False
Direct callers:
  - security/keys/dh.c:keyctl_dh_compute
  - crypto/rsa.c:rsa_verify
  - crypto/rsa.c:rsa_sign
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_data
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff8147fe30-ffffffff8147feb0: mpi_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
MPI mpi_alloc(unsigned int nlimbs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff814890e0)
Location: lib/mpi/mpiutil.c:30
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_verify
  - crypto/rsa.c:rsa_sign
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_data
  - lib/mpi/mpicoder.c:mpi_read_raw_data
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff814890e0-ffffffff8148914d: mpi_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
MPI mpi_alloc(unsigned int nlimbs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff814c5220)
Location: lib/mpi/mpiutil.c:30
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_verify
  - crypto/rsa.c:rsa_sign
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_data
  - lib/mpi/mpicoder.c:mpi_read_raw_data
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff814c5220-ffffffff814c528d: mpi_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
MPI mpi_alloc(unsigned int nlimbs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff814f60f0)
Location: lib/mpi/mpiutil.c:30
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_verify
  - crypto/rsa.c:rsa_sign
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_data
  - lib/mpi/mpicoder.c:mpi_read_raw_data
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff814f60f0-ffffffff814f615d: mpi_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
MPI mpi_alloc(unsigned int nlimbs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff8150a4f0)
Location: lib/mpi/mpiutil.c:30
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_verify
  - crypto/rsa.c:rsa_sign
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_data
  - lib/mpi/mpicoder.c:mpi_read_raw_data
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff8150a4f0-ffffffff8150a55d: mpi_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
MPI mpi_alloc(unsigned int nlimbs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff815385a0)
Location: lib/mpi/mpiutil.c:30
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_data
  - lib/mpi/mpicoder.c:mpi_read_raw_data
```
**Symbols:**

```
ffffffff815385a0-ffffffff8153860f: mpi_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
MPI mpi_alloc(unsigned int nlimbs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff815593c0)
Location: lib/mpi/mpiutil.c:30
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_data
  - lib/mpi/mpicoder.c:mpi_read_raw_data
```
**Symbols:**

```
ffffffff815593c0-ffffffff8155942f: mpi_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
MPI mpi_alloc(unsigned int nlimbs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff815e2c90)
Location: lib/mpi/mpiutil.c:30
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_is_pubkey_valid
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_data
  - lib/mpi/mpicoder.c:mpi_read_raw_data
```
**Symbols:**

```
ffffffff815e2c90-ffffffff815e2cff: mpi_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
MPI mpi_alloc(unsigned int nlimbs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff81607095)
Location: lib/mpi/mpiutil.c:87
Inline: True
Inline callers:
  - lib/mpi/mpiutil.c:mpi_alloc_set_ui
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_is_pubkey_valid
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_point_new
  - lib/mpi/ec.c:mpi_point_new
  - lib/mpi/ec.c:mpi_point_new
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_scanval
  - lib/mpi/mpicoder.c:mpi_read_raw_data
  - lib/mpi/mpicoder.c:mpi_read_raw_data
  - lib/mpi/mpi-div.c:mpi_fdiv_q
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
  - lib/mpi/mpi-mod.c:mpi_barrett_init
  - lib/mpi/mpi-mod.c:mpi_barrett_init
  - lib/mpi/mpi-mod.c:mpi_barrett_init
  - lib/mpi/mpiutil.c:mpi_set_ui
  - lib/mpi/mpiutil.c:mpi_set
  - lib/mpi/mpiutil.c:mpi_alloc_like
  - lib/mpi/mpiutil.c:mpi_copy
```
**Symbols:**

```
ffffffff81606d60-ffffffff81606dd4: mpi_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
MPI mpi_alloc(unsigned int nlimbs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff815e9de5)
Location: lib/mpi/mpiutil.c:87
Inline: True
Inline callers:
  - lib/mpi/mpiutil.c:mpi_alloc_set_ui
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_point_new
  - lib/mpi/ec.c:mpi_point_new
  - lib/mpi/ec.c:mpi_point_new
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_scanval
  - lib/mpi/mpicoder.c:mpi_read_raw_data
  - lib/mpi/mpicoder.c:mpi_read_raw_data
  - lib/mpi/mpi-div.c:mpi_fdiv_q
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
  - lib/mpi/mpi-mod.c:mpi_barrett_init
  - lib/mpi/mpi-mod.c:mpi_barrett_init
  - lib/mpi/mpi-mod.c:mpi_barrett_init
  - lib/mpi/mpiutil.c:mpi_set_ui
  - lib/mpi/mpiutil.c:mpi_set
  - lib/mpi/mpiutil.c:mpi_alloc_like
  - lib/mpi/mpiutil.c:mpi_copy
```
**Symbols:**

```
ffffffff815e9ac0-ffffffff815e9b34: mpi_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
MPI mpi_alloc(unsigned int nlimbs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff816561c5)
Location: lib/mpi/mpiutil.c:87
Inline: True
Inline callers:
  - lib/mpi/mpiutil.c:mpi_alloc_set_ui
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_point_new
  - lib/mpi/ec.c:mpi_point_new
  - lib/mpi/ec.c:mpi_point_new
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_scanval
  - lib/mpi/mpicoder.c:mpi_read_raw_data
  - lib/mpi/mpicoder.c:mpi_read_raw_data
  - lib/mpi/mpi-div.c:mpi_fdiv_q
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
  - lib/mpi/mpi-mod.c:mpi_barrett_init
  - lib/mpi/mpi-mod.c:mpi_barrett_init
  - lib/mpi/mpi-mod.c:mpi_barrett_init
  - lib/mpi/mpiutil.c:mpi_set_ui
  - lib/mpi/mpiutil.c:mpi_set
  - lib/mpi/mpiutil.c:mpi_alloc_like
  - lib/mpi/mpiutil.c:mpi_copy
```
**Symbols:**

```
ffffffff81655ea0-ffffffff81655f14: mpi_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
MPI mpi_alloc(unsigned int nlimbs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff8176d8b5)
Location: lib/mpi/mpiutil.c:87
Inline: True
Inline callers:
  - lib/mpi/mpiutil.c:mpi_alloc_set_ui
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_point_new
  - lib/mpi/ec.c:mpi_point_new
  - lib/mpi/ec.c:mpi_point_new
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_scanval
  - lib/mpi/mpicoder.c:mpi_read_raw_data
  - lib/mpi/mpicoder.c:mpi_read_raw_data
  - lib/mpi/mpi-div.c:mpi_fdiv_q
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
  - lib/mpi/mpi-mod.c:mpi_barrett_init
  - lib/mpi/mpi-mod.c:mpi_barrett_init
  - lib/mpi/mpi-mod.c:mpi_barrett_init
  - lib/mpi/mpiutil.c:mpi_set_ui
  - lib/mpi/mpiutil.c:mpi_set
  - lib/mpi/mpiutil.c:mpi_alloc_like
  - lib/mpi/mpiutil.c:mpi_copy
```
**Symbols:**

```
ffffffff8176d4c0-ffffffff8176d53c: mpi_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
MPI mpi_alloc(unsigned int nlimbs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff8189cc20)
Location: lib/mpi/mpiutil.c:87
Inline: True
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_point_new
  - lib/mpi/ec.c:mpi_point_new
  - lib/mpi/ec.c:mpi_point_new
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_scanval
  - lib/mpi/mpicoder.c:mpi_read_raw_data
  - lib/mpi/mpicoder.c:mpi_read_raw_data
  - lib/mpi/mpi-div.c:mpi_fdiv_q
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
  - lib/mpi/mpi-mod.c:mpi_barrett_init
  - lib/mpi/mpi-mod.c:mpi_barrett_init
  - lib/mpi/mpi-mod.c:mpi_barrett_init
  - lib/mpi/mpiutil.c:mpi_set_ui
  - lib/mpi/mpiutil.c:mpi_set
  - lib/mpi/mpiutil.c:mpi_alloc_like
  - lib/mpi/mpiutil.c:mpi_copy
  - lib/mpi/mpiutil.c:mpi_init
```
**Symbols:**

```
ffffffff8189cc20-ffffffff8189cc9c: mpi_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
MPI mpi_alloc(unsigned int nlimbs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff818df1e0)
Location: lib/mpi/mpiutil.c:87
Inline: True
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_point_new
  - lib/mpi/ec.c:mpi_point_new
  - lib/mpi/ec.c:mpi_point_new
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_scanval
  - lib/mpi/mpicoder.c:mpi_read_raw_data
  - lib/mpi/mpicoder.c:mpi_read_raw_data
  - lib/mpi/mpi-div.c:mpi_fdiv_q
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
  - lib/mpi/mpi-mod.c:mpi_barrett_init
  - lib/mpi/mpi-mod.c:mpi_barrett_init
  - lib/mpi/mpi-mod.c:mpi_barrett_init
  - lib/mpi/mpiutil.c:mpi_set_ui
  - lib/mpi/mpiutil.c:mpi_set
  - lib/mpi/mpiutil.c:mpi_alloc_like
  - lib/mpi/mpiutil.c:mpi_copy
  - lib/mpi/mpiutil.c:mpi_init
```
**Symbols:**

```
ffffffff818df1e0-ffffffff818df25c: mpi_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
MPI mpi_alloc(unsigned int nlimbs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/mpi/mpiutil.c (ffffffff81875de0)
Location: lib/crypto/mpi/mpiutil.c:87
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - lib/crypto/mpi/ec.c:mpi_ec_curve_point
  - lib/crypto/mpi/ec.c:mpi_ec_curve_point
  - lib/crypto/mpi/ec.c:mpi_ec_curve_point
  - lib/crypto/mpi/ec.c:mpi_ec_curve_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:add_points_weierstrass
  - lib/crypto/mpi/ec.c:mpi_ec_get_affine
  - lib/crypto/mpi/ec.c:mpi_ec_get_affine
  - lib/crypto/mpi/ec.c:mpi_ec_get_affine
  - lib/crypto/mpi/ec.c:mpi_ec_get_affine
  - lib/crypto/mpi/ec.c:mpi_point_new
  - lib/crypto/mpi/ec.c:mpi_point_new
  - lib/crypto/mpi/ec.c:mpi_point_new
  - lib/crypto/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/crypto/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/crypto/mpi/mpicoder.c:mpi_scanval
  - lib/crypto/mpi/mpicoder.c:mpi_read_raw_data
  - lib/crypto/mpi/mpicoder.c:mpi_read_raw_data
  - lib/crypto/mpi/mpi-div.c:mpi_fdiv_q
  - lib/crypto/mpi/mpi-mod.c:mpi_mod_barrett
  - lib/crypto/mpi/mpi-mod.c:mpi_barrett_init
  - lib/crypto/mpi/mpi-mod.c:mpi_barrett_init
  - lib/crypto/mpi/mpi-mod.c:mpi_barrett_init
  - lib/crypto/mpi/mpiutil.c:mpi_set_ui
  - lib/crypto/mpi/mpiutil.c:mpi_set
  - lib/crypto/mpi/mpiutil.c:mpi_alloc_like
  - lib/crypto/mpi/mpiutil.c:mpi_copy
  - lib/crypto/mpi/mpiutil.c:mpi_init
```
**Symbols:**

```
ffffffff81875de0-ffffffff81875e8b: mpi_alloc (STB_GLOBAL)
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
MPI mpi_alloc(unsigned int nlimbs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffff800010665a90)
Location: lib/mpi/mpiutil.c:30
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_data
  - lib/mpi/mpicoder.c:mpi_read_raw_data
```
**Symbols:**

```
ffff800010665a90-ffff800010665b00: mpi_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
MPI mpi_alloc(unsigned int nlimbs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (c080e568)
Location: lib/mpi/mpiutil.c:30
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_data
  - lib/mpi/mpicoder.c:mpi_read_raw_data
```
**Symbols:**

```
c080e568-c080e5ec: mpi_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
MPI mpi_alloc(unsigned int nlimbs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (c00000000081b240)
Location: lib/mpi/mpiutil.c:30
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_data
  - lib/mpi/mpicoder.c:mpi_read_raw_data
```
**Symbols:**

```
c00000000081b240-c00000000081b2e8: mpi_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
MPI mpi_alloc(unsigned int nlimbs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffe000491cc6)
Location: lib/mpi/mpiutil.c:30
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_data
  - lib/mpi/mpicoder.c:mpi_read_raw_data
```
**Symbols:**

```
ffffffe000491cc6-ffffffe000491d34: mpi_alloc (STB_GLOBAL)
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
MPI mpi_alloc(unsigned int nlimbs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff815519a0)
Location: lib/mpi/mpiutil.c:30
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_data
  - lib/mpi/mpicoder.c:mpi_read_raw_data
```
**Symbols:**

```
ffffffff815519a0-ffffffff81551a0f: mpi_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
MPI mpi_alloc(unsigned int nlimbs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff81541c80)
Location: lib/mpi/mpiutil.c:30
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_data
  - lib/mpi/mpicoder.c:mpi_read_raw_data
```
**Symbols:**

```
ffffffff81541c80-ffffffff81541cef: mpi_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
MPI mpi_alloc(unsigned int nlimbs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff8154d6e0)
Location: lib/mpi/mpiutil.c:30
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_data
  - lib/mpi/mpicoder.c:mpi_read_raw_data
```
**Symbols:**

```
ffffffff8154d6e0-ffffffff8154d74f: mpi_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
MPI mpi_alloc(unsigned int nlimbs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff81567530)
Location: lib/mpi/mpiutil.c:30
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_data
  - lib/mpi/mpicoder.c:mpi_read_raw_data
```
**Symbols:**

```
ffffffff81567530-ffffffff8156759f: mpi_alloc (STB_GLOBAL)
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
