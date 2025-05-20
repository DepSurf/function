# Function: <code>xfrm_replay_seqhi</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u32 xfrm_replay_seqhi(struct xfrm_state *x, __be32 net_seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff817bd1d0)
Location: net/xfrm/xfrm_replay.c:24
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
```
**Symbols:**

```
ffffffff817bd1d0-ffffffff817bd212: xfrm_replay_seqhi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_replay_seqhi(struct xfrm_state *x, __be32 net_seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff8182991a)
Location: net/xfrm/xfrm_replay.c:24
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff8182a310-ffffffff8182a352: xfrm_replay_seqhi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_replay_seqhi(struct xfrm_state *x, __be32 net_seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff8185b2ea)
Location: net/xfrm/xfrm_replay.c:24
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff8185bce0-ffffffff8185bd22: xfrm_replay_seqhi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_replay_seqhi(struct xfrm_state *x, __be32 net_seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff8187f737)
Location: net/xfrm/xfrm_replay.c:24
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff8187f1c0-ffffffff8187f202: xfrm_replay_seqhi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_replay_seqhi(struct xfrm_state *x, __be32 net_seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff81900867)
Location: net/xfrm/xfrm_replay.c:24
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff819002e0-ffffffff81900322: xfrm_replay_seqhi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 xfrm_replay_seqhi(struct xfrm_state *x, __be32 net_seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff81956df0)
Location: net/xfrm/xfrm_replay.c:24
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn
```
**Symbols:**

```
ffffffff81956df0-ffffffff81956e30: xfrm_replay_seqhi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 xfrm_replay_seqhi(struct xfrm_state *x, __be32 net_seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff8198ba10)
Location: net/xfrm/xfrm_replay.c:24
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn
```
**Symbols:**

```
ffffffff8198ba10-ffffffff8198ba50: xfrm_replay_seqhi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_replay_seqhi(struct xfrm_state *x, __be32 net_seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff819f7577)
Location: net/xfrm/xfrm_replay.c:12
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff819f6f60-ffffffff819f6fa0: xfrm_replay_seqhi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_replay_seqhi(struct xfrm_state *x, __be32 net_seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff81a2e1c7)
Location: net/xfrm/xfrm_replay.c:12
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81a2dbb0-ffffffff81a2dbf0: xfrm_replay_seqhi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_replay_seqhi(struct xfrm_state *x, __be32 net_seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff81b212bd)
Location: net/xfrm/xfrm_replay.c:12
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81b205e0-ffffffff81b20620: xfrm_replay_seqhi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_replay_seqhi(struct xfrm_state *x, __be32 net_seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff81b2fc4d)
Location: net/xfrm/xfrm_replay.c:12
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81b2ef20-ffffffff81b2ef60: xfrm_replay_seqhi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_replay_seqhi(struct xfrm_state *x, __be32 net_seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff81b1d7ee)
Location: net/xfrm/xfrm_replay.c:12
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81b1cce0-ffffffff81b1cd20: xfrm_replay_seqhi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_replay_seqhi(struct xfrm_state *x, __be32 net_seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff81be1ede)
Location: net/xfrm/xfrm_replay.c:12
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_recheck
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81be17d0-ffffffff81be1810: xfrm_replay_seqhi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_replay_seqhi(struct xfrm_state *x, __be32 net_seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff81d78f0e)
Location: net/xfrm/xfrm_replay.c:12
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_recheck
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81d786f0-ffffffff81d78748: xfrm_replay_seqhi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_replay_seqhi(struct xfrm_state *x, __be32 net_seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff81f4595e)
Location: net/xfrm/xfrm_replay.c:12
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_recheck
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81f44ff0-ffffffff81f45048: xfrm_replay_seqhi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_replay_seqhi(struct xfrm_state *x, __be32 net_seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff81fa517e)
Location: net/xfrm/xfrm_replay.c:12
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_recheck
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81fa4800-ffffffff81fa4858: xfrm_replay_seqhi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_replay_seqhi(struct xfrm_state *x, __be32 net_seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff820724ce)
Location: net/xfrm/xfrm_replay.c:12
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_recheck
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff82071b50-ffffffff82071ba8: xfrm_replay_seqhi (STB_GLOBAL)
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
u32 xfrm_replay_seqhi(struct xfrm_state *x, __be32 net_seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffff800010ceca10)
Location: net/xfrm/xfrm_replay.c:12
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn
```
**Symbols:**

```
ffff800010ceca10-ffff800010ceca90: xfrm_replay_seqhi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_replay_seqhi(struct xfrm_state *x, __be32 net_seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (c0df4fa4)
Location: net/xfrm/xfrm_replay.c:12
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
c0df48a4-c0df490c: xfrm_replay_seqhi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_replay_seqhi(struct xfrm_state *x, __be32 net_seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (c000000000e1160c)
Location: net/xfrm/xfrm_replay.c:12
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
c000000000e10c30-c000000000e10cb4: xfrm_replay_seqhi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 xfrm_replay_seqhi(struct xfrm_state *x, __be32 net_seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffe00083a028)
Location: net/xfrm/xfrm_replay.c:12
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn
```
**Symbols:**

```
ffffffe00083a028-ffffffe00083a0aa: xfrm_replay_seqhi (STB_GLOBAL)
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
u32 xfrm_replay_seqhi(struct xfrm_state *x, __be32 net_seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff819cd857)
Location: net/xfrm/xfrm_replay.c:12
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff819cd240-ffffffff819cd280: xfrm_replay_seqhi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_replay_seqhi(struct xfrm_state *x, __be32 net_seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff8198a647)
Location: net/xfrm/xfrm_replay.c:12
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff8198a030-ffffffff8198a070: xfrm_replay_seqhi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_replay_seqhi(struct xfrm_state *x, __be32 net_seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff81a382d7)
Location: net/xfrm/xfrm_replay.c:12
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81a37cc0-ffffffff81a37d00: xfrm_replay_seqhi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_replay_seqhi(struct xfrm_state *x, __be32 net_seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_replay.c (ffffffff81a43fc7)
Location: net/xfrm/xfrm_replay.c:12
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_recheck_esn
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81a43680-ffffffff81a436c0: xfrm_replay_seqhi (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
