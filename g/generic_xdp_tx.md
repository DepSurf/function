# Function: <code>generic_xdp_tx</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817d0ae3)
Location: net/core/dev.c:4437
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void generic_xdp_tx(struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8184a440)
Location: net/core/dev.c:3997
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/dev.c:do_xdp_generic
```
**Symbols:**

```
ffffffff8184a440-ffffffff8184a5ba: generic_xdp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void generic_xdp_tx(struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81894760)
Location: net/core/dev.c:4116
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff81894760-ffffffff818948bb: generic_xdp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void generic_xdp_tx(struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b5170)
Location: net/core/dev.c:4425
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff818b5170-ffffffff818b52c8: generic_xdp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void generic_xdp_tx(struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81901b60)
Location: net/core/dev.c:4439
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff81901b60-ffffffff81901cb3: generic_xdp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void generic_xdp_tx(struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81933da0)
Location: net/core/dev.c:4341
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff81933da0-ffffffff81933ef3: generic_xdp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void generic_xdp_tx(struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a087c0)
Location: net/core/dev.c:4704
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff81a087c0-ffffffff81a0890e: generic_xdp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void generic_xdp_tx(struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a09d80)
Location: net/core/dev.c:4733
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff81a09d80-ffffffff81a09ebf: generic_xdp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void generic_xdp_tx(struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819f0710)
Location: net/core/dev.c:4841
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff819f0710-ffffffff819f084f: generic_xdp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void generic_xdp_tx(struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81aa1f00)
Location: net/core/dev.c:4832
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff81aa1f00-ffffffff81aa203c: generic_xdp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void generic_xdp_tx(struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c1a290)
Location: net/core/dev.c:4872
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - net/core/dev.c:do_xdp_generic
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff81c1a290-ffffffff81c1a4a5: generic_xdp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void generic_xdp_tx(struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dcb330)
Location: net/core/dev.c:4859
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - net/core/dev.c:do_xdp_generic
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff81dcb330-ffffffff81dcb522: generic_xdp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void generic_xdp_tx(struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e3bec0)
Location: net/core/dev.c:4834
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - net/core/dev.c:do_xdp_generic
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff81e3bec0-ffffffff81e3c0b2: generic_xdp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void generic_xdp_tx(struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81efa400)
Location: net/core/dev.c:4982
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - net/core/dev.c:do_xdp_generic
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff81efa400-ffffffff81efa5d1: generic_xdp_tx (STB_GLOBAL)
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
void generic_xdp_tx(struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd2048)
Location: net/core/dev.c:4341
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffff800010bd2048-ffff800010bd2234: generic_xdp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void generic_xdp_tx(struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cecc34)
Location: net/core/dev.c:4341
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
c0cecc34-c0cecdf0: generic_xdp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void generic_xdp_tx(struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cb05e0)
Location: net/core/dev.c:4341
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
c000000000cb05e0-c000000000cb0800: generic_xdp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void generic_xdp_tx(struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075c5ea)
Location: net/core/dev.c:4341
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffe00075c5ea-ffffffe00075c772: generic_xdp_tx (STB_GLOBAL)
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
void generic_xdp_tx(struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d3da0)
Location: net/core/dev.c:4341
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff818d3da0-ffffffff818d3ef3: generic_xdp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void generic_xdp_tx(struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188dc30)
Location: net/core/dev.c:4341
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff8188dc30-ffffffff8188dd83: generic_xdp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void generic_xdp_tx(struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81924da0)
Location: net/core/dev.c:4341
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff81924da0-ffffffff81924ef3: generic_xdp_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void generic_xdp_tx(struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81946250)
Location: net/core/dev.c:4341
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff81946250-ffffffff819463d1: generic_xdp_tx (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
