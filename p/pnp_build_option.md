# Function: <code>pnp_build_option</code>

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
In drivers/pnp/resource.c (ffffffff814b8640)
Location: drivers/pnp/resource.c:34
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_register_irq_resource
  - drivers/pnp/resource.c:pnp_register_dma_resource
  - drivers/pnp/resource.c:pnp_register_port_resource
  - drivers/pnp/resource.c:pnp_register_mem_resource
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
In drivers/pnp/resource.c (ffffffff815082c8)
Location: drivers/pnp/resource.c:34
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_register_mem_resource
  - drivers/pnp/resource.c:pnp_register_port_resource
  - drivers/pnp/resource.c:pnp_register_dma_resource
  - drivers/pnp/resource.c:pnp_register_irq_resource
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
In drivers/pnp/resource.c (ffffffff8152c4e8)
Location: drivers/pnp/resource.c:34
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_register_mem_resource
  - drivers/pnp/resource.c:pnp_register_port_resource
  - drivers/pnp/resource.c:pnp_register_dma_resource
  - drivers/pnp/resource.c:pnp_register_irq_resource
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
In drivers/pnp/resource.c (ffffffff8153f5cb)
Location: drivers/pnp/resource.c:34
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_register_mem_resource
  - drivers/pnp/resource.c:pnp_register_port_resource
  - drivers/pnp/resource.c:pnp_register_dma_resource
  - drivers/pnp/resource.c:pnp_register_irq_resource
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
In drivers/pnp/resource.c (ffffffff815a26eb)
Location: drivers/pnp/resource.c:35
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_register_mem_resource
  - drivers/pnp/resource.c:pnp_register_port_resource
  - drivers/pnp/resource.c:pnp_register_dma_resource
  - drivers/pnp/resource.c:pnp_register_irq_resource
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
In drivers/pnp/resource.c (ffffffff815da355)
Location: drivers/pnp/resource.c:35
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_register_mem_resource
  - drivers/pnp/resource.c:pnp_register_port_resource
  - drivers/pnp/resource.c:pnp_register_dma_resource
  - drivers/pnp/resource.c:pnp_register_irq_resource
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pnp_option *pnp_build_option(struct pnp_dev *dev, long unsigned int type, unsigned int option_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff815f3a40)
Location: drivers/pnp/resource.c:35
Inline: False
Direct callers:
  - drivers/pnp/resource.c:pnp_register_mem_resource
  - drivers/pnp/resource.c:pnp_register_port_resource
  - drivers/pnp/resource.c:pnp_register_dma_resource
  - drivers/pnp/resource.c:pnp_register_irq_resource
```
**Symbols:**

```
ffffffff815f3a40-ffffffff815f3a9d: pnp_build_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct pnp_option *pnp_build_option(struct pnp_dev *dev, long unsigned int type, unsigned int option_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff81625880)
Location: drivers/pnp/resource.c:35
Inline: False
Direct callers:
  - drivers/pnp/resource.c:pnp_register_mem_resource
  - drivers/pnp/resource.c:pnp_register_port_resource
  - drivers/pnp/resource.c:pnp_register_dma_resource
  - drivers/pnp/resource.c:pnp_register_irq_resource
```
**Symbols:**

```
ffffffff81625880-ffffffff816258dd: pnp_build_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct pnp_option *pnp_build_option(struct pnp_dev *dev, long unsigned int type, unsigned int option_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff81647370)
Location: drivers/pnp/resource.c:35
Inline: False
Direct callers:
  - drivers/pnp/resource.c:pnp_register_mem_resource
  - drivers/pnp/resource.c:pnp_register_port_resource
  - drivers/pnp/resource.c:pnp_register_dma_resource
  - drivers/pnp/resource.c:pnp_register_irq_resource
```
**Symbols:**

```
ffffffff81647370-ffffffff816473cd: pnp_build_option (STB_LOCAL)
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
In drivers/pnp/resource.c (ffffffff816f6345)
Location: drivers/pnp/resource.c:35
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_register_mem_resource
  - drivers/pnp/resource.c:pnp_register_port_resource
  - drivers/pnp/resource.c:pnp_register_dma_resource
  - drivers/pnp/resource.c:pnp_register_irq_resource
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
In drivers/pnp/resource.c (ffffffff817133a7)
Location: drivers/pnp/resource.c:35
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_register_mem_resource
  - drivers/pnp/resource.c:pnp_register_port_resource
  - drivers/pnp/resource.c:pnp_register_dma_resource
  - drivers/pnp/resource.c:pnp_register_irq_resource
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
In drivers/pnp/resource.c (ffffffff816f4757)
Location: drivers/pnp/resource.c:35
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_register_mem_resource
  - drivers/pnp/resource.c:pnp_register_port_resource
  - drivers/pnp/resource.c:pnp_register_dma_resource
  - drivers/pnp/resource.c:pnp_register_irq_resource
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
In drivers/pnp/resource.c (ffffffff8176ebc7)
Location: drivers/pnp/resource.c:35
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_register_mem_resource
  - drivers/pnp/resource.c:pnp_register_port_resource
  - drivers/pnp/resource.c:pnp_register_dma_resource
  - drivers/pnp/resource.c:pnp_register_irq_resource
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
In drivers/pnp/resource.c (ffffffff818a3e9b)
Location: drivers/pnp/resource.c:35
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_register_mem_resource
  - drivers/pnp/resource.c:pnp_register_port_resource
  - drivers/pnp/resource.c:pnp_register_dma_resource
  - drivers/pnp/resource.c:pnp_register_irq_resource
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
In drivers/pnp/resource.c (ffffffff819ed95b)
Location: drivers/pnp/resource.c:36
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_register_mem_resource
  - drivers/pnp/resource.c:pnp_register_port_resource
  - drivers/pnp/resource.c:pnp_register_dma_resource
  - drivers/pnp/resource.c:pnp_register_irq_resource
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
In drivers/pnp/resource.c (ffffffff81a360db)
Location: drivers/pnp/resource.c:36
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_register_mem_resource
  - drivers/pnp/resource.c:pnp_register_port_resource
  - drivers/pnp/resource.c:pnp_register_dma_resource
  - drivers/pnp/resource.c:pnp_register_irq_resource
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct pnp_option *pnp_build_option(struct pnp_dev *dev, long unsigned int type, unsigned int option_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff81a817a0)
Location: drivers/pnp/resource.c:36
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_register_mem_resource
  - drivers/pnp/resource.c:pnp_register_port_resource
  - drivers/pnp/resource.c:pnp_register_dma_resource
Direct callers:
  - drivers/pnp/resource.c:pnp_register_irq_resource
```
**Symbols:**

```
ffffffff81a81420-ffffffff81a814b6: pnp_build_option (STB_LOCAL)
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
struct pnp_option *pnp_build_option(struct pnp_dev *dev, long unsigned int type, unsigned int option_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffff8000107b4720)
Location: drivers/pnp/resource.c:35
Inline: False
Direct callers:
  - drivers/pnp/resource.c:pnp_register_mem_resource
  - drivers/pnp/resource.c:pnp_register_port_resource
  - drivers/pnp/resource.c:pnp_register_dma_resource
  - drivers/pnp/resource.c:pnp_register_irq_resource
```
**Symbols:**

```
ffff8000107b4720-ffff8000107b478c: pnp_build_option (STB_LOCAL)
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
struct pnp_option *pnp_build_option(struct pnp_dev *dev, long unsigned int type, unsigned int option_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff8160d3d0)
Location: drivers/pnp/resource.c:35
Inline: False
Direct callers:
  - drivers/pnp/resource.c:pnp_register_mem_resource
  - drivers/pnp/resource.c:pnp_register_port_resource
  - drivers/pnp/resource.c:pnp_register_dma_resource
  - drivers/pnp/resource.c:pnp_register_irq_resource
```
**Symbols:**

```
ffffffff8160d3d0-ffffffff8160d42d: pnp_build_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct pnp_option *pnp_build_option(struct pnp_dev *dev, long unsigned int type, unsigned int option_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff81601920)
Location: drivers/pnp/resource.c:35
Inline: False
Direct callers:
  - drivers/pnp/resource.c:pnp_register_mem_resource
  - drivers/pnp/resource.c:pnp_register_port_resource
  - drivers/pnp/resource.c:pnp_register_dma_resource
  - drivers/pnp/resource.c:pnp_register_irq_resource
```
**Symbols:**

```
ffffffff81601920-ffffffff8160197d: pnp_build_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pnp_option *pnp_build_option(struct pnp_dev *dev, long unsigned int type, unsigned int option_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff8163b1b0)
Location: drivers/pnp/resource.c:35
Inline: False
Direct callers:
  - drivers/pnp/resource.c:pnp_register_mem_resource
  - drivers/pnp/resource.c:pnp_register_port_resource
  - drivers/pnp/resource.c:pnp_register_dma_resource
  - drivers/pnp/resource.c:pnp_register_irq_resource
```
**Symbols:**

```
ffffffff8163b1b0-ffffffff8163b20d: pnp_build_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pnp_option *pnp_build_option(struct pnp_dev *dev, long unsigned int type, unsigned int option_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff81655500)
Location: drivers/pnp/resource.c:35
Inline: False
Direct callers:
  - drivers/pnp/resource.c:pnp_register_mem_resource
  - drivers/pnp/resource.c:pnp_register_port_resource
  - drivers/pnp/resource.c:pnp_register_dma_resource
  - drivers/pnp/resource.c:pnp_register_irq_resource
```
**Symbols:**

```
ffffffff81655500-ffffffff8165555d: pnp_build_option (STB_LOCAL)
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
