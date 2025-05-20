# Function: <code>crypto_comp_decompress</code>

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
In mm/zswap.c (ffffffff811d8832)
Location: include/linux/crypto.h:1866
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_frontswap_load
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
In mm/zswap.c (ffffffff811f6944)
Location: include/linux/crypto.h:1596
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_writeback_entry
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
In mm/zswap.c (ffffffff812072f1)
Location: include/linux/crypto.h:1599
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_writeback_entry
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
In mm/zswap.c (ffffffff81212470)
Location: include/linux/crypto.h:1599
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_writeback_entry
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
In mm/zswap.c (ffffffff8122d0c0)
Location: include/linux/crypto.h:1647
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_writeback_entry
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
Location: include/linux/crypto.h:1660
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_writeback_entry
```
```
In fs/pstore/platform.c (ffffffff813d4cb9)
Location: include/linux/crypto.h:1660
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
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
Location: include/linux/crypto.h:1845
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_writeback_entry
```
```
In fs/pstore/platform.c (ffffffff813ef2eb)
Location: include/linux/crypto.h:1845
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
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
Location: include/linux/crypto.h:1842
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_writeback_entry
```
```
In fs/pstore/platform.c (ffffffff8141b56b)
Location: include/linux/crypto.h:1842
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
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
Location: include/linux/crypto.h:1842
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_writeback_entry
```
```
In fs/pstore/platform.c (ffffffff814353bb)
Location: include/linux/crypto.h:1842
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int crypto_comp_decompress(struct crypto_comp *comp, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/compress.c (ffffffff8151f4f0)
Location: crypto/compress.c:23
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_writeback_entry
```
**Symbols:**

```
ffffffff8151f4f0-ffffffff8151f50b: crypto_comp_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int crypto_comp_decompress(struct crypto_comp *comp, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/compress.c (ffffffff8153c350)
Location: crypto/compress.c:23
Inline: False
Direct callers:
  - fs/pstore/platform.c:decompress_record
```
**Symbols:**

```
ffffffff8153c350-ffffffff8153c36b: crypto_comp_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int crypto_comp_decompress(struct crypto_comp *comp, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/compress.c (ffffffff81544a40)
Location: crypto/compress.c:23
Inline: False
Direct callers:
  - fs/pstore/platform.c:decompress_record
```
**Symbols:**

```
ffffffff81544a40-ffffffff81544a5b: crypto_comp_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int crypto_comp_decompress(struct crypto_comp *comp, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/compress.c (ffffffff815a51e0)
Location: crypto/compress.c:23
Inline: False
Direct callers:
  - fs/pstore/platform.c:decompress_record
```
**Symbols:**

```
ffffffff815a51e0-ffffffff815a51fb: crypto_comp_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int crypto_comp_decompress(struct crypto_comp *comp, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/compress.c (ffffffff8164bee0)
Location: crypto/compress.c:23
Inline: False
Direct callers:
  - fs/pstore/platform.c:decompress_record
```
**Symbols:**

```
ffffffff8164bee0-ffffffff8164bf0a: crypto_comp_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int crypto_comp_decompress(struct crypto_comp *comp, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/compress.c (ffffffff817050d0)
Location: crypto/compress.c:23
Inline: False
Direct callers:
  - fs/pstore/platform.c:decompress_record
```
**Symbols:**

```
ffffffff817050d0-ffffffff817050fa: crypto_comp_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int crypto_comp_decompress(struct crypto_comp *comp, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/compress.c (ffffffff8173f3a0)
Location: crypto/compress.c:23
Inline: False
Direct callers:
  - fs/pstore/platform.c:decompress_record
```
**Symbols:**

```
ffffffff8173f3a0-ffffffff8173f3ca: crypto_comp_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int crypto_comp_decompress(struct crypto_comp *comp, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/compress.c (ffffffff81780220)
Location: crypto/compress.c:23
Inline: False
```
**Symbols:**

```
ffffffff81780220-ffffffff8178024a: crypto_comp_decompress (STB_GLOBAL)
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
Location: include/linux/crypto.h:1842
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_writeback_entry
```
```
In fs/pstore/platform.c (ffff80001051b43c)
Location: include/linux/crypto.h:1842
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
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
Location: include/linux/crypto.h:1842
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_writeback_entry
```
```
In fs/pstore/platform.c (c06d5920)
Location: include/linux/crypto.h:1842
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
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
Location: include/linux/crypto.h:1842
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_writeback_entry
```
```
In fs/pstore/platform.c (c0000000006654c0)
Location: include/linux/crypto.h:1842
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
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
In mm/zswap.c (ffffffe00022a596)
Location: include/linux/crypto.h:1842
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_writeback_entry
```
```
In fs/pstore/platform.c (ffffffe0003843a8)
Location: include/linux/crypto.h:1842
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
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
Location: include/linux/crypto.h:1842
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_writeback_entry
```
```
In fs/pstore/platform.c (ffffffff8142d99b)
Location: include/linux/crypto.h:1842
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
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
Location: include/linux/crypto.h:1842
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_writeback_entry
```
```
In fs/pstore/platform.c (ffffffff8141e41b)
Location: include/linux/crypto.h:1842
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
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
Location: include/linux/crypto.h:1842
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_writeback_entry
```
```
In fs/pstore/platform.c (ffffffff81429b3b)
Location: include/linux/crypto.h:1842
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
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
Location: include/linux/crypto.h:1842
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_writeback_entry
```
```
In fs/pstore/platform.c (ffffffff814409fb)
Location: include/linux/crypto.h:1842
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
