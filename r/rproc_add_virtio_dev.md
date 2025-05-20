# Function: <code>rproc_add_virtio_dev</code>

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
int rproc_add_virtio_dev(struct rproc_vdev *rvdev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: drivers/remoteproc/remoteproc_virtio.c:329
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_do_start
```
**Symbols:**

```
ffffffff818f73f1-ffffffff818f7482: rproc_add_virtio_dev.cold (STB_LOCAL)
ffffffff818f72a0-ffffffff818f7380: rproc_add_virtio_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int rproc_add_virtio_dev(struct rproc_vdev *rvdev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: drivers/remoteproc/remoteproc_virtio.c:330
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_do_start
```
**Symbols:**

```
ffffffff819cd559-ffffffff819cd60e: rproc_add_virtio_dev.cold (STB_LOCAL)
ffffffff819cd3d0-ffffffff819cd4ec: rproc_add_virtio_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int rproc_add_virtio_dev(struct rproc_vdev *rvdev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: drivers/remoteproc/remoteproc_virtio.c:330
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_do_start
```
**Symbols:**

```
ffffffff81c2ee63-ffffffff81c2ef18: rproc_add_virtio_dev.cold (STB_LOCAL)
ffffffff819ccc20-ffffffff819ccd3c: rproc_add_virtio_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int rproc_add_virtio_dev(struct rproc_vdev *rvdev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: drivers/remoteproc/remoteproc_virtio.c:330
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_do_start
```
**Symbols:**

```
ffffffff81c21136-ffffffff81c211eb: rproc_add_virtio_dev.cold (STB_LOCAL)
ffffffff819b1dd0-ffffffff819b1eea: rproc_add_virtio_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int rproc_add_virtio_dev(struct rproc_vdev *rvdev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: drivers/remoteproc/remoteproc_virtio.c:330
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_do_start
```
**Symbols:**

```
ffffffff81d32b57-ffffffff81d32c0c: rproc_add_virtio_dev.cold (STB_LOCAL)
ffffffff81a60530-ffffffff81a6064a: rproc_add_virtio_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int rproc_add_virtio_dev(struct rproc_vdev *rvdev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: drivers/remoteproc/remoteproc_virtio.c:342
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_do_start
```
**Symbols:**

```
ffffffff81eff032-ffffffff81eff0d7: rproc_add_virtio_dev.cold (STB_LOCAL)
ffffffff81bd0a60-ffffffff81bd0b88: rproc_add_virtio_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rproc_add_virtio_dev(struct rproc_vdev *rvdev, int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81d7be20)
Location: drivers/remoteproc/remoteproc_virtio.c:367
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_vdev_do_start
```
**Symbols:**

```
ffffffff81d7be20-ffffffff81d7bfc3: rproc_add_virtio_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rproc_add_virtio_dev(struct rproc_vdev *rvdev, int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81de9fe0)
Location: drivers/remoteproc/remoteproc_virtio.c:367
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_vdev_do_start
```
**Symbols:**

```
ffffffff81de9fe0-ffffffff81dea183: rproc_add_virtio_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rproc_add_virtio_dev(struct rproc_vdev *rvdev, int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81ea0220)
Location: drivers/remoteproc/remoteproc_virtio.c:367
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_vdev_do_start
```
**Symbols:**

```
ffffffff81ea0220-ffffffff81ea03f2: rproc_add_virtio_dev (STB_LOCAL)
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
int rproc_add_virtio_dev(struct rproc_vdev *rvdev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (ffff800010b83588)
Location: drivers/remoteproc/remoteproc_virtio.c:329
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_do_start
```
**Symbols:**

```
ffff800010b83588-ffff800010b83724: rproc_add_virtio_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rproc_add_virtio_dev(struct rproc_vdev *rvdev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (c0c66814)
Location: drivers/remoteproc/remoteproc_virtio.c:329
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_do_start
```
**Symbols:**

```
c0c66814-c0c6699c: rproc_add_virtio_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rproc_add_virtio_dev(struct rproc_vdev *rvdev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (c000000000c609d0)
Location: drivers/remoteproc/remoteproc_virtio.c:329
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_do_start
```
**Symbols:**

```
c000000000c609d0-c000000000c60bfc: rproc_add_virtio_dev (STB_GLOBAL)
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
int rproc_add_virtio_dev(struct rproc_vdev *rvdev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: drivers/remoteproc/remoteproc_virtio.c:329
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_do_start
```
**Symbols:**

```
ffffffff81898721-ffffffff818987b2: rproc_add_virtio_dev.cold (STB_LOCAL)
ffffffff818985d0-ffffffff818986b0: rproc_add_virtio_dev (STB_GLOBAL)
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
int rproc_add_virtio_dev(struct rproc_vdev *rvdev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: drivers/remoteproc/remoteproc_virtio.c:329
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_do_start
```
**Symbols:**

```
ffffffff81908e81-ffffffff81908f12: rproc_add_virtio_dev.cold (STB_LOCAL)
ffffffff81908d30-ffffffff81908e10: rproc_add_virtio_dev (STB_GLOBAL)
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
