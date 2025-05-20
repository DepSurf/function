# Function: <code>__list_del_clearprev</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811f27b6)
Location: include/linux/list.h:117
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:bq_xmit_all
```
```
In kernel/bpf/cpumap.c (ffffffff811f32e6)
Location: include/linux/list.h:117
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
```
In kernel/bpf/xskmap.c (ffffffff811f466d)
Location: include/linux/list.h:117
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:__xsk_map_flush
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
In kernel/bpf/devmap.c (ffffffff811fefe6)
Location: include/linux/list.h:117
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:bq_xmit_all
```
```
In kernel/bpf/cpumap.c (ffffffff81200086)
Location: include/linux/list.h:117
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
```
In kernel/bpf/xskmap.c (ffffffff8120160d)
Location: include/linux/list.h:117
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:__xsk_map_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff81226d39)
Location: include/linux/list.h:124
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff81227c70)
Location: include/linux/list.h:124
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81ba81e9)
Location: include/linux/list.h:124
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_map_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8122d8c3)
Location: include/linux/list.h:124
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:bq_xmit_all
```
```
In kernel/bpf/cpumap.c (ffffffff8122e67f)
Location: include/linux/list.h:124
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
```
In net/xdp/xsk.c (ffffffff81bb7f24)
Location: include/linux/list.h:124
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_map_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8123298f)
Location: include/linux/list.h:124
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:bq_xmit_all
```
```
In kernel/bpf/cpumap.c (ffffffff8123355f)
Location: include/linux/list.h:124
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
```
In net/xdp/xsk.c (ffffffff81ba70fa)
Location: include/linux/list.h:124
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_map_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8126c582)
Location: include/linux/list.h:124
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_flush
```
```
In kernel/bpf/cpumap.c (ffffffff8126e400)
Location: include/linux/list.h:124
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
```
In net/xdp/xsk.c (ffffffff81c74d7a)
Location: include/linux/list.h:124
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_map_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff812bb2f2)
Location: include/linux/list.h:126
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_flush
```
```
In kernel/bpf/cpumap.c (ffffffff812bd322)
Location: include/linux/list.h:126
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
```
In net/xdp/xsk.c (ffffffff81e18e4a)
Location: include/linux/list.h:126
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_map_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8131e762)
Location: include/linux/list.h:126
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_flush
```
```
In kernel/bpf/cpumap.c (ffffffff81320792)
Location: include/linux/list.h:126
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
```
In net/xdp/xsk.c (ffffffff81ff00fa)
Location: include/linux/list.h:126
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_map_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8134e562)
Location: include/linux/list.h:126
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_flush
```
```
In kernel/bpf/cpumap.c (ffffffff81350642)
Location: include/linux/list.h:126
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
```
In net/xdp/xsk.c (ffffffff8206c29a)
Location: include/linux/list.h:126
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_map_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff81375a62)
Location: include/linux/list.h:207
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_flush
```
```
In kernel/bpf/cpumap.c (ffffffff81377b12)
Location: include/linux/list.h:207
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
```
In net/xdp/xsk.c (ffffffff8214007a)
Location: include/linux/list.h:207
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_map_flush
```
</details>
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
In kernel/bpf/devmap.c (ffff800010286548)
Location: include/linux/list.h:117
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:bq_xmit_all
```
```
In kernel/bpf/cpumap.c (ffff800010288534)
Location: include/linux/list.h:117
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
```
In kernel/bpf/xskmap.c (ffff8000102895b4)
Location: include/linux/list.h:117
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:__xsk_map_flush
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
In kernel/bpf/devmap.c (c04b6794)
Location: include/linux/list.h:117
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:bq_xmit_all
```
```
In kernel/bpf/cpumap.c (c04b796c)
Location: include/linux/list.h:117
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
```
In kernel/bpf/xskmap.c (c04b8f64)
Location: include/linux/list.h:117
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:__xsk_map_flush
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
In kernel/bpf/devmap.c (c000000000331230)
Location: include/linux/list.h:117
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:bq_xmit_all
```
```
In kernel/bpf/cpumap.c (c000000000332c84)
Location: include/linux/list.h:117
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
```
In kernel/bpf/xskmap.c (c000000000334c74)
Location: include/linux/list.h:117
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:__xsk_map_flush
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
In kernel/bpf/devmap.c (ffffffe0001bb34c)
Location: include/linux/list.h:117
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:bq_xmit_all
```
```
In kernel/bpf/cpumap.c (ffffffe0001bc4bc)
Location: include/linux/list.h:117
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
```
In kernel/bpf/xskmap.c (ffffffe0001bd99c)
Location: include/linux/list.h:117
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:__xsk_map_flush
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
In kernel/bpf/devmap.c (ffffffff811f7606)
Location: include/linux/list.h:117
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:bq_xmit_all
```
```
In kernel/bpf/cpumap.c (ffffffff811f86a6)
Location: include/linux/list.h:117
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
```
In kernel/bpf/xskmap.c (ffffffff811f9c2d)
Location: include/linux/list.h:117
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:__xsk_map_flush
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
In kernel/bpf/devmap.c (ffffffff811ea356)
Location: include/linux/list.h:117
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:bq_xmit_all
```
```
In kernel/bpf/cpumap.c (ffffffff811eb3f6)
Location: include/linux/list.h:117
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
```
In kernel/bpf/xskmap.c (ffffffff811ec97d)
Location: include/linux/list.h:117
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:__xsk_map_flush
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
In kernel/bpf/devmap.c (ffffffff811f53d6)
Location: include/linux/list.h:117
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:bq_xmit_all
```
```
In kernel/bpf/cpumap.c (ffffffff811f6476)
Location: include/linux/list.h:117
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
```
In kernel/bpf/xskmap.c (ffffffff811f79fd)
Location: include/linux/list.h:117
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:__xsk_map_flush
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
In kernel/bpf/devmap.c (ffffffff81203906)
Location: include/linux/list.h:117
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:bq_xmit_all
```
```
In kernel/bpf/cpumap.c (ffffffff812049e3)
Location: include/linux/list.h:117
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
```
In kernel/bpf/xskmap.c (ffffffff81205f7d)
Location: include/linux/list.h:117
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:__xsk_map_flush
```
</details>
</li>
</ul>

## Differences
