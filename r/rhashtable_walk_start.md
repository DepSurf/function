# Function: <code>rhashtable_walk_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int rhashtable_walk_start(struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff813ffcf0)
Location: lib/rhashtable.c:561
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_walk_start
```
**Symbols:**

```
ffffffff813ffcf0-ffffffff813ffd6f: rhashtable_walk_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int rhashtable_walk_start(struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff814473f0)
Location: lib/rhashtable.c:566
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_walk_start
```
**Symbols:**

```
ffffffff814473f0-ffffffff81447471: rhashtable_walk_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int rhashtable_walk_start(struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81465cf0)
Location: lib/rhashtable.c:654
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_walk_start
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
**Symbols:**

```
ffffffff81465cf0-ffffffff81465d69: rhashtable_walk_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rhashtable_walk_start(struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8146ade0)
Location: lib/rhashtable.c:748
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_walk_start
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
**Symbols:**

```
ffffffff8146ade0-ffffffff8146ae55: rhashtable_walk_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rhashtable_walk_start(struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff814970c0)
Location: lib/rhashtable.c:750
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_walk_start
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
**Symbols:**

```
ffffffff814970c0-ffffffff81497135: rhashtable_walk_start (STB_GLOBAL)
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
In net/netlink/af_netlink.c (ffffffff818d9829)
Location: include/linux/rhashtable.h:392
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/ipv6/seg6.c (ffffffff8199ba0f)
Location: include/linux/rhashtable.h:392
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
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
In net/netlink/af_netlink.c (ffffffff81906019)
Location: include/linux/rhashtable.h:253
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/ipv6/seg6.c (ffffffff819d25df)
Location: include/linux/rhashtable.h:253
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
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
In net/netlink/af_netlink.c (ffffffff81967fe3)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/ipv6/seg6.c (ffffffff81a4140f)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
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
In net/core/xdp.c (ffffffff81962adc)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/netlink/af_netlink.c (ffffffff8199ea83)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/ipv6/seg6.c (ffffffff81a7808f)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
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
In net/core/xdp.c (ffffffff81a362fc)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/netlink/af_netlink.c (ffffffff81a76fc3)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/ipv6/seg6.c (ffffffff81b720fc)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
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
In net/core/xdp.c (ffffffff81a386cc)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/netlink/af_netlink.c (ffffffff81a7fd53)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/ipv6/seg6.c (ffffffff81b80e5c)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
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
In net/core/xdp.c (ffffffff81a1f4fc)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/netlink/af_netlink.c (ffffffff81a68cd3)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/ipv6/seg6.c (ffffffff81b6f9bf)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
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
In net/core/xdp.c (ffffffff81ad379c)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/netlink/af_netlink.c (ffffffff81b22293)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/ipv6/seg6.c (ffffffff81c37b0f)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ioam6.c (ffffffff81c3932f)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
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
In net/core/xdp.c (ffffffff81c50f72)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/netlink/af_netlink.c (ffffffff81caae72)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/ipv6/seg6.c (ffffffff81dd56d4)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ioam6.c (ffffffff81dd6bdf)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
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
In net/core/xdp.c (ffffffff81e06612)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/netlink/af_netlink.c (ffffffff81e67fd2)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/ipv6/seg6.c (ffffffff81fa6e64)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ioam6.c (ffffffff81fa857f)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
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
In net/core/xdp.c (ffffffff81e78e92)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/netlink/af_netlink.c (ffffffff81ec3e42)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/ipv6/seg6.c (ffffffff820076c4)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ioam6.c (ffffffff82008f0f)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
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
In net/core/xdp.c (ffffffff81f38d62)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/netlink/af_netlink.c (ffffffff81f87202)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/ipv6/seg6.c (ffffffff820d6554)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ioam6.c (ffffffff820d7e7f)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc
  - net/ipv6/ioam6.c:ioam6_genl_dumpns
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
In net/core/xdp.c (ffff800010c06150)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/netlink/af_netlink.c (ffff800010c4b474)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/ipv6/seg6.c (ffff800010d41638)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
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
In net/core/xdp.c (c0d1f51c)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/netlink/af_netlink.c (c0d5ca0c)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/ipv6/seg6.c (c0e44014)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
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
In net/core/xdp.c (c000000000cf0620)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/netlink/af_netlink.c (c000000000d4a4c4)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/ipv6/seg6.c (c000000000e75e9c)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
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
In net/core/xdp.c (ffffffe000784862)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/netlink/af_netlink.c (ffffffe0007b94ca)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/ipv6/seg6.c (ffffffe00087cd26)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
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
In net/core/xdp.c (ffffffff81902aac)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/netlink/af_netlink.c (ffffffff8193e8f3)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/ipv6/seg6.c (ffffffff81a1771f)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
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
In net/core/xdp.c (ffffffff818bc8dc)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/netlink/af_netlink.c (ffffffff818f83f3)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/ipv6/seg6.c (ffffffff819d44df)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
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
In net/core/xdp.c (ffffffff81953adc)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/netlink/af_netlink.c (ffffffff8198fa83)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/ipv6/seg6.c (ffffffff81a8219f)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
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
In net/core/xdp.c (ffffffff8197567c)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/netlink/af_netlink.c (ffffffff819b2363)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_start
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/ipv6/seg6.c (ffffffff81a8eaaf)
Location: include/linux/rhashtable.h:250
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
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
</ul>
