# Function: <code>__crypto_acomp_tfm</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/acompress.c (ffffffff813fa569)
Location: include/crypto/acompress.h:125
Inline: True
Inline callers:
  - crypto/acompress.c:crypto_acomp_init_tfm
  - crypto/acompress.c:crypto_acomp_exit_tfm
```
```
In crypto/scompress.c (0)
Location: include/crypto/acompress.h:125
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/acompress.c (ffffffff81406d40)
Location: include/crypto/acompress.h:125
Inline: True
Inline callers:
  - crypto/acompress.c:crypto_acomp_init_tfm
  - crypto/acompress.c:crypto_acomp_exit_tfm
```
```
In crypto/scompress.c (0)
Location: include/crypto/acompress.h:125
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/acompress.c (ffffffff8142f680)
Location: include/crypto/acompress.h:125
Inline: True
Inline callers:
  - crypto/acompress.c:crypto_acomp_init_tfm
  - crypto/acompress.c:crypto_acomp_exit_tfm
```
```
In crypto/scompress.c (0)
Location: include/crypto/acompress.h:125
Inline: True
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
In crypto/acompress.c (ffffffff81462390)
Location: include/crypto/acompress.h:125
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
  - crypto/acompress.c:crypto_acomp_init_tfm
  - crypto/acompress.c:crypto_acomp_exit_tfm
```
```
In crypto/scompress.c (ffffffff81462c15)
Location: include/crypto/acompress.h:125
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_acomp_scomp_free_ctx
  - crypto/scompress.c:crypto_acomp_scomp_alloc_ctx
  - crypto/scompress.c:crypto_init_scomp_ops_async
  - crypto/scompress.c:scomp_acomp_comp_decomp
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
In crypto/acompress.c (ffffffff8147fff0)
Location: include/crypto/acompress.h:125
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
  - crypto/acompress.c:crypto_acomp_init_tfm
  - crypto/acompress.c:crypto_acomp_exit_tfm
```
```
In crypto/scompress.c (ffffffff81480895)
Location: include/crypto/acompress.h:125
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_acomp_scomp_free_ctx
  - crypto/scompress.c:crypto_acomp_scomp_alloc_ctx
  - crypto/scompress.c:crypto_init_scomp_ops_async
  - crypto/scompress.c:scomp_acomp_comp_decomp
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
In crypto/acompress.c (ffffffff814ae243)
Location: include/crypto/acompress.h:120
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
  - crypto/acompress.c:crypto_acomp_init_tfm
  - crypto/acompress.c:crypto_acomp_exit_tfm
```
```
In crypto/scompress.c (ffffffff814aea85)
Location: include/crypto/acompress.h:120
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_acomp_scomp_free_ctx
  - crypto/scompress.c:crypto_acomp_scomp_alloc_ctx
  - crypto/scompress.c:crypto_init_scomp_ops_async
  - crypto/scompress.c:scomp_acomp_comp_decomp
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
In crypto/acompress.c (ffffffff814c8ed3)
Location: include/crypto/acompress.h:120
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
  - crypto/acompress.c:crypto_acomp_init_tfm
  - crypto/acompress.c:crypto_acomp_exit_tfm
```
```
In crypto/scompress.c (ffffffff814c9715)
Location: include/crypto/acompress.h:120
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_acomp_scomp_free_ctx
  - crypto/scompress.c:crypto_acomp_scomp_alloc_ctx
  - crypto/scompress.c:crypto_init_scomp_ops_async
  - crypto/scompress.c:scomp_acomp_comp_decomp
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
In crypto/acompress.c (ffffffff815282d3)
Location: include/crypto/acompress.h:120
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
  - crypto/acompress.c:crypto_acomp_init_tfm
  - crypto/acompress.c:crypto_acomp_exit_tfm
```
```
In crypto/scompress.c (ffffffff81528ad5)
Location: include/crypto/acompress.h:120
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_acomp_scomp_free_ctx
  - crypto/scompress.c:crypto_acomp_scomp_alloc_ctx
  - crypto/scompress.c:crypto_init_scomp_ops_async
  - crypto/scompress.c:scomp_acomp_comp_decomp
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
In mm/zswap.c (ffffffff812cd56d)
Location: include/crypto/acompress.h:138
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In crypto/acompress.c (ffffffff81545283)
Location: include/crypto/acompress.h:138
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
  - crypto/acompress.c:crypto_acomp_init_tfm
  - crypto/acompress.c:crypto_acomp_exit_tfm
```
```
In crypto/scompress.c (ffffffff81545aa5)
Location: include/crypto/acompress.h:138
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_acomp_scomp_free_ctx
  - crypto/scompress.c:crypto_acomp_scomp_alloc_ctx
  - crypto/scompress.c:crypto_init_scomp_ops_async
  - crypto/scompress.c:scomp_acomp_comp_decomp
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
In mm/zswap.c (ffffffff812d3fc5)
Location: include/crypto/acompress.h:138
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In crypto/acompress.c (ffffffff8154d913)
Location: include/crypto/acompress.h:138
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
  - crypto/acompress.c:crypto_acomp_init_tfm
  - crypto/acompress.c:crypto_acomp_exit_tfm
```
```
In crypto/scompress.c (ffffffff8154e125)
Location: include/crypto/acompress.h:138
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_acomp_scomp_free_ctx
  - crypto/scompress.c:crypto_acomp_scomp_alloc_ctx
  - crypto/scompress.c:crypto_init_scomp_ops_async
  - crypto/scompress.c:scomp_acomp_comp_decomp
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
In mm/zswap.c (ffffffff81319c6f)
Location: include/crypto/acompress.h:138
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In crypto/acompress.c (ffffffff815ae0f3)
Location: include/crypto/acompress.h:138
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
  - crypto/acompress.c:crypto_acomp_init_tfm
  - crypto/acompress.c:crypto_acomp_exit_tfm
```
```
In crypto/scompress.c (ffffffff815ae995)
Location: include/crypto/acompress.h:138
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_acomp_scomp_free_ctx
  - crypto/scompress.c:crypto_acomp_scomp_alloc_ctx
  - crypto/scompress.c:crypto_init_scomp_ops_async
  - crypto/scompress.c:scomp_acomp_comp_decomp
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
In mm/zswap.c (0)
Location: include/crypto/acompress.h:138
Inline: True
```
```
In crypto/acompress.c (ffffffff816564f5)
Location: include/crypto/acompress.h:138
Inline: True
Inline callers:
  - crypto/acompress.c:crypto_acomp_init_tfm
  - crypto/acompress.c:crypto_acomp_exit_tfm
```
```
In crypto/scompress.c (0)
Location: include/crypto/acompress.h:138
Inline: True
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
In mm/zswap.c (0)
Location: include/crypto/acompress.h:139
Inline: True
```
```
In crypto/acompress.c (ffffffff81710735)
Location: include/crypto/acompress.h:139
Inline: True
Inline callers:
  - crypto/acompress.c:crypto_acomp_init_tfm
  - crypto/acompress.c:crypto_acomp_exit_tfm
```
```
In crypto/scompress.c (0)
Location: include/crypto/acompress.h:139
Inline: True
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
In mm/zswap.c (0)
Location: include/crypto/acompress.h:141
Inline: True
```
```
In crypto/acompress.c (ffffffff8174b1e5)
Location: include/crypto/acompress.h:141
Inline: True
Inline callers:
  - crypto/acompress.c:crypto_acomp_init_tfm
  - crypto/acompress.c:crypto_acomp_exit_tfm
```
```
In crypto/scompress.c (0)
Location: include/crypto/acompress.h:141
Inline: True
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
In mm/zswap.c (0)
Location: include/crypto/acompress.h:141
Inline: True
```
```
In crypto/acompress.c (ffffffff8178d0b5)
Location: include/crypto/acompress.h:141
Inline: True
Inline callers:
  - crypto/acompress.c:crypto_acomp_init_tfm
  - crypto/acompress.c:crypto_acomp_exit_tfm
```
```
In crypto/scompress.c (0)
Location: include/crypto/acompress.h:141
Inline: True
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
In crypto/acompress.c (ffff8000105c498c)
Location: include/crypto/acompress.h:120
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
  - crypto/acompress.c:crypto_acomp_init_tfm
  - crypto/acompress.c:crypto_acomp_exit_tfm
```
```
In crypto/scompress.c (ffff8000105c53e0)
Location: include/crypto/acompress.h:120
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_acomp_scomp_free_ctx
  - crypto/scompress.c:crypto_acomp_scomp_alloc_ctx
  - crypto/scompress.c:crypto_init_scomp_ops_async
  - crypto/scompress.c:scomp_acomp_comp_decomp
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
In crypto/acompress.c (c0771a70)
Location: include/crypto/acompress.h:120
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
  - crypto/acompress.c:crypto_acomp_init_tfm
  - crypto/acompress.c:crypto_acomp_exit_tfm
```
```
In crypto/scompress.c (c07722d0)
Location: include/crypto/acompress.h:120
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_acomp_scomp_free_ctx
  - crypto/scompress.c:crypto_acomp_scomp_alloc_ctx
  - crypto/scompress.c:crypto_init_scomp_ops_async
  - crypto/scompress.c:scomp_acomp_comp_decomp
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
In crypto/acompress.c (c00000000074dce8)
Location: include/crypto/acompress.h:120
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
  - crypto/acompress.c:crypto_acomp_init_tfm
  - crypto/acompress.c:crypto_acomp_exit_tfm
```
```
In crypto/scompress.c (c00000000074eb20)
Location: include/crypto/acompress.h:120
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_acomp_scomp_free_ctx
  - crypto/scompress.c:crypto_acomp_scomp_alloc_ctx
  - crypto/scompress.c:crypto_init_scomp_ops_async
  - crypto/scompress.c:scomp_acomp_comp_decomp
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
In crypto/acompress.c (ffffffe000408e50)
Location: include/crypto/acompress.h:120
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
  - crypto/acompress.c:crypto_acomp_init_tfm
  - crypto/acompress.c:crypto_acomp_exit_tfm
```
```
In crypto/scompress.c (ffffffe0004096fe)
Location: include/crypto/acompress.h:120
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_acomp_scomp_free_ctx
  - crypto/scompress.c:crypto_acomp_scomp_alloc_ctx
  - crypto/scompress.c:crypto_init_scomp_ops_async
  - crypto/scompress.c:scomp_acomp_comp_decomp
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
In crypto/acompress.c (ffffffff814c14b3)
Location: include/crypto/acompress.h:120
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
  - crypto/acompress.c:crypto_acomp_init_tfm
  - crypto/acompress.c:crypto_acomp_exit_tfm
```
```
In crypto/scompress.c (ffffffff814c1cf5)
Location: include/crypto/acompress.h:120
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_acomp_scomp_free_ctx
  - crypto/scompress.c:crypto_acomp_scomp_alloc_ctx
  - crypto/scompress.c:crypto_init_scomp_ops_async
  - crypto/scompress.c:scomp_acomp_comp_decomp
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
In crypto/acompress.c (ffffffff814b1ed3)
Location: include/crypto/acompress.h:120
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
  - crypto/acompress.c:crypto_acomp_init_tfm
  - crypto/acompress.c:crypto_acomp_exit_tfm
```
```
In crypto/scompress.c (ffffffff814b2715)
Location: include/crypto/acompress.h:120
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_acomp_scomp_free_ctx
  - crypto/scompress.c:crypto_acomp_scomp_alloc_ctx
  - crypto/scompress.c:crypto_init_scomp_ops_async
  - crypto/scompress.c:scomp_acomp_comp_decomp
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
In crypto/acompress.c (ffffffff814bd543)
Location: include/crypto/acompress.h:120
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
  - crypto/acompress.c:crypto_acomp_init_tfm
  - crypto/acompress.c:crypto_acomp_exit_tfm
```
```
In crypto/scompress.c (ffffffff814bdd85)
Location: include/crypto/acompress.h:120
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_acomp_scomp_free_ctx
  - crypto/scompress.c:crypto_acomp_scomp_alloc_ctx
  - crypto/scompress.c:crypto_init_scomp_ops_async
  - crypto/scompress.c:scomp_acomp_comp_decomp
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
In crypto/acompress.c (ffffffff814d6013)
Location: include/crypto/acompress.h:120
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
  - crypto/acompress.c:crypto_acomp_init_tfm
  - crypto/acompress.c:crypto_acomp_exit_tfm
```
```
In crypto/scompress.c (ffffffff814d6855)
Location: include/crypto/acompress.h:120
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_acomp_scomp_free_ctx
  - crypto/scompress.c:crypto_acomp_scomp_alloc_ctx
  - crypto/scompress.c:crypto_init_scomp_ops_async
  - crypto/scompress.c:scomp_acomp_comp_decomp
```
</details>
</li>
</ul>

## Differences
