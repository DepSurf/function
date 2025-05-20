# Function: <code>dev_map_enqueue_multi</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dev_map_enqueue_multi(struct xdp_buff *xdp, struct net_device *dev_rx, struct bpf_map *map, bool exclude_ingress);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8126c850)
Location: kernel/bpf/devmap.c:589
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff8126c850-ffffffff8126cbd8: dev_map_enqueue_multi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dev_map_enqueue_multi(struct xdp_frame *xdpf, struct net_device *dev_rx, struct bpf_map *map, bool exclude_ingress);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff812bb5b0)
Location: kernel/bpf/devmap.c:585
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff812bb5b0-ffffffff812bb8c9: dev_map_enqueue_multi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_map_enqueue_multi(struct xdp_frame *xdpf, struct net_device *dev_rx, struct bpf_map *map, bool exclude_ingress);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8131e980)
Location: kernel/bpf/devmap.c:585
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff8131e980-ffffffff8131ec4f: dev_map_enqueue_multi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_map_enqueue_multi(struct xdp_frame *xdpf, struct net_device *dev_rx, struct bpf_map *map, bool exclude_ingress);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8134e7a0)
Location: kernel/bpf/devmap.c:592
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff8134e7a0-ffffffff8134ea6c: dev_map_enqueue_multi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dev_map_enqueue_multi(struct xdp_frame *xdpf, struct net_device *dev_rx, struct bpf_map *map, bool exclude_ingress);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff81375ca0)
Location: kernel/bpf/devmap.c:601
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff81375ca0-ffffffff81375f6c: dev_map_enqueue_multi (STB_GLOBAL)
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
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct xdp_frame *xdpf</code>
</li>
<li>
<b>Param removed. </b>
<code>struct xdp_buff *xdp</code>
</li>
</ul>
</details>
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
