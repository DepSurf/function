# Function: <code>xdp_clear_umem_at_qid</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81a05c3a)
Location: net/xdp/xdp_umem.c:71
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
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
In net/xdp/xdp_umem.c (ffffffff81a75907)
Location: net/xdp/xdp_umem.c:75
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_clear_dev
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
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
In net/xdp/xdp_umem.c (ffffffff81aac797)
Location: net/xdp/xdp_umem.c:82
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_clear_dev
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
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
In net/xdp/xdp_umem.c (ffffffff81ba8a3a)
Location: net/xdp/xdp_umem.c:82
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_clear_dev
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
```
</details>
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffff800010d81040)
Location: net/xdp/xdp_umem.c:82
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_clear_dev
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
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
In net/xdp/xdp_umem.c (c0e7b538)
Location: net/xdp/xdp_umem.c:82
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_clear_dev
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
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
In net/xdp/xdp_umem.c (c000000000ec0e4c)
Location: net/xdp/xdp_umem.c:82
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_clear_dev
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
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
In net/xdp/xdp_umem.c (ffffffe0008ad522)
Location: net/xdp/xdp_umem.c:82
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_clear_dev
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
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
In net/xdp/xdp_umem.c (ffffffff81a4bb27)
Location: net/xdp/xdp_umem.c:82
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_clear_dev
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
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
In net/xdp/xdp_umem.c (ffffffff81a08717)
Location: net/xdp/xdp_umem.c:82
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_clear_dev
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
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
In net/xdp/xdp_umem.c (ffffffff81ab79d7)
Location: net/xdp/xdp_umem.c:82
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_clear_dev
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
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
In net/xdp/xdp_umem.c (ffffffff81ac3df7)
Location: net/xdp/xdp_umem.c:82
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_clear_dev
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
```
</details>
</li>
</ul>

## Differences
