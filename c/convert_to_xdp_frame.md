# Function: <code>convert_to_xdp_frame</code>

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
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811ca055)
Location: include/net/xdp.h:89
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
```
```
In kernel/bpf/cpumap.c (ffffffff811cadb5)
Location: include/net/xdp.h:89
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
```
In drivers/net/tun.c (ffffffff8173d0ef)
Location: include/net/xdp.h:89
Inline: True
```
```
In net/core/filter.c (ffffffff818b4612)
Location: include/net/xdp.h:89
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811dd973)
Location: include/net/xdp.h:98
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
```
```
In kernel/bpf/cpumap.c (ffffffff811de6b5)
Location: include/net/xdp.h:98
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
```
In drivers/net/tun.c (ffffffff817609ed)
Location: include/net/xdp.h:98
Inline: True
```
```
In net/core/filter.c (ffffffff818da075)
Location: include/net/xdp.h:98
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811f2fd7)
Location: include/net/xdp.h:98
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
```
```
In kernel/bpf/cpumap.c (ffffffff811f3fe5)
Location: include/net/xdp.h:98
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
```
In drivers/net/tun.c (ffffffff8179e1d5)
Location: include/net/xdp.h:98
Inline: True
```
```
In net/core/filter.c (ffffffff8192882a)
Location: include/net/xdp.h:98
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811ffd77)
Location: include/net/xdp.h:98
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
```
```
In kernel/bpf/cpumap.c (ffffffff81200d85)
Location: include/net/xdp.h:98
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
```
In drivers/net/tun.c (ffffffff817c1c65)
Location: include/net/xdp.h:98
Inline: True
```
```
In net/core/filter.c (ffffffff8195aefa)
Location: include/net/xdp.h:98
Inline: True
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffff8000102876d4)
Location: include/net/xdp.h:98
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
```
```
In kernel/bpf/cpumap.c (ffff800010288a14)
Location: include/net/xdp.h:98
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
```
In drivers/net/tun.c (ffff8000109dd130)
Location: include/net/xdp.h:98
Inline: True
```
```
In net/core/filter.c (ffff800010c01738)
Location: include/net/xdp.h:98
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (c04b7654)
Location: include/net/xdp.h:98
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
```
```
In kernel/bpf/cpumap.c (c04b8728)
Location: include/net/xdp.h:98
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
```
In drivers/net/tun.c (c0ac3124)
Location: include/net/xdp.h:98
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad2f3c)
Location: include/net/xdp.h:98
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler
```
```
In net/core/filter.c (c0d15d84)
Location: include/net/xdp.h:98
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_redirect_slow
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (c000000000332804)
Location: include/net/xdp.h:98
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
```
```
In kernel/bpf/cpumap.c (c000000000333f6c)
Location: include/net/xdp.h:98
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
```
In drivers/net/tun.c (c000000000a9e7a8)
Location: include/net/xdp.h:98
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
```
```
In net/core/filter.c (c000000000ce424c)
Location: include/net/xdp.h:98
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffe0001bc196)
Location: include/net/xdp.h:98
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
```
```
In kernel/bpf/cpumap.c (ffffffe0001bd132)
Location: include/net/xdp.h:98
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
```
In drivers/net/tun.c (ffffffe0006276c8)
Location: include/net/xdp.h:98
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_act
```
```
In net/core/filter.c (ffffffe00077d924)
Location: include/net/xdp.h:98
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811f8397)
Location: include/net/xdp.h:98
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
```
```
In kernel/bpf/cpumap.c (ffffffff811f93a5)
Location: include/net/xdp.h:98
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
```
In drivers/net/tun.c (ffffffff81786735)
Location: include/net/xdp.h:98
Inline: True
```
```
In net/core/filter.c (ffffffff818faeca)
Location: include/net/xdp.h:98
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811eb0e7)
Location: include/net/xdp.h:98
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
```
```
In kernel/bpf/cpumap.c (ffffffff811ec0f5)
Location: include/net/xdp.h:98
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
```
In drivers/net/tun.c (ffffffff81766085)
Location: include/net/xdp.h:98
Inline: True
```
```
In net/core/filter.c (ffffffff818b4cfa)
Location: include/net/xdp.h:98
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811f6167)
Location: include/net/xdp.h:98
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
```
```
In kernel/bpf/cpumap.c (ffffffff811f7175)
Location: include/net/xdp.h:98
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
```
In drivers/net/tun.c (ffffffff817b6ae5)
Location: include/net/xdp.h:98
Inline: True
```
```
In net/core/filter.c (ffffffff8194befa)
Location: include/net/xdp.h:98
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff812046d7)
Location: include/net/xdp.h:98
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
```
```
In kernel/bpf/cpumap.c (ffffffff812056f5)
Location: include/net/xdp.h:98
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
```
In drivers/net/tun.c (ffffffff817d0d0a)
Location: include/net/xdp.h:98
Inline: True
```
```
In net/core/filter.c (ffffffff8196d84a)
Location: include/net/xdp.h:98
Inline: True
```
</details>
</li>
</ul>

## Differences
