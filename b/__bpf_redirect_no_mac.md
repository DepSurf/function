# Function: <code>__bpf_redirect_no_mac</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817cbc1f)
Location: net/core/filter.c:1668
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
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
In net/core/filter.c (ffffffff817ea6b2)
Location: net/core/filter.c:1694
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
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
In net/core/filter.c (ffffffff81865de2)
Location: net/core/filter.c:1715
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
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
In net/core/filter.c (ffffffff818b3e8e)
Location: net/core/filter.c:2001
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
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
In net/core/filter.c (ffffffff818dc686)
Location: net/core/filter.c:2020
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
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
In net/core/filter.c (ffffffff8192977f)
Location: net/core/filter.c:2066
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
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
In net/core/filter.c (ffffffff8195bddf)
Location: net/core/filter.c:2067
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __bpf_redirect_no_mac(struct sk_buff *skb, struct net_device *dev, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:2092
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
ffffffff81a30e60-ffffffff81a3105d: __bpf_redirect_no_mac (STB_LOCAL)
ffffffff81a33221-ffffffff81a33232: __bpf_redirect_no_mac.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __bpf_redirect_no_mac(struct sk_buff *skb, struct net_device *dev, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:2122
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
ffffffff81a332f0-ffffffff81a334ed: __bpf_redirect_no_mac (STB_LOCAL)
ffffffff81c3178f-ffffffff81c317a0: __bpf_redirect_no_mac.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __bpf_redirect_no_mac(struct sk_buff *skb, struct net_device *dev, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:2119
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
ffffffff81a1a090-ffffffff81a1a29c: __bpf_redirect_no_mac (STB_LOCAL)
ffffffff81c23a98-ffffffff81c23aa9: __bpf_redirect_no_mac.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __bpf_redirect_no_mac(struct sk_buff *skb, struct net_device *dev, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:2120
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
ffffffff81acc300-ffffffff81acc4fb: __bpf_redirect_no_mac (STB_LOCAL)
ffffffff81d37635-ffffffff81d37646: __bpf_redirect_no_mac.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __bpf_redirect_no_mac(struct sk_buff *skb, struct net_device *dev, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:2121
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
ffffffff81c48f50-ffffffff81c491b3: __bpf_redirect_no_mac (STB_LOCAL)
ffffffff81f03f4e-ffffffff81f03f5f: __bpf_redirect_no_mac.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __bpf_redirect_no_mac(struct sk_buff *skb, struct net_device *dev, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81dfd8f0)
Location: net/core/filter.c:2123
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
ffffffff81dfd8f0-ffffffff81dfdb89: __bpf_redirect_no_mac (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __bpf_redirect_no_mac(struct sk_buff *skb, struct net_device *dev, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e6ee20)
Location: net/core/filter.c:2135
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
ffffffff81e6ee20-ffffffff81e6f0d8: __bpf_redirect_no_mac (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __bpf_redirect_no_mac(struct sk_buff *skb, struct net_device *dev, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f2e480)
Location: net/core/filter.c:2142
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
ffffffff81f2e480-ffffffff81f2e717: __bpf_redirect_no_mac (STB_LOCAL)
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
In net/core/filter.c (ffff800010c01368)
Location: net/core/filter.c:2067
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
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
In net/core/filter.c (c0d18470)
Location: net/core/filter.c:2067
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
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
In net/core/filter.c (c000000000ce8db0)
Location: net/core/filter.c:2067
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
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
In net/core/filter.c (ffffffe00077fe22)
Location: net/core/filter.c:2067
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
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
In net/core/filter.c (ffffffff818fbdaf)
Location: net/core/filter.c:2067
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
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
In net/core/filter.c (ffffffff818b5bdf)
Location: net/core/filter.c:2067
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
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
In net/core/filter.c (ffffffff8194cddf)
Location: net/core/filter.c:2067
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
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
In net/core/filter.c (ffffffff8196e79f)
Location: net/core/filter.c:2067
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
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
