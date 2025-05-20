# Function: <code>trace_event_raw_event_neigh_update</code>

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
void trace_event_raw_event_neigh_update(void *__data, struct neighbour *n, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff8193d190)
Location: include/trace/events/neigh.h:72
Inline: False
```
**Symbols:**

```
ffffffff8193d190-ffffffff8193d4f3: trace_event_raw_event_neigh_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void trace_event_raw_event_neigh_update(void *__data, struct neighbour *n, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81970020)
Location: include/trace/events/neigh.h:72
Inline: False
```
**Symbols:**

```
ffffffff81970020-ffffffff81970383: trace_event_raw_event_neigh_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void trace_event_raw_event_neigh_update(void *__data, struct neighbour *n, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81a482d0)
Location: include/trace/events/neigh.h:72
Inline: False
```
**Symbols:**

```
ffffffff81a482d0-ffffffff81a48623: trace_event_raw_event_neigh_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_neigh_update(void *__data, struct neighbour *n, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
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
ffffffff81a4d510-ffffffff81a4d94a: trace_event_raw_event_neigh_update (STB_LOCAL)
ffffffff81c31dc3-ffffffff81c31ddb: trace_event_raw_event_neigh_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_neigh_update(void *__data, struct neighbour *n, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
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
ffffffff81a32530-ffffffff81a3294b: trace_event_raw_event_neigh_update (STB_LOCAL)
ffffffff81c2408c-ffffffff81c240a4: trace_event_raw_event_neigh_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_neigh_update(void *__data, struct neighbour *n, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
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
ffffffff81ae7f20-ffffffff81ae833b: trace_event_raw_event_neigh_update (STB_LOCAL)
ffffffff81d380c2-ffffffff81d380da: trace_event_raw_event_neigh_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_neigh_update(void *__data, struct neighbour *n, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
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
ffffffff81c69ba0-ffffffff81c69fb7: trace_event_raw_event_neigh_update (STB_LOCAL)
ffffffff81f04a4b-ffffffff81f04a63: trace_event_raw_event_neigh_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_neigh_update(void *__data, struct neighbour *n, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
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
ffffffff81e216c0-ffffffff81e21bce: trace_event_raw_event_neigh_update (STB_LOCAL)
ffffffff820acba7-ffffffff820acc11: trace_event_raw_event_neigh_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_neigh_update(void *__data, struct neighbour *n, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
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
ffffffff81e96f80-ffffffff81e974bf: trace_event_raw_event_neigh_update (STB_LOCAL)
ffffffff8212e29c-ffffffff8212e310: trace_event_raw_event_neigh_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_neigh_update(void *__data, struct neighbour *n, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
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
ffffffff81f59df0-ffffffff81f5a375: trace_event_raw_event_neigh_update (STB_LOCAL)
ffffffff8221007b-ffffffff822100ef: trace_event_raw_event_neigh_update.cold (STB_LOCAL)
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
void trace_event_raw_event_neigh_update(void *__data, struct neighbour *n, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffff800010c19070)
Location: include/trace/events/neigh.h:72
Inline: False
```
**Symbols:**

```
ffff800010c19070-ffff800010c1926c: trace_event_raw_event_neigh_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void trace_event_raw_event_neigh_update(void *__data, struct neighbour *n, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (c0d2e668)
Location: include/trace/events/neigh.h:72
Inline: False
```
**Symbols:**

```
c0d2e668-c0d2e870: trace_event_raw_event_neigh_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void trace_event_raw_event_neigh_update(void *__data, struct neighbour *n, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (c000000000d05490)
Location: include/trace/events/neigh.h:72
Inline: False
```
**Symbols:**

```
c000000000d05490-c000000000d05738: trace_event_raw_event_neigh_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void trace_event_raw_event_neigh_update(void *__data, struct neighbour *n, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffe0007944de)
Location: include/trace/events/neigh.h:72
Inline: False
```
**Symbols:**

```
ffffffe0007944de-ffffffe0007946b4: trace_event_raw_event_neigh_update (STB_LOCAL)
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
void trace_event_raw_event_neigh_update(void *__data, struct neighbour *n, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff8190fff0)
Location: include/trace/events/neigh.h:72
Inline: False
```
**Symbols:**

```
ffffffff8190fff0-ffffffff81910353: trace_event_raw_event_neigh_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void trace_event_raw_event_neigh_update(void *__data, struct neighbour *n, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff818c9db0)
Location: include/trace/events/neigh.h:72
Inline: False
```
**Symbols:**

```
ffffffff818c9db0-ffffffff818ca113: trace_event_raw_event_neigh_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void trace_event_raw_event_neigh_update(void *__data, struct neighbour *n, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81961020)
Location: include/trace/events/neigh.h:72
Inline: False
```
**Symbols:**

```
ffffffff81961020-ffffffff81961383: trace_event_raw_event_neigh_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void trace_event_raw_event_neigh_update(void *__data, struct neighbour *n, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-traces.c (ffffffff81983290)
Location: include/trace/events/neigh.h:72
Inline: False
```
**Symbols:**

```
ffffffff81983290-ffffffff819835f3: trace_event_raw_event_neigh_update (STB_LOCAL)
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
