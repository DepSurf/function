# Function: <code>pcpu_alloc_pages</code>

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
In mm/percpu.c (ffffffff811b0a87)
Location: mm/percpu-vm.c:82
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffff811c9ca7)
Location: mm/percpu-vm.c:82
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffff811d9d9e)
Location: mm/percpu-vm.c:82
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffff811e3416)
Location: mm/percpu-vm.c:81
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffff811f8ce0)
Location: mm/percpu-vm.c:82
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffff8121a6ea)
Location: mm/percpu-vm.c:82
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffff8122d69a)
Location: mm/percpu-vm.c:82
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffff8123d3c6)
Location: mm/percpu-vm.c:81
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffff8124b816)
Location: mm/percpu-vm.c:81
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/percpu.c (ffffffff812797a0)
Location: mm/percpu-vm.c:81
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_populate_chunk
```
**Symbols:**

```
ffffffff812797a0-ffffffff81279925: pcpu_alloc_pages.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/percpu.c (ffffffff81284010)
Location: mm/percpu-vm.c:81
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_populate_chunk
```
**Symbols:**

```
ffffffff81284010-ffffffff81284195: pcpu_alloc_pages.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/percpu.c (ffffffff81288c50)
Location: mm/percpu-vm.c:82
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_populate_chunk
```
**Symbols:**

```
ffffffff81288c50-ffffffff81288dd5: pcpu_alloc_pages.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/percpu.c (ffffffff812c86d0)
Location: mm/percpu-vm.c:82
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_populate_chunk
```
**Symbols:**

```
ffffffff812c86d0-ffffffff812c887a: pcpu_alloc_pages.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/percpu.c (ffffffff81326080)
Location: mm/percpu-vm.c:82
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_populate_chunk
```
**Symbols:**

```
ffffffff81326080-ffffffff81326243: pcpu_alloc_pages.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/percpu.c (ffffffff8139c7d0)
Location: mm/percpu-vm.c:82
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_populate_chunk
```
**Symbols:**

```
ffffffff8139c7d0-ffffffff8139c9be: pcpu_alloc_pages.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/percpu.c (ffffffff813cf8b0)
Location: mm/percpu-vm.c:82
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_populate_chunk
```
**Symbols:**

```
ffffffff813cf8b0-ffffffff813cfa9e: pcpu_alloc_pages.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/percpu.c (ffffffff813fa4b0)
Location: mm/percpu-vm.c:82
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_populate_chunk
```
**Symbols:**

```
ffffffff813fa4b0-ffffffff813fa69e: pcpu_alloc_pages.isra.0 (STB_LOCAL)
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
In mm/percpu.c (ffff8000102e1ad4)
Location: mm/percpu-vm.c:81
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (c0505cb4)
Location: mm/percpu-vm.c:81
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (c0000000003a1970)
Location: mm/percpu-vm.c:81
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffe0001f888c)
Location: mm/percpu-vm.c:81
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffff81243e66)
Location: mm/percpu-vm.c:81
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffff81236e36)
Location: mm/percpu-vm.c:81
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffff81241c06)
Location: mm/percpu-vm.c:81
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffff812513a6)
Location: mm/percpu-vm.c:81
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
</details>
</li>
</ul>

## Differences
