# Function: <code>eth_zero_addr</code>

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
In net/ethernet/eth.c (ffffffff8173feb1)
Location: include/linux/etherdevice.h:247
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header
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
In net/ethernet/eth.c (ffffffff817acbf1)
Location: include/linux/etherdevice.h:247
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header
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
In net/ethernet/eth.c (ffffffff817dc1e1)
Location: include/linux/etherdevice.h:247
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header
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
In net/ethernet/eth.c (ffffffff817fb8b2)
Location: include/linux/etherdevice.h:252
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header
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
In net/ethernet/eth.c (ffffffff81879262)
Location: include/linux/etherdevice.h:253
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header
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
In net/ethernet/eth.c (ffffffff818cac0d)
Location: include/linux/etherdevice.h:253
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header
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
In net/ethernet/eth.c (ffffffff818f5cdd)
Location: include/linux/etherdevice.h:253
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header
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
In net/ethernet/eth.c (ffffffff81955397)
Location: include/linux/etherdevice.h:249
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header
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
In net/ethernet/eth.c (ffffffff8198b837)
Location: include/linux/etherdevice.h:249
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81a634f7)
Location: include/linux/etherdevice.h:249
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header
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
In net/ethernet/eth.c (ffffffff81a6b647)
Location: include/linux/etherdevice.h:249
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81bb0285)
Location: include/linux/etherdevice.h:249
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
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
In net/core/selftests.c (ffffffff81a361eb)
Location: include/linux/etherdevice.h:249
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ethernet/eth.c (ffffffff81a53d77)
Location: include/linux/etherdevice.h:249
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81b9f38a)
Location: include/linux/etherdevice.h:249
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
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
In net/core/selftests.c (ffffffff81aebe8f)
Location: include/linux/etherdevice.h:249
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ethernet/eth.c (ffffffff81b0ca87)
Location: include/linux/etherdevice.h:249
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81c6ca1a)
Location: include/linux/etherdevice.h:249
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
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
In net/core/selftests.c (ffffffff81c6e814)
Location: include/linux/etherdevice.h:254
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ethernet/eth.c (ffffffff81c93377)
Location: include/linux/etherdevice.h:254
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81e0fd25)
Location: include/linux/etherdevice.h:254
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
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
In net/core/selftests.c (ffffffff81e26544)
Location: include/linux/etherdevice.h:254
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ethernet/eth.c (ffffffff81e4ec7f)
Location: include/linux/etherdevice.h:254
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81fe6715)
Location: include/linux/etherdevice.h:254
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
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
In net/core/selftests.c (ffffffff81e9bae4)
Location: include/linux/etherdevice.h:254
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ethernet/eth.c (ffffffff81eaa31f)
Location: include/linux/etherdevice.h:254
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header
```
```
In net/ncsi/ncsi-rsp.c (ffffffff82062a25)
Location: include/linux/etherdevice.h:254
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
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
In net/core/selftests.c (ffffffff81f5e244)
Location: include/linux/etherdevice.h:254
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ethernet/eth.c (ffffffff81f6cdcf)
Location: include/linux/etherdevice.h:254
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header
```
```
In net/ncsi/ncsi-rsp.c (ffffffff82135b75)
Location: include/linux/etherdevice.h:254
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma
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
In net/ethernet/eth.c (ffff800010c367a4)
Location: include/linux/etherdevice.h:249
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header
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
In net/ethernet/eth.c (c0d49194)
Location: include/linux/etherdevice.h:249
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header
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
In net/ethernet/eth.c (c000000000d2e8e0)
Location: include/linux/etherdevice.h:249
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header
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
In net/ethernet/eth.c (ffffffe0007a8144)
Location: include/linux/etherdevice.h:249
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header
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
In net/ethernet/eth.c (ffffffff8192b6a7)
Location: include/linux/etherdevice.h:249
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header
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
In net/ethernet/eth.c (ffffffff818e5457)
Location: include/linux/etherdevice.h:249
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header
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
In net/ethernet/eth.c (ffffffff8197c837)
Location: include/linux/etherdevice.h:249
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header
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
In net/ethernet/eth.c (ffffffff8199ed87)
Location: include/linux/etherdevice.h:249
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_header
```
</details>
</li>
</ul>

## Differences
