# Function: <code>napi_reuse_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81716f50)
Location: net/core/dev.c:4372
Inline: True
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
```
**Symbols:**

```
ffffffff81716f50-ffffffff81716ff3: napi_reuse_skb.isra.82 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff8177ef60)
Location: net/core/dev.c:4648
Inline: True
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
```
**Symbols:**

```
ffffffff8177ef60-ffffffff8177f003: napi_reuse_skb.isra.87 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff817ac740)
Location: net/core/dev.c:4671
Inline: True
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
```
**Symbols:**

```
ffffffff817ac740-ffffffff817ac7e3: napi_reuse_skb.isra.92 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff817cae80)
Location: net/core/dev.c:4893
Inline: True
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
```
**Symbols:**

```
ffffffff817cae80-ffffffff817caf61: napi_reuse_skb.isra.96 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81844710)
Location: net/core/dev.c:5034
Inline: True
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
```
**Symbols:**

```
ffffffff81844710-ffffffff818447f7: napi_reuse_skb.isra.101 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff8188f750)
Location: net/core/dev.c:5164
Inline: True
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
```
**Symbols:**

```
ffffffff8188f750-ffffffff8188f837: napi_reuse_skb.isra.116 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff818af490)
Location: net/core/dev.c:5705
Inline: True
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
```
**Symbols:**

```
ffffffff818af490-ffffffff818af547: napi_reuse_skb.isra.123 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff818fb2d0)
Location: net/core/dev.c:5715
Inline: True
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
```
**Symbols:**

```
ffffffff818fb2d0-ffffffff818fb3a1: napi_reuse_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff8192d420)
Location: net/core/dev.c:5638
Inline: True
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
```
**Symbols:**

```
ffffffff8192d420-ffffffff8192d505: napi_reuse_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void napi_reuse_skb(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a01270)
Location: net/core/dev.c:6021
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_frags_skb
```
**Symbols:**

```
ffffffff81a01270-ffffffff81a01346: napi_reuse_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void napi_reuse_skb(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a01a60)
Location: net/core/dev.c:6122
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_frags_skb
```
**Symbols:**

```
ffffffff81a01a60-ffffffff81a01b36: napi_reuse_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void napi_reuse_skb(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e8a10)
Location: net/core/dev.c:6241
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
```
**Symbols:**

```
ffffffff819e8a10-ffffffff819e8b06: napi_reuse_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void napi_reuse_skb(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a961b0)
Location: net/core/dev.c:6223
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
```
**Symbols:**

```
ffffffff81a961b0-ffffffff81a962ea: napi_reuse_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void napi_reuse_skb(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gro.c (ffffffff81c53740)
Location: net/core/gro.c:645
Inline: False
Direct callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_frags
```
**Symbols:**

```
ffffffff81c53740-ffffffff81c53885: napi_reuse_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void napi_reuse_skb(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gro.c (ffffffff81e08e00)
Location: net/core/gro.c:662
Inline: False
Direct callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_frags
```
**Symbols:**

```
ffffffff81e08e00-ffffffff81e08f5c: napi_reuse_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void napi_reuse_skb(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gro.c (ffffffff81e7b520)
Location: net/core/gro.c:616
Inline: False
Direct callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_frags
```
**Symbols:**

```
ffffffff81e7b520-ffffffff81e7b67d: napi_reuse_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void napi_reuse_skb(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gro.c (ffffffff81f3b7b0)
Location: net/core/gro.c:616
Inline: False
Direct callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_frags
```
**Symbols:**

```
ffffffff81f3b7b0-ffffffff81f3b90d: napi_reuse_skb (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffff800010bc94d0)
Location: net/core/dev.c:5638
Inline: True
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
```
**Symbols:**

```
ffff800010bc94d0-ffff800010bc95ac: napi_reuse_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void napi_reuse_skb(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce4b5c)
Location: net/core/dev.c:5638
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
```
**Symbols:**

```
c0ce4b5c-c0ce4c30: napi_reuse_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (c000000000cab270)
Location: net/core/dev.c:5638
Inline: True
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
```
**Symbols:**

```
c000000000cab270-c000000000cab398: napi_reuse_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffe000756170)
Location: net/core/dev.c:5638
Inline: True
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
```
**Symbols:**

```
ffffffe000756170-ffffffe00075623a: napi_reuse_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff818cd420)
Location: net/core/dev.c:5638
Inline: True
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
```
**Symbols:**

```
ffffffff818cd420-ffffffff818cd505: napi_reuse_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81887540)
Location: net/core/dev.c:5638
Inline: True
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
```
**Symbols:**

```
ffffffff81887540-ffffffff81887625: napi_reuse_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff8191e420)
Location: net/core/dev.c:5638
Inline: True
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
```
**Symbols:**

```
ffffffff8191e420-ffffffff8191e505: napi_reuse_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff8193fab0)
Location: net/core/dev.c:5638
Inline: True
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
```
**Symbols:**

```
ffffffff8193fab0-ffffffff8193fb95: napi_reuse_skb.isra.0 (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
