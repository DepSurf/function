# Function: <code>rproc_remove_subdev</code>

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
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void rproc_remove_subdev(struct rproc *rproc, struct rproc_subdev *subdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff818f4b85)
Location: drivers/remoteproc/remoteproc_core.c:2171
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_release
```
**Symbols:**

```
ffffffff818f3680-ffffffff818f36ae: rproc_remove_subdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void rproc_remove_subdev(struct rproc *rproc, struct rproc_subdev *subdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c9d2e)
Location: drivers/remoteproc/remoteproc_core.c:2332
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
```
**Symbols:**

```
ffffffff819c8ff0-ffffffff819c901e: rproc_remove_subdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void rproc_remove_subdev(struct rproc *rproc, struct rproc_subdev *subdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819ca443)
Location: drivers/remoteproc/remoteproc_core.c:2434
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
```
**Symbols:**

```
ffffffff819c8b90-ffffffff819c8bbe: rproc_remove_subdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void rproc_remove_subdev(struct rproc *rproc, struct rproc_subdev *subdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819af453)
Location: drivers/remoteproc/remoteproc_core.c:2679
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
```
**Symbols:**

```
ffffffff819adae0-ffffffff819adb0e: rproc_remove_subdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void rproc_remove_subdev(struct rproc *rproc, struct rproc_subdev *subdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5da83)
Location: drivers/remoteproc/remoteproc_core.c:2708
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
```
**Symbols:**

```
ffffffff81a5c040-ffffffff81a5c06e: rproc_remove_subdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void rproc_remove_subdev(struct rproc *rproc, struct rproc_subdev *subdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81bcdbb1)
Location: drivers/remoteproc/remoteproc_core.c:2718
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
```
**Symbols:**

```
ffffffff81bcbfc0-ffffffff81bcbff8: rproc_remove_subdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rproc_remove_subdev(struct rproc *rproc, struct rproc_subdev *subdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d75b70)
Location: drivers/remoteproc/remoteproc_core.c:2642
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_remove
```
**Symbols:**

```
ffffffff81d75b70-ffffffff81d75ba8: rproc_remove_subdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rproc_remove_subdev(struct rproc *rproc, struct rproc_subdev *subdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de3ab0)
Location: drivers/remoteproc/remoteproc_core.c:2643
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_remove
```
**Symbols:**

```
ffffffff81de3ab0-ffffffff81de3ae8: rproc_remove_subdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rproc_remove_subdev(struct rproc *rproc, struct rproc_subdev *subdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e99ba0)
Location: drivers/remoteproc/remoteproc_core.c:2643
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_remove
```
**Symbols:**

```
ffffffff81e99ba0-ffffffff81e99bd8: rproc_remove_subdev (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void rproc_remove_subdev(struct rproc *rproc, struct rproc_subdev *subdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffff800010b80d58)
Location: drivers/remoteproc/remoteproc_core.c:2171
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_release
```
**Symbols:**

```
ffff800010b7f300-ffff800010b7f344: rproc_remove_subdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void rproc_remove_subdev(struct rproc *rproc, struct rproc_subdev *subdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (c0c643b0)
Location: drivers/remoteproc/remoteproc_core.c:2171
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_release
```
**Symbols:**

```
c0c62a80-c0c62ab4: rproc_remove_subdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void rproc_remove_subdev(struct rproc *rproc, struct rproc_subdev *subdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (c000000000c5d6d4)
Location: drivers/remoteproc/remoteproc_core.c:2171
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_release
```
**Symbols:**

```
c000000000c5b4a0-c000000000c5b4ec: rproc_remove_subdev (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void rproc_remove_subdev(struct rproc *rproc, struct rproc_subdev *subdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81895eb5)
Location: drivers/remoteproc/remoteproc_core.c:2171
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_release
```
**Symbols:**

```
ffffffff818949b0-ffffffff818949de: rproc_remove_subdev (STB_GLOBAL)
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
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void rproc_remove_subdev(struct rproc *rproc, struct rproc_subdev *subdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81906615)
Location: drivers/remoteproc/remoteproc_core.c:2171
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_release
```
**Symbols:**

```
ffffffff81905110-ffffffff8190513e: rproc_remove_subdev (STB_GLOBAL)
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
