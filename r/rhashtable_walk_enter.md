# Function: <code>rhashtable_walk_enter</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rhashtable_walk_enter(struct rhashtable *ht, struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81465c20)
Location: lib/rhashtable.c:610
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_walk_start
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
**Symbols:**

```
ffffffff81465c20-ffffffff81465c8c: rhashtable_walk_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rhashtable_walk_enter(struct rhashtable *ht, struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8146ad10)
Location: lib/rhashtable.c:704
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_walk_start
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
**Symbols:**

```
ffffffff8146ad10-ffffffff8146ad76: rhashtable_walk_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rhashtable_walk_enter(struct rhashtable *ht, struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81496ff0)
Location: lib/rhashtable.c:706
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_walk_start
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
**Symbols:**

```
ffffffff81496ff0-ffffffff81497056: rhashtable_walk_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rhashtable_walk_enter(struct rhashtable *ht, struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff814cce40)
Location: lib/rhashtable.c:677
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
**Symbols:**

```
ffffffff814cce40-ffffffff814cceaa: rhashtable_walk_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rhashtable_walk_enter(struct rhashtable *ht, struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff814e1450)
Location: lib/rhashtable.c:669
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
**Symbols:**

```
ffffffff814e1450-ffffffff814e14ba: rhashtable_walk_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rhashtable_walk_enter(struct rhashtable *ht, struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8150d210)
Location: lib/rhashtable.c:658
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
**Symbols:**

```
ffffffff8150d210-ffffffff8150d27a: rhashtable_walk_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rhashtable_walk_enter(struct rhashtable *ht, struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8152b060)
Location: lib/rhashtable.c:658
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
**Symbols:**

```
ffffffff8152b060-ffffffff8152b0ca: rhashtable_walk_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rhashtable_walk_enter(struct rhashtable *ht, struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8158edf0)
Location: lib/rhashtable.c:665
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
**Symbols:**

```
ffffffff8158edf0-ffffffff8158ee5a: rhashtable_walk_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rhashtable_walk_enter(struct rhashtable *ht, struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff815ab960)
Location: lib/rhashtable.c:665
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
**Symbols:**

```
ffffffff815ab960-ffffffff815ab9ca: rhashtable_walk_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rhashtable_walk_enter(struct rhashtable *ht, struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff815b6bb0)
Location: lib/rhashtable.c:665
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
**Symbols:**

```
ffffffff815b6bb0-ffffffff815b6c1a: rhashtable_walk_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rhashtable_walk_enter(struct rhashtable *ht, struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8161d130)
Location: lib/rhashtable.c:665
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc_start
  - net/ipv6/ioam6.c:ioam6_genl_dumpns_start
```
**Symbols:**

```
ffffffff8161d130-ffffffff8161d19a: rhashtable_walk_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rhashtable_walk_enter(struct rhashtable *ht, struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff816e9350)
Location: lib/rhashtable.c:665
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc_start
  - net/ipv6/ioam6.c:ioam6_genl_dumpns_start
```
**Symbols:**

```
ffffffff816e9350-ffffffff816e93c6: rhashtable_walk_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rhashtable_walk_enter(struct rhashtable *ht, struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff817d9470)
Location: lib/rhashtable.c:669
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc_start
  - net/ipv6/ioam6.c:ioam6_genl_dumpns_start
```
**Symbols:**

```
ffffffff817d9470-ffffffff817d94e6: rhashtable_walk_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rhashtable_walk_enter(struct rhashtable *ht, struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81818680)
Location: lib/rhashtable.c:669
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc_start
  - net/ipv6/ioam6.c:ioam6_genl_dumpns_start
```
**Symbols:**

```
ffffffff81818680-ffffffff818186f6: rhashtable_walk_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rhashtable_walk_enter(struct rhashtable *ht, struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8185d980)
Location: lib/rhashtable.c:669
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc_start
  - net/ipv6/ioam6.c:ioam6_genl_dumpns_start
```
**Symbols:**

```
ffffffff8185d980-ffffffff8185d9f6: rhashtable_walk_enter (STB_GLOBAL)
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
void rhashtable_walk_enter(struct rhashtable *ht, struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffff8000106365f0)
Location: lib/rhashtable.c:658
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
**Symbols:**

```
ffff8000106365f0-ffff800010636698: rhashtable_walk_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rhashtable_walk_enter(struct rhashtable *ht, struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (c07db854)
Location: lib/rhashtable.c:658
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
**Symbols:**

```
c07db854-c07db8c8: rhashtable_walk_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rhashtable_walk_enter(struct rhashtable *ht, struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (c0000000007db320)
Location: lib/rhashtable.c:658
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
**Symbols:**

```
c0000000007db320-c0000000007db40c: rhashtable_walk_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rhashtable_walk_enter(struct rhashtable *ht, struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffe0004637d0)
Location: lib/rhashtable.c:658
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
**Symbols:**

```
ffffffe0004637d0-ffffffe00046385e: rhashtable_walk_enter (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void rhashtable_walk_enter(struct rhashtable *ht, struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81523640)
Location: lib/rhashtable.c:658
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
**Symbols:**

```
ffffffff81523640-ffffffff815236aa: rhashtable_walk_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rhashtable_walk_enter(struct rhashtable *ht, struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81513920)
Location: lib/rhashtable.c:658
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
**Symbols:**

```
ffffffff81513920-ffffffff8151398a: rhashtable_walk_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rhashtable_walk_enter(struct rhashtable *ht, struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8151f6d0)
Location: lib/rhashtable.c:658
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
**Symbols:**

```
ffffffff8151f6d0-ffffffff8151f73a: rhashtable_walk_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rhashtable_walk_enter(struct rhashtable *ht, struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff815384d0)
Location: lib/rhashtable.c:658
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
```
**Symbols:**

```
ffffffff815384d0-ffffffff81538538: rhashtable_walk_enter (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
