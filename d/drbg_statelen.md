# Function: <code>drbg_statelen</code>

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
In crypto/drbg.c (ffffffff813eb976)
Location: include/crypto/drbg.h:140
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_hmacsetkey
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
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
In crypto/drbg.c (ffffffff814051b6)
Location: include/crypto/drbg.h:142
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_hmacsetkey
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
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
In crypto/drbg.c (ffffffff81412956)
Location: include/crypto/drbg.h:142
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_hmacsetkey
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
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
In crypto/drbg.c (ffffffff8143d0d6)
Location: include/crypto/drbg.h:141
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_hmacsetkey
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
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
In crypto/drbg.c (ffffffff8146ff1c)
Location: include/crypto/drbg.h:141
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_hmacsetkey
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
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
In crypto/drbg.c (ffffffff8148d69c)
Location: include/crypto/drbg.h:140
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_hmacsetkey
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
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
In crypto/drbg.c (ffffffff814bb01c)
Location: include/crypto/drbg.h:142
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_hmacsetkey
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
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
In crypto/drbg.c (ffffffff814d3dec)
Location: include/crypto/drbg.h:142
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_hmacsetkey
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
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
In crypto/drbg.c (ffffffff81533a5e)
Location: include/crypto/drbg.h:142
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
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
In crypto/drbg.c (ffffffff815509ae)
Location: include/crypto/drbg.h:142
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
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
In crypto/drbg.c (ffffffff81558ab6)
Location: include/crypto/drbg.h:142
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
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
In crypto/drbg.c (ffffffff815b9d66)
Location: include/crypto/drbg.h:142
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
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
In crypto/drbg.c (ffffffff81663880)
Location: include/crypto/drbg.h:147
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
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
In crypto/drbg.c (ffffffff8171db80)
Location: include/crypto/drbg.h:147
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
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
In crypto/drbg.c (ffffffff817594a4)
Location: include/crypto/drbg.h:147
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
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
In crypto/drbg.c (ffffffff8179b3a4)
Location: include/crypto/drbg.h:147
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
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
In crypto/drbg.c (ffff8000105d0898)
Location: include/crypto/drbg.h:142
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_hmacsetkey
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
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
In crypto/drbg.c (c077e6e0)
Location: include/crypto/drbg.h:142
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_hmacsetkey
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
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
In crypto/drbg.c (c00000000075d610)
Location: include/crypto/drbg.h:142
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_hmacsetkey
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
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
In crypto/drbg.c (ffffffe0004158dc)
Location: include/crypto/drbg.h:142
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_hmacsetkey
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
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
In crypto/drbg.c (ffffffff814cc3cc)
Location: include/crypto/drbg.h:142
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_hmacsetkey
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
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
In crypto/drbg.c (ffffffff814bcdec)
Location: include/crypto/drbg.h:142
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_hmacsetkey
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
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
In crypto/drbg.c (ffffffff814c845c)
Location: include/crypto/drbg.h:142
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_hmacsetkey
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
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
In crypto/drbg.c (ffffffff814e0f2c)
Location: include/crypto/drbg.h:142
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_hmacsetkey
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
</details>
</li>
</ul>

## Differences
