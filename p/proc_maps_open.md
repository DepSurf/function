# Function: <code>proc_maps_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int proc_maps_open(struct inode *inode, struct file *file, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81276cd0)
Location: fs/proc/task_mmu.c:213
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pid_maps_open
  - fs/proc/task_mmu.c:tid_maps_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:tid_smaps_open
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:tid_numa_maps_open
```
**Symbols:**

```
ffffffff81276cd0-ffffffff81276d3d: proc_maps_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int proc_maps_open(struct inode *inode, struct file *file, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff812a3380)
Location: fs/proc/task_mmu.c:224
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:tid_numa_maps_open
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:tid_smaps_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:tid_maps_open
  - fs/proc/task_mmu.c:pid_maps_open
```
**Symbols:**

```
ffffffff812a3380-ffffffff812a33e6: proc_maps_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int proc_maps_open(struct inode *inode, struct file *file, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff812b8d60)
Location: fs/proc/task_mmu.c:226
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:tid_numa_maps_open
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:tid_smaps_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:tid_maps_open
  - fs/proc/task_mmu.c:pid_maps_open
```
**Symbols:**

```
ffffffff812b8d60-ffffffff812b8dc6: proc_maps_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int proc_maps_open(struct inode *inode, struct file *file, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff812c6130)
Location: fs/proc/task_mmu.c:228
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:tid_numa_maps_open
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:tid_smaps_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:tid_maps_open
  - fs/proc/task_mmu.c:pid_maps_open
```
**Symbols:**

```
ffffffff812c6130-ffffffff812c6196: proc_maps_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int proc_maps_open(struct inode *inode, struct file *file, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff812e9ff0)
Location: fs/proc/task_mmu.c:225
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:tid_numa_maps_open
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:tid_smaps_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:tid_maps_open
  - fs/proc/task_mmu.c:pid_maps_open
```
**Symbols:**

```
ffffffff812e9ff0-ffffffff812ea056: proc_maps_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int proc_maps_open(struct inode *inode, struct file *file, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81317020)
Location: fs/proc/task_mmu.c:222
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:tid_numa_maps_open
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:tid_smaps_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:tid_maps_open
  - fs/proc/task_mmu.c:pid_maps_open
```
**Symbols:**

```
ffffffff81317020-ffffffff8131708d: proc_maps_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int proc_maps_open(struct inode *inode, struct file *file, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8132e300)
Location: fs/proc/task_mmu.c:222
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:pid_maps_open
```
**Symbols:**

```
ffffffff8132e300-ffffffff8132e36d: proc_maps_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int proc_maps_open(struct inode *inode, struct file *file, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813560a0)
Location: fs/proc/task_mmu.c:226
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:pid_maps_open
```
**Symbols:**

```
ffffffff813560a0-ffffffff8135610e: proc_maps_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int proc_maps_open(struct inode *inode, struct file *file, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8136e400)
Location: fs/proc/task_mmu.c:226
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:pid_maps_open
```
**Symbols:**

```
ffffffff8136e400-ffffffff8136e46e: proc_maps_open (STB_LOCAL)
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
In fs/proc/task_mmu.c (ffffffff813b6d05)
Location: fs/proc/task_mmu.c:197
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:pid_maps_open
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
In fs/proc/task_mmu.c (ffffffff813c83b1)
Location: fs/proc/task_mmu.c:197
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:pid_maps_open
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
In fs/proc/task_mmu.c (ffffffff813cf231)
Location: fs/proc/task_mmu.c:197
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:pid_maps_open
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
In fs/proc/task_mmu.c (ffffffff814205f1)
Location: fs/proc/task_mmu.c:197
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:pid_maps_open
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
In fs/proc/task_mmu.c (ffffffff814983cf)
Location: fs/proc/task_mmu.c:198
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:pid_maps_open
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
In fs/proc/task_mmu.c (ffffffff8152b9ff)
Location: fs/proc/task_mmu.c:201
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:pid_maps_open
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
In fs/proc/task_mmu.c (ffffffff8156499f)
Location: fs/proc/task_mmu.c:201
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:pid_maps_open
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
In fs/proc/task_mmu.c (ffffffff8159b37f)
Location: fs/proc/task_mmu.c:204
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:pid_maps_open
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
int proc_maps_open(struct inode *inode, struct file *file, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffff800010437f20)
Location: fs/proc/task_mmu.c:226
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:pid_maps_open
```
**Symbols:**

```
ffff800010437f20-ffff800010437fb0: proc_maps_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/task_mmu.c (c05fffbc)
Location: fs/proc/task_mmu.c:226
Inline: True
Direct callers:
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:pid_maps_open
```
**Symbols:**

```
c05fffbc-c0600038: proc_maps_open.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int proc_maps_open(struct inode *inode, struct file *file, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (c00000000054a570)
Location: fs/proc/task_mmu.c:226
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:pid_maps_open
```
**Symbols:**

```
c00000000054a570-c00000000054a630: proc_maps_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/task_mmu.c (ffffffe0002d29bc)
Location: fs/proc/task_mmu.c:226
Inline: True
Direct callers:
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:pid_maps_open
```
**Symbols:**

```
ffffffe0002d29bc-ffffffe0002d2a30: proc_maps_open.constprop.0 (STB_LOCAL)
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
int proc_maps_open(struct inode *inode, struct file *file, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813669e0)
Location: fs/proc/task_mmu.c:226
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:pid_maps_open
```
**Symbols:**

```
ffffffff813669e0-ffffffff81366a4e: proc_maps_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int proc_maps_open(struct inode *inode, struct file *file, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81357680)
Location: fs/proc/task_mmu.c:226
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:pid_maps_open
```
**Symbols:**

```
ffffffff81357680-ffffffff813576ee: proc_maps_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int proc_maps_open(struct inode *inode, struct file *file, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813644b0)
Location: fs/proc/task_mmu.c:226
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:pid_maps_open
```
**Symbols:**

```
ffffffff813644b0-ffffffff8136451e: proc_maps_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int proc_maps_open(struct inode *inode, struct file *file, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81377b60)
Location: fs/proc/task_mmu.c:226
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:pid_maps_open
```
**Symbols:**

```
ffffffff81377b60-ffffffff81377bce: proc_maps_open (STB_LOCAL)
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
