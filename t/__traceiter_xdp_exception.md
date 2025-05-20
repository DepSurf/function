# Function: <code>__traceiter_xdp_exception</code>

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
int __traceiter_xdp_exception(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, u32 act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f6340)
Location: include/trace/events/xdp.h:28
Inline: False
```
**Symbols:**

```
ffffffff811f6340-ffffffff811f6391: __traceiter_xdp_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_xdp_exception(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, u32 act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f7230)
Location: include/trace/events/xdp.h:28
Inline: False
```
**Symbols:**

```
ffffffff811f7230-ffffffff811f727f: __traceiter_xdp_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_xdp_exception(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, u32 act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81228800)
Location: include/trace/events/xdp.h:28
Inline: False
```
**Symbols:**

```
ffffffff81228800-ffffffff8122884f: __traceiter_xdp_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_xdp_exception(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, u32 act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81269770)
Location: include/trace/events/xdp.h:28
Inline: False
```
**Symbols:**

```
ffffffff81269770-ffffffff812697cb: __traceiter_xdp_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_xdp_exception(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, u32 act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812be6a0)
Location: include/trace/events/xdp.h:28
Inline: False
```
**Symbols:**

```
ffffffff812be6a0-ffffffff812be6fb: __traceiter_xdp_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_xdp_exception(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, u32 act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812e52e0)
Location: include/trace/events/xdp.h:28
Inline: False
```
**Symbols:**

```
ffffffff812e52e0-ffffffff812e533b: __traceiter_xdp_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_xdp_exception(void *__data, const struct net_device *dev, const struct bpf_prog *xdp, u32 act);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81303390)
Location: include/trace/events/xdp.h:29
Inline: False
```
**Symbols:**

```
ffffffff81303390-ffffffff813033eb: __traceiter_xdp_exception (STB_GLOBAL)
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
