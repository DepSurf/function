# Function: <code>is_multicast_ether_addr_64bits</code>

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
In net/ethernet/eth.c (ffffffff817401e3)
Location: include/linux/etherdevice.h:128
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/ethernet/eth.c (ffffffff817acf83)
Location: include/linux/etherdevice.h:128
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/ethernet/eth.c (ffffffff817dc5d3)
Location: include/linux/etherdevice.h:128
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/ethernet/eth.c (ffffffff817fbc93)
Location: include/linux/etherdevice.h:133
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/ethernet/eth.c (ffffffff81879653)
Location: include/linux/etherdevice.h:134
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/ethernet/eth.c (ffffffff818cb033)
Location: include/linux/etherdevice.h:134
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/dev.c (ffffffff818b541b)
Location: include/linux/etherdevice.h:134
Inline: True
```
```
In net/ethernet/eth.c (ffffffff818f6270)
Location: include/linux/etherdevice.h:134
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/dev.c (ffffffff818fab71)
Location: include/linux/etherdevice.h:130
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/ethernet/eth.c (0)
Location: include/linux/etherdevice.h:130
Inline: True
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
In net/core/dev.c (ffffffff8192cc95)
Location: include/linux/etherdevice.h:130
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/ethernet/eth.c (0)
Location: include/linux/etherdevice.h:130
Inline: True
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
In net/core/dev.c (ffffffff81a066d1)
Location: include/linux/etherdevice.h:130
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/ethernet/eth.c (0)
Location: include/linux/etherdevice.h:130
Inline: True
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
In net/core/dev.c (ffffffff81a07c85)
Location: include/linux/etherdevice.h:130
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/ethernet/eth.c (0)
Location: include/linux/etherdevice.h:130
Inline: True
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
In net/core/dev.c (ffffffff819ea65f)
Location: include/linux/etherdevice.h:130
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/ethernet/eth.c (0)
Location: include/linux/etherdevice.h:130
Inline: True
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
In net/core/dev.c (ffffffff81aa1c6a)
Location: include/linux/etherdevice.h:130
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/ethernet/eth.c (0)
Location: include/linux/etherdevice.h:130
Inline: True
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
In net/core/dev.c (ffffffff81c19e42)
Location: include/linux/etherdevice.h:137
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/ethernet/eth.c (0)
Location: include/linux/etherdevice.h:137
Inline: True
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
In net/core/dev.c (ffffffff81dcaec2)
Location: include/linux/etherdevice.h:137
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/ethernet/eth.c (0)
Location: include/linux/etherdevice.h:137
Inline: True
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
In net/core/dev.c (ffffffff81e3ba53)
Location: include/linux/etherdevice.h:137
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/ethernet/eth.c (0)
Location: include/linux/etherdevice.h:137
Inline: True
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
In net/core/dev.c (ffffffff81ef9f93)
Location: include/linux/etherdevice.h:137
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/ethernet/eth.c (0)
Location: include/linux/etherdevice.h:137
Inline: True
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
In net/core/dev.c (ffff800010bcf598)
Location: include/linux/etherdevice.h:130
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/ethernet/eth.c (0)
Location: include/linux/etherdevice.h:130
Inline: True
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
In net/core/dev.c (c0ce5950)
Location: include/linux/etherdevice.h:130
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/ethernet/eth.c (0)
Location: include/linux/etherdevice.h:130
Inline: True
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
In net/core/dev.c (c000000000ca63c4)
Location: include/linux/etherdevice.h:130
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/ethernet/eth.c (0)
Location: include/linux/etherdevice.h:130
Inline: True
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
In net/core/dev.c (ffffffe000755aae)
Location: include/linux/etherdevice.h:130
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/ethernet/eth.c (ffffffe0007a8750)
Location: include/linux/etherdevice.h:130
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
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
In net/core/dev.c (ffffffff818ccc95)
Location: include/linux/etherdevice.h:130
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/ethernet/eth.c (0)
Location: include/linux/etherdevice.h:130
Inline: True
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
In net/core/dev.c (ffffffff81886d25)
Location: include/linux/etherdevice.h:130
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/ethernet/eth.c (0)
Location: include/linux/etherdevice.h:130
Inline: True
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
In net/core/dev.c (ffffffff8191dc95)
Location: include/linux/etherdevice.h:130
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/ethernet/eth.c (0)
Location: include/linux/etherdevice.h:130
Inline: True
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
In net/core/dev.c (ffffffff8193f305)
Location: include/linux/etherdevice.h:130
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/ethernet/eth.c (0)
Location: include/linux/etherdevice.h:130
Inline: True
```
</details>
</li>
</ul>

## Differences
