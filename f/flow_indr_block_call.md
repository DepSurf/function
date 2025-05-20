# Function: <code>flow_indr_block_call</code>

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
void flow_indr_block_call(struct net_device *dev, struct flow_block_offload *bo, enum flow_block_command command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81963a90)
Location: net/core/flow_offload.c:484
Inline: False
```
**Symbols:**

```
ffffffff81963a90-ffffffff81963ae6: flow_indr_block_call (STB_GLOBAL)
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
void flow_indr_block_call(struct net_device *dev, struct flow_block_offload *bo, enum flow_block_command command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffff800010c08010)
Location: net/core/flow_offload.c:484
Inline: False
```
**Symbols:**

```
ffff800010c08010-ffff800010c08080: flow_indr_block_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void flow_indr_block_call(struct net_device *dev, struct flow_block_offload *bo, enum flow_block_command command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (c0d20d18)
Location: net/core/flow_offload.c:484
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_indr_block_call
```
**Symbols:**

```
c0d20d18-c0d20eec: flow_indr_block_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void flow_indr_block_call(struct net_device *dev, struct flow_block_offload *bo, enum flow_block_command command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (c000000000cf2450)
Location: net/core/flow_offload.c:484
Inline: False
```
**Symbols:**

```
c000000000cf2450-c000000000cf24fc: flow_indr_block_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void flow_indr_block_call(struct net_device *dev, struct flow_block_offload *bo, enum flow_block_command command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffe0007860a2)
Location: net/core/flow_offload.c:484
Inline: False
```
**Symbols:**

```
ffffffe0007860a2-ffffffe0007860f8: flow_indr_block_call (STB_GLOBAL)
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
void flow_indr_block_call(struct net_device *dev, struct flow_block_offload *bo, enum flow_block_command command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81903a60)
Location: net/core/flow_offload.c:484
Inline: False
```
**Symbols:**

```
ffffffff81903a60-ffffffff81903ab6: flow_indr_block_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void flow_indr_block_call(struct net_device *dev, struct flow_block_offload *bo, enum flow_block_command command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff818bd890)
Location: net/core/flow_offload.c:484
Inline: False
```
**Symbols:**

```
ffffffff818bd890-ffffffff818bd8e6: flow_indr_block_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void flow_indr_block_call(struct net_device *dev, struct flow_block_offload *bo, enum flow_block_command command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81954a90)
Location: net/core/flow_offload.c:484
Inline: False
```
**Symbols:**

```
ffffffff81954a90-ffffffff81954ae6: flow_indr_block_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void flow_indr_block_call(struct net_device *dev, struct flow_block_offload *bo, enum flow_block_command command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff819765e0)
Location: net/core/flow_offload.c:484
Inline: False
```
**Symbols:**

```
ffffffff819765e0-ffffffff81976790: flow_indr_block_call (STB_GLOBAL)
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
