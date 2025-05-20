# Function: <code>trace_napi_poll</code>

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
In net/core/dev.c (ffffffff8171b071)
Location: include/trace/events/napi.h:13
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/core/netpoll.c (ffffffff81738f9e)
Location: include/trace/events/napi.h:13
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
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
In net/core/dev.c (ffffffff817838eb)
Location: include/trace/events/napi.h:13
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:sk_busy_loop
```
```
In net/core/netpoll.c (ffffffff817a5295)
Location: include/trace/events/napi.h:13
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
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
In net/core/dev.c (ffffffff817b0ea1)
Location: include/trace/events/napi.h:13
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:sk_busy_loop
```
```
In net/core/netpoll.c (ffffffff817d3cfe)
Location: include/trace/events/napi.h:13
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
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
In net/core/dev.c (ffffffff817d110b)
Location: include/trace/events/napi.h:13
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
```
```
In net/core/netpoll.c (ffffffff817f303e)
Location: include/trace/events/napi.h:13
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
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
In net/core/dev.c (ffffffff8184b200)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
```
```
In net/core/netpoll.c (ffffffff8186e434)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
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
In net/core/dev.c (ffffffff818955f9)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
```
```
In net/core/netpoll.c (ffffffff818bf5c1)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
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
In net/core/dev.c (ffffffff818b7273)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
```
```
In net/core/netpoll.c (ffffffff818e83e4)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
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
In net/core/dev.c (ffffffff8190309d)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
```
```
In net/core/netpoll.c (ffffffff81937bf4)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
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
In net/core/dev.c (ffffffff81935e3d)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
```
```
In net/core/netpoll.c (ffffffff8196aab4)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
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
In net/core/dev.c (ffffffff81a0aaf9)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/dev.c:napi_poll
  - net/core/dev.c:napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
```
```
In net/core/netpoll.c (ffffffff81a3e4ac)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
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
In net/core/dev.c (ffffffff81a0bd05)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/dev.c:napi_poll
  - net/core/dev.c:napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
```
```
In net/core/netpoll.c (ffffffff81a4125b)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
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
In net/core/dev.c (ffffffff819f2d04)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
```
```
In net/core/netpoll.c (ffffffff81a25ebb)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
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
In net/core/dev.c (ffffffff81aa3b66)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
```
```
In net/core/netpoll.c (ffffffff81adac1d)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
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
In net/core/dev.c (ffffffff81c1c536)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
```
```
In net/core/netpoll.c (ffffffff81c5bad0)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
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
In net/core/dev.c (ffffffff81dcd556)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
```
```
In net/core/netpoll.c (ffffffff81e11f00)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
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
In net/core/dev.c (ffffffff81e3e0b6)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
```
```
In net/core/netpoll.c (ffffffff81e85811)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
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
In net/core/dev.c (ffffffff81efc956)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
```
```
In net/core/netpoll.c (ffffffff81f47741)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/netpoll.c:poll_one_napi
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
In net/core/dev.c (ffff800010bd43b4)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
```
```
In net/core/netpoll.c (ffff800010c11080)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
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
In net/core/dev.c (c0cefc0c)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
```
```
In net/core/netpoll.c (c0d28f1c)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
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
In net/core/dev.c (c000000000cb3430)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
```
```
In net/core/netpoll.c (c000000000cfd54c)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
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
In net/core/dev.c (ffffffe00075e2d2)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
```
```
In net/core/netpoll.c (ffffffe00078d0e4)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
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
In net/core/dev.c (ffffffff818d5e0d)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
```
```
In net/core/netpoll.c (ffffffff8190aa84)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
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
In net/core/dev.c (ffffffff8188fc51)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
```
```
In net/core/netpoll.c (ffffffff818c4674)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
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
In net/core/dev.c (ffffffff81926e3d)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
```
```
In net/core/netpoll.c (ffffffff8195bab4)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
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
In net/core/dev.c (ffffffff8194848d)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
```
```
In net/core/netpoll.c (ffffffff8197dea4)
Location: include/trace/events/napi.h:14
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
</details>
</li>
</ul>

## Differences
