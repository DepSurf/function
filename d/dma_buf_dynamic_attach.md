# Function: <code>dma_buf_dynamic_attach</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dma_buf_attachment *dma_buf_dynamic_attach(struct dma_buf *dmabuf, struct device *dev, const struct dma_buf_attach_ops *importer_ops, void *importer_priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81825a50)
Location: drivers/dma-buf/dma-buf.c:676
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_attach
```
**Symbols:**

```
ffffffff81825a50-ffffffff81825cbe: dma_buf_dynamic_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dma_buf_attachment *dma_buf_dynamic_attach(struct dma_buf *dmabuf, struct device *dev, const struct dma_buf_attach_ops *importer_ops, void *importer_priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81836430)
Location: drivers/dma-buf/dma-buf.c:689
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_attach
```
**Symbols:**

```
ffffffff81836430-ffffffff8183669e: dma_buf_dynamic_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dma_buf_attachment *dma_buf_dynamic_attach(struct dma_buf *dmabuf, struct device *dev, const struct dma_buf_attach_ops *importer_ops, void *importer_priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-buf.c (ffffffff81818e50)
Location: drivers/dma-buf/dma-buf.c:720
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_attach
```
**Symbols:**

```
ffffffff81818e50-ffffffff818190b2: dma_buf_dynamic_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct dma_buf_attachment *dma_buf_dynamic_attach(struct dma_buf *dmabuf, struct device *dev, const struct dma_buf_attach_ops *importer_ops, void *importer_priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-buf.c (0)
Location: drivers/dma-buf/dma-buf.c:724
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_attach
```
**Symbols:**

```
ffffffff81d0ba9a-ffffffff81d0baaf: dma_buf_dynamic_attach.cold (STB_LOCAL)
ffffffff818a3340-ffffffff818a35b6: dma_buf_dynamic_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct dma_buf_attachment *dma_buf_dynamic_attach(struct dma_buf *dmabuf, struct device *dev, const struct dma_buf_attach_ops *importer_ops, void *importer_priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-buf.c (0)
Location: drivers/dma-buf/dma-buf.c:716
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_attach
```
**Symbols:**

```
ffffffff81ed48c5-ffffffff81ed48da: dma_buf_dynamic_attach.cold (STB_LOCAL)
ffffffff819ed0e0-ffffffff819ed39e: dma_buf_dynamic_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct dma_buf_attachment *dma_buf_dynamic_attach(struct dma_buf *dmabuf, struct device *dev, const struct dma_buf_attach_ops *importer_ops, void *importer_priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-buf.c (0)
Location: drivers/dma-buf/dma-buf.c:894
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_attach
```
**Symbols:**

```
ffffffff8209b6c1-ffffffff8209b6d6: dma_buf_dynamic_attach.cold (STB_LOCAL)
ffffffff81b69fa0-ffffffff81b6a23b: dma_buf_dynamic_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct dma_buf_attachment *dma_buf_dynamic_attach(struct dma_buf *dmabuf, struct device *dev, const struct dma_buf_attach_ops *importer_ops, void *importer_priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-buf.c (0)
Location: drivers/dma-buf/dma-buf.c:894
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_attach
```
**Symbols:**

```
ffffffff8211c5ae-ffffffff8211c5c3: dma_buf_dynamic_attach.cold (STB_LOCAL)
ffffffff81bbd3f0-ffffffff81bbd686: dma_buf_dynamic_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct dma_buf_attachment *dma_buf_dynamic_attach(struct dma_buf *dmabuf, struct device *dev, const struct dma_buf_attach_ops *importer_ops, void *importer_priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/dma-buf.c (0)
Location: drivers/dma-buf/dma-buf.c:889
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_attach
```
**Symbols:**

```
ffffffff821fa44a-ffffffff821fa45f: dma_buf_dynamic_attach.cold (STB_LOCAL)
ffffffff81c11ae0-ffffffff81c11dd4: dma_buf_dynamic_attach (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
