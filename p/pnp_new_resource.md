# Function: <code>pnp_new_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff814b91e6)
Location: drivers/pnp/resource.c:496
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_add_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_bus_resource
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff81509032)
Location: drivers/pnp/resource.c:496
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/pnp/resource.c:pnp_add_resource
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff8152d252)
Location: drivers/pnp/resource.c:496
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/pnp/resource.c:pnp_add_resource
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
In drivers/pnp/resource.c (ffffffff81540312)
Location: drivers/pnp/resource.c:496
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/pnp/resource.c:pnp_add_resource
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
In drivers/pnp/resource.c (ffffffff815a3432)
Location: drivers/pnp/resource.c:497
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/pnp/resource.c:pnp_add_resource
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
In drivers/pnp/resource.c (ffffffff815db095)
Location: drivers/pnp/resource.c:497
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/pnp/resource.c:pnp_add_resource
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pnp_resource *pnp_new_resource(struct pnp_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff815f3aa0)
Location: drivers/pnp/resource.c:497
Inline: False
Direct callers:
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/pnp/resource.c:pnp_add_resource
```
**Symbols:**

```
ffffffff815f3aa0-ffffffff815f3aea: pnp_new_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct pnp_resource *pnp_new_resource(struct pnp_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff816258e0)
Location: drivers/pnp/resource.c:497
Inline: False
Direct callers:
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/pnp/resource.c:pnp_add_resource
```
**Symbols:**

```
ffffffff816258e0-ffffffff8162592a: pnp_new_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct pnp_resource *pnp_new_resource(struct pnp_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff816473d0)
Location: drivers/pnp/resource.c:497
Inline: False
Direct callers:
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/pnp/resource.c:pnp_add_resource
```
**Symbols:**

```
ffffffff816473d0-ffffffff8164741a: pnp_new_resource (STB_LOCAL)
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
In drivers/pnp/resource.c (ffffffff816f6eb5)
Location: drivers/pnp/resource.c:497
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/pnp/resource.c:pnp_add_resource
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
In drivers/pnp/resource.c (ffffffff81713f11)
Location: drivers/pnp/resource.c:497
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/pnp/resource.c:pnp_add_resource
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
In drivers/pnp/resource.c (ffffffff816f52c1)
Location: drivers/pnp/resource.c:497
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/pnp/resource.c:pnp_add_resource
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
In drivers/pnp/resource.c (ffffffff8176f881)
Location: drivers/pnp/resource.c:497
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/pnp/resource.c:pnp_add_resource
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
In drivers/pnp/resource.c (ffffffff818a4c71)
Location: drivers/pnp/resource.c:497
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/pnp/resource.c:pnp_add_resource
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
In drivers/pnp/resource.c (ffffffff819ee972)
Location: drivers/pnp/resource.c:498
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/pnp/resource.c:pnp_add_resource
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
In drivers/pnp/resource.c (ffffffff81a37132)
Location: drivers/pnp/resource.c:498
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/pnp/resource.c:pnp_add_resource
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct pnp_resource *pnp_new_resource(struct pnp_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff81a828d1)
Location: drivers/pnp/resource.c:498
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
Direct callers:
  - drivers/pnp/resource.c:pnp_add_resource
```
**Symbols:**

```
ffffffff81a81380-ffffffff81a81406: pnp_new_resource (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct pnp_resource *pnp_new_resource(struct pnp_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffff8000107b4790)
Location: drivers/pnp/resource.c:497
Inline: False
Direct callers:
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/pnp/resource.c:pnp_add_resource
```
**Symbols:**

```
ffff8000107b4790-ffff8000107b47e4: pnp_new_resource (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct pnp_resource *pnp_new_resource(struct pnp_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff8160d430)
Location: drivers/pnp/resource.c:497
Inline: False
Direct callers:
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/pnp/resource.c:pnp_add_resource
```
**Symbols:**

```
ffffffff8160d430-ffffffff8160d47a: pnp_new_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct pnp_resource *pnp_new_resource(struct pnp_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff81601980)
Location: drivers/pnp/resource.c:497
Inline: False
Direct callers:
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/pnp/resource.c:pnp_add_resource
```
**Symbols:**

```
ffffffff81601980-ffffffff816019ca: pnp_new_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pnp_resource *pnp_new_resource(struct pnp_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff8163b210)
Location: drivers/pnp/resource.c:497
Inline: False
Direct callers:
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/pnp/resource.c:pnp_add_resource
```
**Symbols:**

```
ffffffff8163b210-ffffffff8163b25a: pnp_new_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pnp_resource *pnp_new_resource(struct pnp_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff81655560)
Location: drivers/pnp/resource.c:497
Inline: False
Direct callers:
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/pnp/resource.c:pnp_add_resource
```
**Symbols:**

```
ffffffff81655560-ffffffff816555aa: pnp_new_resource (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
