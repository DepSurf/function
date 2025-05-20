# Function: <code>map_vdso</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int map_vdso(const struct vdso_image *image, bool calculate_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81003f60)
Location: arch/x86/entry/vdso/vma.c:93
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
```
**Symbols:**

```
ffffffff81003f60-ffffffff81004193: map_vdso (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int map_vdso(const struct vdso_image *image, bool calculate_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81003ef0)
Location: arch/x86/entry/vdso/vma.c:179
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
```
**Symbols:**

```
ffffffff81003ef0-ffffffff810040ab: map_vdso (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int map_vdso(const struct vdso_image *image, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004050)
Location: arch/x86/entry/vdso/vma.c:146
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
```
**Symbols:**

```
ffffffff81004050-ffffffff8100416d: map_vdso (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int map_vdso(const struct vdso_image *image, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81003f10)
Location: arch/x86/entry/vdso/vma.c:151
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
```
**Symbols:**

```
ffffffff81003f10-ffffffff81004034: map_vdso (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int map_vdso(const struct vdso_image *image, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004170)
Location: arch/x86/entry/vdso/vma.c:152
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
```
**Symbols:**

```
ffffffff81004170-ffffffff81004294: map_vdso (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int map_vdso(const struct vdso_image *image, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004910)
Location: arch/x86/entry/vdso/vma.c:152
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
```
**Symbols:**

```
ffffffff81004910-ffffffff81004a2c: map_vdso (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int map_vdso(const struct vdso_image *image, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004870)
Location: arch/x86/entry/vdso/vma.c:146
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
```
**Symbols:**

```
ffffffff81004870-ffffffff8100498c: map_vdso (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int map_vdso(const struct vdso_image *image, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004ad0)
Location: arch/x86/entry/vdso/vma.c:146
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
```
**Symbols:**

```
ffffffff81004ad0-ffffffff81004bf3: map_vdso (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int map_vdso(const struct vdso_image *image, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004b50)
Location: arch/x86/entry/vdso/vma.c:146
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
```
**Symbols:**

```
ffffffff81004b50-ffffffff81004c73: map_vdso (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int map_vdso(const struct vdso_image *image, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff810057b0)
Location: arch/x86/entry/vdso/vma.c:264
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:map_vdso_once
```
**Symbols:**

```
ffffffff810057b0-ffffffff810058d3: map_vdso (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int map_vdso(const struct vdso_image *image, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff810047d0)
Location: arch/x86/entry/vdso/vma.c:246
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:map_vdso_once
```
**Symbols:**

```
ffffffff810047d0-ffffffff8100494a: map_vdso (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int map_vdso(const struct vdso_image *image, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004710)
Location: arch/x86/entry/vdso/vma.c:246
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
```
**Symbols:**

```
ffffffff81004710-ffffffff81004887: map_vdso (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int map_vdso(const struct vdso_image *image, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004d40)
Location: arch/x86/entry/vdso/vma.c:246
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
```
**Symbols:**

```
ffffffff81004d40-ffffffff81004eb4: map_vdso (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int map_vdso(const struct vdso_image *image, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81003e20)
Location: arch/x86/entry/vdso/vma.c:246
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:map_vdso_once
```
**Symbols:**

```
ffffffff81003e20-ffffffff81003fac: map_vdso (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int map_vdso(const struct vdso_image *image, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004900)
Location: arch/x86/entry/vdso/vma.c:222
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:map_vdso_once
```
**Symbols:**

```
ffffffff81004900-ffffffff81004a8c: map_vdso (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int map_vdso(const struct vdso_image *image, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff810040c0)
Location: arch/x86/entry/vdso/vma.c:223
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:map_vdso_once
```
**Symbols:**

```
ffffffff810040c0-ffffffff81004266: map_vdso (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int map_vdso(const struct vdso_image *image, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff810069d0)
Location: arch/x86/entry/vdso/vma.c:223
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:map_vdso_once
```
**Symbols:**

```
ffffffff810069d0-ffffffff81006b76: map_vdso (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int map_vdso(const struct vdso_image *image, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004b50)
Location: arch/x86/entry/vdso/vma.c:146
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
```
**Symbols:**

```
ffffffff81004b50-ffffffff81004c73: map_vdso (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int map_vdso(const struct vdso_image *image, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81003230)
Location: arch/x86/entry/vdso/vma.c:146
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
```
**Symbols:**

```
ffffffff81003230-ffffffff81003353: map_vdso (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int map_vdso(const struct vdso_image *image, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004b10)
Location: arch/x86/entry/vdso/vma.c:146
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
```
**Symbols:**

```
ffffffff81004b10-ffffffff81004c33: map_vdso (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int map_vdso(const struct vdso_image *image, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004c50)
Location: arch/x86/entry/vdso/vma.c:146
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
```
**Symbols:**

```
ffffffff81004c50-ffffffff81004d73: map_vdso (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int addr</code>
</li>
<li>
<b>Param removed. </b>
<code>bool calculate_addr</code>
</li>
</ul>
</details>
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
