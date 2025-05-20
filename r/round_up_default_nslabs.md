# Function: <code>round_up_default_nslabs</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool round_up_default_nslabs();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff811c43a7)
Location: kernel/dma/swiotlb.c:107
Inline: True
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_adjust_nareas
  - kernel/dma/swiotlb.c:swiotlb_adjust_size
```
**Symbols:**

```
ffffffff811c4380-ffffffff811c440c: round_up_default_nslabs (STB_LOCAL)
ffffffff8205a911-ffffffff8205a92f: round_up_default_nslabs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool round_up_default_nslabs();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff811d7547)
Location: kernel/dma/swiotlb.c:105
Inline: True
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_adjust_nareas
  - kernel/dma/swiotlb.c:swiotlb_adjust_size
```
**Symbols:**

```
ffffffff811d7520-ffffffff811d75ac: round_up_default_nslabs (STB_LOCAL)
ffffffff820d9185-ffffffff820d91a3: round_up_default_nslabs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool round_up_default_nslabs();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff811ec7f7)
Location: kernel/dma/swiotlb.c:128
Inline: True
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_adjust_nareas
  - kernel/dma/swiotlb.c:swiotlb_adjust_size
```
**Symbols:**

```
ffffffff811ec7d0-ffffffff811ec85c: round_up_default_nslabs (STB_LOCAL)
ffffffff821b4974-ffffffff821b4992: round_up_default_nslabs.cold (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
