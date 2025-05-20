# Function: <code>xdp_do_generic_redirect</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xdp_do_generic_redirect(struct net_device *dev, struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81868650)
Location: net/core/filter.c:2731
Inline: False
Direct callers:
  - net/core/dev.c:do_xdp_generic
```
**Symbols:**

```
ffffffff81868650-ffffffff818687c5: xdp_do_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xdp_do_generic_redirect(struct net_device *dev, struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b5090)
Location: net/core/filter.c:3368
Inline: False
```
**Symbols:**

```
ffffffff818b5090-ffffffff818b53ff: xdp_do_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xdp_do_generic_redirect(struct net_device *dev, struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d9c20)
Location: net/core/filter.c:3560
Inline: False
```
**Symbols:**

```
ffffffff818d9c20-ffffffff818d9fc6: xdp_do_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xdp_do_generic_redirect(struct net_device *dev, struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81927880)
Location: net/core/filter.c:3684
Inline: False
```
**Symbols:**

```
ffffffff81927880-ffffffff81927b94: xdp_do_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xdp_do_generic_redirect(struct net_device *dev, struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8195ab10)
Location: net/core/filter.c:3691
Inline: False
```
**Symbols:**

```
ffffffff8195ab10-ffffffff8195ae41: xdp_do_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xdp_do_generic_redirect(struct net_device *dev, struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a32760)
Location: net/core/filter.c:3651
Inline: False
```
**Symbols:**

```
ffffffff81a32760-ffffffff81a328d7: xdp_do_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xdp_do_generic_redirect(struct net_device *dev, struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a34b30)
Location: net/core/filter.c:4058
Inline: False
```
**Symbols:**

```
ffffffff81a34b30-ffffffff81a34c88: xdp_do_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xdp_do_generic_redirect(struct net_device *dev, struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a1bb30)
Location: net/core/filter.c:4013
Inline: False
```
**Symbols:**

```
ffffffff81a1bb30-ffffffff81a1bdea: xdp_do_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xdp_do_generic_redirect(struct net_device *dev, struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81acf2a0)
Location: net/core/filter.c:4071
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
```
**Symbols:**

```
ffffffff81acf2a0-ffffffff81acf5a5: xdp_do_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xdp_do_generic_redirect(struct net_device *dev, struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c4c9e0)
Location: net/core/filter.c:4352
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
  - net/core/dev.c:do_xdp_generic
```
**Symbols:**

```
ffffffff81c4c9e0-ffffffff81c4cd4e: xdp_do_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xdp_do_generic_redirect(struct net_device *dev, struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e01820)
Location: net/core/filter.c:4366
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
  - net/core/dev.c:do_xdp_generic
```
**Symbols:**

```
ffffffff81e01820-ffffffff81e01b91: xdp_do_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xdp_do_generic_redirect(struct net_device *dev, struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e73af0)
Location: net/core/filter.c:4417
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
  - net/core/dev.c:do_xdp_generic
```
**Symbols:**

```
ffffffff81e73af0-ffffffff81e73eaf: xdp_do_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xdp_do_generic_redirect(struct net_device *dev, struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f332b0)
Location: net/core/filter.c:4491
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
  - net/core/dev.c:do_xdp_generic
```
**Symbols:**

```
ffffffff81f332b0-ffffffff81f3366c: xdp_do_generic_redirect (STB_GLOBAL)
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
int xdp_do_generic_redirect(struct net_device *dev, struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010c01c00)
Location: net/core/filter.c:3691
Inline: False
```
**Symbols:**

```
ffff800010c01c00-ffff800010c01fe8: xdp_do_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xdp_do_generic_redirect(struct net_device *dev, struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d15794)
Location: net/core/filter.c:3691
Inline: False
```
**Symbols:**

```
c0d15794-c0d15b70: xdp_do_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xdp_do_generic_redirect(struct net_device *dev, struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce47e0)
Location: net/core/filter.c:3691
Inline: False
```
**Symbols:**

```
c000000000ce47e0-c000000000ce4cd0: xdp_do_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xdp_do_generic_redirect(struct net_device *dev, struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077dc98)
Location: net/core/filter.c:3691
Inline: False
```
**Symbols:**

```
ffffffe00077dc98-ffffffe00077df7c: xdp_do_generic_redirect (STB_GLOBAL)
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
int xdp_do_generic_redirect(struct net_device *dev, struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818faae0)
Location: net/core/filter.c:3691
Inline: False
```
**Symbols:**

```
ffffffff818faae0-ffffffff818fae11: xdp_do_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int xdp_do_generic_redirect(struct net_device *dev, struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b4910)
Location: net/core/filter.c:3691
Inline: False
```
**Symbols:**

```
ffffffff818b4910-ffffffff818b4c41: xdp_do_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xdp_do_generic_redirect(struct net_device *dev, struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8194bb10)
Location: net/core/filter.c:3691
Inline: False
```
**Symbols:**

```
ffffffff8194bb10-ffffffff8194be41: xdp_do_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xdp_do_generic_redirect(struct net_device *dev, struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8196d420)
Location: net/core/filter.c:3691
Inline: False
```
**Symbols:**

```
ffffffff8196d420-ffffffff8196d795: xdp_do_generic_redirect (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct xdp_buff *xdp</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, skb, xdp_prog</code> ➡️ <code>dev, skb, xdp, xdp_prog</code>
</li>
</ul>
</details>
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
