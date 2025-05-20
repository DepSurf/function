# Function: <code>seq_open_private</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int seq_open_private(struct file *filp, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81231a00)
Location: fs/seq_file.c:647
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_open
  - mm/vmalloc.c:vmalloc_open
  - fs/proc_namespace.c:mounts_open_common
  - fs/locks.c:locks_open
  - lib/dynamic_debug.c:ddebug_proc_open
```
**Symbols:**

```
ffffffff81231a00-ffffffff81231a19: seq_open_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int seq_open_private(struct file *filp, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81259ee0)
Location: fs/seq_file.c:650
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_open
  - mm/vmalloc.c:vmalloc_open
  - fs/proc_namespace.c:mounts_open_common
  - fs/locks.c:locks_open
  - lib/dynamic_debug.c:ddebug_proc_open
```
**Symbols:**

```
ffffffff81259ee0-ffffffff81259ef9: seq_open_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int seq_open_private(struct file *filp, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8126ced0)
Location: fs/seq_file.c:657
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_open
  - mm/vmalloc.c:vmalloc_open
  - fs/proc_namespace.c:mounts_open_common
  - fs/locks.c:locks_open
  - lib/dynamic_debug.c:ddebug_proc_open
```
**Symbols:**

```
ffffffff8126ced0-ffffffff8126cee9: seq_open_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int seq_open_private(struct file *filp, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8127aa90)
Location: fs/seq_file.c:643
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_open
  - mm/vmalloc.c:vmalloc_open
  - fs/proc_namespace.c:mounts_open_common
  - fs/locks.c:locks_open
  - lib/dynamic_debug.c:ddebug_proc_open
```
**Symbols:**

```
ffffffff8127aa90-ffffffff8127aaa9: seq_open_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int seq_open_private(struct file *filp, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8129d500)
Location: fs/seq_file.c:647
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_open
  - mm/vmalloc.c:vmalloc_open
  - fs/proc_namespace.c:mounts_open_common
  - fs/locks.c:locks_open
  - lib/dynamic_debug.c:ddebug_proc_open
```
**Symbols:**

```
ffffffff8129d500-ffffffff8129d519: seq_open_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int seq_open_private(struct file *filp, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812c35a0)
Location: fs/seq_file.c:650
Inline: False
Direct callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc/generic.c:proc_seq_open
  - lib/dynamic_debug.c:ddebug_proc_open
  - drivers/base/power/wakeup.c:wakeup_sources_stats_open
```
**Symbols:**

```
ffffffff812c35a0-ffffffff812c35b9: seq_open_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int seq_open_private(struct file *filp, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812d87f0)
Location: fs/seq_file.c:638
Inline: False
Direct callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc/generic.c:proc_seq_open
  - lib/dynamic_debug.c:ddebug_proc_open
  - drivers/base/power/wakeup.c:wakeup_sources_stats_open
```
**Symbols:**

```
ffffffff812d87f0-ffffffff812d8809: seq_open_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int seq_open_private(struct file *filp, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812f6cf0)
Location: fs/seq_file.c:650
Inline: False
Direct callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc/generic.c:proc_seq_open
  - lib/dynamic_debug.c:ddebug_proc_open
  - drivers/base/power/wakeup.c:wakeup_sources_stats_open
```
**Symbols:**

```
ffffffff812f6cf0-ffffffff812f6d09: seq_open_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int seq_open_private(struct file *filp, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff813088c0)
Location: fs/seq_file.c:650
Inline: False
Direct callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc/generic.c:proc_seq_open
  - lib/dynamic_debug.c:ddebug_proc_open
  - drivers/base/power/wakeup.c:wakeup_sources_stats_open
```
**Symbols:**

```
ffffffff813088c0-ffffffff813088d9: seq_open_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int seq_open_private(struct file *filp, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81341b40)
Location: fs/seq_file.c:626
Inline: False
Direct callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc/generic.c:proc_seq_open
  - lib/dynamic_debug.c:ddebug_proc_open
  - drivers/base/power/wakeup.c:wakeup_sources_stats_open
```
**Symbols:**

```
ffffffff81341b40-ffffffff81341b59: seq_open_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int seq_open_private(struct file *filp, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8134e200)
Location: fs/seq_file.c:642
Inline: False
Direct callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc/generic.c:proc_seq_open
  - lib/dynamic_debug.c:ddebug_proc_open
  - drivers/base/power/wakeup.c:wakeup_sources_stats_open
```
**Symbols:**

```
ffffffff8134e200-ffffffff8134e219: seq_open_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int seq_open_private(struct file *filp, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff813545d0)
Location: fs/seq_file.c:663
Inline: False
Direct callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc/generic.c:proc_seq_open
  - lib/dynamic_debug.c:ddebug_proc_open
  - drivers/base/power/wakeup.c:wakeup_sources_stats_open
```
**Symbols:**

```
ffffffff813545d0-ffffffff813545e9: seq_open_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int seq_open_private(struct file *filp, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff813a29f0)
Location: fs/seq_file.c:672
Inline: False
Direct callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc/generic.c:proc_seq_open
  - lib/dynamic_debug.c:ddebug_proc_open
  - drivers/base/power/wakeup.c:wakeup_sources_stats_open
```
**Symbols:**

```
ffffffff813a29f0-ffffffff813a2a09: seq_open_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int seq_open_private(struct file *filp, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff814266f0)
Location: fs/seq_file.c:656
Inline: False
Direct callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc/generic.c:proc_seq_open
  - lib/dynamic_debug.c:ddebug_proc_open
  - drivers/base/power/wakeup.c:wakeup_sources_stats_open
```
**Symbols:**

```
ffffffff814266f0-ffffffff81426713: seq_open_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int seq_open_private(struct file *filp, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff814b2f20)
Location: fs/seq_file.c:656
Inline: False
Direct callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc/generic.c:proc_seq_open
  - lib/dynamic_debug.c:ddebug_proc_open
  - drivers/base/power/wakeup.c:wakeup_sources_stats_open
```
**Symbols:**

```
ffffffff814b2f20-ffffffff814b2f43: seq_open_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int seq_open_private(struct file *filp, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff814e7f70)
Location: fs/seq_file.c:656
Inline: False
Direct callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc/generic.c:proc_seq_open
  - lib/dynamic_debug.c:ddebug_proc_open
  - drivers/base/power/wakeup.c:wakeup_sources_stats_open
```
**Symbols:**

```
ffffffff814e7f70-ffffffff814e7f93: seq_open_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int seq_open_private(struct file *filp, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8151be00)
Location: fs/seq_file.c:656
Inline: False
Direct callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc/generic.c:proc_seq_open
  - lib/dynamic_debug.c:ddebug_proc_open
  - drivers/base/power/wakeup.c:wakeup_sources_stats_open
```
**Symbols:**

```
ffffffff8151be00-ffffffff8151be23: seq_open_private (STB_GLOBAL)
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
int seq_open_private(struct file *filp, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffff8000103bc600)
Location: fs/seq_file.c:650
Inline: False
Direct callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc/generic.c:proc_seq_open
  - lib/dynamic_debug.c:ddebug_proc_open
  - drivers/base/power/wakeup.c:wakeup_sources_stats_open
```
**Symbols:**

```
ffff8000103bc600-ffff8000103bc650: seq_open_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int seq_open_private(struct file *filp, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (c0599d58)
Location: fs/seq_file.c:650
Inline: False
Direct callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc/generic.c:proc_seq_open
  - lib/dynamic_debug.c:ddebug_proc_open
  - drivers/base/power/wakeup.c:wakeup_sources_stats_open
```
**Symbols:**

```
c0599d58-c0599d80: seq_open_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int seq_open_private(struct file *filp, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (c0000000004b9ed0)
Location: fs/seq_file.c:650
Inline: False
Direct callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc/generic.c:proc_seq_open
  - lib/dynamic_debug.c:ddebug_proc_open
  - drivers/base/power/wakeup.c:wakeup_sources_stats_open
```
**Symbols:**

```
c0000000004b9ed0-c0000000004b9f10: seq_open_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int seq_open_private(struct file *filp, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffe00027de76)
Location: fs/seq_file.c:650
Inline: False
Direct callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc/generic.c:proc_seq_open
  - lib/dynamic_debug.c:ddebug_proc_open
```
**Symbols:**

```
ffffffe00027de76-ffffffe00027deb8: seq_open_private (STB_GLOBAL)
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
int seq_open_private(struct file *filp, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81300ea0)
Location: fs/seq_file.c:650
Inline: False
Direct callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc/generic.c:proc_seq_open
  - lib/dynamic_debug.c:ddebug_proc_open
  - drivers/base/power/wakeup.c:wakeup_sources_stats_open
```
**Symbols:**

```
ffffffff81300ea0-ffffffff81300eb9: seq_open_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int seq_open_private(struct file *filp, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812f1ac0)
Location: fs/seq_file.c:650
Inline: False
Direct callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc/generic.c:proc_seq_open
  - lib/dynamic_debug.c:ddebug_proc_open
  - drivers/base/power/wakeup.c:wakeup_sources_stats_open
```
**Symbols:**

```
ffffffff812f1ac0-ffffffff812f1ad9: seq_open_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int seq_open_private(struct file *filp, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812fec90)
Location: fs/seq_file.c:650
Inline: False
Direct callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc/generic.c:proc_seq_open
  - lib/dynamic_debug.c:ddebug_proc_open
  - drivers/base/power/wakeup.c:wakeup_sources_stats_open
```
**Symbols:**

```
ffffffff812fec90-ffffffff812feca9: seq_open_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int seq_open_private(struct file *filp, const struct seq_operations *ops, int psize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8130ffd0)
Location: fs/seq_file.c:650
Inline: False
Direct callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc/generic.c:proc_seq_open
  - lib/dynamic_debug.c:ddebug_proc_open
  - drivers/base/power/wakeup.c:wakeup_sources_stats_open
```
**Symbols:**

```
ffffffff8130ffd0-ffffffff8130ffe9: seq_open_private (STB_GLOBAL)
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
