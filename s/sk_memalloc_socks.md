# Function: <code>sk_memalloc_socks</code>

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
Location: include/net/sock.h:768
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff81706b95)
Location: include/net/sock.h:768
Inline: True
Inline callers:
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__napi_alloc_skb
```
```
In net/core/dev.c (ffffffff8171ab1c)
Location: include/net/sock.h:768
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81766509)
Location: include/net/sock.h:768
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_prequeue_process
```
```
In net/ipv4/tcp_timer.c (ffffffff81779e33)
Location: include/net/sock.h:768
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177d1e6)
Location: include/net/sock.h:768
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
Location: include/net/sock.h:770
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff81773a2d)
Location: include/net/sock.h:770
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/dev.c (ffffffff8178302c)
Location: include/net/sock.h:770
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff817d2a3e)
Location: include/net/sock.h:770
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_prequeue_process
```
```
In net/ipv4/tcp_timer.c (ffffffff817e704e)
Location: include/net/sock.h:770
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ea891)
Location: include/net/sock.h:770
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
Location: include/net/sock.h:791
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff817a0c5d)
Location: include/net/sock.h:791
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/dev.c (ffffffff817b08cc)
Location: include/net/sock.h:791
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff818025ce)
Location: include/net/sock.h:791
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_prequeue_process
```
```
In net/ipv4/tcp_timer.c (ffffffff81817780)
Location: include/net/sock.h:791
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181ae31)
Location: include/net/sock.h:791
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
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff817bb37e)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/dev.c (ffffffff817cf16c)
Location: include/net/sock.h:805
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff8182270f)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_prequeue_process
```
```
In net/ipv4/tcp_timer.c (ffffffff81837ba2)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183b632)
Location: include/net/sock.h:805
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
In net/core/sock.c (ffffffff8182c7c3)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff818333ee)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/dev.c (ffffffff81848aac)
Location: include/net/sock.h:805
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
In net/core/sock.c (ffffffff8187692f)
Location: include/net/sock.h:812
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff8187d88d)
Location: include/net/sock.h:812
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/dev.c (ffffffff81892b05)
Location: include/net/sock.h:812
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
In net/core/sock.c (ffffffff818987bf)
Location: include/net/sock.h:840
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff8189e49d)
Location: include/net/sock.h:840
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/dev.c (ffffffff818b7ffb)
Location: include/net/sock.h:840
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list
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
In net/core/sock.c (ffffffff818e2d66)
Location: include/net/sock.h:843
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff818e8d02)
Location: include/net/sock.h:843
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/dev.c (ffffffff81904250)
Location: include/net/sock.h:843
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list
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
In net/core/sock.c (ffffffff81914f46)
Location: include/net/sock.h:848
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff8191ae62)
Location: include/net/sock.h:848
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/dev.c (ffffffff8193539f)
Location: include/net/sock.h:848
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In net/core/sock.c (ffffffff819e8066)
Location: include/net/sock.h:890
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff819ed442)
Location: include/net/sock.h:890
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/dev.c (ffffffff81a09f94)
Location: include/net/sock.h:890
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_list
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
In net/core/sock.c (ffffffff819e7cd6)
Location: include/net/sock.h:905
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff819ed10b)
Location: include/net/sock.h:905
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/dev.c (ffffffff81a0b534)
Location: include/net/sock.h:905
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_list
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
In net/core/sock.c (ffffffff819cdca6)
Location: include/net/sock.h:905
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff819d0279)
Location: include/net/sock.h:905
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/dev.c (ffffffff819f1b78)
Location: include/net/sock.h:905
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In net/core/sock.c (ffffffff81a7d486)
Location: include/net/sock.h:917
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff81a8140a)
Location: include/net/sock.h:917
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/dev.c (ffffffff81aa3498)
Location: include/net/sock.h:917
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In net/core/sock.c (ffffffff81bf0ae4)
Location: include/net/sock.h:957
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff81bf50f5)
Location: include/net/sock.h:957
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/dev.c (ffffffff81c1bba1)
Location: include/net/sock.h:957
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In net/core/sock.c (ffffffff81d9d154)
Location: include/net/sock.h:995
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff81da44bd)
Location: include/net/sock.h:995
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/dev.c (ffffffff81dccb71)
Location: include/net/sock.h:995
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In net/core/sock.c (ffffffff81e0b9a4)
Location: include/net/sock.h:997
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff81e1310e)
Location: include/net/sock.h:997
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/dev.c (ffffffff81e3d6d1)
Location: include/net/sock.h:997
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In net/core/sock.c (ffffffff81ec8394)
Location: include/net/sock.h:968
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff81ed02ce)
Location: include/net/sock.h:968
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/dev.c (ffffffff81efbf71)
Location: include/net/sock.h:968
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In net/core/sock.c (ffff800010badd44)
Location: include/net/sock.h:848
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffff800010bb51cc)
Location: include/net/sock.h:848
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/dev.c (ffff800010bd3638)
Location: include/net/sock.h:848
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In net/core/sock.c (c0ccb858)
Location: include/net/sock.h:848
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (c0cd22b8)
Location: include/net/sock.h:848
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/dev.c (c0cee360)
Location: include/net/sock.h:848
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In net/core/sock.c (c000000000c83740)
Location: include/net/sock.h:848
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (c000000000c8c1a4)
Location: include/net/sock.h:848
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/dev.c (c000000000cb2220)
Location: include/net/sock.h:848
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In net/core/sock.c (ffffffe00073fe20)
Location: include/net/sock.h:848
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffe000745268)
Location: include/net/sock.h:848
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/dev.c (ffffffe00075d83a)
Location: include/net/sock.h:848
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In net/core/sock.c (ffffffff818b4f46)
Location: include/net/sock.h:848
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff818bae62)
Location: include/net/sock.h:848
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/dev.c (ffffffff818d5373)
Location: include/net/sock.h:848
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In net/core/sock.c (ffffffff8186ee96)
Location: include/net/sock.h:848
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff81874da2)
Location: include/net/sock.h:848
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/dev.c (ffffffff8188f1e3)
Location: include/net/sock.h:848
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In net/core/sock.c (ffffffff81905f46)
Location: include/net/sock.h:848
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff8190be62)
Location: include/net/sock.h:848
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/dev.c (ffffffff8192639f)
Location: include/net/sock.h:848
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In net/core/sock.c (ffffffff81926f76)
Location: include/net/sock.h:848
Inline: True
Inline callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff8192cf82)
Location: include/net/sock.h:848
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/dev.c (ffffffff81947944)
Location: include/net/sock.h:848
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
```
</details>
</li>
</ul>

## Differences
