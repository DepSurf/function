# Function: <code>shash_digest_unaligned</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int shash_digest_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff813a3880)
Location: crypto/shash.c:168
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_digest
```
**Symbols:**

```
ffffffff813a3880-ffffffff813a38c4: shash_digest_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int shash_digest_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff813dfa00)
Location: crypto/shash.c:168
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_digest
```
**Symbols:**

```
ffffffff813dfa00-ffffffff813dfa44: shash_digest_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int shash_digest_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff813f7f90)
Location: crypto/shash.c:168
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_digest
```
**Symbols:**

```
ffffffff813f7f90-ffffffff813f7fd4: shash_digest_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int shash_digest_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81404450)
Location: crypto/shash.c:169
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_digest
```
**Symbols:**

```
ffffffff81404450-ffffffff81404494: shash_digest_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int shash_digest_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8142cd30)
Location: crypto/shash.c:177
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_digest
```
**Symbols:**

```
ffffffff8142cd30-ffffffff8142cd86: shash_digest_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int shash_digest_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8145f9a0)
Location: crypto/shash.c:177
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_digest
```
**Symbols:**

```
ffffffff8145f9a0-ffffffff8145f9ff: shash_digest_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int shash_digest_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8147d420)
Location: crypto/shash.c:191
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_digest
```
**Symbols:**

```
ffffffff8147d420-ffffffff8147d47f: shash_digest_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int shash_digest_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814ab710)
Location: crypto/shash.c:186
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_digest
```
**Symbols:**

```
ffffffff814ab710-ffffffff814ab772: shash_digest_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int shash_digest_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814c63f0)
Location: crypto/shash.c:186
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_digest
```
**Symbols:**

```
ffffffff814c63f0-ffffffff814c6452: shash_digest_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int shash_digest_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81525b4c)
Location: crypto/shash.c:185
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
```
**Symbols:**

```
ffffffff81525990-ffffffff815259e8: shash_digest_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int shash_digest_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81542a7c)
Location: crypto/shash.c:185
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
```
**Symbols:**

```
ffffffff815428c0-ffffffff81542918: shash_digest_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int shash_digest_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8154b11c)
Location: crypto/shash.c:197
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
```
**Symbols:**

```
ffffffff8154af60-ffffffff8154afb8: shash_digest_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int shash_digest_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff815ab8fc)
Location: crypto/shash.c:197
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
```
**Symbols:**

```
ffffffff815ab740-ffffffff815ab798: shash_digest_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int shash_digest_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff816531e8)
Location: crypto/shash.c:197
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
```
**Symbols:**

```
ffffffff81652fe0-ffffffff8165304e: shash_digest_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int shash_digest_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8170cee8)
Location: crypto/shash.c:187
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
```
**Symbols:**

```
ffffffff8170ccb0-ffffffff8170cd1e: shash_digest_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int shash_digest_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81746320)
Location: crypto/shash.c:219
Inline: True
Direct callers:
  - crypto/shash.c:crypto_shash_digest
```
**Symbols:**

```
ffffffff81746320-ffffffff817463af: shash_digest_unaligned (STB_LOCAL)
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
int shash_digest_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffff8000105c1628)
Location: crypto/shash.c:186
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_digest
```
**Symbols:**

```
ffff8000105c1628-ffff8000105c16b0: shash_digest_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int shash_digest_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (c076ed90)
Location: crypto/shash.c:186
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_digest
```
**Symbols:**

```
c076ed90-c076edf8: shash_digest_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int shash_digest_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (c000000000749a60)
Location: crypto/shash.c:186
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_digest
```
**Symbols:**

```
c000000000749a60-c000000000749b28: shash_digest_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int shash_digest_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffe0004062ea)
Location: crypto/shash.c:186
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_digest
```
**Symbols:**

```
ffffffe0004062ea-ffffffe000406356: shash_digest_unaligned (STB_LOCAL)
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
int shash_digest_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814be9d0)
Location: crypto/shash.c:186
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_digest
```
**Symbols:**

```
ffffffff814be9d0-ffffffff814bea32: shash_digest_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int shash_digest_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814af3f0)
Location: crypto/shash.c:186
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_digest
```
**Symbols:**

```
ffffffff814af3f0-ffffffff814af452: shash_digest_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int shash_digest_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814baa60)
Location: crypto/shash.c:186
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_digest
```
**Symbols:**

```
ffffffff814baa60-ffffffff814baac2: shash_digest_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int shash_digest_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814d3510)
Location: crypto/shash.c:186
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_digest
```
**Symbols:**

```
ffffffff814d3510-ffffffff814d3572: shash_digest_unaligned (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
