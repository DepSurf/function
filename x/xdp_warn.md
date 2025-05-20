# Function: <code>xdp_warn</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xdp_warn(const char *msg, const char *func, const int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a35620)
Location: net/core/xdp.c:474
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:dev_xdp_enqueue
  - kernel/bpf/cpumap.c:cpu_map_enqueue
  - drivers/net/tun.c:tun_xdp_act
```
**Symbols:**

```
ffffffff81a35620-ffffffff81a3563c: xdp_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xdp_warn(const char *msg, const char *func, const int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a37980)
Location: net/core/xdp.c:511
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:dev_xdp_enqueue
  - kernel/bpf/cpumap.c:cpu_map_enqueue
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - drivers/net/tun.c:tun_xdp_act
```
**Symbols:**

```
ffffffff81a37980-ffffffff81a3799c: xdp_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xdp_warn(const char *msg, const char *func, const int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a1eae0)
Location: net/core/xdp.c:512
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:dev_xdp_enqueue
  - kernel/bpf/cpumap.c:cpu_map_enqueue
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - drivers/net/tun.c:tun_xdp_act
```
**Symbols:**

```
ffffffff81a1eae0-ffffffff81a1eafc: xdp_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xdp_warn(const char *msg, const char *func, const int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81ad2b80)
Location: net/core/xdp.c:513
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_enqueue_multi
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:dev_xdp_enqueue
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/cpumap.c:cpu_map_enqueue
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - drivers/net/tun.c:tun_xdp_act
```
**Symbols:**

```
ffffffff81ad2b80-ffffffff81ad2b9c: xdp_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xdp_warn(const char *msg, const char *func, const int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81c50660)
Location: net/core/xdp.c:599
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - drivers/net/tun.c:tun_xdp_act
  - net/core/filter.c:xdp_do_redirect
  - net/bpf/test_run.c:xdp_test_run_init_page
```
**Symbols:**

```
ffffffff81c50660-ffffffff81c50688: xdp_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xdp_warn(const char *msg, const char *func, const int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81e05a90)
Location: net/core/xdp.c:597
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - drivers/net/tun.c:tun_xdp_act
  - net/core/filter.c:xdp_do_redirect
  - net/bpf/test_run.c:xdp_test_run_init_page
```
**Symbols:**

```
ffffffff81e05a90-ffffffff81e05ab8: xdp_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xdp_warn(const char *msg, const char *func, const int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81e78170)
Location: net/core/xdp.c:584
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - drivers/net/tun.c:tun_xdp_act
  - drivers/net/virtio_net.c:virtnet_xdp_handler
  - net/core/filter.c:xdp_do_redirect
  - net/bpf/test_run.c:xdp_test_run_init_page
```
**Symbols:**

```
ffffffff81e78170-ffffffff81e78198: xdp_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xdp_warn(const char *msg, const char *func, const int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81f38130)
Location: net/core/xdp.c:584
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - drivers/net/tun.c:tun_xdp_act
  - drivers/net/virtio_net.c:virtnet_xdp_handler
  - net/core/filter.c:xdp_do_redirect
  - net/bpf/test_run.c:xdp_test_run_init_page
```
**Symbols:**

```
ffffffff81f38130-ffffffff81f38158: xdp_warn (STB_GLOBAL)
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
