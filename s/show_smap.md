# Function: <code>show_smap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int show_smap(struct seq_file *m, void *v, int is_pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81277870)
Location: fs/proc/task_mmu.c:654
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_pid_smap
  - fs/proc/task_mmu.c:show_tid_smap
```
**Symbols:**

```
ffffffff81277870-ffffffff81277a95: show_smap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int show_smap(struct seq_file *m, void *v, int is_pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff812a5c70)
Location: fs/proc/task_mmu.c:729
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_tid_smap
  - fs/proc/task_mmu.c:show_pid_smap
```
**Symbols:**

```
ffffffff812a5c70-ffffffff812a5f16: show_smap (STB_LOCAL)
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
In fs/proc/task_mmu.c (ffffffff812bb5c0)
Location: fs/proc/task_mmu.c:722
Inline: True
```
**Symbols:**

```
ffffffff812bb5c0-ffffffff812bb860: show_smap.isra.33 (STB_LOCAL)
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
In fs/proc/task_mmu.c (ffffffff812c89c0)
Location: fs/proc/task_mmu.c:723
Inline: True
```
**Symbols:**

```
ffffffff812c89c0-ffffffff812c8c37: show_smap.isra.28 (STB_LOCAL)
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
In fs/proc/task_mmu.c (ffffffff812ed110)
Location: fs/proc/task_mmu.c:737
Inline: True
```
**Symbols:**

```
ffffffff812ed110-ffffffff812ed498: show_smap.isra.29 (STB_LOCAL)
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
In fs/proc/task_mmu.c (ffffffff81317690)
Location: fs/proc/task_mmu.c:739
Inline: True
```
**Symbols:**

```
ffffffff81317690-ffffffff81317bcc: show_smap.isra.30 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int show_smap(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8132edb0)
Location: fs/proc/task_mmu.c:784
Inline: False
```
**Symbols:**

```
ffffffff8132edb0-ffffffff8132ef7c: show_smap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int show_smap(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81356820)
Location: fs/proc/task_mmu.c:820
Inline: False
```
**Symbols:**

```
ffffffff81356820-ffffffff813569ec: show_smap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int show_smap(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8136eae0)
Location: fs/proc/task_mmu.c:828
Inline: False
```
**Symbols:**

```
ffffffff8136eae0-ffffffff8136ecac: show_smap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int show_smap(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813b6080)
Location: fs/proc/task_mmu.c:804
Inline: False
```
**Symbols:**

```
ffffffff813b6080-ffffffff813b6235: show_smap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int show_smap(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813c7cb0)
Location: fs/proc/task_mmu.c:816
Inline: False
```
**Symbols:**

```
ffffffff813c7cb0-ffffffff813c7e6e: show_smap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int show_smap(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813ce970)
Location: fs/proc/task_mmu.c:816
Inline: False
```
**Symbols:**

```
ffffffff813ce970-ffffffff813ceb2e: show_smap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int show_smap(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8141fcd0)
Location: fs/proc/task_mmu.c:832
Inline: False
```
**Symbols:**

```
ffffffff8141fcd0-ffffffff8141fed0: show_smap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int show_smap(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81497c10)
Location: fs/proc/task_mmu.c:848
Inline: False
```
**Symbols:**

```
ffffffff81497c10-ffffffff81497e24: show_smap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int show_smap(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8152c0c0)
Location: fs/proc/task_mmu.c:860
Inline: False
```
**Symbols:**

```
ffffffff8152c0c0-ffffffff8152c2e4: show_smap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int show_smap(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81564480)
Location: fs/proc/task_mmu.c:856
Inline: False
```
**Symbols:**

```
ffffffff81564480-ffffffff815646a4: show_smap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int show_smap(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8159aad0)
Location: fs/proc/task_mmu.c:852
Inline: False
```
**Symbols:**

```
ffffffff8159aad0-ffffffff8159ad5d: show_smap (STB_LOCAL)
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
int show_smap(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffff800010438700)
Location: fs/proc/task_mmu.c:828
Inline: False
```
**Symbols:**

```
ffff800010438700-ffff8000104388f0: show_smap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int show_smap(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (c05ffdd4)
Location: fs/proc/task_mmu.c:828
Inline: False
```
**Symbols:**

```
c05ffdd4-c05fffbc: show_smap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int show_smap(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (c00000000054b250)
Location: fs/proc/task_mmu.c:828
Inline: False
```
**Symbols:**

```
c00000000054b250-c00000000054b484: show_smap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int show_smap(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffe0002d25b0)
Location: fs/proc/task_mmu.c:828
Inline: False
```
**Symbols:**

```
ffffffe0002d25b0-ffffffe0002d274e: show_smap (STB_LOCAL)
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
int show_smap(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813670c0)
Location: fs/proc/task_mmu.c:828
Inline: False
```
**Symbols:**

```
ffffffff813670c0-ffffffff8136728c: show_smap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int show_smap(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81357d60)
Location: fs/proc/task_mmu.c:828
Inline: False
```
**Symbols:**

```
ffffffff81357d60-ffffffff81357f2c: show_smap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int show_smap(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81364b90)
Location: fs/proc/task_mmu.c:828
Inline: False
```
**Symbols:**

```
ffffffff81364b90-ffffffff81364d5c: show_smap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int show_smap(struct seq_file *m, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81378600)
Location: fs/proc/task_mmu.c:828
Inline: False
```
**Symbols:**

```
ffffffff81378600-ffffffff813787cc: show_smap (STB_LOCAL)
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
