# Function: <code>perf_trace_br_fdb_add</code>

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
void perf_trace_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81872700)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
ffffffff81872700-ffffffff81872872: perf_trace_br_fdb_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_trace_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff818c41a0)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
ffffffff818c41a0-ffffffff818c4317: perf_trace_br_fdb_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_trace_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff818ed230)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
ffffffff818ed230-ffffffff818ed3a7: perf_trace_br_fdb_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_trace_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff8193d7e0)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
ffffffff8193d7e0-ffffffff8193d95f: perf_trace_br_fdb_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_trace_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81970670)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
ffffffff81970670-ffffffff819707ef: perf_trace_br_fdb_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_trace_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81a444d0)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
ffffffff81a444d0-ffffffff81a44655: perf_trace_br_fdb_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void perf_trace_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
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
ffffffff81a48240-ffffffff81a48473: perf_trace_br_fdb_add (STB_LOCAL)
ffffffff81c31b83-ffffffff81c31b9b: perf_trace_br_fdb_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void perf_trace_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
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
ffffffff81a2d190-ffffffff81a2d3b9: perf_trace_br_fdb_add (STB_LOCAL)
ffffffff81c23e4c-ffffffff81c23e64: perf_trace_br_fdb_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void perf_trace_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
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
ffffffff81ae2770-ffffffff81ae2999: perf_trace_br_fdb_add (STB_LOCAL)
ffffffff81d37e60-ffffffff81d37e78: perf_trace_br_fdb_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void perf_trace_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
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
ffffffff81c66360-ffffffff81c665bb: perf_trace_br_fdb_add (STB_LOCAL)
ffffffff81f04879-ffffffff81f04891: perf_trace_br_fdb_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_trace_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81e1d390)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
ffffffff81e1d390-ffffffff81e1d604: perf_trace_br_fdb_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_trace_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81e93dc0)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
ffffffff81e93dc0-ffffffff81e94054: perf_trace_br_fdb_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_trace_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81f56270)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
ffffffff81f56270-ffffffff81f56517: perf_trace_br_fdb_add (STB_LOCAL)
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
void perf_trace_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffff800010c18d68)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
ffff800010c18d68-ffff800010c18ecc: perf_trace_br_fdb_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_trace_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (c0d2eac8)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
c0d2eac8-c0d2ec3c: perf_trace_br_fdb_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_trace_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (c000000000d05fa0)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
c000000000d05fa0-c000000000d06188: perf_trace_br_fdb_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_trace_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffe000791a96)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
ffffffe000791a96-ffffffe000791bbc: perf_trace_br_fdb_add (STB_LOCAL)
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
void perf_trace_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81910640)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
ffffffff81910640-ffffffff819107bf: perf_trace_br_fdb_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_trace_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff818ca400)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
ffffffff818ca400-ffffffff818ca57f: perf_trace_br_fdb_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_trace_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81961670)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
ffffffff81961670-ffffffff819617ef: perf_trace_br_fdb_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_trace_br_fdb_add(void *__data, struct ndmsg *ndm, struct net_device *dev, const unsigned char *addr, u16 vid, u16 nlh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff819838e0)
Location: include/trace/events/bridge.h:12
Inline: False
```
**Symbols:**

```
ffffffff819838e0-ffffffff81983a5f: perf_trace_br_fdb_add (STB_LOCAL)
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
