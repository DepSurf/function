# Function: <code>__bpf_trace_xdp_redirect_template</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __bpf_trace_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, int to_ifindex, int err, const struct bpf_map *map, u32 map_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811b1000)
Location: include/trace/events/xdp.h:53
Inline: False
```
**Symbols:**

```
ffffffff811b1000-ffffffff811b1015: __bpf_trace_xdp_redirect_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, int to_ifindex, int err, const struct bpf_map *map, u32 map_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811bf680)
Location: include/trace/events/xdp.h:53
Inline: False
```
**Symbols:**

```
ffffffff811bf680-ffffffff811bf695: __bpf_trace_xdp_redirect_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, int to_ifindex, int err, const struct bpf_map *map, u32 map_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811cfc60)
Location: include/trace/events/xdp.h:82
Inline: False
```
**Symbols:**

```
ffffffff811cfc60-ffffffff811cfc75: __bpf_trace_xdp_redirect_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, int to_ifindex, int err, const struct bpf_map *map, u32 map_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811dc200)
Location: include/trace/events/xdp.h:82
Inline: False
```
**Symbols:**

```
ffffffff811dc200-ffffffff811dc215: __bpf_trace_xdp_redirect_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, const void *tgt, int err, const struct bpf_map *map, u32 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f8db0)
Location: include/trace/events/xdp.h:94
Inline: False
```
**Symbols:**

```
ffffffff811f8db0-ffffffff811f8dc3: __bpf_trace_xdp_redirect_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, const void *tgt, int err, const struct bpf_map *map, u32 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f7dd0)
Location: include/trace/events/xdp.h:94
Inline: False
```
**Symbols:**

```
ffffffff811f7dd0-ffffffff811f7de3: __bpf_trace_xdp_redirect_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, const void *tgt, int err, enum bpf_map_type map_type, u32 map_id, u32 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f8bb0)
Location: include/trace/events/xdp.h:89
Inline: False
```
**Symbols:**

```
ffffffff811f8bb0-ffffffff811f8bcb: __bpf_trace_xdp_redirect_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, const void *tgt, int err, enum bpf_map_type map_type, u32 map_id, u32 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122a1a0)
Location: include/trace/events/xdp.h:89
Inline: False
```
**Symbols:**

```
ffffffff8122a1a0-ffffffff8122a1bb: __bpf_trace_xdp_redirect_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, const void *tgt, int err, enum bpf_map_type map_type, u32 map_id, u32 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126bbb0)
Location: include/trace/events/xdp.h:89
Inline: False
```
**Symbols:**

```
ffffffff8126bbb0-ffffffff8126bbdf: __bpf_trace_xdp_redirect_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, const void *tgt, int err, enum bpf_map_type map_type, u32 map_id, u32 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c0db0)
Location: include/trace/events/xdp.h:89
Inline: False
```
**Symbols:**

```
ffffffff812c0db0-ffffffff812c0ddf: __bpf_trace_xdp_redirect_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, const void *tgt, int err, enum bpf_map_type map_type, u32 map_id, u32 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812e7b60)
Location: include/trace/events/xdp.h:89
Inline: False
```
**Symbols:**

```
ffffffff812e7b60-ffffffff812e7b8f: __bpf_trace_xdp_redirect_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, const void *tgt, int err, enum bpf_map_type map_type, u32 map_id, u32 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81305e50)
Location: include/trace/events/xdp.h:90
Inline: False
```
**Symbols:**

```
ffffffff81305e50-ffffffff81305e7f: __bpf_trace_xdp_redirect_template (STB_LOCAL)
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
void __bpf_trace_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, int to_ifindex, int err, const struct bpf_map *map, u32 map_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025c2a0)
Location: include/trace/events/xdp.h:82
Inline: False
```
**Symbols:**

```
ffff80001025c2a0-ffff80001025c2c0: __bpf_trace_xdp_redirect_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, int to_ifindex, int err, const struct bpf_map *map, u32 map_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c04901ec)
Location: include/trace/events/xdp.h:82
Inline: False
```
**Symbols:**

```
c04901ec-c0490248: __bpf_trace_xdp_redirect_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, int to_ifindex, int err, const struct bpf_map *map, u32 map_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c000000000301220)
Location: include/trace/events/xdp.h:82
Inline: False
```
**Symbols:**

```
c000000000301220-c000000000301254: __bpf_trace_xdp_redirect_template (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __bpf_trace_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, int to_ifindex, int err, const struct bpf_map *map, u32 map_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d4820)
Location: include/trace/events/xdp.h:82
Inline: False
```
**Symbols:**

```
ffffffff811d4820-ffffffff811d4835: __bpf_trace_xdp_redirect_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, int to_ifindex, int err, const struct bpf_map *map, u32 map_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c75e0)
Location: include/trace/events/xdp.h:82
Inline: False
```
**Symbols:**

```
ffffffff811c75e0-ffffffff811c75f5: __bpf_trace_xdp_redirect_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, int to_ifindex, int err, const struct bpf_map *map, u32 map_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d25f0)
Location: include/trace/events/xdp.h:82
Inline: False
```
**Symbols:**

```
ffffffff811d25f0-ffffffff811d2605: __bpf_trace_xdp_redirect_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_xdp_redirect_template(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, int to_ifindex, int err, const struct bpf_map *map, u32 map_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811e08e0)
Location: include/trace/events/xdp.h:82
Inline: False
```
**Symbols:**

```
ffffffff811e08e0-ffffffff811e08f5: __bpf_trace_xdp_redirect_template (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
