# Function: <code>kexec_image_load_default</code>

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
In kernel/kexec_file.c (ffffffff81138c05)
Location: kernel/kexec_file.c:65
Inline: True
Inline callers:
  - kernel/kexec_file.c:arch_kexec_kernel_image_load
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81144505)
Location: kernel/kexec_file.c:64
Inline: True
Inline callers:
  - kernel/kexec_file.c:arch_kexec_kernel_image_load
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8114f895)
Location: kernel/kexec_file.c:62
Inline: True
Inline callers:
  - kernel/kexec_file.c:arch_kexec_kernel_image_load
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8115b575)
Location: kernel/kexec_file.c:62
Inline: True
Inline callers:
  - kernel/kexec_file.c:arch_kexec_kernel_image_load
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
In kernel/kexec_file.c (ffffffff8116c565)
Location: kernel/kexec_file.c:62
Inline: True
Inline callers:
  - kernel/kexec_file.c:arch_kexec_kernel_image_load
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
In kernel/kexec_file.c (ffffffff81168ba5)
Location: kernel/kexec_file.c:63
Inline: True
Inline callers:
  - kernel/kexec_file.c:arch_kexec_kernel_image_load
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
In kernel/kexec_file.c (ffffffff81169955)
Location: kernel/kexec_file.c:63
Inline: True
Inline callers:
  - kernel/kexec_file.c:arch_kexec_kernel_image_load
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
In kernel/kexec_file.c (ffffffff8118f4f5)
Location: kernel/kexec_file.c:63
Inline: True
Inline callers:
  - kernel/kexec_file.c:arch_kexec_kernel_image_load
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *kexec_image_load_default(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff811bec00)
Location: kernel/kexec_file.c:65
Inline: False
```
**Symbols:**

```
ffffffff811bec00-ffffffff811bec7b: kexec_image_load_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *kexec_image_load_default(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81200d90)
Location: kernel/kexec_file.c:68
Inline: False
```
**Symbols:**

```
ffffffff81200d90-ffffffff81200e0b: kexec_image_load_default (STB_GLOBAL)
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
In kernel/kexec_file.c (ffffffff812165c1)
Location: kernel/kexec_file.c:68
Inline: True
Inline callers:
  - kernel/kexec_file.c:kimage_file_alloc_init
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
In kernel/kexec_file.c (ffffffff8122e3e5)
Location: kernel/kexec_file.c:68
Inline: True
Inline callers:
  - kernel/kexec_file.c:kimage_file_prepare_segments
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffff8000101cab70)
Location: kernel/kexec_file.c:62
Inline: True
Inline callers:
  - kernel/kexec_file.c:arch_kexec_kernel_image_load
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (c000000000233d50)
Location: kernel/kexec_file.c:62
Inline: True
Inline callers:
  - kernel/kexec_file.c:arch_kexec_kernel_image_load
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81153b95)
Location: kernel/kexec_file.c:62
Inline: True
Inline callers:
  - kernel/kexec_file.c:arch_kexec_kernel_image_load
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81146eb5)
Location: kernel/kexec_file.c:62
Inline: True
Inline callers:
  - kernel/kexec_file.c:arch_kexec_kernel_image_load
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81151a45)
Location: kernel/kexec_file.c:62
Inline: True
Inline callers:
  - kernel/kexec_file.c:arch_kexec_kernel_image_load
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8115e865)
Location: kernel/kexec_file.c:62
Inline: True
Inline callers:
  - kernel/kexec_file.c:arch_kexec_kernel_image_load
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
