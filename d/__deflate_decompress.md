# Function: <code>__deflate_decompress</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __deflate_decompress(const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen, void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff8146eeb0)
Location: crypto/deflate.c:224
Inline: False
Direct callers:
  - crypto/deflate.c:deflate_sdecompress
  - crypto/deflate.c:deflate_decompress
```
**Symbols:**

```
ffffffff8146eeb0-ffffffff8146ef99: __deflate_decompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __deflate_decompress(const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen, void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff8148c860)
Location: crypto/deflate.c:224
Inline: False
Direct callers:
  - crypto/deflate.c:deflate_sdecompress
  - crypto/deflate.c:deflate_decompress
```
**Symbols:**

```
ffffffff8148c860-ffffffff8148c949: __deflate_decompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __deflate_decompress(const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen, void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff814b9f50)
Location: crypto/deflate.c:220
Inline: False
Direct callers:
  - crypto/deflate.c:deflate_sdecompress
  - crypto/deflate.c:deflate_decompress
```
**Symbols:**

```
ffffffff814b9f50-ffffffff814ba039: __deflate_decompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __deflate_decompress(const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen, void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff814d2d20)
Location: crypto/deflate.c:220
Inline: False
Direct callers:
  - crypto/deflate.c:deflate_sdecompress
  - crypto/deflate.c:deflate_decompress
```
**Symbols:**

```
ffffffff814d2d20-ffffffff814d2e09: __deflate_decompress (STB_LOCAL)
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
In crypto/deflate.c (ffffffff81531e2c)
Location: crypto/deflate.c:220
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_sdecompress
  - crypto/deflate.c:deflate_decompress
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
In crypto/deflate.c (ffffffff8154ed7c)
Location: crypto/deflate.c:220
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_sdecompress
  - crypto/deflate.c:deflate_decompress
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
In crypto/deflate.c (ffffffff815575ec)
Location: crypto/deflate.c:220
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_sdecompress
  - crypto/deflate.c:deflate_decompress
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
In crypto/deflate.c (ffffffff815b889c)
Location: crypto/deflate.c:220
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_sdecompress
  - crypto/deflate.c:deflate_decompress
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
In crypto/deflate.c (ffffffff81661c8c)
Location: crypto/deflate.c:220
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_sdecompress
  - crypto/deflate.c:deflate_decompress
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
In crypto/deflate.c (ffffffff8171bb6c)
Location: crypto/deflate.c:220
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_sdecompress
  - crypto/deflate.c:deflate_decompress
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
In crypto/deflate.c (ffffffff817572fc)
Location: crypto/deflate.c:220
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_sdecompress
  - crypto/deflate.c:deflate_decompress
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
In crypto/deflate.c (ffffffff8179916c)
Location: crypto/deflate.c:203
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_sdecompress
  - crypto/deflate.c:deflate_decompress
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __deflate_decompress(const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen, void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffff8000105cf208)
Location: crypto/deflate.c:220
Inline: False
Direct callers:
  - crypto/deflate.c:deflate_sdecompress
  - crypto/deflate.c:deflate_decompress
```
**Symbols:**

```
ffff8000105cf208-ffff8000105cf300: __deflate_decompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __deflate_decompress(const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen, void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (c077d024)
Location: crypto/deflate.c:220
Inline: False
Direct callers:
  - crypto/deflate.c:deflate_sdecompress
  - crypto/deflate.c:deflate_decompress
```
**Symbols:**

```
c077d024-c077d120: __deflate_decompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __deflate_decompress(const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen, void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (c00000000075b100)
Location: crypto/deflate.c:220
Inline: False
Direct callers:
  - crypto/deflate.c:deflate_sdecompress
  - crypto/deflate.c:deflate_decompress
```
**Symbols:**

```
c00000000075b100-c00000000075b244: __deflate_decompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __deflate_decompress(const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen, void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffe0004141ec)
Location: crypto/deflate.c:220
Inline: False
Direct callers:
  - crypto/deflate.c:deflate_sdecompress
  - crypto/deflate.c:deflate_decompress
```
**Symbols:**

```
ffffffe0004141ec-ffffffe000414298: __deflate_decompress (STB_LOCAL)
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
int __deflate_decompress(const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen, void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff814cb300)
Location: crypto/deflate.c:220
Inline: False
Direct callers:
  - crypto/deflate.c:deflate_sdecompress
  - crypto/deflate.c:deflate_decompress
```
**Symbols:**

```
ffffffff814cb300-ffffffff814cb3e9: __deflate_decompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __deflate_decompress(const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen, void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff814bbd20)
Location: crypto/deflate.c:220
Inline: False
Direct callers:
  - crypto/deflate.c:deflate_sdecompress
  - crypto/deflate.c:deflate_decompress
```
**Symbols:**

```
ffffffff814bbd20-ffffffff814bbe09: __deflate_decompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __deflate_decompress(const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen, void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff814c7390)
Location: crypto/deflate.c:220
Inline: False
Direct callers:
  - crypto/deflate.c:deflate_sdecompress
  - crypto/deflate.c:deflate_decompress
```
**Symbols:**

```
ffffffff814c7390-ffffffff814c7479: __deflate_decompress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __deflate_decompress(const u8 *src, unsigned int slen, u8 *dst, unsigned int *dlen, void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff814dfe60)
Location: crypto/deflate.c:220
Inline: False
Direct callers:
  - crypto/deflate.c:deflate_sdecompress
  - crypto/deflate.c:deflate_decompress
```
**Symbols:**

```
ffffffff814dfe60-ffffffff814dff49: __deflate_decompress (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
