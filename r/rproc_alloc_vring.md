# Function: <code>rproc_alloc_vring</code>

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
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int rproc_alloc_vring(struct rproc_vdev *rvdev, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:317
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffffffff818f56d4-ffffffff818f570b: rproc_alloc_vring.cold (STB_LOCAL)
ffffffff818f4580-ffffffff818f470e: rproc_alloc_vring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int rproc_alloc_vring(struct rproc_vdev *rvdev, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:321
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffffffff819cbf4d-ffffffff819cbf84: rproc_alloc_vring.cold (STB_LOCAL)
ffffffff819ca730-ffffffff819ca8bd: rproc_alloc_vring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int rproc_alloc_vring(struct rproc_vdev *rvdev, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:321
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffffffff81c2e6ba-ffffffff81c2e6f1: rproc_alloc_vring.cold (STB_LOCAL)
ffffffff819c9bb0-ffffffff819c9d3d: rproc_alloc_vring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int rproc_alloc_vring(struct rproc_vdev *rvdev, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:324
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffffffff81c2074d-ffffffff81c20784: rproc_alloc_vring.cold (STB_LOCAL)
ffffffff819aebc0-ffffffff819aed4c: rproc_alloc_vring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int rproc_alloc_vring(struct rproc_vdev *rvdev, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:326
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffffffff81d320ae-ffffffff81d320e5: rproc_alloc_vring.cold (STB_LOCAL)
ffffffff81a5d190-ffffffff81a5d343: rproc_alloc_vring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int rproc_alloc_vring(struct rproc_vdev *rvdev, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:326
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffffffff81efe5c6-ffffffff81efe5fd: rproc_alloc_vring.cold (STB_LOCAL)
ffffffff81bcd290-ffffffff81bcd453: rproc_alloc_vring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rproc_alloc_vring(struct rproc_vdev *rvdev, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d78bd0)
Location: drivers/remoteproc/remoteproc_core.c:325
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
```
**Symbols:**

```
ffffffff81d78bd0-ffffffff81d78dca: rproc_alloc_vring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rproc_alloc_vring(struct rproc_vdev *rvdev, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de6b20)
Location: drivers/remoteproc/remoteproc_core.c:325
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
```
**Symbols:**

```
ffffffff81de6b20-ffffffff81de6d1a: rproc_alloc_vring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rproc_alloc_vring(struct rproc_vdev *rvdev, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9cd00)
Location: drivers/remoteproc/remoteproc_core.c:325
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
```
**Symbols:**

```
ffffffff81e9cd00-ffffffff81e9cefa: rproc_alloc_vring (STB_GLOBAL)
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
int rproc_alloc_vring(struct rproc_vdev *rvdev, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffff800010b806d0)
Location: drivers/remoteproc/remoteproc_core.c:317
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffff800010b806d0-ffff800010b80898: rproc_alloc_vring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rproc_alloc_vring(struct rproc_vdev *rvdev, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (c0c63cc4)
Location: drivers/remoteproc/remoteproc_core.c:317
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
c0c63cc4-c0c63e88: rproc_alloc_vring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rproc_alloc_vring(struct rproc_vdev *rvdev, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (c000000000c5ceb0)
Location: drivers/remoteproc/remoteproc_core.c:317
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
c000000000c5ceb0-c000000000c5d0e8: rproc_alloc_vring (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int rproc_alloc_vring(struct rproc_vdev *rvdev, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:317
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffffffff81896a04-ffffffff81896a3b: rproc_alloc_vring.cold (STB_LOCAL)
ffffffff818958b0-ffffffff81895a3e: rproc_alloc_vring (STB_GLOBAL)
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
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int rproc_alloc_vring(struct rproc_vdev *rvdev, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:317
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffffffff81907164-ffffffff8190719b: rproc_alloc_vring.cold (STB_LOCAL)
ffffffff81906010-ffffffff8190619e: rproc_alloc_vring (STB_GLOBAL)
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
