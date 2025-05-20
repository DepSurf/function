# Function: <code>mptcp_skb_can_collapse</code>

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
In net/ipv4/tcp_input.c (ffffffff81ab210f)
Location: include/net/mptcp.h:125
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
```
In net/ipv4/tcp_output.c (ffffffff81ac03b6)
Location: include/net/mptcp.h:125
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
In net/ipv4/tcp_input.c (ffffffff81abd0d3)
Location: include/net/mptcp.h:141
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
```
In net/ipv4/tcp_output.c (ffffffff81acbe16)
Location: include/net/mptcp.h:141
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
In net/ipv4/tcp_input.c (ffffffff81aa7f1f)
Location: include/net/mptcp.h:155
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
```
In net/ipv4/tcp_output.c (ffffffff81ab7055)
Location: include/net/mptcp.h:155
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
In net/ipv4/tcp_input.c (ffffffff81b6431e)
Location: include/net/mptcp.h:174
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
```
In net/ipv4/tcp_output.c (ffffffff81b74245)
Location: include/net/mptcp.h:174
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
In net/ipv4/tcp_input.c (ffffffff81cf3294)
Location: include/net/mptcp.h:179
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
```
In net/ipv4/tcp_output.c (ffffffff81d0371b)
Location: include/net/mptcp.h:179
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
In net/ipv4/tcp_input.c (ffffffff81eb78c4)
Location: include/net/mptcp.h:178
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
```
In net/ipv4/tcp_output.c (ffffffff81ec865b)
Location: include/net/mptcp.h:178
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
In net/ipv4/tcp_input.c (ffffffff81f15fa5)
Location: include/net/mptcp.h:178
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
```
In net/ipv4/tcp_output.c (ffffffff81f2717b)
Location: include/net/mptcp.h:178
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
In net/ipv4/tcp_input.c (ffffffff81fda2af)
Location: include/net/mptcp.h:199
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
```
In net/ipv4/tcp_output.c (ffffffff81febb6b)
Location: include/net/mptcp.h:199
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff6338)
Location: include/net/mptcp.h:199
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
