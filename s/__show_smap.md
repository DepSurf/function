# Function: <code>__show_smap</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __show_smap(struct seq_file *m, const struct mem_size_stats *mss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8132dcb0)
Location: fs/proc/task_mmu.c:760
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff8132dcb0-ffffffff8132dea1: __show_smap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __show_smap(struct seq_file *m, const struct mem_size_stats *mss, bool rollup_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813559f0)
Location: fs/proc/task_mmu.c:783
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff813559f0-ffffffff81355c44: __show_smap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __show_smap(struct seq_file *m, const struct mem_size_stats *mss, bool rollup_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8136dd30)
Location: fs/proc/task_mmu.c:790
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff8136dd30-ffffffff8136dfa3: __show_smap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __show_smap(struct seq_file *m, const struct mem_size_stats *mss, bool rollup_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813b58b0)
Location: fs/proc/task_mmu.c:766
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff813b58b0-ffffffff813b5b23: __show_smap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __show_smap(struct seq_file *m, const struct mem_size_stats *mss, bool rollup_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813c70a0)
Location: fs/proc/task_mmu.c:778
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff813c70a0-ffffffff813c7313: __show_smap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __show_smap(struct seq_file *m, const struct mem_size_stats *mss, bool rollup_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813ce130)
Location: fs/proc/task_mmu.c:778
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff813ce130-ffffffff813ce3a3: __show_smap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __show_smap(struct seq_file *m, const struct mem_size_stats *mss, bool rollup_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8141f460)
Location: fs/proc/task_mmu.c:794
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff8141f460-ffffffff8141f6d3: __show_smap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __show_smap(struct seq_file *m, const struct mem_size_stats *mss, bool rollup_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff814972f0)
Location: fs/proc/task_mmu.c:810
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff814972f0-ffffffff81497582: __show_smap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __show_smap(struct seq_file *m, const struct mem_size_stats *mss, bool rollup_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8152b2f0)
Location: fs/proc/task_mmu.c:821
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff8152b2f0-ffffffff8152b5a2: __show_smap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __show_smap(struct seq_file *m, const struct mem_size_stats *mss, bool rollup_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81563690)
Location: fs/proc/task_mmu.c:817
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff81563690-ffffffff81563942: __show_smap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __show_smap(struct seq_file *m, const struct mem_size_stats *mss, bool rollup_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81599db0)
Location: fs/proc/task_mmu.c:812
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff81599db0-ffffffff8159a082: __show_smap (STB_LOCAL)
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
void __show_smap(struct seq_file *m, const struct mem_size_stats *mss, bool rollup_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffff8000104377d8)
Location: fs/proc/task_mmu.c:790
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffff8000104377d8-ffff800010437a54: __show_smap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __show_smap(struct seq_file *m, const struct mem_size_stats *mss, bool rollup_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (c05ff41c)
Location: fs/proc/task_mmu.c:790
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
c05ff41c-c05ff70c: __show_smap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __show_smap(struct seq_file *m, const struct mem_size_stats *mss, bool rollup_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (c000000000549c20)
Location: fs/proc/task_mmu.c:790
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
c000000000549c20-c000000000549f14: __show_smap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __show_smap(struct seq_file *m, const struct mem_size_stats *mss, bool rollup_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffe0002d19a8)
Location: fs/proc/task_mmu.c:790
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffe0002d19a8-ffffffe0002d1bf4: __show_smap (STB_LOCAL)
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
void __show_smap(struct seq_file *m, const struct mem_size_stats *mss, bool rollup_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81366310)
Location: fs/proc/task_mmu.c:790
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff81366310-ffffffff81366583: __show_smap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __show_smap(struct seq_file *m, const struct mem_size_stats *mss, bool rollup_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81356fb0)
Location: fs/proc/task_mmu.c:790
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff81356fb0-ffffffff81357223: __show_smap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __show_smap(struct seq_file *m, const struct mem_size_stats *mss, bool rollup_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81363de0)
Location: fs/proc/task_mmu.c:790
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff81363de0-ffffffff81364053: __show_smap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __show_smap(struct seq_file *m, const struct mem_size_stats *mss, bool rollup_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81377490)
Location: fs/proc/task_mmu.c:790
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff81377490-ffffffff81377703: __show_smap (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool rollup_mode</code>
</li>
</ul>
</details>
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
