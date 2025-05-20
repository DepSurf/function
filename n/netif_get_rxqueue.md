# Function: <code>netif_get_rxqueue</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818949b1)
Location: net/core/dev.c:3995
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b542b)
Location: net/core/dev.c:4290
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818fab8a)
Location: net/core/dev.c:4299
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192ccae)
Location: net/core/dev.c:4201
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a066ea)
Location: net/core/dev.c:4562
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a07c9e)
Location: net/core/dev.c:4591
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ea5d7)
Location: net/core/dev.c:4697
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81aa1bd9)
Location: net/core/dev.c:4665
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c19db7)
Location: net/core/dev.c:4702
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dcae37)
Location: net/core/dev.c:4689
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e3b9b9)
Location: net/core/dev.c:4664
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef9ef9)
Location: net/core/dev.c:4812
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bcf5a8)
Location: net/core/dev.c:4201
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce5970)
Location: net/core/dev.c:4201
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca63d4)
Location: net/core/dev.c:4201
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000755ab6)
Location: net/core/dev.c:4201
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818cccae)
Location: net/core/dev.c:4201
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81886d3e)
Location: net/core/dev.c:4201
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191dcae)
Location: net/core/dev.c:4201
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193f31e)
Location: net/core/dev.c:4201
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
</details>
</li>
</ul>

## Differences
