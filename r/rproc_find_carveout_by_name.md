# Function: <code>rproc_find_carveout_by_name</code>

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
struct rproc_mem_entry *rproc_find_carveout_by_name(struct rproc *rproc, const char *name, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff818f4360)
Location: drivers/remoteproc/remoteproc_core.c:244
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
```
**Symbols:**

```
ffffffff818f4360-ffffffff818f442b: rproc_find_carveout_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rproc_mem_entry *rproc_find_carveout_by_name(struct rproc *rproc, const char *name, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819ca520)
Location: drivers/remoteproc/remoteproc_core.c:248
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
  - drivers/remoteproc/remoteproc_virtio.c:rp_find_vq
```
**Symbols:**

```
ffffffff819ca520-ffffffff819ca5eb: rproc_find_carveout_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct rproc_mem_entry *rproc_find_carveout_by_name(struct rproc *rproc, const char *name, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c99a0)
Location: drivers/remoteproc/remoteproc_core.c:248
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
  - drivers/remoteproc/remoteproc_virtio.c:rp_find_vq
```
**Symbols:**

```
ffffffff819c99a0-ffffffff819c9a6b: rproc_find_carveout_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct rproc_mem_entry *rproc_find_carveout_by_name(struct rproc *rproc, const char *name, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819ae9b0)
Location: drivers/remoteproc/remoteproc_core.c:251
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
  - drivers/remoteproc/remoteproc_virtio.c:rp_find_vq
```
**Symbols:**

```
ffffffff819ae9b0-ffffffff819aea7b: rproc_find_carveout_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct rproc_mem_entry *rproc_find_carveout_by_name(struct rproc *rproc, const char *name, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5cf80)
Location: drivers/remoteproc/remoteproc_core.c:253
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
  - drivers/remoteproc/remoteproc_virtio.c:rp_find_vq
```
**Symbols:**

```
ffffffff81a5cf80-ffffffff81a5d04b: rproc_find_carveout_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct rproc_mem_entry *rproc_find_carveout_by_name(struct rproc *rproc, const char *name, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81bcd020)
Location: drivers/remoteproc/remoteproc_core.c:253
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
  - drivers/remoteproc/remoteproc_virtio.c:rp_find_vq
```
**Symbols:**

```
ffffffff81bcd020-ffffffff81bcd139: rproc_find_carveout_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct rproc_mem_entry *rproc_find_carveout_by_name(struct rproc *rproc, const char *name, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d788f0)
Location: drivers/remoteproc/remoteproc_core.c:252
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
  - drivers/remoteproc/remoteproc_virtio.c:rp_find_vq
```
**Symbols:**

```
ffffffff81d788f0-ffffffff81d78a09: rproc_find_carveout_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct rproc_mem_entry *rproc_find_carveout_by_name(struct rproc *rproc, const char *name, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de6840)
Location: drivers/remoteproc/remoteproc_core.c:252
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
  - drivers/remoteproc/remoteproc_virtio.c:rp_find_vq
```
**Symbols:**

```
ffffffff81de6840-ffffffff81de6959: rproc_find_carveout_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct rproc_mem_entry *rproc_find_carveout_by_name(struct rproc *rproc, const char *name, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9ca20)
Location: drivers/remoteproc/remoteproc_core.c:252
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
  - drivers/remoteproc/remoteproc_virtio.c:rp_find_vq
```
**Symbols:**

```
ffffffff81e9ca20-ffffffff81e9cb39: rproc_find_carveout_by_name (STB_GLOBAL)
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
struct rproc_mem_entry *rproc_find_carveout_by_name(struct rproc *rproc, const char *name, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffff800010b80430)
Location: drivers/remoteproc/remoteproc_core.c:244
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
```
**Symbols:**

```
ffff800010b80430-ffff800010b80518: rproc_find_carveout_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct rproc_mem_entry *rproc_find_carveout_by_name(struct rproc *rproc, const char *name, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (c0c63a50)
Location: drivers/remoteproc/remoteproc_core.c:244
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
```
**Symbols:**

```
c0c63a50-c0c63b0c: rproc_find_carveout_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct rproc_mem_entry *rproc_find_carveout_by_name(struct rproc *rproc, const char *name, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (c000000000c5c9c0)
Location: drivers/remoteproc/remoteproc_core.c:244
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
```
**Symbols:**

```
c000000000c5c9c0-c000000000c5cca4: rproc_find_carveout_by_name (STB_GLOBAL)
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
struct rproc_mem_entry *rproc_find_carveout_by_name(struct rproc *rproc, const char *name, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81895690)
Location: drivers/remoteproc/remoteproc_core.c:244
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
```
**Symbols:**

```
ffffffff81895690-ffffffff8189575b: rproc_find_carveout_by_name (STB_GLOBAL)
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
struct rproc_mem_entry *rproc_find_carveout_by_name(struct rproc *rproc, const char *name, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81905df0)
Location: drivers/remoteproc/remoteproc_core.c:244
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
```
**Symbols:**

```
ffffffff81905df0-ffffffff81905ebb: rproc_find_carveout_by_name (STB_GLOBAL)
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
