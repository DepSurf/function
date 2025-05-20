# Function: <code>neigh_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void neigh_release(struct neighbour *neigh);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff8172753d)
Location: include/net/neighbour.h:409
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
```
```
In net/ipv4/route.c (ffffffff81754c09)
Location: include/net/neighbour.h:409
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffffffff8178ba00)
Location: include/net/neighbour.h:409
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_ioctl
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/fib_semantics.c (ffffffff8179c0d9)
Location: include/net/neighbour.h:409
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
```
```
In net/ipv6/route.c (ffffffff817d7a1a)
Location: include/net/neighbour.h:409
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ip6_fib.c (ffffffff817d97dd)
Location: include/net/neighbour.h:409
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_age
```
```
In net/ipv6/ndisc.c (ffffffff817de250)
Location: include/net/neighbour.h:409
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_redirect
Direct callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff8178ba00-ffffffff8178ba12: neigh_release (STB_LOCAL)
ffffffff817de250-ffffffff817de262: neigh_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void neigh_release(struct neighbour *neigh);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81793028)
Location: include/net/neighbour.h:409
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/ipv4/route.c (ffffffff817c0d89)
Location: include/net/neighbour.h:409
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffffffff817fafdb)
Location: include/net/neighbour.h:409
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/fib_semantics.c (ffffffff81809c59)
Location: include/net/neighbour.h:409
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
```
```
In net/ipv6/route.c (ffffffff81846293)
Location: include/net/neighbour.h:409
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ip6_fib.c (ffffffff81847926)
Location: include/net/neighbour.h:409
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_age
```
```
In net/ipv6/ndisc.c (ffffffff8184f81d)
Location: include/net/neighbour.h:409
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff817f9070-ffffffff817f9082: neigh_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void neigh_release(struct neighbour *neigh);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff817c08f8)
Location: include/net/neighbour.h:409
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/ipv4/route.c (ffffffff817f02ee)
Location: include/net/neighbour.h:409
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffffffff8182be8b)
Location: include/net/neighbour.h:409
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/fib_semantics.c (ffffffff8183add9)
Location: include/net/neighbour.h:409
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
```
```
In net/ipv6/route.c (ffffffff81877ff3)
Location: include/net/neighbour.h:409
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ip6_fib.c (ffffffff81879766)
Location: include/net/neighbour.h:409
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_age
```
```
In net/ipv6/ndisc.c (ffffffff81881787)
Location: include/net/neighbour.h:409
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81829f40-ffffffff81829f52: neigh_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void neigh_release(struct neighbour *neigh);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff817df035)
Location: include/net/neighbour.h:412
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/ipv4/route.c (ffffffff8181037c)
Location: include/net/neighbour.h:412
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffffffff8184d2ed)
Location: include/net/neighbour.h:412
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/fib_semantics.c (ffffffff8185c2c9)
Location: include/net/neighbour.h:412
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
```
```
In net/ipv6/route.c (ffffffff8189d1c7)
Location: include/net/neighbour.h:412
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ip6_fib.c (ffffffff8189f0f8)
Location: include/net/neighbour.h:412
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_age
```
```
In net/ipv6/ndisc.c (ffffffff818a784c)
Location: include/net/neighbour.h:412
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff8184b180-ffffffff8184b193: neigh_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void neigh_release(struct neighbour *neigh);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff818598d5)
Location: include/net/neighbour.h:413
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/ipv4/route.c (ffffffff8188f9d8)
Location: include/net/neighbour.h:413
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffffffff818cd01d)
Location: include/net/neighbour.h:413
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/fib_semantics.c (ffffffff818dc1b9)
Location: include/net/neighbour.h:413
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
```
```
In net/ipv6/route.c (ffffffff8191cb66)
Location: include/net/neighbour.h:413
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff8192a2c6)
Location: include/net/neighbour.h:413
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff818cadf0-ffffffff818cae09: neigh_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void neigh_release(struct neighbour *neigh);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff818a4e6f)
Location: include/net/neighbour.h:414
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/ipv4/route.c (ffffffff818e37e0)
Location: include/net/neighbour.h:414
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffffffff81923501)
Location: include/net/neighbour.h:414
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/fib_semantics.c (ffffffff81932de9)
Location: include/net/neighbour.h:414
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
```
```
In net/ipv6/route.c (ffffffff8197525c)
Location: include/net/neighbour.h:414
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff81982541)
Location: include/net/neighbour.h:414
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81921300-ffffffff81921319: neigh_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void neigh_release(struct neighbour *neigh);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff818c6c70)
Location: include/net/neighbour.h:421
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/ipv4/route.c (ffffffff8191068a)
Location: include/net/neighbour.h:421
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffffffff819522f1)
Location: include/net/neighbour.h:421
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/fib_semantics.c (ffffffff81962679)
Location: include/net/neighbour.h:421
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
```
```
In net/ipv6/route.c (ffffffff819aaf13)
Location: include/net/neighbour.h:421
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff819b8bf1)
Location: include/net/neighbour.h:421
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81950110-ffffffff81950129: neigh_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void neigh_release(struct neighbour *neigh);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81912db7)
Location: include/net/neighbour.h:423
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/ipv4/route.c (ffffffff819730db)
Location: include/net/neighbour.h:423
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffffffff819b6bab)
Location: include/net/neighbour.h:423
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/fib_semantics.c (ffffffff819c7685)
Location: include/net/neighbour.h:423
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
```
```
In net/ipv6/route.c (ffffffff81a1820e)
Location: include/net/neighbour.h:423
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff81a276a4)
Location: include/net/neighbour.h:423
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff819b49d0-ffffffff819b49e8: neigh_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void neigh_release(struct neighbour *neigh);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81945417)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/ipv4/route.c (ffffffff819a9a51)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffffffff819ed8cb)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/fib_semantics.c (ffffffff819fe235)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
```
```
In net/ipv6/route.c (ffffffff81a4ee6e)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff81a5e104)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff819eb700-ffffffff819eb718: neigh_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void neigh_release(struct neighbour *neigh);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81a15e20)
Location: include/net/neighbour.h:421
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/ipv4/route.c (ffffffff81a92e96)
Location: include/net/neighbour.h:421
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffffffff81ada2aa)
Location: include/net/neighbour.h:421
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_get
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/fib_semantics.c (ffffffff81aed832)
Location: include/net/neighbour.h:421
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
```
```
In net/ipv6/route.c (ffffffff81b4670a)
Location: include/net/neighbour.h:421
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff81b56ed3)
Location: include/net/neighbour.h:421
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81ad9c00-ffffffff81ad9c33: neigh_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void neigh_release(struct neighbour *neigh);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81a16100)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/ipv4/route.c (ffffffff81a9cd3c)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffffffff81ae6d4a)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_get
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/fib_semantics.c (ffffffff81afa702)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
```
```
In net/ipv6/route.c (ffffffff81b5524f)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff81b65543)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81ae6650-ffffffff81ae6683: neigh_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void neigh_release(struct neighbour *neigh);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff819fcc6f)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/ipv4/route.c (ffffffff81a87dfe)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffffffff81ad2019)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_get
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae5d02)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
```
```
In net/ipv6/route.c (ffffffff81b42cc0)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff81b5382e)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81ad1920-ffffffff81ad1953: neigh_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void neigh_release(struct neighbour *neigh);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81aaecaf)
Location: include/net/neighbour.h:423
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/ipv4/route.c (ffffffff81b42345)
Location: include/net/neighbour.h:423
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffffffff81b90c69)
Location: include/net/neighbour.h:423
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_get
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba55c2)
Location: include/net/neighbour.h:423
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
```
```
In net/ipv6/route.c (ffffffff81c0841d)
Location: include/net/neighbour.h:423
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff81c1ad3e)
Location: include/net/neighbour.h:423
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81b90550-ffffffff81b90583: neigh_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void neigh_release(struct neighbour *neigh);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81c27a4b)
Location: include/net/neighbour.h:449
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/ipv4/route.c (ffffffff81cced51)
Location: include/net/neighbour.h:449
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffffffff81d235cc)
Location: include/net/neighbour.h:449
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_invalidate
  - net/ipv4/arp.c:arp_invalidate
  - net/ipv4/arp.c:arp_req_get
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/fib_semantics.c (ffffffff81d37f83)
Location: include/net/neighbour.h:449
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
```
```
In net/ipv6/route.c (ffffffff81da3207)
Location: include/net/neighbour.h:449
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff81db7347)
Location: include/net/neighbour.h:449
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81d21980-ffffffff81d219d7: neigh_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void neigh_release(struct neighbour *neigh);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81dda60b)
Location: include/net/neighbour.h:446
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
Direct callers:
  - net/core/neighbour.c:neigh_add
```
```
In net/ipv4/route.c (ffffffff81e8efbc)
Location: include/net/neighbour.h:446
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffffffff81eeabcc)
Location: include/net/neighbour.h:446
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_invalidate
  - net/ipv4/arp.c:arp_invalidate
  - net/ipv4/arp.c:arp_req_get
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/fib_semantics.c (ffffffff81f007d3)
Location: include/net/neighbour.h:446
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
```
```
In net/ipv6/route.c (ffffffff81f72617)
Location: include/net/neighbour.h:446
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff81f8701c)
Location: include/net/neighbour.h:446
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81dd9750-ffffffff81dd97a7: neigh_release (STB_LOCAL)
ffffffff81ee8da0-ffffffff81ee8df7: neigh_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void neigh_release(struct neighbour *neigh);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81e4b37b)
Location: include/net/neighbour.h:444
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
Direct callers:
  - net/core/neighbour.c:neigh_add
```
```
In net/ipv4/route.c (ffffffff81eed6cc)
Location: include/net/neighbour.h:444
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffffffff81f4a4b6)
Location: include/net/neighbour.h:444
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_invalidate
  - net/ipv4/arp.c:arp_invalidate
  - net/ipv4/arp.c:arp_req_get
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/fib_semantics.c (ffffffff81f60253)
Location: include/net/neighbour.h:444
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
```
```
In net/ipv6/route.c (ffffffff81fd270a)
Location: include/net/neighbour.h:444
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff81fe735c)
Location: include/net/neighbour.h:444
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81e4a4a0-ffffffff81e4a4f7: neigh_release (STB_LOCAL)
ffffffff81f48760-ffffffff81f487b7: neigh_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void neigh_release(struct neighbour *neigh);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81f0a09b)
Location: include/net/neighbour.h:442
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
Direct callers:
  - net/core/neighbour.c:neigh_add
```
```
In net/ipv4/route.c (ffffffff81fb1740)
Location: include/net/neighbour.h:442
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffffffff820105c6)
Location: include/net/neighbour.h:442
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_invalidate
  - net/ipv4/arp.c:arp_invalidate
  - net/ipv4/arp.c:arp_req_get
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/fib_semantics.c (ffffffff82026823)
Location: include/net/neighbour.h:442
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
```
```
In net/ipv6/route.c (ffffffff8209fc9a)
Location: include/net/neighbour.h:442
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff820b51bb)
Location: include/net/neighbour.h:442
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81f091c0-ffffffff81f09217: neigh_release (STB_LOCAL)
ffffffff8200e8c0-ffffffff8200e917: neigh_release (STB_LOCAL)
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
In net/core/neighbour.c (ffff800010be5690)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/ipv4/route.c (ffff800010c59618)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffff800010ca32cc)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/fib_semantics.c (ffff800010cb63c4)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
```
```
In net/ipv6/route.c (ffff800010d12ac8)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffff800010d231a4)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (c0d00330)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/ipv4/route.c (c0d691c4)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (c0db0004)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/fib_semantics.c (c0dc1eb8)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
```
```
In net/ipv6/route.c (c0e18968)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (c0e27cbc)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void neigh_release(struct neighbour *neigh);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (c000000000cc9880)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/ipv4/route.c (c000000000d5b40c)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (c000000000db6b58)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/fib_semantics.c (c000000000dce3b4)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
```
```
In net/ipv6/route.c (c000000000e3f1b8)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (c000000000e530d4)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
c000000000db42d0-c000000000db4324: neigh_release (STB_LOCAL)
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
In net/core/neighbour.c (ffffffe00076c1a0)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/ipv4/route.c (ffffffe0007c32c2)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffffffe0007ff270)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/fib_semantics.c (ffffffe00080dafc)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
```
```
In net/ipv6/route.c (ffffffe000858f46)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffe000864b92)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void neigh_release(struct neighbour *neigh);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff818e53e7)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/ipv4/route.c (ffffffff819498c1)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffffffff8198d66b)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/fib_semantics.c (ffffffff8199dfd5)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
```
```
In net/ipv6/route.c (ffffffff819ee4fe)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff819fd794)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff8198b570-ffffffff8198b588: neigh_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void neigh_release(struct neighbour *neigh);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/vxlan.c (ffffffff81773334)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - drivers/net/vxlan.c:route_shortcircuit
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/vxlan.c:neigh_reduce
Direct callers:
  - drivers/net/vxlan.c:vxlan_xmit
  - drivers/net/vxlan.c:vxlan_xmit
```
```
In net/core/neighbour.c (ffffffff8189f227)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/ipv4/route.c (ffffffff819033b1)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffffffff8194712b)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/fib_semantics.c (ffffffff81957a95)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
```
```
In net/ipv4/ip_tunnel.c (ffffffff819678a6)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
```
```
In net/ipv6/route.c (ffffffff819ab2be)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff819ba554)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff8176bcb0-ffffffff8176bcc8: neigh_release (STB_LOCAL)
ffffffff81945030-ffffffff81945048: neigh_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void neigh_release(struct neighbour *neigh);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81936417)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/ipv4/route.c (ffffffff819b4091)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffffffff819f7f0b)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/fib_semantics.c (ffffffff81a08875)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
```
```
In net/ipv6/route.c (ffffffff81a58f7e)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff81a68214)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff819f5d40-ffffffff819f5d58: neigh_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void neigh_release(struct neighbour *neigh);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81957ba7)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/ipv4/route.c (ffffffff819bd781)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffffffff81a0214b)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/fib_semantics.c (ffffffff81a12fd5)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
```
```
In net/ipv6/route.c (ffffffff81a6516f)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff81a74804)
Location: include/net/neighbour.h:422
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff819fff40-ffffffff819fff58: neigh_release (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
