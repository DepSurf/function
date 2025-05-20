# Function: <code>seq_put_decimal_ull</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void seq_put_decimal_ull(struct seq_file *m, char delimiter, long long unsigned int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81231290)
Location: fs/seq_file.c:683
Inline: True
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff81231290-ffffffff81231304: seq_put_decimal_ull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void seq_put_decimal_ull(struct seq_file *m, char delimiter, long long unsigned int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812595a0)
Location: fs/seq_file.c:686
Inline: True
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff812595a0-ffffffff81259614: seq_put_decimal_ull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void seq_put_decimal_ull(struct seq_file *m, const char *delimiter, long long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8126c8a0)
Location: fs/seq_file.c:693
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_show
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff8126c8a0-ffffffff8126c95d: seq_put_decimal_ull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void seq_put_decimal_ull(struct seq_file *m, const char *delimiter, long long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8127a460)
Location: fs/seq_file.c:679
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_show
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff8127a460-ffffffff8127a518: seq_put_decimal_ull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void seq_put_decimal_ull(struct seq_file *m, const char *delimiter, long long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8129cee0)
Location: fs/seq_file.c:683
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_show
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff8129cee0-ffffffff8129cf98: seq_put_decimal_ull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void seq_put_decimal_ull(struct seq_file *m, const char *delimiter, long long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812c3f70)
Location: fs/seq_file.c:723
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_show
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff812c3f70-ffffffff812c3f82: seq_put_decimal_ull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void seq_put_decimal_ull(struct seq_file *m, const char *delimiter, long long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812d9170)
Location: fs/seq_file.c:711
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_show
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff812d9170-ffffffff812d9182: seq_put_decimal_ull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void seq_put_decimal_ull(struct seq_file *m, const char *delimiter, long long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812f76f0)
Location: fs/seq_file.c:723
Inline: False
Direct callers:
  - kernel/fork.c:pidfd_show_fdinfo
  - mm/vmstat.c:vmstat_show
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff812f76f0-ffffffff812f7702: seq_put_decimal_ull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void seq_put_decimal_ull(struct seq_file *m, const char *delimiter, long long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81309300)
Location: fs/seq_file.c:723
Inline: False
Direct callers:
  - kernel/fork.c:pidfd_show_fdinfo
  - mm/vmstat.c:vmstat_show
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff81309300-ffffffff81309312: seq_put_decimal_ull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void seq_put_decimal_ull(struct seq_file *m, const char *delimiter, long long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff813427f0)
Location: fs/seq_file.c:699
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_show
  - fs/io_uring.c:io_uring_show_cred
  - fs/io_uring.c:io_uring_show_cred
  - fs/io_uring.c:io_uring_show_cred
  - fs/io_uring.c:io_uring_show_cred
  - fs/io_uring.c:io_uring_show_cred
  - fs/io_uring.c:io_uring_show_cred
  - fs/io_uring.c:io_uring_show_cred
  - fs/io_uring.c:io_uring_show_cred
  - fs/io_uring.c:io_uring_show_cred
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_all_irqs
```
**Symbols:**

```
ffffffff813427f0-ffffffff81342802: seq_put_decimal_ull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void seq_put_decimal_ull(struct seq_file *m, const char *delimiter, long long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8134ea40)
Location: fs/seq_file.c:715
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_show
  - fs/io_uring.c:io_uring_show_cred
  - fs/io_uring.c:io_uring_show_cred
  - fs/io_uring.c:io_uring_show_cred
  - fs/io_uring.c:io_uring_show_cred
  - fs/io_uring.c:io_uring_show_cred
  - fs/io_uring.c:io_uring_show_cred
  - fs/io_uring.c:io_uring_show_cred
  - fs/io_uring.c:io_uring_show_cred
  - fs/io_uring.c:io_uring_show_cred
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:task_seccomp
  - fs/proc/array.c:task_seccomp
  - fs/proc/array.c:task_seccomp
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_all_irqs
```
**Symbols:**

```
ffffffff8134ea40-ffffffff8134ea52: seq_put_decimal_ull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void seq_put_decimal_ull(struct seq_file *m, const char *delimiter, long long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81355640)
Location: fs/seq_file.c:737
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_show
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:task_seccomp
  - fs/proc/array.c:task_seccomp
  - fs/proc/array.c:task_seccomp
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - drivers/base/power/domain.c:genpd_summary_one
```
**Symbols:**

```
ffffffff81355640-ffffffff81355652: seq_put_decimal_ull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void seq_put_decimal_ull(struct seq_file *m, const char *delimiter, long long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff813a3a60)
Location: fs/seq_file.c:746
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_show
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:task_seccomp
  - fs/proc/array.c:task_seccomp
  - fs/proc/array.c:task_seccomp
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - drivers/base/power/domain.c:genpd_summary_one
```
**Symbols:**

```
ffffffff813a3a60-ffffffff813a3a72: seq_put_decimal_ull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void seq_put_decimal_ull(struct seq_file *m, const char *delimiter, long long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81427800)
Location: fs/seq_file.c:730
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_show
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:task_seccomp
  - fs/proc/array.c:task_seccomp
  - fs/proc/array.c:task_seccomp
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - drivers/base/power/domain.c:genpd_summary_one
```
**Symbols:**

```
ffffffff81427800-ffffffff8142781e: seq_put_decimal_ull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void seq_put_decimal_ull(struct seq_file *m, const char *delimiter, long long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff814b42f0)
Location: fs/seq_file.c:730
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_show
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:task_seccomp
  - fs/proc/array.c:task_seccomp
  - fs/proc/array.c:task_seccomp
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - drivers/base/power/domain.c:genpd_summary_one
```
**Symbols:**

```
ffffffff814b42f0-ffffffff814b430e: seq_put_decimal_ull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void seq_put_decimal_ull(struct seq_file *m, const char *delimiter, long long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff814e9390)
Location: fs/seq_file.c:730
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_show
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:task_seccomp
  - fs/proc/array.c:task_seccomp
  - fs/proc/array.c:task_seccomp
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - drivers/base/power/domain.c:genpd_summary_one
```
**Symbols:**

```
ffffffff814e9390-ffffffff814e93ae: seq_put_decimal_ull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void seq_put_decimal_ull(struct seq_file *m, const char *delimiter, long long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8151d270)
Location: fs/seq_file.c:730
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_show
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:task_seccomp
  - fs/proc/array.c:task_seccomp
  - fs/proc/array.c:task_seccomp
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - drivers/pmdomain/core.c:genpd_summary_one
```
**Symbols:**

```
ffffffff8151d270-ffffffff8151d28e: seq_put_decimal_ull (STB_GLOBAL)
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
void seq_put_decimal_ull(struct seq_file *m, const char *delimiter, long long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffff8000103bd430)
Location: fs/seq_file.c:723
Inline: False
Direct callers:
  - kernel/fork.c:pidfd_show_fdinfo
  - mm/vmstat.c:vmstat_show
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffff8000103bd430-ffff8000103bd478: seq_put_decimal_ull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void seq_put_decimal_ull(struct seq_file *m, const char *delimiter, long long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (c059a974)
Location: fs/seq_file.c:723
Inline: False
Direct callers:
  - kernel/fork.c:pidfd_show_fdinfo
  - mm/vmstat.c:vmstat_show
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
c059a974-c059a9a0: seq_put_decimal_ull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void seq_put_decimal_ull(struct seq_file *m, const char *delimiter, long long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (c0000000004baf30)
Location: fs/seq_file.c:723
Inline: False
Direct callers:
  - kernel/fork.c:pidfd_show_fdinfo
  - mm/vmstat.c:vmstat_show
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
c0000000004baf30-c0000000004baf48: seq_put_decimal_ull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void seq_put_decimal_ull(struct seq_file *m, const char *delimiter, long long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffe00027e72e)
Location: fs/seq_file.c:723
Inline: False
Direct callers:
  - kernel/fork.c:pidfd_show_fdinfo
  - mm/vmstat.c:vmstat_show
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffe00027e72e-ffffffe00027e76a: seq_put_decimal_ull (STB_GLOBAL)
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
void seq_put_decimal_ull(struct seq_file *m, const char *delimiter, long long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff813018e0)
Location: fs/seq_file.c:723
Inline: False
Direct callers:
  - kernel/fork.c:pidfd_show_fdinfo
  - mm/vmstat.c:vmstat_show
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff813018e0-ffffffff813018f2: seq_put_decimal_ull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void seq_put_decimal_ull(struct seq_file *m, const char *delimiter, long long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812f2500)
Location: fs/seq_file.c:723
Inline: False
Direct callers:
  - kernel/fork.c:pidfd_show_fdinfo
  - mm/vmstat.c:vmstat_show
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff812f2500-ffffffff812f2512: seq_put_decimal_ull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void seq_put_decimal_ull(struct seq_file *m, const char *delimiter, long long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812ff6d0)
Location: fs/seq_file.c:723
Inline: False
Direct callers:
  - kernel/fork.c:pidfd_show_fdinfo
  - mm/vmstat.c:vmstat_show
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff812ff6d0-ffffffff812ff6e2: seq_put_decimal_ull (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void seq_put_decimal_ull(struct seq_file *m, const char *delimiter, long long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81310a10)
Location: fs/seq_file.c:723
Inline: False
Direct callers:
  - kernel/fork.c:pidfd_show_fdinfo
  - mm/vmstat.c:vmstat_show
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff81310a10-ffffffff81310a22: seq_put_decimal_ull (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char delimiter</code> ➡️ <code>const char *delimiter</code>
</li>
</ul>
</details>
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
