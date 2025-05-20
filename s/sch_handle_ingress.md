# Function: <code>sch_handle_ingress</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8178294f)
Location: net/core/dev.c:3926
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
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
In net/core/dev.c (ffffffff817b0233)
Location: net/core/dev.c:3921
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
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
In net/core/dev.c (ffffffff817ceb27)
Location: net/core/dev.c:4009
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
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
In net/core/dev.c (ffffffff81848434)
Location: net/core/dev.c:4209
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
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
In net/core/dev.c (ffffffff81892126)
Location: net/core/dev.c:4335
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
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
In net/core/dev.c (ffffffff818b5f85)
Location: net/core/dev.c:4650
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
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
In net/core/dev.c (ffffffff819020ca)
Location: net/core/dev.c:4647
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
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
In net/core/dev.c (ffffffff8193430a)
Location: net/core/dev.c:4549
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
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
In net/core/dev.c (ffffffff81a09036)
Location: net/core/dev.c:4911
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0a5b0)
Location: net/core/dev.c:4955
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
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
In net/core/dev.c (ffffffff819f0c55)
Location: net/core/dev.c:5079
Inline: True
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
In net/core/dev.c (ffffffff81aa289b)
Location: net/core/dev.c:5070
Inline: True
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
In net/core/dev.c (ffffffff81c1ab7d)
Location: net/core/dev.c:5105
Inline: True
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
In net/core/dev.c (ffffffff81dc7bb0)
Location: net/core/dev.c:5092
Inline: True
```
**Symbols:**

```
ffffffff81dc7bb0-ffffffff81dc7e3e: sch_handle_ingress.constprop.0 (STB_LOCAL)
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
In net/core/dev.c (ffffffff81e369b0)
Location: net/core/dev.c:5068
Inline: True
```
**Symbols:**

```
ffffffff81e369b0-ffffffff81e36c38: sch_handle_ingress.constprop.0 (STB_LOCAL)
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
In net/core/dev.c (ffffffff81efad00)
Location: net/core/dev.c:3985
Inline: True
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
In net/core/dev.c (ffff800010bd2654)
Location: net/core/dev.c:4549
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
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
In net/core/dev.c (c0ced6ac)
Location: net/core/dev.c:4549
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
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
In net/core/dev.c (c000000000cb0d50)
Location: net/core/dev.c:4549
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
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
In net/core/dev.c (ffffffe00075ce20)
Location: net/core/dev.c:4549
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
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
In net/core/dev.c (ffffffff818d430a)
Location: net/core/dev.c:4549
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
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
In net/core/dev.c (ffffffff8188e19a)
Location: net/core/dev.c:4549
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
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
In net/core/dev.c (ffffffff8192530a)
Location: net/core/dev.c:4549
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
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
In net/core/dev.c (ffffffff819467bb)
Location: net/core/dev.c:4549
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
```
</details>
</li>
</ul>

## Differences
