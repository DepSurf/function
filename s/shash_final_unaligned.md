# Function: <code>shash_final_unaligned</code>

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
In crypto/shash.c (ffffffff813a37b8)
Location: crypto/shash.c:112
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_final
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
In crypto/shash.c (ffffffff813df92e)
Location: crypto/shash.c:112
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_final
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
In crypto/shash.c (ffffffff813f7ebe)
Location: crypto/shash.c:112
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_final
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
In crypto/shash.c (ffffffff81404382)
Location: crypto/shash.c:113
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_final
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
In crypto/shash.c (ffffffff8142cc64)
Location: crypto/shash.c:121
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_final
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
In crypto/shash.c (ffffffff8145f8d7)
Location: crypto/shash.c:121
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_final
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int shash_final_unaligned(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8147d2d0)
Location: crypto/shash.c:129
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_final
```
**Symbols:**

```
ffffffff8147d2d0-ffffffff8147d387: shash_final_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int shash_final_unaligned(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/shash.c (0)
Location: crypto/shash.c:124
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_final
```
**Symbols:**

```
ffffffff814ab5c0-ffffffff814ab66d: shash_final_unaligned (STB_LOCAL)
ffffffff814abe40-ffffffff814abe59: shash_final_unaligned.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int shash_final_unaligned(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814c6290)
Location: crypto/shash.c:124
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_final
```
**Symbols:**

```
ffffffff814c6290-ffffffff814c6343: shash_final_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int shash_final_unaligned(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff815251d0)
Location: crypto/shash.c:123
Inline: False
Direct callers:
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:crypto_shash_finup
```
**Symbols:**

```
ffffffff815251d0-ffffffff81525281: shash_final_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int shash_final_unaligned(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff815420c0)
Location: crypto/shash.c:123
Inline: False
Direct callers:
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:crypto_shash_finup
```
**Symbols:**

```
ffffffff815420c0-ffffffff81542171: shash_final_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int shash_final_unaligned(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8154a760)
Location: crypto/shash.c:135
Inline: False
Direct callers:
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:crypto_shash_finup
```
**Symbols:**

```
ffffffff8154a760-ffffffff8154a811: shash_final_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int shash_final_unaligned(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff815aaf40)
Location: crypto/shash.c:135
Inline: False
Direct callers:
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:crypto_shash_finup
```
**Symbols:**

```
ffffffff815aaf40-ffffffff815aaff1: shash_final_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int shash_final_unaligned(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81652660)
Location: crypto/shash.c:135
Inline: False
Direct callers:
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:crypto_shash_finup
```
**Symbols:**

```
ffffffff81652660-ffffffff81652754: shash_final_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int shash_final_unaligned(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8170c530)
Location: crypto/shash.c:125
Inline: False
Direct callers:
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:crypto_shash_finup
```
**Symbols:**

```
ffffffff8170c530-ffffffff8170c624: shash_final_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int shash_final_unaligned(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81745e30)
Location: crypto/shash.c:140
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
```
**Symbols:**

```
ffffffff81745e30-ffffffff81745f24: shash_final_unaligned (STB_LOCAL)
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
int shash_final_unaligned(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffff8000105c13f0)
Location: crypto/shash.c:124
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_final
```
**Symbols:**

```
ffff8000105c13f0-ffff8000105c14c4: shash_final_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int shash_final_unaligned(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (c076ec04)
Location: crypto/shash.c:124
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_final
```
**Symbols:**

```
c076ec04-c076ecdc: shash_final_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int shash_final_unaligned(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (c0000000007497f0)
Location: crypto/shash.c:124
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_final
```
**Symbols:**

```
c0000000007497f0-c000000000749908: shash_final_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int shash_final_unaligned(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffe00040613c)
Location: crypto/shash.c:124
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_final
```
**Symbols:**

```
ffffffe00040613c-ffffffe0004061c6: shash_final_unaligned (STB_LOCAL)
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
int shash_final_unaligned(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814be870)
Location: crypto/shash.c:124
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_final
```
**Symbols:**

```
ffffffff814be870-ffffffff814be923: shash_final_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int shash_final_unaligned(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814af290)
Location: crypto/shash.c:124
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_final
```
**Symbols:**

```
ffffffff814af290-ffffffff814af343: shash_final_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int shash_final_unaligned(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814ba900)
Location: crypto/shash.c:124
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_final
```
**Symbols:**

```
ffffffff814ba900-ffffffff814ba9b3: shash_final_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int shash_final_unaligned(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814d33b0)
Location: crypto/shash.c:124
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_final
```
**Symbols:**

```
ffffffff814d33b0-ffffffff814d3463: shash_final_unaligned (STB_LOCAL)
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
