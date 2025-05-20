# Function: <code>madvise_update_vma</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int madvise_update_vma(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end, long unsigned int new_flags, struct anon_vma_name *anon_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81377f80)
Location: mm/madvise.c:139
Inline: False
Direct callers:
  - mm/madvise.c:madvise_vma_anon_name
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
**Symbols:**

```
ffffffff81377f80-ffffffff813781ed: madvise_update_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int madvise_update_vma(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end, long unsigned int new_flags, struct anon_vma_name *anon_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff813f5890)
Location: mm/madvise.c:137
Inline: False
Direct callers:
  - mm/madvise.c:madvise_vma_anon_name
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
**Symbols:**

```
ffffffff813f5890-ffffffff813f5af5: madvise_update_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int madvise_update_vma(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end, long unsigned int new_flags, struct anon_vma_name *anon_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff814285e0)
Location: mm/madvise.c:137
Inline: False
Direct callers:
  - mm/madvise.c:madvise_vma_anon_name
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
**Symbols:**

```
ffffffff814285e0-ffffffff814288a0: madvise_update_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int madvise_update_vma(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end, long unsigned int new_flags, struct anon_vma_name *anon_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81461e90)
Location: mm/madvise.c:137
Inline: False
Direct callers:
  - mm/madvise.c:madvise_vma_anon_name
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
**Symbols:**

```
ffffffff81461e90-ffffffff814620c3: madvise_update_vma (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
