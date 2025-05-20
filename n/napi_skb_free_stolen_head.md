# Function: <code>napi_skb_free_stolen_head</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
void napi_skb_free_stolen_head(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817cc8e0)
Location: net/core/dev.c:4847
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
```
**Symbols:**

```
ffffffff817cc8e0-ffffffff817cc93e: napi_skb_free_stolen_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void napi_skb_free_stolen_head(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81846250)
Location: net/core/dev.c:4988
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
```
**Symbols:**

```
ffffffff81846250-ffffffff818462b4: napi_skb_free_stolen_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void napi_skb_free_stolen_head(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188db30)
Location: net/core/dev.c:5118
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
```
**Symbols:**

```
ffffffff8188db30-ffffffff8188db9c: napi_skb_free_stolen_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void napi_skb_free_stolen_head(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ae9c0)
Location: net/core/dev.c:5654
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
```
**Symbols:**

```
ffffffff818ae9c0-ffffffff818aea1e: napi_skb_free_stolen_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void napi_skb_free_stolen_head(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818fa2b0)
Location: net/core/dev.c:5664
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
```
**Symbols:**

```
ffffffff818fa2b0-ffffffff818fa30b: napi_skb_free_stolen_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void napi_skb_free_stolen_head(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192c3f0)
Location: net/core/dev.c:5587
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
```
**Symbols:**

```
ffffffff8192c3f0-ffffffff8192c44b: napi_skb_free_stolen_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void napi_skb_free_stolen_head(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a00e50)
Location: net/core/dev.c:5969
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
```
**Symbols:**

```
ffffffff81a00e50-ffffffff81a00eb5: napi_skb_free_stolen_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void napi_skb_free_stolen_head(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a01260)
Location: net/core/dev.c:6070
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
```
**Symbols:**

```
ffffffff81a01260-ffffffff81a012c5: napi_skb_free_stolen_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void napi_skb_free_stolen_head(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d8450)
Location: net/core/skbuff.c:940
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
```
**Symbols:**

```
ffffffff819d8450-ffffffff819d8507: napi_skb_free_stolen_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void napi_skb_free_stolen_head(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a882a0)
Location: net/core/skbuff.c:956
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
```
**Symbols:**

```
ffffffff81a882a0-ffffffff81a88398: napi_skb_free_stolen_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void napi_skb_free_stolen_head(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bfd8f0)
Location: net/core/skbuff.c:961
Inline: False
Direct callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_receive
```
**Symbols:**

```
ffffffff81bfd8f0-ffffffff81bfda16: napi_skb_free_stolen_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void napi_skb_free_stolen_head(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81dae620)
Location: net/core/skbuff.c:1142
Inline: False
Direct callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_receive
```
**Symbols:**

```
ffffffff81dae620-ffffffff81dae746: napi_skb_free_stolen_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void napi_skb_free_stolen_head(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e1e4c0)
Location: net/core/skbuff.c:1282
Inline: False
Direct callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_receive
```
**Symbols:**

```
ffffffff81e1e4c0-ffffffff81e1e640: napi_skb_free_stolen_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void napi_skb_free_stolen_head(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81edbbc0)
Location: net/core/skbuff.c:1370
Inline: False
Direct callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_receive
```
**Symbols:**

```
ffffffff81edbbc0-ffffffff81edbc95: napi_skb_free_stolen_head (STB_GLOBAL)
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
void napi_skb_free_stolen_head(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bc89f0)
Location: net/core/dev.c:5587
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
```
**Symbols:**

```
ffff800010bc89f0-ffff800010bc8a6c: napi_skb_free_stolen_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void napi_skb_free_stolen_head(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce4aec)
Location: net/core/dev.c:5587
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
```
**Symbols:**

```
c0ce4aec-c0ce4b5c: napi_skb_free_stolen_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void napi_skb_free_stolen_head(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca5160)
Location: net/core/dev.c:5587
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
```
**Symbols:**

```
c000000000ca5160-c000000000ca5228: napi_skb_free_stolen_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void napi_skb_free_stolen_head(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe0007551f2)
Location: net/core/dev.c:5587
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
```
**Symbols:**

```
ffffffe0007551f2-ffffffe000755250: napi_skb_free_stolen_head (STB_LOCAL)
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
void napi_skb_free_stolen_head(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818cc3f0)
Location: net/core/dev.c:5587
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
```
**Symbols:**

```
ffffffff818cc3f0-ffffffff818cc44b: napi_skb_free_stolen_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void napi_skb_free_stolen_head(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81886480)
Location: net/core/dev.c:5587
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
```
**Symbols:**

```
ffffffff81886480-ffffffff818864db: napi_skb_free_stolen_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void napi_skb_free_stolen_head(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191d3f0)
Location: net/core/dev.c:5587
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
```
**Symbols:**

```
ffffffff8191d3f0-ffffffff8191d44b: napi_skb_free_stolen_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void napi_skb_free_stolen_head(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193e910)
Location: net/core/dev.c:5587
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
```
**Symbols:**

```
ffffffff8193e910-ffffffff8193e96b: napi_skb_free_stolen_head (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
