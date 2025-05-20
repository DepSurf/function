# Function: <code>neigh_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void neigh_destroy(struct neighbour *neigh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81727560)
Location: net/core/neighbour.c:683
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ip6_fib.c:fib6_age
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
**Symbols:**

```
ffffffff81727560-ffffffff81727693: neigh_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void neigh_destroy(struct neighbour *neigh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81791080)
Location: net/core/neighbour.c:683
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ip6_fib.c:fib6_age
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81791080-ffffffff817911ad: neigh_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void neigh_destroy(struct neighbour *neigh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff817be940)
Location: net/core/neighbour.c:684
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ip6_fib.c:fib6_age
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff817be940-ffffffff817bea6d: neigh_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void neigh_destroy(struct neighbour *neigh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff817dc190)
Location: net/core/neighbour.c:719
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ip6_fib.c:fib6_age
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff817dc190-ffffffff817dc2bf: neigh_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void neigh_destroy(struct neighbour *neigh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81857f70)
Location: net/core/neighbour.c:719
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81857f70-ffffffff818580a8: neigh_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void neigh_destroy(struct neighbour *neigh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:729
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff818a5722-ffffffff818a574c: neigh_destroy.cold.58 (STB_LOCAL)
ffffffff818a3380-ffffffff818a349a: neigh_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void neigh_destroy(struct neighbour *neigh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:827
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff818c8cd9-ffffffff818c8d03: neigh_destroy.cold.67 (STB_LOCAL)
ffffffff818c6440-ffffffff818c655a: neigh_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void neigh_destroy(struct neighbour *neigh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:831
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff819158de-ffffffff81915908: neigh_destroy.cold (STB_LOCAL)
ffffffff819124e0-ffffffff81912606: neigh_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void neigh_destroy(struct neighbour *neigh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:828
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81947eb5-ffffffff81947edf: neigh_destroy.cold (STB_LOCAL)
ffffffff81944b50-ffffffff81944c76: neigh_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void neigh_destroy(struct neighbour *neigh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:828
Inline: False
Direct callers:
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
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_get
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81a1809b-ffffffff81a180b4: neigh_destroy.cold (STB_LOCAL)
ffffffff81a14f90-ffffffff81a1511d: neigh_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void neigh_destroy(struct neighbour *neigh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:830
Inline: False
Direct callers:
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
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_get
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81c31603-ffffffff81c3161c: neigh_destroy.cold (STB_LOCAL)
ffffffff81a15290-ffffffff81a1541d: neigh_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void neigh_destroy(struct neighbour *neigh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:834
Inline: False
Direct callers:
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
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_get
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81c2390c-ffffffff81c23925: neigh_destroy.cold (STB_LOCAL)
ffffffff819fbdf0-ffffffff819fbf7d: neigh_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void neigh_destroy(struct neighbour *neigh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:829
Inline: False
Direct callers:
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
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_get
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81d36bad-ffffffff81d36bc6: neigh_destroy.cold (STB_LOCAL)
ffffffff81aade30-ffffffff81aadfc2: neigh_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void neigh_destroy(struct neighbour *neigh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:874
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/arp.c:arp_invalidate
  - net/ipv4/arp.c:arp_invalidate
  - net/ipv4/arp.c:arp_req_get
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81f034a6-ffffffff81f034bf: neigh_destroy.cold (STB_LOCAL)
ffffffff81c26b50-ffffffff81c26ceb: neigh_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void neigh_destroy(struct neighbour *neigh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81dd9570)
Location: net/core/neighbour.c:912
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/arp.c:arp_invalidate
  - net/ipv4/arp.c:arp_invalidate
  - net/ipv4/arp.c:arp_req_get
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81dd9570-ffffffff81dd9739: neigh_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void neigh_destroy(struct neighbour *neigh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81e4a2c0)
Location: net/core/neighbour.c:881
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/arp.c:arp_invalidate
  - net/ipv4/arp.c:arp_invalidate
  - net/ipv4/arp.c:arp_req_get
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81e4a2c0-ffffffff81e4a487: neigh_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void neigh_destroy(struct neighbour *neigh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81f08fe0)
Location: net/core/neighbour.c:889
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/arp.c:arp_invalidate
  - net/ipv4/arp.c:arp_invalidate
  - net/ipv4/arp.c:arp_req_get
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81f08fe0-ffffffff81f091a4: neigh_destroy (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void neigh_destroy(struct neighbour *neigh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffff800010be3518)
Location: net/core/neighbour.c:828
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffff800010be3518-ffff800010be3710: neigh_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void neigh_destroy(struct neighbour *neigh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (c0cfd35c)
Location: net/core/neighbour.c:828
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
c0cfd35c-c0cfd4ec: neigh_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void neigh_destroy(struct neighbour *neigh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (c000000000cc55e0)
Location: net/core/neighbour.c:828
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
c000000000cc55e0-c000000000cc5834: neigh_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void neigh_destroy(struct neighbour *neigh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffe00076949e)
Location: net/core/neighbour.c:828
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffe00076949e-ffffffe000769600: neigh_destroy (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void neigh_destroy(struct neighbour *neigh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:828
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff818e7e85-ffffffff818e7eaf: neigh_destroy.cold (STB_LOCAL)
ffffffff818e4b20-ffffffff818e4c46: neigh_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void neigh_destroy(struct neighbour *neigh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:828
Inline: False
Direct callers:
  - drivers/net/vxlan.c:route_shortcircuit
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/vxlan.c:neigh_reduce
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff818a1cc5-ffffffff818a1cef: neigh_destroy.cold (STB_LOCAL)
ffffffff8189e960-ffffffff8189ea86: neigh_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void neigh_destroy(struct neighbour *neigh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:828
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81938eb5-ffffffff81938edf: neigh_destroy.cold (STB_LOCAL)
ffffffff81935b50-ffffffff81935c76: neigh_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void neigh_destroy(struct neighbour *neigh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:828
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff8195a6c5-ffffffff8195a6ef: neigh_destroy.cold (STB_LOCAL)
ffffffff81957260-ffffffff81957386: neigh_destroy (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
