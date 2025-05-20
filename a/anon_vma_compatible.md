# Function: <code>anon_vma_compatible</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811c4065)
Location: mm/mmap.c:1133
Inline: True
Inline callers:
  - mm/mmap.c:reusable_anon_vma
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811dff25)
Location: mm/mmap.c:1035
Inline: True
Inline callers:
  - mm/mmap.c:reusable_anon_vma
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811efe75)
Location: mm/mmap.c:1188
Inline: True
Inline callers:
  - mm/mmap.c:reusable_anon_vma
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int anon_vma_compatible(struct vm_area_struct *a, struct vm_area_struct *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811fae20)
Location: mm/mmap.c:1204
Inline: False
Direct callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
```
**Symbols:**

```
ffffffff811fae20-ffffffff811faea5: anon_vma_compatible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int anon_vma_compatible(struct vm_area_struct *a, struct vm_area_struct *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81213340)
Location: mm/mmap.c:1205
Inline: False
Direct callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
```
**Symbols:**

```
ffffffff81213340-ffffffff812133c5: anon_vma_compatible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int anon_vma_compatible(struct vm_area_struct *a, struct vm_area_struct *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812342e0)
Location: mm/mmap.c:1214
Inline: False
Direct callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
```
**Symbols:**

```
ffffffff812342e0-ffffffff81234365: anon_vma_compatible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int anon_vma_compatible(struct vm_area_struct *a, struct vm_area_struct *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81247a90)
Location: mm/mmap.c:1238
Inline: False
Direct callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
```
**Symbols:**

```
ffffffff81247a90-ffffffff81247b15: anon_vma_compatible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int anon_vma_compatible(struct vm_area_struct *a, struct vm_area_struct *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81259be0)
Location: mm/mmap.c:1240
Inline: False
Direct callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
```
**Symbols:**

```
ffffffff81259be0-ffffffff81259c65: anon_vma_compatible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int anon_vma_compatible(struct vm_area_struct *a, struct vm_area_struct *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81268090)
Location: mm/mmap.c:1241
Inline: False
Direct callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
```
**Symbols:**

```
ffffffff81268090-ffffffff81268115: anon_vma_compatible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int anon_vma_compatible(struct vm_area_struct *a, struct vm_area_struct *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81298740)
Location: mm/mmap.c:1222
Inline: False
Direct callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
```
**Symbols:**

```
ffffffff81298740-ffffffff812987c5: anon_vma_compatible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int anon_vma_compatible(struct vm_area_struct *a, struct vm_area_struct *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a38c0)
Location: mm/mmap.c:1260
Inline: False
Direct callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
```
**Symbols:**

```
ffffffff812a38c0-ffffffff812a3945: anon_vma_compatible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int anon_vma_compatible(struct vm_area_struct *a, struct vm_area_struct *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a90f0)
Location: mm/mmap.c:1264
Inline: False
Direct callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
```
**Symbols:**

```
ffffffff812a90f0-ffffffff812a9175: anon_vma_compatible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int anon_vma_compatible(struct vm_area_struct *a, struct vm_area_struct *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812ea750)
Location: mm/mmap.c:1261
Inline: False
Direct callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
```
**Symbols:**

```
ffffffff812ea750-ffffffff812ea7d5: anon_vma_compatible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int anon_vma_compatible(struct vm_area_struct *a, struct vm_area_struct *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8134d3c0)
Location: mm/mmap.c:1273
Inline: False
Direct callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
```
**Symbols:**

```
ffffffff8134d3c0-ffffffff8134d455: anon_vma_compatible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int anon_vma_compatible(struct vm_area_struct *a, struct vm_area_struct *b);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813c862c)
Location: mm/mmap.c:1090
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
Direct callers:
  - mm/mmap.c:find_mergeable_anon_vma
```
**Symbols:**

```
ffffffff813c6880-ffffffff813c6909: anon_vma_compatible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int anon_vma_compatible(struct vm_area_struct *a, struct vm_area_struct *b);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813fc810)
Location: mm/mmap.c:1039
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
Direct callers:
  - mm/mmap.c:find_mergeable_anon_vma
```
**Symbols:**

```
ffffffff813faae0-ffffffff813fab75: anon_vma_compatible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int anon_vma_compatible(struct vm_area_struct *a, struct vm_area_struct *b);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff814291e7)
Location: mm/mmap.c:1067
Inline: True
Inline callers:
  - mm/mmap.c:find_mergeable_anon_vma
Direct callers:
  - mm/mmap.c:find_mergeable_anon_vma
```
**Symbols:**

```
ffffffff814268a0-ffffffff81426935: anon_vma_compatible (STB_LOCAL)
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
int anon_vma_compatible(struct vm_area_struct *a, struct vm_area_struct *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffff8000102ff320)
Location: mm/mmap.c:1241
Inline: False
Direct callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
```
**Symbols:**

```
ffff8000102ff320-ffff8000102ff3c0: anon_vma_compatible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c051e50c)
Location: mm/mmap.c:1241
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int anon_vma_compatible(struct vm_area_struct *a, struct vm_area_struct *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0000000003caf40)
Location: mm/mmap.c:1241
Inline: False
Direct callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
```
**Symbols:**

```
c0000000003caf40-c0000000003cb020: anon_vma_compatible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffe00020d6ae)
Location: mm/mmap.c:1241
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
int anon_vma_compatible(struct vm_area_struct *a, struct vm_area_struct *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812606e0)
Location: mm/mmap.c:1241
Inline: False
Direct callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
```
**Symbols:**

```
ffffffff812606e0-ffffffff81260765: anon_vma_compatible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int anon_vma_compatible(struct vm_area_struct *a, struct vm_area_struct *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81252b00)
Location: mm/mmap.c:1241
Inline: False
Direct callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
```
**Symbols:**

```
ffffffff81252b00-ffffffff81252b85: anon_vma_compatible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int anon_vma_compatible(struct vm_area_struct *a, struct vm_area_struct *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125e480)
Location: mm/mmap.c:1241
Inline: False
Direct callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
```
**Symbols:**

```
ffffffff8125e480-ffffffff8125e505: anon_vma_compatible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int anon_vma_compatible(struct vm_area_struct *a, struct vm_area_struct *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8126ded0)
Location: mm/mmap.c:1241
Inline: False
Direct callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:find_mergeable_anon_vma
```
**Symbols:**

```
ffffffff8126ded0-ffffffff8126df55: anon_vma_compatible (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
