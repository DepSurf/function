# Function: <code>nf_hook_egress</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c199ab)
Location: include/linux/netfilter_netdev.h:85
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/packet/af_packet.c (ffffffff81df1716)
Location: include/linux/netfilter_netdev.h:85
Inline: True
Inline callers:
  - net/packet/af_packet.c:nf_hook_direct_egress
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
In net/core/dev.c (ffffffff81dcabc6)
Location: include/linux/netfilter_netdev.h:85
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/packet/af_packet.c (ffffffff81fc56b6)
Location: include/linux/netfilter_netdev.h:85
Inline: True
Inline callers:
  - net/packet/af_packet.c:nf_hook_direct_egress
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
In net/core/dev.c (ffffffff81e3b5c4)
Location: include/linux/netfilter_netdev.h:85
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/packet/af_packet.c (ffffffff820262c6)
Location: include/linux/netfilter_netdev.h:85
Inline: True
Inline callers:
  - net/packet/af_packet.c:nf_hook_direct_egress
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
In net/core/dev.c (ffffffff81ef9921)
Location: include/linux/netfilter_netdev.h:85
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/packet/af_packet.c (ffffffff820f5cd6)
Location: include/linux/netfilter_netdev.h:85
Inline: True
Inline callers:
  - net/packet/af_packet.c:nf_hook_direct_egress
```
</details>
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
