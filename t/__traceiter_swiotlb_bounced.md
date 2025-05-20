# Function: <code>__traceiter_swiotlb_bounced</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
int __traceiter_swiotlb_bounced(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size, enum swiotlb_force swiotlb_force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81139d40)
Location: include/trace/events/swiotlb.h:10
Inline: False
```
**Symbols:**

```
ffffffff81139d40-ffffffff81139d9b: __traceiter_swiotlb_bounced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_swiotlb_bounced(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size, enum swiotlb_force swiotlb_force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8113ae60)
Location: include/trace/events/swiotlb.h:10
Inline: False
```
**Symbols:**

```
ffffffff8113ae60-ffffffff8113aeb9: __traceiter_swiotlb_bounced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_swiotlb_bounced(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size, enum swiotlb_force swiotlb_force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8115dd90)
Location: include/trace/events/swiotlb.h:10
Inline: False
```
**Symbols:**

```
ffffffff8115dd90-ffffffff8115dde9: __traceiter_swiotlb_bounced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_swiotlb_bounced(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81187da0)
Location: include/trace/events/swiotlb.h:10
Inline: False
```
**Symbols:**

```
ffffffff81187da0-ffffffff81187dfb: __traceiter_swiotlb_bounced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_swiotlb_bounced(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff811c3af0)
Location: include/trace/events/swiotlb.h:10
Inline: False
```
**Symbols:**

```
ffffffff811c3af0-ffffffff811c3b4b: __traceiter_swiotlb_bounced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_swiotlb_bounced(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff811d6640)
Location: include/trace/events/swiotlb.h:10
Inline: False
```
**Symbols:**

```
ffffffff811d6640-ffffffff811d669b: __traceiter_swiotlb_bounced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_swiotlb_bounced(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff811eb670)
Location: include/trace/events/swiotlb.h:10
Inline: False
```
**Symbols:**

```
ffffffff811eb670-ffffffff811eb6cb: __traceiter_swiotlb_bounced (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>enum swiotlb_force swiotlb_force</code>
</li>
</ul>
</details>
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
