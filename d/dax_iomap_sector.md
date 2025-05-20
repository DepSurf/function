# Function: <code>dax_iomap_sector</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8129ce47)
Location: fs/dax.c:993
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_actor
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812abafa)
Location: fs/dax.c:936
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_actor
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812cf3c8)
Location: fs/dax.c:828
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812f6f4a)
Location: fs/dax.c:1075
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
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
In fs/dax.c (ffffffff8130bffa)
Location: fs/dax.c:980
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
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
In fs/dax.c (ffffffff813335a6)
Location: fs/dax.c:985
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
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
In fs/dax.c (ffffffff81347166)
Location: fs/dax.c:986
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
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
In fs/dax.c (ffffffff8138e6b5)
Location: fs/dax.c:980
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
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
In fs/dax.c (ffffffff8139fe0e)
Location: fs/dax.c:996
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
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
In fs/dax.c (ffffffff813a73ca)
Location: fs/dax.c:1008
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
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
In fs/dax.c (ffffffff813f686c)
Location: fs/dax.c:1008
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_iomap_iter
```
</details>
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
In fs/dax.c (ffff80001040746c)
Location: fs/dax.c:986
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (c000000000512d50)
Location: fs/dax.c:986
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
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
In fs/dax.c (ffffffe0002b22c6)
Location: fs/dax.c:986
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
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
In fs/dax.c (ffffffff8133f746)
Location: fs/dax.c:986
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
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
In fs/dax.c (ffffffff81330406)
Location: fs/dax.c:986
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
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
In fs/dax.c (ffffffff8133d216)
Location: fs/dax.c:986
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
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
In fs/dax.c (ffffffff81350926)
Location: fs/dax.c:986
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
```
</details>
</li>
</ul>

## Differences
