# Function: <code>__do_proc_dointvec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __do_proc_dointvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(bool *, long unsigned int *, int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff81088770)
Location: kernel/sysctl.c:2068
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
  - kernel/sysctl.c:proc_dointvec_jiffies
  - kernel/sysctl.c:proc_dointvec_userhz_jiffies
  - kernel/sysctl.c:proc_dointvec_ms_jiffies
```
**Symbols:**

```
ffffffff81088770-ffffffff81088b9d: __do_proc_dointvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __do_proc_dointvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(bool *, long unsigned int *, int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff8108b180)
Location: kernel/sysctl.c:2203
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sysctl.c:proc_dointvec_ms_jiffies
  - kernel/sysctl.c:proc_dointvec_userhz_jiffies
  - kernel/sysctl.c:proc_dointvec_jiffies
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
  - kernel/sysctl.c:proc_douintvec
  - kernel/sysctl.c:moksbstate_disabled_proc_handler
  - kernel/sysctl.c:secure_boot_proc_handler
```
**Symbols:**

```
ffffffff8108b180-ffffffff8108b535: __do_proc_dointvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __do_proc_dointvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(bool *, long unsigned int *, int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810900d0)
Location: kernel/sysctl.c:2188
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sysctl.c:proc_dointvec_ms_jiffies
  - kernel/sysctl.c:proc_dointvec_userhz_jiffies
  - kernel/sysctl.c:proc_dointvec_jiffies
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
  - kernel/sysctl.c:proc_douintvec
  - kernel/sysctl.c:moksbstate_disabled_proc_handler
  - kernel/sysctl.c:secure_boot_proc_handler
```
**Symbols:**

```
ffffffff810900d0-ffffffff81090485: __do_proc_dointvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __do_proc_dointvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(bool *, long unsigned int *, int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff8108d8f0)
Location: kernel/sysctl.c:2214
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sysctl.c:proc_dointvec_ms_jiffies
  - kernel/sysctl.c:proc_dointvec_userhz_jiffies
  - kernel/sysctl.c:proc_dointvec_jiffies
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
```
**Symbols:**

```
ffffffff8108d8f0-ffffffff8108dcdd: __do_proc_dointvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __do_proc_dointvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(bool *, long unsigned int *, int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff81094260)
Location: kernel/sysctl.c:2204
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sysctl.c:proc_dointvec_ms_jiffies
  - kernel/sysctl.c:proc_dointvec_userhz_jiffies
  - kernel/sysctl.c:proc_dointvec_jiffies
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
```
**Symbols:**

```
ffffffff81094260-ffffffff81094651: __do_proc_dointvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __do_proc_dointvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(bool *, long unsigned int *, int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff81097bf0)
Location: kernel/sysctl.c:2209
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sysctl.c:proc_dointvec_ms_jiffies
  - kernel/sysctl.c:proc_dointvec_userhz_jiffies
  - kernel/sysctl.c:proc_dointvec_jiffies
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
```
**Symbols:**

```
ffffffff81097bf0-ffffffff81097fdb: __do_proc_dointvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __do_proc_dointvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(bool *, long unsigned int *, int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff8109ff40)
Location: kernel/sysctl.c:2257
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sysctl.c:proc_dointvec_ms_jiffies
  - kernel/sysctl.c:proc_dointvec_userhz_jiffies
  - kernel/sysctl.c:proc_dointvec_jiffies
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
```
**Symbols:**

```
ffffffff8109ff40-ffffffff810a02ee: __do_proc_dointvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __do_proc_dointvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(bool *, long unsigned int *, int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810a4640)
Location: kernel/sysctl.c:2343
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sysctl.c:proc_dointvec_ms_jiffies
  - kernel/sysctl.c:proc_dointvec_userhz_jiffies
  - kernel/sysctl.c:proc_dointvec_jiffies
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
```
**Symbols:**

```
ffffffff810a4640-ffffffff810a4a2b: __do_proc_dointvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __do_proc_dointvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(bool *, long unsigned int *, int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810aac20)
Location: kernel/sysctl.c:2345
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sysctl.c:proc_dointvec_ms_jiffies
  - kernel/sysctl.c:proc_dointvec_userhz_jiffies
  - kernel/sysctl.c:proc_dointvec_jiffies
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
```
**Symbols:**

```
ffffffff810aac20-ffffffff810ab00b: __do_proc_dointvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __do_proc_dointvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(bool *, long unsigned int *, int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:571
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sysctl.c:proc_dointvec_ms_jiffies
  - kernel/sysctl.c:proc_dointvec_userhz_jiffies
  - kernel/sysctl.c:proc_dointvec_jiffies
  - kernel/sysctl.c:sysrq_sysctl_handler
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
  - kernel/sysctl.c:proc_dointvec_minmax_warn_RT_change
  - kernel/sysctl.c:proc_dointvec
  - kernel/sysctl.c:bpf_stats_handler
  - kernel/sysctl.c:bpf_stats_handler
```
**Symbols:**

```
ffffffff810b3150-ffffffff810b3496: __do_proc_dointvec (STB_LOCAL)
ffffffff810b3d4f-ffffffff810b3da7: __do_proc_dointvec.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __do_proc_dointvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(bool *, long unsigned int *, int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:570
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sysctl.c:proc_dointvec_ms_jiffies
  - kernel/sysctl.c:proc_dointvec_userhz_jiffies
  - kernel/sysctl.c:proc_dointvec_jiffies
  - kernel/sysctl.c:sysrq_sysctl_handler
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
  - kernel/sysctl.c:proc_dointvec_minmax_warn_RT_change
  - kernel/sysctl.c:proc_dointvec
  - kernel/sysctl.c:bpf_stats_handler
  - kernel/sysctl.c:bpf_stats_handler
```
**Symbols:**

```
ffffffff810ae980-ffffffff810aecc6: __do_proc_dointvec (STB_LOCAL)
ffffffff81bdb98b-ffffffff81bdb9e3: __do_proc_dointvec.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __do_proc_dointvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(bool *, long unsigned int *, int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:582
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sysctl.c:proc_dointvec_ms_jiffies
  - kernel/sysctl.c:proc_dointvec_userhz_jiffies
  - kernel/sysctl.c:proc_dointvec_jiffies
  - kernel/sysctl.c:sysrq_sysctl_handler
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
  - kernel/sysctl.c:proc_dointvec_minmax_warn_RT_change
  - kernel/sysctl.c:proc_dointvec
  - kernel/sysctl.c:bpf_unpriv_handler
  - kernel/sysctl.c:bpf_unpriv_handler
  - kernel/sysctl.c:bpf_stats_handler
  - kernel/sysctl.c:bpf_stats_handler
```
**Symbols:**

```
ffffffff810af910-ffffffff810afcb4: __do_proc_dointvec (STB_LOCAL)
ffffffff81bcda1b-ffffffff81bcda56: __do_proc_dointvec.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __do_proc_dointvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(bool *, long unsigned int *, int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:606
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sysctl.c:proc_dointvec_ms_jiffies
  - kernel/sysctl.c:proc_dointvec_userhz_jiffies
  - kernel/sysctl.c:proc_dointvec_jiffies
  - kernel/sysctl.c:sysrq_sysctl_handler
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
  - kernel/sysctl.c:proc_dointvec_minmax_warn_RT_change
  - kernel/sysctl.c:proc_dointvec
  - kernel/sysctl.c:proc_dobool
  - kernel/sysctl.c:bpf_unpriv_handler
  - kernel/sysctl.c:bpf_unpriv_handler
  - kernel/sysctl.c:bpf_stats_handler
  - kernel/sysctl.c:bpf_stats_handler
```
**Symbols:**

```
ffffffff810c0a30-ffffffff810c0dd1: __do_proc_dointvec (STB_LOCAL)
ffffffff81ca4453-ffffffff81ca446e: __do_proc_dointvec.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __do_proc_dointvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(bool *, long unsigned int *, int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:486
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sysctl.c:proc_dointvec_ms_jiffies
  - kernel/sysctl.c:proc_dointvec_userhz_jiffies
  - kernel/sysctl.c:proc_dointvec_jiffies
  - kernel/sysctl.c:sysrq_sysctl_handler
  - kernel/sysctl.c:proc_dointvec_minmax_warn_RT_change
  - kernel/sysctl.c:proc_dointvec
  - kernel/sysctl.c:proc_dobool
```
**Symbols:**

```
ffffffff810d80b0-ffffffff810d849a: __do_proc_dointvec (STB_LOCAL)
ffffffff81e53ce7-ffffffff81e53d02: __do_proc_dointvec.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __do_proc_dointvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(bool *, long unsigned int *, int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:473
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sysctl.c:proc_dointvec_ms_jiffies
  - kernel/sysctl.c:proc_dointvec_userhz_jiffies
  - kernel/sysctl.c:proc_dointvec_ms_jiffies_minmax
  - kernel/sysctl.c:proc_dointvec_jiffies
  - kernel/sysctl.c:sysrq_sysctl_handler
  - kernel/sysctl.c:proc_dointvec_minmax_warn_RT_change
  - kernel/sysctl.c:proc_dobool
```
**Symbols:**

```
ffffffff810f8f10-ffffffff810f938d: __do_proc_dointvec (STB_LOCAL)
ffffffff82055ed7-ffffffff82055ef8: __do_proc_dointvec.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __do_proc_dointvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(bool *, long unsigned int *, int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:472
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sysctl.c:proc_dointvec_ms_jiffies
  - kernel/sysctl.c:proc_dointvec_userhz_jiffies
  - kernel/sysctl.c:proc_dointvec_ms_jiffies_minmax
  - kernel/sysctl.c:proc_dointvec_jiffies
  - kernel/sysctl.c:sysrq_sysctl_handler
  - kernel/sysctl.c:proc_dobool
```
**Symbols:**

```
ffffffff811052f0-ffffffff81105727: __do_proc_dointvec (STB_LOCAL)
ffffffff820d44c6-ffffffff820d44e1: __do_proc_dointvec.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __do_proc_dointvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(bool *, long unsigned int *, int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:472
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sysctl.c:proc_dointvec_ms_jiffies
  - kernel/sysctl.c:proc_dointvec_userhz_jiffies
  - kernel/sysctl.c:proc_dointvec_ms_jiffies_minmax
  - kernel/sysctl.c:proc_dointvec_jiffies
  - kernel/sysctl.c:sysrq_sysctl_handler
  - kernel/sysctl.c:proc_dobool
```
**Symbols:**

```
ffffffff8110ec40-ffffffff8110f077: __do_proc_dointvec (STB_LOCAL)
ffffffff821af3bf-ffffffff821af3da: __do_proc_dointvec.cold (STB_LOCAL)
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
int __do_proc_dointvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(bool *, long unsigned int *, int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffff8000101031f8)
Location: kernel/sysctl.c:2345
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sysctl.c:proc_dointvec_ms_jiffies
  - kernel/sysctl.c:proc_dointvec_userhz_jiffies
  - kernel/sysctl.c:proc_dointvec_jiffies
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
```
**Symbols:**

```
ffff8000101031f8-ffff800010103590: __do_proc_dointvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __do_proc_dointvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(bool *, long unsigned int *, int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (c035f254)
Location: kernel/sysctl.c:2345
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sysctl.c:proc_dointvec_ms_jiffies
  - kernel/sysctl.c:proc_dointvec_userhz_jiffies
  - kernel/sysctl.c:proc_dointvec_jiffies
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
```
**Symbols:**

```
c035f254-c035f628: __do_proc_dointvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __do_proc_dointvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(bool *, long unsigned int *, int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (c00000000014af20)
Location: kernel/sysctl.c:2345
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sysctl.c:proc_dointvec_ms_jiffies
  - kernel/sysctl.c:proc_dointvec_userhz_jiffies
  - kernel/sysctl.c:proc_dointvec_jiffies
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
```
**Symbols:**

```
c00000000014af20-c00000000014b3d4: __do_proc_dointvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __do_proc_dointvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(bool *, long unsigned int *, int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffe0000ca078)
Location: kernel/sysctl.c:2345
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sysctl.c:proc_dointvec_ms_jiffies
  - kernel/sysctl.c:proc_dointvec_userhz_jiffies
  - kernel/sysctl.c:proc_dointvec_jiffies
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
```
**Symbols:**

```
ffffffe0000ca078-ffffffe0000ca328: __do_proc_dointvec (STB_LOCAL)
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
int __do_proc_dointvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(bool *, long unsigned int *, int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810a4540)
Location: kernel/sysctl.c:2345
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sysctl.c:proc_dointvec_ms_jiffies
  - kernel/sysctl.c:proc_dointvec_userhz_jiffies
  - kernel/sysctl.c:proc_dointvec_jiffies
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
```
**Symbols:**

```
ffffffff810a4540-ffffffff810a492b: __do_proc_dointvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __do_proc_dointvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(bool *, long unsigned int *, int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff81092f20)
Location: kernel/sysctl.c:2345
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sysctl.c:proc_dointvec_ms_jiffies
  - kernel/sysctl.c:proc_dointvec_userhz_jiffies
  - kernel/sysctl.c:proc_dointvec_jiffies
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
```
**Symbols:**

```
ffffffff81092f20-ffffffff8109330b: __do_proc_dointvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __do_proc_dointvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(bool *, long unsigned int *, int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810a44f0)
Location: kernel/sysctl.c:2345
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sysctl.c:proc_dointvec_ms_jiffies
  - kernel/sysctl.c:proc_dointvec_userhz_jiffies
  - kernel/sysctl.c:proc_dointvec_jiffies
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
```
**Symbols:**

```
ffffffff810a44f0-ffffffff810a48db: __do_proc_dointvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __do_proc_dointvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(bool *, long unsigned int *, int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810ac5b0)
Location: kernel/sysctl.c:2345
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sysctl.c:proc_dointvec_ms_jiffies
  - kernel/sysctl.c:proc_dointvec_userhz_jiffies
  - kernel/sysctl.c:proc_dointvec_jiffies
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
```
**Symbols:**

```
ffffffff810ac5b0-ffffffff810ac99b: __do_proc_dointvec (STB_LOCAL)
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
