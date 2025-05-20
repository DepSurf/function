# Function: <code>__flow_indr_block_cb_unregister</code>

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
void __flow_indr_block_cb_unregister(struct net_device *dev, flow_indr_block_bind_cb_t *cb, void *cb_ident);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81963c90)
Location: net/core/flow_offload.c:451
Inline: False
Direct callers:
  - net/core/flow_offload.c:flow_indr_block_cb_unregister
```
**Symbols:**

```
ffffffff81963c90-ffffffff81963d4c: __flow_indr_block_cb_unregister (STB_GLOBAL)
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
void __flow_indr_block_cb_unregister(struct net_device *dev, flow_indr_block_bind_cb_t *cb, void *cb_ident);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffff800010c08330)
Location: net/core/flow_offload.c:451
Inline: False
Direct callers:
  - net/core/flow_offload.c:flow_indr_block_cb_unregister
```
**Symbols:**

```
ffff800010c08330-ffff800010c08420: __flow_indr_block_cb_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __flow_indr_block_cb_unregister(struct net_device *dev, flow_indr_block_bind_cb_t *cb, void *cb_ident);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (c0d21208)
Location: net/core/flow_offload.c:451
Inline: False
Direct callers:
  - net/core/flow_offload.c:flow_indr_block_cb_unregister
```
**Symbols:**

```
c0d21208-c0d2145c: __flow_indr_block_cb_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __flow_indr_block_cb_unregister(struct net_device *dev, flow_indr_block_bind_cb_t *cb, void *cb_ident);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (c000000000cf2800)
Location: net/core/flow_offload.c:451
Inline: False
Direct callers:
  - net/core/flow_offload.c:flow_indr_block_cb_unregister
```
**Symbols:**

```
c000000000cf2800-c000000000cf2958: __flow_indr_block_cb_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __flow_indr_block_cb_unregister(struct net_device *dev, flow_indr_block_bind_cb_t *cb, void *cb_ident);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffe00078669c)
Location: net/core/flow_offload.c:451
Inline: False
Direct callers:
  - net/core/flow_offload.c:flow_indr_block_cb_unregister
```
**Symbols:**

```
ffffffe00078669c-ffffffe000786746: __flow_indr_block_cb_unregister (STB_GLOBAL)
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
void __flow_indr_block_cb_unregister(struct net_device *dev, flow_indr_block_bind_cb_t *cb, void *cb_ident);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81903c60)
Location: net/core/flow_offload.c:451
Inline: False
Direct callers:
  - net/core/flow_offload.c:flow_indr_block_cb_unregister
```
**Symbols:**

```
ffffffff81903c60-ffffffff81903d1c: __flow_indr_block_cb_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __flow_indr_block_cb_unregister(struct net_device *dev, flow_indr_block_bind_cb_t *cb, void *cb_ident);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff818bda90)
Location: net/core/flow_offload.c:451
Inline: False
Direct callers:
  - net/core/flow_offload.c:flow_indr_block_cb_unregister
```
**Symbols:**

```
ffffffff818bda90-ffffffff818bdb4c: __flow_indr_block_cb_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __flow_indr_block_cb_unregister(struct net_device *dev, flow_indr_block_bind_cb_t *cb, void *cb_ident);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81954c90)
Location: net/core/flow_offload.c:451
Inline: False
Direct callers:
  - net/core/flow_offload.c:flow_indr_block_cb_unregister
```
**Symbols:**

```
ffffffff81954c90-ffffffff81954d4c: __flow_indr_block_cb_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __flow_indr_block_cb_unregister(struct net_device *dev, flow_indr_block_bind_cb_t *cb, void *cb_ident);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff819769a0)
Location: net/core/flow_offload.c:451
Inline: False
Direct callers:
  - net/core/flow_offload.c:flow_indr_block_cb_unregister
```
**Symbols:**

```
ffffffff819769a0-ffffffff81976bab: __flow_indr_block_cb_unregister (STB_GLOBAL)
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
