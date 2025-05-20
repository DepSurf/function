# Function: <code>trace_event_raw_event_xdp_redirect_template</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void trace_event_raw_event_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, int to_ifindex, int err, const struct bpf_map *map, u32 map_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8119c900)
Location: include/trace/events/xdp.h:53
Inline: False
```
**Symbols:**

```
ffffffff8119c900-ffffffff8119ca14: trace_event_raw_event_xdp_redirect_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void trace_event_raw_event_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, int to_ifindex, int err, const struct bpf_map *map, u32 map_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811b0b90)
Location: include/trace/events/xdp.h:53
Inline: False
```
**Symbols:**

```
ffffffff811b0b90-ffffffff811b0c91: trace_event_raw_event_xdp_redirect_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void trace_event_raw_event_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, int to_ifindex, int err, const struct bpf_map *map, u32 map_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811bf210)
Location: include/trace/events/xdp.h:53
Inline: False
```
**Symbols:**

```
ffffffff811bf210-ffffffff811bf311: trace_event_raw_event_xdp_redirect_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void trace_event_raw_event_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, int to_ifindex, int err, const struct bpf_map *map, u32 map_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811cf4e0)
Location: include/trace/events/xdp.h:82
Inline: False
```
**Symbols:**

```
ffffffff811cf4e0-ffffffff811cf5e7: trace_event_raw_event_xdp_redirect_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void trace_event_raw_event_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, int to_ifindex, int err, const struct bpf_map *map, u32 map_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811dbae0)
Location: include/trace/events/xdp.h:82
Inline: False
```
**Symbols:**

```
ffffffff811dbae0-ffffffff811dbbe7: trace_event_raw_event_xdp_redirect_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void trace_event_raw_event_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, const void *tgt, int err, const struct bpf_map *map, u32 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f86a0)
Location: include/trace/events/xdp.h:94
Inline: False
```
**Symbols:**

```
ffffffff811f86a0-ffffffff811f87bd: trace_event_raw_event_xdp_redirect_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void trace_event_raw_event_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, const void *tgt, int err, const struct bpf_map *map, u32 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f7690)
Location: include/trace/events/xdp.h:94
Inline: False
```
**Symbols:**

```
ffffffff811f7690-ffffffff811f77ad: trace_event_raw_event_xdp_redirect_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void trace_event_raw_event_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, const void *tgt, int err, enum bpf_map_type map_type, u32 map_id, u32 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f84e0)
Location: include/trace/events/xdp.h:89
Inline: False
```
**Symbols:**

```
ffffffff811f84e0-ffffffff811f861e: trace_event_raw_event_xdp_redirect_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void trace_event_raw_event_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, const void *tgt, int err, enum bpf_map_type map_type, u32 map_id, u32 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81229ac0)
Location: include/trace/events/xdp.h:89
Inline: False
```
**Symbols:**

```
ffffffff81229ac0-ffffffff81229c01: trace_event_raw_event_xdp_redirect_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void trace_event_raw_event_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, const void *tgt, int err, enum bpf_map_type map_type, u32 map_id, u32 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126ae50)
Location: include/trace/events/xdp.h:89
Inline: False
```
**Symbols:**

```
ffffffff8126ae50-ffffffff8126af8b: trace_event_raw_event_xdp_redirect_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void trace_event_raw_event_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, const void *tgt, int err, enum bpf_map_type map_type, u32 map_id, u32 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812bff10)
Location: include/trace/events/xdp.h:89
Inline: False
```
**Symbols:**

```
ffffffff812bff10-ffffffff812c004b: trace_event_raw_event_xdp_redirect_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void trace_event_raw_event_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, const void *tgt, int err, enum bpf_map_type map_type, u32 map_id, u32 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812e6cc0)
Location: include/trace/events/xdp.h:89
Inline: False
```
**Symbols:**

```
ffffffff812e6cc0-ffffffff812e6dfb: trace_event_raw_event_xdp_redirect_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void trace_event_raw_event_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, const void *tgt, int err, enum bpf_map_type map_type, u32 map_id, u32 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81304dc0)
Location: include/trace/events/xdp.h:90
Inline: False
```
**Symbols:**

```
ffffffff81304dc0-ffffffff81304efb: trace_event_raw_event_xdp_redirect_template (STB_LOCAL)
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
void trace_event_raw_event_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, int to_ifindex, int err, const struct bpf_map *map, u32 map_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025bc10)
Location: include/trace/events/xdp.h:82
Inline: False
```
**Symbols:**

```
ffff80001025bc10-ffff80001025bd14: trace_event_raw_event_xdp_redirect_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void trace_event_raw_event_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, int to_ifindex, int err, const struct bpf_map *map, u32 map_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c048fae0)
Location: include/trace/events/xdp.h:82
Inline: False
```
**Symbols:**

```
c048fae0-c048fbe4: trace_event_raw_event_xdp_redirect_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void trace_event_raw_event_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, int to_ifindex, int err, const struct bpf_map *map, u32 map_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0000000003007d0)
Location: include/trace/events/xdp.h:82
Inline: False
```
**Symbols:**

```
c0000000003007d0-c000000000300940: trace_event_raw_event_xdp_redirect_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void trace_event_raw_event_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, int to_ifindex, int err, const struct bpf_map *map, u32 map_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019ae22)
Location: include/trace/events/xdp.h:82
Inline: False
```
**Symbols:**

```
ffffffe00019ae22-ffffffe00019aeec: trace_event_raw_event_xdp_redirect_template (STB_LOCAL)
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
void trace_event_raw_event_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, int to_ifindex, int err, const struct bpf_map *map, u32 map_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d4100)
Location: include/trace/events/xdp.h:82
Inline: False
```
**Symbols:**

```
ffffffff811d4100-ffffffff811d4207: trace_event_raw_event_xdp_redirect_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void trace_event_raw_event_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, int to_ifindex, int err, const struct bpf_map *map, u32 map_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c6ec0)
Location: include/trace/events/xdp.h:82
Inline: False
```
**Symbols:**

```
ffffffff811c6ec0-ffffffff811c6fc7: trace_event_raw_event_xdp_redirect_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void trace_event_raw_event_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, int to_ifindex, int err, const struct bpf_map *map, u32 map_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d1ed0)
Location: include/trace/events/xdp.h:82
Inline: False
```
**Symbols:**

```
ffffffff811d1ed0-ffffffff811d1fd7: trace_event_raw_event_xdp_redirect_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void trace_event_raw_event_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, int to_ifindex, int err, const struct bpf_map *map, u32 map_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811e01c0)
Location: include/trace/events/xdp.h:82
Inline: False
```
**Symbols:**

```
ffffffff811e01c0-ffffffff811e02c7: trace_event_raw_event_xdp_redirect_template (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const void *tgt</code>
</li>
<li>
<b>Param added. </b>
<code>u32 index</code>
</li>
<li>
<b>Param removed. </b>
<code>int to_ifindex</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 map_index</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum bpf_map_type map_type</code>
</li>
<li>
<b>Param added. </b>
<code>u32 map_id</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct bpf_map *map</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, dev, xdp, tgt, err, map, index</code> ➡️ <code>__data, dev, xdp, tgt, err, map_type, map_id, index</code>
</li>
</ul>
</details>
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
