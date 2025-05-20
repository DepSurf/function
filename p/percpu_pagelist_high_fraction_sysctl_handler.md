# Function: <code>percpu_pagelist_high_fraction_sysctl_handler</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int percpu_pagelist_high_fraction_sysctl_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81309590)
Location: mm/page_alloc.c:8619
Inline: False
```
**Symbols:**

```
ffffffff81309590-ffffffff8130966c: percpu_pagelist_high_fraction_sysctl_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int percpu_pagelist_high_fraction_sysctl_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81371b80)
Location: mm/page_alloc.c:8806
Inline: False
```
**Symbols:**

```
ffffffff81371b80-ffffffff81371c6a: percpu_pagelist_high_fraction_sysctl_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int percpu_pagelist_high_fraction_sysctl_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813ef350)
Location: mm/page_alloc.c:8980
Inline: False
```
**Symbols:**

```
ffffffff813ef350-ffffffff813ef43a: percpu_pagelist_high_fraction_sysctl_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int percpu_pagelist_high_fraction_sysctl_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81419cd0)
Location: mm/page_alloc.c:5958
Inline: False
```
**Symbols:**

```
ffffffff81419cd0-ffffffff81419dba: percpu_pagelist_high_fraction_sysctl_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int percpu_pagelist_high_fraction_sysctl_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81446bc0)
Location: mm/page_alloc.c:6100
Inline: False
```
**Symbols:**

```
ffffffff81446bc0-ffffffff81446caa: percpu_pagelist_high_fraction_sysctl_handler (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
