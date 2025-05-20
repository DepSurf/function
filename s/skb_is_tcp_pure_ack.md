# Function: <code>skb_is_tcp_pure_ack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: include/net/tcp.h:1794
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: include/net/tcp.h:1822
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: include/net/tcp.h:1897
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (0)
Location: include/net/tcp.h:1952
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/net/tcp.h:1952
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (0)
Location: include/net/tcp.h:1917
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/net/tcp.h:1917
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (0)
Location: include/net/tcp.h:1932
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/net/tcp.h:1932
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (0)
Location: include/net/tcp.h:2008
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/net/tcp.h:2008
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (0)
Location: include/net/tcp.h:2037
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/net/tcp.h:2037
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (0)
Location: include/net/tcp.h:2060
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/net/tcp.h:2060
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e6b55)
Location: include/net/tcp.h:2103
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81abe101)
Location: include/net/tcp.h:2103
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
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
In net/core/sock.c (ffffffff819e6385)
Location: include/net/tcp.h:2111
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81ac99dd)
Location: include/net/tcp.h:2111
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/mptcp/options.c (ffffffff81bc4346)
Location: include/net/tcp.h:2111
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_established_options_add_addr
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
In net/core/sock.c (ffffffff819cae05)
Location: include/net/tcp.h:2115
Inline: True
Inline callers:
  - net/core/sock.c:skb_orphan_partial
```
```
In net/ipv4/tcp_output.c (ffffffff81ab4883)
Location: include/net/tcp.h:2115
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/mptcp/options.c (ffffffff81bb4a94)
Location: include/net/tcp.h:2115
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_established_options_add_addr
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
In net/core/sock.c (ffffffff81a7a435)
Location: include/net/tcp.h:2107
Inline: True
Inline callers:
  - net/core/sock.c:skb_orphan_partial
```
```
In net/ipv4/tcp_output.c (ffffffff81b71843)
Location: include/net/tcp.h:2107
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/mptcp/pm.c (ffffffff81c86d99)
Location: include/net/tcp.h:2107
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_signal
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
In net/core/sock.c (ffffffff81bede55)
Location: include/net/tcp.h:2163
Inline: True
Inline callers:
  - net/core/sock.c:skb_orphan_partial
```
```
In net/ipv4/tcp_output.c (ffffffff81d00fa6)
Location: include/net/tcp.h:2163
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/mptcp/pm.c (ffffffff81e2d4b1)
Location: include/net/tcp.h:2163
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_signal
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
In net/core/sock.c (ffffffff81d9a725)
Location: include/net/tcp.h:2211
Inline: True
Inline callers:
  - net/core/sock.c:skb_orphan_partial
```
```
In net/ipv4/tcp_output.c (ffffffff81ec6106)
Location: include/net/tcp.h:2211
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/mptcp/pm.c (ffffffff82005901)
Location: include/net/tcp.h:2211
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_signal
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
In net/core/sock.c (ffffffff81e08f85)
Location: include/net/tcp.h:2228
Inline: True
Inline callers:
  - net/core/sock.c:skb_orphan_partial
```
```
In net/ipv4/tcp_output.c (ffffffff81f2484b)
Location: include/net/tcp.h:2228
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/mptcp/pm.c (ffffffff82081af1)
Location: include/net/tcp.h:2228
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_signal
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
In net/core/sock.c (ffffffff81ec59f5)
Location: include/net/tcp.h:2425
Inline: True
Inline callers:
  - net/core/sock.c:skb_orphan_partial
```
```
In net/ipv4/tcp_output.c (ffffffff81fe9030)
Location: include/net/tcp.h:2425
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/mptcp/pm.c (ffffffff821570e1)
Location: include/net/tcp.h:2425
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_signal
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (0)
Location: include/net/tcp.h:2060
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/net/tcp.h:2060
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0cc9e44)
Location: include/net/tcp.h:2060
Inline: True
```
```
In net/ipv4/tcp_output.c (c0d92f64)
Location: include/net/tcp.h:2060
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (0)
Location: include/net/tcp.h:2060
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/net/tcp.h:2060
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (0)
Location: include/net/tcp.h:2060
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/net/tcp.h:2060
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (0)
Location: include/net/tcp.h:2060
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/net/tcp.h:2060
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (0)
Location: include/net/tcp.h:2060
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/net/tcp.h:2060
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (0)
Location: include/net/tcp.h:2060
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/net/tcp.h:2060
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (0)
Location: include/net/tcp.h:2060
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/net/tcp.h:2060
Inline: True
```
</details>
</li>
</ul>

## Differences
