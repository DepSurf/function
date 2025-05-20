# Function: <code>netif_alloc_rx_queues</code>

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
In net/core/dev.c (ffffffff8171bc6c)
Location: net/core/dev.c:6527
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In net/core/dev.c (ffffffff8178450c)
Location: net/core/dev.c:7023
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In net/core/dev.c (ffffffff817b1b10)
Location: net/core/dev.c:7193
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In net/core/dev.c (ffffffff817cb871)
Location: net/core/dev.c:7381
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In net/core/dev.c (ffffffff818450c0)
Location: net/core/dev.c:7554
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In net/core/dev.c (ffffffff8189133c)
Location: net/core/dev.c:7790
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In net/core/dev.c (ffffffff818b196c)
Location: net/core/dev.c:8417
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In net/core/dev.c (ffffffff818fe70c)
Location: net/core/dev.c:8520
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In net/core/dev.c (ffffffff81930a49)
Location: net/core/dev.c:8831
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int netif_alloc_rx_queues(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a00050)
Location: net/core/dev.c:9294
Inline: False
Direct callers:
  - net/core/dev.c:alloc_netdev_mqs
```
**Symbols:**

```
ffffffff81a00050-ffffffff81a0013e: netif_alloc_rx_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int netif_alloc_rx_queues(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a00140)
Location: net/core/dev.c:9924
Inline: False
Direct callers:
  - net/core/dev.c:alloc_netdev_mqs
```
**Symbols:**

```
ffffffff81a00140-ffffffff81a00230: netif_alloc_rx_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ed231)
Location: net/core/dev.c:10089
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a9e44d)
Location: net/core/dev.c:10096
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c12c86)
Location: net/core/dev.c:9839
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc2daa)
Location: net/core/dev.c:9826
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e3224f)
Location: net/core/dev.c:9838
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef0700)
Location: net/core/dev.c:9975
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In net/core/dev.c (ffff800010bcc8cc)
Location: net/core/dev.c:8831
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In net/core/dev.c (c0ce6cd4)
Location: net/core/dev.c:8831
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In net/core/dev.c (c000000000cabc5c)
Location: net/core/dev.c:8831
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In net/core/dev.c (ffffffe00075831e)
Location: net/core/dev.c:8831
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In net/core/dev.c (ffffffff818d0a49)
Location: net/core/dev.c:8831
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In net/core/dev.c (ffffffff8188a929)
Location: net/core/dev.c:8831
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In net/core/dev.c (ffffffff81921a49)
Location: net/core/dev.c:8831
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
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
In net/core/dev.c (ffffffff81940419)
Location: net/core/dev.c:8831
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
