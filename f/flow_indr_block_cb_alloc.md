# Function: <code>flow_indr_block_cb_alloc</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct flow_block_cb *flow_indr_block_cb_alloc(flow_setup_cb_t *cb, void *cb_ident, void *cb_priv, void (*release)(void *), struct flow_block_offload *bo, struct net_device *dev, void *data, void *indr_cb_priv, void (*cleanup)(struct flow_block_cb *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81a36e90)
Location: net/core/flow_offload.c:444
Inline: False
```
**Symbols:**

```
ffffffff81a36e90-ffffffff81a36f5a: flow_indr_block_cb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct flow_block_cb *flow_indr_block_cb_alloc(flow_setup_cb_t *cb, void *cb_ident, void *cb_priv, void (*release)(void *), struct flow_block_offload *bo, struct net_device *dev, struct Qdisc *sch, void *data, void *indr_cb_priv, void (*cleanup)(struct flow_block_cb *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81a39240)
Location: net/core/flow_offload.c:443
Inline: False
```
**Symbols:**

```
ffffffff81a39240-ffffffff81a39312: flow_indr_block_cb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct flow_block_cb *flow_indr_block_cb_alloc(flow_setup_cb_t *cb, void *cb_ident, void *cb_priv, void (*release)(void *), struct flow_block_offload *bo, struct net_device *dev, struct Qdisc *sch, void *data, void *indr_cb_priv, void (*cleanup)(struct flow_block_cb *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81a204f0)
Location: net/core/flow_offload.c:443
Inline: False
```
**Symbols:**

```
ffffffff81a204f0-ffffffff81a205c2: flow_indr_block_cb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct flow_block_cb *flow_indr_block_cb_alloc(flow_setup_cb_t *cb, void *cb_ident, void *cb_priv, void (*release)(void *), struct flow_block_offload *bo, struct net_device *dev, struct Qdisc *sch, void *data, void *indr_cb_priv, void (*cleanup)(struct flow_block_cb *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81ad4930)
Location: net/core/flow_offload.c:471
Inline: False
```
**Symbols:**

```
ffffffff81ad4930-ffffffff81ad4a02: flow_indr_block_cb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct flow_block_cb *flow_indr_block_cb_alloc(flow_setup_cb_t *cb, void *cb_ident, void *cb_priv, void (*release)(void *), struct flow_block_offload *bo, struct net_device *dev, struct Qdisc *sch, void *data, void *indr_cb_priv, void (*cleanup)(struct flow_block_cb *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81c52cd0)
Location: net/core/flow_offload.c:495
Inline: False
```
**Symbols:**

```
ffffffff81c52cd0-ffffffff81c52dab: flow_indr_block_cb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct flow_block_cb *flow_indr_block_cb_alloc(flow_setup_cb_t *cb, void *cb_ident, void *cb_priv, void (*release)(void *), struct flow_block_offload *bo, struct net_device *dev, struct Qdisc *sch, void *data, void *indr_cb_priv, void (*cleanup)(struct flow_block_cb *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81e082b0)
Location: net/core/flow_offload.c:523
Inline: False
```
**Symbols:**

```
ffffffff81e082b0-ffffffff81e0838b: flow_indr_block_cb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct flow_block_cb *flow_indr_block_cb_alloc(flow_setup_cb_t *cb, void *cb_ident, void *cb_priv, void (*release)(void *), struct flow_block_offload *bo, struct net_device *dev, struct Qdisc *sch, void *data, void *indr_cb_priv, void (*cleanup)(struct flow_block_cb *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81e7abd0)
Location: net/core/flow_offload.c:523
Inline: False
```
**Symbols:**

```
ffffffff81e7abd0-ffffffff81e7acab: flow_indr_block_cb_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct flow_block_cb *flow_indr_block_cb_alloc(flow_setup_cb_t *cb, void *cb_ident, void *cb_priv, void (*release)(void *), struct flow_block_offload *bo, struct net_device *dev, struct Qdisc *sch, void *data, void *indr_cb_priv, void (*cleanup)(struct flow_block_cb *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81f3add0)
Location: net/core/flow_offload.c:530
Inline: False
```
**Symbols:**

```
ffffffff81f3add0-ffffffff81f3aeda: flow_indr_block_cb_alloc (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct Qdisc *sch</code>
</li>
<li>
<b>Param reordered. </b>
<code>cb, cb_ident, cb_priv, release, bo, dev, data, indr_cb_priv, cleanup</code> ➡️ <code>cb, cb_ident, cb_priv, release, bo, dev, sch, data, indr_cb_priv, cleanup</code>
</li>
</ul>
</details>
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
