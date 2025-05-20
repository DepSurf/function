# Function: <code>__xsk_rcv_zc</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff819cc7c4)
Location: net/xdp/xsk.c:83
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_rcv
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
In net/xdp/xsk.c (ffffffff81a0584a)
Location: net/xdp/xsk.c:93
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_rcv
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
In net/xdp/xsk.c (ffffffff81a75127)
Location: net/xdp/xsk.c:95
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_rcv
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
In net/xdp/xsk.c (ffffffff81aabd23)
Location: net/xdp/xsk.c:179
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __xsk_rcv_zc(struct xdp_sock *xs, struct xdp_buff *xdp, u32 len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba73f0)
Location: net/xdp/xsk.c:117
Inline: True
Direct callers:
  - net/xdp/xsk.c:__xsk_rcv
```
**Symbols:**

```
ffffffff81ba73f0-ffffffff81ba7498: __xsk_rcv_zc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __xsk_rcv_zc(struct xdp_sock *xs, struct xdp_buff *xdp, u32 len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81bb6b30)
Location: net/xdp/xsk.c:152
Inline: True
Direct callers:
  - net/xdp/xsk.c:__xsk_map_redirect
  - net/xdp/xsk.c:__xsk_rcv
```
**Symbols:**

```
ffffffff81bb6b30-ffffffff81bb6bf1: __xsk_rcv_zc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __xsk_rcv_zc(struct xdp_sock *xs, struct xdp_buff *xdp, u32 len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba5ae0)
Location: net/xdp/xsk.c:152
Inline: True
Direct callers:
  - net/xdp/xsk.c:__xsk_map_redirect
  - net/xdp/xsk.c:__xsk_rcv
```
**Symbols:**

```
ffffffff81ba5ae0-ffffffff81ba5ba5: __xsk_rcv_zc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __xsk_rcv_zc(struct xdp_sock *xs, struct xdp_buff *xdp, u32 len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (ffffffff81c735e1)
Location: net/xdp/xsk.c:152
Inline: True
Direct callers:
  - net/xdp/xsk.c:__xsk_map_redirect
  - net/xdp/xsk.c:__xsk_rcv
```
**Symbols:**

```
ffffffff81c73540-ffffffff81c73622: __xsk_rcv_zc (STB_LOCAL)
ffffffff81d4301e-ffffffff81d43033: __xsk_rcv_zc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __xsk_rcv_zc(struct xdp_sock *xs, struct xdp_buff *xdp, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:137
Inline: False
Direct callers:
  - net/xdp/xsk.c:__xsk_map_redirect
  - net/xdp/xsk.c:__xsk_rcv
```
**Symbols:**

```
ffffffff81e17110-ffffffff81e17223: __xsk_rcv_zc (STB_LOCAL)
ffffffff81f0f98a-ffffffff81f0f9b3: __xsk_rcv_zc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __xsk_rcv_zc(struct xdp_sock *xs, struct xdp_buff *xdp, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:137
Inline: False
Direct callers:
  - net/xdp/xsk.c:__xsk_map_redirect
  - net/xdp/xsk.c:__xsk_rcv
```
**Symbols:**

```
ffffffff81fedf60-ffffffff81fee073: __xsk_rcv_zc (STB_LOCAL)
ffffffff820b5d0b-ffffffff820b5d34: __xsk_rcv_zc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __xsk_rcv_zc(struct xdp_sock *xs, struct xdp_buff *xdp, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:138
Inline: False
Direct callers:
  - net/xdp/xsk.c:__xsk_map_redirect
  - net/xdp/xsk.c:__xsk_rcv
```
**Symbols:**

```
ffffffff8206a0c0-ffffffff8206a1d3: __xsk_rcv_zc (STB_LOCAL)
ffffffff82137252-ffffffff8213727b: __xsk_rcv_zc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __xsk_rcv_zc(struct xdp_sock *xs, struct xdp_buff_xsk *xskb, u32 len, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:140
Inline: False
Direct callers:
  - net/xdp/xsk.c:__xsk_map_redirect
  - net/xdp/xsk.c:__xsk_map_redirect
  - net/xdp/xsk.c:__xsk_rcv
  - net/xdp/xsk.c:__xsk_rcv
```
**Symbols:**

```
ffffffff8213d580-ffffffff8213d6a4: __xsk_rcv_zc (STB_LOCAL)
ffffffff822190d1-ffffffff82219100: __xsk_rcv_zc.cold (STB_LOCAL)
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
In net/xdp/xsk.c (ffff800010d80444)
Location: net/xdp/xsk.c:179
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_rcv
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
In net/xdp/xsk.c (c0e7a9bc)
Location: net/xdp/xsk.c:179
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_rcv
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
In net/xdp/xsk.c (c000000000ec0138)
Location: net/xdp/xsk.c:179
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_rcv
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
In net/xdp/xsk.c (ffffffe0008acd9a)
Location: net/xdp/xsk.c:179
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_rcv
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
In net/xdp/xsk.c (ffffffff81a4b0b3)
Location: net/xdp/xsk.c:179
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_rcv
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
In net/xdp/xsk.c (ffffffff81a07ca3)
Location: net/xdp/xsk.c:179
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_rcv
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
In net/xdp/xsk.c (ffffffff81ab6f63)
Location: net/xdp/xsk.c:179
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_rcv
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
In net/xdp/xsk.c (ffffffff81ac3383)
Location: net/xdp/xsk.c:179
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_rcv
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct xdp_buff_xsk *xskb</code>
</li>
<li>
<b>Param added. </b>
<code>u32 flags</code>
</li>
<li>
<b>Param removed. </b>
<code>struct xdp_buff *xdp</code>
</li>
</ul>
</details>
</li>
</ul>
