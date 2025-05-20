# Function: <code>trace_event_raw_event_br_fdb_add</code>

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
void trace_event_raw_event_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81874b80)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
ffffffff81874b80-ffffffff81874d29: trace_event_raw_event_br_fdb_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void trace_event_raw_event_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff818c6390)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
ffffffff818c6390-ffffffff818c6505: trace_event_raw_event_br_fdb_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void trace_event_raw_event_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff818ef0f0)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
ffffffff818ef0f0-ffffffff818ef265: trace_event_raw_event_br_fdb_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void trace_event_raw_event_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81940340)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
ffffffff81940340-ffffffff819404b9: trace_event_raw_event_br_fdb_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void trace_event_raw_event_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff819731e0)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
ffffffff819731e0-ffffffff81973359: trace_event_raw_event_br_fdb_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void trace_event_raw_event_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81a47890)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
ffffffff81a47890-ffffffff81a47a02: trace_event_raw_event_br_fdb_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
ffffffff81a4c740-ffffffff81a4c93c: trace_event_raw_event_br_fdb_add (STB_LOCAL)
ffffffff81c31d4b-ffffffff81c31d63: trace_event_raw_event_br_fdb_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
ffffffff81a31490-ffffffff81a3169a: trace_event_raw_event_br_fdb_add (STB_LOCAL)
ffffffff81c24014-ffffffff81c2402c: trace_event_raw_event_br_fdb_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
ffffffff81ae6e70-ffffffff81ae707a: trace_event_raw_event_br_fdb_add (STB_LOCAL)
ffffffff81d38028-ffffffff81d38040: trace_event_raw_event_br_fdb_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/net-traces.c (0)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
ffffffff81c69310-ffffffff81c69528: trace_event_raw_event_br_fdb_add (STB_LOCAL)
ffffffff81f049e1-ffffffff81f049f9: trace_event_raw_event_br_fdb_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void trace_event_raw_event_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81e21480)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
ffffffff81e21480-ffffffff81e216ab: trace_event_raw_event_br_fdb_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void trace_event_raw_event_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81e96d10)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
ffffffff81e96d10-ffffffff81e96f66: trace_event_raw_event_br_fdb_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void trace_event_raw_event_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81f590b0)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
ffffffff81f590b0-ffffffff81f59300: trace_event_raw_event_br_fdb_add (STB_LOCAL)
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
void trace_event_raw_event_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffff800010c173e8)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
ffff800010c173e8-ffff800010c17518: trace_event_raw_event_br_fdb_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void trace_event_raw_event_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (c0d3137c)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
c0d3137c-c0d314d8: trace_event_raw_event_br_fdb_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void trace_event_raw_event_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (c000000000d09090)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
c000000000d09090-c000000000d09230: trace_event_raw_event_br_fdb_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void trace_event_raw_event_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffe0007933f8)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
ffffffe0007933f8-ffffffe000793534: trace_event_raw_event_br_fdb_add (STB_LOCAL)
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
void trace_event_raw_event_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff819131b0)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
ffffffff819131b0-ffffffff81913329: trace_event_raw_event_br_fdb_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void trace_event_raw_event_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff818ccf70)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
ffffffff818ccf70-ffffffff818cd0e9: trace_event_raw_event_br_fdb_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void trace_event_raw_event_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff819641e0)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
ffffffff819641e0-ffffffff81964359: trace_event_raw_event_br_fdb_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void trace_event_raw_event_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81986450)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
ffffffff81986450-ffffffff819865c9: trace_event_raw_event_br_fdb_add (STB_LOCAL)
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
