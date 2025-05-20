# Function: <code>vm_area_dup</code>

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
struct vm_area_struct *vm_area_dup(struct vm_area_struct *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108b640)
Location: kernel/fork.c:325
Inline: False
Direct callers:
  - kernel/fork.c:copy_mm
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff8108b640-ffffffff8108b683: vm_area_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct vm_area_struct *vm_area_dup(struct vm_area_struct *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81093540)
Location: kernel/fork.c:344
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff81093540-ffffffff81093583: vm_area_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct vm_area_struct *vm_area_dup(struct vm_area_struct *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097650)
Location: kernel/fork.c:350
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff81097650-ffffffff81097693: vm_area_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct vm_area_struct *vm_area_dup(struct vm_area_struct *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109dd10)
Location: kernel/fork.c:359
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff8109dd10-ffffffff8109dd53: vm_area_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct vm_area_struct *vm_area_dup(struct vm_area_struct *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a5320)
Location: kernel/fork.c:362
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff810a5320-ffffffff810a5376: vm_area_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct vm_area_struct *vm_area_dup(struct vm_area_struct *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a0a40)
Location: kernel/fork.c:359
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff810a0a40-ffffffff810a0adf: vm_area_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct vm_area_struct *vm_area_dup(struct vm_area_struct *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a17d0)
Location: kernel/fork.c:360
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff810a17d0-ffffffff810a186f: vm_area_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct vm_area_struct *vm_area_dup(struct vm_area_struct *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b2c00)
Location: kernel/fork.c:360
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff810b2c00-ffffffff810b2c9f: vm_area_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct vm_area_struct *vm_area_dup(struct vm_area_struct *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810c8e10)
Location: kernel/fork.c:470
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff810c8e10-ffffffff810c8f3f: vm_area_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct vm_area_struct *vm_area_dup(struct vm_area_struct *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e62d0)
Location: kernel/fork.c:469
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff810e62d0-ffffffff810e63ef: vm_area_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct vm_area_struct *vm_area_dup(struct vm_area_struct *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f1ba0)
Location: kernel/fork.c:503
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff810f1ba0-ffffffff810f1cdd: vm_area_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct vm_area_struct *vm_area_dup(struct vm_area_struct *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810faf30)
Location: kernel/fork.c:483
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff810faf30-ffffffff810fb06d: vm_area_dup (STB_GLOBAL)
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
struct vm_area_struct *vm_area_dup(struct vm_area_struct *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f2938)
Location: kernel/fork.c:359
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffff8000100f2938-ffff8000100f2990: vm_area_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct vm_area_struct *vm_area_dup(struct vm_area_struct *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0351200)
Location: kernel/fork.c:359
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
c0351200-c0351254: vm_area_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct vm_area_struct *vm_area_dup(struct vm_area_struct *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0000000001384e0)
Location: kernel/fork.c:359
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
c0000000001384e0-c00000000013855c: vm_area_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct vm_area_struct *vm_area_dup(struct vm_area_struct *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000bf560)
Location: kernel/fork.c:359
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffe0000bf560-ffffffe0000bf5d0: vm_area_dup (STB_GLOBAL)
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
struct vm_area_struct *vm_area_dup(struct vm_area_struct *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097630)
Location: kernel/fork.c:359
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff81097630-ffffffff81097673: vm_area_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct vm_area_struct *vm_area_dup(struct vm_area_struct *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810860b0)
Location: kernel/fork.c:359
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff810860b0-ffffffff810860f3: vm_area_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct vm_area_struct *vm_area_dup(struct vm_area_struct *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810975e0)
Location: kernel/fork.c:359
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff810975e0-ffffffff81097623: vm_area_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct vm_area_struct *vm_area_dup(struct vm_area_struct *orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109f1e0)
Location: kernel/fork.c:359
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff8109f1e0-ffffffff8109f223: vm_area_dup (STB_GLOBAL)
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
