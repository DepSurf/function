# Function: <code>ldma_chan_desc_hw_cfg</code>

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
void ldma_chan_desc_hw_cfg(struct ldma_chan *c, dma_addr_t desc_base, int desc_num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff817077c0)
Location: drivers/dma/lgm/lgm-dma.c:635
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
  - drivers/dma/lgm/lgm-dma.c:ldma_issue_pending
  - drivers/dma/lgm/lgm-dma.c:ldma_dev_init
```
**Symbols:**

```
ffffffff817077c0-ffffffff81707860: ldma_chan_desc_hw_cfg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ldma_chan_desc_hw_cfg(struct ldma_chan *c, dma_addr_t desc_base, int desc_num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff81783090)
Location: drivers/dma/lgm/lgm-dma.c:635
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
  - drivers/dma/lgm/lgm-dma.c:ldma_issue_pending
```
**Symbols:**

```
ffffffff81783090-ffffffff81783130: ldma_chan_desc_hw_cfg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ldma_chan_desc_hw_cfg(struct ldma_chan *c, dma_addr_t desc_base, int desc_num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff818b9c10)
Location: drivers/dma/lgm/lgm-dma.c:635
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
  - drivers/dma/lgm/lgm-dma.c:ldma_issue_pending
```
**Symbols:**

```
ffffffff818b9c10-ffffffff818b9cbe: ldma_chan_desc_hw_cfg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ldma_chan_desc_hw_cfg(struct ldma_chan *c, dma_addr_t desc_base, int desc_num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a085b0)
Location: drivers/dma/lgm/lgm-dma.c:635
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
  - drivers/dma/lgm/lgm-dma.c:ldma_issue_pending
```
**Symbols:**

```
ffffffff81a085b0-ffffffff81a0865e: ldma_chan_desc_hw_cfg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ldma_chan_desc_hw_cfg(struct ldma_chan *c, dma_addr_t desc_base, int desc_num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a514f0)
Location: drivers/dma/lgm/lgm-dma.c:635
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
  - drivers/dma/lgm/lgm-dma.c:ldma_issue_pending
```
**Symbols:**

```
ffffffff81a514f0-ffffffff81a515a1: ldma_chan_desc_hw_cfg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ldma_chan_desc_hw_cfg(struct ldma_chan *c, dma_addr_t desc_base, int desc_num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9d240)
Location: drivers/dma/lgm/lgm-dma.c:635
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
  - drivers/dma/lgm/lgm-dma.c:ldma_issue_pending
```
**Symbols:**

```
ffffffff81a9d240-ffffffff81a9d2f1: ldma_chan_desc_hw_cfg (STB_LOCAL)
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
