# Function: <code>xdp_return_buff</code>

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
void xdp_return_buff(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818babe0)
Location: net/core/xdp.c:361
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_rcv
```
**Symbols:**

```
ffffffff818babe0-ffffffff818bac04: xdp_return_buff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void xdp_return_buff(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818e1c60)
Location: net/core/xdp.c:376
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
Direct callers:
  - net/xdp/xsk.c:xsk_rcv
```
**Symbols:**

```
ffffffff818e1b50-ffffffff818e1b74: xdp_return_buff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void xdp_return_buff(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff819306ec)
Location: net/core/xdp.c:448
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
Direct callers:
  - net/xdp/xsk.c:xsk_rcv
```
**Symbols:**

```
ffffffff819305d0-ffffffff819305f4: xdp_return_buff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void xdp_return_buff(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff8196284c)
Location: net/core/xdp.c:415
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
Direct callers:
  - net/xdp/xsk.c:xsk_rcv
```
**Symbols:**

```
ffffffff81962730-ffffffff81962754: xdp_return_buff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xdp_return_buff(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a364c0)
Location: net/core/xdp.c:383
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_run_prog
  - kernel/bpf/devmap.c:dev_map_run_prog
  - net/xdp/xsk.c:__xsk_rcv
```
**Symbols:**

```
ffffffff81a364c0-ffffffff81a364e0: xdp_return_buff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xdp_return_buff(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a38860)
Location: net/core/xdp.c:441
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_run_prog
  - kernel/bpf/devmap.c:dev_map_run_prog
  - net/xdp/xsk.c:__xsk_rcv
```
**Symbols:**

```
ffffffff81a38860-ffffffff81a38883: xdp_return_buff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xdp_return_buff(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a1fb10)
Location: net/core/xdp.c:442
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_run_prog
  - kernel/bpf/devmap.c:dev_map_run_prog
  - net/xdp/xsk.c:__xsk_map_redirect
```
**Symbols:**

```
ffffffff81a1fb10-ffffffff81a1fb33: xdp_return_buff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xdp_return_buff(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81ad3c90)
Location: net/core/xdp.c:443
Inline: False
Direct callers:
  - net/xdp/xsk.c:__xsk_map_redirect
```
**Symbols:**

```
ffffffff81ad3c90-ffffffff81ad3cb3: xdp_return_buff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xdp_return_buff(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81c51fa0)
Location: net/core/xdp.c:515
Inline: False
Direct callers:
  - net/xdp/xsk.c:__xsk_map_redirect
```
**Symbols:**

```
ffffffff81c51fa0-ffffffff81c52047: xdp_return_buff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xdp_return_buff(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81e07220)
Location: net/core/xdp.c:513
Inline: False
Direct callers:
  - net/xdp/xsk.c:__xsk_map_redirect
```
**Symbols:**

```
ffffffff81e07220-ffffffff81e072c7: xdp_return_buff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xdp_return_buff(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81e79a10)
Location: net/core/xdp.c:515
Inline: False
Direct callers:
  - net/xdp/xsk.c:__xsk_map_redirect
```
**Symbols:**

```
ffffffff81e79a10-ffffffff81e79ad3: xdp_return_buff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xdp_return_buff(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81f39b30)
Location: net/core/xdp.c:515
Inline: False
Direct callers:
  - net/xdp/xsk.c:__xsk_map_redirect
```
**Symbols:**

```
ffffffff81f39b30-ffffffff81f39bf3: xdp_return_buff (STB_GLOBAL)
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
void xdp_return_buff(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffff800010c07154)
Location: net/core/xdp.c:415
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
Direct callers:
  - net/xdp/xsk.c:xsk_rcv
```
**Symbols:**

```
ffff800010c07038-ffff800010c07070: xdp_return_buff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void xdp_return_buff(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (c0d2035c)
Location: net/core/xdp.c:415
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
Direct callers:
  - net/xdp/xsk.c:xsk_rcv
```
**Symbols:**

```
c0d20238-c0d20268: xdp_return_buff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void xdp_return_buff(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (c000000000cf1a1c)
Location: net/core/xdp.c:415
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
Direct callers:
  - net/xdp/xsk.c:xsk_rcv
```
**Symbols:**

```
c000000000cf18d0-c000000000cf18f8: xdp_return_buff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void xdp_return_buff(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffe000785522)
Location: net/core/xdp.c:415
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
Direct callers:
  - net/xdp/xsk.c:xsk_rcv
```
**Symbols:**

```
ffffffe000785426-ffffffe000785458: xdp_return_buff (STB_GLOBAL)
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
void xdp_return_buff(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff8190281c)
Location: net/core/xdp.c:415
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
Direct callers:
  - net/xdp/xsk.c:xsk_rcv
```
**Symbols:**

```
ffffffff81902700-ffffffff81902724: xdp_return_buff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void xdp_return_buff(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818bc64c)
Location: net/core/xdp.c:415
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
Direct callers:
  - net/xdp/xsk.c:xsk_rcv
```
**Symbols:**

```
ffffffff818bc530-ffffffff818bc554: xdp_return_buff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void xdp_return_buff(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff8195384c)
Location: net/core/xdp.c:415
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
Direct callers:
  - net/xdp/xsk.c:xsk_rcv
```
**Symbols:**

```
ffffffff81953730-ffffffff81953754: xdp_return_buff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void xdp_return_buff(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff8197536c)
Location: net/core/xdp.c:415
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
Direct callers:
  - net/xdp/xsk.c:xsk_rcv
```
**Symbols:**

```
ffffffff81975250-ffffffff81975274: xdp_return_buff (STB_GLOBAL)
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
