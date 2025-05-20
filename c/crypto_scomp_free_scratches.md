# Function: <code>crypto_scomp_free_scratches</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void crypto_scomp_free_scratches(void **scratches);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff813fa7f0)
Location: crypto/scompress.c:72
Inline: False
Direct callers:
  - crypto/scompress.c:crypto_scomp_alloc_scratches
```
**Symbols:**

```
ffffffff813fa7f0-ffffffff813fa856: crypto_scomp_free_scratches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/scompress.c (ffffffff81407207)
Location: crypto/scompress.c:73
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_scomp_alloc_scratches
Direct callers:
  - crypto/scompress.c:crypto_scomp_alloc_scratches
```
**Symbols:**

```
ffffffff81407110-ffffffff8140716f: crypto_scomp_free_scratches.part.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/scompress.c (ffffffff8142fc51)
Location: crypto/scompress.c:68
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_alloc_scratches
Direct callers:
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_alloc_scratches
```
**Symbols:**

```
ffffffff8142fbc0-ffffffff8142fc19: crypto_scomp_free_scratches.part.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/scompress.c (ffffffff814629c1)
Location: crypto/scompress.c:68
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_alloc_scratches
Direct callers:
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_alloc_scratches
```
**Symbols:**

```
ffffffff81462930-ffffffff81462989: crypto_scomp_free_scratches.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/scompress.c (ffffffff81480641)
Location: crypto/scompress.c:65
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_alloc_scratches
Direct callers:
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_alloc_scratches
```
**Symbols:**

```
ffffffff814805b0-ffffffff81480609: crypto_scomp_free_scratches.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void crypto_scomp_free_scratches();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff814ae5e0)
Location: crypto/scompress.c:68
Inline: False
Direct callers:
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/scompress.c:crypto_scomp_init_tfm
```
**Symbols:**

```
ffffffff814ae5e0-ffffffff814ae64e: crypto_scomp_free_scratches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void crypto_scomp_free_scratches();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff814c9270)
Location: crypto/scompress.c:68
Inline: False
Direct callers:
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/scompress.c:crypto_scomp_init_tfm
```
**Symbols:**

```
ffffffff814c9270-ffffffff814c92de: crypto_scomp_free_scratches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void crypto_scomp_free_scratches();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff81528640)
Location: crypto/scompress.c:68
Inline: False
Direct callers:
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/scompress.c:crypto_scomp_alloc_scratches
```
**Symbols:**

```
ffffffff81528640-ffffffff815286ae: crypto_scomp_free_scratches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void crypto_scomp_free_scratches();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff815455e0)
Location: crypto/scompress.c:68
Inline: False
Direct callers:
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/scompress.c:crypto_scomp_alloc_scratches
```
**Symbols:**

```
ffffffff815455e0-ffffffff8154564e: crypto_scomp_free_scratches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void crypto_scomp_free_scratches();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff8154dc80)
Location: crypto/scompress.c:68
Inline: False
Direct callers:
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/scompress.c:crypto_scomp_init_tfm
```
**Symbols:**

```
ffffffff8154dc80-ffffffff8154dcee: crypto_scomp_free_scratches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void crypto_scomp_free_scratches();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff815ae460)
Location: crypto/scompress.c:68
Inline: False
Direct callers:
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/scompress.c:crypto_scomp_init_tfm
```
**Symbols:**

```
ffffffff815ae460-ffffffff815ae4eb: crypto_scomp_free_scratches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void crypto_scomp_free_scratches();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff816569f0)
Location: crypto/scompress.c:68
Inline: False
Direct callers:
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/scompress.c:crypto_scomp_init_tfm
```
**Symbols:**

```
ffffffff816569f0-ffffffff81656a85: crypto_scomp_free_scratches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void crypto_scomp_free_scratches();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff81710ec0)
Location: crypto/scompress.c:68
Inline: False
Direct callers:
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/scompress.c:crypto_scomp_init_tfm
```
**Symbols:**

```
ffffffff81710ec0-ffffffff81710f5c: crypto_scomp_free_scratches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void crypto_scomp_free_scratches();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff8174b9b0)
Location: crypto/scompress.c:61
Inline: False
Direct callers:
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/scompress.c:crypto_scomp_init_tfm
```
**Symbols:**

```
ffffffff8174b9b0-ffffffff8174ba4c: crypto_scomp_free_scratches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void crypto_scomp_free_scratches();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff8178d890)
Location: crypto/scompress.c:61
Inline: False
Direct callers:
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/scompress.c:crypto_scomp_init_tfm
```
**Symbols:**

```
ffffffff8178d890-ffffffff8178d92c: crypto_scomp_free_scratches (STB_LOCAL)
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
void crypto_scomp_free_scratches();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffff8000105c4c18)
Location: crypto/scompress.c:68
Inline: False
Direct callers:
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/scompress.c:crypto_scomp_init_tfm
```
**Symbols:**

```
ffff8000105c4c18-ffff8000105c4ca8: crypto_scomp_free_scratches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void crypto_scomp_free_scratches();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (c0771e10)
Location: crypto/scompress.c:68
Inline: False
Direct callers:
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/scompress.c:crypto_scomp_init_tfm
```
**Symbols:**

```
c0771e10-c0771e8c: crypto_scomp_free_scratches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void crypto_scomp_free_scratches();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (c00000000074e2d0)
Location: crypto/scompress.c:68
Inline: False
Direct callers:
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/scompress.c:crypto_scomp_init_tfm
```
**Symbols:**

```
c00000000074e2d0-c00000000074e3ac: crypto_scomp_free_scratches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void crypto_scomp_free_scratches();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffe0004091f8)
Location: crypto/scompress.c:68
Inline: False
Direct callers:
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/scompress.c:crypto_scomp_init_tfm
```
**Symbols:**

```
ffffffe0004091f8-ffffffe00040928e: crypto_scomp_free_scratches (STB_LOCAL)
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
void crypto_scomp_free_scratches();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff814c1850)
Location: crypto/scompress.c:68
Inline: False
Direct callers:
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/scompress.c:crypto_scomp_init_tfm
```
**Symbols:**

```
ffffffff814c1850-ffffffff814c18be: crypto_scomp_free_scratches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void crypto_scomp_free_scratches();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff814b2270)
Location: crypto/scompress.c:68
Inline: False
Direct callers:
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/scompress.c:crypto_scomp_init_tfm
```
**Symbols:**

```
ffffffff814b2270-ffffffff814b22de: crypto_scomp_free_scratches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void crypto_scomp_free_scratches();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff814bd8e0)
Location: crypto/scompress.c:68
Inline: False
Direct callers:
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/scompress.c:crypto_scomp_init_tfm
```
**Symbols:**

```
ffffffff814bd8e0-ffffffff814bd94e: crypto_scomp_free_scratches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void crypto_scomp_free_scratches();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff814d63b0)
Location: crypto/scompress.c:68
Inline: False
Direct callers:
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/scompress.c:crypto_scomp_init_tfm
```
**Symbols:**

```
ffffffff814d63b0-ffffffff814d641e: crypto_scomp_free_scratches (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
