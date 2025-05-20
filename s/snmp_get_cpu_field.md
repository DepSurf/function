# Function: <code>snmp_get_cpu_field</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
u64 snmp_get_cpu_field(void *mib, int cpu, int offt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81792e70)
Location: net/ipv4/af_inet.c:1448
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:snmp_fold_field
```
**Symbols:**

```
ffffffff81792e70-ffffffff81792e90: snmp_get_cpu_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
u64 snmp_get_cpu_field(void *mib, int cpu, int offt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff818016a6)
Location: net/ipv4/af_inet.c:1512
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:snmp_fold_field
```
**Symbols:**

```
ffffffff81800630-ffffffff81800650: snmp_get_cpu_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
u64 snmp_get_cpu_field(void *mib, int cpu, int offt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff818324b6)
Location: net/ipv4/af_inet.c:1526
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:snmp_fold_field
Direct callers:
  - net/ipv4/proc.c:snmp_seq_show
  - net/ipv4/proc.c:snmp_seq_show
  - net/ipv4/proc.c:snmp_seq_show
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
  - net/ipv6/proc.c:snmp6_seq_show_item
```
**Symbols:**

```
ffffffff81831580-ffffffff818315a0: snmp_get_cpu_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
u64 snmp_get_cpu_field(void *mib, int cpu, int offt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff818537c0)
Location: net/ipv4/af_inet.c:1547
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:snmp_fold_field
Direct callers:
  - net/ipv4/proc.c:snmp_seq_show
  - net/ipv4/proc.c:snmp_seq_show
  - net/ipv4/proc.c:snmp_seq_show
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
  - net/ipv6/proc.c:snmp6_seq_show_item
```
**Symbols:**

```
ffffffff81852b30-ffffffff81852b50: snmp_get_cpu_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
u64 snmp_get_cpu_field(void *mib, int cpu, int offt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff818d3644)
Location: net/ipv4/af_inet.c:1551
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:snmp_fold_field
Direct callers:
  - net/ipv4/proc.c:snmp_seq_show
  - net/ipv4/proc.c:snmp_seq_show
  - net/ipv4/proc.c:snmp_seq_show
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
  - net/ipv6/proc.c:snmp6_seq_show_item
```
**Symbols:**

```
ffffffff818d2940-ffffffff818d2960: snmp_get_cpu_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
u64 snmp_get_cpu_field(void *mib, int cpu, int offt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81929b2a)
Location: net/ipv4/af_inet.c:1620
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:snmp_fold_field
Direct callers:
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
```
**Symbols:**

```
ffffffff81928f00-ffffffff81928f20: snmp_get_cpu_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
u64 snmp_get_cpu_field(void *mib, int cpu, int offt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff8195911a)
Location: net/ipv4/af_inet.c:1629
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:snmp_fold_field
Direct callers:
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
```
**Symbols:**

```
ffffffff819581f0-ffffffff81958210: snmp_get_cpu_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
u64 snmp_get_cpu_field(void *mib, int cpu, int offt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff819bdbe5)
Location: net/ipv4/af_inet.c:1644
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:snmp_fold_field
Direct callers:
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
```
**Symbols:**

```
ffffffff819bcd10-ffffffff819bcd30: snmp_get_cpu_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
u64 snmp_get_cpu_field(void *mib, int cpu, int offt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff819f47f5)
Location: net/ipv4/af_inet.c:1644
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:snmp_fold_field
Direct callers:
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
```
**Symbols:**

```
ffffffff819f3930-ffffffff819f3950: snmp_get_cpu_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
u64 snmp_get_cpu_field(void *mib, int cpu, int offt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81ae2505)
Location: net/ipv4/af_inet.c:1676
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:snmp_fold_field
Direct callers:
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
```
**Symbols:**

```
ffffffff81ae1bf0-ffffffff81ae1c10: snmp_get_cpu_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
u64 snmp_get_cpu_field(void *mib, int cpu, int offt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81aef3a5)
Location: net/ipv4/af_inet.c:1668
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:snmp_fold_field
Direct callers:
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
```
**Symbols:**

```
ffffffff81aeea70-ffffffff81aeea90: snmp_get_cpu_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u64 snmp_get_cpu_field(void *mib, int cpu, int offt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81adaaf8)
Location: net/ipv4/af_inet.c:1669
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:snmp_fold_field
Direct callers:
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/proc.c:netstat_seq_show
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
```
**Symbols:**

```
ffffffff81ada1a0-ffffffff81ada1c0: snmp_get_cpu_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
u64 snmp_get_cpu_field(void *mib, int cpu, int offt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81b99d44)
Location: net/ipv4/af_inet.c:1674
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:snmp_fold_field
Direct callers:
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/proc.c:netstat_seq_show
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
```
**Symbols:**

```
ffffffff81b992f0-ffffffff81b99341: snmp_get_cpu_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81d2bd20)
Location: include/net/ip.h:296
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:snmp_fold_field
```
```
In net/ipv4/proc.c (ffffffff81d4f93f)
Location: include/net/ip.h:296
Inline: True
Inline callers:
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/proc.c:netstat_seq_show
```
```
In net/xfrm/xfrm_proc.c (ffffffff81d7a76e)
Location: include/net/ip.h:296
Inline: True
Inline callers:
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
```
```
In net/ipv6/addrconf.c (ffffffff81d8e97d)
Location: include/net/ip.h:296
Inline: True
```
```
In net/ipv6/proc.c (ffffffff81de2721)
Location: include/net/ip.h:296
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_seq_show_item
```
```
In net/mptcp/mib.c (ffffffff81e2dd6f)
Location: include/net/ip.h:296
Inline: True
Inline callers:
  - net/mptcp/mib.c:mptcp_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81ef4cdd)
Location: include/net/ip.h:296
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:snmp_fold_field
```
```
In net/ipv4/proc.c (ffffffff81f19b50)
Location: include/net/ip.h:296
Inline: True
Inline callers:
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/proc.c:netstat_seq_show
```
```
In net/xfrm/xfrm_proc.c (ffffffff81f47696)
Location: include/net/ip.h:296
Inline: True
Inline callers:
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
```
```
In net/ipv6/addrconf.c (ffffffff81f5d402)
Location: include/net/ip.h:296
Inline: True
```
```
In net/ipv6/proc.c (ffffffff81fb4fec)
Location: include/net/ip.h:296
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_seq_show_item
```
```
In net/mptcp/mib.c (ffffffff82006334)
Location: include/net/ip.h:296
Inline: True
Inline callers:
  - net/mptcp/mib.c:mptcp_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81f5417d)
Location: include/net/ip.h:304
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:snmp_fold_field
```
```
In net/ipv4/proc.c (ffffffff81f7a230)
Location: include/net/ip.h:304
Inline: True
Inline callers:
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/proc.c:netstat_seq_show
```
```
In net/xfrm/xfrm_proc.c (ffffffff81fa7168)
Location: include/net/ip.h:304
Inline: True
Inline callers:
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
```
```
In net/ipv6/addrconf.c (ffffffff81fbd123)
Location: include/net/ip.h:304
Inline: True
```
```
In net/ipv6/proc.c (ffffffff8201573d)
Location: include/net/ip.h:304
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_seq_show_item
```
```
In net/mptcp/mib.c (ffffffff820826bf)
Location: include/net/ip.h:304
Inline: True
Inline callers:
  - net/mptcp/mib.c:mptcp_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff8201a3cd)
Location: include/net/ip.h:305
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:snmp_fold_field
```
```
In net/ipv4/proc.c (ffffffff82040928)
Location: include/net/ip.h:305
Inline: True
Inline callers:
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/proc.c:netstat_seq_show
```
```
In net/xfrm/xfrm_proc.c (ffffffff82074418)
Location: include/net/ip.h:305
Inline: True
Inline callers:
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
```
```
In net/ipv6/addrconf.c (ffffffff8208a553)
Location: include/net/ip.h:305
Inline: True
```
```
In net/ipv6/proc.c (ffffffff820e487d)
Location: include/net/ip.h:305
Inline: True
Inline callers:
  - net/ipv6/proc.c:snmp6_seq_show_item
```
```
In net/mptcp/mib.c (ffffffff82157d2f)
Location: include/net/ip.h:305
Inline: True
Inline callers:
  - net/mptcp/mib.c:mptcp_seq_show
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
u64 snmp_get_cpu_field(void *mib, int cpu, int offt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffff800010caa70c)
Location: net/ipv4/af_inet.c:1644
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:snmp_fold_field
Direct callers:
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
```
**Symbols:**

```
ffff800010ca9cf8-ffff800010ca9d44: snmp_get_cpu_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
u64 snmp_get_cpu_field(void *mib, int cpu, int offt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (c0db6ddc)
Location: net/ipv4/af_inet.c:1644
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:snmp_fold_field
Direct callers:
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
```
**Symbols:**

```
c0db6378-c0db63a8: snmp_get_cpu_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
u64 snmp_get_cpu_field(void *mib, int cpu, int offt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (c000000000dc0830)
Location: net/ipv4/af_inet.c:1644
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:snmp_fold_field
Direct callers:
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
```
**Symbols:**

```
c000000000dbf1d0-c000000000dbf200: snmp_get_cpu_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
u64 snmp_get_cpu_field(void *mib, int cpu, int offt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffe00080547e)
Location: net/ipv4/af_inet.c:1644
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:snmp_fold_field
Direct callers:
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
```
**Symbols:**

```
ffffffe0008046d4-ffffffe00080471c: snmp_get_cpu_field (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
u64 snmp_get_cpu_field(void *mib, int cpu, int offt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81994595)
Location: net/ipv4/af_inet.c:1644
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:snmp_fold_field
Direct callers:
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
```
**Symbols:**

```
ffffffff819936d0-ffffffff819936f0: snmp_get_cpu_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
u64 snmp_get_cpu_field(void *mib, int cpu, int offt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff8194e055)
Location: net/ipv4/af_inet.c:1644
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:snmp_fold_field
Direct callers:
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
```
**Symbols:**

```
ffffffff8194d190-ffffffff8194d1b0: snmp_get_cpu_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
u64 snmp_get_cpu_field(void *mib, int cpu, int offt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff819fee35)
Location: net/ipv4/af_inet.c:1644
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:snmp_fold_field
Direct callers:
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
```
**Symbols:**

```
ffffffff819fdf70-ffffffff819fdf90: snmp_get_cpu_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
u64 snmp_get_cpu_field(void *mib, int cpu, int offt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81a08f05)
Location: net/ipv4/af_inet.c:1644
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:snmp_fold_field
Direct callers:
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
```
**Symbols:**

```
ffffffff81a08300-ffffffff81a08320: snmp_get_cpu_field (STB_GLOBAL)
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
