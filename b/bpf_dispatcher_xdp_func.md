# Function: <code>bpf_dispatcher_xdp_func</code>

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
unsigned int bpf_dispatcher_xdp_func(const void *ctx, const struct bpf_insn *insnsi, unsigned int (*bpf_func)(const void *, const struct bpf_insn *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a275f0)
Location: net/core/filter.c:9242
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_run_prog
  - kernel/bpf/devmap.c:dev_map_run_prog
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_build_skb
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
**Symbols:**

```
ffffffff81a275f0-ffffffff81a27600: bpf_dispatcher_xdp_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int bpf_dispatcher_xdp_func(const void *ctx, const struct bpf_insn *insnsi, unsigned int (*bpf_func)(const void *, const struct bpf_insn *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a27c50)
Location: net/core/filter.c:10293
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_run_prog
  - kernel/bpf/devmap.c:dev_map_run_prog
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_build_skb
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
**Symbols:**

```
ffffffff81a27c50-ffffffff81a27c60: bpf_dispatcher_xdp_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int bpf_dispatcher_xdp_func(const void *ctx, const struct bpf_insn *insnsi, unsigned int (*bpf_func)(const void *, const struct bpf_insn *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a0efd0)
Location: net/core/filter.c:10435
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_run_prog
  - kernel/bpf/devmap.c:dev_map_run_prog
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_build_skb
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
**Symbols:**

```
ffffffff81a0efd0-ffffffff81a0efe0: bpf_dispatcher_xdp_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int bpf_dispatcher_xdp_func(const void *ctx, const struct bpf_insn *insnsi, unsigned int (*bpf_func)(const void *, const struct bpf_insn *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81ac15f0)
Location: net/core/filter.c:10634
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_build_skb
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
**Symbols:**

```
ffffffff81ac15f0-ffffffff81ac1600: bpf_dispatcher_xdp_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int bpf_dispatcher_xdp_func(const void *ctx, const struct bpf_insn *insnsi, unsigned int (*bpf_func)(const void *, const struct bpf_insn *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c3b8f0)
Location: net/core/filter.c:11166
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
**Symbols:**

```
ffffffff81c3b8f0-ffffffff81c3b90a: bpf_dispatcher_xdp_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int bpf_dispatcher_xdp_func(const void *ctx, const struct bpf_insn *insnsi, bpf_func_t bpf_func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81df36f0)
Location: net/core/filter.c:11372
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
**Symbols:**

```
ffffffff81df36f0-ffffffff81df370a: bpf_dispatcher_xdp_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int bpf_dispatcher_xdp_func(const void *ctx, const struct bpf_insn *insnsi, bpf_func_t bpf_func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e654e0)
Location: net/core/filter.c:11521
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/virtio_net.c:virtnet_xdp_handler
  - drivers/net/virtio_net.c:virtnet_xdp_handler
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
**Symbols:**

```
ffffffff81e654e0-ffffffff81e654fa: bpf_dispatcher_xdp_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int bpf_dispatcher_xdp_func(const void *ctx, const struct bpf_insn *insnsi, bpf_func_t bpf_func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f24690)
Location: net/core/filter.c:11612
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/virtio_net.c:virtnet_xdp_handler
  - drivers/net/virtio_net.c:virtnet_xdp_handler
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
**Symbols:**

```
ffffffff81f24690-ffffffff81f246aa: bpf_dispatcher_xdp_func (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int (*bpf_func)(const void *, const struct bpf_insn *)</code> ➡️ <code>bpf_func_t bpf_func</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
