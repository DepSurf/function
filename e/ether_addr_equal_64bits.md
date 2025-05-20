# Function: <code>ether_addr_equal_64bits</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff817401ea)
Location: include/linux/etherdevice.h:342
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/8021q/vlan_core.c (ffffffff818096c3)
Location: include/linux/etherdevice.h:342
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/ethernet/eth.c (ffffffff817acf8a)
Location: include/linux/etherdevice.h:342
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/8021q/vlan_core.c (ffffffff8187b1cb)
Location: include/linux/etherdevice.h:342
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/ethernet/eth.c (ffffffff817dc5da)
Location: include/linux/etherdevice.h:342
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/8021q/vlan_core.c (ffffffff818afa8b)
Location: include/linux/etherdevice.h:342
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/ethernet/eth.c (ffffffff817fbc9e)
Location: include/linux/etherdevice.h:347
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/8021q/vlan_core.c (ffffffff818d6253)
Location: include/linux/etherdevice.h:347
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/ethernet/eth.c (ffffffff8187965e)
Location: include/linux/etherdevice.h:348
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/8021q/vlan_core.c (ffffffff8195bf1b)
Location: include/linux/etherdevice.h:348
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/ethernet/eth.c (ffffffff818cb03e)
Location: include/linux/etherdevice.h:348
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/8021q/vlan_core.c (ffffffff819b561a)
Location: include/linux/etherdevice.h:348
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/ethernet/eth.c (ffffffff818f61da)
Location: include/linux/etherdevice.h:348
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/8021q/vlan_core.c (ffffffff819ec8e5)
Location: include/linux/etherdevice.h:348
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/ethernet/eth.c (ffffffff8195581b)
Location: include/linux/etherdevice.h:344
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/8021q/vlan_core.c (ffffffff81a5ba8f)
Location: include/linux/etherdevice.h:344
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/ethernet/eth.c (ffffffff8198bcbb)
Location: include/linux/etherdevice.h:344
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/8021q/vlan_core.c (ffffffff81a92808)
Location: include/linux/etherdevice.h:344
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/ethernet/eth.c (ffffffff81a6396b)
Location: include/linux/etherdevice.h:355
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/8021q/vlan_core.c (ffffffff81b8dcbb)
Location: include/linux/etherdevice.h:355
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/ethernet/eth.c (ffffffff81a6bacb)
Location: include/linux/etherdevice.h:355
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/8021q/vlan_core.c (ffffffff81b9d98a)
Location: include/linux/etherdevice.h:355
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/dev.c (ffffffff819ea646)
Location: include/linux/etherdevice.h:355
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/ethernet/eth.c (ffffffff81a5425b)
Location: include/linux/etherdevice.h:355
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/8021q/vlan_core.c (ffffffff81b8cab3)
Location: include/linux/etherdevice.h:355
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/dev.c (ffffffff81aa1c4c)
Location: include/linux/etherdevice.h:367
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/ethernet/eth.c (ffffffff81b0cf6d)
Location: include/linux/etherdevice.h:367
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/8021q/vlan_core.c (ffffffff81c58e73)
Location: include/linux/etherdevice.h:367
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/dev.c (ffffffff81c19e29)
Location: include/linux/etherdevice.h:375
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/ethernet/eth.c (ffffffff81c938a3)
Location: include/linux/etherdevice.h:375
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/8021q/vlan_core.c (ffffffff81dfa526)
Location: include/linux/etherdevice.h:375
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/dev.c (ffffffff81dcaea9)
Location: include/linux/etherdevice.h:375
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/ethernet/eth.c (ffffffff81e4efd3)
Location: include/linux/etherdevice.h:375
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/8021q/vlan_core.c (ffffffff81fcec47)
Location: include/linux/etherdevice.h:375
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/dev.c (ffffffff81e3ba35)
Location: include/linux/etherdevice.h:375
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/ethernet/eth.c (ffffffff81eaa673)
Location: include/linux/etherdevice.h:375
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/8021q/vlan_core.c (ffffffff8204a47c)
Location: include/linux/etherdevice.h:375
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/dev.c (ffffffff81ef9f75)
Location: include/linux/etherdevice.h:375
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/ethernet/eth.c (ffffffff81f6d123)
Location: include/linux/etherdevice.h:375
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/8021q/vlan_core.c (ffffffff8211c8e8)
Location: include/linux/etherdevice.h:375
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/ethernet/eth.c (ffff800010c36d40)
Location: include/linux/etherdevice.h:344
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/8021q/vlan_core.c (ffff800010d60448)
Location: include/linux/etherdevice.h:344
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/ethernet/eth.c (c0d49694)
Location: include/linux/etherdevice.h:344
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/8021q/vlan_core.c (c0e60088)
Location: include/linux/etherdevice.h:344
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/ethernet/eth.c (c000000000d2ed44)
Location: include/linux/etherdevice.h:344
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/8021q/vlan_core.c (c000000000e9b670)
Location: include/linux/etherdevice.h:344
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/ethernet/eth.c (ffffffe0007a86de)
Location: include/linux/etherdevice.h:344
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/8021q/vlan_core.c (ffffffe000895982)
Location: include/linux/etherdevice.h:344
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/ethernet/eth.c (ffffffff8192bb2b)
Location: include/linux/etherdevice.h:344
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/8021q/vlan_core.c (ffffffff81a31e98)
Location: include/linux/etherdevice.h:344
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/ethernet/eth.c (ffffffff818e58db)
Location: include/linux/etherdevice.h:344
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/8021q/vlan_core.c (ffffffff819ef088)
Location: include/linux/etherdevice.h:344
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/ethernet/eth.c (ffffffff8197ccbb)
Location: include/linux/etherdevice.h:344
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/8021q/vlan_core.c (ffffffff81a9da48)
Location: include/linux/etherdevice.h:344
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/ethernet/eth.c (ffffffff8199f22b)
Location: include/linux/etherdevice.h:344
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/8021q/vlan_core.c (ffffffff81aa9c48)
Location: include/linux/etherdevice.h:344
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
</details>
</li>
</ul>

## Differences
