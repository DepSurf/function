# Function: <code>__flow_indr_block_cb_register</code>

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
int __flow_indr_block_cb_register(struct net_device *dev, void *cb_priv, flow_indr_block_bind_cb_t *cb, void *cb_ident);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81963d90)
Location: net/core/flow_offload.c:409
Inline: False
Direct callers:
  - net/core/flow_offload.c:flow_indr_block_cb_register
```
**Symbols:**

```
ffffffff81963d90-ffffffff8196410c: __flow_indr_block_cb_register (STB_GLOBAL)
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
int __flow_indr_block_cb_register(struct net_device *dev, void *cb_priv, flow_indr_block_bind_cb_t *cb, void *cb_ident);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffff800010c08470)
Location: net/core/flow_offload.c:409
Inline: False
Direct callers:
  - net/core/flow_offload.c:flow_indr_block_cb_register
```
**Symbols:**

```
ffff800010c08470-ffff800010c08894: __flow_indr_block_cb_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __flow_indr_block_cb_register(struct net_device *dev, void *cb_priv, flow_indr_block_bind_cb_t *cb, void *cb_ident);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (c0d21498)
Location: net/core/flow_offload.c:409
Inline: False
Direct callers:
  - net/core/flow_offload.c:flow_indr_block_cb_register
```
**Symbols:**

```
c0d21498-c0d21a50: __flow_indr_block_cb_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __flow_indr_block_cb_register(struct net_device *dev, void *cb_priv, flow_indr_block_bind_cb_t *cb, void *cb_ident);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (c000000000cf2a80)
Location: net/core/flow_offload.c:409
Inline: False
Direct callers:
  - net/core/flow_offload.c:flow_indr_block_cb_register
```
**Symbols:**

```
c000000000cf2a80-c000000000cf2fe0: __flow_indr_block_cb_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __flow_indr_block_cb_register(struct net_device *dev, void *cb_priv, flow_indr_block_bind_cb_t *cb, void *cb_ident);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffe000786304)
Location: net/core/flow_offload.c:409
Inline: False
Direct callers:
  - net/core/flow_offload.c:flow_indr_block_cb_register
```
**Symbols:**

```
ffffffe000786304-ffffffe000786646: __flow_indr_block_cb_register (STB_GLOBAL)
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
int __flow_indr_block_cb_register(struct net_device *dev, void *cb_priv, flow_indr_block_bind_cb_t *cb, void *cb_ident);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81903d60)
Location: net/core/flow_offload.c:409
Inline: False
Direct callers:
  - net/core/flow_offload.c:flow_indr_block_cb_register
```
**Symbols:**

```
ffffffff81903d60-ffffffff819040dc: __flow_indr_block_cb_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __flow_indr_block_cb_register(struct net_device *dev, void *cb_priv, flow_indr_block_bind_cb_t *cb, void *cb_ident);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff818bdb90)
Location: net/core/flow_offload.c:409
Inline: False
Direct callers:
  - net/core/flow_offload.c:flow_indr_block_cb_register
```
**Symbols:**

```
ffffffff818bdb90-ffffffff818bdf0c: __flow_indr_block_cb_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __flow_indr_block_cb_register(struct net_device *dev, void *cb_priv, flow_indr_block_bind_cb_t *cb, void *cb_ident);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81954d90)
Location: net/core/flow_offload.c:409
Inline: False
Direct callers:
  - net/core/flow_offload.c:flow_indr_block_cb_register
```
**Symbols:**

```
ffffffff81954d90-ffffffff8195510c: __flow_indr_block_cb_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __flow_indr_block_cb_register(struct net_device *dev, void *cb_priv, flow_indr_block_bind_cb_t *cb, void *cb_ident);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81976bf0)
Location: net/core/flow_offload.c:409
Inline: False
Direct callers:
  - net/core/flow_offload.c:flow_indr_block_cb_register
```
**Symbols:**

```
ffffffff81976bf0-ffffffff8197718d: __flow_indr_block_cb_register (STB_GLOBAL)
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
