# Function: <code>madvise_vma_behavior</code>

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
int madvise_vma_behavior(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end, long unsigned int behavior);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81378260)
Location: mm/madvise.c:989
Inline: False
```
**Symbols:**

```
ffffffff81378260-ffffffff813788db: madvise_vma_behavior (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int madvise_vma_behavior(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end, long unsigned int behavior);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff813f5ba0)
Location: mm/madvise.c:1019
Inline: False
```
**Symbols:**

```
ffffffff813f5ba0-ffffffff813f61d2: madvise_vma_behavior (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int madvise_vma_behavior(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end, long unsigned int behavior);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81428940)
Location: mm/madvise.c:1021
Inline: False
```
**Symbols:**

```
ffffffff81428940-ffffffff81428fc9: madvise_vma_behavior (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int madvise_vma_behavior(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end, long unsigned int behavior);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81462170)
Location: mm/madvise.c:1015
Inline: False
```
**Symbols:**

```
ffffffff81462170-ffffffff814627f9: madvise_vma_behavior (STB_LOCAL)
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
