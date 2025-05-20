# Function: <code>bq_enqueue</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811b033b)
Location: kernel/bpf/cpumap.c:633
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811ca0ca)
Location: kernel/bpf/devmap.c:316
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
```
```
In kernel/bpf/cpumap.c (ffffffff811cae27)
Location: kernel/bpf/cpumap.c:599
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811dd9de)
Location: kernel/bpf/devmap.c:317
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
```
```
In kernel/bpf/cpumap.c (ffffffff811de72e)
Location: kernel/bpf/cpumap.c:602
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811f303e)
Location: kernel/bpf/devmap.c:298
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
```
```
In kernel/bpf/cpumap.c (ffffffff811f4071)
Location: kernel/bpf/cpumap.c:643
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811ffdde)
Location: kernel/bpf/devmap.c:436
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
```
```
In kernel/bpf/cpumap.c (ffffffff81200e11)
Location: kernel/bpf/cpumap.c:643
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int bq_enqueue(struct net_device *dev, struct xdp_frame *xdpf, struct net_device *dev_rx);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff81226e00)
Location: kernel/bpf/devmap.c:424
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:dev_xdp_enqueue
```
```
In kernel/bpf/cpumap.c (ffffffff81228884)
Location: kernel/bpf/cpumap.c:594
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
**Symbols:**

```
ffffffff81226e00-ffffffff81226ebd: bq_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
void bq_enqueue(struct net_device *dev, struct xdp_frame *xdpf, struct net_device *dev_rx);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8122d960)
Location: kernel/bpf/devmap.c:410
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:dev_xdp_enqueue
```
```
In kernel/bpf/cpumap.c (ffffffff8122f774)
Location: kernel/bpf/cpumap.c:696
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
**Symbols:**

```
ffffffff8122d960-ffffffff8122da19: bq_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void bq_enqueue(struct net_device *dev, struct xdp_frame *xdpf, struct net_device *dev_rx);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff81232a30)
Location: kernel/bpf/devmap.c:403
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:dev_xdp_enqueue
```
```
In kernel/bpf/cpumap.c (ffffffff81234571)
Location: kernel/bpf/cpumap.c:659
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
**Symbols:**

```
ffffffff81232a30-ffffffff81232ae9: bq_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void bq_enqueue(struct net_device *dev, struct xdp_frame *xdpf, struct net_device *dev_rx, struct bpf_prog *xdp_prog);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8126c030)
Location: kernel/bpf/devmap.c:445
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_enqueue_multi
  - kernel/bpf/devmap.c:dev_map_enqueue_multi
  - kernel/bpf/devmap.c:dev_map_enqueue_multi
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:dev_xdp_enqueue
```
```
In kernel/bpf/cpumap.c (ffffffff8126e543)
Location: kernel/bpf/cpumap.c:726
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
**Symbols:**

```
ffffffff8126c030-ffffffff8126c0fa: bq_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
void bq_enqueue(struct net_device *dev, struct xdp_frame *xdpf, struct net_device *dev_rx, struct bpf_prog *xdp_prog);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff812bb4de)
Location: kernel/bpf/devmap.c:446
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:dev_xdp_enqueue
Direct callers:
  - kernel/bpf/devmap.c:dev_map_enqueue_multi
  - kernel/bpf/devmap.c:dev_map_enqueue_multi
  - kernel/bpf/devmap.c:dev_map_enqueue_multi
```
```
In kernel/bpf/cpumap.c (ffffffff812bd48e)
Location: kernel/bpf/cpumap.c:728
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
**Symbols:**

```
ffffffff812baeb0-ffffffff812baf8b: bq_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
void bq_enqueue(struct net_device *dev, struct xdp_frame *xdpf, struct net_device *dev_rx, struct bpf_prog *xdp_prog);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8131e2c0)
Location: kernel/bpf/devmap.c:446
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_enqueue_multi
  - kernel/bpf/devmap.c:dev_map_enqueue_multi
  - kernel/bpf/devmap.c:dev_map_enqueue_multi
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:dev_xdp_enqueue
```
```
In kernel/bpf/cpumap.c (ffffffff8132091e)
Location: kernel/bpf/cpumap.c:727
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
**Symbols:**

```
ffffffff8131e2c0-ffffffff8131e39b: bq_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
void bq_enqueue(struct net_device *dev, struct xdp_frame *xdpf, struct net_device *dev_rx, struct bpf_prog *xdp_prog);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8134e0b0)
Location: kernel/bpf/devmap.c:443
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_enqueue_multi
  - kernel/bpf/devmap.c:dev_map_enqueue_multi
  - kernel/bpf/devmap.c:dev_map_enqueue_multi
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:dev_xdp_enqueue
```
```
In kernel/bpf/cpumap.c (ffffffff813507ce)
Location: kernel/bpf/cpumap.c:748
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
**Symbols:**

```
ffffffff8134e0b0-ffffffff8134e18b: bq_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void bq_enqueue(struct net_device *dev, struct xdp_frame *xdpf, struct net_device *dev_rx, struct bpf_prog *xdp_prog);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff813755b0)
Location: kernel/bpf/devmap.c:452
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_enqueue_multi
  - kernel/bpf/devmap.c:dev_map_enqueue_multi
  - kernel/bpf/devmap.c:dev_map_enqueue_multi
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:dev_xdp_enqueue
```
```
In kernel/bpf/cpumap.c (ffffffff81377bfe)
Location: kernel/bpf/cpumap.c:702
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
**Symbols:**

```
ffffffff813755b0-ffffffff8137568b: bq_enqueue (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffff800010287734)
Location: kernel/bpf/devmap.c:436
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
```
```
In kernel/bpf/cpumap.c (ffff800010288a78)
Location: kernel/bpf/cpumap.c:643
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (c04b76bc)
Location: kernel/bpf/devmap.c:436
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
```
```
In kernel/bpf/cpumap.c (c04b879c)
Location: kernel/bpf/cpumap.c:643
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (c000000000332870)
Location: kernel/bpf/devmap.c:436
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
```
```
In kernel/bpf/cpumap.c (c000000000333fec)
Location: kernel/bpf/cpumap.c:643
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffe0001bc1e8)
Location: kernel/bpf/devmap.c:436
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
```
```
In kernel/bpf/cpumap.c (ffffffe0001bd188)
Location: kernel/bpf/cpumap.c:643
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811f83fe)
Location: kernel/bpf/devmap.c:436
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
```
```
In kernel/bpf/cpumap.c (ffffffff811f9431)
Location: kernel/bpf/cpumap.c:643
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811eb14e)
Location: kernel/bpf/devmap.c:436
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
```
```
In kernel/bpf/cpumap.c (ffffffff811ec181)
Location: kernel/bpf/cpumap.c:643
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811f61ce)
Location: kernel/bpf/devmap.c:436
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
```
```
In kernel/bpf/cpumap.c (ffffffff811f7201)
Location: kernel/bpf/cpumap.c:643
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8120473e)
Location: kernel/bpf/devmap.c:436
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
```
```
In kernel/bpf/cpumap.c (ffffffff81205781)
Location: kernel/bpf/cpumap.c:643
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_prog *xdp_prog</code>
</li>
</ul>
</details>
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
