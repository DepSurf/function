# Function: <code>skb_reorder_vlan_header</code>

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
In net/core/skbuff.c (ffffffff8170a0d6)
Location: net/core/skbuff.c:4338
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
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
In net/core/skbuff.c (ffffffff81771893)
Location: net/core/skbuff.c:4412
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
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
In net/core/skbuff.c (ffffffff8179e9c3)
Location: net/core/skbuff.c:4456
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
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
In net/core/skbuff.c (ffffffff817bd9ba)
Location: net/core/skbuff.c:4550
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
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
In net/core/skbuff.c (ffffffff8183700a)
Location: net/core/skbuff.c:4981
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
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
In net/core/skbuff.c (ffffffff818814b9)
Location: net/core/skbuff.c:5056
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
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
In net/core/skbuff.c (ffffffff818a1fe7)
Location: net/core/skbuff.c:5084
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
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
In net/core/skbuff.c (ffffffff818ecc60)
Location: net/core/skbuff.c:5269
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
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
In net/core/skbuff.c (ffffffff8191ed80)
Location: net/core/skbuff.c:5281
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *skb_reorder_vlan_header(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819f07c0)
Location: net/core/skbuff.c:5383
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_vlan_untag
```
**Symbols:**

```
ffffffff819f07c0-ffffffff819f089b: skb_reorder_vlan_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *skb_reorder_vlan_header(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819eff80)
Location: net/core/skbuff.c:5450
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_vlan_untag
```
**Symbols:**

```
ffffffff819eff80-ffffffff819f005b: skb_reorder_vlan_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *skb_reorder_vlan_header(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d77b0)
Location: net/core/skbuff.c:5538
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_vlan_untag
```
**Symbols:**

```
ffffffff819d77b0-ffffffff819d788b: skb_reorder_vlan_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *skb_reorder_vlan_header(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a85ff0)
Location: net/core/skbuff.c:5613
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_vlan_untag
```
**Symbols:**

```
ffffffff81a85ff0-ffffffff81a860cb: skb_reorder_vlan_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *skb_reorder_vlan_header(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf8ff0)
Location: net/core/skbuff.c:5534
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_vlan_untag
```
**Symbols:**

```
ffffffff81bf8ff0-ffffffff81bf90ce: skb_reorder_vlan_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *skb_reorder_vlan_header(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81daa5d0)
Location: net/core/skbuff.c:5736
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_vlan_untag
```
**Symbols:**

```
ffffffff81daa5d0-ffffffff81daa6ae: skb_reorder_vlan_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *skb_reorder_vlan_header(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e1b790)
Location: net/core/skbuff.c:5793
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_vlan_untag
```
**Symbols:**

```
ffffffff81e1b790-ffffffff81e1b86e: skb_reorder_vlan_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *skb_reorder_vlan_header(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed8d50)
Location: net/core/skbuff.c:5921
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_vlan_untag
```
**Symbols:**

```
ffffffff81ed8d50-ffffffff81ed8e2e: skb_reorder_vlan_header (STB_LOCAL)
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
In net/core/skbuff.c (ffff800010bb958c)
Location: net/core/skbuff.c:5281
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
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
In net/core/skbuff.c (c0cd6028)
Location: net/core/skbuff.c:5281
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
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
In net/core/skbuff.c (c000000000c91b40)
Location: net/core/skbuff.c:5281
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
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
In net/core/skbuff.c (ffffffe000748b04)
Location: net/core/skbuff.c:5281
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
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
In net/core/skbuff.c (ffffffff818bed80)
Location: net/core/skbuff.c:5281
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
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
In net/core/skbuff.c (ffffffff81878cc0)
Location: net/core/skbuff.c:5281
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
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
In net/core/skbuff.c (ffffffff8190fd80)
Location: net/core/skbuff.c:5281
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
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
In net/core/skbuff.c (ffffffff81930eb0)
Location: net/core/skbuff.c:5281
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
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
