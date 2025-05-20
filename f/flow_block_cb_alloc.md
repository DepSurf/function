# Function: <code>flow_block_cb_alloc</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct flow_block_cb *flow_block_cb_alloc(flow_setup_cb_t *cb, void *cb_ident, void *cb_priv, void (*release)(void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81931525)
Location: net/core/flow_offload.c:168
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_block_cb_setup_simple
```
**Symbols:**

```
ffffffff819313b0-ffffffff81931409: flow_block_cb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct flow_block_cb *flow_block_cb_alloc(flow_setup_cb_t *cb, void *cb_ident, void *cb_priv, void (*release)(void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81963715)
Location: net/core/flow_offload.c:170
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_block_cb_setup_simple
```
**Symbols:**

```
ffffffff819635a0-ffffffff819635f9: flow_block_cb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct flow_block_cb *flow_block_cb_alloc(flow_setup_cb_t *cb, void *cb_ident, void *cb_priv, void (*release)(void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81a36e95)
Location: net/core/flow_offload.c:205
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_cb_alloc
Direct callers:
  - net/core/flow_offload.c:flow_block_cb_setup_simple
```
**Symbols:**

```
ffffffff81a36e30-ffffffff81a36e90: flow_block_cb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct flow_block_cb *flow_block_cb_alloc(flow_setup_cb_t *cb, void *cb_ident, void *cb_priv, void (*release)(void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81a39267)
Location: net/core/flow_offload.c:205
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_cb_alloc
  - net/core/flow_offload.c:flow_block_cb_setup_simple
```
**Symbols:**

```
ffffffff81a391e0-ffffffff81a39240: flow_block_cb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct flow_block_cb *flow_block_cb_alloc(flow_setup_cb_t *cb, void *cb_ident, void *cb_priv, void (*release)(void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81a20517)
Location: net/core/flow_offload.c:205
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_cb_alloc
  - net/core/flow_offload.c:flow_block_cb_setup_simple
```
**Symbols:**

```
ffffffff81a20490-ffffffff81a204f0: flow_block_cb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct flow_block_cb *flow_block_cb_alloc(flow_setup_cb_t *cb, void *cb_ident, void *cb_priv, void (*release)(void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81ad4957)
Location: net/core/flow_offload.c:205
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_cb_alloc
  - net/core/flow_offload.c:flow_block_cb_setup_simple
```
**Symbols:**

```
ffffffff81ad4700-ffffffff81ad4760: flow_block_cb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct flow_block_cb *flow_block_cb_alloc(flow_setup_cb_t *cb, void *cb_ident, void *cb_priv, void (*release)(void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81c52cfb)
Location: net/core/flow_offload.c:226
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_cb_alloc
  - net/core/flow_offload.c:flow_block_cb_setup_simple
```
**Symbols:**

```
ffffffff81c52c60-ffffffff81c52cc5: flow_block_cb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct flow_block_cb *flow_block_cb_alloc(flow_setup_cb_t *cb, void *cb_ident, void *cb_priv, void (*release)(void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81e082db)
Location: net/core/flow_offload.c:254
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_cb_alloc
  - net/core/flow_offload.c:flow_block_cb_setup_simple
```
**Symbols:**

```
ffffffff81e08230-ffffffff81e08295: flow_block_cb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct flow_block_cb *flow_block_cb_alloc(flow_setup_cb_t *cb, void *cb_ident, void *cb_priv, void (*release)(void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81e7abfb)
Location: net/core/flow_offload.c:254
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_cb_alloc
  - net/core/flow_offload.c:flow_block_cb_setup_simple
```
**Symbols:**

```
ffffffff81e7ab50-ffffffff81e7abb5: flow_block_cb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct flow_block_cb *flow_block_cb_alloc(flow_setup_cb_t *cb, void *cb_ident, void *cb_priv, void (*release)(void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81f3ae00)
Location: net/core/flow_offload.c:261
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_block_cb_alloc
  - net/core/flow_offload.c:flow_block_cb_setup_simple
```
**Symbols:**

```
ffffffff81f3ad20-ffffffff81f3adb4: flow_block_cb_alloc (STB_GLOBAL)
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
struct flow_block_cb *flow_block_cb_alloc(flow_setup_cb_t *cb, void *cb_ident, void *cb_priv, void (*release)(void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffff800010c07c5c)
Location: net/core/flow_offload.c:170
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_block_cb_setup_simple
```
**Symbols:**

```
ffff800010c07a50-ffff800010c07ab0: flow_block_cb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct flow_block_cb *flow_block_cb_alloc(flow_setup_cb_t *cb, void *cb_ident, void *cb_priv, void (*release)(void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (c0d20b1c)
Location: net/core/flow_offload.c:170
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_block_cb_setup_simple
```
**Symbols:**

```
c0d20960-c0d209b8: flow_block_cb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct flow_block_cb *flow_block_cb_alloc(flow_setup_cb_t *cb, void *cb_ident, void *cb_priv, void (*release)(void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (c000000000cf31f0)
Location: net/core/flow_offload.c:170
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_block_cb_setup_simple
```
**Symbols:**

```
c000000000cf29c0-c000000000cf2a74: flow_block_cb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct flow_block_cb *flow_block_cb_alloc(flow_setup_cb_t *cb, void *cb_ident, void *cb_priv, void (*release)(void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffe000785d5a)
Location: net/core/flow_offload.c:170
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_block_cb_setup_simple
```
**Symbols:**

```
ffffffe000785bea-ffffffe000785c4a: flow_block_cb_alloc (STB_GLOBAL)
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
struct flow_block_cb *flow_block_cb_alloc(flow_setup_cb_t *cb, void *cb_ident, void *cb_priv, void (*release)(void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff819036e5)
Location: net/core/flow_offload.c:170
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_block_cb_setup_simple
```
**Symbols:**

```
ffffffff81903570-ffffffff819035c9: flow_block_cb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct flow_block_cb *flow_block_cb_alloc(flow_setup_cb_t *cb, void *cb_ident, void *cb_priv, void (*release)(void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff818bd515)
Location: net/core/flow_offload.c:170
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_block_cb_setup_simple
```
**Symbols:**

```
ffffffff818bd3a0-ffffffff818bd3f9: flow_block_cb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct flow_block_cb *flow_block_cb_alloc(flow_setup_cb_t *cb, void *cb_ident, void *cb_priv, void (*release)(void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81954715)
Location: net/core/flow_offload.c:170
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_block_cb_setup_simple
```
**Symbols:**

```
ffffffff819545a0-ffffffff819545f9: flow_block_cb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct flow_block_cb *flow_block_cb_alloc(flow_setup_cb_t *cb, void *cb_ident, void *cb_priv, void (*release)(void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff819763c5)
Location: net/core/flow_offload.c:170
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_block_cb_setup_simple
```
**Symbols:**

```
ffffffff81976250-ffffffff819762a9: flow_block_cb_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
