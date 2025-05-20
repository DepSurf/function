# Function: <code>vma_dup_policy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vma_dup_policy(struct vm_area_struct *src, struct vm_area_struct *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811e23f0)
Location: mm/mempolicy.c:2066
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - mm/mmap.c:copy_vma
```
**Symbols:**

```
ffffffff811e23f0-ffffffff811e2425: vma_dup_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vma_dup_policy(struct vm_area_struct *src, struct vm_area_struct *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81200de0)
Location: mm/mempolicy.c:2083
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
```
**Symbols:**

```
ffffffff81200de0-ffffffff81200e15: vma_dup_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vma_dup_policy(struct vm_area_struct *src, struct vm_area_struct *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812127f0)
Location: mm/mempolicy.c:2077
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
```
**Symbols:**

```
ffffffff812127f0-ffffffff81212825: vma_dup_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vma_dup_policy(struct vm_area_struct *src, struct vm_area_struct *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8121db00)
Location: mm/mempolicy.c:1982
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff8121db00-ffffffff8121db35: vma_dup_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vma_dup_policy(struct vm_area_struct *src, struct vm_area_struct *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81238d50)
Location: mm/mempolicy.c:2044
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
```
**Symbols:**

```
ffffffff81238d50-ffffffff81238d85: vma_dup_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vma_dup_policy(struct vm_area_struct *src, struct vm_area_struct *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8125c270)
Location: mm/mempolicy.c:2101
Inline: False
Direct callers:
  - kernel/fork.c:copy_mm
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff8125c270-ffffffff8125c2a8: vma_dup_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vma_dup_policy(struct vm_area_struct *src, struct vm_area_struct *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81270b40)
Location: mm/mempolicy.c:2140
Inline: False
Direct callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff81270b40-ffffffff81270b78: vma_dup_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vma_dup_policy(struct vm_area_struct *src, struct vm_area_struct *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8128c150)
Location: mm/mempolicy.c:2161
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff8128c150-ffffffff8128c185: vma_dup_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vma_dup_policy(struct vm_area_struct *src, struct vm_area_struct *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8129bd20)
Location: mm/mempolicy.c:2200
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff8129bd20-ffffffff8129bd55: vma_dup_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vma_dup_policy(struct vm_area_struct *src, struct vm_area_struct *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812cfa10)
Location: mm/mempolicy.c:2300
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff812cfa10-ffffffff812cfa48: vma_dup_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vma_dup_policy(struct vm_area_struct *src, struct vm_area_struct *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812db4e0)
Location: mm/mempolicy.c:2275
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff812db4e0-ffffffff812db518: vma_dup_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vma_dup_policy(struct vm_area_struct *src, struct vm_area_struct *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812e2c60)
Location: mm/mempolicy.c:2280
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff812e2c60-ffffffff812e2c98: vma_dup_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vma_dup_policy(struct vm_area_struct *src, struct vm_area_struct *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81329fe0)
Location: mm/mempolicy.c:2198
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff81329fe0-ffffffff8132a018: vma_dup_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vma_dup_policy(struct vm_area_struct *src, struct vm_area_struct *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff813996b0)
Location: mm/mempolicy.c:2372
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff813996b0-ffffffff813996f0: vma_dup_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vma_dup_policy(struct vm_area_struct *src, struct vm_area_struct *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81419520)
Location: mm/mempolicy.c:2387
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff81419520-ffffffff81419560: vma_dup_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vma_dup_policy(struct vm_area_struct *src, struct vm_area_struct *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8144cb20)
Location: mm/mempolicy.c:2398
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff8144cb20-ffffffff8144cb60: vma_dup_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vma_dup_policy(struct vm_area_struct *src, struct vm_area_struct *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81486380)
Location: mm/mempolicy.c:2300
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff81486380-ffffffff814863c0: vma_dup_policy (STB_GLOBAL)
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
int vma_dup_policy(struct vm_area_struct *src, struct vm_area_struct *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffff80001033acf8)
Location: mm/mempolicy.c:2200
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffff80001033acf8-ffff80001033ad44: vma_dup_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (0)
Location: include/linux/mempolicy.h:249
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/mempolicy.h:249
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vma_dup_policy(struct vm_area_struct *src, struct vm_area_struct *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (c000000000415780)
Location: mm/mempolicy.c:2200
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
c000000000415780-c000000000415808: vma_dup_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (0)
Location: include/linux/mempolicy.h:249
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/mempolicy.h:249
Inline: True
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
int vma_dup_policy(struct vm_area_struct *src, struct vm_area_struct *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81294300)
Location: mm/mempolicy.c:2200
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff81294300-ffffffff81294335: vma_dup_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vma_dup_policy(struct vm_area_struct *src, struct vm_area_struct *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81285f10)
Location: mm/mempolicy.c:2200
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff81285f10-ffffffff81285f45: vma_dup_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vma_dup_policy(struct vm_area_struct *src, struct vm_area_struct *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81292110)
Location: mm/mempolicy.c:2200
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff81292110-ffffffff81292145: vma_dup_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vma_dup_policy(struct vm_area_struct *src, struct vm_area_struct *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812a1f10)
Location: mm/mempolicy.c:2200
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__split_vma
```
**Symbols:**

```
ffffffff812a1f10-ffffffff812a1f45: vma_dup_policy (STB_GLOBAL)
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
