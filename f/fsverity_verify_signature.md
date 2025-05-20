# Function: <code>fsverity_verify_signature</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int fsverity_verify_signature(const struct fsverity_info *vi, const struct fsverity_descriptor *desc, size_t desc_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/signature.c (0)
Location: fs/verity/signature.c:37
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
ffffffff81351bc4-ffffffff81351c8e: fsverity_verify_signature.cold (STB_LOCAL)
ffffffff81351a80-ffffffff81351bc4: fsverity_verify_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int fsverity_verify_signature(const struct fsverity_info *vi, const struct fsverity_descriptor *desc, size_t desc_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/signature.c (0)
Location: fs/verity/signature.c:40
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
ffffffff81398634-ffffffff813986fe: fsverity_verify_signature.cold (STB_LOCAL)
ffffffff813984f0-ffffffff81398634: fsverity_verify_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int fsverity_verify_signature(const struct fsverity_info *vi, const struct fsverity_descriptor *desc, size_t desc_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/signature.c (0)
Location: fs/verity/signature.c:40
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
ffffffff81beb87b-ffffffff81beb945: fsverity_verify_signature.cold (STB_LOCAL)
ffffffff813a9c70-ffffffff813a9db4: fsverity_verify_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int fsverity_verify_signature(const struct fsverity_info *vi, const u8 *signature, size_t sig_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/signature.c (0)
Location: fs/verity/signature.c:40
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
ffffffff81bdd8ff-ffffffff81bdd9a7: fsverity_verify_signature.cold (STB_LOCAL)
ffffffff813b11a0-ffffffff813b12d8: fsverity_verify_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fsverity_verify_signature(const struct fsverity_info *vi, const u8 *signature, size_t sig_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/signature.c (0)
Location: fs/verity/signature.c:40
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
ffffffff81cc7308-ffffffff81cc73b0: fsverity_verify_signature.cold (STB_LOCAL)
ffffffff81400e90-ffffffff81400fc5: fsverity_verify_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fsverity_verify_signature(const struct fsverity_info *vi, const u8 *signature, size_t sig_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/signature.c (0)
Location: fs/verity/signature.c:40
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
ffffffff81e79873-ffffffff81e7991b: fsverity_verify_signature.cold (STB_LOCAL)
ffffffff81474fd0-ffffffff81475118: fsverity_verify_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fsverity_verify_signature(const struct fsverity_info *vi, const u8 *signature, size_t sig_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/signature.c (ffffffff81507310)
Location: fs/verity/signature.c:40
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
ffffffff81507310-ffffffff815074fa: fsverity_verify_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fsverity_verify_signature(const struct fsverity_info *vi, const u8 *signature, size_t sig_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/signature.c (ffffffff8153e8e0)
Location: fs/verity/signature.c:48
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
ffffffff8153e8e0-ffffffff8153eae5: fsverity_verify_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fsverity_verify_signature(const struct fsverity_info *vi, const u8 *signature, size_t sig_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/signature.c (ffffffff81573dc0)
Location: fs/verity/signature.c:48
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
ffffffff81573dc0-ffffffff81573fc5: fsverity_verify_signature (STB_GLOBAL)
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
int fsverity_verify_signature(const struct fsverity_info *vi, const struct fsverity_descriptor *desc, size_t desc_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/signature.c (ffff800010413b40)
Location: fs/verity/signature.c:37
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
ffff800010413b40-ffff800010413d58: fsverity_verify_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fsverity_verify_signature(const struct fsverity_info *vi, const struct fsverity_descriptor *desc, size_t desc_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/signature.c (c05dfdbc)
Location: fs/verity/signature.c:37
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
c05dfdbc-c05dffc0: fsverity_verify_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fsverity_verify_signature(const struct fsverity_info *vi, const struct fsverity_descriptor *desc, size_t desc_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/signature.c (c000000000521bd0)
Location: fs/verity/signature.c:37
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_create_info
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
c000000000521bd0-c000000000521e74: fsverity_verify_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fsverity_verify_signature(const struct fsverity_info *vi, const struct fsverity_descriptor *desc, size_t desc_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/signature.c (ffffffe0002bb4e2)
Location: fs/verity/signature.c:37
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
ffffffe0002bb4e2-ffffffe0002bb6d0: fsverity_verify_signature (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int fsverity_verify_signature(const struct fsverity_info *vi, const struct fsverity_descriptor *desc, size_t desc_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/signature.c (0)
Location: fs/verity/signature.c:37
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
ffffffff8134a1a4-ffffffff8134a26e: fsverity_verify_signature.cold (STB_LOCAL)
ffffffff8134a060-ffffffff8134a1a4: fsverity_verify_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int fsverity_verify_signature(const struct fsverity_info *vi, const struct fsverity_descriptor *desc, size_t desc_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/signature.c (0)
Location: fs/verity/signature.c:37
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
ffffffff8133ae84-ffffffff8133af4e: fsverity_verify_signature.cold (STB_LOCAL)
ffffffff8133ad40-ffffffff8133ae84: fsverity_verify_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int fsverity_verify_signature(const struct fsverity_info *vi, const struct fsverity_descriptor *desc, size_t desc_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/signature.c (0)
Location: fs/verity/signature.c:37
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
ffffffff81347c74-ffffffff81347d3e: fsverity_verify_signature.cold (STB_LOCAL)
ffffffff81347b30-ffffffff81347c74: fsverity_verify_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int fsverity_verify_signature(const struct fsverity_info *vi, const struct fsverity_descriptor *desc, size_t desc_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/signature.c (0)
Location: fs/verity/signature.c:37
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
ffffffff8135af74-ffffffff8135b03e: fsverity_verify_signature.cold (STB_LOCAL)
ffffffff8135ae30-ffffffff8135af74: fsverity_verify_signature (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const u8 *signature</code>
</li>
<li>
<b>Param added. </b>
<code>size_t sig_size</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct fsverity_descriptor *desc</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t desc_size</code>
</li>
</ul>
</details>
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
