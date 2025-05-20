# Function: <code>__netif_receive_skb_list_core</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void __netif_receive_skb_list_core(struct list_head *head, bool pfmemalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b6cb0)
Location: net/core/dev.c:5021
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb_list
```
**Symbols:**

```
ffffffff818b6cb0-ffffffff818b6ea6: __netif_receive_skb_list_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __netif_receive_skb_list_core(struct list_head *head, bool pfmemalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81903ed0)
Location: net/core/dev.c:5060
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb_list
```
**Symbols:**

```
ffffffff81903ed0-ffffffff81904121: __netif_receive_skb_list_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __netif_receive_skb_list_core(struct list_head *head, bool pfmemalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81935030)
Location: net/core/dev.c:4962
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
```
**Symbols:**

```
ffffffff81935030-ffffffff81935281: __netif_receive_skb_list_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __netif_receive_skb_list_core(struct list_head *head, bool pfmemalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a09cd0)
Location: net/core/dev.c:5333
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list
  - net/core/dev.c:__netif_receive_skb_list
  - net/core/dev.c:__netif_receive_skb_list
```
**Symbols:**

```
ffffffff81a09cd0-ffffffff81a09f1a: __netif_receive_skb_list_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __netif_receive_skb_list_core(struct list_head *head, bool pfmemalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0b270)
Location: net/core/dev.c:5387
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list
  - net/core/dev.c:__netif_receive_skb_list
  - net/core/dev.c:__netif_receive_skb_list
```
**Symbols:**

```
ffffffff81a0b270-ffffffff81a0b4ba: __netif_receive_skb_list_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __netif_receive_skb_list_core(struct list_head *head, bool pfmemalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819f1830)
Location: net/core/dev.c:5511
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
```
**Symbols:**

```
ffffffff819f1830-ffffffff819f1a61: __netif_receive_skb_list_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __netif_receive_skb_list_core(struct list_head *head, bool pfmemalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81aa3150)
Location: net/core/dev.c:5500
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
```
**Symbols:**

```
ffffffff81aa3150-ffffffff81aa3381: __netif_receive_skb_list_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __netif_receive_skb_list_core(struct list_head *head, bool pfmemalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c1b430)
Location: net/core/dev.c:5537
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
```
**Symbols:**

```
ffffffff81c1b430-ffffffff81c1b67b: __netif_receive_skb_list_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __netif_receive_skb_list_core(struct list_head *head, bool pfmemalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dcc3a0)
Location: net/core/dev.c:5528
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
```
**Symbols:**

```
ffffffff81dcc3a0-ffffffff81dcc5eb: __netif_receive_skb_list_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __netif_receive_skb_list_core(struct list_head *head, bool pfmemalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e3cf00)
Location: net/core/dev.c:5504
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
```
**Symbols:**

```
ffffffff81e3cf00-ffffffff81e3d14b: __netif_receive_skb_list_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __netif_receive_skb_list_core(struct list_head *head, bool pfmemalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81efb7a0)
Location: net/core/dev.c:5586
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
```
**Symbols:**

```
ffffffff81efb7a0-ffffffff81efb9eb: __netif_receive_skb_list_core (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __netif_receive_skb_list_core(struct list_head *head, bool pfmemalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd3318)
Location: net/core/dev.c:4962
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
```
**Symbols:**

```
ffff800010bd3318-ffff800010bd3534: __netif_receive_skb_list_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __netif_receive_skb_list_core(struct list_head *head, bool pfmemalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cedff4)
Location: net/core/dev.c:4962
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
```
**Symbols:**

```
c0cedff4-c0cee214: __netif_receive_skb_list_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __netif_receive_skb_list_core(struct list_head *head, bool pfmemalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cb1de0)
Location: net/core/dev.c:4962
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
```
**Symbols:**

```
c000000000cb1de0-c000000000cb20e8: __netif_receive_skb_list_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __netif_receive_skb_list_core(struct list_head *head, bool pfmemalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075d608)
Location: net/core/dev.c:4962
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
```
**Symbols:**

```
ffffffe00075d608-ffffffe00075d766: __netif_receive_skb_list_core (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __netif_receive_skb_list_core(struct list_head *head, bool pfmemalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d5010)
Location: net/core/dev.c:4962
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
```
**Symbols:**

```
ffffffff818d5010-ffffffff818d5261: __netif_receive_skb_list_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __netif_receive_skb_list_core(struct list_head *head, bool pfmemalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188ee80)
Location: net/core/dev.c:4962
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
```
**Symbols:**

```
ffffffff8188ee80-ffffffff8188f0d1: __netif_receive_skb_list_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __netif_receive_skb_list_core(struct list_head *head, bool pfmemalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81926030)
Location: net/core/dev.c:4962
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
```
**Symbols:**

```
ffffffff81926030-ffffffff81926281: __netif_receive_skb_list_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __netif_receive_skb_list_core(struct list_head *head, bool pfmemalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819475d0)
Location: net/core/dev.c:4962
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
```
**Symbols:**

```
ffffffff819475d0-ffffffff81947821: __netif_receive_skb_list_core (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
