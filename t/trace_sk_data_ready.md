# Function: <code>trace_sk_data_ready</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e094bd)
Location: include/trace/events/sock.h:266
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_readable
```
```
In net/core/skmsg.c (ffffffff81ea19ff)
Location: include/trace/events/sock.h:266
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_strp_data_ready
```
```
In net/xfrm/espintcp.c (ffffffff81fa7591)
Location: include/trace/events/sock.h:266
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_data_ready
```
```
In net/mptcp/subflow.c (ffffffff8207bdeb)
Location: include/trace/events/sock.h:266
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_data_ready
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec5ead)
Location: include/trace/events/sock.h:266
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_readable
```
```
In net/core/skmsg.c (ffffffff81f6420f)
Location: include/trace/events/sock.h:266
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_strp_data_ready
```
```
In net/xfrm/espintcp.c (ffffffff82074841)
Location: include/trace/events/sock.h:266
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_data_ready
```
```
In net/mptcp/subflow.c (ffffffff821511fb)
Location: include/trace/events/sock.h:266
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_data_ready
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
