# Function: <code>proc_mem_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct mm_struct *proc_mem_open(struct inode *inode, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8127d550)
Location: fs/proc/base.c:809
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:proc_maps_open
  - fs/proc/task_mmu.c:pagemap_open
  - fs/proc/base.c:mem_open
  - fs/proc/base.c:environ_open
```
**Symbols:**

```
ffffffff8127d550-ffffffff8127d5c2: proc_mem_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct mm_struct *proc_mem_open(struct inode *inode, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812aa530)
Location: fs/proc/base.c:811
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pagemap_open
  - fs/proc/task_mmu.c:proc_maps_open
  - fs/proc/base.c:environ_open
  - fs/proc/base.c:mem_open
```
**Symbols:**

```
ffffffff812aa530-ffffffff812aa5a2: proc_mem_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct mm_struct *proc_mem_open(struct inode *inode, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812bfe50)
Location: fs/proc/base.c:797
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pagemap_open
  - fs/proc/task_mmu.c:proc_maps_open
  - fs/proc/base.c:auxv_open
  - fs/proc/base.c:environ_open
  - fs/proc/base.c:mem_open
```
**Symbols:**

```
ffffffff812bfe50-ffffffff812bfec2: proc_mem_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct mm_struct *proc_mem_open(struct inode *inode, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812cce40)
Location: fs/proc/base.c:774
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pagemap_open
  - fs/proc/task_mmu.c:proc_maps_open
  - fs/proc/base.c:auxv_open
  - fs/proc/base.c:environ_open
  - fs/proc/base.c:mem_open
```
**Symbols:**

```
ffffffff812cce40-ffffffff812cceb2: proc_mem_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct mm_struct *proc_mem_open(struct inode *inode, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812f16e0)
Location: fs/proc/base.c:774
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pagemap_open
  - fs/proc/task_mmu.c:proc_maps_open
  - fs/proc/base.c:auxv_open
  - fs/proc/base.c:environ_open
  - fs/proc/base.c:mem_open
```
**Symbols:**

```
ffffffff812f16e0-ffffffff812f1752: proc_mem_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct mm_struct *proc_mem_open(struct inode *inode, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8131e590)
Location: fs/proc/base.c:742
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pagemap_open
  - fs/proc/task_mmu.c:proc_maps_open
  - fs/proc/base.c:auxv_open
  - fs/proc/base.c:environ_open
  - fs/proc/base.c:mem_open
```
**Symbols:**

```
ffffffff8131e590-ffffffff8131e612: proc_mem_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct mm_struct *proc_mem_open(struct inode *inode, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81335680)
Location: fs/proc/base.c:762
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pagemap_open
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/task_mmu.c:proc_maps_open
  - fs/proc/base.c:auxv_open
  - fs/proc/base.c:environ_open
  - fs/proc/base.c:mem_open
```
**Symbols:**

```
ffffffff81335680-ffffffff81335702: proc_mem_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct mm_struct *proc_mem_open(struct inode *inode, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8135d700)
Location: fs/proc/base.c:775
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pagemap_open
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/task_mmu.c:proc_maps_open
  - fs/proc/base.c:auxv_open
  - fs/proc/base.c:environ_open
  - fs/proc/base.c:mem_open
```
**Symbols:**

```
ffffffff8135d700-ffffffff8135d77c: proc_mem_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct mm_struct *proc_mem_open(struct inode *inode, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81375960)
Location: fs/proc/base.c:775
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pagemap_open
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/task_mmu.c:proc_maps_open
  - fs/proc/base.c:auxv_open
  - fs/proc/base.c:environ_open
  - fs/proc/base.c:mem_open
```
**Symbols:**

```
ffffffff81375960-ffffffff813759dc: proc_mem_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct mm_struct *proc_mem_open(struct inode *inode, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813be400)
Location: fs/proc/base.c:785
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:pagemap_open
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:pid_maps_open
  - fs/proc/base.c:auxv_open
  - fs/proc/base.c:environ_open
  - fs/proc/base.c:mem_open
```
**Symbols:**

```
ffffffff813be400-ffffffff813be48f: proc_mem_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct mm_struct *proc_mem_open(struct inode *inode, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813d0150)
Location: fs/proc/base.c:794
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:pagemap_open
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:pid_maps_open
  - fs/proc/base.c:auxv_open
  - fs/proc/base.c:environ_open
  - fs/proc/base.c:mem_open
```
**Symbols:**

```
ffffffff813d0150-ffffffff813d01df: proc_mem_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct mm_struct *proc_mem_open(struct inode *inode, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813d7030)
Location: fs/proc/base.c:793
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:pagemap_open
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:pid_maps_open
  - fs/proc/base.c:proc_pid_attr_open
  - fs/proc/base.c:auxv_open
  - fs/proc/base.c:environ_open
  - fs/proc/base.c:mem_open
```
**Symbols:**

```
ffffffff813d7030-ffffffff813d70bf: proc_mem_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct mm_struct *proc_mem_open(struct inode *inode, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81428770)
Location: fs/proc/base.c:797
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:pagemap_open
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:pid_maps_open
  - fs/proc/base.c:proc_pid_attr_open
  - fs/proc/base.c:auxv_open
  - fs/proc/base.c:environ_open
  - fs/proc/base.c:mem_open
```
**Symbols:**

```
ffffffff81428770-ffffffff814287ff: proc_mem_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct mm_struct *proc_mem_open(struct inode *inode, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff814a1a30)
Location: fs/proc/base.c:796
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:pagemap_open
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:pid_maps_open
  - fs/proc/base.c:proc_pid_attr_open
  - fs/proc/base.c:auxv_open
  - fs/proc/base.c:environ_open
  - fs/proc/base.c:mem_open
```
**Symbols:**

```
ffffffff814a1a30-ffffffff814a1ac7: proc_mem_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct mm_struct *proc_mem_open(struct inode *inode, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81536a90)
Location: fs/proc/base.c:797
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:pagemap_open
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:pid_maps_open
  - fs/proc/base.c:proc_pid_attr_open
  - fs/proc/base.c:auxv_open
  - fs/proc/base.c:environ_open
  - fs/proc/base.c:mem_open
```
**Symbols:**

```
ffffffff81536a90-ffffffff81536b27: proc_mem_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct mm_struct *proc_mem_open(struct inode *inode, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8156ec70)
Location: fs/proc/base.c:797
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:pagemap_open
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:pid_maps_open
  - fs/proc/base.c:proc_pid_attr_open
  - fs/proc/base.c:auxv_open
  - fs/proc/base.c:environ_open
  - fs/proc/base.c:mem_open
```
**Symbols:**

```
ffffffff8156ec70-ffffffff8156ed06: proc_mem_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct mm_struct *proc_mem_open(struct inode *inode, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff815a7630)
Location: fs/proc/base.c:797
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:pagemap_open
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:pid_maps_open
  - fs/proc/base.c:proc_pid_attr_open
  - fs/proc/base.c:auxv_open
  - fs/proc/base.c:environ_open
  - fs/proc/base.c:mem_open
```
**Symbols:**

```
ffffffff815a7630-ffffffff815a76c6: proc_mem_open (STB_GLOBAL)
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
struct mm_struct *proc_mem_open(struct inode *inode, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffff800010440c18)
Location: fs/proc/base.c:775
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pagemap_open
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/task_mmu.c:proc_maps_open
  - fs/proc/base.c:auxv_open
  - fs/proc/base.c:environ_open
  - fs/proc/base.c:mem_open
```
**Symbols:**

```
ffff800010440c18-ffff800010440cc8: proc_mem_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct mm_struct *proc_mem_open(struct inode *inode, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c0606664)
Location: fs/proc/base.c:775
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pagemap_open
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:auxv_open
  - fs/proc/base.c:environ_open
  - fs/proc/base.c:mem_open
```
**Symbols:**

```
c0606664-c0606700: proc_mem_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct mm_struct *proc_mem_open(struct inode *inode, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c0000000005559f0)
Location: fs/proc/base.c:775
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pagemap_open
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/task_mmu.c:proc_maps_open
  - fs/proc/base.c:auxv_open
  - fs/proc/base.c:environ_open
  - fs/proc/base.c:mem_open
```
**Symbols:**

```
c0000000005559f0-c000000000555af8: proc_mem_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct mm_struct *proc_mem_open(struct inode *inode, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffe0002d7ca0)
Location: fs/proc/base.c:775
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pagemap_open
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:auxv_open
  - fs/proc/base.c:environ_open
  - fs/proc/base.c:mem_open
```
**Symbols:**

```
ffffffe0002d7ca0-ffffffe0002d7d38: proc_mem_open (STB_GLOBAL)
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
struct mm_struct *proc_mem_open(struct inode *inode, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8136df40)
Location: fs/proc/base.c:775
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pagemap_open
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/task_mmu.c:proc_maps_open
  - fs/proc/base.c:auxv_open
  - fs/proc/base.c:environ_open
  - fs/proc/base.c:mem_open
```
**Symbols:**

```
ffffffff8136df40-ffffffff8136dfbc: proc_mem_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct mm_struct *proc_mem_open(struct inode *inode, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8135e9d0)
Location: fs/proc/base.c:775
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pagemap_open
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/task_mmu.c:proc_maps_open
  - fs/proc/base.c:auxv_open
  - fs/proc/base.c:environ_open
  - fs/proc/base.c:mem_open
```
**Symbols:**

```
ffffffff8135e9d0-ffffffff8135ea4c: proc_mem_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct mm_struct *proc_mem_open(struct inode *inode, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8136ba10)
Location: fs/proc/base.c:775
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pagemap_open
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/task_mmu.c:proc_maps_open
  - fs/proc/base.c:auxv_open
  - fs/proc/base.c:environ_open
  - fs/proc/base.c:mem_open
```
**Symbols:**

```
ffffffff8136ba10-ffffffff8136ba8c: proc_mem_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct mm_struct *proc_mem_open(struct inode *inode, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8137f2b0)
Location: fs/proc/base.c:775
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:pagemap_open
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/task_mmu.c:proc_maps_open
  - fs/proc/base.c:auxv_open
  - fs/proc/base.c:environ_open
  - fs/proc/base.c:mem_open
```
**Symbols:**

```
ffffffff8137f2b0-ffffffff8137f32c: proc_mem_open (STB_GLOBAL)
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
