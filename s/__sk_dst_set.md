# Function: <code>__sk_dst_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff817682c7)
Location: include/net/sock.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_timer.c (ffffffff8177a284)
Location: include/net/sock.h:1746
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f0112)
Location: include/net/sock.h:1746
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff817d4ba6)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_timer.c (ffffffff817e74f3)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185ef5b)
Location: include/net/sock.h:1707
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818048b9)
Location: include/net/sock.h:1769
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_timer.c (ffffffff81817a72)
Location: include/net/sock.h:1769
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818910f7)
Location: include/net/sock.h:1769
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
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
In net/ipv4/tcp.c (ffffffff81824b43)
Location: include/net/sock.h:1775
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_timer.c (ffffffff81837e9c)
Location: include/net/sock.h:1775
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/ipv4/tcp.c (ffffffff818a6920)
Location: include/net/sock.h:1789
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_timer.c (ffffffff818b75d4)
Location: include/net/sock.h:1789
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff818fa8d0)
Location: include/net/sock.h:1789
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
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
In net/ipv4/tcp.c (ffffffff818fba19)
Location: include/net/sock.h:1800
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_timer.c (ffffffff8190cf51)
Location: include/net/sock.h:1800
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff819513d6)
Location: include/net/sock.h:1800
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
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
In net/ipv4/tcp.c (ffffffff81929970)
Location: include/net/sock.h:1885
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_timer.c (ffffffff8193b268)
Location: include/net/sock.h:1885
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff819848b6)
Location: include/net/sock.h:1885
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
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
In net/ipv4/tcp.c (ffffffff8198cab2)
Location: include/net/sock.h:1897
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_timer.c (ffffffff8199f635)
Location: include/net/sock.h:1897
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff819ee5ac)
Location: include/net/sock.h:1897
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
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
In net/ipv4/tcp.c (ffffffff819c342e)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_timer.c (ffffffff819d61df)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2548c)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
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
In net/ipv4/tcp.c (ffffffff81aaeb29)
Location: include/net/sock.h:1956
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac30e1)
Location: include/net/sock.h:1956
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1741b)
Location: include/net/sock.h:1956
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/xfrm/espintcp.c (ffffffff81b2335e)
Location: include/net/sock.h:1956
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_init_sk
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
In net/ipv4/tcp.c (ffffffff81ab8d90)
Location: include/net/sock.h:1975
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_timer.c (ffffffff81aceb61)
Location: include/net/sock.h:1975
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81b2644a)
Location: include/net/sock.h:1975
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/xfrm/espintcp.c (ffffffff81b31d4e)
Location: include/net/sock.h:1975
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_init_sk
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
In net/ipv4/tcp.c (ffffffff81aa4043)
Location: include/net/sock.h:1992
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_timer.c (ffffffff81ab9d02)
Location: include/net/sock.h:1992
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81b13fe7)
Location: include/net/sock.h:1992
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/xfrm/espintcp.c (ffffffff81b1fa6e)
Location: include/net/sock.h:1992
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_init_sk
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
In net/ipv4/tcp.c (ffffffff81b60258)
Location: include/net/sock.h:2032
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_timer.c (ffffffff81b77149)
Location: include/net/sock.h:2032
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd80e7)
Location: include/net/sock.h:2032
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/xfrm/espintcp.c (ffffffff81be470e)
Location: include/net/sock.h:2032
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_init_sk
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
In net/ipv4/tcp.c (ffffffff81ceeb97)
Location: include/net/sock.h:2153
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_timer.c (ffffffff81d06a7f)
Location: include/net/sock.h:2153
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6efab)
Location: include/net/sock.h:2153
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/xfrm/espintcp.c (ffffffff81d7bbfe)
Location: include/net/sock.h:2153
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_init_sk
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
In net/ipv4/tcp.c (ffffffff81eb1e10)
Location: include/net/sock.h:2190
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_timer.c (ffffffff81ecbce1)
Location: include/net/sock.h:2190
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3a901)
Location: include/net/sock.h:2190
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/xfrm/espintcp.c (ffffffff81f48cce)
Location: include/net/sock.h:2190
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_init_sk
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
In net/ipv4/tcp.c (ffffffff81f104be)
Location: include/net/sock.h:2178
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_timer.c (ffffffff81f2a8ab)
Location: include/net/sock.h:2178
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9a321)
Location: include/net/sock.h:2178
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/xfrm/espintcp.c (ffffffff81fa816e)
Location: include/net/sock.h:2178
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_init_sk
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
In net/ipv4/tcp.c (ffffffff81fd46b9)
Location: include/net/sock.h:2168
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_timer.c (ffffffff81fef46c)
Location: include/net/sock.h:2168
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff82067681)
Location: include/net/sock.h:2168
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/xfrm/espintcp.c (ffffffff8207545d)
Location: include/net/sock.h:2168
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_init_sk
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
In net/ipv4/tcp.c (ffff800010c760ac)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_timer.c (ffff800010c891ec)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/xfrm/xfrm_state.c (ffff800010ce2948)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
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
In net/ipv4/tcp.c (c0d847b8)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_timer.c (c0d98244)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/xfrm/xfrm_state.c (c0dec0d0)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
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
In net/ipv4/tcp.c (c000000000d7db34)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_timer.c (c000000000d96464)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/xfrm/xfrm_state.c (c000000000e05a68)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
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
In net/ipv4/tcp.c (ffffffe0007d92aa)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_timer.c (ffffffe0007ea152)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/xfrm/xfrm_state.c (ffffffe000831280)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
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
In net/ipv4/tcp.c (ffffffff8196329e)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_timer.c (ffffffff8197604f)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff819c4b1c)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
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
In net/ipv4/tcp.c (ffffffff8191cd8e)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_timer.c (ffffffff8192fb0f)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff8198190c)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
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
In net/ipv4/tcp.c (ffffffff819cda6e)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_timer.c (ffffffff819e081f)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2f59c)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
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
In net/ipv4/tcp.c (ffffffff819d75fe)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_timer.c (ffffffff819ea4df)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3aefa)
Location: include/net/sock.h:1907
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
</details>
</li>
</ul>

## Differences
