# Function: <code>sysctl_vm_numa_stat_handler</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sysctl_vm_numa_stat_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811f5460)
Location: mm/vmstat.c:77
Inline: False
```
**Symbols:**

```
ffffffff811f5460-ffffffff811f5612: sysctl_vm_numa_stat_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int sysctl_vm_numa_stat_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmstat.c (0)
Location: mm/vmstat.c:77
Inline: False
```
**Symbols:**

```
ffffffff81217454-ffffffff812174a7: sysctl_vm_numa_stat_handler.cold.19 (STB_LOCAL)
ffffffff81216740-ffffffff8121688f: sysctl_vm_numa_stat_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int sysctl_vm_numa_stat_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmstat.c (0)
Location: mm/vmstat.c:77
Inline: False
```
**Symbols:**

```
ffffffff8122a364-ffffffff8122a3b7: sysctl_vm_numa_stat_handler.cold.19 (STB_LOCAL)
ffffffff81229640-ffffffff81229792: sysctl_vm_numa_stat_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int sysctl_vm_numa_stat_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmstat.c (0)
Location: mm/vmstat.c:78
Inline: False
```
**Symbols:**

```
ffffffff81239fe4-ffffffff8123a037: sysctl_vm_numa_stat_handler.cold (STB_LOCAL)
ffffffff81239300-ffffffff8123944d: sysctl_vm_numa_stat_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int sysctl_vm_numa_stat_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmstat.c (0)
Location: mm/vmstat.c:78
Inline: False
```
**Symbols:**

```
ffffffff812482e4-ffffffff81248337: sysctl_vm_numa_stat_handler.cold (STB_LOCAL)
ffffffff81247610-ffffffff8124775d: sysctl_vm_numa_stat_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int sysctl_vm_numa_stat_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmstat.c (0)
Location: mm/vmstat.c:78
Inline: False
```
**Symbols:**

```
ffffffff8127646e-ffffffff812764c1: sysctl_vm_numa_stat_handler.cold (STB_LOCAL)
ffffffff812757f0-ffffffff8127593e: sysctl_vm_numa_stat_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int sysctl_vm_numa_stat_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmstat.c (0)
Location: mm/vmstat.c:78
Inline: False
```
**Symbols:**

```
ffffffff81be6f19-ffffffff81be6f6c: sysctl_vm_numa_stat_handler.cold (STB_LOCAL)
ffffffff812800d0-ffffffff8128021e: sysctl_vm_numa_stat_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int sysctl_vm_numa_stat_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmstat.c (0)
Location: mm/vmstat.c:78
Inline: False
```
**Symbols:**

```
ffffffff81bd8cb9-ffffffff81bd8d0c: sysctl_vm_numa_stat_handler.cold (STB_LOCAL)
ffffffff812851e0-ffffffff8128532f: sysctl_vm_numa_stat_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sysctl_vm_numa_stat_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmstat.c (0)
Location: mm/vmstat.c:77
Inline: False
```
**Symbols:**

```
ffffffff81cbab06-ffffffff81cbab59: sysctl_vm_numa_stat_handler.cold (STB_LOCAL)
ffffffff812c3a10-ffffffff812c3ba1: sysctl_vm_numa_stat_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sysctl_vm_numa_stat_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmstat.c (0)
Location: mm/vmstat.c:78
Inline: False
```
**Symbols:**

```
ffffffff81e6c437-ffffffff81e6c474: sysctl_vm_numa_stat_handler.cold (STB_LOCAL)
ffffffff81320e20-ffffffff81320fc2: sysctl_vm_numa_stat_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sysctl_vm_numa_stat_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81394d10)
Location: mm/vmstat.c:77
Inline: False
```
**Symbols:**

```
ffffffff81394d10-ffffffff81394f29: sysctl_vm_numa_stat_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sysctl_vm_numa_stat_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813c7810)
Location: mm/vmstat.c:78
Inline: False
```
**Symbols:**

```
ffffffff813c7810-ffffffff813c7a83: sysctl_vm_numa_stat_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sysctl_vm_numa_stat_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813f21f0)
Location: mm/vmstat.c:77
Inline: False
```
**Symbols:**

```
ffffffff813f21f0-ffffffff813f2463: sysctl_vm_numa_stat_handler (STB_GLOBAL)
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
int sysctl_vm_numa_stat_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffff8000102db960)
Location: mm/vmstat.c:78
Inline: False
```
**Symbols:**

```
ffff8000102db960-ffff8000102dbb2c: sysctl_vm_numa_stat_handler (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sysctl_vm_numa_stat_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c00000000039b360)
Location: mm/vmstat.c:78
Inline: False
```
**Symbols:**

```
c00000000039b360-c00000000039b5d8: sysctl_vm_numa_stat_handler (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int sysctl_vm_numa_stat_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmstat.c (0)
Location: mm/vmstat.c:78
Inline: False
```
**Symbols:**

```
ffffffff81240934-ffffffff81240987: sysctl_vm_numa_stat_handler.cold (STB_LOCAL)
ffffffff8123fc60-ffffffff8123fdad: sysctl_vm_numa_stat_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int sysctl_vm_numa_stat_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmstat.c (0)
Location: mm/vmstat.c:78
Inline: False
```
**Symbols:**

```
ffffffff81233934-ffffffff81233987: sysctl_vm_numa_stat_handler.cold (STB_LOCAL)
ffffffff81232c60-ffffffff81232dad: sysctl_vm_numa_stat_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int sysctl_vm_numa_stat_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmstat.c (0)
Location: mm/vmstat.c:78
Inline: False
```
**Symbols:**

```
ffffffff8123e6d4-ffffffff8123e727: sysctl_vm_numa_stat_handler.cold (STB_LOCAL)
ffffffff8123da00-ffffffff8123db4d: sysctl_vm_numa_stat_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int sysctl_vm_numa_stat_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmstat.c (0)
Location: mm/vmstat.c:78
Inline: False
```
**Symbols:**

```
ffffffff8124de04-ffffffff8124de57: sysctl_vm_numa_stat_handler.cold (STB_LOCAL)
ffffffff8124d130-ffffffff8124d27d: sysctl_vm_numa_stat_handler (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
