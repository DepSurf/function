# Function: <code>dma_direct_need_sync</code>

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
bool dma_direct_need_sync(struct device *dev, dma_addr_t dma_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8113e520)
Location: kernel/dma/direct.c:548
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_need_sync
```
**Symbols:**

```
ffffffff8113e520-ffffffff8113e55e: dma_direct_need_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool dma_direct_need_sync(struct device *dev, dma_addr_t dma_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81139910)
Location: kernel/dma/direct.c:504
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_need_sync
```
**Symbols:**

```
ffffffff81139910-ffffffff81139979: dma_direct_need_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool dma_direct_need_sync(struct device *dev, dma_addr_t dma_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8113a9f0)
Location: kernel/dma/direct.c:504
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_need_sync
```
**Symbols:**

```
ffffffff8113a9f0-ffffffff8113aa63: dma_direct_need_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool dma_direct_need_sync(struct device *dev, dma_addr_t dma_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8115d930)
Location: kernel/dma/direct.c:546
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_need_sync
```
**Symbols:**

```
ffffffff8115d930-ffffffff8115d9a3: dma_direct_need_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool dma_direct_need_sync(struct device *dev, dma_addr_t dma_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811878d0)
Location: kernel/dma/direct.c:580
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_need_sync
```
**Symbols:**

```
ffffffff811878d0-ffffffff8118794f: dma_direct_need_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool dma_direct_need_sync(struct device *dev, dma_addr_t dma_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811c34e0)
Location: kernel/dma/direct.c:611
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_need_sync
```
**Symbols:**

```
ffffffff811c34e0-ffffffff811c355f: dma_direct_need_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool dma_direct_need_sync(struct device *dev, dma_addr_t dma_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811d6030)
Location: kernel/dma/direct.c:610
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_need_sync
```
**Symbols:**

```
ffffffff811d6030-ffffffff811d60af: dma_direct_need_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool dma_direct_need_sync(struct device *dev, dma_addr_t dma_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:639
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_need_sync
```
**Symbols:**

```
ffffffff821b48e9-ffffffff821b48fe: dma_direct_need_sync.cold (STB_LOCAL)
ffffffff811eaff0-ffffffff811eb0b6: dma_direct_need_sync (STB_GLOBAL)
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
