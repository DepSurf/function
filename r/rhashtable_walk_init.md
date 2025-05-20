# Function: <code>rhashtable_walk_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int rhashtable_walk_init(struct rhashtable *ht, struct rhashtable_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff813ffea0)
Location: lib/rhashtable.c:510
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_walk_start
```
**Symbols:**

```
ffffffff813ffea0-ffffffff813fff3c: rhashtable_walk_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int rhashtable_walk_init(struct rhashtable *ht, struct rhashtable_iter *iter, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff814475c0)
Location: lib/rhashtable.c:514
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_walk_start
```
**Symbols:**

```
ffffffff814475c0-ffffffff81447669: rhashtable_walk_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817e7342)
Location: include/linux/rhashtable.h:1170
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_walk_start
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81807042)
Location: include/linux/rhashtable.h:1236
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_walk_start
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81885df2)
Location: include/linux/rhashtable.h:1238
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_walk_start
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818d980b)
Location: include/linux/rhashtable.h:1249
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81905ffb)
Location: include/linux/rhashtable.h:1117
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
</ul>
</details>
</li>
</ul>
