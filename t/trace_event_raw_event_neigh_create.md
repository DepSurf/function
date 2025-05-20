# Function: <code>trace_event_raw_event_neigh_create</code>

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
void trace_event_raw_event_neigh_create(void *__data, struct neigh_table *tbl, struct net_device *dev, const void *pkey, const struct neighbour *n, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81940200)
Location: include/trace/events/neigh.h:23
Inline: False
```
**Symbols:**

```
ffffffff81940200-ffffffff81940333: trace_event_raw_event_neigh_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void trace_event_raw_event_neigh_create(void *__data, struct neigh_table *tbl, struct net_device *dev, const void *pkey, const struct neighbour *n, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff819730a0)
Location: include/trace/events/neigh.h:23
Inline: False
```
**Symbols:**

```
ffffffff819730a0-ffffffff819731d3: trace_event_raw_event_neigh_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void trace_event_raw_event_neigh_create(void *__data, struct neigh_table *tbl, struct net_device *dev, const void *pkey, const struct neighbour *n, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81a47190)
Location: include/trace/events/neigh.h:23
Inline: False
```
**Symbols:**

```
ffffffff81a47190-ffffffff81a472bd: trace_event_raw_event_neigh_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_neigh_create(void *__data, struct neigh_table *tbl, struct net_device *dev, const void *pkey, const struct neighbour *n, bool exempt_from_gc);
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
ffffffff81a4bd40-ffffffff81a4bf38: trace_event_raw_event_neigh_create (STB_LOCAL)
ffffffff81c31ceb-ffffffff81c31d03: trace_event_raw_event_neigh_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_neigh_create(void *__data, struct neigh_table *tbl, struct net_device *dev, const void *pkey, const struct neighbour *n, bool exempt_from_gc);
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
ffffffff81a30d00-ffffffff81a30efa: trace_event_raw_event_neigh_create (STB_LOCAL)
ffffffff81c23fb4-ffffffff81c23fcc: trace_event_raw_event_neigh_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_neigh_create(void *__data, struct neigh_table *tbl, struct net_device *dev, const void *pkey, const struct neighbour *n, bool exempt_from_gc);
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
ffffffff81ae66e0-ffffffff81ae68da: trace_event_raw_event_neigh_create (STB_LOCAL)
ffffffff81d37fc8-ffffffff81d37fe0: trace_event_raw_event_neigh_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_neigh_create(void *__data, struct neigh_table *tbl, struct net_device *dev, const void *pkey, const struct neighbour *n, bool exempt_from_gc);
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
ffffffff81c64af0-ffffffff81c64cf9: trace_event_raw_event_neigh_create (STB_LOCAL)
ffffffff81f0474d-ffffffff81f04765: trace_event_raw_event_neigh_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void trace_event_raw_event_neigh_create(void *__data, struct neigh_table *tbl, struct net_device *dev, const void *pkey, const struct neighbour *n, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81e20b40)
Location: include/trace/events/neigh.h:23
Inline: False
```
**Symbols:**

```
ffffffff81e20b40-ffffffff81e20d94: trace_event_raw_event_neigh_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void trace_event_raw_event_neigh_create(void *__data, struct neigh_table *tbl, struct net_device *dev, const void *pkey, const struct neighbour *n, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81e96640)
Location: include/trace/events/neigh.h:23
Inline: False
```
**Symbols:**

```
ffffffff81e96640-ffffffff81e968b6: trace_event_raw_event_neigh_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void trace_event_raw_event_neigh_create(void *__data, struct neigh_table *tbl, struct net_device *dev, const void *pkey, const struct neighbour *n, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81f58de0)
Location: include/trace/events/neigh.h:23
Inline: False
```
**Symbols:**

```
ffffffff81f58de0-ffffffff81f59097: trace_event_raw_event_neigh_create (STB_LOCAL)
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
void trace_event_raw_event_neigh_create(void *__data, struct neigh_table *tbl, struct net_device *dev, const void *pkey, const struct neighbour *n, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffff800010c172a0)
Location: include/trace/events/neigh.h:23
Inline: False
```
**Symbols:**

```
ffff800010c172a0-ffff800010c173e4: trace_event_raw_event_neigh_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void trace_event_raw_event_neigh_create(void *__data, struct neigh_table *tbl, struct net_device *dev, const void *pkey, const struct neighbour *n, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (c0d31244)
Location: include/trace/events/neigh.h:23
Inline: False
```
**Symbols:**

```
c0d31244-c0d3137c: trace_event_raw_event_neigh_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void trace_event_raw_event_neigh_create(void *__data, struct neigh_table *tbl, struct net_device *dev, const void *pkey, const struct neighbour *n, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (c000000000d08ee0)
Location: include/trace/events/neigh.h:23
Inline: False
```
**Symbols:**

```
c000000000d08ee0-c000000000d09090: trace_event_raw_event_neigh_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void trace_event_raw_event_neigh_create(void *__data, struct neigh_table *tbl, struct net_device *dev, const void *pkey, const struct neighbour *n, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffe000793534)
Location: include/trace/events/neigh.h:23
Inline: False
```
**Symbols:**

```
ffffffe000793534-ffffffe00079364e: trace_event_raw_event_neigh_create (STB_LOCAL)
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
void trace_event_raw_event_neigh_create(void *__data, struct neigh_table *tbl, struct net_device *dev, const void *pkey, const struct neighbour *n, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81913070)
Location: include/trace/events/neigh.h:23
Inline: False
```
**Symbols:**

```
ffffffff81913070-ffffffff819131a3: trace_event_raw_event_neigh_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void trace_event_raw_event_neigh_create(void *__data, struct neigh_table *tbl, struct net_device *dev, const void *pkey, const struct neighbour *n, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff818cce30)
Location: include/trace/events/neigh.h:23
Inline: False
```
**Symbols:**

```
ffffffff818cce30-ffffffff818ccf63: trace_event_raw_event_neigh_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void trace_event_raw_event_neigh_create(void *__data, struct neigh_table *tbl, struct net_device *dev, const void *pkey, const struct neighbour *n, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff819640a0)
Location: include/trace/events/neigh.h:23
Inline: False
```
**Symbols:**

```
ffffffff819640a0-ffffffff819641d3: trace_event_raw_event_neigh_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void trace_event_raw_event_neigh_create(void *__data, struct neigh_table *tbl, struct net_device *dev, const void *pkey, const struct neighbour *n, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81986310)
Location: include/trace/events/neigh.h:23
Inline: False
```
**Symbols:**

```
ffffffff81986310-ffffffff81986443: trace_event_raw_event_neigh_create (STB_LOCAL)
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
