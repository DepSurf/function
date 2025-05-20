# Function: <code>dma_direct_set_offset</code>

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
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dma_direct_set_offset(struct device *dev, phys_addr_t cpu_start, dma_addr_t dma_start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:526
Inline: False
```
**Symbols:**

```
ffffffff81be3619-ffffffff81be3630: dma_direct_set_offset.cold (STB_LOCAL)
ffffffff81139980-ffffffff81139a14: dma_direct_set_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dma_direct_set_offset(struct device *dev, phys_addr_t cpu_start, dma_addr_t dma_start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:526
Inline: False
```
**Symbols:**

```
ffffffff81bd54d4-ffffffff81bd54eb: dma_direct_set_offset.cold (STB_LOCAL)
ffffffff8113aa70-ffffffff8113ab04: dma_direct_set_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dma_direct_set_offset(struct device *dev, phys_addr_t cpu_start, dma_addr_t dma_start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:568
Inline: False
```
**Symbols:**

```
ffffffff81cb04b2-ffffffff81cb04c9: dma_direct_set_offset.cold (STB_LOCAL)
ffffffff8115d9b0-ffffffff8115da44: dma_direct_set_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dma_direct_set_offset(struct device *dev, phys_addr_t cpu_start, dma_addr_t dma_start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:602
Inline: False
```
**Symbols:**

```
ffffffff81e610fc-ffffffff81e61112: dma_direct_set_offset.cold (STB_LOCAL)
ffffffff81187950-ffffffff811879da: dma_direct_set_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dma_direct_set_offset(struct device *dev, phys_addr_t cpu_start, dma_addr_t dma_start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811c3570)
Location: kernel/dma/direct.c:633
Inline: False
```
**Symbols:**

```
ffffffff811c3570-ffffffff811c3609: dma_direct_set_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dma_direct_set_offset(struct device *dev, phys_addr_t cpu_start, dma_addr_t dma_start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811d60c0)
Location: kernel/dma/direct.c:632
Inline: False
```
**Symbols:**

```
ffffffff811d60c0-ffffffff811d6159: dma_direct_set_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dma_direct_set_offset(struct device *dev, phys_addr_t cpu_start, dma_addr_t dma_start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811eb0d0)
Location: kernel/dma/direct.c:661
Inline: False
```
**Symbols:**

```
ffffffff811eb0d0-ffffffff811eb18c: dma_direct_set_offset (STB_GLOBAL)
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
