# Function: <code>busy_loop_current_time</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81269ba6)
Location: include/net/busy_poll.h:73
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8129dce6)
Location: include/net/busy_poll.h:73
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In net/core/sock.c (ffffffff817b30ff)
Location: include/net/busy_poll.h:73
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (ffffffff817cd5fd)
Location: include/net/busy_poll.h:73
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
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
In fs/select.c (ffffffff8128c446)
Location: include/net/busy_poll.h:73
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff812c0ed6)
Location: include/net/busy_poll.h:73
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In net/core/sock.c (ffffffff8182b3df)
Location: include/net/busy_poll.h:73
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (ffffffff81846d2d)
Location: include/net/busy_poll.h:73
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
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
In fs/select.c (ffffffff812b2c3e)
Location: include/net/busy_poll.h:73
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff812e9e05)
Location: include/net/busy_poll.h:73
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In net/core/sock.c (ffffffff818754f1)
Location: include/net/busy_poll.h:73
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (ffffffff8189039d)
Location: include/net/busy_poll.h:73
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
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
In fs/select.c (ffffffff812c7d53)
Location: include/net/busy_poll.h:73
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff812fe98e)
Location: include/net/busy_poll.h:73
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In net/core/sock.c (ffffffff81895dc1)
Location: include/net/busy_poll.h:73
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (ffffffff818b0c4d)
Location: include/net/busy_poll.h:73
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
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
In fs/select.c (ffffffff812e48fa)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8131fb55)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In net/core/sock.c (ffffffff818e02d1)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (ffffffff818fd9ed)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
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
In fs/select.c (ffffffff812f6309)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff81332905)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In net/core/sock.c (ffffffff81912484)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (ffffffff8193575d)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
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
In fs/select.c (ffffffff8132e0c5)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8136cbe8)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In net/core/sock.c (ffffffff819e4307)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (ffffffff81a0a41d)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
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
In fs/select.c (ffffffff8133993d)
Location: include/net/busy_poll.h:63
Inline: True
Inline callers:
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8137a698)
Location: include/net/busy_poll.h:63
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In net/core/sock.c (ffffffff819e3b87)
Location: include/net/busy_poll.h:63
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (ffffffff81a0c746)
Location: include/net/busy_poll.h:63
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
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
In fs/select.c (ffffffff8133fed3)
Location: include/net/busy_poll.h:63
Inline: True
Inline callers:
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff81381310)
Location: include/net/busy_poll.h:63
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In net/core/sock.c (ffffffff819c9c12)
Location: include/net/busy_poll.h:63
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (ffffffff819f2a26)
Location: include/net/busy_poll.h:63
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
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
In fs/select.c (ffffffff8138d8a9)
Location: include/net/busy_poll.h:63
Inline: True
Inline callers:
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff813ce550)
Location: include/net/busy_poll.h:63
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In net/core/sock.c (ffffffff81a790b2)
Location: include/net/busy_poll.h:63
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (ffffffff81aa48f6)
Location: include/net/busy_poll.h:63
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
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
In fs/select.c (ffffffff8140ec50)
Location: include/net/busy_poll.h:63
Inline: True
Inline callers:
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff814575ed)
Location: include/net/busy_poll.h:63
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In net/core/sock.c (ffffffff81becdae)
Location: include/net/busy_poll.h:63
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (ffffffff81c1c05e)
Location: include/net/busy_poll.h:63
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
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
In fs/select.c (ffffffff81499752)
Location: include/net/busy_poll.h:63
Inline: True
Inline callers:
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff814e688d)
Location: include/net/busy_poll.h:63
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In net/core/sock.c (ffffffff81d9932e)
Location: include/net/busy_poll.h:63
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (ffffffff81dcd03e)
Location: include/net/busy_poll.h:63
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
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
In fs/select.c (ffffffff814ce8b8)
Location: include/net/busy_poll.h:63
Inline: True
Inline callers:
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8151d3fd)
Location: include/net/busy_poll.h:63
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In net/core/sock.c (ffffffff81e0764e)
Location: include/net/busy_poll.h:63
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (ffffffff81e3db9e)
Location: include/net/busy_poll.h:63
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
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
In fs/select.c (ffffffff815011f8)
Location: include/net/busy_poll.h:64
Inline: True
Inline callers:
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff815519dd)
Location: include/net/busy_poll.h:64
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In net/core/sock.c (ffffffff81ec4070)
Location: include/net/busy_poll.h:64
Inline: True
```
```
In net/core/dev.c (ffffffff81efc43e)
Location: include/net/busy_poll.h:64
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
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
In fs/select.c (ffff8000103a35c0)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffff8000103f016c)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In net/core/sock.c (ffff800010ba9fd8)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (ffff800010bd3b28)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
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
In fs/select.c (c0585d60)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (c05c61b8)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In net/core/sock.c (c0cc866c)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (c0cee810)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
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
In fs/select.c (c00000000049d248)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (c0000000004f7cf0)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In net/core/sock.c (c000000000c7f898)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (c000000000cb28b0)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
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
In fs/select.c (ffffffe00026b3f4)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffe0002a2f8a)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In net/core/sock.c (ffffffe00073d506)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (ffffffe00075dc40)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
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
In fs/select.c (ffffffff812ee8e9)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8132aee5)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In net/core/sock.c (ffffffff818b2484)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (ffffffff818d572d)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
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
In fs/select.c (ffffffff812df519)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8131ba85)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In net/core/sock.c (ffffffff8186c3d4)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (ffffffff8188f59d)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
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
In fs/select.c (ffffffff812ec6f9)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff813289b5)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In net/core/sock.c (ffffffff81903484)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (ffffffff8192675d)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
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
In fs/select.c (ffffffff812fd6f9)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8133a7d5)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_busy_loop_end
```
```
In net/core/sock.c (ffffffff81924464)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - net/core/sock.c:sk_busy_loop_end
```
```
In net/core/dev.c (ffffffff81947d5d)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
```
</details>
</li>
</ul>

## Differences
