# Function: <code>perf_trace_neigh_create</code>

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
void perf_trace_neigh_create(void *__data, struct neigh_table *tbl, struct net_device *dev, const void *pkey, const struct neighbour *n, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff8193c710)
Location: include/trace/events/neigh.h:23
Inline: False
```
**Symbols:**

```
ffffffff8193c710-ffffffff8193c882: perf_trace_neigh_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_trace_neigh_create(void *__data, struct neigh_table *tbl, struct net_device *dev, const void *pkey, const struct neighbour *n, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff8196f5a0)
Location: include/trace/events/neigh.h:23
Inline: False
```
**Symbols:**

```
ffffffff8196f5a0-ffffffff8196f712: perf_trace_neigh_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_trace_neigh_create(void *__data, struct neigh_table *tbl, struct net_device *dev, const void *pkey, const struct neighbour *n, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81a434b0)
Location: include/trace/events/neigh.h:23
Inline: False
```
**Symbols:**

```
ffffffff81a434b0-ffffffff81a43624: perf_trace_neigh_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void perf_trace_neigh_create(void *__data, struct neigh_table *tbl, struct net_device *dev, const void *pkey, const struct neighbour *n, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/neigh.h:23
Inline: False
```
**Symbols:**

```
ffffffff81a47010-ffffffff81a4722d: perf_trace_neigh_create (STB_LOCAL)
ffffffff81c31b53-ffffffff81c31b6b: perf_trace_neigh_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void perf_trace_neigh_create(void *__data, struct neigh_table *tbl, struct net_device *dev, const void *pkey, const struct neighbour *n, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/neigh.h:23
Inline: False
```
**Symbols:**

```
ffffffff81a2bcc0-ffffffff81a2bee0: perf_trace_neigh_create (STB_LOCAL)
ffffffff81c23e1c-ffffffff81c23e34: perf_trace_neigh_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void perf_trace_neigh_create(void *__data, struct neigh_table *tbl, struct net_device *dev, const void *pkey, const struct neighbour *n, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/neigh.h:23
Inline: False
```
**Symbols:**

```
ffffffff81ae0d40-ffffffff81ae0f60: perf_trace_neigh_create (STB_LOCAL)
ffffffff81d37d4c-ffffffff81d37d64: perf_trace_neigh_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void perf_trace_neigh_create(void *__data, struct neigh_table *tbl, struct net_device *dev, const void *pkey, const struct neighbour *n, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/neigh.h:23
Inline: False
```
**Symbols:**

```
ffffffff81c64600-ffffffff81c64840: perf_trace_neigh_create (STB_LOCAL)
ffffffff81f0471d-ffffffff81f04735: perf_trace_neigh_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_trace_neigh_create(void *__data, struct neigh_table *tbl, struct net_device *dev, const void *pkey, const struct neighbour *n, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81e1d0d0)
Location: include/trace/events/neigh.h:23
Inline: False
```
**Symbols:**

```
ffffffff81e1d0d0-ffffffff81e1d375: perf_trace_neigh_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_trace_neigh_create(void *__data, struct neigh_table *tbl, struct net_device *dev, const void *pkey, const struct neighbour *n, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81e92450)
Location: include/trace/events/neigh.h:23
Inline: False
```
**Symbols:**

```
ffffffff81e92450-ffffffff81e92711: perf_trace_neigh_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_trace_neigh_create(void *__data, struct neigh_table *tbl, struct net_device *dev, const void *pkey, const struct neighbour *n, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81f54890)
Location: include/trace/events/neigh.h:23
Inline: False
```
**Symbols:**

```
ffffffff81f54890-ffffffff81f54b94: perf_trace_neigh_create (STB_LOCAL)
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
void perf_trace_neigh_create(void *__data, struct neigh_table *tbl, struct net_device *dev, const void *pkey, const struct neighbour *n, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffff800010c18a68)
Location: include/trace/events/neigh.h:23
Inline: False
```
**Symbols:**

```
ffff800010c18a68-ffff800010c18be4: perf_trace_neigh_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_trace_neigh_create(void *__data, struct neigh_table *tbl, struct net_device *dev, const void *pkey, const struct neighbour *n, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (c0d2d9c4)
Location: include/trace/events/neigh.h:23
Inline: False
```
**Symbols:**

```
c0d2d9c4-c0d2db2c: perf_trace_neigh_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_trace_neigh_create(void *__data, struct neigh_table *tbl, struct net_device *dev, const void *pkey, const struct neighbour *n, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (c000000000d044b0)
Location: include/trace/events/neigh.h:23
Inline: False
```
**Symbols:**

```
c000000000d044b0-c000000000d046f0: perf_trace_neigh_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_trace_neigh_create(void *__data, struct neigh_table *tbl, struct net_device *dev, const void *pkey, const struct neighbour *n, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffe000790ede)
Location: include/trace/events/neigh.h:23
Inline: False
```
**Symbols:**

```
ffffffe000790ede-ffffffe000790ff4: perf_trace_neigh_create (STB_LOCAL)
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
void perf_trace_neigh_create(void *__data, struct neigh_table *tbl, struct net_device *dev, const void *pkey, const struct neighbour *n, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff8190f570)
Location: include/trace/events/neigh.h:23
Inline: False
```
**Symbols:**

```
ffffffff8190f570-ffffffff8190f6e2: perf_trace_neigh_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_trace_neigh_create(void *__data, struct neigh_table *tbl, struct net_device *dev, const void *pkey, const struct neighbour *n, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff818c9330)
Location: include/trace/events/neigh.h:23
Inline: False
```
**Symbols:**

```
ffffffff818c9330-ffffffff818c94a2: perf_trace_neigh_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_trace_neigh_create(void *__data, struct neigh_table *tbl, struct net_device *dev, const void *pkey, const struct neighbour *n, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff819605a0)
Location: include/trace/events/neigh.h:23
Inline: False
```
**Symbols:**

```
ffffffff819605a0-ffffffff81960712: perf_trace_neigh_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_trace_neigh_create(void *__data, struct neigh_table *tbl, struct net_device *dev, const void *pkey, const struct neighbour *n, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81982810)
Location: include/trace/events/neigh.h:23
Inline: False
```
**Symbols:**

```
ffffffff81982810-ffffffff81982982: perf_trace_neigh_create (STB_LOCAL)
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
