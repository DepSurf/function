# Function: <code>madvise_walk_vmas</code>

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
int madvise_walk_vmas(struct mm_struct *mm, long unsigned int start, long unsigned int end, long unsigned int arg, int (*visit)(struct vm_area_struct *, struct vm_area_struct **, long unsigned int, long unsigned int, long unsigned int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff813752f0)
Location: mm/madvise.c:1191
Inline: False
Direct callers:
  - mm/madvise.c:do_madvise
  - mm/madvise.c:do_madvise
  - mm/madvise.c:madvise_set_anon_name
```
**Symbols:**

```
ffffffff813752f0-ffffffff8137541a: madvise_walk_vmas (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int madvise_walk_vmas(struct mm_struct *mm, long unsigned int start, long unsigned int end, long unsigned int arg, int (*visit)(struct vm_area_struct *, struct vm_area_struct **, long unsigned int, long unsigned int, long unsigned int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff813f2d30)
Location: mm/madvise.c:1224
Inline: False
Direct callers:
  - mm/madvise.c:do_madvise
  - mm/madvise.c:do_madvise
  - mm/madvise.c:madvise_set_anon_name
```
**Symbols:**

```
ffffffff813f2d30-ffffffff813f2e64: madvise_walk_vmas (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int madvise_walk_vmas(struct mm_struct *mm, long unsigned int start, long unsigned int end, long unsigned int arg, int (*visit)(struct vm_area_struct *, struct vm_area_struct **, long unsigned int, long unsigned int, long unsigned int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81426770)
Location: mm/madvise.c:1226
Inline: False
Direct callers:
  - mm/madvise.c:do_madvise
  - mm/madvise.c:do_madvise
  - mm/madvise.c:madvise_set_anon_name
```
**Symbols:**

```
ffffffff81426770-ffffffff814268a4: madvise_walk_vmas (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int madvise_walk_vmas(struct mm_struct *mm, long unsigned int start, long unsigned int end, long unsigned int arg, int (*visit)(struct vm_area_struct *, struct vm_area_struct **, long unsigned int, long unsigned int, long unsigned int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff8145ff20)
Location: mm/madvise.c:1220
Inline: False
Direct callers:
  - mm/madvise.c:do_madvise
  - mm/madvise.c:do_madvise
  - mm/madvise.c:madvise_set_anon_name
```
**Symbols:**

```
ffffffff8145ff20-ffffffff81460054: madvise_walk_vmas (STB_LOCAL)
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
