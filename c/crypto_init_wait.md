# Function: <code>crypto_init_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81420ad4)
Location: include/linux/crypto.h:513
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (ffffffff8143a3f5)
Location: include/linux/crypto.h:513
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8143cfd0)
Location: include/linux/crypto.h:513
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814424fc)
Location: include/linux/crypto.h:513
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81452f7c)
Location: include/linux/crypto.h:526
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (ffffffff8146cdbf)
Location: include/linux/crypto.h:526
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8146fe14)
Location: include/linux/crypto.h:526
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81475462)
Location: include/linux/crypto.h:526
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff814700cc)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/gcm.c (ffffffff81489380)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff81490151)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814932dc)
Location: include/linux/crypto.h:697
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff8149dacf)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814b6fc7)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814bd309)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814c0f28)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff814b7f0f)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814d01e7)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814d5f9a)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814d9d58)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81516f3a)
Location: include/linux/crypto.h:571
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff8153024a)
Location: include/linux/crypto.h:571
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff81535b59)
Location: include/linux/crypto.h:571
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff815392ef)
Location: include/linux/crypto.h:571
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff812ccb2e)
Location: include/linux/crypto.h:605
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In security/integrity/ima/ima_crypto.c (ffffffff815340fa)
Location: include/linux/crypto.h:605
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff8154d19a)
Location: include/linux/crypto.h:605
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff81552ac9)
Location: include/linux/crypto.h:605
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff815560e1)
Location: include/linux/crypto.h:605
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff812d36fe)
Location: include/linux/crypto.h:605
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8153d0f2)
Location: include/linux/crypto.h:605
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff81555115)
Location: include/linux/crypto.h:605
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8155b389)
Location: include/linux/crypto.h:605
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8155e843)
Location: include/linux/crypto.h:605
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff813191e1)
Location: include/linux/crypto.h:605
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8159bf72)
Location: include/linux/crypto.h:605
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff815b6145)
Location: include/linux/crypto.h:605
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff815bbd29)
Location: include/linux/crypto.h:605
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff815bfb9c)
Location: include/linux/crypto.h:605
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff81384421)
Location: include/linux/crypto.h:614
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81640f4c)
Location: include/linux/crypto.h:614
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff8165f403)
Location: include/linux/crypto.h:614
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff816655e8)
Location: include/linux/crypto.h:614
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8166a0e6)
Location: include/linux/crypto.h:614
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff81401f71)
Location: include/linux/crypto.h:614
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In security/integrity/ima/ima_crypto.c (ffffffff816f8ebc)
Location: include/linux/crypto.h:614
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff81718833)
Location: include/linux/crypto.h:614
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff817203f8)
Location: include/linux/crypto.h:614
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff817246b1)
Location: include/linux/crypto.h:614
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff81434e71)
Location: include/linux/crypto.h:406
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In security/integrity/ima/ima_crypto.c (ffffffff817330c3)
Location: include/linux/crypto.h:406
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/akcipher.c (ffffffff81747667)
Location: include/linux/crypto.h:406
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_sync_prep
```
```
In crypto/gcm.c (ffffffff817541a3)
Location: include/linux/crypto.h:406
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8175bced)
Location: include/linux/crypto.h:406
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff8146ddd4)
Location: include/linux/crypto.h:406
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81773ad3)
Location: include/linux/crypto.h:406
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/akcipher.c (ffffffff817894d7)
Location: include/linux/crypto.h:406
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_sync_prep
```
```
In crypto/gcm.c (ffffffff81795b13)
Location: include/linux/crypto.h:406
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8179dbed)
Location: include/linux/crypto.h:406
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffff8000105b02d4)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffff8000105cc6f8)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffff8000105d1dc4)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (ffff8000105d5b64)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (c075f9ec)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (c077a5ec)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (c077f664)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (c078366c)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (c00000000072fd9c)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (c000000000757b58)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (c00000000075ed70)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (c00000000076435c)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffe0003f7f5e)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffe000410634)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffe000415542)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (ffffffe000419cc8)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff814b04ef)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814c87c7)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814ce57a)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814d2338)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff814a0f0f)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814b91e7)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814bef9a)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814c2d58)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff814ac57f)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814c4857)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814ca60a)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814ce3c8)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff814c4fcf)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/gcm.c (ffffffff814dd327)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814e30da)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814e6e98)
Location: include/linux/crypto.h:694
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
</details>
</li>
</ul>

## Differences
