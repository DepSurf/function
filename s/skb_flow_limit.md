# Function: <code>skb_flow_limit</code>

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
In net/core/dev.c (ffffffff817193b3)
Location: net/core/dev.c:3447
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
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
In net/core/dev.c (ffffffff817818a2)
Location: net/core/dev.c:3700
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
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
In net/core/dev.c (ffffffff817af1b2)
Location: net/core/dev.c:3696
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
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
In net/core/dev.c (ffffffff817cdac2)
Location: net/core/dev.c:3782
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
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
In net/core/dev.c (ffffffff818475c2)
Location: net/core/dev.c:3828
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
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
In net/core/dev.c (ffffffff81891e11)
Location: net/core/dev.c:3909
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
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
In net/core/dev.c (ffffffff818b2771)
Location: net/core/dev.c:4204
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
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
In net/core/dev.c (ffffffff818fef21)
Location: net/core/dev.c:4213
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
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
In net/core/dev.c (ffffffff81931291)
Location: net/core/dev.c:4115
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool skb_flow_limit(struct sk_buff *skb, unsigned int qlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ff340)
Location: net/core/dev.c:4476
Inline: False
Direct callers:
  - net/core/dev.c:enqueue_to_backlog
```
**Symbols:**

```
ffffffff819ff340-ffffffff819ff40b: skb_flow_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool skb_flow_limit(struct sk_buff *skb, unsigned int qlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ff090)
Location: net/core/dev.c:4505
Inline: False
Direct callers:
  - net/core/dev.c:enqueue_to_backlog
```
**Symbols:**

```
ffffffff819ff090-ffffffff819ff15b: skb_flow_limit (STB_LOCAL)
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
In net/core/dev.c (ffffffff819ee6e8)
Location: net/core/dev.c:4611
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
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
In net/core/dev.c (ffffffff81a9f985)
Location: net/core/dev.c:4579
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
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
In net/core/dev.c (ffffffff81c11124)
Location: net/core/dev.c:4620
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
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
In net/core/dev.c (ffffffff81dc0d94)
Location: net/core/dev.c:4607
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
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
In net/core/dev.c (ffffffff81e309a6)
Location: net/core/dev.c:4582
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
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
In net/core/dev.c (ffffffff81eecf2c)
Location: net/core/dev.c:4730
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
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
In net/core/dev.c (ffff800010bcfa34)
Location: net/core/dev.c:4115
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
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
In net/core/dev.c (c0ce4198)
Location: net/core/dev.c:4115
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
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
In net/core/dev.c (c000000000cac5e0)
Location: net/core/dev.c:4115
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
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
In net/core/dev.c (ffffffe000759bf4)
Location: net/core/dev.c:4115
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
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
In net/core/dev.c (ffffffff818d1291)
Location: net/core/dev.c:4115
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
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
In net/core/dev.c (ffffffff8188b12d)
Location: net/core/dev.c:4115
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
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
In net/core/dev.c (ffffffff81922291)
Location: net/core/dev.c:4115
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
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
In net/core/dev.c (ffffffff8194335f)
Location: net/core/dev.c:4115
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
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
