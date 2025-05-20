# Function: <code>perf_trace_br_fdb_update</code>

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
void perf_trace_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, bool added_by_user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81873480)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
ffffffff81873480-ffffffff8187365c: perf_trace_br_fdb_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_trace_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, bool added_by_user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff818c4c10)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
ffffffff818c4c10-ffffffff818c4df1: perf_trace_br_fdb_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_trace_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, bool added_by_user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff818edc80)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
ffffffff818edc80-ffffffff818ede61: perf_trace_br_fdb_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_trace_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, bool added_by_user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff8193e8b0)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
ffffffff8193e8b0-ffffffff8193ea94: perf_trace_br_fdb_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_trace_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, bool added_by_user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81971740)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
ffffffff81971740-ffffffff81971924: perf_trace_br_fdb_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_trace_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81a45600)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
ffffffff81a45600-ffffffff81a457d5: perf_trace_br_fdb_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void perf_trace_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
ffffffff81a49910-ffffffff81a49c88: perf_trace_br_fdb_update (STB_LOCAL)
ffffffff81c31c43-ffffffff81c31c5b: perf_trace_br_fdb_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void perf_trace_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
ffffffff81a2e860-ffffffff81a2ebd8: perf_trace_br_fdb_update (STB_LOCAL)
ffffffff81c23f0c-ffffffff81c23f24: perf_trace_br_fdb_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void perf_trace_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
ffffffff81ae3e40-ffffffff81ae41b8: perf_trace_br_fdb_update (STB_LOCAL)
ffffffff81d37f20-ffffffff81d37f38: perf_trace_br_fdb_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void perf_trace_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
ffffffff81c67900-ffffffff81c67c90: perf_trace_br_fdb_update (STB_LOCAL)
ffffffff81f04951-ffffffff81f04969: perf_trace_br_fdb_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_trace_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81e1ea90)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
ffffffff81e1ea90-ffffffff81e1ee33: perf_trace_br_fdb_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_trace_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81e92a70)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
ffffffff81e92a70-ffffffff81e92e5f: perf_trace_br_fdb_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_trace_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81f54f00)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
ffffffff81f54f00-ffffffff81f55300: perf_trace_br_fdb_update (STB_LOCAL)
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
void perf_trace_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, bool added_by_user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffff800010c19e68)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
ffff800010c19e68-ffff800010c1a030: perf_trace_br_fdb_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_trace_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, bool added_by_user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (c0d2f898)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
c0d2f898-c0d2fa7c: perf_trace_br_fdb_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_trace_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, bool added_by_user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (c000000000d06c60)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
c000000000d06c60-c000000000d06f08: perf_trace_br_fdb_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_trace_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, bool added_by_user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffe000792532)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
ffffffe000792532-ffffffe0007926ce: perf_trace_br_fdb_update (STB_LOCAL)
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
void perf_trace_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, bool added_by_user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81911710)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
ffffffff81911710-ffffffff819118f4: perf_trace_br_fdb_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_trace_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, bool added_by_user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff818cb4d0)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
ffffffff818cb4d0-ffffffff818cb6b4: perf_trace_br_fdb_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_trace_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, bool added_by_user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81962740)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
ffffffff81962740-ffffffff81962924: perf_trace_br_fdb_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_trace_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, bool added_by_user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff819849b0)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
ffffffff819849b0-ffffffff81984b94: perf_trace_br_fdb_update (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool added_by_user</code>
</li>
</ul>
</details>
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
