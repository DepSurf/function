# Function: <code>__bpf_redirect</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
int __bpf_redirect(struct sk_buff *skb, struct net_device *dev, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817cbbb0)
Location: net/core/filter.c:1703
Inline: False
Direct callers:
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
**Symbols:**

```
ffffffff817cbbb0-ffffffff817cbe3f: __bpf_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __bpf_redirect(struct sk_buff *skb, struct net_device *dev, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817ea650)
Location: net/core/filter.c:1729
Inline: False
Direct callers:
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
**Symbols:**

```
ffffffff817ea650-ffffffff817ea8cb: __bpf_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __bpf_redirect(struct sk_buff *skb, struct net_device *dev, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81865d80)
Location: net/core/filter.c:1750
Inline: False
Direct callers:
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
**Symbols:**

```
ffffffff81865d80-ffffffff81866015: __bpf_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int __bpf_redirect(struct sk_buff *skb, struct net_device *dev, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:2036
Inline: False
Direct callers:
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
**Symbols:**

```
ffffffff818b3e40-ffffffff818b40ee: __bpf_redirect (STB_LOCAL)
ffffffff818b87a8-ffffffff818b87b9: __bpf_redirect.cold.95 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int __bpf_redirect(struct sk_buff *skb, struct net_device *dev, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:2056
Inline: False
Direct callers:
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
**Symbols:**

```
ffffffff818dc600-ffffffff818dc8b4: __bpf_redirect (STB_LOCAL)
ffffffff818df400-ffffffff818df411: __bpf_redirect.cold.102 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __bpf_redirect(struct sk_buff *skb, struct net_device *dev, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:2102
Inline: False
Direct callers:
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
**Symbols:**

```
ffffffff81929700-ffffffff81929a01: __bpf_redirect (STB_LOCAL)
ffffffff8192da11-ffffffff8192da22: __bpf_redirect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __bpf_redirect(struct sk_buff *skb, struct net_device *dev, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:2103
Inline: False
Direct callers:
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
**Symbols:**

```
ffffffff8195bd60-ffffffff8195c06a: __bpf_redirect (STB_LOCAL)
ffffffff8195fcca-ffffffff8195fcdb: __bpf_redirect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __bpf_redirect(struct sk_buff *skb, struct net_device *dev, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:2128
Inline: False
Direct callers:
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
**Symbols:**

```
ffffffff81a31060-ffffffff81a311ba: __bpf_redirect (STB_LOCAL)
ffffffff81a33232-ffffffff81a33243: __bpf_redirect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __bpf_redirect(struct sk_buff *skb, struct net_device *dev, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:2158
Inline: False
Direct callers:
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
**Symbols:**

```
ffffffff81a334f0-ffffffff81a3364a: __bpf_redirect (STB_LOCAL)
ffffffff81c317a0-ffffffff81c317b1: __bpf_redirect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __bpf_redirect(struct sk_buff *skb, struct net_device *dev, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:2155
Inline: False
Direct callers:
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
**Symbols:**

```
ffffffff81a1a2a0-ffffffff81a1a3f3: __bpf_redirect (STB_LOCAL)
ffffffff81c23aa9-ffffffff81c23aba: __bpf_redirect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __bpf_redirect(struct sk_buff *skb, struct net_device *dev, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:2156
Inline: False
Direct callers:
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
**Symbols:**

```
ffffffff81acc500-ffffffff81acc658: __bpf_redirect (STB_LOCAL)
ffffffff81d37646-ffffffff81d37657: __bpf_redirect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __bpf_redirect(struct sk_buff *skb, struct net_device *dev, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:2157
Inline: False
Direct callers:
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
**Symbols:**

```
ffffffff81c491c0-ffffffff81c49337: __bpf_redirect (STB_LOCAL)
ffffffff81f03f5f-ffffffff81f03f70: __bpf_redirect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __bpf_redirect(struct sk_buff *skb, struct net_device *dev, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81dfdba0)
Location: net/core/filter.c:2164
Inline: False
Direct callers:
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
**Symbols:**

```
ffffffff81dfdba0-ffffffff81dfdd30: __bpf_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __bpf_redirect(struct sk_buff *skb, struct net_device *dev, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e6f0f0)
Location: net/core/filter.c:2176
Inline: False
Direct callers:
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
**Symbols:**

```
ffffffff81e6f0f0-ffffffff81e6f2af: __bpf_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __bpf_redirect(struct sk_buff *skb, struct net_device *dev, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f2e730)
Location: net/core/filter.c:2183
Inline: False
Direct callers:
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
**Symbols:**

```
ffffffff81f2e730-ffffffff81f2e8ef: __bpf_redirect (STB_LOCAL)
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
int __bpf_redirect(struct sk_buff *skb, struct net_device *dev, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010c012e0)
Location: net/core/filter.c:2103
Inline: False
Direct callers:
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
**Symbols:**

```
ffff800010c012e0-ffff800010c015bc: __bpf_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __bpf_redirect(struct sk_buff *skb, struct net_device *dev, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d183e4)
Location: net/core/filter.c:2103
Inline: False
Direct callers:
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
**Symbols:**

```
c0d183e4-c0d186d4: __bpf_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __bpf_redirect(struct sk_buff *skb, struct net_device *dev, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce8d00)
Location: net/core/filter.c:2103
Inline: False
Direct callers:
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
**Symbols:**

```
c000000000ce8d00-c000000000ce9108: __bpf_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __bpf_redirect(struct sk_buff *skb, struct net_device *dev, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077fd9c)
Location: net/core/filter.c:2103
Inline: False
Direct callers:
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
**Symbols:**

```
ffffffe00077fd9c-ffffffe000780070: __bpf_redirect (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int __bpf_redirect(struct sk_buff *skb, struct net_device *dev, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:2103
Inline: False
Direct callers:
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
**Symbols:**

```
ffffffff818fbd30-ffffffff818fc03a: __bpf_redirect (STB_LOCAL)
ffffffff818ffc9a-ffffffff818ffcab: __bpf_redirect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __bpf_redirect(struct sk_buff *skb, struct net_device *dev, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:2103
Inline: False
Direct callers:
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
**Symbols:**

```
ffffffff818b5b60-ffffffff818b5e6a: __bpf_redirect (STB_LOCAL)
ffffffff818b9aca-ffffffff818b9adb: __bpf_redirect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __bpf_redirect(struct sk_buff *skb, struct net_device *dev, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:2103
Inline: False
Direct callers:
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
**Symbols:**

```
ffffffff8194cd60-ffffffff8194d06a: __bpf_redirect (STB_LOCAL)
ffffffff81950cca-ffffffff81950cdb: __bpf_redirect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __bpf_redirect(struct sk_buff *skb, struct net_device *dev, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:2103
Inline: False
Direct callers:
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
**Symbols:**

```
ffffffff8196e720-ffffffff8196ea2a: __bpf_redirect (STB_LOCAL)
ffffffff8197269a-ffffffff819726ab: __bpf_redirect.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
