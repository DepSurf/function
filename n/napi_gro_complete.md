# Function: <code>napi_gro_complete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int napi_gro_complete(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8171ac80)
Location: net/core/dev.c:4067
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_flush
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
```
**Symbols:**

```
ffffffff8171ac80-ffffffff8171ad18: napi_gro_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int napi_gro_complete(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81783190)
Location: net/core/dev.c:4339
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
**Symbols:**

```
ffffffff81783190-ffffffff81783228: napi_gro_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int napi_gro_complete(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817b0a30)
Location: net/core/dev.c:4360
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
**Symbols:**

```
ffffffff817b0a30-ffffffff817b0ac8: napi_gro_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int napi_gro_complete(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817d0df0)
Location: net/core/dev.c:4574
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
**Symbols:**

```
ffffffff817d0df0-ffffffff817d0e79: napi_gro_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int napi_gro_complete(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8184aee0)
Location: net/core/dev.c:4714
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
**Symbols:**

```
ffffffff8184aee0-ffffffff8184af6c: napi_gro_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int napi_gro_complete(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818952e0)
Location: net/core/dev.c:4844
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
**Symbols:**

```
ffffffff818952e0-ffffffff8189536c: napi_gro_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int napi_gro_complete(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b6eb0)
Location: net/core/dev.c:5344
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
**Symbols:**

```
ffffffff818b6eb0-ffffffff818b6f5c: napi_gro_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int napi_gro_complete(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:5354
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
**Symbols:**

```
ffffffff81902c90-ffffffff81902d5c: napi_gro_complete (STB_LOCAL)
ffffffff81907450-ffffffff81907463: napi_gro_complete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int napi_gro_complete(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819359b0)
Location: net/core/dev.c:5276
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
**Symbols:**

```
ffffffff819359b0-ffffffff81935adf: napi_gro_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81a0a690)
Location: net/core/dev.c:5659
Inline: True
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
**Symbols:**

```
ffffffff81a0a690-ffffffff81a0a7ce: napi_gro_complete.constprop.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81a0b870)
Location: net/core/dev.c:5760
Inline: True
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
**Symbols:**

```
ffffffff81a0b870-ffffffff81a0b9d2: napi_gro_complete.constprop.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff819f1dc0)
Location: net/core/dev.c:5882
Inline: True
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
**Symbols:**

```
ffffffff819f1dc0-ffffffff819f1f22: napi_gro_complete.constprop.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81aa36d0)
Location: net/core/dev.c:5852
Inline: True
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
**Symbols:**

```
ffffffff81aa36d0-ffffffff81aa3832: napi_gro_complete.constprop.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/gro.c (ffffffff81c53de0)
Location: net/core/gro.c:282
Inline: True
Direct callers:
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:napi_gro_flush
```
**Symbols:**

```
ffffffff81c53de0-ffffffff81c53f78: napi_gro_complete.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/gro.c (ffffffff81e094e0)
Location: net/core/gro.c:293
Inline: True
Direct callers:
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:napi_gro_flush
```
**Symbols:**

```
ffffffff81e094e0-ffffffff81e09678: napi_gro_complete.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/gro.c (ffffffff81e7bcb0)
Location: net/core/gro.c:236
Inline: True
Direct callers:
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:napi_gro_flush
```
**Symbols:**

```
ffffffff81e7bcb0-ffffffff81e7be48: napi_gro_complete.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/gro.c (ffffffff81f3c000)
Location: net/core/gro.c:236
Inline: True
Direct callers:
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:dev_gro_receive
  - net/core/gro.c:napi_gro_flush
```
**Symbols:**

```
ffffffff81f3c000-ffffffff81f3c198: napi_gro_complete.constprop.0 (STB_LOCAL)
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
int napi_gro_complete(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd3db8)
Location: net/core/dev.c:5276
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__napi_gro_flush_chain
```
**Symbols:**

```
ffff800010bd3db8-ffff800010bd3ef0: napi_gro_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (c0ceeb48)
Location: net/core/dev.c:5276
Inline: True
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__napi_gro_flush_chain
```
**Symbols:**

```
c0ceeb48-c0ceec7c: napi_gro_complete.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int napi_gro_complete(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cb2bd0)
Location: net/core/dev.c:5276
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:__napi_gro_flush_chain
```
**Symbols:**

```
c000000000cb2bd0-c000000000cb2d88: napi_gro_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int napi_gro_complete(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075de76)
Location: net/core/dev.c:5276
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
**Symbols:**

```
ffffffe00075de76-ffffffe00075df4a: napi_gro_complete (STB_LOCAL)
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
int napi_gro_complete(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d5980)
Location: net/core/dev.c:5276
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
**Symbols:**

```
ffffffff818d5980-ffffffff818d5aaf: napi_gro_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int napi_gro_complete(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188f7f0)
Location: net/core/dev.c:5276
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
**Symbols:**

```
ffffffff8188f7f0-ffffffff8188f91f: napi_gro_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int napi_gro_complete(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819269b0)
Location: net/core/dev.c:5276
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
**Symbols:**

```
ffffffff819269b0-ffffffff81926adf: napi_gro_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int napi_gro_complete(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81947ff0)
Location: net/core/dev.c:5276
Inline: False
Direct callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:napi_gro_flush
```
**Symbols:**

```
ffffffff81947ff0-ffffffff81948122: napi_gro_complete (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct napi_struct *napi</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb</code> ➡️ <code>napi, skb</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
