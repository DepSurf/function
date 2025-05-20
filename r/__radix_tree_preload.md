# Function: <code>__radix_tree_preload</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __radix_tree_preload(gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff813ee030)
Location: lib/radix-tree.c:254
Inline: False
Direct callers:
  - lib/radix-tree.c:radix_tree_preload
  - lib/radix-tree.c:radix_tree_maybe_preload
```
**Symbols:**

```
ffffffff813ee030-ffffffff813ee0b9: __radix_tree_preload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __radix_tree_preload(gfp_t gfp_mask, int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81434170)
Location: lib/radix-tree.c:348
Inline: False
Direct callers:
  - lib/radix-tree.c:radix_tree_maybe_preload_order
  - lib/radix-tree.c:radix_tree_preload
```
**Symbols:**

```
ffffffff81434170-ffffffff81434208: __radix_tree_preload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __radix_tree_preload(gfp_t gfp_mask, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81450620)
Location: lib/radix-tree.c:380
Inline: False
Direct callers:
  - lib/radix-tree.c:radix_tree_maybe_preload_order
  - lib/radix-tree.c:radix_tree_split_preload
  - lib/radix-tree.c:radix_tree_preload
```
**Symbols:**

```
ffffffff81450620-ffffffff814506b8: __radix_tree_preload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __radix_tree_preload(gfp_t gfp_mask, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff818f0450)
Location: lib/radix-tree.c:466
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_preload
  - lib/radix-tree.c:radix_tree_maybe_preload_order
  - lib/radix-tree.c:radix_tree_split_preload
  - lib/radix-tree.c:radix_tree_preload
  - lib/radix-tree.c:radix_tree_preload
```
**Symbols:**

```
ffffffff818f0450-ffffffff818f04e8: __radix_tree_preload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __radix_tree_preload(gfp_t gfp_mask, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819768a0)
Location: lib/radix-tree.c:466
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_preload
  - lib/radix-tree.c:radix_tree_maybe_preload_order
  - lib/radix-tree.c:radix_tree_split_preload
  - lib/radix-tree.c:radix_tree_preload
  - lib/radix-tree.c:radix_tree_preload
```
**Symbols:**

```
ffffffff819768a0-ffffffff81976938: __radix_tree_preload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __radix_tree_preload(gfp_t gfp_mask, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819d3060)
Location: lib/radix-tree.c:467
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_preload
  - lib/radix-tree.c:radix_tree_maybe_preload_order
  - lib/radix-tree.c:radix_tree_split_preload
  - lib/radix-tree.c:radix_tree_preload
```
**Symbols:**

```
ffffffff819d3060-ffffffff819d30f8: __radix_tree_preload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __radix_tree_preload(gfp_t gfp_mask, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0ca50)
Location: lib/radix-tree.c:344
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_preload
  - lib/radix-tree.c:radix_tree_preload
```
**Symbols:**

```
ffffffff81a0ca50-ffffffff81a0cae8: __radix_tree_preload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __radix_tree_preload(gfp_t gfp_mask, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a7c3d0)
Location: lib/radix-tree.c:331
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_preload
  - lib/radix-tree.c:radix_tree_preload
  - lib/radix-tree.c:radix_tree_preload
```
**Symbols:**

```
ffffffff81a7c3d0-ffffffff81a7c463: __radix_tree_preload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __radix_tree_preload(gfp_t gfp_mask, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81ab3700)
Location: lib/radix-tree.c:331
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_preload
  - lib/radix-tree.c:radix_tree_preload
  - lib/radix-tree.c:radix_tree_preload
```
**Symbols:**

```
ffffffff81ab3700-ffffffff81ab3793: __radix_tree_preload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __radix_tree_preload(gfp_t gfp_mask, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815eda40)
Location: lib/radix-tree.c:323
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_preload
  - lib/radix-tree.c:radix_tree_preload
  - lib/radix-tree.c:radix_tree_preload
```
**Symbols:**

```
ffffffff815eda40-ffffffff815edad3: __radix_tree_preload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __radix_tree_preload(gfp_t gfp_mask, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81612170)
Location: lib/radix-tree.c:323
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_preload
  - lib/radix-tree.c:radix_tree_preload
  - lib/radix-tree.c:radix_tree_preload
```
**Symbols:**

```
ffffffff81612170-ffffffff81612203: __radix_tree_preload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __radix_tree_preload(gfp_t gfp_mask, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815f5860)
Location: lib/radix-tree.c:323
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_preload
  - lib/radix-tree.c:radix_tree_preload
  - lib/radix-tree.c:radix_tree_preload
```
**Symbols:**

```
ffffffff815f5860-ffffffff815f58f3: __radix_tree_preload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __radix_tree_preload(gfp_t gfp_mask, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81662cc0)
Location: lib/radix-tree.c:323
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_preload
  - lib/radix-tree.c:radix_tree_preload
  - lib/radix-tree.c:radix_tree_preload
```
**Symbols:**

```
ffffffff81662cc0-ffffffff81662d53: __radix_tree_preload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __radix_tree_preload(gfp_t gfp_mask, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff8177cbe0)
Location: lib/radix-tree.c:323
Inline: False
Direct callers:
  - lib/radix-tree.c:radix_tree_preload
  - lib/radix-tree.c:radix_tree_preload
```
**Symbols:**

```
ffffffff8177cbe0-ffffffff8177cc9b: __radix_tree_preload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __radix_tree_preload(gfp_t gfp_mask, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff820396b0)
Location: lib/radix-tree.c:323
Inline: False
Direct callers:
  - lib/radix-tree.c:radix_tree_preload
  - lib/radix-tree.c:radix_tree_preload
```
**Symbols:**

```
ffffffff820396b0-ffffffff8203976b: __radix_tree_preload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __radix_tree_preload(gfp_t gfp_mask, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff820b79d0)
Location: lib/radix-tree.c:322
Inline: False
Direct callers:
  - lib/radix-tree.c:radix_tree_preload
  - lib/radix-tree.c:radix_tree_preload
```
**Symbols:**

```
ffffffff820b79d0-ffffffff820b7a8b: __radix_tree_preload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __radix_tree_preload(gfp_t gfp_mask, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff821922e0)
Location: lib/radix-tree.c:322
Inline: False
Direct callers:
  - lib/radix-tree.c:radix_tree_preload
  - lib/radix-tree.c:radix_tree_preload
```
**Symbols:**

```
ffffffff821922e0-ffffffff8219239b: __radix_tree_preload (STB_LOCAL)
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
int __radix_tree_preload(gfp_t gfp_mask, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffff800010d8e5e0)
Location: lib/radix-tree.c:331
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_preload
  - lib/radix-tree.c:radix_tree_preload
  - lib/radix-tree.c:radix_tree_preload
```
**Symbols:**

```
ffff800010d8e5e0-ffff800010d8e6a0: __radix_tree_preload (STB_LOCAL)
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
In lib/radix-tree.c (c0e88858)
Location: lib/radix-tree.c:331
Inline: True
Direct callers:
  - lib/radix-tree.c:idr_preload
  - lib/radix-tree.c:radix_tree_preload
```
**Symbols:**

```
c0e88858-c0e888fc: __radix_tree_preload.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __radix_tree_preload(gfp_t gfp_mask, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c000000000ecf7e0)
Location: lib/radix-tree.c:331
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_preload
  - lib/radix-tree.c:radix_tree_preload
  - lib/radix-tree.c:radix_tree_preload
```
**Symbols:**

```
c000000000ecf7e0-c000000000ecf8ec: __radix_tree_preload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __radix_tree_preload(gfp_t gfp_mask, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffe0008b664e)
Location: lib/radix-tree.c:331
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_preload
  - lib/radix-tree.c:radix_tree_preload
  - lib/radix-tree.c:radix_tree_preload
```
**Symbols:**

```
ffffffe0008b664e-ffffffe0008b66fc: __radix_tree_preload (STB_LOCAL)
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
int __radix_tree_preload(gfp_t gfp_mask, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a52550)
Location: lib/radix-tree.c:331
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_preload
  - lib/radix-tree.c:radix_tree_preload
  - lib/radix-tree.c:radix_tree_preload
```
**Symbols:**

```
ffffffff81a52550-ffffffff81a525e3: __radix_tree_preload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __radix_tree_preload(gfp_t gfp_mask, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0f650)
Location: lib/radix-tree.c:331
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_preload
  - lib/radix-tree.c:radix_tree_preload
  - lib/radix-tree.c:radix_tree_preload
```
**Symbols:**

```
ffffffff81a0f650-ffffffff81a0f6e3: __radix_tree_preload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __radix_tree_preload(gfp_t gfp_mask, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81abe940)
Location: lib/radix-tree.c:331
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_preload
  - lib/radix-tree.c:radix_tree_preload
  - lib/radix-tree.c:radix_tree_preload
```
**Symbols:**

```
ffffffff81abe940-ffffffff81abe9d3: __radix_tree_preload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __radix_tree_preload(gfp_t gfp_mask, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81acade0)
Location: lib/radix-tree.c:331
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_preload
  - lib/radix-tree.c:radix_tree_preload
  - lib/radix-tree.c:radix_tree_preload
```
**Symbols:**

```
ffffffff81acade0-ffffffff81acae91: __radix_tree_preload (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int nr</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int nr</code> ➡️ <code>unsigned int nr</code>
</li>
</ul>
</details>
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
