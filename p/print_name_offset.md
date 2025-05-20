# Function: <code>print_name_offset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
void print_name_offset(struct seq_file *m, void *sym);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff810f8cb0)
Location: kernel/time/timer_list.c:51
Inline: False
Direct callers:
  - kernel/time/timer_list.c:print_active_timers
  - kernel/time/timer_list.c:print_active_timers
  - kernel/time/timer_list.c:print_active_timers
  - kernel/time/timer_list.c:print_cpu
```
```
In kernel/time/timer_stats.c (ffffffff810ff040)
Location: kernel/time/timer_stats.c:270
Inline: False
Direct callers:
  - kernel/time/timer_stats.c:tstats_show
  - kernel/time/timer_stats.c:tstats_show
```
**Symbols:**

```
ffffffff810f8cb0-ffffffff810f8d35: print_name_offset (STB_LOCAL)
ffffffff810ff040-ffffffff810ff0c5: print_name_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
void print_name_offset(struct seq_file *m, void *sym);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff810fff30)
Location: kernel/time/timer_list.c:51
Inline: False
Direct callers:
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_active_timers
  - kernel/time/timer_list.c:print_active_timers
  - kernel/time/timer_list.c:print_active_timers
```
```
In kernel/time/timer_stats.c (ffffffff811063a0)
Location: kernel/time/timer_stats.c:270
Inline: False
Direct callers:
  - kernel/time/timer_stats.c:tstats_show
  - kernel/time/timer_stats.c:tstats_show
```
**Symbols:**

```
ffffffff810fff30-ffffffff810fffb5: print_name_offset (STB_LOCAL)
ffffffff811063a0-ffffffff81106425: print_name_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
void print_name_offset(struct seq_file *m, void *sym);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff81102d30)
Location: kernel/time/timer_list.c:51
Inline: False
Direct callers:
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_active_timers
  - kernel/time/timer_list.c:print_active_timers
  - kernel/time/timer_list.c:print_active_timers
```
```
In kernel/time/timer_stats.c (ffffffff8110db20)
Location: kernel/time/timer_stats.c:270
Inline: False
Direct callers:
  - kernel/time/timer_stats.c:tstats_show
  - kernel/time/timer_stats.c:tstats_show
```
**Symbols:**

```
ffffffff81102d30-ffffffff81102db5: print_name_offset (STB_LOCAL)
ffffffff8110db20-ffffffff8110dba5: print_name_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void print_name_offset(struct seq_file *m, void *sym);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff81104f20)
Location: kernel/time/timer_list.c:52
Inline: False
Direct callers:
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffff81104f20-ffffffff81104fa5: print_name_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void print_name_offset(struct seq_file *m, void *sym);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff81110080)
Location: kernel/time/timer_list.c:52
Inline: False
Direct callers:
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffff81110080-ffffffff81110105: print_name_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void print_name_offset(struct seq_file *m, void *sym);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff8111ba90)
Location: kernel/time/timer_list.c:50
Inline: False
Direct callers:
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffff8111ba90-ffffffff8111bb15: print_name_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void print_name_offset(struct seq_file *m, void *sym);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff81127240)
Location: kernel/time/timer_list.c:45
Inline: False
Direct callers:
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffff81127240-ffffffff811272c5: print_name_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void print_name_offset(struct seq_file *m, void *sym);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff81131c80)
Location: kernel/time/timer_list.c:45
Inline: False
Direct callers:
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffff81131c80-ffffffff81131d07: print_name_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void print_name_offset(struct seq_file *m, void *sym);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff8113dbd0)
Location: kernel/time/timer_list.c:45
Inline: False
Direct callers:
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffff8113dbd0-ffffffff8113dc57: print_name_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void print_name_offset(struct seq_file *m, void *sym);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff8114cd40)
Location: kernel/time/timer_list.c:45
Inline: False
Direct callers:
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_base
  - kernel/time/timer_list.c:print_active_timers
  - kernel/time/timer_list.c:print_active_timers
```
**Symbols:**

```
ffffffff8114cd40-ffffffff8114cdc7: print_name_offset (STB_LOCAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void print_name_offset(struct seq_file *m, void *sym);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffff8000101a7768)
Location: kernel/time/timer_list.c:45
Inline: False
Direct callers:
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_active_timers
  - kernel/time/timer_list.c:print_active_timers
```
**Symbols:**

```
ffff8000101a7768-ffff8000101a77fc: print_name_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void print_name_offset(struct seq_file *m, void *sym);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (c03f2ac4)
Location: kernel/time/timer_list.c:45
Inline: False
Direct callers:
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_tickdevice
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
c03f2ac4-c03f2b50: print_name_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void print_name_offset(struct seq_file *m, void *sym);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (c00000000020a4b0)
Location: kernel/time/timer_list.c:45
Inline: False
Direct callers:
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
c00000000020a4b0-c00000000020a560: print_name_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void print_name_offset(struct seq_file *m, void *sym);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffe0001336b4)
Location: kernel/time/timer_list.c:45
Inline: False
Direct callers:
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffe0001336b4-ffffffe000133722: print_name_offset (STB_LOCAL)
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
void print_name_offset(struct seq_file *m, void *sym);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff81136380)
Location: kernel/time/timer_list.c:45
Inline: False
Direct callers:
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffff81136380-ffffffff81136407: print_name_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void print_name_offset(struct seq_file *m, void *sym);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff81128dd0)
Location: kernel/time/timer_list.c:45
Inline: False
Direct callers:
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffff81128dd0-ffffffff81128e57: print_name_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void print_name_offset(struct seq_file *m, void *sym);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff811340a0)
Location: kernel/time/timer_list.c:45
Inline: False
Direct callers:
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffff811340a0-ffffffff81134127: print_name_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void print_name_offset(struct seq_file *m, void *sym);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer_list.c (ffffffff81140ac0)
Location: kernel/time/timer_list.c:45
Inline: False
Direct callers:
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
  - kernel/time/timer_list.c:print_cpu
```
**Symbols:**

```
ffffffff81140ac0-ffffffff81140b47: print_name_offset (STB_LOCAL)
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
