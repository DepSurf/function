# Function: <code>__cgroup_bpf_run_filter_sysctl</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sysctl(struct ctl_table_header *head, struct ctl_table *table, int write, void *buf, size_t *pcount, loff_t *ppos, void **new_buf, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811f8600)
Location: kernel/bpf/cgroup.c:874
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffffffff811f8600-ffffffff811f88c1: __cgroup_bpf_run_filter_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sysctl(struct ctl_table_header *head, struct ctl_table *table, int write, void *buf, size_t *pcount, loff_t *ppos, void **new_buf, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81205470)
Location: kernel/bpf/cgroup.c:884
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffffffff81205470-ffffffff81205731: __cgroup_bpf_run_filter_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sysctl(struct ctl_table_header *head, struct ctl_table *table, int write, void **buf, size_t *pcount, loff_t *ppos, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8122e580)
Location: kernel/bpf/cgroup.c:1203
Inline: False
```
**Symbols:**

```
ffffffff8122e580-ffffffff8122e858: __cgroup_bpf_run_filter_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sysctl(struct ctl_table_header *head, struct ctl_table *table, int write, char **buf, size_t *pcount, loff_t *ppos, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81236af0)
Location: kernel/bpf/cgroup.c:1227
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffffffff81236af0-ffffffff81236dce: __cgroup_bpf_run_filter_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sysctl(struct ctl_table_header *head, struct ctl_table *table, int write, char **buf, size_t *pcount, loff_t *ppos, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8123ade0)
Location: kernel/bpf/cgroup.c:1231
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffffffff8123ade0-ffffffff8123b15d: __cgroup_bpf_run_filter_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sysctl(struct ctl_table_header *head, struct ctl_table *table, int write, char **buf, size_t *pcount, loff_t *ppos, enum cgroup_bpf_attach_type atype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81275970)
Location: kernel/bpf/cgroup.c:1261
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffffffff81275970-ffffffff81275c8e: __cgroup_bpf_run_filter_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sysctl(struct ctl_table_header *head, struct ctl_table *table, int write, char **buf, size_t *pcount, loff_t *ppos, enum cgroup_bpf_attach_type atype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812c53e0)
Location: kernel/bpf/cgroup.c:1442
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffffffff812c53e0-ffffffff812c572e: __cgroup_bpf_run_filter_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sysctl(struct ctl_table_header *head, struct ctl_table *table, int write, char **buf, size_t *pcount, loff_t *ppos, enum cgroup_bpf_attach_type atype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8132a920)
Location: kernel/bpf/cgroup.c:1681
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffffffff8132a920-ffffffff8132ac7b: __cgroup_bpf_run_filter_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sysctl(struct ctl_table_header *head, struct ctl_table *table, int write, char **buf, size_t *pcount, loff_t *ppos, enum cgroup_bpf_attach_type atype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8135aa60)
Location: kernel/bpf/cgroup.c:1681
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffffffff8135aa60-ffffffff8135adbb: __cgroup_bpf_run_filter_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sysctl(struct ctl_table_header *head, struct ctl_table *table, int write, char **buf, size_t *pcount, loff_t *ppos, enum cgroup_bpf_attach_type atype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81383650)
Location: kernel/bpf/cgroup.c:1696
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffffffff81383650-ffffffff813839ab: __cgroup_bpf_run_filter_sysctl (STB_GLOBAL)
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
int __cgroup_bpf_run_filter_sysctl(struct ctl_table_header *head, struct ctl_table *table, int write, void *buf, size_t *pcount, loff_t *ppos, void **new_buf, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffff80001028e010)
Location: kernel/bpf/cgroup.c:884
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffff80001028e010-ffff80001028e300: __cgroup_bpf_run_filter_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sysctl(struct ctl_table_header *head, struct ctl_table *table, int write, void *buf, size_t *pcount, loff_t *ppos, void **new_buf, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c04bdf98)
Location: kernel/bpf/cgroup.c:884
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
c04bdf98-c04be350: __cgroup_bpf_run_filter_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sysctl(struct ctl_table_header *head, struct ctl_table *table, int write, void *buf, size_t *pcount, loff_t *ppos, void **new_buf, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c00000000033aa20)
Location: kernel/bpf/cgroup.c:884
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
c00000000033aa20-c00000000033ade0: __cgroup_bpf_run_filter_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sysctl(struct ctl_table_header *head, struct ctl_table *table, int write, void *buf, size_t *pcount, loff_t *ppos, void **new_buf, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffe0001c0b68)
Location: kernel/bpf/cgroup.c:884
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffffffe0001c0b68-ffffffe0001c0de2: __cgroup_bpf_run_filter_sysctl (STB_GLOBAL)
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
int __cgroup_bpf_run_filter_sysctl(struct ctl_table_header *head, struct ctl_table *table, int write, void *buf, size_t *pcount, loff_t *ppos, void **new_buf, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fda90)
Location: kernel/bpf/cgroup.c:884
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffffffff811fda90-ffffffff811fdd51: __cgroup_bpf_run_filter_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sysctl(struct ctl_table_header *head, struct ctl_table *table, int write, void *buf, size_t *pcount, loff_t *ppos, void **new_buf, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811f07e0)
Location: kernel/bpf/cgroup.c:884
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffffffff811f07e0-ffffffff811f0aa1: __cgroup_bpf_run_filter_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sysctl(struct ctl_table_header *head, struct ctl_table *table, int write, void *buf, size_t *pcount, loff_t *ppos, void **new_buf, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fb860)
Location: kernel/bpf/cgroup.c:884
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffffffff811fb860-ffffffff811fbb21: __cgroup_bpf_run_filter_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sysctl(struct ctl_table_header *head, struct ctl_table *table, int write, void *buf, size_t *pcount, loff_t *ppos, void **new_buf, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8120a410)
Location: kernel/bpf/cgroup.c:884
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffffffff8120a410-ffffffff8120a6ea: __cgroup_bpf_run_filter_sysctl (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>void **new_buf</code>
</li>
<li>
<b>Param reordered. </b>
<code>head, table, write, buf, pcount, ppos, new_buf, type</code> ➡️ <code>head, table, write, buf, pcount, ppos, type</code>
</li>
<li>
<b>Param type changed. </b>
<code>void *buf</code> ➡️ <code>void **buf</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void **buf</code> ➡️ <code>char **buf</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum cgroup_bpf_attach_type atype</code>
</li>
<li>
<b>Param removed. </b>
<code>enum bpf_attach_type type</code>
</li>
</ul>
</details>
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
