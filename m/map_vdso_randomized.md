# Function: <code>map_vdso_randomized</code>

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
int map_vdso_randomized(const struct vdso_image *image);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004170)
Location: arch/x86/entry/vdso/vma.c:245
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
```
**Symbols:**

```
ffffffff81004170-ffffffff8100420b: map_vdso_randomized (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int map_vdso_randomized(const struct vdso_image *image);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004040)
Location: arch/x86/entry/vdso/vma.c:250
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
```
**Symbols:**

```
ffffffff81004040-ffffffff810040e7: map_vdso_randomized (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int map_vdso_randomized(const struct vdso_image *image);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff810042a0)
Location: arch/x86/entry/vdso/vma.c:251
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
```
**Symbols:**

```
ffffffff810042a0-ffffffff81004347: map_vdso_randomized (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int map_vdso_randomized(const struct vdso_image *image);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004a30)
Location: arch/x86/entry/vdso/vma.c:251
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
```
**Symbols:**

```
ffffffff81004a30-ffffffff81004acd: map_vdso_randomized (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int map_vdso_randomized(const struct vdso_image *image);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004990)
Location: arch/x86/entry/vdso/vma.c:245
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
```
**Symbols:**

```
ffffffff81004990-ffffffff81004a2d: map_vdso_randomized (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int map_vdso_randomized(const struct vdso_image *image);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004c00)
Location: arch/x86/entry/vdso/vma.c:245
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
```
**Symbols:**

```
ffffffff81004c00-ffffffff81004c9d: map_vdso_randomized (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int map_vdso_randomized(const struct vdso_image *image);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004c80)
Location: arch/x86/entry/vdso/vma.c:245
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
```
**Symbols:**

```
ffffffff81004c80-ffffffff81004d1d: map_vdso_randomized (STB_LOCAL)
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
In arch/x86/entry/vdso/vma.c (ffffffff81005dad)
Location: arch/x86/entry/vdso/vma.c:363
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
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
In arch/x86/entry/vdso/vma.c (ffffffff81004dfb)
Location: arch/x86/entry/vdso/vma.c:345
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int map_vdso_randomized(const struct vdso_image *image);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004890)
Location: arch/x86/entry/vdso/vma.c:345
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
```
**Symbols:**

```
ffffffff81004890-ffffffff81004938: map_vdso_randomized (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int map_vdso_randomized(const struct vdso_image *image);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004ec0)
Location: arch/x86/entry/vdso/vma.c:345
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
```
**Symbols:**

```
ffffffff81004ec0-ffffffff81004f68: map_vdso_randomized (STB_LOCAL)
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
In arch/x86/entry/vdso/vma.c (ffffffff8100440e)
Location: arch/x86/entry/vdso/vma.c:345
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
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
In arch/x86/entry/vdso/vma.c (ffffffff81004d6c)
Location: arch/x86/entry/vdso/vma.c:321
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
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
In arch/x86/entry/vdso/vma.c (ffffffff8100457c)
Location: arch/x86/entry/vdso/vma.c:322
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
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
In arch/x86/entry/vdso/vma.c (ffffffff81006e8c)
Location: arch/x86/entry/vdso/vma.c:322
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
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
int map_vdso_randomized(const struct vdso_image *image);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004c80)
Location: arch/x86/entry/vdso/vma.c:245
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
```
**Symbols:**

```
ffffffff81004c80-ffffffff81004d1d: map_vdso_randomized (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int map_vdso_randomized(const struct vdso_image *image);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81003360)
Location: arch/x86/entry/vdso/vma.c:245
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
```
**Symbols:**

```
ffffffff81003360-ffffffff810033fd: map_vdso_randomized (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int map_vdso_randomized(const struct vdso_image *image);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004c40)
Location: arch/x86/entry/vdso/vma.c:245
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
```
**Symbols:**

```
ffffffff81004c40-ffffffff81004cdd: map_vdso_randomized (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int map_vdso_randomized(const struct vdso_image *image);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004d80)
Location: arch/x86/entry/vdso/vma.c:245
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
```
**Symbols:**

```
ffffffff81004d80-ffffffff81004e1d: map_vdso_randomized (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
