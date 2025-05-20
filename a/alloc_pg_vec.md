# Function: <code>alloc_pg_vec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8174d7a6)
Location: net/netlink/af_netlink.c:355
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81805451)
Location: net/packet/af_packet.c:4036
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81875fce)
Location: net/packet/af_packet.c:4129
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
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
In net/packet/af_packet.c (ffffffff818aa4d8)
Location: net/packet/af_packet.c:4102
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
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
In net/packet/af_packet.c (ffffffff818d1007)
Location: net/packet/af_packet.c:4175
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
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
In net/packet/af_packet.c (ffffffff81955f17)
Location: net/packet/af_packet.c:4174
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
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
In net/packet/af_packet.c (ffffffff819b1165)
Location: net/packet/af_packet.c:4179
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
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
In net/packet/af_packet.c (ffffffff819e8549)
Location: net/packet/af_packet.c:4208
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a5884f)
Location: net/packet/af_packet.c:4241
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a8e93a)
Location: net/packet/af_packet.c:4260
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b85b00)
Location: net/packet/af_packet.c:4271
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81b85b00-ffffffff81b85bdd: alloc_pg_vec.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b95510)
Location: net/packet/af_packet.c:4267
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81b95510-ffffffff81b955ed: alloc_pg_vec.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b84600)
Location: net/packet/af_packet.c:4281
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81b84600-ffffffff81b846dd: alloc_pg_vec.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:4282
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81c50a90-ffffffff81c50b7e: alloc_pg_vec.isra.0 (STB_LOCAL)
ffffffff81d41914-ffffffff81d4192e: alloc_pg_vec.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:4337
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81df1cd0-ffffffff81df1dc7: alloc_pg_vec.isra.0 (STB_LOCAL)
ffffffff81f0e2a0-ffffffff81f0e2ba: alloc_pg_vec.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:4336
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81fc5d70-ffffffff81fc5e67: alloc_pg_vec.isra.0 (STB_LOCAL)
ffffffff820b53f4-ffffffff820b540e: alloc_pg_vec.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:4357
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff820263f0-ffffffff820264e7: alloc_pg_vec.isra.0 (STB_LOCAL)
ffffffff821362d2-ffffffff821362ec: alloc_pg_vec.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:4358
Inline: True
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff820f5e00-ffffffff820f5ef7: alloc_pg_vec.isra.0 (STB_LOCAL)
ffffffff82217ebf-ffffffff82217ed9: alloc_pg_vec.isra.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffff800010d5bb18)
Location: net/packet/af_packet.c:4260
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (c0e5bc64)
Location: net/packet/af_packet.c:4260
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (c000000000e974b0)
Location: net/packet/af_packet.c:4260
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffe000891e8e)
Location: net/packet/af_packet.c:4260
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a2dfca)
Location: net/packet/af_packet.c:4260
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819eb1ba)
Location: net/packet/af_packet.c:4260
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a99b7a)
Location: net/packet/af_packet.c:4260
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81aa68ab)
Location: net/packet/af_packet.c:4260
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
</details>
</li>
</ul>

## Differences
