# Function: <code>rhashtable_walk_start_check</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rhashtable_walk_start_check(struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff814ccf80)
Location: lib/rhashtable.c:726
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
**Symbols:**

```
ffffffff814ccf80-ffffffff814cd0ef: rhashtable_walk_start_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rhashtable_walk_start_check(struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff814e1530)
Location: lib/rhashtable.c:718
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
**Symbols:**

```
ffffffff814e1530-ffffffff814e169f: rhashtable_walk_start_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rhashtable_walk_start_check(struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8150d300)
Location: lib/rhashtable.c:707
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
**Symbols:**

```
ffffffff8150d300-ffffffff8150d4d0: rhashtable_walk_start_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rhashtable_walk_start_check(struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8152b150)
Location: lib/rhashtable.c:707
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
**Symbols:**

```
ffffffff8152b150-ffffffff8152b320: rhashtable_walk_start_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rhashtable_walk_start_check(struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8158f4d0)
Location: lib/rhashtable.c:714
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
**Symbols:**

```
ffffffff8158f4d0-ffffffff8158f651: rhashtable_walk_start_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rhashtable_walk_start_check(struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff815ac000)
Location: lib/rhashtable.c:714
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
**Symbols:**

```
ffffffff815ac000-ffffffff815ac181: rhashtable_walk_start_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rhashtable_walk_start_check(struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff815b6ca0)
Location: lib/rhashtable.c:714
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
**Symbols:**

```
ffffffff815b6ca0-ffffffff815b6e27: rhashtable_walk_start_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int rhashtable_walk_start_check(struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (0)
Location: lib/rhashtable.c:714
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
**Symbols:**

```
ffffffff81cdad17-ffffffff81cdad41: rhashtable_walk_start_check.cold (STB_LOCAL)
ffffffff8161d220-ffffffff8161d3c1: rhashtable_walk_start_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int rhashtable_walk_start_check(struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (0)
Location: lib/rhashtable.c:714
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
**Symbols:**

```
ffffffff81e935a1-ffffffff81e935cb: rhashtable_walk_start_check.cold (STB_LOCAL)
ffffffff816ea7c0-ffffffff816ea96e: rhashtable_walk_start_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int rhashtable_walk_start_check(struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (0)
Location: lib/rhashtable.c:718
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
**Symbols:**

```
ffffffff82078723-ffffffff8207874d: rhashtable_walk_start_check.cold (STB_LOCAL)
ffffffff817daa30-ffffffff817dabde: rhashtable_walk_start_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int rhashtable_walk_start_check(struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (0)
Location: lib/rhashtable.c:718
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
**Symbols:**

```
ffffffff820f8c77-ffffffff820f8ca1: rhashtable_walk_start_check.cold (STB_LOCAL)
ffffffff81819ca0-ffffffff81819e4e: rhashtable_walk_start_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int rhashtable_walk_start_check(struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (0)
Location: lib/rhashtable.c:718
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
```
**Symbols:**

```
ffffffff821d6798-ffffffff821d67c2: rhashtable_walk_start_check.cold (STB_LOCAL)
ffffffff8185eff0-ffffffff8185f19e: rhashtable_walk_start_check (STB_GLOBAL)
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
int rhashtable_walk_start_check(struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffff800010636768)
Location: lib/rhashtable.c:707
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
**Symbols:**

```
ffff800010636768-ffff800010636990: rhashtable_walk_start_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rhashtable_walk_start_check(struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (c07dc458)
Location: lib/rhashtable.c:707
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
**Symbols:**

```
c07dc458-c07dc650: rhashtable_walk_start_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rhashtable_walk_start_check(struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (c0000000007dbc60)
Location: lib/rhashtable.c:707
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
**Symbols:**

```
c0000000007dbc60-c0000000007dbefc: rhashtable_walk_start_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rhashtable_walk_start_check(struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffe00046390a)
Location: lib/rhashtable.c:707
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
**Symbols:**

```
ffffffe00046390a-ffffffe000463a82: rhashtable_walk_start_check (STB_GLOBAL)
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
int rhashtable_walk_start_check(struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81523730)
Location: lib/rhashtable.c:707
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
**Symbols:**

```
ffffffff81523730-ffffffff81523900: rhashtable_walk_start_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rhashtable_walk_start_check(struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81513a10)
Location: lib/rhashtable.c:707
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
**Symbols:**

```
ffffffff81513a10-ffffffff81513be0: rhashtable_walk_start_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rhashtable_walk_start_check(struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8151f7c0)
Location: lib/rhashtable.c:707
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
**Symbols:**

```
ffffffff8151f7c0-ffffffff8151f990: rhashtable_walk_start_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rhashtable_walk_start_check(struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81539090)
Location: lib/rhashtable.c:707
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
**Symbols:**

```
ffffffff81539090-ffffffff81539265: rhashtable_walk_start_check (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
