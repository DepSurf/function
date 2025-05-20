# Function: <code>shash_update_unaligned</code>

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
In crypto/shash.c (ffffffff813a36c1)
Location: crypto/shash.c:74
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_update
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
In crypto/shash.c (ffffffff813df827)
Location: crypto/shash.c:74
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_update
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
In crypto/shash.c (ffffffff813f7db7)
Location: crypto/shash.c:74
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_update
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
In crypto/shash.c (ffffffff81404267)
Location: crypto/shash.c:75
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_update
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
In crypto/shash.c (ffffffff8142cb3f)
Location: crypto/shash.c:83
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_update
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
In crypto/shash.c (ffffffff8145f7b3)
Location: crypto/shash.c:83
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int shash_update_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8147d180)
Location: crypto/shash.c:85
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_update
```
**Symbols:**

```
ffffffff8147d180-ffffffff8147d29c: shash_update_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int shash_update_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/shash.c (0)
Location: crypto/shash.c:80
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_update
```
**Symbols:**

```
ffffffff814ab480-ffffffff814ab58d: shash_update_unaligned (STB_LOCAL)
ffffffff814abe27-ffffffff814abe40: shash_update_unaligned.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int shash_update_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814c6140)
Location: crypto/shash.c:80
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_update
```
**Symbols:**

```
ffffffff814c6140-ffffffff814c625c: shash_update_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int shash_update_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81525070)
Location: crypto/shash.c:79
Inline: False
Direct callers:
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_update
  - crypto/shash.c:crypto_shash_finup
```
**Symbols:**

```
ffffffff81525070-ffffffff81525195: shash_update_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int shash_update_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81541f60)
Location: crypto/shash.c:79
Inline: False
Direct callers:
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_update
  - crypto/shash.c:crypto_shash_finup
```
**Symbols:**

```
ffffffff81541f60-ffffffff81542085: shash_update_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int shash_update_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8154a600)
Location: crypto/shash.c:91
Inline: False
Direct callers:
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_update
  - crypto/shash.c:crypto_shash_finup
```
**Symbols:**

```
ffffffff8154a600-ffffffff8154a725: shash_update_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int shash_update_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff815aade0)
Location: crypto/shash.c:91
Inline: False
Direct callers:
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_update
  - crypto/shash.c:crypto_shash_finup
```
**Symbols:**

```
ffffffff815aade0-ffffffff815aaf05: shash_update_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int shash_update_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff816524c0)
Location: crypto/shash.c:91
Inline: False
Direct callers:
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_update
  - crypto/shash.c:crypto_shash_finup
```
**Symbols:**

```
ffffffff816524c0-ffffffff8165261b: shash_update_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int shash_update_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8170c370)
Location: crypto/shash.c:81
Inline: False
Direct callers:
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_update
  - crypto/shash.c:crypto_shash_finup
```
**Symbols:**

```
ffffffff8170c370-ffffffff8170c4cb: shash_update_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int shash_update_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81745cc0)
Location: crypto/shash.c:90
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_update
```
**Symbols:**

```
ffffffff81745cc0-ffffffff81745e1b: shash_update_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int shash_update_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffff8000105c1248)
Location: crypto/shash.c:80
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_update
```
**Symbols:**

```
ffff8000105c1248-ffff8000105c1370: shash_update_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int shash_update_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (c076eab8)
Location: crypto/shash.c:80
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_update
```
**Symbols:**

```
c076eab8-c076ebc8: shash_update_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int shash_update_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (c0000000007495d0)
Location: crypto/shash.c:80
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_update
```
**Symbols:**

```
c0000000007495d0-c000000000749778: shash_update_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int shash_update_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffe000406000)
Location: crypto/shash.c:80
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_update
```
**Symbols:**

```
ffffffe000406000-ffffffe0004060da: shash_update_unaligned (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int shash_update_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814be720)
Location: crypto/shash.c:80
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_update
```
**Symbols:**

```
ffffffff814be720-ffffffff814be83c: shash_update_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int shash_update_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814af140)
Location: crypto/shash.c:80
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_update
```
**Symbols:**

```
ffffffff814af140-ffffffff814af25c: shash_update_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int shash_update_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814ba7b0)
Location: crypto/shash.c:80
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_update
```
**Symbols:**

```
ffffffff814ba7b0-ffffffff814ba8cc: shash_update_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int shash_update_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814d3260)
Location: crypto/shash.c:80
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_update
```
**Symbols:**

```
ffffffff814d3260-ffffffff814d337c: shash_update_unaligned (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
