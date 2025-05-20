# Function: <code>perf_trace_neigh_update</code>

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
void perf_trace_neigh_update(void *__data, struct neighbour *n, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff8193d960)
Location: include/trace/events/neigh.h:72
Inline: False
```
**Symbols:**

```
ffffffff8193d960-ffffffff8193dd12: perf_trace_neigh_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_trace_neigh_update(void *__data, struct neighbour *n, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff819707f0)
Location: include/trace/events/neigh.h:72
Inline: False
```
**Symbols:**

```
ffffffff819707f0-ffffffff81970ba2: perf_trace_neigh_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_trace_neigh_update(void *__data, struct neighbour *n, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81a44660)
Location: include/trace/events/neigh.h:72
Inline: False
```
**Symbols:**

```
ffffffff81a44660-ffffffff81a44a2c: perf_trace_neigh_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void perf_trace_neigh_update(void *__data, struct neighbour *n, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/neigh.h:72
Inline: False
```
**Symbols:**

```
ffffffff81a48480-ffffffff81a48913: perf_trace_neigh_update (STB_LOCAL)
ffffffff81c31b9b-ffffffff81c31bb3: perf_trace_neigh_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void perf_trace_neigh_update(void *__data, struct neighbour *n, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/neigh.h:72
Inline: False
```
**Symbols:**

```
ffffffff81a2d3c0-ffffffff81a2d853: perf_trace_neigh_update (STB_LOCAL)
ffffffff81c23e64-ffffffff81c23e7c: perf_trace_neigh_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void perf_trace_neigh_update(void *__data, struct neighbour *n, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/neigh.h:72
Inline: False
```
**Symbols:**

```
ffffffff81ae29a0-ffffffff81ae2e33: perf_trace_neigh_update (STB_LOCAL)
ffffffff81d37e78-ffffffff81d37e90: perf_trace_neigh_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void perf_trace_neigh_update(void *__data, struct neighbour *n, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/neigh.h:72
Inline: False
```
**Symbols:**

```
ffffffff81c67c90-ffffffff81c680ed: perf_trace_neigh_update (STB_LOCAL)
ffffffff81f04969-ffffffff81f04981: perf_trace_neigh_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void perf_trace_neigh_update(void *__data, struct neighbour *n, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/neigh.h:72
Inline: False
```
**Symbols:**

```
ffffffff81e1ee50-ffffffff81e1f39d: perf_trace_neigh_update (STB_LOCAL)
ffffffff820acb0c-ffffffff820acb5a: perf_trace_neigh_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void perf_trace_neigh_update(void *__data, struct neighbour *n, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/neigh.h:72
Inline: False
```
**Symbols:**

```
ffffffff81e91ee0-ffffffff81e92438: perf_trace_neigh_update (STB_LOCAL)
ffffffff8212e22d-ffffffff8212e283: perf_trace_neigh_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void perf_trace_neigh_update(void *__data, struct neighbour *n, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/neigh.h:72
Inline: False
```
**Symbols:**

```
ffffffff81f542e0-ffffffff81f5487e: perf_trace_neigh_update (STB_LOCAL)
ffffffff8221000c-ffffffff82210062: perf_trace_neigh_update.cold (STB_LOCAL)
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
void perf_trace_neigh_update(void *__data, struct neighbour *n, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffff800010c1a208)
Location: include/trace/events/neigh.h:72
Inline: False
```
**Symbols:**

```
ffff800010c1a208-ffff800010c1a448: perf_trace_neigh_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_trace_neigh_update(void *__data, struct neighbour *n, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (c0d2ec3c)
Location: include/trace/events/neigh.h:72
Inline: False
```
**Symbols:**

```
c0d2ec3c-c0d2ee90: perf_trace_neigh_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_trace_neigh_update(void *__data, struct neighbour *n, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (c000000000d06970)
Location: include/trace/events/neigh.h:72
Inline: False
```
**Symbols:**

```
c000000000d06970-c000000000d06c54: perf_trace_neigh_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_trace_neigh_update(void *__data, struct neighbour *n, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffe000791bbc)
Location: include/trace/events/neigh.h:72
Inline: False
```
**Symbols:**

```
ffffffe000791bbc-ffffffe000791d94: perf_trace_neigh_update (STB_LOCAL)
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
void perf_trace_neigh_update(void *__data, struct neighbour *n, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff819107c0)
Location: include/trace/events/neigh.h:72
Inline: False
```
**Symbols:**

```
ffffffff819107c0-ffffffff81910b72: perf_trace_neigh_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_trace_neigh_update(void *__data, struct neighbour *n, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff818ca580)
Location: include/trace/events/neigh.h:72
Inline: False
```
**Symbols:**

```
ffffffff818ca580-ffffffff818ca932: perf_trace_neigh_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_trace_neigh_update(void *__data, struct neighbour *n, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff819617f0)
Location: include/trace/events/neigh.h:72
Inline: False
```
**Symbols:**

```
ffffffff819617f0-ffffffff81961ba2: perf_trace_neigh_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_trace_neigh_update(void *__data, struct neighbour *n, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81983a60)
Location: include/trace/events/neigh.h:72
Inline: False
```
**Symbols:**

```
ffffffff81983a60-ffffffff81983e12: perf_trace_neigh_update (STB_LOCAL)
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
