# Function: <code>dma_free_desc_resource</code>

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
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void dma_free_desc_resource(struct virt_dma_desc *vdesc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff81709367)
Location: drivers/dma/lgm/lgm-dma.c:965
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
```
**Symbols:**

```
ffffffff81707860-ffffffff81707897: dma_free_desc_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void dma_free_desc_resource(struct virt_dma_desc *vdesc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff81784d17)
Location: drivers/dma/lgm/lgm-dma.c:965
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
```
**Symbols:**

```
ffffffff81783130-ffffffff81783167: dma_free_desc_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void dma_free_desc_resource(struct virt_dma_desc *vdesc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff818bb777)
Location: drivers/dma/lgm/lgm-dma.c:965
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
```
**Symbols:**

```
ffffffff818b9cc0-ffffffff818b9d02: dma_free_desc_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void dma_free_desc_resource(struct virt_dma_desc *vdesc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a0a427)
Location: drivers/dma/lgm/lgm-dma.c:965
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
```
**Symbols:**

```
ffffffff81a08670-ffffffff81a086b2: dma_free_desc_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void dma_free_desc_resource(struct virt_dma_desc *vdesc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a532a7)
Location: drivers/dma/lgm/lgm-dma.c:965
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
```
**Symbols:**

```
ffffffff81a51700-ffffffff81a51742: dma_free_desc_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void dma_free_desc_resource(struct virt_dma_desc *vdesc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9f057)
Location: drivers/dma/lgm/lgm-dma.c:965
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
```
**Symbols:**

```
ffffffff81a9d450-ffffffff81a9d492: dma_free_desc_resource (STB_LOCAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
