# Function: <code>dev_map_generic_redirect</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dev_map_generic_redirect(struct bpf_dtab_netdev *dst, struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811ca140)
Location: kernel/bpf/devmap.c:357
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff811ca140-ffffffff811ca195: dev_map_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dev_map_generic_redirect(struct bpf_dtab_netdev *dst, struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811dda60)
Location: kernel/bpf/devmap.c:358
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff811dda60-ffffffff811ddab2: dev_map_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dev_map_generic_redirect(struct bpf_dtab_netdev *dst, struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811f3110)
Location: kernel/bpf/devmap.c:344
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff811f3110-ffffffff811f3161: dev_map_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dev_map_generic_redirect(struct bpf_dtab_netdev *dst, struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811ffeb0)
Location: kernel/bpf/devmap.c:482
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff811ffeb0-ffffffff811fff01: dev_map_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dev_map_generic_redirect(struct bpf_dtab_netdev *dst, struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff81227960)
Location: kernel/bpf/devmap.c:515
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_generic_redirect_map
```
**Symbols:**

```
ffffffff81227960-ffffffff812279b1: dev_map_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dev_map_generic_redirect(struct bpf_dtab_netdev *dst, struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8122e4c0)
Location: kernel/bpf/devmap.c:500
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_generic_redirect_map
```
**Symbols:**

```
ffffffff8122e4c0-ffffffff8122e511: dev_map_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dev_map_generic_redirect(struct bpf_dtab_netdev *dst, struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff81233330)
Location: kernel/bpf/devmap.c:493
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff81233330-ffffffff81233381: dev_map_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dev_map_generic_redirect(struct bpf_dtab_netdev *dst, struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8126cbe0)
Location: kernel/bpf/devmap.c:668
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff8126cbe0-ffffffff8126cd3f: dev_map_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dev_map_generic_redirect(struct bpf_dtab_netdev *dst, struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff812bb8d0)
Location: kernel/bpf/devmap.c:659
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff812bb8d0-ffffffff812bba6b: dev_map_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_map_generic_redirect(struct bpf_dtab_netdev *dst, struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8131ec60)
Location: kernel/bpf/devmap.c:659
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff8131ec60-ffffffff8131edfb: dev_map_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_map_generic_redirect(struct bpf_dtab_netdev *dst, struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8134ea80)
Location: kernel/bpf/devmap.c:666
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff8134ea80-ffffffff8134ec1b: dev_map_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dev_map_generic_redirect(struct bpf_dtab_netdev *dst, struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff81375f80)
Location: kernel/bpf/devmap.c:675
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - kernel/bpf/devmap.c:dev_map_redirect_multi
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff81375f80-ffffffff81376118: dev_map_generic_redirect (STB_GLOBAL)
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
int dev_map_generic_redirect(struct bpf_dtab_netdev *dst, struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffff800010287818)
Location: kernel/bpf/devmap.c:482
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffff800010287818-ffff8000102878a4: dev_map_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dev_map_generic_redirect(struct bpf_dtab_netdev *dst, struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (c04b7770)
Location: kernel/bpf/devmap.c:482
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
c04b7770-c04b77e0: dev_map_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dev_map_generic_redirect(struct bpf_dtab_netdev *dst, struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (c0000000003329d0)
Location: kernel/bpf/devmap.c:482
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
c0000000003329d0-c000000000332a50: dev_map_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dev_map_generic_redirect(struct bpf_dtab_netdev *dst, struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffe0001bc2a0)
Location: kernel/bpf/devmap.c:482
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffe0001bc2a0-ffffffe0001bc312: dev_map_generic_redirect (STB_GLOBAL)
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
int dev_map_generic_redirect(struct bpf_dtab_netdev *dst, struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811f84d0)
Location: kernel/bpf/devmap.c:482
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff811f84d0-ffffffff811f8521: dev_map_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dev_map_generic_redirect(struct bpf_dtab_netdev *dst, struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811eb220)
Location: kernel/bpf/devmap.c:482
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff811eb220-ffffffff811eb271: dev_map_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dev_map_generic_redirect(struct bpf_dtab_netdev *dst, struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811f62a0)
Location: kernel/bpf/devmap.c:482
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff811f62a0-ffffffff811f62f1: dev_map_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dev_map_generic_redirect(struct bpf_dtab_netdev *dst, struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff81204810)
Location: kernel/bpf/devmap.c:482
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff81204810-ffffffff81204861: dev_map_generic_redirect (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
