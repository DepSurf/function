# Function: <code>kexec_image_post_load_cleanup_default</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81138c6c)
Location: kernel/kexec_file.c:81
Inline: True
Inline callers:
  - kernel/kexec_file.c:arch_kimage_file_post_load_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int kexec_image_post_load_cleanup_default(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81144595)
Location: kernel/kexec_file.c:80
Inline: True
Inline callers:
  - kernel/kexec_file.c:arch_kimage_file_post_load_cleanup
```
**Symbols:**

```
ffffffff81144560-ffffffff8114458f: kexec_image_post_load_cleanup_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int kexec_image_post_load_cleanup_default(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8114f925)
Location: kernel/kexec_file.c:78
Inline: True
Inline callers:
  - kernel/kexec_file.c:arch_kimage_file_post_load_cleanup
```
**Symbols:**

```
ffffffff8114f8f0-ffffffff8114f91f: kexec_image_post_load_cleanup_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int kexec_image_post_load_cleanup_default(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8115b605)
Location: kernel/kexec_file.c:78
Inline: True
Inline callers:
  - kernel/kexec_file.c:arch_kimage_file_post_load_cleanup
```
**Symbols:**

```
ffffffff8115b5d0-ffffffff8115b5ff: kexec_image_post_load_cleanup_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int kexec_image_post_load_cleanup_default(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8116c5f5)
Location: kernel/kexec_file.c:78
Inline: True
Inline callers:
  - kernel/kexec_file.c:arch_kimage_file_post_load_cleanup
```
**Symbols:**

```
ffffffff8116c5c0-ffffffff8116c5ef: kexec_image_post_load_cleanup_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int kexec_image_post_load_cleanup_default(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81168c35)
Location: kernel/kexec_file.c:79
Inline: True
Inline callers:
  - kernel/kexec_file.c:arch_kimage_file_post_load_cleanup
```
**Symbols:**

```
ffffffff81168c00-ffffffff81168c2f: kexec_image_post_load_cleanup_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int kexec_image_post_load_cleanup_default(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff811699e5)
Location: kernel/kexec_file.c:79
Inline: True
Inline callers:
  - kernel/kexec_file.c:arch_kimage_file_post_load_cleanup
```
**Symbols:**

```
ffffffff811699b0-ffffffff811699df: kexec_image_post_load_cleanup_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int kexec_image_post_load_cleanup_default(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8118f585)
Location: kernel/kexec_file.c:79
Inline: True
Inline callers:
  - kernel/kexec_file.c:arch_kimage_file_post_load_cleanup
```
**Symbols:**

```
ffffffff8118f550-ffffffff8118f57f: kexec_image_post_load_cleanup_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kexec_image_post_load_cleanup_default(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff811bec80)
Location: kernel/kexec_file.c:76
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_kimage_file_post_load_cleanup
```
**Symbols:**

```
ffffffff811bec80-ffffffff811becbb: kexec_image_post_load_cleanup_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kexec_image_post_load_cleanup_default(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81200e20)
Location: kernel/kexec_file.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_kimage_file_post_load_cleanup
```
**Symbols:**

```
ffffffff81200e20-ffffffff81200e5b: kexec_image_post_load_cleanup_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kexec_image_post_load_cleanup_default(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff812161a0)
Location: kernel/kexec_file.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_kimage_file_post_load_cleanup
```
**Symbols:**

```
ffffffff812161a0-ffffffff812161db: kexec_image_post_load_cleanup_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kexec_image_post_load_cleanup_default(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8122e140)
Location: kernel/kexec_file.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_kimage_file_post_load_cleanup
```
**Symbols:**

```
ffffffff8122e140-ffffffff8122e17b: kexec_image_post_load_cleanup_default (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int kexec_image_post_load_cleanup_default(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffff8000101cac20)
Location: kernel/kexec_file.c:78
Inline: True
Inline callers:
  - kernel/kexec_file.c:arch_kimage_file_post_load_cleanup
Direct callers:
  - arch/arm64/kernel/machine_kexec_file.c:arch_kimage_file_post_load_cleanup
```
**Symbols:**

```
ffff8000101cabb8-ffff8000101cac04: kexec_image_post_load_cleanup_default (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int kexec_image_post_load_cleanup_default(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (c000000000233e40)
Location: kernel/kexec_file.c:78
Inline: True
Inline callers:
  - kernel/kexec_file.c:arch_kimage_file_post_load_cleanup
```
**Symbols:**

```
c000000000233dc0-c000000000233e28: kexec_image_post_load_cleanup_default (STB_GLOBAL)
```
</details>
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
int kexec_image_post_load_cleanup_default(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81153c25)
Location: kernel/kexec_file.c:78
Inline: True
Inline callers:
  - kernel/kexec_file.c:arch_kimage_file_post_load_cleanup
```
**Symbols:**

```
ffffffff81153bf0-ffffffff81153c1f: kexec_image_post_load_cleanup_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int kexec_image_post_load_cleanup_default(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81146f45)
Location: kernel/kexec_file.c:78
Inline: True
Inline callers:
  - kernel/kexec_file.c:arch_kimage_file_post_load_cleanup
```
**Symbols:**

```
ffffffff81146f10-ffffffff81146f3f: kexec_image_post_load_cleanup_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int kexec_image_post_load_cleanup_default(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81151ad5)
Location: kernel/kexec_file.c:78
Inline: True
Inline callers:
  - kernel/kexec_file.c:arch_kimage_file_post_load_cleanup
```
**Symbols:**

```
ffffffff81151aa0-ffffffff81151acf: kexec_image_post_load_cleanup_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int kexec_image_post_load_cleanup_default(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8115e8f5)
Location: kernel/kexec_file.c:78
Inline: True
Inline callers:
  - kernel/kexec_file.c:arch_kimage_file_post_load_cleanup
```
**Symbols:**

```
ffffffff8115e8c0-ffffffff8115e8ef: kexec_image_post_load_cleanup_default (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
