# Function: <code>flow_indr_block_cb_register</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int flow_indr_block_cb_register(struct net_device *dev, void *cb_priv, flow_indr_block_bind_cb_t *cb, void *cb_ident);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81964110)
Location: net/core/flow_offload.c:437
Inline: False
```
**Symbols:**

```
ffffffff81964110-ffffffff81964158: flow_indr_block_cb_register (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int flow_indr_block_cb_register(struct net_device *dev, void *cb_priv, flow_indr_block_bind_cb_t *cb, void *cb_ident);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffff800010c08898)
Location: net/core/flow_offload.c:437
Inline: False
```
**Symbols:**

```
ffff800010c08898-ffff800010c088f4: flow_indr_block_cb_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int flow_indr_block_cb_register(struct net_device *dev, void *cb_priv, flow_indr_block_bind_cb_t *cb, void *cb_ident);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (c0d21a50)
Location: net/core/flow_offload.c:437
Inline: False
```
**Symbols:**

```
c0d21a50-c0d21a9c: flow_indr_block_cb_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int flow_indr_block_cb_register(struct net_device *dev, void *cb_priv, flow_indr_block_bind_cb_t *cb, void *cb_ident);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (c000000000cf2fe0)
Location: net/core/flow_offload.c:437
Inline: False
```
**Symbols:**

```
c000000000cf2fe0-c000000000cf3048: flow_indr_block_cb_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int flow_indr_block_cb_register(struct net_device *dev, void *cb_priv, flow_indr_block_bind_cb_t *cb, void *cb_ident);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffe000786646)
Location: net/core/flow_offload.c:437
Inline: False
```
**Symbols:**

```
ffffffe000786646-ffffffe00078669c: flow_indr_block_cb_register (STB_GLOBAL)
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
int flow_indr_block_cb_register(struct net_device *dev, void *cb_priv, flow_indr_block_bind_cb_t *cb, void *cb_ident);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff819040e0)
Location: net/core/flow_offload.c:437
Inline: False
```
**Symbols:**

```
ffffffff819040e0-ffffffff81904128: flow_indr_block_cb_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int flow_indr_block_cb_register(struct net_device *dev, void *cb_priv, flow_indr_block_bind_cb_t *cb, void *cb_ident);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff818bdf10)
Location: net/core/flow_offload.c:437
Inline: False
```
**Symbols:**

```
ffffffff818bdf10-ffffffff818bdf58: flow_indr_block_cb_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int flow_indr_block_cb_register(struct net_device *dev, void *cb_priv, flow_indr_block_bind_cb_t *cb, void *cb_ident);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81955110)
Location: net/core/flow_offload.c:437
Inline: False
```
**Symbols:**

```
ffffffff81955110-ffffffff81955158: flow_indr_block_cb_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int flow_indr_block_cb_register(struct net_device *dev, void *cb_priv, flow_indr_block_bind_cb_t *cb, void *cb_ident);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81977190)
Location: net/core/flow_offload.c:437
Inline: False
```
**Symbols:**

```
ffffffff81977190-ffffffff819771d8: flow_indr_block_cb_register (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
