# Function: <code>napi_frags_skb</code>

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
In net/core/dev.c (ffffffff8171b57e)
Location: net/core/dev.c:4432
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
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
In net/core/dev.c (ffffffff81783e0e)
Location: net/core/dev.c:4711
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
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
In net/core/dev.c (ffffffff817b141e)
Location: net/core/dev.c:4734
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
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
In net/core/dev.c (ffffffff817d18be)
Location: net/core/dev.c:4964
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
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
In net/core/dev.c (ffffffff8184bb0e)
Location: net/core/dev.c:5105
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
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
In net/core/dev.c (ffffffff81895e85)
Location: net/core/dev.c:5235
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
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
In net/core/dev.c (ffffffff818b7c45)
Location: net/core/dev.c:5780
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
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
In net/core/dev.c (ffffffff81903ab5)
Location: net/core/dev.c:5790
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
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
In net/core/dev.c (ffffffff81936875)
Location: net/core/dev.c:5713
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct sk_buff *napi_frags_skb(struct napi_struct *napi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6096
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_frags
```
**Symbols:**

```
ffffffff81a02160-ffffffff81a0226c: napi_frags_skb (STB_LOCAL)
ffffffff81a0ee50-ffffffff81a0ee6c: napi_frags_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct sk_buff *napi_frags_skb(struct napi_struct *napi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6197
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_frags
```
**Symbols:**

```
ffffffff81a02960-ffffffff81a02a6c: napi_frags_skb (STB_LOCAL)
ffffffff81c31144-ffffffff81c31160: napi_frags_skb.cold (STB_LOCAL)
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
In net/core/dev.c (ffffffff819f2565)
Location: net/core/dev.c:6313
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
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
In net/core/dev.c (ffffffff81aa4435)
Location: net/core/dev.c:6299
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
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
In net/core/gro.c (ffffffff81c54415)
Location: net/core/gro.c:720
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
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
In net/core/gro.c (ffffffff81e09b65)
Location: net/core/gro.c:738
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
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
In net/core/gro.c (ffffffff81e7c325)
Location: net/core/gro.c:692
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
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
In net/core/gro.c (ffffffff81f3c675)
Location: net/core/gro.c:692
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
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
In net/core/dev.c (ffff800010bd4f4c)
Location: net/core/dev.c:5713
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
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
In net/core/dev.c (c0cef410)
Location: net/core/dev.c:5713
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
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
In net/core/dev.c (c000000000cb42c0)
Location: net/core/dev.c:5713
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
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
In net/core/dev.c (ffffffe00075eb08)
Location: net/core/dev.c:5713
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
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
In net/core/dev.c (ffffffff818d6845)
Location: net/core/dev.c:5713
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
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
In net/core/dev.c (ffffffff81890685)
Location: net/core/dev.c:5713
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
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
In net/core/dev.c (ffffffff81927875)
Location: net/core/dev.c:5713
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
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
In net/core/dev.c (ffffffff81948f15)
Location: net/core/dev.c:5713
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
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
