# Function: <code>flow_indr_block_cb_unregister</code>

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
void flow_indr_block_cb_unregister(struct net_device *dev, flow_indr_block_bind_cb_t *cb, void *cb_ident);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81963d50)
Location: net/core/flow_offload.c:474
Inline: False
```
**Symbols:**

```
ffffffff81963d50-ffffffff81963d88: flow_indr_block_cb_unregister (STB_GLOBAL)
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
void flow_indr_block_cb_unregister(struct net_device *dev, flow_indr_block_bind_cb_t *cb, void *cb_ident);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffff800010c08420)
Location: net/core/flow_offload.c:474
Inline: False
```
**Symbols:**

```
ffff800010c08420-ffff800010c0846c: flow_indr_block_cb_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void flow_indr_block_cb_unregister(struct net_device *dev, flow_indr_block_bind_cb_t *cb, void *cb_ident);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (c0d2145c)
Location: net/core/flow_offload.c:474
Inline: False
```
**Symbols:**

```
c0d2145c-c0d21498: flow_indr_block_cb_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void flow_indr_block_cb_unregister(struct net_device *dev, flow_indr_block_bind_cb_t *cb, void *cb_ident);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (c000000000cf2960)
Location: net/core/flow_offload.c:474
Inline: False
```
**Symbols:**

```
c000000000cf2960-c000000000cf29b8: flow_indr_block_cb_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void flow_indr_block_cb_unregister(struct net_device *dev, flow_indr_block_bind_cb_t *cb, void *cb_ident);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffe000786746)
Location: net/core/flow_offload.c:474
Inline: False
```
**Symbols:**

```
ffffffe000786746-ffffffe000786790: flow_indr_block_cb_unregister (STB_GLOBAL)
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
void flow_indr_block_cb_unregister(struct net_device *dev, flow_indr_block_bind_cb_t *cb, void *cb_ident);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81903d20)
Location: net/core/flow_offload.c:474
Inline: False
```
**Symbols:**

```
ffffffff81903d20-ffffffff81903d58: flow_indr_block_cb_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void flow_indr_block_cb_unregister(struct net_device *dev, flow_indr_block_bind_cb_t *cb, void *cb_ident);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff818bdb50)
Location: net/core/flow_offload.c:474
Inline: False
```
**Symbols:**

```
ffffffff818bdb50-ffffffff818bdb88: flow_indr_block_cb_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void flow_indr_block_cb_unregister(struct net_device *dev, flow_indr_block_bind_cb_t *cb, void *cb_ident);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81954d50)
Location: net/core/flow_offload.c:474
Inline: False
```
**Symbols:**

```
ffffffff81954d50-ffffffff81954d88: flow_indr_block_cb_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void flow_indr_block_cb_unregister(struct net_device *dev, flow_indr_block_bind_cb_t *cb, void *cb_ident);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81976bb0)
Location: net/core/flow_offload.c:474
Inline: False
```
**Symbols:**

```
ffffffff81976bb0-ffffffff81976be8: flow_indr_block_cb_unregister (STB_GLOBAL)
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
