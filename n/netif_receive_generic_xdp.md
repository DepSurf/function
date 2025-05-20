# Function: <code>netif_receive_generic_xdp</code>

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
In net/core/dev.c (ffffffff817d0a01)
Location: net/core/dev.c:4376
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_internal
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
In net/core/dev.c (ffffffff8184a5ee)
Location: net/core/dev.c:3914
Inline: True
Inline callers:
  - net/core/dev.c:do_xdp_generic
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
In net/core/dev.c (ffffffff818948f2)
Location: net/core/dev.c:4018
Inline: True
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
In net/core/dev.c (ffffffff818b52fb)
Location: net/core/dev.c:4313
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 netif_receive_generic_xdp(struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818faa40)
Location: net/core/dev.c:4322
Inline: False
```
**Symbols:**

```
ffffffff818faa40-ffffffff818fae6a: netif_receive_generic_xdp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 netif_receive_generic_xdp(struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192cb80)
Location: net/core/dev.c:4224
Inline: False
```
**Symbols:**

```
ffffffff8192cb80-ffffffff8192cfb8: netif_receive_generic_xdp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 netif_receive_generic_xdp(struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a065a0)
Location: net/core/dev.c:4585
Inline: False
```
**Symbols:**

```
ffffffff81a065a0-ffffffff81a06a07: netif_receive_generic_xdp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 netif_receive_generic_xdp(struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a07b50)
Location: net/core/dev.c:4614
Inline: False
```
**Symbols:**

```
ffffffff81a07b50-ffffffff81a07fd9: netif_receive_generic_xdp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 netif_receive_generic_xdp(struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ea4d0)
Location: net/core/dev.c:4720
Inline: False
```
**Symbols:**

```
ffffffff819ea4d0-ffffffff819ea92a: netif_receive_generic_xdp (STB_LOCAL)
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
In net/core/dev.c (ffffffff81aa2061)
Location: net/core/dev.c:4776
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 netif_receive_generic_xdp(struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c1a0f0)
Location: net/core/dev.c:4813
Inline: False
Direct callers:
  - net/core/dev.c:do_xdp_generic
```
**Symbols:**

```
ffffffff81c1a0f0-ffffffff81c1a281: netif_receive_generic_xdp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 netif_receive_generic_xdp(struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dcb180)
Location: net/core/dev.c:4800
Inline: False
Direct callers:
  - net/core/dev.c:do_xdp_generic
```
**Symbols:**

```
ffffffff81dcb180-ffffffff81dcb31e: netif_receive_generic_xdp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 netif_receive_generic_xdp(struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e3bd10)
Location: net/core/dev.c:4775
Inline: False
Direct callers:
  - net/core/dev.c:do_xdp_generic
```
**Symbols:**

```
ffffffff81e3bd10-ffffffff81e3bea8: netif_receive_generic_xdp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 netif_receive_generic_xdp(struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81efa250)
Location: net/core/dev.c:4923
Inline: False
Direct callers:
  - net/core/dev.c:do_xdp_generic
```
**Symbols:**

```
ffffffff81efa250-ffffffff81efa3e8: netif_receive_generic_xdp (STB_LOCAL)
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
u32 netif_receive_generic_xdp(struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bcf4a8)
Location: net/core/dev.c:4224
Inline: False
```
**Symbols:**

```
ffff800010bcf4a8-ffff800010bcf908: netif_receive_generic_xdp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 netif_receive_generic_xdp(struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce5868)
Location: net/core/dev.c:4224
Inline: False
```
**Symbols:**

```
c0ce5868-c0ce5cfc: netif_receive_generic_xdp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 netif_receive_generic_xdp(struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca6270)
Location: net/core/dev.c:4224
Inline: False
```
**Symbols:**

```
c000000000ca6270-c000000000ca682c: netif_receive_generic_xdp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 netif_receive_generic_xdp(struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe0007559b0)
Location: net/core/dev.c:4224
Inline: False
```
**Symbols:**

```
ffffffe0007559b0-ffffffe000755d68: netif_receive_generic_xdp (STB_LOCAL)
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
u32 netif_receive_generic_xdp(struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ccb80)
Location: net/core/dev.c:4224
Inline: False
```
**Symbols:**

```
ffffffff818ccb80-ffffffff818ccfb8: netif_receive_generic_xdp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 netif_receive_generic_xdp(struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81886c10)
Location: net/core/dev.c:4224
Inline: False
```
**Symbols:**

```
ffffffff81886c10-ffffffff81887048: netif_receive_generic_xdp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 netif_receive_generic_xdp(struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191db80)
Location: net/core/dev.c:4224
Inline: False
```
**Symbols:**

```
ffffffff8191db80-ffffffff8191dfb8: netif_receive_generic_xdp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 netif_receive_generic_xdp(struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193f1f0)
Location: net/core/dev.c:4224
Inline: False
```
**Symbols:**

```
ffffffff8193f1f0-ffffffff8193f641: netif_receive_generic_xdp (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
