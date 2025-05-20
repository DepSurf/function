# Function: <code>report_addr</code>

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
In kernel/dma/direct.c (ffffffff81118841)
Location: kernel/dma/direct.c:34
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void report_addr(struct device *dev, dma_addr_t dma_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:26
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_resource
  - kernel/dma/direct.c:dma_direct_map_page
```
**Symbols:**

```
ffffffff81122bb0-ffffffff81122c06: report_addr (STB_LOCAL)
ffffffff8112334c-ffffffff8112338a: report_addr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void report_addr(struct device *dev, dma_addr_t dma_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:26
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_resource
  - kernel/dma/direct.c:dma_direct_map_page
```
**Symbols:**

```
ffffffff8112eff0-ffffffff8112f046: report_addr (STB_LOCAL)
ffffffff8112f78c-ffffffff8112f7ca: report_addr.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void report_addr(struct device *dev, dma_addr_t dma_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffff8000101948f8)
Location: kernel/dma/direct.c:26
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_resource
  - kernel/dma/direct.c:dma_direct_map_page
```
**Symbols:**

```
ffff8000101948f8-ffff8000101949ac: report_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void report_addr(struct device *dev, dma_addr_t dma_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (c03e16d4)
Location: kernel/dma/direct.c:26
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_resource
  - kernel/dma/direct.c:dma_direct_map_page
```
**Symbols:**

```
c03e16d4-c03e17e0: report_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void report_addr(struct device *dev, dma_addr_t dma_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (c0000000001f4b70)
Location: kernel/dma/direct.c:26
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_resource
  - kernel/dma/direct.c:dma_direct_map_page
```
**Symbols:**

```
c0000000001f4b70-c0000000001f4c70: report_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void report_addr(struct device *dev, dma_addr_t dma_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffe000126884)
Location: kernel/dma/direct.c:26
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_resource
  - kernel/dma/direct.c:dma_direct_map_page
```
**Symbols:**

```
ffffffe000126884-ffffffe000126922: report_addr (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void report_addr(struct device *dev, dma_addr_t dma_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:26
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_resource
  - kernel/dma/direct.c:dma_direct_map_page
```
**Symbols:**

```
ffffffff811275d0-ffffffff81127626: report_addr (STB_LOCAL)
ffffffff81127dcc-ffffffff81127e0a: report_addr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void report_addr(struct device *dev, dma_addr_t dma_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:26
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_resource
  - kernel/dma/direct.c:dma_direct_map_page
```
**Symbols:**

```
ffffffff8111a030-ffffffff8111a086: report_addr (STB_LOCAL)
ffffffff8111a7cc-ffffffff8111a80a: report_addr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void report_addr(struct device *dev, dma_addr_t dma_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:26
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_resource
  - kernel/dma/direct.c:dma_direct_map_page
```
**Symbols:**

```
ffffffff811254c0-ffffffff81125516: report_addr (STB_LOCAL)
ffffffff81125c5c-ffffffff81125c9a: report_addr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void report_addr(struct device *dev, dma_addr_t dma_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:26
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_resource
  - kernel/dma/direct.c:dma_direct_map_page
```
**Symbols:**

```
ffffffff81131b00-ffffffff81131b56: report_addr (STB_LOCAL)
ffffffff8113229c-ffffffff811322da: report_addr.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
