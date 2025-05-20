# Function: <code>seq_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int seq_write(struct seq_file *seq, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81231090)
Location: fs/seq_file.c:734
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_auxv
  - lib/seq_buf.c:seq_buf_print_seq
  - net/ipv4/route.c:rt_acct_proc_show
```
**Symbols:**

```
ffffffff81231090-ffffffff812310d3: seq_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int seq_write(struct seq_file *seq, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812593a0)
Location: fs/seq_file.c:737
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_auxv
  - lib/seq_buf.c:seq_buf_print_seq
  - net/ipv4/route.c:rt_acct_proc_show
```
**Symbols:**

```
ffffffff812593a0-ffffffff812593e3: seq_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int seq_write(struct seq_file *seq, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8126c850)
Location: fs/seq_file.c:775
Inline: False
Direct callers:
  - fs/proc/meminfo.c:show_val_kb
  - fs/proc/meminfo.c:show_val_kb
  - fs/proc/meminfo.c:show_val_kb
  - fs/proc/meminfo.c:show_val_kb
  - lib/seq_buf.c:seq_buf_print_seq
  - net/ipv4/route.c:rt_acct_proc_show
```
**Symbols:**

```
ffffffff8126c850-ffffffff8126c893: seq_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int seq_write(struct seq_file *seq, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8127a410)
Location: fs/seq_file.c:761
Inline: False
Direct callers:
  - fs/proc/meminfo.c:show_val_kb
  - fs/proc/meminfo.c:show_val_kb
  - fs/proc/meminfo.c:show_val_kb
  - fs/proc/meminfo.c:show_val_kb
  - drivers/char/tpm/tpm2_eventlog.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/tpm2_eventlog.c:tpm2_binary_bios_measurements_show
  - net/ipv4/route.c:rt_acct_proc_show
  - lib/seq_buf.c:seq_buf_print_seq
```
**Symbols:**

```
ffffffff8127a410-ffffffff8127a453: seq_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int seq_write(struct seq_file *seq, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8129ce90)
Location: fs/seq_file.c:765
Inline: False
Direct callers:
  - fs/proc/meminfo.c:show_val_kb
  - fs/proc/meminfo.c:show_val_kb
  - fs/proc/meminfo.c:show_val_kb
  - fs/proc/meminfo.c:show_val_kb
  - drivers/char/tpm/tpm2_eventlog.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/tpm2_eventlog.c:tpm2_binary_bios_measurements_show
  - net/ipv4/route.c:rt_acct_proc_show
  - lib/seq_buf.c:seq_buf_print_seq
```
**Symbols:**

```
ffffffff8129ce90-ffffffff8129ced3: seq_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int seq_write(struct seq_file *seq, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812c3180)
Location: fs/seq_file.c:823
Inline: False
Direct callers:
  - fs/proc/meminfo.c:show_val_kb
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - net/ipv4/route.c:rt_acct_proc_show
  - lib/seq_buf.c:seq_buf_print_seq
```
**Symbols:**

```
ffffffff812c3180-ffffffff812c31c3: seq_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int seq_write(struct seq_file *seq, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812d80f0)
Location: fs/seq_file.c:811
Inline: False
Direct callers:
  - fs/proc/meminfo.c:show_val_kb
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - net/ipv4/route.c:rt_acct_proc_show
  - lib/seq_buf.c:seq_buf_print_seq
```
**Symbols:**

```
ffffffff812d80f0-ffffffff812d8133: seq_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int seq_write(struct seq_file *seq, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812f6600)
Location: fs/seq_file.c:823
Inline: False
Direct callers:
  - fs/proc/meminfo.c:show_val_kb
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - net/ipv4/route.c:rt_acct_proc_show
  - lib/seq_buf.c:seq_buf_print_seq
```
**Symbols:**

```
ffffffff812f6600-ffffffff812f6643: seq_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int seq_write(struct seq_file *seq, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff813081d0)
Location: fs/seq_file.c:823
Inline: False
Direct callers:
  - fs/proc/meminfo.c:show_val_kb
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - net/ipv4/route.c:rt_acct_proc_show
  - lib/seq_buf.c:seq_buf_print_seq
```
**Symbols:**

```
ffffffff813081d0-ffffffff81308213: seq_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int seq_write(struct seq_file *seq, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff813415b0)
Location: fs/seq_file.c:799
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_seq_write
  - fs/proc/array.c:proc_pid_statm
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
  - fs/proc/stat.c:show_all_irqs
  - fs/proc/stat.c:show_all_irqs
  - lib/seq_buf.c:seq_buf_print_seq
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - net/ipv4/route.c:rt_acct_proc_show
```
**Symbols:**

```
ffffffff813415b0-ffffffff813415f3: seq_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int seq_write(struct seq_file *seq, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8134d620)
Location: fs/seq_file.c:815
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_seq_write
  - fs/proc/array.c:proc_pid_statm
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
  - fs/proc/stat.c:show_all_irqs
  - fs/proc/stat.c:show_all_irqs
  - lib/seq_buf.c:seq_buf_print_seq
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - net/ipv4/route.c:rt_acct_proc_show
```
**Symbols:**

```
ffffffff8134d620-ffffffff8134d663: seq_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int seq_write(struct seq_file *seq, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff813541d0)
Location: fs/seq_file.c:837
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_seq_write
  - fs/proc/array.c:proc_pid_statm
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
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - lib/seq_buf.c:seq_buf_print_seq
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - net/ipv4/route.c:rt_acct_proc_show
```
**Symbols:**

```
ffffffff813541d0-ffffffff8135421b: seq_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int seq_write(struct seq_file *seq, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff813a2600)
Location: fs/seq_file.c:846
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_seq_write
  - fs/proc/array.c:proc_pid_statm
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
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - lib/seq_buf.c:seq_buf_print_seq
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - net/ipv4/route.c:rt_acct_proc_show
```
**Symbols:**

```
ffffffff813a2600-ffffffff813a264b: seq_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int seq_write(struct seq_file *seq, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81426200)
Location: fs/seq_file.c:830
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_seq_write
  - fs/proc/array.c:proc_pid_statm
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
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - lib/seq_buf.c:seq_buf_print_seq
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - net/ipv4/route.c:rt_acct_proc_show
```
**Symbols:**

```
ffffffff81426200-ffffffff81426252: seq_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int seq_write(struct seq_file *seq, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff814b2d10)
Location: fs/seq_file.c:830
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_seq_write
  - fs/proc/array.c:proc_pid_statm
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
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - net/ipv4/route.c:rt_acct_proc_show
  - lib/seq_buf.c:seq_buf_print_seq
```
**Symbols:**

```
ffffffff814b2d10-ffffffff814b2d62: seq_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int seq_write(struct seq_file *seq, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff814e7d60)
Location: fs/seq_file.c:830
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_seq_write
  - fs/proc/array.c:proc_pid_statm
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
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - net/ipv4/route.c:rt_acct_proc_show
  - lib/seq_buf.c:seq_buf_print_seq
```
**Symbols:**

```
ffffffff814e7d60-ffffffff814e7db2: seq_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int seq_write(struct seq_file *seq, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8151bbf0)
Location: fs/seq_file.c:830
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_seq_write
  - fs/proc/array.c:proc_pid_statm
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
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/gpu/drm/drm_edid.c:drm_edid_override_show
  - net/ipv4/route.c:rt_acct_proc_show
  - lib/seq_buf.c:seq_buf_print_seq
```
**Symbols:**

```
ffffffff8151bbf0-ffffffff8151bc42: seq_write (STB_GLOBAL)
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
int seq_write(struct seq_file *seq, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffff8000103bbd90)
Location: fs/seq_file.c:823
Inline: False
Direct callers:
  - fs/proc/meminfo.c:show_val_kb
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - net/ipv4/route.c:rt_acct_proc_show
  - lib/seq_buf.c:seq_buf_print_seq
```
**Symbols:**

```
ffff8000103bbd90-ffff8000103bbe08: seq_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int seq_write(struct seq_file *seq, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (c05994b0)
Location: fs/seq_file.c:823
Inline: False
Direct callers:
  - fs/proc/meminfo.c:show_val_kb
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/firmware/tegra/bpmp-debugfs.c:debugfs_show
  - net/ipv4/route.c:rt_acct_proc_show
  - lib/seq_buf.c:seq_buf_print_seq
```
**Symbols:**

```
c05994b0-c059950c: seq_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int seq_write(struct seq_file *seq, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (c0000000004b9340)
Location: fs/seq_file.c:823
Inline: False
Direct callers:
  - fs/proc/meminfo.c:show_val_kb
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - net/ipv4/route.c:rt_acct_proc_show
  - lib/seq_buf.c:seq_buf_print_seq
```
**Symbols:**

```
c0000000004b9340-c0000000004b93cc: seq_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int seq_write(struct seq_file *seq, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffe00027d7a0)
Location: fs/seq_file.c:823
Inline: False
Direct callers:
  - arch/riscv/kernel/cpu.c:c_show
  - arch/riscv/kernel/cpu.c:c_show
  - fs/proc/meminfo.c:show_val_kb
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - net/ipv4/route.c:rt_acct_proc_show
  - lib/seq_buf.c:seq_buf_print_seq
```
**Symbols:**

```
ffffffe00027d7a0-ffffffe00027d7f6: seq_write (STB_GLOBAL)
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
int seq_write(struct seq_file *seq, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff813007b0)
Location: fs/seq_file.c:823
Inline: False
Direct callers:
  - fs/proc/meminfo.c:show_val_kb
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - net/ipv4/route.c:rt_acct_proc_show
  - lib/seq_buf.c:seq_buf_print_seq
```
**Symbols:**

```
ffffffff813007b0-ffffffff813007f3: seq_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int seq_write(struct seq_file *seq, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812f13d0)
Location: fs/seq_file.c:823
Inline: False
Direct callers:
  - fs/proc/meminfo.c:show_val_kb
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - net/ipv4/route.c:rt_acct_proc_show
  - lib/seq_buf.c:seq_buf_print_seq
```
**Symbols:**

```
ffffffff812f13d0-ffffffff812f1413: seq_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int seq_write(struct seq_file *seq, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812fe5a0)
Location: fs/seq_file.c:823
Inline: False
Direct callers:
  - fs/proc/meminfo.c:show_val_kb
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - net/ipv4/route.c:rt_acct_proc_show
  - lib/seq_buf.c:seq_buf_print_seq
```
**Symbols:**

```
ffffffff812fe5a0-ffffffff812fe5e3: seq_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int seq_write(struct seq_file *seq, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8130f8e0)
Location: fs/seq_file.c:823
Inline: False
Direct callers:
  - fs/proc/meminfo.c:show_val_kb
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm2.c:tpm2_binary_bios_measurements_show
  - net/ipv4/route.c:rt_acct_proc_show
  - lib/seq_buf.c:seq_buf_print_seq
```
**Symbols:**

```
ffffffff8130f8e0-ffffffff8130f923: seq_write (STB_GLOBAL)
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
