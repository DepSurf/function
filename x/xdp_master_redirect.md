# Function: <code>xdp_master_redirect</code>

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
u32 xdp_master_redirect(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81ac29c0)
Location: net/core/filter.c:3942
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - drivers/net/tun.c:tun_build_skb
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/bpf/test_run.c:bpf_test_run
```
**Symbols:**

```
ffffffff81ac29c0-ffffffff81ac2a39: xdp_master_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 xdp_master_redirect(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c3d5c0)
Location: net/core/filter.c:4162
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - drivers/net/tun.c:tun_xdp_one
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/bpf/test_run.c:bpf_test_run
```
**Symbols:**

```
ffffffff81c3d5c0-ffffffff81c3d642: xdp_master_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 xdp_master_redirect(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81df1750)
Location: net/core/filter.c:4176
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - drivers/net/tun.c:tun_xdp_one
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/bpf/test_run.c:bpf_test_run
```
**Symbols:**

```
ffffffff81df1750-ffffffff81df17d2: xdp_master_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 xdp_master_redirect(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e636e0)
Location: net/core/filter.c:4230
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/virtio_net.c:virtnet_xdp_handler
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/bpf/test_run.c:bpf_test_run
```
**Symbols:**

```
ffffffff81e636e0-ffffffff81e63762: xdp_master_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 xdp_master_redirect(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f228d0)
Location: net/core/filter.c:4309
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/virtio_net.c:virtnet_xdp_handler
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/bpf/test_run.c:bpf_test_run
```
**Symbols:**

```
ffffffff81f228d0-ffffffff81f2294f: xdp_master_redirect (STB_GLOBAL)
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
