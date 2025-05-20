# Function: <code>trace_event_raw_event_br_fdb_update</code>

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
void trace_event_raw_event_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, bool added_by_user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81875360)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
ffffffff81875360-ffffffff81875512: trace_event_raw_event_br_fdb_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void trace_event_raw_event_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, bool added_by_user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff818c6990)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
ffffffff818c6990-ffffffff818c6b34: trace_event_raw_event_br_fdb_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void trace_event_raw_event_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, bool added_by_user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff818efae0)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
ffffffff818efae0-ffffffff818efc84: trace_event_raw_event_br_fdb_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void trace_event_raw_event_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, bool added_by_user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff819411e0)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
ffffffff819411e0-ffffffff8194138d: trace_event_raw_event_br_fdb_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void trace_event_raw_event_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, bool added_by_user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81974080)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
ffffffff81974080-ffffffff8197422d: trace_event_raw_event_br_fdb_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void trace_event_raw_event_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81a48c50)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
ffffffff81a48c50-ffffffff81a48df7: trace_event_raw_event_br_fdb_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, long unsigned int flags);
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
ffffffff81a4e0b0-ffffffff81a4e3d7: trace_event_raw_event_br_fdb_update (STB_LOCAL)
ffffffff81c31e23-ffffffff81c31e3b: trace_event_raw_event_br_fdb_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, long unsigned int flags);
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
ffffffff81a330c0-ffffffff81a333e9: trace_event_raw_event_br_fdb_update (STB_LOCAL)
ffffffff81c240ec-ffffffff81c24104: trace_event_raw_event_br_fdb_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, long unsigned int flags);
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
ffffffff81ae8ab0-ffffffff81ae8dd9: trace_event_raw_event_br_fdb_update (STB_LOCAL)
ffffffff81d38122-ffffffff81d3813a: trace_event_raw_event_br_fdb_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, long unsigned int flags);
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
ffffffff81c6aaa0-ffffffff81c6adcf: trace_event_raw_event_br_fdb_update (STB_LOCAL)
ffffffff81f04ac3-ffffffff81f04adb: trace_event_raw_event_br_fdb_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void trace_event_raw_event_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81e227b0)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
ffffffff81e227b0-ffffffff81e22ae9: trace_event_raw_event_br_fdb_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void trace_event_raw_event_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81e987c0)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
ffffffff81e987c0-ffffffff81e98b45: trace_event_raw_event_br_fdb_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void trace_event_raw_event_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81f5ae40)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
ffffffff81f5ae40-ffffffff81f5b1d3: trace_event_raw_event_br_fdb_update (STB_LOCAL)
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
void trace_event_raw_event_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, bool added_by_user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffff800010c18be8)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
ffff800010c18be8-ffff800010c18d68: trace_event_raw_event_br_fdb_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void trace_event_raw_event_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, bool added_by_user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (c0d32028)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
c0d32028-c0d321c4: trace_event_raw_event_br_fdb_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void trace_event_raw_event_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, bool added_by_user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (c000000000d0a0d0)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
c000000000d0a0d0-c000000000d0a31c: trace_event_raw_event_br_fdb_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void trace_event_raw_event_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, bool added_by_user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffe0007938a6)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
ffffffe0007938a6-ffffffe000793a1e: trace_event_raw_event_br_fdb_update (STB_LOCAL)
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
void trace_event_raw_event_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, bool added_by_user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81914050)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
ffffffff81914050-ffffffff819141fd: trace_event_raw_event_br_fdb_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void trace_event_raw_event_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, bool added_by_user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff818cde10)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
ffffffff818cde10-ffffffff818cdfbd: trace_event_raw_event_br_fdb_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void trace_event_raw_event_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, bool added_by_user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81965080)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
ffffffff81965080-ffffffff8196522d: trace_event_raw_event_br_fdb_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void trace_event_raw_event_br_fdb_update(void *__data, struct net_bridge *br, struct net_bridge_port *source, const unsigned char *addr, u16 vid, bool added_by_user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff819872f0)
Location: include/trace/events/bridge.h:95
Inline: False
```
**Symbols:**

```
ffffffff819872f0-ffffffff8198749d: trace_event_raw_event_br_fdb_update (STB_LOCAL)
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
