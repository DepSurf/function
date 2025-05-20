# Function: <code>sk_backlog_rcv</code>

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
In net/core/sock.c (ffffffff81702283)
Location: include/net/sock.h:865
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:sk_receive_skb
```
```
In net/ipv4/tcp.c (ffffffff81766509)
Location: include/net/sock.h:865
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_prequeue_process
```
```
In net/ipv4/tcp_timer.c (ffffffff81779e33)
Location: include/net/sock.h:865
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177d1e6)
Location: include/net/sock.h:865
Inline: True
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
In net/core/sock.c (ffffffff81769485)
Location: include/net/sock.h:867
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp.c (ffffffff817d2a3e)
Location: include/net/sock.h:867
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_prequeue_process
```
```
In net/ipv4/tcp_timer.c (ffffffff817e704e)
Location: include/net/sock.h:867
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ea891)
Location: include/net/sock.h:867
Inline: True
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
In net/core/sock.c (ffffffff81796395)
Location: include/net/sock.h:888
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp.c (ffffffff818025ce)
Location: include/net/sock.h:888
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_prequeue_process
```
```
In net/ipv4/tcp_timer.c (ffffffff81817780)
Location: include/net/sock.h:888
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181ae31)
Location: include/net/sock.h:888
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
In net/core/sock.c (ffffffff817b4573)
Location: include/net/sock.h:902
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/ipv4/tcp.c (ffffffff8182270f)
Location: include/net/sock.h:902
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_prequeue_process
```
```
In net/ipv4/tcp_timer.c (ffffffff81837ba2)
Location: include/net/sock.h:902
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183b632)
Location: include/net/sock.h:902
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182c7c3)
Location: include/net/sock.h:902
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8187692f)
Location: include/net/sock.h:909
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818987bf)
Location: include/net/sock.h:937
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818e2d66)
Location: include/net/sock.h:940
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81914f46)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e8066)
Location: include/net/sock.h:996
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e7cd6)
Location: include/net/sock.h:1011
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819cdca6)
Location: include/net/sock.h:1015
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a7d486)
Location: include/net/sock.h:1027
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81bf0ae4)
Location: include/net/sock.h:1070
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d9d154)
Location: include/net/sock.h:1108
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e0b9a4)
Location: include/net/sock.h:1110
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec8394)
Location: include/net/sock.h:1087
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010badd44)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0ccb858)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c83740)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe00073fe1c)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b4f46)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186ee96)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81905f46)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81926f76)
Location: include/net/sock.h:950
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
</details>
</li>
</ul>

## Differences
