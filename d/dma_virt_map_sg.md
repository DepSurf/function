# Function: <code>dma_virt_map_sg</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int dma_virt_map_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dma-virt.c (ffffffff818ebee0)
Location: lib/dma-virt.c:38
Inline: True
```
**Symbols:**

```
ffffffff818ebee0-ffffffff818ebf45: dma_virt_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int dma_virt_map_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dma-virt.c (ffffffff81971ed0)
Location: lib/dma-virt.c:39
Inline: True
```
**Symbols:**

```
ffffffff81971ed0-ffffffff81971f35: dma_virt_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int dma_virt_map_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/virt.c (ffffffff8110d230)
Location: kernel/dma/virt.c:37
Inline: True
```
**Symbols:**

```
ffffffff8110d230-ffffffff8110d29a: dma_virt_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int dma_virt_map_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/virt.c (ffffffff81118f00)
Location: kernel/dma/virt.c:37
Inline: True
```
**Symbols:**

```
ffffffff81118f00-ffffffff81118f6a: dma_virt_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int dma_virt_map_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/virt.c (ffffffff811238c0)
Location: kernel/dma/virt.c:37
Inline: True
```
**Symbols:**

```
ffffffff811238c0-ffffffff81123923: dma_virt_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int dma_virt_map_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/virt.c (ffffffff8112f850)
Location: kernel/dma/virt.c:37
Inline: True
```
**Symbols:**

```
ffffffff8112f850-ffffffff8112f8b3: dma_virt_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dma_virt_map_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/virt.c (ffffffff8113e610)
Location: kernel/dma/virt.c:37
Inline: False
```
**Symbols:**

```
ffffffff8113e610-ffffffff8113e673: dma_virt_map_sg (STB_LOCAL)
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int dma_virt_map_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/virt.c (ffff800010195f58)
Location: kernel/dma/virt.c:37
Inline: True
```
**Symbols:**

```
ffff800010195f58-ffff800010195ff4: dma_virt_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int dma_virt_map_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/virt.c (c03e27f4)
Location: kernel/dma/virt.c:37
Inline: True
```
**Symbols:**

```
c03e27f4-c03e2868: dma_virt_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dma_virt_map_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/virt.c (c0000000001f5fc0)
Location: kernel/dma/virt.c:37
Inline: False
```
**Symbols:**

```
c0000000001f5fc0-c0000000001f6088: dma_virt_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int dma_virt_map_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/virt.c (ffffffe0001279be)
Location: kernel/dma/virt.c:37
Inline: True
```
**Symbols:**

```
ffffffe0001279be-ffffffe000127a36: dma_virt_map_sg (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int dma_virt_map_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/virt.c (ffffffff81128000)
Location: kernel/dma/virt.c:37
Inline: True
```
**Symbols:**

```
ffffffff81128000-ffffffff81128063: dma_virt_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int dma_virt_map_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/virt.c (ffffffff8111a890)
Location: kernel/dma/virt.c:37
Inline: True
```
**Symbols:**

```
ffffffff8111a890-ffffffff8111a8f3: dma_virt_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int dma_virt_map_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/virt.c (ffffffff81125d20)
Location: kernel/dma/virt.c:37
Inline: True
```
**Symbols:**

```
ffffffff81125d20-ffffffff81125d83: dma_virt_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int dma_virt_map_sg(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/virt.c (ffffffff81132360)
Location: kernel/dma/virt.c:37
Inline: True
```
**Symbols:**

```
ffffffff81132360-ffffffff811323c3: dma_virt_map_sg (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
