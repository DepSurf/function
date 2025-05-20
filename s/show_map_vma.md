# Function: <code>show_map_vma</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void show_map_vma(struct seq_file *m, struct vm_area_struct *vma, int is_pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff812775f0)
Location: fs/proc/task_mmu.c:277
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_pid_map
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_tid_map
```
**Symbols:**

```
ffffffff812775f0-ffffffff8127782d: show_map_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void show_map_vma(struct seq_file *m, struct vm_area_struct *vma, int is_pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff812a3bc0)
Location: fs/proc/task_mmu.c:288
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_tid_map
  - fs/proc/task_mmu.c:show_pid_map
```
**Symbols:**

```
ffffffff812a3bc0-ffffffff812a3dfd: show_map_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff812b9550)
Location: fs/proc/task_mmu.c:281
Inline: True
```
**Symbols:**

```
ffffffff812b9550-ffffffff812b9786: show_map_vma.isra.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff812c6980)
Location: fs/proc/task_mmu.c:283
Inline: True
```
**Symbols:**

```
ffffffff812c6980-ffffffff812c6b76: show_map_vma.isra.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff812ea500)
Location: fs/proc/task_mmu.c:297
Inline: True
```
**Symbols:**

```
ffffffff812ea500-ffffffff812ea6f9: show_map_vma.isra.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81317510)
Location: fs/proc/task_mmu.c:297
Inline: True
Direct callers:
  - fs/proc/task_mmu.c:show_pid_map
```
**Symbols:**

```
ffffffff81317510-ffffffff81317683: show_map_vma.isra.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void show_map_vma(struct seq_file *m, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8132e000)
Location: fs/proc/task_mmu.c:296
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map
```
**Symbols:**

```
ffffffff8132e000-ffffffff8132e173: show_map_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void show_map_vma(struct seq_file *m, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81355da0)
Location: fs/proc/task_mmu.c:300
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map
```
**Symbols:**

```
ffffffff81355da0-ffffffff81355f13: show_map_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void show_map_vma(struct seq_file *m, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8136e100)
Location: fs/proc/task_mmu.c:300
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map
```
**Symbols:**

```
ffffffff8136e100-ffffffff8136e273: show_map_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void show_map_vma(struct seq_file *m, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813b5c80)
Location: fs/proc/task_mmu.c:271
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map
```
**Symbols:**

```
ffffffff813b5c80-ffffffff813b5df3: show_map_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void show_map_vma(struct seq_file *m, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813c7470)
Location: fs/proc/task_mmu.c:271
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map
```
**Symbols:**

```
ffffffff813c7470-ffffffff813c75e3: show_map_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void show_map_vma(struct seq_file *m, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813ce500)
Location: fs/proc/task_mmu.c:271
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map
```
**Symbols:**

```
ffffffff813ce500-ffffffff813ce644: show_map_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void show_map_vma(struct seq_file *m, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8141f830)
Location: fs/proc/task_mmu.c:271
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map
```
**Symbols:**

```
ffffffff8141f830-ffffffff8141f9a3: show_map_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void show_map_vma(struct seq_file *m, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff814976f0)
Location: fs/proc/task_mmu.c:272
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map
```
**Symbols:**

```
ffffffff814976f0-ffffffff814978ae: show_map_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void show_map_vma(struct seq_file *m, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8152b730)
Location: fs/proc/task_mmu.c:275
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map
```
**Symbols:**

```
ffffffff8152b730-ffffffff8152b93d: show_map_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void show_map_vma(struct seq_file *m, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81563ad0)
Location: fs/proc/task_mmu.c:275
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map
```
**Symbols:**

```
ffffffff81563ad0-ffffffff81563cbe: show_map_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void show_map_vma(struct seq_file *m, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8159a360)
Location: fs/proc/task_mmu.c:263
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map
```
**Symbols:**

```
ffffffff8159a360-ffffffff8159a593: show_map_vma (STB_LOCAL)
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
void show_map_vma(struct seq_file *m, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffff800010437bb0)
Location: fs/proc/task_mmu.c:300
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map
```
**Symbols:**

```
ffff800010437bb0-ffff800010437d50: show_map_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void show_map_vma(struct seq_file *m, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (c05ff854)
Location: fs/proc/task_mmu.c:300
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map
```
**Symbols:**

```
c05ff854-c05ff9f0: show_map_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void show_map_vma(struct seq_file *m, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (c00000000054a0d0)
Location: fs/proc/task_mmu.c:300
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map
```
**Symbols:**

```
c00000000054a0d0-c00000000054a2fc: show_map_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void show_map_vma(struct seq_file *m, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffe0002d1dd8)
Location: fs/proc/task_mmu.c:300
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map
```
**Symbols:**

```
ffffffe0002d1dd8-ffffffe0002d1f14: show_map_vma (STB_LOCAL)
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
void show_map_vma(struct seq_file *m, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813666e0)
Location: fs/proc/task_mmu.c:300
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map
```
**Symbols:**

```
ffffffff813666e0-ffffffff81366853: show_map_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void show_map_vma(struct seq_file *m, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81357380)
Location: fs/proc/task_mmu.c:300
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map
```
**Symbols:**

```
ffffffff81357380-ffffffff813574f3: show_map_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void show_map_vma(struct seq_file *m, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813641b0)
Location: fs/proc/task_mmu.c:300
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map
```
**Symbols:**

```
ffffffff813641b0-ffffffff81364323: show_map_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void show_map_vma(struct seq_file *m, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81377860)
Location: fs/proc/task_mmu.c:300
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map
```
**Symbols:**

```
ffffffff81377860-ffffffff813779d3: show_map_vma (STB_LOCAL)
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
