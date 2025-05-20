# Function: <code>show_numa_map</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int show_numa_map(struct seq_file *m, void *v, int is_pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81277ae0)
Location: fs/proc/task_mmu.c:1497
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_pid_numa_map
  - fs/proc/task_mmu.c:show_tid_numa_map
```
**Symbols:**

```
ffffffff81277ae0-ffffffff81277ef0: show_numa_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int show_numa_map(struct seq_file *m, void *v, int is_pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff812a3e40)
Location: fs/proc/task_mmu.c:1634
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_tid_numa_map
  - fs/proc/task_mmu.c:show_pid_numa_map
```
**Symbols:**

```
ffffffff812a3e40-ffffffff812a4250: show_numa_map (STB_LOCAL)
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
In fs/proc/task_mmu.c (ffffffff812b9920)
Location: fs/proc/task_mmu.c:1628
Inline: True
```
**Symbols:**

```
ffffffff812b9920-ffffffff812b9d1a: show_numa_map.isra.32 (STB_LOCAL)
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
In fs/proc/task_mmu.c (ffffffff812c6b80)
Location: fs/proc/task_mmu.c:1640
Inline: True
```
**Symbols:**

```
ffffffff812c6b80-ffffffff812c6f70: show_numa_map.isra.27 (STB_LOCAL)
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
In fs/proc/task_mmu.c (ffffffff812ea700)
Location: fs/proc/task_mmu.c:1736
Inline: True
```
**Symbols:**

```
ffffffff812ea700-ffffffff812eaaf0: show_numa_map.isra.28 (STB_LOCAL)
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
In fs/proc/task_mmu.c (ffffffff81317be0)
Location: fs/proc/task_mmu.c:1734
Inline: True
```
**Symbols:**

```
ffffffff81317be0-ffffffff81317fcc: show_numa_map.isra.35 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int show_numa_map(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8132e9c0)
Location: fs/proc/task_mmu.c:1740
Inline: False
```
**Symbols:**

```
ffffffff8132e9c0-ffffffff8132edac: show_numa_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int show_numa_map(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81356430)
Location: fs/proc/task_mmu.c:1807
Inline: False
```
**Symbols:**

```
ffffffff81356430-ffffffff81356820: show_numa_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int show_numa_map(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8136e6b0)
Location: fs/proc/task_mmu.c:1819
Inline: False
```
**Symbols:**

```
ffffffff8136e6b0-ffffffff8136ea46: show_numa_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int show_numa_map(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813b62e0)
Location: fs/proc/task_mmu.c:1793
Inline: False
```
**Symbols:**

```
ffffffff813b62e0-ffffffff813b6664: show_numa_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int show_numa_map(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813c7860)
Location: fs/proc/task_mmu.c:1863
Inline: False
```
**Symbols:**

```
ffffffff813c7860-ffffffff813c7be4: show_numa_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int show_numa_map(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813cebd0)
Location: fs/proc/task_mmu.c:1861
Inline: False
```
**Symbols:**

```
ffffffff813cebd0-ffffffff813cef33: show_numa_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int show_numa_map(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8141ff70)
Location: fs/proc/task_mmu.c:1888
Inline: False
```
**Symbols:**

```
ffffffff8141ff70-ffffffff814202e1: show_numa_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int show_numa_map(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81497ed0)
Location: fs/proc/task_mmu.c:1909
Inline: False
```
**Symbols:**

```
ffffffff81497ed0-ffffffff81498252: show_numa_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int show_numa_map(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8152bc40)
Location: fs/proc/task_mmu.c:1940
Inline: False
```
**Symbols:**

```
ffffffff8152bc40-ffffffff8152bfc6: show_numa_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int show_numa_map(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81563fc0)
Location: fs/proc/task_mmu.c:1947
Inline: False
```
**Symbols:**

```
ffffffff81563fc0-ffffffff81564384: show_numa_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int show_numa_map(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8159ae20)
Location: fs/proc/task_mmu.c:2698
Inline: False
```
**Symbols:**

```
ffffffff8159ae20-ffffffff8159b208: show_numa_map (STB_LOCAL)
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
int show_numa_map(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffff800010438290)
Location: fs/proc/task_mmu.c:1819
Inline: False
```
**Symbols:**

```
ffff800010438290-ffff800010438630: show_numa_map (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int show_numa_map(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (c00000000054a910)
Location: fs/proc/task_mmu.c:1819
Inline: False
```
**Symbols:**

```
c00000000054a910-c00000000054ae18: show_numa_map (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int show_numa_map(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81366c90)
Location: fs/proc/task_mmu.c:1819
Inline: False
```
**Symbols:**

```
ffffffff81366c90-ffffffff81367026: show_numa_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int show_numa_map(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81357930)
Location: fs/proc/task_mmu.c:1819
Inline: False
```
**Symbols:**

```
ffffffff81357930-ffffffff81357cc6: show_numa_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int show_numa_map(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81364760)
Location: fs/proc/task_mmu.c:1819
Inline: False
```
**Symbols:**

```
ffffffff81364760-ffffffff81364af6: show_numa_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int show_numa_map(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81378180)
Location: fs/proc/task_mmu.c:1819
Inline: False
```
**Symbols:**

```
ffffffff81378180-ffffffff81378516: show_numa_map (STB_LOCAL)
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
