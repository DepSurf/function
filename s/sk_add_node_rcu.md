# Function: <code>sk_add_node_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff8180408f)
Location: include/net/sock.h:644
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
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
In net/ipv4/udp.c (ffffffff817f4b26)
Location: include/net/sock.h:637
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (ffffffff8187506b)
Location: include/net/sock.h:637
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
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
In net/ipv4/udp.c (ffffffff81825bed)
Location: include/net/sock.h:658
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (ffffffff818a952b)
Location: include/net/sock.h:658
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
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
In net/ipv4/udp.c (ffffffff81847bee)
Location: include/net/sock.h:672
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (ffffffff818d027f)
Location: include/net/sock.h:672
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
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
In net/ipv4/udp.c (ffffffff818c763e)
Location: include/net/sock.h:676
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (ffffffff81955193)
Location: include/net/sock.h:676
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
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
In net/ipv4/udp.c (ffffffff8191e77f)
Location: include/net/sock.h:683
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (ffffffff819aed8e)
Location: include/net/sock.h:683
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
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
In net/ipv4/udp.c (ffffffff8194d57f)
Location: include/net/sock.h:703
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
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
In net/ipv4/udp.c (ffffffff819b1d3e)
Location: include/net/sock.h:705
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/xdp/xsk.c (ffffffff81a746a9)
Location: include/net/sock.h:705
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In net/ipv4/udp.c (ffffffff819e8ac4)
Location: include/net/sock.h:705
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/xdp/xsk.c (ffffffff81aab058)
Location: include/net/sock.h:705
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In net/ipv4/udp.c (ffffffff81ad6e59)
Location: include/net/sock.h:747
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/xdp/xsk.c (ffffffff81ba6fd8)
Location: include/net/sock.h:747
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In net/ipv4/udp.c (ffffffff81ae3439)
Location: include/net/sock.h:754
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/xdp/xsk.c (ffffffff81bb6317)
Location: include/net/sock.h:754
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In net/ipv4/udp.c (ffffffff81ace345)
Location: include/net/sock.h:754
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/xdp/xsk.c (ffffffff81ba6687)
Location: include/net/sock.h:754
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In net/ipv4/udp.c (ffffffff81b8cd0e)
Location: include/net/sock.h:766
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/xdp/xsk.c (ffffffff81c741d7)
Location: include/net/sock.h:766
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In net/ipv4/udp.c (ffffffff81d1b407)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/xdp/xsk.c (ffffffff81e17a87)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
```
```
In net/mctp/af_mctp.c (ffffffff81e37aff)
Location: include/net/sock.h:805
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_hash
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
In net/ipv4/udp.c (ffffffff81ee1dfd)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/xdp/xsk.c (ffffffff81feea37)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
```
```
In net/mctp/af_mctp.c (ffffffff82010d6f)
Location: include/net/sock.h:831
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_hash
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
In net/ipv4/raw.c (ffffffff81f3bc18)
Location: include/net/sock.h:833
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81f41819)
Location: include/net/sock.h:833
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff81f6c540)
Location: include/net/sock.h:833
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_port
```
```
In net/xdp/xsk.c (ffffffff8206ab5f)
Location: include/net/sock.h:833
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
```
```
In net/mctp/af_mctp.c (ffffffff8208d5d5)
Location: include/net/sock.h:833
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_hash
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
In net/ipv4/raw.c (ffffffff82001d38)
Location: include/net/sock.h:816
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff82007479)
Location: include/net/sock.h:816
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff82032c90)
Location: include/net/sock.h:816
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_port
```
```
In net/xdp/xsk.c (ffffffff8213e26f)
Location: include/net/sock.h:816
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
```
```
In net/mctp/af_mctp.c (ffffffff82163a95)
Location: include/net/sock.h:816
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_hash
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
In net/ipv4/udp.c (ffff800010c9c058)
Location: include/net/sock.h:705
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/xdp/xsk.c (ffff800010d7e6dc)
Location: include/net/sock.h:705
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In net/ipv4/udp.c (c0da8744)
Location: include/net/sock.h:705
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/xdp/xsk.c (c0e790f0)
Location: include/net/sock.h:705
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In net/ipv4/udp.c (c000000000dae0e4)
Location: include/net/sock.h:705
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/xdp/xsk.c (c000000000ebe6ec)
Location: include/net/sock.h:705
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In net/ipv4/udp.c (ffffffe0007fb092)
Location: include/net/sock.h:705
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/xdp/xsk.c (ffffffe0008ac100)
Location: include/net/sock.h:705
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In net/ipv4/udp.c (ffffffff81988934)
Location: include/net/sock.h:705
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/xdp/xsk.c (ffffffff81a4a3e8)
Location: include/net/sock.h:705
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In net/ipv4/udp.c (ffffffff819423f4)
Location: include/net/sock.h:705
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/xdp/xsk.c (ffffffff81a06fd8)
Location: include/net/sock.h:705
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In net/ipv4/udp.c (ffffffff819f3104)
Location: include/net/sock.h:705
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/xdp/xsk.c (ffffffff81ab6298)
Location: include/net/sock.h:705
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In net/ipv4/udp.c (ffffffff819fb9cf)
Location: include/net/sock.h:705
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/xdp/xsk.c (ffffffff81ac23b8)
Location: include/net/sock.h:705
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
```
</details>
</li>
</ul>

## Differences
