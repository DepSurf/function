# Function: <code>__do_proc_douintvec</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __do_proc_douintvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(long unsigned int *, unsigned int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff8108d5d0)
Location: kernel/sysctl.c:2399
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
```
**Symbols:**

```
ffffffff8108d5d0-ffffffff8108d846: __do_proc_douintvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __do_proc_douintvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(long unsigned int *, unsigned int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff81093ee0)
Location: kernel/sysctl.c:2389
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_dopipe_max_size
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
```
**Symbols:**

```
ffffffff81093ee0-ffffffff8109415a: __do_proc_douintvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __do_proc_douintvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(long unsigned int *, unsigned int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810978c0)
Location: kernel/sysctl.c:2394
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_dopipe_max_size
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
```
**Symbols:**

```
ffffffff810978c0-ffffffff81097b19: __do_proc_douintvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __do_proc_douintvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(long unsigned int *, unsigned int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff8109fc10)
Location: kernel/sysctl.c:2442
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_dopipe_max_size
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
```
**Symbols:**

```
ffffffff8109fc10-ffffffff8109fe69: __do_proc_douintvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __do_proc_douintvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(long unsigned int *, unsigned int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810a42d0)
Location: kernel/sysctl.c:2528
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_dopipe_max_size
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
```
**Symbols:**

```
ffffffff810a42d0-ffffffff810a4543: __do_proc_douintvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __do_proc_douintvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(long unsigned int *, unsigned int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810aa8b0)
Location: kernel/sysctl.c:2530
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_dopipe_max_size
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
```
**Symbols:**

```
ffffffff810aa8b0-ffffffff810aab23: __do_proc_douintvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __do_proc_douintvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(long unsigned int *, unsigned int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810b29f0)
Location: kernel/sysctl.c:742
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_dopipe_max_size
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
```
**Symbols:**

```
ffffffff810b29f0-ffffffff810b2b0e: __do_proc_douintvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __do_proc_douintvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(long unsigned int *, unsigned int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810ae220)
Location: kernel/sysctl.c:741
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_dopipe_max_size
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
```
**Symbols:**

```
ffffffff810ae220-ffffffff810ae33e: __do_proc_douintvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __do_proc_douintvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(long unsigned int *, unsigned int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:753
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_dopipe_max_size
  - kernel/sysctl.c:proc_dou8vec_minmax
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
```
**Symbols:**

```
ffffffff810b0430-ffffffff810b0643: __do_proc_douintvec (STB_LOCAL)
ffffffff81bcda67-ffffffff81bcdaa2: __do_proc_douintvec.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __do_proc_douintvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(long unsigned int *, unsigned int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:777
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_dopipe_max_size
  - kernel/sysctl.c:proc_dou8vec_minmax
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
```
**Symbols:**

```
ffffffff810c11f0-ffffffff810c140b: __do_proc_douintvec (STB_LOCAL)
ffffffff81ca44a4-ffffffff81ca44b8: __do_proc_douintvec.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __do_proc_douintvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(long unsigned int *, unsigned int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:657
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_dou8vec_minmax
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
```
**Symbols:**

```
ffffffff810d8860-ffffffff810d8ae3: __do_proc_douintvec (STB_LOCAL)
ffffffff81e53d02-ffffffff81e53d1e: __do_proc_douintvec.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __do_proc_douintvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(long unsigned int *, unsigned int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:644
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_dou8vec_minmax
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
```
**Symbols:**

```
ffffffff810f8a40-ffffffff810f8caa: __do_proc_douintvec (STB_LOCAL)
ffffffff82055ebb-ffffffff82055ed7: __do_proc_douintvec.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __do_proc_douintvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(long unsigned int *, unsigned int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:643
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_dou8vec_minmax
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
```
**Symbols:**

```
ffffffff81104e20-ffffffff8110508a: __do_proc_douintvec (STB_LOCAL)
ffffffff820d44aa-ffffffff820d44c6: __do_proc_douintvec.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __do_proc_douintvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(long unsigned int *, unsigned int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:643
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_dou8vec_minmax
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
```
**Symbols:**

```
ffffffff8110e770-ffffffff8110e9da: __do_proc_douintvec (STB_LOCAL)
ffffffff821af3a3-ffffffff821af3bf: __do_proc_douintvec.cold (STB_LOCAL)
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
int __do_proc_douintvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(long unsigned int *, unsigned int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffff800010102e00)
Location: kernel/sysctl.c:2530
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_dopipe_max_size
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
```
**Symbols:**

```
ffff800010102e00-ffff800010103080: __do_proc_douintvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __do_proc_douintvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(long unsigned int *, unsigned int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (c035ee70)
Location: kernel/sysctl.c:2530
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_dopipe_max_size
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
```
**Symbols:**

```
c035ee70-c035f110: __do_proc_douintvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __do_proc_douintvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(long unsigned int *, unsigned int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (c00000000014aa60)
Location: kernel/sysctl.c:2530
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_dopipe_max_size
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
```
**Symbols:**

```
c00000000014aa60-c00000000014ade0: __do_proc_douintvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __do_proc_douintvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(long unsigned int *, unsigned int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffe0000ca8de)
Location: kernel/sysctl.c:2530
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_dopipe_max_size
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
```
**Symbols:**

```
ffffffe0000ca8de-ffffffe0000caacc: __do_proc_douintvec (STB_LOCAL)
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
int __do_proc_douintvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(long unsigned int *, unsigned int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810a41d0)
Location: kernel/sysctl.c:2530
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_dopipe_max_size
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
```
**Symbols:**

```
ffffffff810a41d0-ffffffff810a4443: __do_proc_douintvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __do_proc_douintvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(long unsigned int *, unsigned int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff81092bb0)
Location: kernel/sysctl.c:2530
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_dopipe_max_size
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
```
**Symbols:**

```
ffffffff81092bb0-ffffffff81092e23: __do_proc_douintvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __do_proc_douintvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(long unsigned int *, unsigned int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810a4180)
Location: kernel/sysctl.c:2530
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_dopipe_max_size
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
```
**Symbols:**

```
ffffffff810a4180-ffffffff810a43f3: __do_proc_douintvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __do_proc_douintvec(void *tbl_data, struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos, int (*conv)(long unsigned int *, unsigned int *, int, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810ac240)
Location: kernel/sysctl.c:2530
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_dopipe_max_size
  - kernel/sysctl.c:proc_douintvec_minmax
  - kernel/sysctl.c:proc_douintvec
```
**Symbols:**

```
ffffffff810ac240-ffffffff810ac4b3: __do_proc_douintvec (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
