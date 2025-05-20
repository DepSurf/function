# Function: <code>cpu_map_enqueue</code>

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
int cpu_map_enqueue(struct bpf_cpu_map_entry *rcpu, struct xdp_buff *xdp, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811b02e0)
Location: kernel/bpf/cpumap.c:653
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff811b02e0-ffffffff811b037d: cpu_map_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cpu_map_enqueue(struct bpf_cpu_map_entry *rcpu, struct xdp_buff *xdp, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811cadb0)
Location: kernel/bpf/cpumap.c:619
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff811cadb0-ffffffff811cae74: cpu_map_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cpu_map_enqueue(struct bpf_cpu_map_entry *rcpu, struct xdp_buff *xdp, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811de6b0)
Location: kernel/bpf/cpumap.c:622
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff811de6b0-ffffffff811de790: cpu_map_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cpu_map_enqueue(struct bpf_cpu_map_entry *rcpu, struct xdp_buff *xdp, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811f3fe0)
Location: kernel/bpf/cpumap.c:668
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff811f3fe0-ffffffff811f4107: cpu_map_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cpu_map_enqueue(struct bpf_cpu_map_entry *rcpu, struct xdp_buff *xdp, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff81200d80)
Location: kernel/bpf/cpumap.c:668
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff81200d80-ffffffff81200ea7: cpu_map_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cpu_map_enqueue(struct bpf_cpu_map_entry *rcpu, struct xdp_buff *xdp, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff812287e0)
Location: kernel/bpf/cpumap.c:619
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff812287e0-ffffffff81228929: cpu_map_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cpu_map_enqueue(struct bpf_cpu_map_entry *rcpu, struct xdp_buff *xdp, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff8122f6d0)
Location: kernel/bpf/cpumap.c:719
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff8122f6d0-ffffffff8122f816: cpu_map_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cpu_map_enqueue(struct bpf_cpu_map_entry *rcpu, struct xdp_buff *xdp, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff812344d0)
Location: kernel/bpf/cpumap.c:682
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff812344d0-ffffffff81234613: cpu_map_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cpu_map_enqueue(struct bpf_cpu_map_entry *rcpu, struct xdp_buff *xdp, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff8126e4a0)
Location: kernel/bpf/cpumap.c:749
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff8126e4a0-ffffffff8126e615: cpu_map_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cpu_map_enqueue(struct bpf_cpu_map_entry *rcpu, struct xdp_frame *xdpf, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff812bd470)
Location: kernel/bpf/cpumap.c:751
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff812bd470-ffffffff812bd523: cpu_map_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cpu_map_enqueue(struct bpf_cpu_map_entry *rcpu, struct xdp_frame *xdpf, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff81320900)
Location: kernel/bpf/cpumap.c:750
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff81320900-ffffffff813209b3: cpu_map_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cpu_map_enqueue(struct bpf_cpu_map_entry *rcpu, struct xdp_frame *xdpf, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff813507b0)
Location: kernel/bpf/cpumap.c:771
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff813507b0-ffffffff81350863: cpu_map_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cpu_map_enqueue(struct bpf_cpu_map_entry *rcpu, struct xdp_frame *xdpf, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff81377be0)
Location: kernel/bpf/cpumap.c:725
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff81377be0-ffffffff81377c93: cpu_map_enqueue (STB_GLOBAL)
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
int cpu_map_enqueue(struct bpf_cpu_map_entry *rcpu, struct xdp_buff *xdp, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffff8000102889f0)
Location: kernel/bpf/cpumap.c:668
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffff8000102889f0-ffff800010288b10: cpu_map_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cpu_map_enqueue(struct bpf_cpu_map_entry *rcpu, struct xdp_buff *xdp, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (c04b8714)
Location: kernel/bpf/cpumap.c:668
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
c04b8714-c04b8820: cpu_map_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cpu_map_enqueue(struct bpf_cpu_map_entry *rcpu, struct xdp_buff *xdp, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (c000000000333f50)
Location: kernel/bpf/cpumap.c:668
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
c000000000333f50-c0000000003340f4: cpu_map_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cpu_map_enqueue(struct bpf_cpu_map_entry *rcpu, struct xdp_buff *xdp, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffe0001bd110)
Location: kernel/bpf/cpumap.c:668
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffe0001bd110-ffffffe0001bd21c: cpu_map_enqueue (STB_GLOBAL)
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
int cpu_map_enqueue(struct bpf_cpu_map_entry *rcpu, struct xdp_buff *xdp, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811f93a0)
Location: kernel/bpf/cpumap.c:668
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff811f93a0-ffffffff811f94c7: cpu_map_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cpu_map_enqueue(struct bpf_cpu_map_entry *rcpu, struct xdp_buff *xdp, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811ec0f0)
Location: kernel/bpf/cpumap.c:668
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff811ec0f0-ffffffff811ec217: cpu_map_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cpu_map_enqueue(struct bpf_cpu_map_entry *rcpu, struct xdp_buff *xdp, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811f7170)
Location: kernel/bpf/cpumap.c:668
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff811f7170-ffffffff811f7297: cpu_map_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cpu_map_enqueue(struct bpf_cpu_map_entry *rcpu, struct xdp_buff *xdp, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff812056f0)
Location: kernel/bpf/cpumap.c:668
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff812056f0-ffffffff81205817: cpu_map_enqueue (STB_GLOBAL)
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
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
