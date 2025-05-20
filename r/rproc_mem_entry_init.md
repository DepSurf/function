# Function: <code>rproc_mem_entry_init</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct rproc_mem_entry *rproc_mem_entry_init(struct device *dev, void *va, dma_addr_t dma, int len, u32 da, int (*alloc)(struct rproc *, struct rproc_mem_entry *), int (*release)(struct rproc *, struct rproc_mem_entry *), const char *name, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff818f38b0)
Location: drivers/remoteproc/remoteproc_core.c:960
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
**Symbols:**

```
ffffffff818f38b0-ffffffff818f39a0: rproc_mem_entry_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rproc_mem_entry *rproc_mem_entry_init(struct device *dev, void *va, dma_addr_t dma, size_t len, u32 da, int (*alloc)(struct rproc *, struct rproc_mem_entry *), int (*release)(struct rproc *, struct rproc_mem_entry *), const char *name, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819ca110)
Location: drivers/remoteproc/remoteproc_core.c:971
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
**Symbols:**

```
ffffffff819ca110-ffffffff819ca201: rproc_mem_entry_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct rproc_mem_entry *rproc_mem_entry_init(struct device *dev, void *va, dma_addr_t dma, size_t len, u32 da, int (*alloc)(struct rproc *, struct rproc_mem_entry *), int (*release)(struct rproc *, struct rproc_mem_entry *), const char *name, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c95d0)
Location: drivers/remoteproc/remoteproc_core.c:1005
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
**Symbols:**

```
ffffffff819c95d0-ffffffff819c96c1: rproc_mem_entry_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct rproc_mem_entry *rproc_mem_entry_init(struct device *dev, void *va, dma_addr_t dma, size_t len, u32 da, int (*alloc)(struct rproc *, struct rproc_mem_entry *), int (*release)(struct rproc *, struct rproc_mem_entry *), const char *name, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819ae5e0)
Location: drivers/remoteproc/remoteproc_core.c:1011
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
**Symbols:**

```
ffffffff819ae5e0-ffffffff819ae6d3: rproc_mem_entry_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct rproc_mem_entry *rproc_mem_entry_init(struct device *dev, void *va, dma_addr_t dma, size_t len, u32 da, int (*alloc)(struct rproc *, struct rproc_mem_entry *), int (*release)(struct rproc *, struct rproc_mem_entry *), const char *name, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5cbb0)
Location: drivers/remoteproc/remoteproc_core.c:1025
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
**Symbols:**

```
ffffffff81a5cbb0-ffffffff81a5cca3: rproc_mem_entry_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct rproc_mem_entry *rproc_mem_entry_init(struct device *dev, void *va, dma_addr_t dma, size_t len, u32 da, int (*alloc)(struct rproc *, struct rproc_mem_entry *), int (*release)(struct rproc *, struct rproc_mem_entry *), const char *name, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81bccc00)
Location: drivers/remoteproc/remoteproc_core.c:1021
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
**Symbols:**

```
ffffffff81bccc00-ffffffff81bccd20: rproc_mem_entry_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct rproc_mem_entry *rproc_mem_entry_init(struct device *dev, void *va, dma_addr_t dma, size_t len, u32 da, int (*alloc)(struct rproc *, struct rproc_mem_entry *), int (*release)(struct rproc *, struct rproc_mem_entry *), const char *name, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d77380)
Location: drivers/remoteproc/remoteproc_core.c:914
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
**Symbols:**

```
ffffffff81d77380-ffffffff81d774a0: rproc_mem_entry_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct rproc_mem_entry *rproc_mem_entry_init(struct device *dev, void *va, dma_addr_t dma, size_t len, u32 da, int (*alloc)(struct rproc *, struct rproc_mem_entry *), int (*release)(struct rproc *, struct rproc_mem_entry *), const char *name, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de52c0)
Location: drivers/remoteproc/remoteproc_core.c:915
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
**Symbols:**

```
ffffffff81de52c0-ffffffff81de53e0: rproc_mem_entry_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct rproc_mem_entry *rproc_mem_entry_init(struct device *dev, void *va, dma_addr_t dma, size_t len, u32 da, int (*alloc)(struct rproc *, struct rproc_mem_entry *), int (*release)(struct rproc *, struct rproc_mem_entry *), const char *name, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9b410)
Location: drivers/remoteproc/remoteproc_core.c:915
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
**Symbols:**

```
ffffffff81e9b410-ffffffff81e9b55f: rproc_mem_entry_init (STB_GLOBAL)
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
struct rproc_mem_entry *rproc_mem_entry_init(struct device *dev, void *va, dma_addr_t dma, int len, u32 da, int (*alloc)(struct rproc *, struct rproc_mem_entry *), int (*release)(struct rproc *, struct rproc_mem_entry *), const char *name, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffff800010b7f5d8)
Location: drivers/remoteproc/remoteproc_core.c:960
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
**Symbols:**

```
ffff800010b7f5d8-ffff800010b7f6c8: rproc_mem_entry_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct rproc_mem_entry *rproc_mem_entry_init(struct device *dev, void *va, dma_addr_t dma, int len, u32 da, int (*alloc)(struct rproc *, struct rproc_mem_entry *), int (*release)(struct rproc *, struct rproc_mem_entry *), const char *name, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (c0c62d94)
Location: drivers/remoteproc/remoteproc_core.c:960
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
**Symbols:**

```
c0c62d94-c0c62e60: rproc_mem_entry_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct rproc_mem_entry *rproc_mem_entry_init(struct device *dev, void *va, dma_addr_t dma, int len, u32 da, int (*alloc)(struct rproc *, struct rproc_mem_entry *), int (*release)(struct rproc *, struct rproc_mem_entry *), const char *name, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (c000000000c5bf10)
Location: drivers/remoteproc/remoteproc_core.c:960
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
**Symbols:**

```
c000000000c5bf10-c000000000c5bffc: rproc_mem_entry_init (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct rproc_mem_entry *rproc_mem_entry_init(struct device *dev, void *va, dma_addr_t dma, int len, u32 da, int (*alloc)(struct rproc *, struct rproc_mem_entry *), int (*release)(struct rproc *, struct rproc_mem_entry *), const char *name, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81894be0)
Location: drivers/remoteproc/remoteproc_core.c:960
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
**Symbols:**

```
ffffffff81894be0-ffffffff81894cd0: rproc_mem_entry_init (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct rproc_mem_entry *rproc_mem_entry_init(struct device *dev, void *va, dma_addr_t dma, int len, u32 da, int (*alloc)(struct rproc *, struct rproc_mem_entry *), int (*release)(struct rproc *, struct rproc_mem_entry *), const char *name, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81905340)
Location: drivers/remoteproc/remoteproc_core.c:960
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
```
**Symbols:**

```
ffffffff81905340-ffffffff81905430: rproc_mem_entry_init (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int len</code> ➡️ <code>size_t len</code>
</li>
</ul>
</details>
</li>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
