# Function: <code>drbg_string_fill</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff813ee3bf)
Location: include/crypto/drbg.h:73
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_set_entropy
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff81407bff)
Location: include/crypto/drbg.h:73
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_set_entropy
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff8141531b)
Location: include/crypto/drbg.h:73
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_set_entropy
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff8143faeb)
Location: include/crypto/drbg.h:73
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_set_entropy
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff81472985)
Location: include/crypto/drbg.h:73
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_set_entropy
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff8148fdd5)
Location: include/crypto/drbg.h:73
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_set_entropy
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff814be632)
Location: include/crypto/drbg.h:73
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_set_entropy
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff814d7482)
Location: include/crypto/drbg.h:73
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_set_entropy
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff81534aa3)
Location: include/crypto/drbg.h:73
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_set_entropy
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff81551a15)
Location: include/crypto/drbg.h:73
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_set_entropy
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff8155a031)
Location: include/crypto/drbg.h:73
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_set_entropy
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff815bb334)
Location: include/crypto/drbg.h:73
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_set_entropy
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff81664c39)
Location: include/crypto/drbg.h:73
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_set_entropy
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed_from_random
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff8171efb9)
Location: include/crypto/drbg.h:73
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_set_entropy
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed_from_random
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff8175a8c9)
Location: include/crypto/drbg.h:73
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_set_entropy
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed_from_random
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff8179c7c9)
Location: include/crypto/drbg.h:73
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_set_entropy
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed_from_random
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffff8000105d19e8)
Location: include/crypto/drbg.h:73
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_set_entropy
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (c07808dc)
Location: include/crypto/drbg.h:73
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_set_entropy
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (c000000000760294)
Location: include/crypto/drbg.h:73
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_set_entropy
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffe0004166cc)
Location: include/crypto/drbg.h:73
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_set_entropy
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff814cfa62)
Location: include/crypto/drbg.h:73
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_set_entropy
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff814c0482)
Location: include/crypto/drbg.h:73
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_set_entropy
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff814cbaf2)
Location: include/crypto/drbg.h:73
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_set_entropy
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff814e45c2)
Location: include/crypto/drbg.h:73
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_set_entropy
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
</details>
</li>
</ul>

## Differences
