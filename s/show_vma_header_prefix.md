# Function: <code>show_vma_header_prefix</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff812ea578)
Location: fs/proc/task_mmu.c:279
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void show_vma_header_prefix(struct seq_file *m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81316d60)
Location: fs/proc/task_mmu.c:276
Inline: False
```
**Symbols:**

```
ffffffff81316d60-ffffffff81316ea2: show_vma_header_prefix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void show_vma_header_prefix(struct seq_file *m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8132deb0)
Location: fs/proc/task_mmu.c:275
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_map_vma
```
**Symbols:**

```
ffffffff8132deb0-ffffffff8132dff2: show_vma_header_prefix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void show_vma_header_prefix(struct seq_file *m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81355c50)
Location: fs/proc/task_mmu.c:279
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_map_vma
```
**Symbols:**

```
ffffffff81355c50-ffffffff81355d91: show_vma_header_prefix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void show_vma_header_prefix(struct seq_file *m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8136dfb0)
Location: fs/proc/task_mmu.c:279
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_map_vma
```
**Symbols:**

```
ffffffff8136dfb0-ffffffff8136e0f1: show_vma_header_prefix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void show_vma_header_prefix(struct seq_file *m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813b5b30)
Location: fs/proc/task_mmu.c:250
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_map_vma
```
**Symbols:**

```
ffffffff813b5b30-ffffffff813b5c71: show_vma_header_prefix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void show_vma_header_prefix(struct seq_file *m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813c7320)
Location: fs/proc/task_mmu.c:250
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_map_vma
```
**Symbols:**

```
ffffffff813c7320-ffffffff813c7461: show_vma_header_prefix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void show_vma_header_prefix(struct seq_file *m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813ce3b0)
Location: fs/proc/task_mmu.c:250
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_map_vma
```
**Symbols:**

```
ffffffff813ce3b0-ffffffff813ce4f1: show_vma_header_prefix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void show_vma_header_prefix(struct seq_file *m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8141f6e0)
Location: fs/proc/task_mmu.c:250
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_map_vma
```
**Symbols:**

```
ffffffff8141f6e0-ffffffff8141f821: show_vma_header_prefix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void show_vma_header_prefix(struct seq_file *m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81497590)
Location: fs/proc/task_mmu.c:251
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_map_vma
```
**Symbols:**

```
ffffffff81497590-ffffffff814976e6: show_vma_header_prefix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void show_vma_header_prefix(struct seq_file *m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8152b5c0)
Location: fs/proc/task_mmu.c:254
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_map_vma
```
**Symbols:**

```
ffffffff8152b5c0-ffffffff8152b716: show_vma_header_prefix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void show_vma_header_prefix(struct seq_file *m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81563960)
Location: fs/proc/task_mmu.c:254
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_map_vma
```
**Symbols:**

```
ffffffff81563960-ffffffff81563ab6: show_vma_header_prefix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void show_vma_header_prefix(struct seq_file *m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8159a1f0)
Location: fs/proc/task_mmu.c:242
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_map_vma
```
**Symbols:**

```
ffffffff8159a1f0-ffffffff8159a346: show_vma_header_prefix (STB_LOCAL)
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
void show_vma_header_prefix(struct seq_file *m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffff800010437a58)
Location: fs/proc/task_mmu.c:279
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_map_vma
```
**Symbols:**

```
ffff800010437a58-ffff800010437bac: show_vma_header_prefix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void show_vma_header_prefix(struct seq_file *m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (c05ff70c)
Location: fs/proc/task_mmu.c:279
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_map_vma
```
**Symbols:**

```
c05ff70c-c05ff854: show_vma_header_prefix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void show_vma_header_prefix(struct seq_file *m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (c000000000549f20)
Location: fs/proc/task_mmu.c:279
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_map_vma
```
**Symbols:**

```
c000000000549f20-c00000000054a0d0: show_vma_header_prefix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void show_vma_header_prefix(struct seq_file *m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffe0002d1c8c)
Location: fs/proc/task_mmu.c:279
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_map_vma
```
**Symbols:**

```
ffffffe0002d1c8c-ffffffe0002d1dd8: show_vma_header_prefix (STB_LOCAL)
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
void show_vma_header_prefix(struct seq_file *m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81366590)
Location: fs/proc/task_mmu.c:279
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_map_vma
```
**Symbols:**

```
ffffffff81366590-ffffffff813666d1: show_vma_header_prefix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void show_vma_header_prefix(struct seq_file *m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81357230)
Location: fs/proc/task_mmu.c:279
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_map_vma
```
**Symbols:**

```
ffffffff81357230-ffffffff81357371: show_vma_header_prefix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void show_vma_header_prefix(struct seq_file *m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81364060)
Location: fs/proc/task_mmu.c:279
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_map_vma
```
**Symbols:**

```
ffffffff81364060-ffffffff813641a1: show_vma_header_prefix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void show_vma_header_prefix(struct seq_file *m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81377710)
Location: fs/proc/task_mmu.c:279
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_map_vma
```
**Symbols:**

```
ffffffff81377710-ffffffff81377851: show_vma_header_prefix (STB_LOCAL)
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
