# Function: <code>perf_trace_mptcp_subflow_get_send</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_trace_mptcp_subflow_get_send(void *__data, struct mptcp_subflow_context *subflow);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81baac80)
Location: include/trace/events/mptcp.h:18
Inline: False
```
**Symbols:**

```
ffffffff81baac80-ffffffff81baaea8: perf_trace_mptcp_subflow_get_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void perf_trace_mptcp_subflow_get_send(void *__data, struct mptcp_subflow_context *subflow);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: include/trace/events/mptcp.h:18
Inline: False
```
**Symbols:**

```
ffffffff81c7bcb0-ffffffff81c7bed9: perf_trace_mptcp_subflow_get_send (STB_LOCAL)
ffffffff81d43732-ffffffff81d43792: perf_trace_mptcp_subflow_get_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void perf_trace_mptcp_subflow_get_send(void *__data, struct mptcp_subflow_context *subflow);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: include/trace/events/mptcp.h:18
Inline: False
```
**Symbols:**

```
ffffffff81e20fa0-ffffffff81e211dd: perf_trace_mptcp_subflow_get_send (STB_LOCAL)
ffffffff81f101f6-ffffffff81f10256: perf_trace_mptcp_subflow_get_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void perf_trace_mptcp_subflow_get_send(void *__data, struct mptcp_subflow_context *subflow);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: include/trace/events/mptcp.h:18
Inline: False
```
**Symbols:**

```
ffffffff81ff8450-ffffffff81ff868a: perf_trace_mptcp_subflow_get_send (STB_LOCAL)
ffffffff820b64d0-ffffffff820b6530: perf_trace_mptcp_subflow_get_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void perf_trace_mptcp_subflow_get_send(void *__data, struct mptcp_subflow_context *subflow);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: include/trace/events/mptcp.h:18
Inline: False
```
**Symbols:**

```
ffffffff82074940-ffffffff82074b70: perf_trace_mptcp_subflow_get_send (STB_LOCAL)
ffffffff82137996-ffffffff821379e1: perf_trace_mptcp_subflow_get_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void perf_trace_mptcp_subflow_get_send(void *__data, struct mptcp_subflow_context *subflow);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: include/trace/events/mptcp.h:18
Inline: False
```
**Symbols:**

```
ffffffff82148d60-ffffffff82148f90: perf_trace_mptcp_subflow_get_send (STB_LOCAL)
ffffffff82219753-ffffffff8221979e: perf_trace_mptcp_subflow_get_send.cold (STB_LOCAL)
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
