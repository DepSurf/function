# Function: <code>sync_file_create</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sync_file *sync_file_create(struct fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff815fd2d0)
Location: drivers/dma-buf/sync_file.c:75
Inline: False
```
**Symbols:**

```
ffffffff815fd2d0-ffffffff815fd388: sync_file_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sync_file *sync_file_create(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff8162b670)
Location: drivers/dma-buf/sync_file.c:74
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff8162b670-ffffffff8162b727: sync_file_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sync_file *sync_file_create(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff81640c80)
Location: drivers/dma-buf/sync_file.c:73
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff81640c80-ffffffff81640ca6: sync_file_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sync_file *sync_file_create(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff816a9ad0)
Location: drivers/dma-buf/sync_file.c:73
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff816a9ad0-ffffffff816a9afc: sync_file_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sync_file *sync_file_create(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff816e6000)
Location: drivers/dma-buf/sync_file.c:73
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff816e6000-ffffffff816e602c: sync_file_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sync_file *sync_file_create(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff81709390)
Location: drivers/dma-buf/sync_file.c:73
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff81709390-ffffffff817093bc: sync_file_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sync_file *sync_file_create(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff81744b50)
Location: drivers/dma-buf/sync_file.c:64
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff81744b50-ffffffff81744b7c: sync_file_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sync_file *sync_file_create(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff81768d00)
Location: drivers/dma-buf/sync_file.c:64
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff81768d00-ffffffff81768d2d: sync_file_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sync_file *sync_file_create(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff8182ac90)
Location: drivers/dma-buf/sync_file.c:64
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl_create_fence
```
**Symbols:**

```
ffffffff8182ac90-ffffffff8182acfb: sync_file_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sync_file *sync_file_create(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff8183ba70)
Location: drivers/dma-buf/sync_file.c:64
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl_create_fence
```
**Symbols:**

```
ffffffff8183ba70-ffffffff8183badb: sync_file_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sync_file *sync_file_create(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff8181eb60)
Location: drivers/dma-buf/sync_file.c:64
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff8181eb60-ffffffff8181ebcb: sync_file_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sync_file *sync_file_create(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff818a91f0)
Location: drivers/dma-buf/sync_file.c:64
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff818a91f0-ffffffff818a925b: sync_file_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sync_file *sync_file_create(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff819f3170)
Location: drivers/dma-buf/sync_file.c:65
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff819f3170-ffffffff819f31e7: sync_file_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sync_file *sync_file_create(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff81b70ee0)
Location: drivers/dma-buf/sync_file.c:65
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff81b70ee0-ffffffff81b70f57: sync_file_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sync_file *sync_file_create(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff81bc4710)
Location: drivers/dma-buf/sync_file.c:65
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff81bc4710-ffffffff81bc4787: sync_file_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sync_file *sync_file_create(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff81c18ec0)
Location: drivers/dma-buf/sync_file.c:65
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/gpu/drm/drm_atomic_uapi.c:prepare_signaling
  - drivers/gpu/drm/drm_atomic_uapi.c:prepare_signaling
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_handle_to_fd_ioctl
```
**Symbols:**

```
ffffffff81c18ec0-ffffffff81c18f37: sync_file_create (STB_GLOBAL)
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
struct sync_file *sync_file_create(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffff800010969ee8)
Location: drivers/dma-buf/sync_file.c:64
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffff800010969ee8-ffff800010969f2c: sync_file_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sync_file *sync_file_create(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (c0a3ffb4)
Location: drivers/dma-buf/sync_file.c:64
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
c0a3ffb4-c0a3fff4: sync_file_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sync_file *sync_file_create(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (c000000000a22a10)
Location: drivers/dma-buf/sync_file.c:64
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
c000000000a22a10-c000000000a22a74: sync_file_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sync_file *sync_file_create(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffe0005d58da)
Location: drivers/dma-buf/sync_file.c:64
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffe0005d58da-ffffffe0005d5912: sync_file_create (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct sync_file *sync_file_create(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff8171d3f0)
Location: drivers/dma-buf/sync_file.c:64
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff8171d3f0-ffffffff8171d41d: sync_file_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sync_file *sync_file_create(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff816f6850)
Location: drivers/dma-buf/sync_file.c:64
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff816f6850-ffffffff816f687d: sync_file_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sync_file *sync_file_create(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff8175c1c0)
Location: drivers/dma-buf/sync_file.c:64
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff8175c1c0-ffffffff8175c1ed: sync_file_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sync_file *sync_file_create(struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_file.c (ffffffff81777860)
Location: drivers/dma-buf/sync_file.c:64
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff81777860-ffffffff8177788d: sync_file_create (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct fence *fence</code> ➡️ <code>struct dma_fence *fence</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
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
