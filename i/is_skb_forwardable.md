# Function: <code>is_skb_forwardable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool is_skb_forwardable(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817169e0)
Location: net/core/dev.c:1726
Inline: True
Direct callers:
  - net/core/dev.c:__dev_forward_skb
```
**Symbols:**

```
ffffffff817169e0-ffffffff81716a2a: is_skb_forwardable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool is_skb_forwardable(const struct net_device *dev, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177e9d0)
Location: net/core/dev.c:1746
Inline: True
Direct callers:
  - net/core/dev.c:__dev_forward_skb
```
**Symbols:**

```
ffffffff8177e9d0-ffffffff8177ea1a: is_skb_forwardable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool is_skb_forwardable(const struct net_device *dev, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ac2c0)
Location: net/core/dev.c:1767
Inline: True
Direct callers:
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
ffffffff817ac2c0-ffffffff817ac30a: is_skb_forwardable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool is_skb_forwardable(const struct net_device *dev, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ca7d0)
Location: net/core/dev.c:1801
Inline: True
Direct callers:
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
ffffffff817ca7d0-ffffffff817ca81a: is_skb_forwardable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool is_skb_forwardable(const struct net_device *dev, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818442d0)
Location: net/core/dev.c:1816
Inline: True
Direct callers:
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
ffffffff818442d0-ffffffff8184431a: is_skb_forwardable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool is_skb_forwardable(const struct net_device *dev, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188e040)
Location: net/core/dev.c:1860
Inline: True
Direct callers:
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
ffffffff8188e040-ffffffff8188e08a: is_skb_forwardable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool is_skb_forwardable(const struct net_device *dev, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818aef00)
Location: net/core/dev.c:1894
Inline: True
Direct callers:
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
ffffffff818aef00-ffffffff818aef47: is_skb_forwardable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool is_skb_forwardable(const struct net_device *dev, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818fa910)
Location: net/core/dev.c:1904
Inline: True
Direct callers:
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
ffffffff818fa910-ffffffff818fa957: is_skb_forwardable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool is_skb_forwardable(const struct net_device *dev, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192ca50)
Location: net/core/dev.c:1822
Inline: True
Direct callers:
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
ffffffff8192ca50-ffffffff8192ca97: is_skb_forwardable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool is_skb_forwardable(const struct net_device *dev, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a022eb)
Location: net/core/dev.c:2182
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
  - net/core/dev.c:__dev_forward_skb
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:__bpf_redirect_no_mac
```
**Symbols:**

```
ffffffff81a008b0-ffffffff81a008f7: is_skb_forwardable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool is_skb_forwardable(const struct net_device *dev, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a02aeb)
Location: net/core/dev.c:2207
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
  - net/core/dev.c:__dev_forward_skb
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
```
**Symbols:**

```
ffffffff81a00cc0-ffffffff81a00d07: is_skb_forwardable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool is_skb_forwardable(const struct net_device *dev, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e7490)
Location: net/core/dev.c:2276
Inline: True
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
```
**Symbols:**

```
ffffffff819e7490-ffffffff819e74d7: is_skb_forwardable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool is_skb_forwardable(const struct net_device *dev, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a97e80)
Location: net/core/dev.c:2151
Inline: True
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
```
**Symbols:**

```
ffffffff81a97e80-ffffffff81a97ec7: is_skb_forwardable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool is_skb_forwardable(const struct net_device *dev, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c0f870)
Location: net/core/dev.c:2128
Inline: True
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
```
**Symbols:**

```
ffffffff81c0f870-ffffffff81c0f8c1: is_skb_forwardable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool is_skb_forwardable(const struct net_device *dev, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dbf480)
Location: net/core/dev.c:2113
Inline: True
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
```
**Symbols:**

```
ffffffff81dbf480-ffffffff81dbf4d1: is_skb_forwardable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool is_skb_forwardable(const struct net_device *dev, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e2f130)
Location: net/core/dev.c:2139
Inline: True
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
```
**Symbols:**

```
ffffffff81e2f130-ffffffff81e2f181: is_skb_forwardable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool is_skb_forwardable(const struct net_device *dev, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81eeddb0)
Location: net/core/dev.c:2143
Inline: True
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
```
**Symbols:**

```
ffffffff81eeddb0-ffffffff81eeddfe: is_skb_forwardable (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool is_skb_forwardable(const struct net_device *dev, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bc9068)
Location: net/core/dev.c:1822
Inline: True
Direct callers:
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
ffff800010bc9068-ffff800010bc90e0: is_skb_forwardable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool is_skb_forwardable(const struct net_device *dev, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce572c)
Location: net/core/dev.c:1822
Inline: True
Direct callers:
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
c0ce572c-c0ce5790: is_skb_forwardable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool is_skb_forwardable(const struct net_device *dev, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca6140)
Location: net/core/dev.c:1822
Inline: True
Direct callers:
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
c000000000ca6140-c000000000ca61a8: is_skb_forwardable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool is_skb_forwardable(const struct net_device *dev, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe0007557de)
Location: net/core/dev.c:1822
Inline: True
Direct callers:
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
ffffffe0007557de-ffffffe000755836: is_skb_forwardable (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool is_skb_forwardable(const struct net_device *dev, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818cca50)
Location: net/core/dev.c:1822
Inline: True
Direct callers:
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
ffffffff818cca50-ffffffff818cca97: is_skb_forwardable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool is_skb_forwardable(const struct net_device *dev, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81886ae0)
Location: net/core/dev.c:1822
Inline: True
Direct callers:
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
ffffffff81886ae0-ffffffff81886b27: is_skb_forwardable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool is_skb_forwardable(const struct net_device *dev, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191da50)
Location: net/core/dev.c:1822
Inline: True
Direct callers:
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
ffffffff8191da50-ffffffff8191da97: is_skb_forwardable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool is_skb_forwardable(const struct net_device *dev, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193f0c0)
Location: net/core/dev.c:1822
Inline: True
Direct callers:
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
ffffffff8193f0c0-ffffffff8193f107: is_skb_forwardable (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct net_device *dev</code> ➡️ <code>const struct net_device *dev</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct sk_buff *skb</code> ➡️ <code>const struct sk_buff *skb</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
