# Function: <code>shash_finup_unaligned</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int shash_finup_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff813a3820)
Location: crypto/shash.c:147
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_finup
```
**Symbols:**

```
ffffffff813a3820-ffffffff813a384b: shash_finup_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int shash_finup_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff813df9a0)
Location: crypto/shash.c:147
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_finup
```
**Symbols:**

```
ffffffff813df9a0-ffffffff813df9cb: shash_finup_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int shash_finup_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff813f7f30)
Location: crypto/shash.c:147
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_finup
```
**Symbols:**

```
ffffffff813f7f30-ffffffff813f7f5b: shash_finup_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int shash_finup_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814043f0)
Location: crypto/shash.c:148
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_finup
```
**Symbols:**

```
ffffffff814043f0-ffffffff8140441b: shash_finup_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int shash_finup_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8142ccd0)
Location: crypto/shash.c:156
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_finup
```
**Symbols:**

```
ffffffff8142ccd0-ffffffff8142ccfb: shash_finup_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int shash_finup_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8145f940)
Location: crypto/shash.c:156
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_finup
```
**Symbols:**

```
ffffffff8145f940-ffffffff8145f970: shash_finup_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int shash_finup_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8147d3c0)
Location: crypto/shash.c:170
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_finup
```
**Symbols:**

```
ffffffff8147d3c0-ffffffff8147d3f0: shash_finup_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int shash_finup_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814ab6a0)
Location: crypto/shash.c:165
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_finup
```
**Symbols:**

```
ffffffff814ab6a0-ffffffff814ab6d3: shash_finup_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int shash_finup_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814c6380)
Location: crypto/shash.c:165
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_finup
```
**Symbols:**

```
ffffffff814c6380-ffffffff814c63b3: shash_finup_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int shash_finup_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8152592e)
Location: crypto/shash.c:164
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_finup
```
**Symbols:**

```
ffffffff81525890-ffffffff815258f9: shash_finup_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int shash_finup_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8154285e)
Location: crypto/shash.c:164
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_finup
```
**Symbols:**

```
ffffffff815427c0-ffffffff81542829: shash_finup_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int shash_finup_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8154af09)
Location: crypto/shash.c:176
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_finup
```
**Symbols:**

```
ffffffff8154ae60-ffffffff8154aec9: shash_finup_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int shash_finup_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff815ab6e9)
Location: crypto/shash.c:176
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_finup
```
**Symbols:**

```
ffffffff815ab640-ffffffff815ab6a9: shash_finup_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int shash_finup_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81652f87)
Location: crypto/shash.c:176
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_finup
```
**Symbols:**

```
ffffffff81652ec0-ffffffff81652f3d: shash_finup_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int shash_finup_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8170cc47)
Location: crypto/shash.c:166
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_finup
```
**Symbols:**

```
ffffffff8170cb70-ffffffff8170cbed: shash_finup_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int shash_finup_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8174643c)
Location: crypto/shash.c:187
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_finup
```
**Symbols:**

```
ffffffff81745f40-ffffffff81745f88: shash_finup_unaligned (STB_LOCAL)
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
int shash_finup_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffff8000105c1530)
Location: crypto/shash.c:165
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_finup
```
**Symbols:**

```
ffff8000105c1530-ffff8000105c1598: shash_finup_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int shash_finup_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (c076ed18)
Location: crypto/shash.c:165
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_finup
```
**Symbols:**

```
c076ed18-c076ed50: shash_finup_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int shash_finup_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (c000000000749980)
Location: crypto/shash.c:165
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_finup
```
**Symbols:**

```
c000000000749980-c0000000007499f0: shash_finup_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int shash_finup_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffe00040621c)
Location: crypto/shash.c:165
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_finup
```
**Symbols:**

```
ffffffe00040621c-ffffffe00040627a: shash_finup_unaligned (STB_LOCAL)
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
int shash_finup_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814be960)
Location: crypto/shash.c:165
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_finup
```
**Symbols:**

```
ffffffff814be960-ffffffff814be993: shash_finup_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int shash_finup_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814af380)
Location: crypto/shash.c:165
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_finup
```
**Symbols:**

```
ffffffff814af380-ffffffff814af3b3: shash_finup_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int shash_finup_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814ba9f0)
Location: crypto/shash.c:165
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_finup
```
**Symbols:**

```
ffffffff814ba9f0-ffffffff814baa23: shash_finup_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int shash_finup_unaligned(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814d34a0)
Location: crypto/shash.c:165
Inline: False
Direct callers:
  - crypto/shash.c:crypto_shash_finup
```
**Symbols:**

```
ffffffff814d34a0-ffffffff814d34d3: shash_finup_unaligned (STB_LOCAL)
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
