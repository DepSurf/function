# Function: <code>busy_loop_timeout</code>

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
In fs/select.c (ffffffff81221763)
Location: include/net/busy_poll.h:68
Inline: True
Inline callers:
  - fs/select.c:do_select
  - fs/select.c:do_sys_poll
```
```
In net/socket.c (0)
Location: include/net/busy_poll.h:68
Inline: True
```
```
In net/core/datagram.c (ffffffff8170cd17)
Location: include/net/busy_poll.h:68
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff817676b6)
Location: include/net/busy_poll.h:68
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
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
In fs/select.c (ffffffff81249f62)
Location: include/net/busy_poll.h:68
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In net/core/dev.c (ffffffff8178345a)
Location: include/net/busy_poll.h:68
Inline: True
Inline callers:
  - net/core/dev.c:sk_busy_loop
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
In fs/select.c (ffffffff8125cf20)
Location: include/net/busy_poll.h:67
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In net/core/dev.c (ffffffff817aed22)
Location: include/net/busy_poll.h:67
Inline: True
Inline callers:
  - net/core/dev.c:sk_busy_loop
  - net/core/dev.c:sk_busy_loop
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
In fs/select.c (ffffffff812699ff)
Location: include/net/busy_poll.h:83
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8129dcd5)
Location: include/net/busy_poll.h:83
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
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
In fs/select.c (ffffffff8128c29f)
Location: include/net/busy_poll.h:83
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff812c0ec5)
Location: include/net/busy_poll.h:83
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
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
In fs/select.c (ffffffff812b2b7a)
Location: include/net/busy_poll.h:83
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff812e9def)
Location: include/net/busy_poll.h:83
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
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
In fs/select.c (ffffffff812c7c8f)
Location: include/net/busy_poll.h:83
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff812fe978)
Location: include/net/busy_poll.h:83
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
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
In fs/select.c (ffffffff812e47e3)
Location: include/net/busy_poll.h:71
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8131fb3c)
Location: include/net/busy_poll.h:71
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
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
In fs/select.c (ffffffff812f61aa)
Location: include/net/busy_poll.h:71
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff813328ec)
Location: include/net/busy_poll.h:71
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
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
In fs/select.c (ffffffff8132e0af)
Location: include/net/busy_poll.h:71
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8136cbcc)
Location: include/net/busy_poll.h:71
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
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
In fs/select.c (ffffffff81339927)
Location: include/net/busy_poll.h:73
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8137a67c)
Location: include/net/busy_poll.h:73
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
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
In fs/select.c (ffffffff8133febf)
Location: include/net/busy_poll.h:73
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff813812fc)
Location: include/net/busy_poll.h:73
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
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
In fs/select.c (ffffffff8138d895)
Location: include/net/busy_poll.h:73
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff813ce53c)
Location: include/net/busy_poll.h:73
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
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
In fs/select.c (ffffffff8140ea8b)
Location: include/net/busy_poll.h:73
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff814575d9)
Location: include/net/busy_poll.h:73
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
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
In fs/select.c (ffffffff81499733)
Location: include/net/busy_poll.h:73
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff814e6879)
Location: include/net/busy_poll.h:73
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
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
In fs/select.c (ffffffff814ce701)
Location: include/net/busy_poll.h:73
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8151d3e9)
Location: include/net/busy_poll.h:73
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
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
In fs/select.c (ffffffff81501041)
Location: include/net/busy_poll.h:74
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff815519c9)
Location: include/net/busy_poll.h:74
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
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
In fs/select.c (ffff8000103a3288)
Location: include/net/busy_poll.h:71
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffff8000103f0158)
Location: include/net/busy_poll.h:71
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
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
In fs/select.c (c0585c14)
Location: include/net/busy_poll.h:71
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (c05c61a0)
Location: include/net/busy_poll.h:71
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
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
In fs/select.c (c00000000049d070)
Location: include/net/busy_poll.h:71
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (c0000000004f7cc8)
Location: include/net/busy_poll.h:71
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
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
In fs/select.c (ffffffe00026b2aa)
Location: include/net/busy_poll.h:71
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffe0002a2f7e)
Location: include/net/busy_poll.h:71
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
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
In fs/select.c (ffffffff812ee78a)
Location: include/net/busy_poll.h:71
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8132aecc)
Location: include/net/busy_poll.h:71
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
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
In fs/select.c (ffffffff812df3ba)
Location: include/net/busy_poll.h:71
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8131ba6c)
Location: include/net/busy_poll.h:71
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
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
In fs/select.c (ffffffff812ec59a)
Location: include/net/busy_poll.h:71
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8132899c)
Location: include/net/busy_poll.h:71
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
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
In fs/select.c (ffffffff812fd59a)
Location: include/net/busy_poll.h:71
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8133a7bc)
Location: include/net/busy_poll.h:71
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
</details>
</li>
</ul>

## Differences
