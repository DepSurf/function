# Function: <code>crypto_acomp_reqtfm</code>

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
In crypto/acompress.c (ffffffff813fa5bc)
Location: include/crypto/acompress.h:146
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
```
```
In crypto/scompress.c (0)
Location: include/crypto/acompress.h:146
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
In crypto/acompress.c (ffffffff81406d9c)
Location: include/crypto/acompress.h:146
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
```
```
In crypto/scompress.c (0)
Location: include/crypto/acompress.h:146
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
In crypto/acompress.c (ffffffff8142f6dc)
Location: include/crypto/acompress.h:146
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
```
```
In crypto/scompress.c (0)
Location: include/crypto/acompress.h:146
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
In crypto/acompress.c (ffffffff81462385)
Location: include/crypto/acompress.h:146
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
```
```
In crypto/scompress.c (ffffffff81462c15)
Location: include/crypto/acompress.h:146
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_acomp_scomp_free_ctx
  - crypto/scompress.c:crypto_acomp_scomp_alloc_ctx
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
In crypto/acompress.c (ffffffff8147ffe5)
Location: include/crypto/acompress.h:146
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
```
```
In crypto/scompress.c (ffffffff81480895)
Location: include/crypto/acompress.h:146
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_acomp_scomp_free_ctx
  - crypto/scompress.c:crypto_acomp_scomp_alloc_ctx
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
In crypto/acompress.c (ffffffff814ae235)
Location: include/crypto/acompress.h:141
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
```
```
In crypto/scompress.c (ffffffff814aea85)
Location: include/crypto/acompress.h:141
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_acomp_scomp_free_ctx
  - crypto/scompress.c:crypto_acomp_scomp_alloc_ctx
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
In crypto/acompress.c (ffffffff814c8ec5)
Location: include/crypto/acompress.h:141
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
```
```
In crypto/scompress.c (ffffffff814c9715)
Location: include/crypto/acompress.h:141
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_acomp_scomp_free_ctx
  - crypto/scompress.c:crypto_acomp_scomp_alloc_ctx
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
In crypto/acompress.c (ffffffff815282c5)
Location: include/crypto/acompress.h:141
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
```
```
In crypto/scompress.c (ffffffff81528ad5)
Location: include/crypto/acompress.h:141
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_acomp_scomp_free_ctx
  - crypto/scompress.c:crypto_acomp_scomp_alloc_ctx
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
In mm/zswap.c (ffffffff812cd569)
Location: include/crypto/acompress.h:159
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In crypto/acompress.c (ffffffff81545275)
Location: include/crypto/acompress.h:159
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
```
```
In crypto/scompress.c (ffffffff81545aa5)
Location: include/crypto/acompress.h:159
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_acomp_scomp_free_ctx
  - crypto/scompress.c:crypto_acomp_scomp_alloc_ctx
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
In mm/zswap.c (ffffffff812d3fc1)
Location: include/crypto/acompress.h:159
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In crypto/acompress.c (ffffffff8154d905)
Location: include/crypto/acompress.h:159
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
```
```
In crypto/scompress.c (ffffffff8154e125)
Location: include/crypto/acompress.h:159
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_acomp_scomp_free_ctx
  - crypto/scompress.c:crypto_acomp_scomp_alloc_ctx
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
In mm/zswap.c (ffffffff81319c6b)
Location: include/crypto/acompress.h:159
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In crypto/acompress.c (ffffffff815ae0e5)
Location: include/crypto/acompress.h:159
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
```
```
In crypto/scompress.c (ffffffff815ae995)
Location: include/crypto/acompress.h:159
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_acomp_scomp_free_ctx
  - crypto/scompress.c:crypto_acomp_scomp_alloc_ctx
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
In mm/zswap.c (ffffffff81385550)
Location: include/crypto/acompress.h:159
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In crypto/acompress.c (ffffffff81656605)
Location: include/crypto/acompress.h:159
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
```
```
In crypto/scompress.c (ffffffff81656fa5)
Location: include/crypto/acompress.h:159
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_acomp_scomp_free_ctx
  - crypto/scompress.c:crypto_acomp_scomp_alloc_ctx
  - crypto/scompress.c:scomp_acomp_comp_decomp
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
In mm/zswap.c (ffffffff814032c0)
Location: include/crypto/acompress.h:160
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In crypto/acompress.c (ffffffff81710885)
Location: include/crypto/acompress.h:160
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
```
```
In crypto/scompress.c (ffffffff81711375)
Location: include/crypto/acompress.h:160
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_acomp_scomp_free_ctx
  - crypto/scompress.c:crypto_acomp_scomp_alloc_ctx
  - crypto/scompress.c:scomp_acomp_comp_decomp
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
In mm/zswap.c (ffffffff81436810)
Location: include/crypto/acompress.h:163
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In crypto/acompress.c (ffffffff8174b335)
Location: include/crypto/acompress.h:163
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
```
```
In crypto/scompress.c (ffffffff8174be65)
Location: include/crypto/acompress.h:163
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_acomp_scomp_free_ctx
  - crypto/scompress.c:crypto_acomp_scomp_alloc_ctx
  - crypto/scompress.c:scomp_acomp_comp_decomp
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
In mm/zswap.c (ffffffff81470b43)
Location: include/crypto/acompress.h:163
Inline: True
Inline callers:
  - mm/zswap.c:zswap_store
  - mm/zswap.c:__zswap_load
```
```
In crypto/acompress.c (ffffffff8178d205)
Location: include/crypto/acompress.h:163
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
```
```
In crypto/scompress.c (ffffffff8178dd45)
Location: include/crypto/acompress.h:163
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_acomp_scomp_free_ctx
  - crypto/scompress.c:crypto_acomp_scomp_alloc_ctx
  - crypto/scompress.c:scomp_acomp_comp_decomp
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
In crypto/acompress.c (ffff8000105c4980)
Location: include/crypto/acompress.h:141
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
```
```
In crypto/scompress.c (ffff8000105c53e0)
Location: include/crypto/acompress.h:141
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_acomp_scomp_free_ctx
  - crypto/scompress.c:crypto_acomp_scomp_alloc_ctx
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
In crypto/acompress.c (c0771a6c)
Location: include/crypto/acompress.h:141
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
```
```
In crypto/scompress.c (c07722d0)
Location: include/crypto/acompress.h:141
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_acomp_scomp_free_ctx
  - crypto/scompress.c:crypto_acomp_scomp_alloc_ctx
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
In crypto/acompress.c (c00000000074dcd4)
Location: include/crypto/acompress.h:141
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
```
```
In crypto/scompress.c (c00000000074eb20)
Location: include/crypto/acompress.h:141
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_acomp_scomp_free_ctx
  - crypto/scompress.c:crypto_acomp_scomp_alloc_ctx
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
In crypto/acompress.c (ffffffe000408e4c)
Location: include/crypto/acompress.h:141
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
```
```
In crypto/scompress.c (ffffffe0004096fe)
Location: include/crypto/acompress.h:141
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_acomp_scomp_free_ctx
  - crypto/scompress.c:crypto_acomp_scomp_alloc_ctx
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
In crypto/acompress.c (ffffffff814c14a5)
Location: include/crypto/acompress.h:141
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
```
```
In crypto/scompress.c (ffffffff814c1cf5)
Location: include/crypto/acompress.h:141
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_acomp_scomp_free_ctx
  - crypto/scompress.c:crypto_acomp_scomp_alloc_ctx
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
In crypto/acompress.c (ffffffff814b1ec5)
Location: include/crypto/acompress.h:141
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
```
```
In crypto/scompress.c (ffffffff814b2715)
Location: include/crypto/acompress.h:141
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_acomp_scomp_free_ctx
  - crypto/scompress.c:crypto_acomp_scomp_alloc_ctx
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
In crypto/acompress.c (ffffffff814bd535)
Location: include/crypto/acompress.h:141
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
```
```
In crypto/scompress.c (ffffffff814bdd85)
Location: include/crypto/acompress.h:141
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_acomp_scomp_free_ctx
  - crypto/scompress.c:crypto_acomp_scomp_alloc_ctx
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
In crypto/acompress.c (ffffffff814d6005)
Location: include/crypto/acompress.h:141
Inline: True
Inline callers:
  - crypto/acompress.c:acomp_request_free
```
```
In crypto/scompress.c (ffffffff814d6855)
Location: include/crypto/acompress.h:141
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_acomp_scomp_free_ctx
  - crypto/scompress.c:crypto_acomp_scomp_alloc_ctx
  - crypto/scompress.c:scomp_acomp_comp_decomp
```
</details>
</li>
</ul>

## Differences
