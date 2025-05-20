# Function: <code>__netif_receive_skb_list</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b7fb4)
Location: net/core/dev.c:5088
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list
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
In net/core/dev.c (ffffffff819041ff)
Location: net/core/dev.c:5127
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list
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
In net/core/dev.c (ffffffff8193534e)
Location: net/core/dev.c:5029
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __netif_receive_skb_list(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a09f20)
Location: net/core/dev.c:5400
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
```
**Symbols:**

```
ffffffff81a09f20-ffffffff81a0a08b: __netif_receive_skb_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __netif_receive_skb_list(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0b4c0)
Location: net/core/dev.c:5454
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
```
**Symbols:**

```
ffffffff81a0b4c0-ffffffff81a0b62b: __netif_receive_skb_list (STB_LOCAL)
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
In net/core/dev.c (ffffffff819f1b2e)
Location: net/core/dev.c:5578
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In net/core/dev.c (ffffffff81aa344e)
Location: net/core/dev.c:5567
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In net/core/dev.c (ffffffff81c1bb53)
Location: net/core/dev.c:5604
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In net/core/dev.c (ffffffff81dccb23)
Location: net/core/dev.c:5595
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In net/core/dev.c (ffffffff81e3d683)
Location: net/core/dev.c:5571
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In net/core/dev.c (ffffffff81efbf23)
Location: net/core/dev.c:5653
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In net/core/dev.c (ffff800010bd3610)
Location: net/core/dev.c:5029
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In net/core/dev.c (c0cee324)
Location: net/core/dev.c:5029
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In net/core/dev.c (c000000000cb21e4)
Location: net/core/dev.c:5029
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In net/core/dev.c (ffffffe00075d82c)
Location: net/core/dev.c:5029
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In net/core/dev.c (ffffffff818d5322)
Location: net/core/dev.c:5029
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In net/core/dev.c (ffffffff8188f192)
Location: net/core/dev.c:5029
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In net/core/dev.c (ffffffff8192634e)
Location: net/core/dev.c:5029
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
In net/core/dev.c (ffffffff819478f3)
Location: net/core/dev.c:5029
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
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
