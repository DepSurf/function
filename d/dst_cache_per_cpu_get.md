# Function: <code>dst_cache_per_cpu_get</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dst_cache.c (ffffffff817aaed0)
Location: net/core/dst_cache.c:42
Inline: True
Direct callers:
  - net/core/dst_cache.c:dst_cache_get_ip6
  - net/core/dst_cache.c:dst_cache_get_ip4
  - net/core/dst_cache.c:dst_cache_get
```
**Symbols:**

```
ffffffff817aaed0-ffffffff817aaf53: dst_cache_per_cpu_get.isra.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dst_cache.c (ffffffff817da4f0)
Location: net/core/dst_cache.c:42
Inline: True
Direct callers:
  - net/core/dst_cache.c:dst_cache_get_ip6
  - net/core/dst_cache.c:dst_cache_get_ip4
  - net/core/dst_cache.c:dst_cache_get
```
**Symbols:**

```
ffffffff817da4f0-ffffffff817da573: dst_cache_per_cpu_get.isra.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dst_cache.c (ffffffff817f96a0)
Location: net/core/dst_cache.c:42
Inline: True
Direct callers:
  - net/core/dst_cache.c:dst_cache_get_ip6
  - net/core/dst_cache.c:dst_cache_get_ip4
  - net/core/dst_cache.c:dst_cache_get
```
**Symbols:**

```
ffffffff817f96a0-ffffffff817f9756: dst_cache_per_cpu_get.isra.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dst_cache.c (ffffffff81876fc0)
Location: net/core/dst_cache.c:42
Inline: True
Direct callers:
  - net/core/dst_cache.c:dst_cache_get_ip6
  - net/core/dst_cache.c:dst_cache_get_ip4
  - net/core/dst_cache.c:dst_cache_get
```
**Symbols:**

```
ffffffff81876fc0-ffffffff8187707c: dst_cache_per_cpu_get.isra.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dst_cache.c (ffffffff818c86e0)
Location: net/core/dst_cache.c:42
Inline: True
Direct callers:
  - net/core/dst_cache.c:dst_cache_get_ip6
  - net/core/dst_cache.c:dst_cache_get_ip4
  - net/core/dst_cache.c:dst_cache_get
```
**Symbols:**

```
ffffffff818c86e0-ffffffff818c8791: dst_cache_per_cpu_get.isra.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dst_cache.c (ffffffff818f3610)
Location: net/core/dst_cache.c:42
Inline: True
Direct callers:
  - net/core/dst_cache.c:dst_cache_get_ip6
  - net/core/dst_cache.c:dst_cache_get_ip4
  - net/core/dst_cache.c:dst_cache_get
```
**Symbols:**

```
ffffffff818f3610-ffffffff818f36c1: dst_cache_per_cpu_get.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dst_cache.c (0)
Location: net/core/dst_cache.c:38
Inline: True
Direct callers:
  - net/core/dst_cache.c:dst_cache_get_ip6
  - net/core/dst_cache.c:dst_cache_get_ip4
  - net/core/dst_cache.c:dst_cache_get
```
**Symbols:**

```
ffffffff81945a90-ffffffff81945b34: dst_cache_per_cpu_get.isra.0 (STB_LOCAL)
ffffffff81945c7f-ffffffff81945c91: dst_cache_per_cpu_get.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dst_cache.c (ffffffff8197aab0)
Location: net/core/dst_cache.c:38
Inline: True
Direct callers:
  - net/core/dst_cache.c:dst_cache_get_ip6
  - net/core/dst_cache.c:dst_cache_get_ip4
  - net/core/dst_cache.c:dst_cache_get
```
**Symbols:**

```
ffffffff8197aab0-ffffffff8197ab48: dst_cache_per_cpu_get.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dst_entry *dst_cache_per_cpu_get(struct dst_cache *dst_cache, struct dst_cache_pcpu *idst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff81a4ff70)
Location: net/core/dst_cache.c:38
Inline: False
Direct callers:
  - net/core/dst_cache.c:dst_cache_get_ip6
  - net/core/dst_cache.c:dst_cache_get_ip4
  - net/core/dst_cache.c:dst_cache_get
```
**Symbols:**

```
ffffffff81a4ff70-ffffffff81a50009: dst_cache_per_cpu_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dst_entry *dst_cache_per_cpu_get(struct dst_cache *dst_cache, struct dst_cache_pcpu *idst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff81a55fb0)
Location: net/core/dst_cache.c:38
Inline: False
Direct callers:
  - net/core/dst_cache.c:dst_cache_get_ip6
  - net/core/dst_cache.c:dst_cache_get_ip4
  - net/core/dst_cache.c:dst_cache_get
```
**Symbols:**

```
ffffffff81a55fb0-ffffffff81a56049: dst_cache_per_cpu_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dst_entry *dst_cache_per_cpu_get(struct dst_cache *dst_cache, struct dst_cache_pcpu *idst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff81a38fc0)
Location: net/core/dst_cache.c:38
Inline: False
Direct callers:
  - net/core/dst_cache.c:dst_cache_get_ip6
  - net/core/dst_cache.c:dst_cache_get_ip4
  - net/core/dst_cache.c:dst_cache_get
```
**Symbols:**

```
ffffffff81a38fc0-ffffffff81a39059: dst_cache_per_cpu_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dst_entry *dst_cache_per_cpu_get(struct dst_cache *dst_cache, struct dst_cache_pcpu *idst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff81aeefa0)
Location: net/core/dst_cache.c:38
Inline: False
Direct callers:
  - net/core/dst_cache.c:dst_cache_get_ip6
  - net/core/dst_cache.c:dst_cache_get_ip4
  - net/core/dst_cache.c:dst_cache_get
```
**Symbols:**

```
ffffffff81aeefa0-ffffffff81aef039: dst_cache_per_cpu_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dst_entry *dst_cache_per_cpu_get(struct dst_cache *dst_cache, struct dst_cache_pcpu *idst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff81c71f60)
Location: net/core/dst_cache.c:38
Inline: False
Direct callers:
  - net/core/dst_cache.c:dst_cache_get_ip6
  - net/core/dst_cache.c:dst_cache_get_ip4
  - net/core/dst_cache.c:dst_cache_get
```
**Symbols:**

```
ffffffff81c71f60-ffffffff81c72014: dst_cache_per_cpu_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dst_entry *dst_cache_per_cpu_get(struct dst_cache *dst_cache, struct dst_cache_pcpu *idst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff81e2a0c0)
Location: net/core/dst_cache.c:38
Inline: False
Direct callers:
  - net/core/dst_cache.c:dst_cache_get_ip6
  - net/core/dst_cache.c:dst_cache_get_ip4
  - net/core/dst_cache.c:dst_cache_get
```
**Symbols:**

```
ffffffff81e2a0c0-ffffffff81e2a174: dst_cache_per_cpu_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dst_entry *dst_cache_per_cpu_get(struct dst_cache *dst_cache, struct dst_cache_pcpu *idst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff81e9f430)
Location: net/core/dst_cache.c:38
Inline: False
Direct callers:
  - net/core/dst_cache.c:dst_cache_get_ip6
  - net/core/dst_cache.c:dst_cache_get_ip4
  - net/core/dst_cache.c:dst_cache_get
```
**Symbols:**

```
ffffffff81e9f430-ffffffff81e9f4f0: dst_cache_per_cpu_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dst_entry *dst_cache_per_cpu_get(struct dst_cache *dst_cache, struct dst_cache_pcpu *idst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (ffffffff81f61ba0)
Location: net/core/dst_cache.c:38
Inline: False
Direct callers:
  - net/core/dst_cache.c:dst_cache_get_ip6
  - net/core/dst_cache.c:dst_cache_get_ip4
  - net/core/dst_cache.c:dst_cache_get
```
**Symbols:**

```
ffffffff81f61ba0-ffffffff81f61c60: dst_cache_per_cpu_get (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dst_cache.c (ffff800010c21ff0)
Location: net/core/dst_cache.c:38
Inline: True
Direct callers:
  - net/core/dst_cache.c:dst_cache_get_ip6
  - net/core/dst_cache.c:dst_cache_get_ip4
  - net/core/dst_cache.c:dst_cache_get
```
**Symbols:**

```
ffff800010c21ff0-ffff800010c220ec: dst_cache_per_cpu_get.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dst_entry *dst_cache_per_cpu_get(struct dst_cache *dst_cache, struct dst_cache_pcpu *idst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst_cache.c (c0d39484)
Location: net/core/dst_cache.c:38
Inline: False
Direct callers:
  - net/core/dst_cache.c:dst_cache_get_ip6
  - net/core/dst_cache.c:dst_cache_get_ip4
  - net/core/dst_cache.c:dst_cache_get
```
**Symbols:**

```
c0d39484-c0d3957c: dst_cache_per_cpu_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dst_cache.c (c000000000d14630)
Location: net/core/dst_cache.c:38
Inline: True
Direct callers:
  - net/core/dst_cache.c:dst_cache_get_ip6
  - net/core/dst_cache.c:dst_cache_get_ip4
  - net/core/dst_cache.c:dst_cache_get
```
**Symbols:**

```
c000000000d14630-c000000000d1476c: dst_cache_per_cpu_get.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dst_cache.c (ffffffe00079ac94)
Location: net/core/dst_cache.c:38
Inline: True
Direct callers:
  - net/core/dst_cache.c:dst_cache_get_ip6
  - net/core/dst_cache.c:dst_cache_get_ip4
  - net/core/dst_cache.c:dst_cache_get
```
**Symbols:**

```
ffffffe00079ac94-ffffffe00079ad4a: dst_cache_per_cpu_get.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dst_cache.c (ffffffff8191a920)
Location: net/core/dst_cache.c:38
Inline: True
Direct callers:
  - net/core/dst_cache.c:dst_cache_get_ip6
  - net/core/dst_cache.c:dst_cache_get_ip4
  - net/core/dst_cache.c:dst_cache_get
```
**Symbols:**

```
ffffffff8191a920-ffffffff8191a9b8: dst_cache_per_cpu_get.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dst_cache.c (ffffffff818d46d0)
Location: net/core/dst_cache.c:38
Inline: True
Direct callers:
  - net/core/dst_cache.c:dst_cache_get_ip6
  - net/core/dst_cache.c:dst_cache_get_ip4
  - net/core/dst_cache.c:dst_cache_get
```
**Symbols:**

```
ffffffff818d46d0-ffffffff818d4768: dst_cache_per_cpu_get.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dst_cache.c (ffffffff8196bab0)
Location: net/core/dst_cache.c:38
Inline: True
Direct callers:
  - net/core/dst_cache.c:dst_cache_get_ip6
  - net/core/dst_cache.c:dst_cache_get_ip4
  - net/core/dst_cache.c:dst_cache_get
```
**Symbols:**

```
ffffffff8196bab0-ffffffff8196bb48: dst_cache_per_cpu_get.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dst_cache.c (ffffffff8198df30)
Location: net/core/dst_cache.c:38
Inline: True
Direct callers:
  - net/core/dst_cache.c:dst_cache_get_ip6
  - net/core/dst_cache.c:dst_cache_get_ip4
  - net/core/dst_cache.c:dst_cache_get
```
**Symbols:**

```
ffffffff8198df30-ffffffff8198dfc8: dst_cache_per_cpu_get.isra.0 (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
