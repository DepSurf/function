# Function: <code>rproc_coredump_add_custom_segment</code>

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
int rproc_coredump_add_custom_segment(struct rproc *rproc, dma_addr_t da, size_t size, void (*dumpfn)(struct rproc *, struct rproc_dump_segment *, void *), void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff818f3830)
Location: drivers/remoteproc/remoteproc_core.c:1534
Inline: False
```
**Symbols:**

```
ffffffff818f3830-ffffffff818f38ac: rproc_coredump_add_custom_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rproc_coredump_add_custom_segment(struct rproc *rproc, dma_addr_t da, size_t size, void (*dumpfn)(struct rproc *, struct rproc_dump_segment *, void *), void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c9850)
Location: drivers/remoteproc/remoteproc_core.c:1563
Inline: False
```
**Symbols:**

```
ffffffff819c9850-ffffffff819c98cc: rproc_coredump_add_custom_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rproc_coredump_add_custom_segment(struct rproc *rproc, dma_addr_t da, size_t size, void (*dumpfn)(struct rproc *, struct rproc_dump_segment *, void *, size_t, size_t), void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_coredump.c (ffffffff819cb1c0)
Location: drivers/remoteproc/remoteproc_coredump.c:78
Inline: False
```
**Symbols:**

```
ffffffff819cb1c0-ffffffff819cb23c: rproc_coredump_add_custom_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rproc_coredump_add_custom_segment(struct rproc *rproc, dma_addr_t da, size_t size, void (*dumpfn)(struct rproc *, struct rproc_dump_segment *, void *, size_t, size_t), void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_coredump.c (ffffffff819b0370)
Location: drivers/remoteproc/remoteproc_coredump.c:78
Inline: False
```
**Symbols:**

```
ffffffff819b0370-ffffffff819b03ec: rproc_coredump_add_custom_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rproc_coredump_add_custom_segment(struct rproc *rproc, dma_addr_t da, size_t size, void (*dumpfn)(struct rproc *, struct rproc_dump_segment *, void *, size_t, size_t), void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81a5e9e0)
Location: drivers/remoteproc/remoteproc_coredump.c:78
Inline: False
```
**Symbols:**

```
ffffffff81a5e9e0-ffffffff81a5ea5c: rproc_coredump_add_custom_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rproc_coredump_add_custom_segment(struct rproc *rproc, dma_addr_t da, size_t size, void (*dumpfn)(struct rproc *, struct rproc_dump_segment *, void *, size_t, size_t), void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81bcec90)
Location: drivers/remoteproc/remoteproc_coredump.c:78
Inline: False
```
**Symbols:**

```
ffffffff81bcec90-ffffffff81bced1b: rproc_coredump_add_custom_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rproc_coredump_add_custom_segment(struct rproc *rproc, dma_addr_t da, size_t size, void (*dumpfn)(struct rproc *, struct rproc_dump_segment *, void *, size_t, size_t), void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81d79c40)
Location: drivers/remoteproc/remoteproc_coredump.c:78
Inline: False
```
**Symbols:**

```
ffffffff81d79c40-ffffffff81d79ccb: rproc_coredump_add_custom_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rproc_coredump_add_custom_segment(struct rproc *rproc, dma_addr_t da, size_t size, void (*dumpfn)(struct rproc *, struct rproc_dump_segment *, void *, size_t, size_t), void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81de7ca0)
Location: drivers/remoteproc/remoteproc_coredump.c:78
Inline: False
```
**Symbols:**

```
ffffffff81de7ca0-ffffffff81de7d2b: rproc_coredump_add_custom_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rproc_coredump_add_custom_segment(struct rproc *rproc, dma_addr_t da, size_t size, void (*dumpfn)(struct rproc *, struct rproc_dump_segment *, void *, size_t, size_t), void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81e9df00)
Location: drivers/remoteproc/remoteproc_coredump.c:79
Inline: False
```
**Symbols:**

```
ffffffff81e9df00-ffffffff81e9dfba: rproc_coredump_add_custom_segment (STB_GLOBAL)
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
int rproc_coredump_add_custom_segment(struct rproc *rproc, dma_addr_t da, size_t size, void (*dumpfn)(struct rproc *, struct rproc_dump_segment *, void *), void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffff800010b7f548)
Location: drivers/remoteproc/remoteproc_core.c:1534
Inline: False
```
**Symbols:**

```
ffff800010b7f548-ffff800010b7f5d4: rproc_coredump_add_custom_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rproc_coredump_add_custom_segment(struct rproc *rproc, dma_addr_t da, size_t size, void (*dumpfn)(struct rproc *, struct rproc_dump_segment *, void *), void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (c0c62d14)
Location: drivers/remoteproc/remoteproc_core.c:1534
Inline: False
```
**Symbols:**

```
c0c62d14-c0c62d94: rproc_coredump_add_custom_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rproc_coredump_add_custom_segment(struct rproc *rproc, dma_addr_t da, size_t size, void (*dumpfn)(struct rproc *, struct rproc_dump_segment *, void *), void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (c000000000c5bd80)
Location: drivers/remoteproc/remoteproc_core.c:1534
Inline: False
```
**Symbols:**

```
c000000000c5bd80-c000000000c5be40: rproc_coredump_add_custom_segment (STB_GLOBAL)
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
int rproc_coredump_add_custom_segment(struct rproc *rproc, dma_addr_t da, size_t size, void (*dumpfn)(struct rproc *, struct rproc_dump_segment *, void *), void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81894b60)
Location: drivers/remoteproc/remoteproc_core.c:1534
Inline: False
```
**Symbols:**

```
ffffffff81894b60-ffffffff81894bdc: rproc_coredump_add_custom_segment (STB_GLOBAL)
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
int rproc_coredump_add_custom_segment(struct rproc *rproc, dma_addr_t da, size_t size, void (*dumpfn)(struct rproc *, struct rproc_dump_segment *, void *), void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819052c0)
Location: drivers/remoteproc/remoteproc_core.c:1534
Inline: False
```
**Symbols:**

```
ffffffff819052c0-ffffffff8190533c: rproc_coredump_add_custom_segment (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void (*dumpfn)(struct rproc *, struct rproc_dump_segment *, void *)</code> ➡️ <code>void (*dumpfn)(struct rproc *, struct rproc_dump_segment *, void *, size_t, size_t)</code>
</li>
</ul>
</details>
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
