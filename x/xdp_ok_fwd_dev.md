# Function: <code>xdp_ok_fwd_dev</code>

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
In kernel/bpf/devmap.c (ffffffff811ca148)
Location: include/linux/filter.h:768
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:dev_map_enqueue
```
```
In net/core/filter.c (ffffffff818b51f1)
Location: include/linux/filter.h:768
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
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
In kernel/bpf/devmap.c (ffffffff811dda68)
Location: include/linux/filter.h:820
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:dev_map_enqueue
```
```
In net/core/filter.c (ffffffff818d9cd3)
Location: include/linux/filter.h:820
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
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
In kernel/bpf/devmap.c (ffffffff811f3121)
Location: include/linux/filter.h:887
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:dev_map_enqueue
```
```
In net/core/filter.c (ffffffff81927939)
Location: include/linux/filter.h:887
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
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
In kernel/bpf/devmap.c (ffffffff811ffec1)
Location: include/linux/filter.h:887
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:dev_map_enqueue
```
```
In net/core/filter.c (ffffffff8195abd2)
Location: include/linux/filter.h:887
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
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
In kernel/bpf/devmap.c (ffffffff81227971)
Location: include/linux/filter.h:922
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:dev_xdp_enqueue
```
```
In net/core/filter.c (ffffffff81a327d0)
Location: include/linux/filter.h:922
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
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
In kernel/bpf/devmap.c (ffffffff8122e4d4)
Location: include/linux/filter.h:931
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:dev_xdp_enqueue
```
```
In net/core/filter.c (ffffffff81a34b9f)
Location: include/linux/filter.h:931
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
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
In kernel/bpf/devmap.c (ffffffff81233344)
Location: include/linux/filter.h:974
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:dev_xdp_enqueue
```
```
In net/core/filter.c (ffffffff81a1bba0)
Location: include/linux/filter.h:974
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
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
In kernel/bpf/devmap.c (ffffffff8126cc0c)
Location: include/linux/filter.h:995
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:is_valid_dst
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:dev_xdp_enqueue
```
```
In net/core/filter.c (ffffffff81acf310)
Location: include/linux/filter.h:995
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
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
In kernel/bpf/devmap.c (ffffffff812bb8fd)
Location: include/linux/filter.h:990
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:dev_map_enqueue_multi
  - kernel/bpf/devmap.c:dev_map_enqueue_multi
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:dev_xdp_enqueue
```
```
In net/core/filter.c (ffffffff81c4ca58)
Location: include/linux/filter.h:990
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
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
In kernel/bpf/devmap.c (ffffffff8131ec8d)
Location: include/linux/filter.h:960
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:is_valid_dst
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:dev_xdp_enqueue
```
```
In net/core/filter.c (ffffffff81e01897)
Location: include/linux/filter.h:960
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
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
In kernel/bpf/devmap.c (ffffffff8134eaad)
Location: include/linux/filter.h:960
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:is_valid_dst
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:dev_xdp_enqueue
```
```
In net/core/filter.c (ffffffff81e73b67)
Location: include/linux/filter.h:960
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
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
In kernel/bpf/devmap.c (ffffffff81375fad)
Location: include/linux/filter.h:996
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:is_valid_dst
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:dev_xdp_enqueue
```
```
In net/core/filter.c (ffffffff81f33327)
Location: include/linux/filter.h:996
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
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
In kernel/bpf/devmap.c (ffff800010287844)
Location: include/linux/filter.h:887
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:dev_map_enqueue
```
```
In net/core/filter.c (ffff800010c01cc4)
Location: include/linux/filter.h:887
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
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
In kernel/bpf/devmap.c (c04b778c)
Location: include/linux/filter.h:887
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:dev_map_enqueue
```
```
In net/core/filter.c (c0d15850)
Location: include/linux/filter.h:887
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
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
In kernel/bpf/devmap.c (c0000000003329e8)
Location: include/linux/filter.h:887
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:dev_map_enqueue
```
```
In net/core/filter.c (c000000000ce4964)
Location: include/linux/filter.h:887
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
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
In kernel/bpf/devmap.c (ffffffe0001bc2c4)
Location: include/linux/filter.h:887
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:dev_map_enqueue
```
```
In net/core/filter.c (ffffffe00077dde8)
Location: include/linux/filter.h:887
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
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
In kernel/bpf/devmap.c (ffffffff811f84e1)
Location: include/linux/filter.h:887
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:dev_map_enqueue
```
```
In net/core/filter.c (ffffffff818faba2)
Location: include/linux/filter.h:887
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
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
In kernel/bpf/devmap.c (ffffffff811eb231)
Location: include/linux/filter.h:887
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:dev_map_enqueue
```
```
In net/core/filter.c (ffffffff818b49d2)
Location: include/linux/filter.h:887
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
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
In kernel/bpf/devmap.c (ffffffff811f62b1)
Location: include/linux/filter.h:887
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:dev_map_enqueue
```
```
In net/core/filter.c (ffffffff8194bbd2)
Location: include/linux/filter.h:887
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
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
In kernel/bpf/devmap.c (ffffffff81204821)
Location: include/linux/filter.h:887
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:dev_map_enqueue
```
```
In net/core/filter.c (ffffffff8196d4e2)
Location: include/linux/filter.h:887
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
</details>
</li>
</ul>

## Differences
