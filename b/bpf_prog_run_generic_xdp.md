# Function: <code>bpf_prog_run_generic_xdp</code>

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
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u32 bpf_prog_run_generic_xdp(struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:4688
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
```
**Symbols:**

```
ffffffff81d363be-ffffffff81d363ef: bpf_prog_run_generic_xdp.cold (STB_LOCAL)
ffffffff81aa1b70-ffffffff81aa1eff: bpf_prog_run_generic_xdp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u32 bpf_prog_run_generic_xdp(struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:4725
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
  - net/core/dev.c:netif_receive_generic_xdp
```
**Symbols:**

```
ffffffff81f02bae-ffffffff81f02be9: bpf_prog_run_generic_xdp.cold (STB_LOCAL)
ffffffff81c19d50-ffffffff81c1a0ee: bpf_prog_run_generic_xdp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u32 bpf_prog_run_generic_xdp(struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:4712
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
  - net/core/dev.c:netif_receive_generic_xdp
```
**Symbols:**

```
ffffffff820ab620-ffffffff820ab65b: bpf_prog_run_generic_xdp.cold (STB_LOCAL)
ffffffff81dcadd0-ffffffff81dcb16e: bpf_prog_run_generic_xdp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u32 bpf_prog_run_generic_xdp(struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:4687
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
  - net/core/dev.c:netif_receive_generic_xdp
```
**Symbols:**

```
ffffffff8212cda9-ffffffff8212cdda: bpf_prog_run_generic_xdp.cold (STB_LOCAL)
ffffffff81e3b950-ffffffff81e3bcfd: bpf_prog_run_generic_xdp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u32 bpf_prog_run_generic_xdp(struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:4835
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
  - net/core/dev.c:netif_receive_generic_xdp
```
**Symbols:**

```
ffffffff8220eb12-ffffffff8220eb43: bpf_prog_run_generic_xdp.cold (STB_LOCAL)
ffffffff81ef9e90-ffffffff81efa23d: bpf_prog_run_generic_xdp (STB_GLOBAL)
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
