# Function: <code>irq_fpu_usable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool irq_fpu_usable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81039950)
Location: arch/x86/kernel/fpu/core.c:100
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
**Symbols:**

```
ffffffff81039950-ffffffff810399c8: irq_fpu_usable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool irq_fpu_usable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81038940)
Location: arch/x86/kernel/fpu/core.c:104
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
**Symbols:**

```
ffffffff81038940-ffffffff810389b9: irq_fpu_usable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool irq_fpu_usable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff810386a6)
Location: arch/x86/kernel/fpu/core.c:88
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
**Symbols:**

```
ffffffff81038360-ffffffff810383a1: irq_fpu_usable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool irq_fpu_usable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103680f)
Location: arch/x86/kernel/fpu/core.c:87
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
**Symbols:**

```
ffffffff81036540-ffffffff81036581: irq_fpu_usable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool irq_fpu_usable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81038bd6)
Location: arch/x86/kernel/fpu/core.c:87
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
**Symbols:**

```
ffffffff81038910-ffffffff81038951: irq_fpu_usable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool irq_fpu_usable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103a39a)
Location: arch/x86/kernel/fpu/core.c:88
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
**Symbols:**

```
ffffffff81039ea0-ffffffff81039ee1: irq_fpu_usable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool irq_fpu_usable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103ba23)
Location: arch/x86/kernel/fpu/core.c:88
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
**Symbols:**

```
ffffffff8103b3c0-ffffffff8103b401: irq_fpu_usable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool irq_fpu_usable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103dd29)
Location: arch/x86/kernel/fpu/core.c:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
**Symbols:**

```
ffffffff8103d990-ffffffff8103d9d1: irq_fpu_usable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool irq_fpu_usable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103e4e9)
Location: arch/x86/kernel/fpu/core.c:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
**Symbols:**

```
ffffffff8103e150-ffffffff8103e191: irq_fpu_usable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool irq_fpu_usable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff810418dc)
Location: arch/x86/kernel/fpu/core.c:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
Direct callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_digest
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_finup
```
**Symbols:**

```
ffffffff810412e0-ffffffff81041321: irq_fpu_usable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool irq_fpu_usable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff810413b0)
Location: arch/x86/kernel/fpu/core.c:77
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_digest
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_finup
```
**Symbols:**

```
ffffffff810413b0-ffffffff810413f3: irq_fpu_usable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool irq_fpu_usable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81042db0)
Location: arch/x86/kernel/fpu/core.c:77
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_digest
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_finup
```
**Symbols:**

```
ffffffff81042db0-ffffffff81042df3: irq_fpu_usable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool irq_fpu_usable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81049120)
Location: arch/x86/kernel/fpu/core.c:77
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_digest
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_finup
```
**Symbols:**

```
ffffffff81049120-ffffffff81049163: irq_fpu_usable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool irq_fpu_usable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81052c80)
Location: arch/x86/kernel/fpu/core.c:58
Inline: True
Direct callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
  - arch/x86/crypto/blake2s-glue.c:blake2s_compress
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_digest
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_finup
```
**Symbols:**

```
ffffffff81052c80-ffffffff81052cd0: irq_fpu_usable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool irq_fpu_usable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81060330)
Location: arch/x86/kernel/fpu/core.c:58
Inline: True
Direct callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
  - arch/x86/crypto/blake2s-glue.c:blake2s_compress
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_digest
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_finup
```
**Symbols:**

```
ffffffff81060330-ffffffff81060380: irq_fpu_usable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool irq_fpu_usable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff810621c6)
Location: arch/x86/kernel/fpu/core.c:58
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
Direct callers:
  - arch/x86/crypto/blake2s-glue.c:blake2s_compress
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_digest
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_finup
```
**Symbols:**

```
ffffffff81061aa0-ffffffff81061af0: irq_fpu_usable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool irq_fpu_usable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81069e45)
Location: arch/x86/kernel/fpu/core.c:58
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_lock_and_load
  - arch/x86/kernel/fpu/core.c:fpregs_lock_and_load
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
Direct callers:
  - arch/x86/crypto/blake2s-glue.c:blake2s_compress
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_digest
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_finup
```
**Symbols:**

```
ffffffff81068bc0-ffffffff81068c10: irq_fpu_usable (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool irq_fpu_usable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103e669)
Location: arch/x86/kernel/fpu/core.c:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
**Symbols:**

```
ffffffff8103e2d0-ffffffff8103e311: irq_fpu_usable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool irq_fpu_usable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8102de69)
Location: arch/x86/kernel/fpu/core.c:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
**Symbols:**

```
ffffffff8102dad0-ffffffff8102db11: irq_fpu_usable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool irq_fpu_usable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103e4a9)
Location: arch/x86/kernel/fpu/core.c:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
**Symbols:**

```
ffffffff8103e110-ffffffff8103e151: irq_fpu_usable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool irq_fpu_usable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103f640)
Location: arch/x86/kernel/fpu/core.c:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
**Symbols:**

```
ffffffff8103f290-ffffffff8103f2d1: irq_fpu_usable (STB_GLOBAL)
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
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
