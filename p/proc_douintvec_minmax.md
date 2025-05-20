# Function: <code>proc_douintvec_minmax</code>

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
int proc_douintvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff8108d880)
Location: kernel/sysctl.c:2635
Inline: False
```
**Symbols:**

```
ffffffff8108d880-ffffffff8108d8e7: proc_douintvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int proc_douintvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff81094190)
Location: kernel/sysctl.c:2626
Inline: False
```
**Symbols:**

```
ffffffff81094190-ffffffff810941f7: proc_douintvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int proc_douintvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff81097b80)
Location: kernel/sysctl.c:2649
Inline: False
```
**Symbols:**

```
ffffffff81097b80-ffffffff81097be7: proc_douintvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int proc_douintvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff8109fed0)
Location: kernel/sysctl.c:2706
Inline: False
```
**Symbols:**

```
ffffffff8109fed0-ffffffff8109ff37: proc_douintvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int proc_douintvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810a45d0)
Location: kernel/sysctl.c:2785
Inline: False
```
**Symbols:**

```
ffffffff810a45d0-ffffffff810a463c: proc_douintvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int proc_douintvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810aabb0)
Location: kernel/sysctl.c:2787
Inline: False
```
**Symbols:**

```
ffffffff810aabb0-ffffffff810aac1c: proc_douintvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int proc_douintvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810b2b50)
Location: kernel/sysctl.c:1028
Inline: False
```
**Symbols:**

```
ffffffff810b2b50-ffffffff810b2bba: proc_douintvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int proc_douintvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810ae380)
Location: kernel/sysctl.c:1027
Inline: False
```
**Symbols:**

```
ffffffff810ae380-ffffffff810ae3ea: proc_douintvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int proc_douintvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810b0690)
Location: kernel/sysctl.c:1039
Inline: False
```
**Symbols:**

```
ffffffff810b0690-ffffffff810b06fa: proc_douintvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int proc_douintvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810c1450)
Location: kernel/sysctl.c:1083
Inline: False
Direct callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_fields
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_fields
```
**Symbols:**

```
ffffffff810c1450-ffffffff810c14ba: proc_douintvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int proc_douintvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810d8b30)
Location: kernel/sysctl.c:952
Inline: False
Direct callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_fields
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_fields
```
**Symbols:**

```
ffffffff810d8b30-ffffffff810d8ba7: proc_douintvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int proc_douintvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810f8d10)
Location: kernel/sysctl.c:959
Inline: False
Direct callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_fields
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_fields
```
**Symbols:**

```
ffffffff810f8d10-ffffffff810f8d87: proc_douintvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int proc_douintvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff811050f0)
Location: kernel/sysctl.c:937
Inline: False
Direct callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_fields
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_fields
```
**Symbols:**

```
ffffffff811050f0-ffffffff81105167: proc_douintvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int proc_douintvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff8110ea40)
Location: kernel/sysctl.c:937
Inline: False
Direct callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_fields
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_fields
```
**Symbols:**

```
ffffffff8110ea40-ffffffff8110eab7: proc_douintvec_minmax (STB_GLOBAL)
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
int proc_douintvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffff800010103160)
Location: kernel/sysctl.c:2787
Inline: False
```
**Symbols:**

```
ffff800010103160-ffff8000101031f8: proc_douintvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int proc_douintvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (c035f1c0)
Location: kernel/sysctl.c:2787
Inline: False
```
**Symbols:**

```
c035f1c0-c035f254: proc_douintvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int proc_douintvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (c00000000014ae80)
Location: kernel/sysctl.c:2787
Inline: False
```
**Symbols:**

```
c00000000014ae80-c00000000014af18: proc_douintvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int proc_douintvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffe0000cab78)
Location: kernel/sysctl.c:2787
Inline: False
```
**Symbols:**

```
ffffffe0000cab78-ffffffe0000cabe0: proc_douintvec_minmax (STB_GLOBAL)
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
int proc_douintvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810a44d0)
Location: kernel/sysctl.c:2787
Inline: False
```
**Symbols:**

```
ffffffff810a44d0-ffffffff810a453c: proc_douintvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int proc_douintvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff81092eb0)
Location: kernel/sysctl.c:2787
Inline: False
```
**Symbols:**

```
ffffffff81092eb0-ffffffff81092f1c: proc_douintvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int proc_douintvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810a4480)
Location: kernel/sysctl.c:2787
Inline: False
```
**Symbols:**

```
ffffffff810a4480-ffffffff810a44ec: proc_douintvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int proc_douintvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810ac540)
Location: kernel/sysctl.c:2787
Inline: False
```
**Symbols:**

```
ffffffff810ac540-ffffffff810ac5ac: proc_douintvec_minmax (STB_GLOBAL)
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
