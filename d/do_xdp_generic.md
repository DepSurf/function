# Function: <code>do_xdp_generic</code>

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
int do_xdp_generic(struct bpf_prog *xdp_prog, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8184a5c0)
Location: net/core/dev.c:4022
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff8184a5c0-ffffffff8184a8d4: do_xdp_generic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_xdp_generic(struct bpf_prog *xdp_prog, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81894d7f)
Location: net/core/dev.c:4141
Inline: True
Inline callers:
  - net/core/dev.c:netif_rx_internal
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff818948c0-ffffffff81894c86: do_xdp_generic.part.126 (STB_LOCAL)
ffffffff81894c90-ffffffff81894cab: do_xdp_generic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_xdp_generic(struct bpf_prog *xdp_prog, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff818b8234)
Location: net/core/dev.c:4450
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_rx_internal
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_rx_internal
```
**Symbols:**

```
ffffffff818b52d0-ffffffff818b56e3: do_xdp_generic.part.133 (STB_LOCAL)
ffffffff818b56f0-ffffffff818b570b: do_xdp_generic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_xdp_generic(struct bpf_prog *xdp_prog, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81901f14)
Location: net/core/dev.c:4464
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - net/core/dev.c:__netif_receive_skb_core
```
**Symbols:**

```
ffffffff81901cc0-ffffffff81901d66: do_xdp_generic.part.0 (STB_LOCAL)
ffffffff81901d70-ffffffff81901d8b: do_xdp_generic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_xdp_generic(struct bpf_prog *xdp_prog, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81934154)
Location: net/core/dev.c:4366
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - net/core/dev.c:__netif_receive_skb_core
```
**Symbols:**

```
ffffffff81933f00-ffffffff81933fa6: do_xdp_generic.part.0 (STB_LOCAL)
ffffffff81933fb0-ffffffff81933fcb: do_xdp_generic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_xdp_generic(struct bpf_prog *xdp_prog, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81a08c42)
Location: net/core/dev.c:4728
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/dev.c:__netif_receive_skb_core
```
**Symbols:**

```
ffffffff81a08910-ffffffff81a089b6: do_xdp_generic.part.0 (STB_LOCAL)
ffffffff81a0b4d0-ffffffff81a0b57c: do_xdp_generic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_xdp_generic(struct bpf_prog *xdp_prog, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81a0a157)
Location: net/core/dev.c:4757
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/dev.c:__netif_receive_skb_core
```
**Symbols:**

```
ffffffff81a09ec0-ffffffff81a09f66: do_xdp_generic.part.0 (STB_LOCAL)
ffffffff81a0cb70-ffffffff81a0cc1c: do_xdp_generic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_xdp_generic(struct bpf_prog *xdp_prog, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff819f0850)
Location: net/core/dev.c:4865
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff819f0850-ffffffff819f08f6: do_xdp_generic.part.0 (STB_LOCAL)
ffffffff819f3820-ffffffff819f38cc: do_xdp_generic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_xdp_generic(struct bpf_prog *xdp_prog, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81aa2040)
Location: net/core/dev.c:4856
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81aa2040-ffffffff81aa2232: do_xdp_generic.part.0 (STB_LOCAL)
ffffffff81aa2240-ffffffff81aa225b: do_xdp_generic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_xdp_generic(struct bpf_prog *xdp_prog, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c1a4b0)
Location: net/core/dev.c:4897
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81c1a4b0-ffffffff81c1a574: do_xdp_generic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_xdp_generic(struct bpf_prog *xdp_prog, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dcb540)
Location: net/core/dev.c:4884
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81dcb540-ffffffff81dcb604: do_xdp_generic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_xdp_generic(struct bpf_prog *xdp_prog, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e3c0d0)
Location: net/core/dev.c:4859
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81e3c0d0-ffffffff81e3c194: do_xdp_generic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_xdp_generic(struct bpf_prog *xdp_prog, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81efa5f0)
Location: net/core/dev.c:5007
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff81efa5f0-ffffffff81efa6b4: do_xdp_generic (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_xdp_generic(struct bpf_prog *xdp_prog, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffff800010bd24c4)
Location: net/core/dev.c:4366
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - net/core/dev.c:__netif_receive_skb_core
```
**Symbols:**

```
ffff800010bd2238-ffff800010bd22fc: do_xdp_generic.part.0 (STB_LOCAL)
ffff800010bd2300-ffff800010bd233c: do_xdp_generic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_xdp_generic(struct bpf_prog *xdp_prog, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (c0ced5c4)
Location: net/core/dev.c:4366
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
Direct callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - net/core/dev.c:__netif_receive_skb_core
```
**Symbols:**

```
c0cecdf0-c0ceceb0: do_xdp_generic.part.0 (STB_LOCAL)
c0ceceb0-c0cecedc: do_xdp_generic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_xdp_generic(struct bpf_prog *xdp_prog, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (c000000000cb0bbc)
Location: net/core/dev.c:4366
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - net/core/dev.c:__netif_receive_skb_core
```
**Symbols:**

```
c000000000cb0800-c000000000cb08f8: do_xdp_generic.part.0 (STB_LOCAL)
c000000000cb0900-c000000000cb0928: do_xdp_generic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_xdp_generic(struct bpf_prog *xdp_prog, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffe00075cd76)
Location: net/core/dev.c:4366
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - net/core/dev.c:__netif_receive_skb_core
```
**Symbols:**

```
ffffffe00075c772-ffffffe00075c7f2: do_xdp_generic.part.0 (STB_LOCAL)
ffffffe00075c7f2-ffffffe00075c828: do_xdp_generic (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_xdp_generic(struct bpf_prog *xdp_prog, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff818d4154)
Location: net/core/dev.c:4366
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - net/core/dev.c:__netif_receive_skb_core
```
**Symbols:**

```
ffffffff818d3f00-ffffffff818d3fa6: do_xdp_generic.part.0 (STB_LOCAL)
ffffffff818d3fb0-ffffffff818d3fcb: do_xdp_generic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_xdp_generic(struct bpf_prog *xdp_prog, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff8188dfe4)
Location: net/core/dev.c:4366
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - net/core/dev.c:__netif_receive_skb_core
```
**Symbols:**

```
ffffffff8188dd90-ffffffff8188de36: do_xdp_generic.part.0 (STB_LOCAL)
ffffffff8188de40-ffffffff8188de5b: do_xdp_generic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_xdp_generic(struct bpf_prog *xdp_prog, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81925154)
Location: net/core/dev.c:4366
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - net/core/dev.c:__netif_receive_skb_core
```
**Symbols:**

```
ffffffff81924f00-ffffffff81924fa6: do_xdp_generic.part.0 (STB_LOCAL)
ffffffff81924fb0-ffffffff81924fcb: do_xdp_generic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_xdp_generic(struct bpf_prog *xdp_prog, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff8194663b)
Location: net/core/dev.c:4366
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - net/core/dev.c:__netif_receive_skb_core
```
**Symbols:**

```
ffffffff819463e0-ffffffff81946486: do_xdp_generic.part.0 (STB_LOCAL)
ffffffff81946490-ffffffff819464ab: do_xdp_generic (STB_GLOBAL)
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
