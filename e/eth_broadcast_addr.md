# Function: <code>eth_broadcast_addr</code>

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
In net/ethernet/eth.c (ffffffff8173fee0)
Location: include/linux/etherdevice.h:236
Inline: True
Inline callers:
  - net/ethernet/eth.c:ether_setup
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
In net/ethernet/eth.c (ffffffff817acc20)
Location: include/linux/etherdevice.h:236
Inline: True
Inline callers:
  - net/ethernet/eth.c:ether_setup
```
```
In net/ncsi/ncsi-cmd.c (ffffffff8188c44a)
Location: include/linux/etherdevice.h:236
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In net/ethernet/eth.c (ffffffff817dc215)
Location: include/linux/etherdevice.h:236
Inline: True
Inline callers:
  - net/ethernet/eth.c:ether_setup
```
```
In net/ncsi/ncsi-cmd.c (ffffffff818c05f9)
Location: include/linux/etherdevice.h:236
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In net/ethernet/eth.c (ffffffff817fb7ca)
Location: include/linux/etherdevice.h:241
Inline: True
Inline callers:
  - net/ethernet/eth.c:ether_setup
```
```
In net/ncsi/ncsi-cmd.c (ffffffff818e6f67)
Location: include/linux/etherdevice.h:241
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In net/ethernet/eth.c (ffffffff8187917a)
Location: include/linux/etherdevice.h:242
Inline: True
Inline callers:
  - net/ethernet/eth.c:ether_setup
```
```
In net/ncsi/ncsi-cmd.c (ffffffff8196c420)
Location: include/linux/etherdevice.h:242
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In net/ethernet/eth.c (ffffffff818cab88)
Location: include/linux/etherdevice.h:242
Inline: True
Inline callers:
  - net/ethernet/eth.c:ether_setup
```
```
In net/ncsi/ncsi-cmd.c (ffffffff819c5ef4)
Location: include/linux/etherdevice.h:242
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In net/ethernet/eth.c (ffffffff818f5c58)
Location: include/linux/etherdevice.h:242
Inline: True
Inline callers:
  - net/ethernet/eth.c:ether_setup
```
```
In net/ncsi/ncsi-cmd.c (ffffffff819fd656)
Location: include/linux/etherdevice.h:242
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In net/ethernet/eth.c (ffffffff81955318)
Location: include/linux/etherdevice.h:238
Inline: True
Inline callers:
  - net/ethernet/eth.c:ether_setup
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81a6c8bd)
Location: include/linux/etherdevice.h:238
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In net/ethernet/eth.c (ffffffff8198b7b8)
Location: include/linux/etherdevice.h:238
Inline: True
Inline callers:
  - net/ethernet/eth.c:ether_setup
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81aa327d)
Location: include/linux/etherdevice.h:238
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In net/ethernet/eth.c (ffffffff81a63478)
Location: include/linux/etherdevice.h:238
Inline: True
Inline callers:
  - net/ethernet/eth.c:ether_setup
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81b9ecf2)
Location: include/linux/etherdevice.h:238
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In net/ethernet/eth.c (ffffffff81a6b5c8)
Location: include/linux/etherdevice.h:238
Inline: True
Inline callers:
  - net/ethernet/eth.c:ether_setup
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81bae6f2)
Location: include/linux/etherdevice.h:238
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In net/ethernet/eth.c (ffffffff81a53cf9)
Location: include/linux/etherdevice.h:238
Inline: True
Inline callers:
  - net/ethernet/eth.c:ether_setup
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81b9d810)
Location: include/linux/etherdevice.h:238
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In net/ethernet/eth.c (ffffffff81b0ca09)
Location: include/linux/etherdevice.h:238
Inline: True
Inline callers:
  - net/ethernet/eth.c:ether_setup
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81c6ada1)
Location: include/linux/etherdevice.h:238
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In net/ethernet/eth.c (ffffffff81c9345a)
Location: include/linux/etherdevice.h:243
Inline: True
Inline callers:
  - net/ethernet/eth.c:ether_setup
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81e0e4fd)
Location: include/linux/etherdevice.h:243
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In net/ethernet/eth.c (ffffffff81e4e91a)
Location: include/linux/etherdevice.h:243
Inline: True
Inline callers:
  - net/ethernet/eth.c:ether_setup
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81fe4911)
Location: include/linux/etherdevice.h:243
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In net/ethernet/eth.c (ffffffff81ea9fba)
Location: include/linux/etherdevice.h:243
Inline: True
Inline callers:
  - net/ethernet/eth.c:ether_setup
```
```
In net/ncsi/ncsi-cmd.c (ffffffff82060c21)
Location: include/linux/etherdevice.h:243
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In net/ethernet/eth.c (ffffffff81f6ca70)
Location: include/linux/etherdevice.h:243
Inline: True
Inline callers:
  - net/ethernet/eth.c:ether_setup
```
```
In net/ncsi/ncsi-cmd.c (ffffffff82133b3e)
Location: include/linux/etherdevice.h:243
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In net/ethernet/eth.c (ffff800010c36708)
Location: include/linux/etherdevice.h:238
Inline: True
Inline callers:
  - net/ethernet/eth.c:ether_setup
```
```
In net/ncsi/ncsi-cmd.c (ffff800010d74d3c)
Location: include/linux/etherdevice.h:238
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In net/ethernet/eth.c (c0d49110)
Location: include/linux/etherdevice.h:238
Inline: True
Inline callers:
  - net/ethernet/eth.c:ether_setup
```
```
In net/ncsi/ncsi-cmd.c (c0e71800)
Location: include/linux/etherdevice.h:238
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In net/ethernet/eth.c (c000000000d2e79c)
Location: include/linux/etherdevice.h:238
Inline: True
Inline callers:
  - net/ethernet/eth.c:ether_setup
```
```
In net/ncsi/ncsi-cmd.c (c000000000eb4664)
Location: include/linux/etherdevice.h:238
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In net/ethernet/eth.c (ffffffe0007a820c)
Location: include/linux/etherdevice.h:238
Inline: True
Inline callers:
  - net/ethernet/eth.c:ether_setup
```
```
In net/ncsi/ncsi-cmd.c (ffffffe0008a4d28)
Location: include/linux/etherdevice.h:238
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In net/ethernet/eth.c (ffffffff8192b628)
Location: include/linux/etherdevice.h:238
Inline: True
Inline callers:
  - net/ethernet/eth.c:ether_setup
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81a4260d)
Location: include/linux/etherdevice.h:238
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In net/ethernet/eth.c (ffffffff818e53d8)
Location: include/linux/etherdevice.h:238
Inline: True
Inline callers:
  - net/ethernet/eth.c:ether_setup
```
```
In net/ncsi/ncsi-cmd.c (ffffffff819ff1fd)
Location: include/linux/etherdevice.h:238
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In net/ethernet/eth.c (ffffffff8197c7b8)
Location: include/linux/etherdevice.h:238
Inline: True
Inline callers:
  - net/ethernet/eth.c:ether_setup
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81aae4bd)
Location: include/linux/etherdevice.h:238
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
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
In net/ethernet/eth.c (ffffffff8199ed08)
Location: include/linux/etherdevice.h:238
Inline: True
Inline callers:
  - net/ethernet/eth.c:ether_setup
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81aba86d)
Location: include/linux/etherdevice.h:238
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
</details>
</li>
</ul>

## Differences
