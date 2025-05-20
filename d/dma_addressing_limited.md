# Function: <code>dma_addressing_limited</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811232f4)
Location: include/linux/dma-mapping.h:690
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
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
In kernel/dma/direct.c (ffffffff8112f734)
Location: include/linux/dma-mapping.h:695
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
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
In kernel/dma/direct.c (ffffffff8113e4c4)
Location: include/linux/dma-mapping.h:781
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
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
In kernel/dma/direct.c (ffffffff811398b4)
Location: include/linux/dma-mapping.h:446
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
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
In kernel/dma/direct.c (ffffffff8113a984)
Location: include/linux/dma-mapping.h:488
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
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
In kernel/dma/direct.c (ffffffff8115d8b4)
Location: include/linux/dma-mapping.h:468
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
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
In kernel/dma/direct.c (ffffffff8118784e)
Location: include/linux/dma-mapping.h:468
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
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
In kernel/dma/direct.c (ffffffff811c344e)
Location: include/linux/dma-mapping.h:473
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
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
In kernel/dma/direct.c (ffffffff811d5f9e)
Location: include/linux/dma-mapping.h:474
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool dma_addressing_limited(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811e92b0)
Location: kernel/dma/mapping.c:804
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
**Symbols:**

```
ffffffff811e92b0-ffffffff811e9366: dma_addressing_limited (STB_GLOBAL)
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
In kernel/dma/direct.c (ffff800010195294)
Location: include/linux/dma-mapping.h:695
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
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
In kernel/dma/direct.c (0)
Location: include/linux/dma-mapping.h:695
Inline: False
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
In kernel/dma/direct.c (c0000000001f55b4)
Location: include/linux/dma-mapping.h:695
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
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
In kernel/dma/direct.c (ffffffe000126f9c)
Location: include/linux/dma-mapping.h:695
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
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
In kernel/dma/direct.c (ffffffff81127d74)
Location: include/linux/dma-mapping.h:695
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
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
In kernel/dma/direct.c (ffffffff8111a774)
Location: include/linux/dma-mapping.h:695
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
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
In kernel/dma/direct.c (ffffffff81125c04)
Location: include/linux/dma-mapping.h:695
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
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
In kernel/dma/direct.c (ffffffff81132244)
Location: include/linux/dma-mapping.h:695
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
