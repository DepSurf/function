# Function: <code>compare_ether_header</code>

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
In net/core/dev.c (ffffffff8171b49a)
Location: include/linux/etherdevice.h:416
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/ethernet/eth.c (ffffffff817400aa)
Location: include/linux/etherdevice.h:416
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
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
In net/core/dev.c (ffffffff81783d30)
Location: include/linux/etherdevice.h:439
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/ethernet/eth.c (ffffffff817acdec)
Location: include/linux/etherdevice.h:439
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
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
In net/core/dev.c (ffffffff817b1322)
Location: include/linux/etherdevice.h:439
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/ethernet/eth.c (ffffffff817dc43c)
Location: include/linux/etherdevice.h:439
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
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
In net/core/dev.c (ffffffff817d151f)
Location: include/linux/etherdevice.h:489
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/ethernet/eth.c (ffffffff817fbae4)
Location: include/linux/etherdevice.h:489
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
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
In net/core/dev.c (ffffffff8184b62f)
Location: include/linux/etherdevice.h:490
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/ethernet/eth.c (ffffffff818794a4)
Location: include/linux/etherdevice.h:490
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
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
In net/core/dev.c (ffffffff81895b41)
Location: include/linux/etherdevice.h:490
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/ethernet/eth.c (ffffffff818cae8c)
Location: include/linux/etherdevice.h:490
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
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
In net/core/dev.c (ffffffff818b7849)
Location: include/linux/etherdevice.h:490
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/ethernet/eth.c (ffffffff818f601e)
Location: include/linux/etherdevice.h:490
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
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
In net/core/dev.c (ffffffff819036bf)
Location: include/linux/etherdevice.h:498
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/ethernet/eth.c (ffffffff8195569d)
Location: include/linux/etherdevice.h:498
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
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
In net/core/dev.c (ffffffff81936472)
Location: include/linux/etherdevice.h:498
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/ethernet/eth.c (ffffffff8198bb3d)
Location: include/linux/etherdevice.h:498
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
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
In net/core/dev.c (ffffffff81a00a73)
Location: include/linux/etherdevice.h:509
Inline: True
Inline callers:
  - net/core/dev.c:gro_list_prepare
```
```
In net/ethernet/eth.c (ffffffff81a6373d)
Location: include/linux/etherdevice.h:509
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
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
In net/core/dev.c (ffffffff81a00e83)
Location: include/linux/etherdevice.h:509
Inline: True
Inline callers:
  - net/core/dev.c:gro_list_prepare
```
```
In net/ethernet/eth.c (ffffffff81a6b88d)
Location: include/linux/etherdevice.h:509
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
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
In net/core/dev.c (ffffffff819e7755)
Location: include/linux/etherdevice.h:509
Inline: True
Inline callers:
  - net/core/dev.c:gro_list_prepare
```
```
In net/ethernet/eth.c (ffffffff81a53fed)
Location: include/linux/etherdevice.h:509
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
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
In net/core/dev.c (ffffffff81a98368)
Location: include/linux/etherdevice.h:521
Inline: True
Inline callers:
  - net/core/dev.c:gro_list_prepare
```
```
In net/ethernet/eth.c (ffffffff81b0ccfd)
Location: include/linux/etherdevice.h:521
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
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
In net/core/gro.c (ffffffff81c53b2f)
Location: include/linux/etherdevice.h:528
Inline: True
Inline callers:
  - net/core/gro.c:gro_list_prepare
```
```
In net/ethernet/eth.c (ffffffff81c9361f)
Location: include/linux/etherdevice.h:528
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
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
In net/core/gro.c (ffffffff81e092bd)
Location: include/linux/etherdevice.h:550
Inline: True
Inline callers:
  - net/core/gro.c:gro_list_prepare
```
```
In net/ethernet/eth.c (ffffffff81e4ed17)
Location: include/linux/etherdevice.h:550
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
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
In net/core/gro.c (ffffffff81e7bb00)
Location: include/linux/etherdevice.h:564
Inline: True
Inline callers:
  - net/core/gro.c:gro_list_prepare
```
```
In net/ethernet/eth.c (ffffffff81eaa3b7)
Location: include/linux/etherdevice.h:564
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
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
In net/core/gro.c (ffffffff81f3bc9c)
Location: include/linux/etherdevice.h:564
Inline: True
Inline callers:
  - net/core/gro.c:gro_list_prepare
```
```
In net/ethernet/eth.c (ffffffff81f6ce67)
Location: include/linux/etherdevice.h:564
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
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
In net/core/dev.c (ffff800010bd4ab0)
Location: include/linux/etherdevice.h:498
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/ethernet/eth.c (ffff800010c36b64)
Location: include/linux/etherdevice.h:498
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
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
In net/core/dev.c (c0cef0f8)
Location: include/linux/etherdevice.h:498
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/ethernet/eth.c (c0d494a8)
Location: include/linux/etherdevice.h:498
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
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
In net/core/dev.c (c000000000cb3bf8)
Location: include/linux/etherdevice.h:498
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/ethernet/eth.c (c000000000d2f0d0)
Location: include/linux/etherdevice.h:498
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
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
In net/core/dev.c (ffffffe00075e84a)
Location: include/linux/etherdevice.h:498
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/ethernet/eth.c (ffffffe0007a8538)
Location: include/linux/etherdevice.h:498
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
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
In net/core/dev.c (ffffffff818d6442)
Location: include/linux/etherdevice.h:498
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/ethernet/eth.c (ffffffff8192b9ad)
Location: include/linux/etherdevice.h:498
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
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
In net/core/dev.c (ffffffff81890282)
Location: include/linux/etherdevice.h:498
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/ethernet/eth.c (ffffffff818e575d)
Location: include/linux/etherdevice.h:498
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
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
In net/core/dev.c (ffffffff81927472)
Location: include/linux/etherdevice.h:498
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/ethernet/eth.c (ffffffff8197cb3d)
Location: include/linux/etherdevice.h:498
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
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
In net/core/dev.c (ffffffff81948ada)
Location: include/linux/etherdevice.h:498
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/ethernet/eth.c (ffffffff8199f09d)
Location: include/linux/etherdevice.h:498
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
</details>
</li>
</ul>

## Differences
