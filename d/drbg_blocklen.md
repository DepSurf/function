# Function: <code>drbg_blocklen</code>

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
In crypto/drbg.c (ffffffff813eecdb)
Location: include/crypto/drbg.h:147
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
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
In crypto/drbg.c (ffffffff81408521)
Location: include/crypto/drbg.h:149
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
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
In crypto/drbg.c (ffffffff81415be7)
Location: include/crypto/drbg.h:149
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
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
In crypto/drbg.c (ffffffff814403b7)
Location: include/crypto/drbg.h:148
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
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
In crypto/drbg.c (ffffffff81473297)
Location: include/crypto/drbg.h:148
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
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
In crypto/drbg.c (ffffffff8148f813)
Location: include/crypto/drbg.h:147
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
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
In crypto/drbg.c (ffffffff814be1a3)
Location: include/crypto/drbg.h:149
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
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
In crypto/drbg.c (ffffffff814d6ff3)
Location: include/crypto/drbg.h:149
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
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
In crypto/drbg.c (ffffffff81533801)
Location: include/crypto/drbg.h:149
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff81550751)
Location: include/crypto/drbg.h:149
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
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
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff81558f31)
Location: include/crypto/drbg.h:149
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
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
In crypto/drbg.c (ffffffff815ba1f1)
Location: include/crypto/drbg.h:149
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
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
In crypto/drbg.c (ffffffff81663295)
Location: include/crypto/drbg.h:154
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
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
In crypto/drbg.c (ffffffff8171d525)
Location: include/crypto/drbg.h:154
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
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
In crypto/drbg.c (ffffffff81758e05)
Location: include/crypto/drbg.h:154
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
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
In crypto/drbg.c (ffffffff8179ad05)
Location: include/crypto/drbg.h:154
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
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
In crypto/drbg.c (ffff8000105d14bc)
Location: include/crypto/drbg.h:149
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
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
In crypto/drbg.c (c0780428)
Location: include/crypto/drbg.h:149
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
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
In crypto/drbg.c (c00000000075fc2c)
Location: include/crypto/drbg.h:149
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
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
In crypto/drbg.c (ffffffe000416244)
Location: include/crypto/drbg.h:149
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
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
In crypto/drbg.c (ffffffff814cf5d3)
Location: include/crypto/drbg.h:149
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
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
In crypto/drbg.c (ffffffff814bfff3)
Location: include/crypto/drbg.h:149
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
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
In crypto/drbg.c (ffffffff814cb663)
Location: include/crypto/drbg.h:149
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
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
In crypto/drbg.c (ffffffff814e4133)
Location: include/crypto/drbg.h:149
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_hashgen
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hash_df
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_hmac_generate
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_update
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
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
