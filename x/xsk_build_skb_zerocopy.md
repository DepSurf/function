# Function: <code>xsk_build_skb_zerocopy</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *xsk_build_skb_zerocopy(struct xdp_sock *xs, struct xdp_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba51f0)
Location: net/xdp/xsk.c:448
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_generic_xmit
```
**Symbols:**

```
ffffffff81ba51f0-ffffffff81ba53e1: xsk_build_skb_zerocopy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct sk_buff *xsk_build_skb_zerocopy(struct xdp_sock *xs, struct xdp_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:448
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_generic_xmit
```
**Symbols:**

```
ffffffff81c72d70-ffffffff81c72f6f: xsk_build_skb_zerocopy (STB_LOCAL)
ffffffff81d42fcd-ffffffff81d42ff0: xsk_build_skb_zerocopy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct sk_buff *xsk_build_skb_zerocopy(struct xdp_sock *xs, struct xdp_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:423
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_generic_xmit
```
**Symbols:**

```
ffffffff81e17ba0-ffffffff81e17e5b: xsk_build_skb_zerocopy (STB_LOCAL)
ffffffff81f0fa1d-ffffffff81f0fa40: xsk_build_skb_zerocopy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct sk_buff *xsk_build_skb_zerocopy(struct xdp_sock *xs, struct xdp_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:423
Inline: False
Direct callers:
  - net/xdp/xsk.c:__xsk_generic_xmit
```
**Symbols:**

```
ffffffff81feed40-ffffffff81feeffb: xsk_build_skb_zerocopy (STB_LOCAL)
ffffffff820b5db3-ffffffff820b5dd6: xsk_build_skb_zerocopy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct sk_buff *xsk_build_skb_zerocopy(struct xdp_sock *xs, struct xdp_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:424
Inline: False
Direct callers:
  - net/xdp/xsk.c:__xsk_generic_xmit
```
**Symbols:**

```
ffffffff8206acc0-ffffffff8206afe2: xsk_build_skb_zerocopy (STB_LOCAL)
ffffffff821372e5-ffffffff8213730a: xsk_build_skb_zerocopy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct sk_buff *xsk_build_skb_zerocopy(struct xdp_sock *xs, struct xdp_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:613
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_build_skb
```
**Symbols:**

```
ffffffff8213e690-ffffffff8213e9de: xsk_build_skb_zerocopy (STB_LOCAL)
ffffffff82219179-ffffffff8221919d: xsk_build_skb_zerocopy.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
