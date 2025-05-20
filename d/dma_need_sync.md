# Function: <code>dma_need_sync</code>

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
bool dma_need_sync(struct device *dev, dma_addr_t dma_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8113d3b0)
Location: kernel/dma/mapping.c:400
Inline: False
```
**Symbols:**

```
ffffffff8113d3b0-ffffffff8113d3f4: dma_need_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool dma_need_sync(struct device *dev, dma_addr_t dma_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81137c40)
Location: kernel/dma/mapping.c:629
Inline: False
```
**Symbols:**

```
ffffffff81137c40-ffffffff81137c84: dma_need_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool dma_need_sync(struct device *dev, dma_addr_t dma_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81138c80)
Location: kernel/dma/mapping.c:719
Inline: False
```
**Symbols:**

```
ffffffff81138c80-ffffffff81138cbe: dma_need_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool dma_need_sync(struct device *dev, dma_addr_t dma_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8115bb90)
Location: kernel/dma/mapping.c:784
Inline: False
```
**Symbols:**

```
ffffffff8115bb90-ffffffff8115bbce: dma_need_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool dma_need_sync(struct device *dev, dma_addr_t dma_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81185710)
Location: kernel/dma/mapping.c:776
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_map
```
**Symbols:**

```
ffffffff81185710-ffffffff8118576c: dma_need_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool dma_need_sync(struct device *dev, dma_addr_t dma_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811c1060)
Location: kernel/dma/mapping.c:824
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_map
```
**Symbols:**

```
ffffffff811c1060-ffffffff811c10bf: dma_need_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool dma_need_sync(struct device *dev, dma_addr_t dma_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811d3ad0)
Location: kernel/dma/mapping.c:828
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_map
```
**Symbols:**

```
ffffffff811d3ad0-ffffffff811d3b2f: dma_need_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool dma_need_sync(struct device *dev, dma_addr_t dma_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811e8770)
Location: kernel/dma/mapping.c:844
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_map
```
**Symbols:**

```
ffffffff811e8770-ffffffff811e87cf: dma_need_sync (STB_GLOBAL)
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
