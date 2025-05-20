# Function: <code>seq_put_decimal_ull_width</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void seq_put_decimal_ull_width(struct seq_file *m, const char *delimiter, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812c3eb0)
Location: fs/seq_file.c:691
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ull
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/meminfo.c:show_val_kb
```
**Symbols:**

```
ffffffff812c3eb0-ffffffff812c3f70: seq_put_decimal_ull_width (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void seq_put_decimal_ull_width(struct seq_file *m, const char *delimiter, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812d90b0)
Location: fs/seq_file.c:679
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ull
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/meminfo.c:show_val_kb
```
**Symbols:**

```
ffffffff812d90b0-ffffffff812d9170: seq_put_decimal_ull_width (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void seq_put_decimal_ull_width(struct seq_file *m, const char *delimiter, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812f7630)
Location: fs/seq_file.c:691
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ull
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/meminfo.c:show_val_kb
```
**Symbols:**

```
ffffffff812f7630-ffffffff812f76ec: seq_put_decimal_ull_width (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void seq_put_decimal_ull_width(struct seq_file *m, const char *delimiter, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81309240)
Location: fs/seq_file.c:691
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ull
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/meminfo.c:show_val_kb
```
**Symbols:**

```
ffffffff81309240-ffffffff813092fc: seq_put_decimal_ull_width (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void seq_put_decimal_ull_width(struct seq_file *m, const char *delimiter, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81342720)
Location: fs/seq_file.c:667
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ull
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
```
**Symbols:**

```
ffffffff81342720-ffffffff813427ec: seq_put_decimal_ull_width (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void seq_put_decimal_ull_width(struct seq_file *m, const char *delimiter, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8134e970)
Location: fs/seq_file.c:683
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ull
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
```
**Symbols:**

```
ffffffff8134e970-ffffffff8134ea3c: seq_put_decimal_ull_width (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void seq_put_decimal_ull_width(struct seq_file *m, const char *delimiter, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81355570)
Location: fs/seq_file.c:705
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ull
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
```
**Symbols:**

```
ffffffff81355570-ffffffff81355635: seq_put_decimal_ull_width (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void seq_put_decimal_ull_width(struct seq_file *m, const char *delimiter, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff813a3990)
Location: fs/seq_file.c:714
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ull
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
```
**Symbols:**

```
ffffffff813a3990-ffffffff813a3a55: seq_put_decimal_ull_width (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void seq_put_decimal_ull_width(struct seq_file *m, const char *delimiter, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81427710)
Location: fs/seq_file.c:698
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ull
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
```
**Symbols:**

```
ffffffff81427710-ffffffff814277ff: seq_put_decimal_ull_width (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void seq_put_decimal_ull_width(struct seq_file *m, const char *delimiter, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff814b41f0)
Location: fs/seq_file.c:698
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ull
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
```
**Symbols:**

```
ffffffff814b41f0-ffffffff814b42df: seq_put_decimal_ull_width (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void seq_put_decimal_ull_width(struct seq_file *m, const char *delimiter, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff814e9290)
Location: fs/seq_file.c:698
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ull
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
```
**Symbols:**

```
ffffffff814e9290-ffffffff814e937f: seq_put_decimal_ull_width (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void seq_put_decimal_ull_width(struct seq_file *m, const char *delimiter, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8151d170)
Location: fs/seq_file.c:698
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ull
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
  - fs/proc/meminfo.c:meminfo_proc_show
```
**Symbols:**

```
ffffffff8151d170-ffffffff8151d25f: seq_put_decimal_ull_width (STB_GLOBAL)
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
void seq_put_decimal_ull_width(struct seq_file *m, const char *delimiter, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffff8000103bd340)
Location: fs/seq_file.c:691
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ull
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/meminfo.c:show_val_kb
```
**Symbols:**

```
ffff8000103bd340-ffff8000103bd42c: seq_put_decimal_ull_width (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void seq_put_decimal_ull_width(struct seq_file *m, const char *delimiter, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (c059a88c)
Location: fs/seq_file.c:691
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ull
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/meminfo.c:show_val_kb
```
**Symbols:**

```
c059a88c-c059a974: seq_put_decimal_ull_width (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void seq_put_decimal_ull_width(struct seq_file *m, const char *delimiter, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (c0000000004bade0)
Location: fs/seq_file.c:691
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ull
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/meminfo.c:show_val_kb
```
**Symbols:**

```
c0000000004bade0-c0000000004baf2c: seq_put_decimal_ull_width (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void seq_put_decimal_ull_width(struct seq_file *m, const char *delimiter, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffe00027e668)
Location: fs/seq_file.c:691
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ull
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/meminfo.c:show_val_kb
```
**Symbols:**

```
ffffffe00027e668-ffffffe00027e72e: seq_put_decimal_ull_width (STB_GLOBAL)
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
void seq_put_decimal_ull_width(struct seq_file *m, const char *delimiter, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81301820)
Location: fs/seq_file.c:691
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ull
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/meminfo.c:show_val_kb
```
**Symbols:**

```
ffffffff81301820-ffffffff813018dc: seq_put_decimal_ull_width (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void seq_put_decimal_ull_width(struct seq_file *m, const char *delimiter, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812f2440)
Location: fs/seq_file.c:691
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ull
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/meminfo.c:show_val_kb
```
**Symbols:**

```
ffffffff812f2440-ffffffff812f24fc: seq_put_decimal_ull_width (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void seq_put_decimal_ull_width(struct seq_file *m, const char *delimiter, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812ff610)
Location: fs/seq_file.c:691
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ull
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/meminfo.c:show_val_kb
```
**Symbols:**

```
ffffffff812ff610-ffffffff812ff6cc: seq_put_decimal_ull_width (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void seq_put_decimal_ull_width(struct seq_file *m, const char *delimiter, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81310950)
Location: fs/seq_file.c:691
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ull
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:__show_smap
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/task_mmu.c:task_mem
  - fs/proc/meminfo.c:show_val_kb
```
**Symbols:**

```
ffffffff81310950-ffffffff81310a0c: seq_put_decimal_ull_width (STB_GLOBAL)
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
