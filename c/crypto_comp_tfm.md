# Function: <code>crypto_comp_tfm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/zswap.c (0)
Location: include/linux/crypto.h:1829
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/zswap.c (0)
Location: include/linux/crypto.h:1559
Inline: True
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
In mm/zswap.c (0)
Location: include/linux/crypto.h:1562
Inline: True
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
In mm/zswap.c (0)
Location: include/linux/crypto.h:1562
Inline: True
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
In mm/zswap.c (0)
Location: include/linux/crypto.h:1610
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
In mm/zswap.c (ffffffff8124fdfb)
Location: include/linux/crypto.h:1623
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/pstore/platform.c (ffffffff813d4cb9)
Location: include/linux/crypto.h:1623
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
  - fs/pstore/platform.c:pstore_unregister
  - fs/pstore/platform.c:pstore_dump
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
In mm/zswap.c (ffffffff8126436b)
Location: include/linux/crypto.h:1808
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/pstore/platform.c (ffffffff813ef2eb)
Location: include/linux/crypto.h:1808
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
  - fs/pstore/platform.c:pstore_unregister
  - fs/pstore/platform.c:pstore_dump
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
In mm/zswap.c (ffffffff8127f2c9)
Location: include/linux/crypto.h:1805
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/pstore/platform.c (ffffffff8141b56b)
Location: include/linux/crypto.h:1805
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
  - fs/pstore/platform.c:pstore_unregister
  - fs/pstore/platform.c:pstore_dump
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
In mm/zswap.c (ffffffff8128ed29)
Location: include/linux/crypto.h:1805
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/pstore/platform.c (ffffffff814353bb)
Location: include/linux/crypto.h:1805
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
  - fs/pstore/platform.c:pstore_unregister
  - fs/pstore/platform.c:pstore_dump
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
In mm/zswap.c (ffffffff812c1032)
Location: include/linux/crypto.h:887
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/pstore/platform.c (ffffffff81484cb5)
Location: include/linux/crypto.h:887
Inline: True
```
```
In crypto/compress.c (ffffffff8151f4f5)
Location: include/linux/crypto.h:887
Inline: True
Inline callers:
  - crypto/compress.c:crypto_comp_decompress
  - crypto/compress.c:crypto_comp_compress
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
In fs/pstore/platform.c (ffffffff814a22e5)
Location: include/linux/crypto.h:923
Inline: True
```
```
In crypto/compress.c (ffffffff8153c355)
Location: include/linux/crypto.h:923
Inline: True
Inline callers:
  - crypto/compress.c:crypto_comp_decompress
  - crypto/compress.c:crypto_comp_compress
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
In fs/pstore/platform.c (ffffffff814a8385)
Location: include/linux/crypto.h:760
Inline: True
```
```
In crypto/compress.c (ffffffff81544a45)
Location: include/linux/crypto.h:760
Inline: True
Inline callers:
  - crypto/compress.c:crypto_comp_decompress
  - crypto/compress.c:crypto_comp_compress
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
In fs/pstore/platform.c (ffffffff815006a5)
Location: include/linux/crypto.h:734
Inline: True
```
```
In crypto/compress.c (ffffffff815a51e5)
Location: include/linux/crypto.h:734
Inline: True
Inline callers:
  - crypto/compress.c:crypto_comp_decompress
  - crypto/compress.c:crypto_comp_compress
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
In fs/pstore/platform.c (ffffffff81591715)
Location: include/linux/crypto.h:743
Inline: True
```
```
In crypto/compress.c (ffffffff8164bee5)
Location: include/linux/crypto.h:743
Inline: True
Inline callers:
  - crypto/compress.c:crypto_comp_decompress
  - crypto/compress.c:crypto_comp_compress
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
In fs/pstore/platform.c (ffffffff83ecf09d)
Location: include/linux/crypto.h:738
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_init
```
```
In crypto/compress.c (ffffffff817050d5)
Location: include/linux/crypto.h:738
Inline: True
Inline callers:
  - crypto/compress.c:crypto_comp_decompress
  - crypto/compress.c:crypto_comp_compress
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
In fs/pstore/platform.c (ffffffff836f412d)
Location: include/linux/crypto.h:511
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_init
```
```
In crypto/compress.c (ffffffff8173f3a5)
Location: include/linux/crypto.h:511
Inline: True
Inline callers:
  - crypto/compress.c:crypto_comp_decompress
  - crypto/compress.c:crypto_comp_compress
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
In crypto/compress.c (ffffffff81780225)
Location: include/linux/crypto.h:511
Inline: True
Inline callers:
  - crypto/compress.c:crypto_comp_decompress
  - crypto/compress.c:crypto_comp_compress
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
In mm/zswap.c (ffff80001032b970)
Location: include/linux/crypto.h:1805
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/pstore/platform.c (ffff80001051b43c)
Location: include/linux/crypto.h:1805
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
  - fs/pstore/platform.c:pstore_unregister
  - fs/pstore/platform.c:pstore_dump
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
In mm/zswap.c (c054215c)
Location: include/linux/crypto.h:1805
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/pstore/platform.c (c06d5920)
Location: include/linux/crypto.h:1805
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
  - fs/pstore/platform.c:pstore_unregister
  - fs/pstore/platform.c:pstore_dump
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
In mm/zswap.c (c0000000004027e8)
Location: include/linux/crypto.h:1805
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/pstore/platform.c (c0000000006654c0)
Location: include/linux/crypto.h:1805
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
  - fs/pstore/platform.c:pstore_unregister
  - fs/pstore/platform.c:pstore_dump
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
In mm/zswap.c (ffffffe00022a5a4)
Location: include/linux/crypto.h:1805
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/pstore/platform.c (ffffffe0003843a8)
Location: include/linux/crypto.h:1805
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
  - fs/pstore/platform.c:pstore_unregister
  - fs/pstore/platform.c:pstore_dump
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
In mm/zswap.c (ffffffff81287309)
Location: include/linux/crypto.h:1805
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/pstore/platform.c (ffffffff8142d99b)
Location: include/linux/crypto.h:1805
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
  - fs/pstore/platform.c:pstore_unregister
  - fs/pstore/platform.c:pstore_dump
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
In mm/zswap.c (ffffffff81279169)
Location: include/linux/crypto.h:1805
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/pstore/platform.c (ffffffff8141e41b)
Location: include/linux/crypto.h:1805
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
  - fs/pstore/platform.c:pstore_unregister
  - fs/pstore/platform.c:pstore_dump
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
In mm/zswap.c (ffffffff81285119)
Location: include/linux/crypto.h:1805
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/pstore/platform.c (ffffffff81429b3b)
Location: include/linux/crypto.h:1805
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
  - fs/pstore/platform.c:pstore_unregister
  - fs/pstore/platform.c:pstore_dump
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
In mm/zswap.c (ffffffff812951b7)
Location: include/linux/crypto.h:1805
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In fs/pstore/platform.c (ffffffff814409fb)
Location: include/linux/crypto.h:1805
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
  - fs/pstore/platform.c:pstore_unregister
  - fs/pstore/platform.c:pstore_dump
```
</details>
</li>
</ul>

## Differences
