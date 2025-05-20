# Function: <code>neigh_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int neigh_update(struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81728610)
Location: net/core/neighbour.c:1075
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_event_ns
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_rcv
```
**Symbols:**

```
ffffffff81728610-ffffffff81728d77: neigh_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int neigh_update(struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81792170)
Location: net/core/neighbour.c:1073
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_event_ns
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ndisc.c:ndisc_update
```
**Symbols:**

```
ffffffff81792170-ffffffff81792855: neigh_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int neigh_update(struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff817bfa40)
Location: net/core/neighbour.c:1074
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_event_ns
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ndisc.c:ndisc_update
```
**Symbols:**

```
ffffffff817bfa40-ffffffff817c012e: neigh_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int neigh_update(struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff817de0c0)
Location: net/core/neighbour.c:1110
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_event_ns
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ndisc.c:ndisc_update
```
**Symbols:**

```
ffffffff817de0c0-ffffffff817de7a8: neigh_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int neigh_update(struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81858920)
Location: net/core/neighbour.c:1110
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_event_ns
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ndisc.c:ndisc_update
```
**Symbols:**

```
ffffffff81858920-ffffffff81859020: neigh_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int neigh_update(struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff818a3d90)
Location: net/core/neighbour.c:1121
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_event_ns
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ndisc.c:ndisc_update
```
**Symbols:**

```
ffffffff818a3d90-ffffffff818a4545: neigh_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int neigh_update(struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff818c830f)
Location: net/core/neighbour.c:1399
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
Direct callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ndisc.c:ndisc_update
```
**Symbols:**

```
ffffffff818c7ae0-ffffffff818c7af6: neigh_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int neigh_update(struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81914df0)
Location: net/core/neighbour.c:1413
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
Direct callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ndisc.c:ndisc_update
```
**Symbols:**

```
ffffffff819141e0-ffffffff819141f6: neigh_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int neigh_update(struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81947460)
Location: net/core/neighbour.c:1410
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
Direct callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ndisc.c:ndisc_update
```
**Symbols:**

```
ffffffff81946850-ffffffff81946866: neigh_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int neigh_update(struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81a175b0)
Location: net/core/neighbour.c:1411
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
Direct callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81a16d20-ffffffff81a16d36: neigh_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int neigh_update(struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81a17880)
Location: net/core/neighbour.c:1414
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
Direct callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81a16c50-ffffffff81a16c66: neigh_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int neigh_update(struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff819fe790)
Location: net/core/neighbour.c:1418
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
Direct callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff819fd8e0-ffffffff819fd8f6: neigh_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int neigh_update(struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81ab08f3)
Location: net/core/neighbour.c:1419
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
Direct callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81aaff00-ffffffff81aaff16: neigh_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int neigh_update(struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81c29988)
Location: net/core/neighbour.c:1465
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
Direct callers:
  - net/ipv4/arp.c:arp_invalidate
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81c28e70-ffffffff81c28e98: neigh_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int neigh_update(struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81ddc6b8)
Location: net/core/neighbour.c:1505
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
Direct callers:
  - net/ipv4/arp.c:arp_invalidate
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81ddbb70-ffffffff81ddbb98: neigh_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int neigh_update(struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81e4d438)
Location: net/core/neighbour.c:1474
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
Direct callers:
  - net/ipv4/arp.c:arp_invalidate
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81e4c8c0-ffffffff81e4c8e8: neigh_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int neigh_update(struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81f0c198)
Location: net/core/neighbour.c:1485
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
Direct callers:
  - net/ipv4/arp.c:arp_invalidate
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
**Symbols:**

```
ffffffff81f0b5d0-ffffffff81f0b5f8: neigh_update (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int neigh_update(struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffff800010be885c)
Location: net/core/neighbour.c:1410
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
Direct callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ndisc.c:ndisc_update
```
**Symbols:**

```
ffff800010be6778-ffff800010be67d8: neigh_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int neigh_update(struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (c0d01a30)
Location: net/core/neighbour.c:1410
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
Direct callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ndisc.c:ndisc_update
```
**Symbols:**

```
c0cfef88-c0cfefb8: neigh_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int neigh_update(struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (c000000000ccade0)
Location: net/core/neighbour.c:1410
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
Direct callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ndisc.c:ndisc_update
```
**Symbols:**

```
c000000000cc8170-c000000000cc8188: neigh_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int neigh_update(struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffe00076ccbe)
Location: net/core/neighbour.c:1410
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
Direct callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ndisc.c:ndisc_update
```
**Symbols:**

```
ffffffe00076b2a8-ffffffe00076b2f4: neigh_update (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int neigh_update(struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff818e7430)
Location: net/core/neighbour.c:1410
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
Direct callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ndisc.c:ndisc_update
```
**Symbols:**

```
ffffffff818e6820-ffffffff818e6836: neigh_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int neigh_update(struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff818a1270)
Location: net/core/neighbour.c:1410
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
Direct callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ndisc.c:ndisc_update
```
**Symbols:**

```
ffffffff818a0660-ffffffff818a0676: neigh_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int neigh_update(struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81938460)
Location: net/core/neighbour.c:1410
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
Direct callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ndisc.c:ndisc_update
```
**Symbols:**

```
ffffffff81937850-ffffffff81937866: neigh_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int neigh_update(struct neighbour *neigh, const u8 *lladdr, u8 new, u32 flags, u32 nlmsg_pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81959c70)
Location: net/core/neighbour.c:1410
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
Direct callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv6/ndisc.c:ndisc_update
```
**Symbols:**

```
ffffffff81959020-ffffffff81959036: neigh_update (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 nlmsg_pid</code>
</li>
</ul>
</details>
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
