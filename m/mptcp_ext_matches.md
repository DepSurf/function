# Function: <code>mptcp_ext_matches</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab214b)
Location: include/net/mptcp.h:109
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
```
In net/ipv4/tcp_output.c (ffffffff81ac03eb)
Location: include/net/mptcp.h:109
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81abd111)
Location: include/net/mptcp.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
```
In net/ipv4/tcp_output.c (ffffffff81acbe4e)
Location: include/net/mptcp.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aa7f5e)
Location: include/net/mptcp.h:139
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
```
In net/ipv4/tcp_output.c (ffffffff81ab708d)
Location: include/net/mptcp.h:139
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b64366)
Location: include/net/mptcp.h:158
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
```
In net/ipv4/tcp_output.c (ffffffff81b7427d)
Location: include/net/mptcp.h:158
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf32d2)
Location: include/net/mptcp.h:163
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
```
In net/ipv4/tcp_output.c (ffffffff81d03758)
Location: include/net/mptcp.h:163
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81eb7902)
Location: include/net/mptcp.h:162
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
```
In net/ipv4/tcp_output.c (ffffffff81ec8698)
Location: include/net/mptcp.h:162
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f15ef1)
Location: include/net/mptcp.h:162
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
```
In net/ipv4/tcp_output.c (ffffffff81f271b9)
Location: include/net/mptcp.h:162
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
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
In net/ipv4/tcp_input.c (ffffffff81fda2ef)
Location: include/net/mptcp.h:183
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
```
In net/ipv4/tcp_output.c (ffffffff81febba9)
Location: include/net/mptcp.h:183
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff6374)
Location: include/net/mptcp.h:183
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
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
