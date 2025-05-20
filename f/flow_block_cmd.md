# Function: <code>flow_block_cmd</code>

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
void flow_block_cmd(struct net_device *dev, flow_indr_block_bind_cb_t *cb, void *cb_priv, enum flow_block_command command);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff819637e0)
Location: net/core/flow_offload.c:396
Inline: False
Direct callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_unregister
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
**Symbols:**

```
ffffffff819637e0-ffffffff81963858: flow_block_cmd (STB_LOCAL)
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
void flow_block_cmd(struct net_device *dev, flow_indr_block_bind_cb_t *cb, void *cb_priv, enum flow_block_command command);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffff800010c07cf0)
Location: net/core/flow_offload.c:396
Inline: False
Direct callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_unregister
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
**Symbols:**

```
ffff800010c07cf0-ffff800010c07d90: flow_block_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void flow_block_cmd(struct net_device *dev, flow_indr_block_bind_cb_t *cb, void *cb_priv, enum flow_block_command command);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (c0d20ba4)
Location: net/core/flow_offload.c:396
Inline: False
Direct callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_unregister
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
**Symbols:**

```
c0d20ba4-c0d20c24: flow_block_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void flow_block_cmd(struct net_device *dev, flow_indr_block_bind_cb_t *cb, void *cb_priv, enum flow_block_command command);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (c000000000cf1ff0)
Location: net/core/flow_offload.c:396
Inline: False
Direct callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_unregister
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
**Symbols:**

```
c000000000cf1ff0-c000000000cf20d8: flow_block_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void flow_block_cmd(struct net_device *dev, flow_indr_block_bind_cb_t *cb, void *cb_priv, enum flow_block_command command);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffe000785dc2)
Location: net/core/flow_offload.c:396
Inline: False
Direct callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_unregister
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
**Symbols:**

```
ffffffe000785dc2-ffffffe000785e46: flow_block_cmd (STB_LOCAL)
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
void flow_block_cmd(struct net_device *dev, flow_indr_block_bind_cb_t *cb, void *cb_priv, enum flow_block_command command);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff819037b0)
Location: net/core/flow_offload.c:396
Inline: False
Direct callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_unregister
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
**Symbols:**

```
ffffffff819037b0-ffffffff81903828: flow_block_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void flow_block_cmd(struct net_device *dev, flow_indr_block_bind_cb_t *cb, void *cb_priv, enum flow_block_command command);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff818bd5e0)
Location: net/core/flow_offload.c:396
Inline: False
Direct callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_unregister
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
**Symbols:**

```
ffffffff818bd5e0-ffffffff818bd658: flow_block_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void flow_block_cmd(struct net_device *dev, flow_indr_block_bind_cb_t *cb, void *cb_priv, enum flow_block_command command);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff819547e0)
Location: net/core/flow_offload.c:396
Inline: False
Direct callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_unregister
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
**Symbols:**

```
ffffffff819547e0-ffffffff81954858: flow_block_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void flow_block_cmd(struct net_device *dev, flow_indr_block_bind_cb_t *cb, void *cb_priv, enum flow_block_command command);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81976490)
Location: net/core/flow_offload.c:396
Inline: False
Direct callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_unregister
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
**Symbols:**

```
ffffffff81976490-ffffffff81976508: flow_block_cmd (STB_LOCAL)
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
