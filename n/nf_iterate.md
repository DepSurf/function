# Function: <code>nf_iterate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int nf_iterate(struct list_head *head, struct sk_buff *skb, struct nf_hook_state *state, struct nf_hook_ops **elemp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81751800)
Location: net/netfilter/core.c:256
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_slow
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff81751800-ffffffff81751872: nf_iterate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int nf_iterate(struct list_head *head, struct sk_buff *skb, struct nf_hook_state *state, struct nf_hook_ops **elemp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff817bd850)
Location: net/netfilter/core.c:256
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_slow
  - net/netfilter/nf_queue.c:nf_reinject
```
**Symbols:**

```
ffffffff817bd850-ffffffff817bd8c2: nf_iterate (STB_GLOBAL)
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
In net/netfilter/nf_queue.c (ffffffff817ee42f)
Location: net/netfilter/nf_queue.c:180
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
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
In net/netfilter/nf_queue.c (ffffffff8180e583)
Location: net/netfilter/nf_queue.c:183
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
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
In net/netfilter/nf_queue.c (ffffffff8188da97)
Location: net/netfilter/nf_queue.c:183
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
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
In net/netfilter/nf_queue.c (ffffffff818e1781)
Location: net/netfilter/nf_queue.c:228
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
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
In net/netfilter/nf_queue.c (ffffffff8190e311)
Location: net/netfilter/nf_queue.c:244
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
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
In net/netfilter/nf_queue.c (ffffffff8196fec5)
Location: net/netfilter/nf_queue.c:247
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
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
In net/netfilter/nf_queue.c (ffffffff819a68c5)
Location: net/netfilter/nf_queue.c:247
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
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
In net/netfilter/nf_queue.c (ffffffff81a8fbf3)
Location: net/netfilter/nf_queue.c:237
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
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
In net/netfilter/nf_queue.c (ffffffff81a99bed)
Location: net/netfilter/nf_queue.c:237
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
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
In net/netfilter/nf_queue.c (ffffffff81a84efd)
Location: net/netfilter/nf_queue.c:237
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
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
In net/netfilter/nf_queue.c (ffffffff81b3f5b2)
Location: net/netfilter/nf_queue.c:254
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
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
In net/netfilter/nf_queue.c (ffffffff81ccbd5a)
Location: net/netfilter/nf_queue.c:254
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
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
In net/netfilter/nf_queue.c (ffffffff81e8bbc8)
Location: net/netfilter/nf_queue.c:254
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
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
In net/netfilter/nf_queue.c (ffffffff81ee9c37)
Location: net/netfilter/nf_queue.c:254
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
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
In net/netfilter/nf_queue.c (ffffffff81fad9e7)
Location: net/netfilter/nf_queue.c:252
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
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
In net/netfilter/nf_queue.c (ffff800010c5614c)
Location: net/netfilter/nf_queue.c:247
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
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
In net/netfilter/nf_queue.c (c0d65afc)
Location: net/netfilter/nf_queue.c:247
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
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
In net/netfilter/nf_queue.c (c000000000d56a1c)
Location: net/netfilter/nf_queue.c:247
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
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
In net/netfilter/nf_queue.c (ffffffe0007c043e)
Location: net/netfilter/nf_queue.c:247
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
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
In net/netfilter/nf_queue.c (ffffffff81946735)
Location: net/netfilter/nf_queue.c:247
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
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
In net/netfilter/nf_queue.c (ffffffff81900225)
Location: net/netfilter/nf_queue.c:247
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
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
In net/netfilter/nf_queue.c (ffffffff819978c5)
Location: net/netfilter/nf_queue.c:247
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
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
In net/netfilter/nf_queue.c (ffffffff819ba5a5)
Location: net/netfilter/nf_queue.c:247
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
</ul>
