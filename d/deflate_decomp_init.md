# Function: <code>deflate_decomp_init</code>

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
int deflate_decomp_init(struct deflate_ctx *ctx, int format);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff8146ee30)
Location: crypto/deflate.c:75
Inline: False
Direct callers:
  - crypto/deflate.c:deflate_init
```
**Symbols:**

```
ffffffff8146ee30-ffffffff8146eea7: deflate_decomp_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int deflate_decomp_init(struct deflate_ctx *ctx, int format);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff8148c7e0)
Location: crypto/deflate.c:75
Inline: False
Direct callers:
  - crypto/deflate.c:deflate_init
```
**Symbols:**

```
ffffffff8148c7e0-ffffffff8148c857: deflate_decomp_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int deflate_decomp_init(struct deflate_ctx *ctx, int format);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff814b9ed0)
Location: crypto/deflate.c:71
Inline: False
Direct callers:
  - crypto/deflate.c:deflate_init
```
**Symbols:**

```
ffffffff814b9ed0-ffffffff814b9f47: deflate_decomp_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int deflate_decomp_init(struct deflate_ctx *ctx, int format);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff814d2ca0)
Location: crypto/deflate.c:71
Inline: False
Direct callers:
  - crypto/deflate.c:deflate_init
```
**Symbols:**

```
ffffffff814d2ca0-ffffffff814d2d17: deflate_decomp_init (STB_LOCAL)
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
In crypto/deflate.c (ffffffff81532180)
Location: crypto/deflate.c:71
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:zlib_deflate_alloc_ctx
  - crypto/deflate.c:deflate_alloc_ctx
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
In crypto/deflate.c (ffffffff8154f0d0)
Location: crypto/deflate.c:71
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:zlib_deflate_alloc_ctx
  - crypto/deflate.c:deflate_alloc_ctx
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
In crypto/deflate.c (ffffffff81557940)
Location: crypto/deflate.c:71
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:zlib_deflate_alloc_ctx
  - crypto/deflate.c:deflate_alloc_ctx
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
In crypto/deflate.c (ffffffff815b8bf0)
Location: crypto/deflate.c:71
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:zlib_deflate_alloc_ctx
  - crypto/deflate.c:deflate_alloc_ctx
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int deflate_decomp_init(struct deflate_ctx *ctx, int format);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff81662036)
Location: crypto/deflate.c:71
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_init
```
**Symbols:**

```
ffffffff81661bd0-ffffffff81661c4f: deflate_decomp_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int deflate_decomp_init(struct deflate_ctx *ctx, int format);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff8171bf96)
Location: crypto/deflate.c:71
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_init
```
**Symbols:**

```
ffffffff8171baa0-ffffffff8171bb1f: deflate_decomp_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int deflate_decomp_init(struct deflate_ctx *ctx, int format);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff81757726)
Location: crypto/deflate.c:71
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_init
```
**Symbols:**

```
ffffffff81757230-ffffffff817572af: deflate_decomp_init (STB_LOCAL)
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
In crypto/deflate.c (ffffffff81799624)
Location: crypto/deflate.c:67
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_init
  - crypto/deflate.c:deflate_alloc_ctx
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
int deflate_decomp_init(struct deflate_ctx *ctx, int format);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffff8000105cf188)
Location: crypto/deflate.c:71
Inline: False
Direct callers:
  - crypto/deflate.c:deflate_init
```
**Symbols:**

```
ffff8000105cf188-ffff8000105cf204: deflate_decomp_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int deflate_decomp_init(struct deflate_ctx *ctx, int format);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (c077cfbc)
Location: crypto/deflate.c:71
Inline: False
Direct callers:
  - crypto/deflate.c:deflate_init
```
**Symbols:**

```
c077cfbc-c077d024: deflate_decomp_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int deflate_decomp_init(struct deflate_ctx *ctx, int format);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (c00000000075b040)
Location: crypto/deflate.c:71
Inline: False
Direct callers:
  - crypto/deflate.c:deflate_init
```
**Symbols:**

```
c00000000075b040-c00000000075b0fc: deflate_decomp_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int deflate_decomp_init(struct deflate_ctx *ctx, int format);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffe00041417e)
Location: crypto/deflate.c:71
Inline: False
Direct callers:
  - crypto/deflate.c:deflate_init
```
**Symbols:**

```
ffffffe00041417e-ffffffe0004141ec: deflate_decomp_init (STB_LOCAL)
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
int deflate_decomp_init(struct deflate_ctx *ctx, int format);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff814cb280)
Location: crypto/deflate.c:71
Inline: False
Direct callers:
  - crypto/deflate.c:deflate_init
```
**Symbols:**

```
ffffffff814cb280-ffffffff814cb2f7: deflate_decomp_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int deflate_decomp_init(struct deflate_ctx *ctx, int format);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff814bbca0)
Location: crypto/deflate.c:71
Inline: False
Direct callers:
  - crypto/deflate.c:deflate_init
```
**Symbols:**

```
ffffffff814bbca0-ffffffff814bbd17: deflate_decomp_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int deflate_decomp_init(struct deflate_ctx *ctx, int format);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff814c7310)
Location: crypto/deflate.c:71
Inline: False
Direct callers:
  - crypto/deflate.c:deflate_init
```
**Symbols:**

```
ffffffff814c7310-ffffffff814c7387: deflate_decomp_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int deflate_decomp_init(struct deflate_ctx *ctx, int format);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff814dfde0)
Location: crypto/deflate.c:71
Inline: False
Direct callers:
  - crypto/deflate.c:deflate_init
```
**Symbols:**

```
ffffffff814dfde0-ffffffff814dfe57: deflate_decomp_init (STB_LOCAL)
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
