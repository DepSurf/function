# Function: <code>vchan_find_desc</code>

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
<summary>In <code>5.13</code>: ✅</summary>

```c
struct virt_dma_desc *vchan_find_desc(struct virt_dma_chan *vc, dma_cookie_t cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff81706a50)
Location: drivers/dma/virt-dma.c:66
Inline: False
```
**Symbols:**

```
ffffffff81706a50-ffffffff81706a89: vchan_find_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct virt_dma_desc *vchan_find_desc(struct virt_dma_chan *vc, dma_cookie_t cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff81782310)
Location: drivers/dma/virt-dma.c:66
Inline: False
```
**Symbols:**

```
ffffffff81782310-ffffffff81782349: vchan_find_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct virt_dma_desc *vchan_find_desc(struct virt_dma_chan *vc, dma_cookie_t cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff818b8d20)
Location: drivers/dma/virt-dma.c:66
Inline: False
```
**Symbols:**

```
ffffffff818b8d20-ffffffff818b8d6d: vchan_find_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct virt_dma_desc *vchan_find_desc(struct virt_dma_chan *vc, dma_cookie_t cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff81a06390)
Location: drivers/dma/virt-dma.c:66
Inline: False
Direct callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_tx_status
```
**Symbols:**

```
ffffffff81a06390-ffffffff81a063dd: vchan_find_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct virt_dma_desc *vchan_find_desc(struct virt_dma_chan *vc, dma_cookie_t cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff81a4f220)
Location: drivers/dma/virt-dma.c:66
Inline: False
Direct callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_tx_status
```
**Symbols:**

```
ffffffff81a4f220-ffffffff81a4f26d: vchan_find_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct virt_dma_desc *vchan_find_desc(struct virt_dma_chan *vc, dma_cookie_t cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff81a9aec0)
Location: drivers/dma/virt-dma.c:66
Inline: False
Direct callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_tx_status
```
**Symbols:**

```
ffffffff81a9aec0-ffffffff81a9af0d: vchan_find_desc (STB_GLOBAL)
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
struct virt_dma_desc *vchan_find_desc(struct virt_dma_chan *vc, dma_cookie_t cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffff8000107fe348)
Location: drivers/dma/virt-dma.c:66
Inline: False
```
**Symbols:**

```
ffff8000107fe348-ffff8000107fe3b4: vchan_find_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct virt_dma_desc *vchan_find_desc(struct virt_dma_chan *vc, dma_cookie_t cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (c091f654)
Location: drivers/dma/virt-dma.c:66
Inline: False
```
**Symbols:**

```
c091f654-c091f6a0: vchan_find_desc (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
