# Function: <code>__traceiter_xdp_redirect_map_err</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __traceiter_xdp_redirect_map_err(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, const void *tgt, int err, const struct bpf_map *map, u32 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f6550)
Location: include/trace/events/xdp.h:169
Inline: False
```
**Symbols:**

```
ffffffff811f6550-ffffffff811f65c0: __traceiter_xdp_redirect_map_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_xdp_redirect_map_err(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, const void *tgt, int err, enum bpf_map_type map_type, u32 map_id, u32 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f7460)
Location: include/trace/events/xdp.h:176
Inline: False
```
**Symbols:**

```
ffffffff811f7460-ffffffff811f74d3: __traceiter_xdp_redirect_map_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_xdp_redirect_map_err(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, const void *tgt, int err, enum bpf_map_type map_type, u32 map_id, u32 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81228a30)
Location: include/trace/events/xdp.h:180
Inline: False
```
**Symbols:**

```
ffffffff81228a30-ffffffff81228aa3: __traceiter_xdp_redirect_map_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_xdp_redirect_map_err(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, const void *tgt, int err, enum bpf_map_type map_type, u32 map_id, u32 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81269a20)
Location: include/trace/events/xdp.h:180
Inline: False
```
**Symbols:**

```
ffffffff81269a20-ffffffff81269ab5: __traceiter_xdp_redirect_map_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_xdp_redirect_map_err(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, const void *tgt, int err, enum bpf_map_type map_type, u32 map_id, u32 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812be9a0)
Location: include/trace/events/xdp.h:180
Inline: False
```
**Symbols:**

```
ffffffff812be9a0-ffffffff812bea35: __traceiter_xdp_redirect_map_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_xdp_redirect_map_err(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, const void *tgt, int err, enum bpf_map_type map_type, u32 map_id, u32 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812e5640)
Location: include/trace/events/xdp.h:180
Inline: False
```
**Symbols:**

```
ffffffff812e5640-ffffffff812e56d5: __traceiter_xdp_redirect_map_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_xdp_redirect_map_err(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, const void *tgt, int err, enum bpf_map_type map_type, u32 map_id, u32 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff813036f0)
Location: include/trace/events/xdp.h:181
Inline: False
```
**Symbols:**

```
ffffffff813036f0-ffffffff81303785: __traceiter_xdp_redirect_map_err (STB_GLOBAL)
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
