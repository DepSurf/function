# Function: <code>__bpf_trace_xdp_devmap_xmit</code>

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
void __bpf_trace_xdp_devmap_xmit(void *__data, const struct bpf_map *map, u32 map_index, int sent, int drops, const struct net_device *from_dev, const struct net_device *to_dev, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811b1040)
Location: include/trace/events/xdp.h:232
Inline: False
```
**Symbols:**

```
ffffffff811b1040-ffffffff811b105b: __bpf_trace_xdp_devmap_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_xdp_devmap_xmit(void *__data, const struct bpf_map *map, u32 map_index, int sent, int drops, const struct net_device *from_dev, const struct net_device *to_dev, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811bf6c0)
Location: include/trace/events/xdp.h:231
Inline: False
```
**Symbols:**

```
ffffffff811bf6c0-ffffffff811bf6db: __bpf_trace_xdp_devmap_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_xdp_devmap_xmit(void *__data, const struct bpf_map *map, u32 map_index, int sent, int drops, const struct net_device *from_dev, const struct net_device *to_dev, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811cfc80)
Location: include/trace/events/xdp.h:259
Inline: False
```
**Symbols:**

```
ffffffff811cfc80-ffffffff811cfc9b: __bpf_trace_xdp_devmap_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_xdp_devmap_xmit(void *__data, const struct bpf_map *map, u32 map_index, int sent, int drops, const struct net_device *from_dev, const struct net_device *to_dev, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811dc220)
Location: include/trace/events/xdp.h:260
Inline: False
```
**Symbols:**

```
ffffffff811dc220-ffffffff811dc23b: __bpf_trace_xdp_devmap_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_xdp_devmap_xmit(void *__data, const struct net_device *from_dev, const struct net_device *to_dev, int sent, int drops, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f8dd0)
Location: include/trace/events/xdp.h:247
Inline: False
```
**Symbols:**

```
ffffffff811f8dd0-ffffffff811f8de3: __bpf_trace_xdp_devmap_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_xdp_devmap_xmit(void *__data, const struct net_device *from_dev, const struct net_device *to_dev, int sent, int drops, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f7e10)
Location: include/trace/events/xdp.h:255
Inline: False
```
**Symbols:**

```
ffffffff811f7e10-ffffffff811f7e23: __bpf_trace_xdp_devmap_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_xdp_devmap_xmit(void *__data, const struct net_device *from_dev, const struct net_device *to_dev, int sent, int drops, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f8bf0)
Location: include/trace/events/xdp.h:263
Inline: False
```
**Symbols:**

```
ffffffff811f8bf0-ffffffff811f8c03: __bpf_trace_xdp_devmap_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_xdp_devmap_xmit(void *__data, const struct net_device *from_dev, const struct net_device *to_dev, int sent, int drops, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122a1e0)
Location: include/trace/events/xdp.h:267
Inline: False
```
**Symbols:**

```
ffffffff8122a1e0-ffffffff8122a1f3: __bpf_trace_xdp_devmap_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_xdp_devmap_xmit(void *__data, const struct net_device *from_dev, const struct net_device *to_dev, int sent, int drops, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126bc10)
Location: include/trace/events/xdp.h:267
Inline: False
```
**Symbols:**

```
ffffffff8126bc10-ffffffff8126bc35: __bpf_trace_xdp_devmap_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_xdp_devmap_xmit(void *__data, const struct net_device *from_dev, const struct net_device *to_dev, int sent, int drops, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c0e30)
Location: include/trace/events/xdp.h:267
Inline: False
```
**Symbols:**

```
ffffffff812c0e30-ffffffff812c0e55: __bpf_trace_xdp_devmap_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_xdp_devmap_xmit(void *__data, const struct net_device *from_dev, const struct net_device *to_dev, int sent, int drops, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812e7be0)
Location: include/trace/events/xdp.h:267
Inline: False
```
**Symbols:**

```
ffffffff812e7be0-ffffffff812e7c05: __bpf_trace_xdp_devmap_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_xdp_devmap_xmit(void *__data, const struct net_device *from_dev, const struct net_device *to_dev, int sent, int drops, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81305ed0)
Location: include/trace/events/xdp.h:268
Inline: False
```
**Symbols:**

```
ffffffff81305ed0-ffffffff81305ef5: __bpf_trace_xdp_devmap_xmit (STB_LOCAL)
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
void __bpf_trace_xdp_devmap_xmit(void *__data, const struct bpf_map *map, u32 map_index, int sent, int drops, const struct net_device *from_dev, const struct net_device *to_dev, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025c2c0)
Location: include/trace/events/xdp.h:260
Inline: False
```
**Symbols:**

```
ffff80001025c2c0-ffff80001025c2e4: __bpf_trace_xdp_devmap_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_xdp_devmap_xmit(void *__data, const struct bpf_map *map, u32 map_index, int sent, int drops, const struct net_device *from_dev, const struct net_device *to_dev, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0490248)
Location: include/trace/events/xdp.h:260
Inline: False
```
**Symbols:**

```
c0490248-c04902b0: __bpf_trace_xdp_devmap_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_xdp_devmap_xmit(void *__data, const struct bpf_map *map, u32 map_index, int sent, int drops, const struct net_device *from_dev, const struct net_device *to_dev, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c000000000301260)
Location: include/trace/events/xdp.h:260
Inline: False
```
**Symbols:**

```
c000000000301260-c000000000301298: __bpf_trace_xdp_devmap_xmit (STB_LOCAL)
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
void __bpf_trace_xdp_devmap_xmit(void *__data, const struct bpf_map *map, u32 map_index, int sent, int drops, const struct net_device *from_dev, const struct net_device *to_dev, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d4840)
Location: include/trace/events/xdp.h:260
Inline: False
```
**Symbols:**

```
ffffffff811d4840-ffffffff811d485b: __bpf_trace_xdp_devmap_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_xdp_devmap_xmit(void *__data, const struct bpf_map *map, u32 map_index, int sent, int drops, const struct net_device *from_dev, const struct net_device *to_dev, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c7600)
Location: include/trace/events/xdp.h:260
Inline: False
```
**Symbols:**

```
ffffffff811c7600-ffffffff811c761b: __bpf_trace_xdp_devmap_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_xdp_devmap_xmit(void *__data, const struct bpf_map *map, u32 map_index, int sent, int drops, const struct net_device *from_dev, const struct net_device *to_dev, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d2610)
Location: include/trace/events/xdp.h:260
Inline: False
```
**Symbols:**

```
ffffffff811d2610-ffffffff811d262b: __bpf_trace_xdp_devmap_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_xdp_devmap_xmit(void *__data, const struct bpf_map *map, u32 map_index, int sent, int drops, const struct net_device *from_dev, const struct net_device *to_dev, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811e0900)
Location: include/trace/events/xdp.h:260
Inline: False
```
**Symbols:**

```
ffffffff811e0900-ffffffff811e091b: __bpf_trace_xdp_devmap_xmit (STB_LOCAL)
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
<b>Param removed. </b>
<code>const struct bpf_map *map</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 map_index</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, map, map_index, sent, drops, from_dev, to_dev, err</code> ➡️ <code>__data, from_dev, to_dev, sent, drops, err</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
