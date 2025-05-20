# Function: <code>mpi_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mpi_free(MPI a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff81419540)
Location: lib/mpi/mpiutil.c:109
Inline: False
Direct callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/rsa.c:RSA_verify_signature
  - crypto/asymmetric_keys/rsa.c:RSA_verify_signature
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_free_certificate
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_free_signed_info
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff81419540-ffffffff81419584: mpi_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mpi_free(MPI a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff814612a0)
Location: lib/mpi/mpiutil.c:109
Inline: False
Direct callers:
  - security/keys/dh.c:keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_verify
  - crypto/rsa.c:rsa_verify
  - crypto/rsa.c:rsa_sign
  - crypto/rsa.c:rsa_sign
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - crypto/rsa.c:rsa_enc
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff814612a0-ffffffff814612e4: mpi_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mpi_free(MPI a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff8147fdc0)
Location: lib/mpi/mpiutil.c:109
Inline: False
Direct callers:
  - security/keys/dh.c:keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_verify
  - crypto/rsa.c:rsa_verify
  - crypto/rsa.c:rsa_sign
  - crypto/rsa.c:rsa_sign
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - crypto/rsa.c:rsa_enc
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff8147fdc0-ffffffff8147fe04: mpi_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mpi_free(MPI a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff81489070)
Location: lib/mpi/mpiutil.c:109
Inline: False
Direct callers:
  - crypto/dh.c:dh_exit_tfm
  - crypto/dh.c:dh_exit_tfm
  - crypto/dh.c:dh_exit_tfm
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_verify
  - crypto/rsa.c:rsa_verify
  - crypto/rsa.c:rsa_sign
  - crypto/rsa.c:rsa_sign
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - crypto/rsa.c:rsa_enc
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff81489070-ffffffff814890b5: mpi_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mpi_free(MPI a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff814c51b0)
Location: lib/mpi/mpiutil.c:109
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_verify
  - crypto/rsa.c:rsa_verify
  - crypto/rsa.c:rsa_sign
  - crypto/rsa.c:rsa_sign
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - crypto/rsa.c:rsa_enc
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff814c51b0-ffffffff814c51f5: mpi_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void mpi_free(MPI a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/mpiutil.c (0)
Location: lib/mpi/mpiutil.c:109
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_verify
  - crypto/rsa.c:rsa_verify
  - crypto/rsa.c:rsa_sign
  - crypto/rsa.c:rsa_sign
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - crypto/rsa.c:rsa_enc
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff814f6231-ffffffff814f6242: mpi_free.cold.1 (STB_LOCAL)
ffffffff814f6090-ffffffff814f60ca: mpi_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void mpi_free(MPI a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/mpiutil.c (0)
Location: lib/mpi/mpiutil.c:109
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_verify
  - crypto/rsa.c:rsa_verify
  - crypto/rsa.c:rsa_sign
  - crypto/rsa.c:rsa_sign
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - crypto/rsa.c:rsa_enc
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff8150a631-ffffffff8150a642: mpi_free.cold.1 (STB_LOCAL)
ffffffff8150a490-ffffffff8150a4ca: mpi_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void mpi_free(MPI a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/mpiutil.c (0)
Location: lib/mpi/mpiutil.c:109
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff815386e1-ffffffff815386f2: mpi_free.cold (STB_LOCAL)
ffffffff81538540-ffffffff8153857e: mpi_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void mpi_free(MPI a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/mpiutil.c (0)
Location: lib/mpi/mpiutil.c:109
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff81559501-ffffffff81559512: mpi_free.cold (STB_LOCAL)
ffffffff81559360-ffffffff8155939e: mpi_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void mpi_free(MPI a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/mpiutil.c (0)
Location: lib/mpi/mpiutil.c:109
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_is_pubkey_valid
  - crypto/dh.c:dh_is_pubkey_valid
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/rsa.c:rsa_exit_tfm
  - crypto/rsa.c:rsa_exit_tfm
  - crypto/rsa.c:rsa_exit_tfm
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff815e2dd1-ffffffff815e2de2: mpi_free.cold (STB_LOCAL)
ffffffff815e2c30-ffffffff815e2c70: mpi_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void mpi_free(MPI a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/mpiutil.c (0)
Location: lib/mpi/mpiutil.c:175
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_is_pubkey_valid
  - crypto/dh.c:dh_is_pubkey_valid
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/rsa.c:rsa_exit_tfm
  - crypto/rsa.c:rsa_exit_tfm
  - crypto/rsa.c:rsa_exit_tfm
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
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
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_init
  - lib/mpi/ec.c:mpi_ec_init
  - lib/mpi/ec.c:mpi_ec_init
  - lib/mpi/mpicoder.c:mpi_scanval
  - lib/mpi/mpi-add.c:mpi_subm
  - lib/mpi/mpi-div.c:mpi_fdiv_qr
  - lib/mpi/mpi-div.c:mpi_fdiv_q
  - lib/mpi/mpi-div.c:mpi_fdiv_r
  - lib/mpi/mpi-mod.c:mpi_barrett_free
  - lib/mpi/mpi-mod.c:mpi_barrett_free
  - lib/mpi/mpi-mod.c:mpi_barrett_free
  - lib/mpi/mpi-mod.c:mpi_barrett_free
  - lib/mpi/mpi-mod.c:mpi_barrett_free
  - lib/mpi/mpiutil.c:mpi_snatch
```
**Symbols:**

```
ffffffff81bf489e-ffffffff81bf48af: mpi_free.cold (STB_LOCAL)
ffffffff81606c70-ffffffff81606cb5: mpi_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void mpi_free(MPI a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/mpiutil.c (0)
Location: lib/mpi/mpiutil.c:175
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/rsa.c:rsa_exit_tfm
  - crypto/rsa.c:rsa_exit_tfm
  - crypto/rsa.c:rsa_exit_tfm
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
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
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_init
  - lib/mpi/ec.c:mpi_ec_init
  - lib/mpi/ec.c:mpi_ec_init
  - lib/mpi/mpicoder.c:mpi_scanval
  - lib/mpi/mpi-add.c:mpi_subm
  - lib/mpi/mpi-div.c:mpi_fdiv_qr
  - lib/mpi/mpi-div.c:mpi_fdiv_q
  - lib/mpi/mpi-div.c:mpi_fdiv_r
  - lib/mpi/mpi-mod.c:mpi_barrett_free
  - lib/mpi/mpi-mod.c:mpi_barrett_free
  - lib/mpi/mpi-mod.c:mpi_barrett_free
  - lib/mpi/mpi-mod.c:mpi_barrett_free
  - lib/mpi/mpi-mod.c:mpi_barrett_free
  - lib/mpi/mpiutil.c:mpi_snatch
```
**Symbols:**

```
ffffffff81be6796-ffffffff81be67a7: mpi_free.cold (STB_LOCAL)
ffffffff815e99d0-ffffffff815e9a15: mpi_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void mpi_free(MPI a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/mpiutil.c (0)
Location: lib/mpi/mpiutil.c:175
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/rsa.c:rsa_exit_tfm
  - crypto/rsa.c:rsa_exit_tfm
  - crypto/rsa.c:rsa_exit_tfm
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
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
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_init
  - lib/mpi/ec.c:mpi_ec_init
  - lib/mpi/ec.c:mpi_ec_init
  - lib/mpi/mpicoder.c:mpi_scanval
  - lib/mpi/mpi-add.c:mpi_subm
  - lib/mpi/mpi-div.c:mpi_fdiv_qr
  - lib/mpi/mpi-div.c:mpi_fdiv_q
  - lib/mpi/mpi-div.c:mpi_fdiv_r
  - lib/mpi/mpi-mod.c:mpi_barrett_free
  - lib/mpi/mpi-mod.c:mpi_barrett_free
  - lib/mpi/mpi-mod.c:mpi_barrett_free
  - lib/mpi/mpi-mod.c:mpi_barrett_free
  - lib/mpi/mpi-mod.c:mpi_barrett_free
  - lib/mpi/mpiutil.c:mpi_snatch
```
**Symbols:**

```
ffffffff81cde5c5-ffffffff81cde5d6: mpi_free.cold (STB_LOCAL)
ffffffff81655db0-ffffffff81655df5: mpi_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void mpi_free(MPI a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/mpiutil.c (0)
Location: lib/mpi/mpiutil.c:175
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/rsa.c:rsa_exit_tfm
  - crypto/rsa.c:rsa_exit_tfm
  - crypto/rsa.c:rsa_exit_tfm
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_set_pub_key
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
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
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_init
  - lib/mpi/ec.c:mpi_ec_init
  - lib/mpi/ec.c:mpi_ec_init
  - lib/mpi/mpicoder.c:mpi_scanval
  - lib/mpi/mpi-add.c:mpi_subm
  - lib/mpi/mpi-div.c:mpi_fdiv_qr
  - lib/mpi/mpi-div.c:mpi_fdiv_q
  - lib/mpi/mpi-div.c:mpi_fdiv_r
  - lib/mpi/mpi-mod.c:mpi_barrett_free
  - lib/mpi/mpi-mod.c:mpi_barrett_free
  - lib/mpi/mpi-mod.c:mpi_barrett_free
  - lib/mpi/mpi-mod.c:mpi_barrett_free
  - lib/mpi/mpi-mod.c:mpi_barrett_free
  - lib/mpi/mpiutil.c:mpi_snatch
```
**Symbols:**

```
ffffffff81ea4930-ffffffff81ea4941: mpi_free.cold (STB_LOCAL)
ffffffff8176d430-ffffffff8176d482: mpi_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mpi_free(MPI a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff8189cb60)
Location: lib/mpi/mpiutil.c:175
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
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
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_init
  - lib/mpi/ec.c:mpi_ec_init
  - lib/mpi/ec.c:mpi_ec_init
  - lib/mpi/mpicoder.c:mpi_scanval
  - lib/mpi/mpi-add.c:mpi_subm
  - lib/mpi/mpi-div.c:mpi_fdiv_qr
  - lib/mpi/mpi-div.c:mpi_fdiv_q
  - lib/mpi/mpi-div.c:mpi_fdiv_r
  - lib/mpi/mpi-mod.c:mpi_barrett_free
  - lib/mpi/mpi-mod.c:mpi_barrett_free
  - lib/mpi/mpi-mod.c:mpi_barrett_free
  - lib/mpi/mpi-mod.c:mpi_barrett_free
  - lib/mpi/mpi-mod.c:mpi_barrett_free
  - lib/mpi/mpiutil.c:mpi_snatch
```
**Symbols:**

```
ffffffff8189cb60-ffffffff8189cbd0: mpi_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mpi_free(MPI a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff818df120)
Location: lib/mpi/mpiutil.c:175
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
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
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_deinit
  - lib/mpi/ec.c:mpi_ec_init
  - lib/mpi/ec.c:mpi_ec_init
  - lib/mpi/ec.c:mpi_ec_init
  - lib/mpi/mpicoder.c:mpi_scanval
  - lib/mpi/mpi-add.c:mpi_subm
  - lib/mpi/mpi-div.c:mpi_fdiv_qr
  - lib/mpi/mpi-div.c:mpi_fdiv_q
  - lib/mpi/mpi-div.c:mpi_fdiv_r
  - lib/mpi/mpi-mod.c:mpi_barrett_free
  - lib/mpi/mpi-mod.c:mpi_barrett_free
  - lib/mpi/mpi-mod.c:mpi_barrett_free
  - lib/mpi/mpi-mod.c:mpi_barrett_free
  - lib/mpi/mpi-mod.c:mpi_barrett_free
  - lib/mpi/mpiutil.c:mpi_snatch
```
**Symbols:**

```
ffffffff818df120-ffffffff818df190: mpi_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mpi_free(MPI a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/mpi/mpiutil.c (ffffffff81875d20)
Location: lib/crypto/mpi/mpiutil.c:175
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
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
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:dup_point_weierstrass
  - lib/crypto/mpi/ec.c:mpi_ec_get_affine
  - lib/crypto/mpi/ec.c:mpi_ec_get_affine
  - lib/crypto/mpi/ec.c:mpi_ec_get_affine
  - lib/crypto/mpi/ec.c:mpi_ec_get_affine
  - lib/crypto/mpi/ec.c:mpi_ec_deinit
  - lib/crypto/mpi/ec.c:mpi_ec_deinit
  - lib/crypto/mpi/ec.c:mpi_ec_deinit
  - lib/crypto/mpi/ec.c:mpi_ec_deinit
  - lib/crypto/mpi/ec.c:mpi_ec_deinit
  - lib/crypto/mpi/ec.c:mpi_ec_deinit
  - lib/crypto/mpi/ec.c:mpi_ec_deinit
  - lib/crypto/mpi/ec.c:mpi_ec_deinit
  - lib/crypto/mpi/ec.c:mpi_ec_deinit
  - lib/crypto/mpi/ec.c:mpi_ec_deinit
  - lib/crypto/mpi/ec.c:mpi_ec_deinit
  - lib/crypto/mpi/ec.c:mpi_ec_deinit
  - lib/crypto/mpi/ec.c:mpi_ec_deinit
  - lib/crypto/mpi/ec.c:mpi_ec_init
  - lib/crypto/mpi/ec.c:mpi_ec_init
  - lib/crypto/mpi/ec.c:mpi_ec_init
  - lib/crypto/mpi/mpicoder.c:mpi_scanval
  - lib/crypto/mpi/mpi-add.c:mpi_subm
  - lib/crypto/mpi/mpi-div.c:mpi_fdiv_qr
  - lib/crypto/mpi/mpi-div.c:mpi_fdiv_q
  - lib/crypto/mpi/mpi-div.c:mpi_fdiv_r
  - lib/crypto/mpi/mpi-mod.c:mpi_barrett_free
  - lib/crypto/mpi/mpi-mod.c:mpi_barrett_free
  - lib/crypto/mpi/mpi-mod.c:mpi_barrett_free
  - lib/crypto/mpi/mpi-mod.c:mpi_barrett_free
  - lib/crypto/mpi/mpi-mod.c:mpi_barrett_free
  - lib/crypto/mpi/mpiutil.c:mpi_snatch
```
**Symbols:**

```
ffffffff81875d20-ffffffff81875d90: mpi_free (STB_GLOBAL)
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
void mpi_free(MPI a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffff800010665a08)
Location: lib/mpi/mpiutil.c:109
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffff800010665a08-ffff800010665a64: mpi_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mpi_free(MPI a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (c080e4f0)
Location: lib/mpi/mpiutil.c:109
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
c080e4f0-c080e548: mpi_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mpi_free(MPI a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (c00000000081b160)
Location: lib/mpi/mpiutil.c:109
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
c00000000081b160-c00000000081b1e4: mpi_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mpi_free(MPI a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffe000491c48)
Location: lib/mpi/mpiutil.c:109
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffe000491c48-ffffffe000491c98: mpi_free (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void mpi_free(MPI a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/mpiutil.c (0)
Location: lib/mpi/mpiutil.c:109
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff81551ae1-ffffffff81551af2: mpi_free.cold (STB_LOCAL)
ffffffff81551940-ffffffff8155197e: mpi_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void mpi_free(MPI a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/mpiutil.c (0)
Location: lib/mpi/mpiutil.c:109
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff81541dc1-ffffffff81541dd2: mpi_free.cold (STB_LOCAL)
ffffffff81541c20-ffffffff81541c5e: mpi_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void mpi_free(MPI a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/mpiutil.c (0)
Location: lib/mpi/mpiutil.c:109
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff8154d821-ffffffff8154d832: mpi_free.cold (STB_LOCAL)
ffffffff8154d680-ffffffff8154d6be: mpi_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void mpi_free(MPI a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/mpiutil.c (0)
Location: lib/mpi/mpiutil.c:109
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_compute_value
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/dh.c:dh_clear_ctx
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_free_mpi_key
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_dec
  - crypto/rsa.c:rsa_enc
  - crypto/rsa.c:rsa_enc
```
**Symbols:**

```
ffffffff81567671-ffffffff81567682: mpi_free.cold (STB_LOCAL)
ffffffff815674d0-ffffffff8156750e: mpi_free (STB_GLOBAL)
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
