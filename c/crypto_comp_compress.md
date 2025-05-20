# Function: <code>crypto_comp_compress</code>

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
In mm/zswap.c (ffffffff811d8d56)
Location: include/linux/crypto.h:1858
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
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
In mm/zswap.c (ffffffff811f6bcc)
Location: include/linux/crypto.h:1588
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
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
In mm/zswap.c (ffffffff81207580)
Location: include/linux/crypto.h:1591
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
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
In mm/zswap.c (ffffffff81212c90)
Location: include/linux/crypto.h:1591
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
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
In mm/zswap.c (ffffffff8122d759)
Location: include/linux/crypto.h:1639
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
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
In mm/zswap.c (ffffffff8125081d)
Location: include/linux/crypto.h:1652
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In fs/pstore/platform.c (ffffffff813d4934)
Location: include/linux/crypto.h:1652
Inline: True
Inline callers:
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
In mm/zswap.c (ffffffff81264cf2)
Location: include/linux/crypto.h:1837
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In fs/pstore/platform.c (ffffffff813eef43)
Location: include/linux/crypto.h:1837
Inline: True
Inline callers:
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
In mm/zswap.c (ffffffff8127f900)
Location: include/linux/crypto.h:1834
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In fs/pstore/platform.c (ffffffff8141b1f6)
Location: include/linux/crypto.h:1834
Inline: True
Inline callers:
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
In mm/zswap.c (ffffffff8128f6f0)
Location: include/linux/crypto.h:1834
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In fs/pstore/platform.c (ffffffff81435046)
Location: include/linux/crypto.h:1834
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int crypto_comp_compress(struct crypto_comp *comp, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/compress.c (ffffffff8151f4d0)
Location: crypto/compress.c:12
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
ffffffff8151f4d0-ffffffff8151f4eb: crypto_comp_compress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int crypto_comp_compress(struct crypto_comp *comp, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/compress.c (ffffffff8153c330)
Location: crypto/compress.c:12
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffffffff8153c330-ffffffff8153c34b: crypto_comp_compress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int crypto_comp_compress(struct crypto_comp *comp, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/compress.c (ffffffff81544a20)
Location: crypto/compress.c:12
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffffffff81544a20-ffffffff81544a3b: crypto_comp_compress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int crypto_comp_compress(struct crypto_comp *comp, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/compress.c (ffffffff815a51c0)
Location: crypto/compress.c:12
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffffffff815a51c0-ffffffff815a51db: crypto_comp_compress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int crypto_comp_compress(struct crypto_comp *comp, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/compress.c (ffffffff8164beb0)
Location: crypto/compress.c:12
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffffffff8164beb0-ffffffff8164beda: crypto_comp_compress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int crypto_comp_compress(struct crypto_comp *comp, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/compress.c (ffffffff81705090)
Location: crypto/compress.c:12
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffffffff81705090-ffffffff817050ba: crypto_comp_compress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int crypto_comp_compress(struct crypto_comp *comp, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/compress.c (ffffffff8173f360)
Location: crypto/compress.c:12
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffffffff8173f360-ffffffff8173f38a: crypto_comp_compress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int crypto_comp_compress(struct crypto_comp *comp, const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/compress.c (ffffffff817801e0)
Location: crypto/compress.c:12
Inline: False
```
**Symbols:**

```
ffffffff817801e0-ffffffff8178020a: crypto_comp_compress (STB_GLOBAL)
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
In mm/zswap.c (ffff80001032c084)
Location: include/linux/crypto.h:1834
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In fs/pstore/platform.c (ffff80001051b094)
Location: include/linux/crypto.h:1834
Inline: True
Inline callers:
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
In mm/zswap.c (c0542464)
Location: include/linux/crypto.h:1834
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In fs/pstore/platform.c (c06d55dc)
Location: include/linux/crypto.h:1834
Inline: True
Inline callers:
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
In mm/zswap.c (c000000000402c7c)
Location: include/linux/crypto.h:1834
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In fs/pstore/platform.c (c000000000665064)
Location: include/linux/crypto.h:1834
Inline: True
Inline callers:
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
In mm/zswap.c (ffffffe00022acb2)
Location: include/linux/crypto.h:1834
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In fs/pstore/platform.c (ffffffe0003840c2)
Location: include/linux/crypto.h:1834
Inline: True
Inline callers:
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
In mm/zswap.c (ffffffff81287cd0)
Location: include/linux/crypto.h:1834
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In fs/pstore/platform.c (ffffffff8142d626)
Location: include/linux/crypto.h:1834
Inline: True
Inline callers:
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
In mm/zswap.c (ffffffff81279b30)
Location: include/linux/crypto.h:1834
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In fs/pstore/platform.c (ffffffff8141e0a6)
Location: include/linux/crypto.h:1834
Inline: True
Inline callers:
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
In mm/zswap.c (ffffffff81285ae0)
Location: include/linux/crypto.h:1834
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In fs/pstore/platform.c (ffffffff814297c6)
Location: include/linux/crypto.h:1834
Inline: True
Inline callers:
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
In mm/zswap.c (ffffffff81295833)
Location: include/linux/crypto.h:1834
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In fs/pstore/platform.c (ffffffff81440686)
Location: include/linux/crypto.h:1834
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
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
