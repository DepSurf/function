# Function: <code>rproc_add_subdev</code>

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
void rproc_add_subdev(struct rproc *rproc, struct rproc_subdev *subdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff818f4b04)
Location: drivers/remoteproc/remoteproc_core.c:2160
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffffffff818f3650-ffffffff818f3677: rproc_add_subdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void rproc_add_subdev(struct rproc *rproc, struct rproc_subdev *subdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819cacb3)
Location: drivers/remoteproc/remoteproc_core.c:2321
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffffffff819c8fc0-ffffffff819c8fe7: rproc_add_subdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void rproc_add_subdev(struct rproc *rproc, struct rproc_subdev *subdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819ca1c0)
Location: drivers/remoteproc/remoteproc_core.c:2423
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffffffff819c8b60-ffffffff819c8b87: rproc_add_subdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void rproc_add_subdev(struct rproc *rproc, struct rproc_subdev *subdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819af1d0)
Location: drivers/remoteproc/remoteproc_core.c:2668
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffffffff819adab0-ffffffff819adad7: rproc_add_subdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void rproc_add_subdev(struct rproc *rproc, struct rproc_subdev *subdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5d7ee)
Location: drivers/remoteproc/remoteproc_core.c:2697
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffffffff81a5c010-ffffffff81a5c037: rproc_add_subdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void rproc_add_subdev(struct rproc *rproc, struct rproc_subdev *subdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81bcd92c)
Location: drivers/remoteproc/remoteproc_core.c:2707
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffffffff81bcbf80-ffffffff81bcbfb1: rproc_add_subdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rproc_add_subdev(struct rproc *rproc, struct rproc_subdev *subdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d75b20)
Location: drivers/remoteproc/remoteproc_core.c:2631
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
```
**Symbols:**

```
ffffffff81d75b20-ffffffff81d75b51: rproc_add_subdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rproc_add_subdev(struct rproc *rproc, struct rproc_subdev *subdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de3a60)
Location: drivers/remoteproc/remoteproc_core.c:2632
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
```
**Symbols:**

```
ffffffff81de3a60-ffffffff81de3a91: rproc_add_subdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rproc_add_subdev(struct rproc *rproc, struct rproc_subdev *subdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e99b50)
Location: drivers/remoteproc/remoteproc_core.c:2632
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
```
**Symbols:**

```
ffffffff81e99b50-ffffffff81e99b81: rproc_add_subdev (STB_GLOBAL)
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
void rproc_add_subdev(struct rproc *rproc, struct rproc_subdev *subdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffff800010b80c40)
Location: drivers/remoteproc/remoteproc_core.c:2160
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffff800010b7f2c0-ffff800010b7f300: rproc_add_subdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void rproc_add_subdev(struct rproc *rproc, struct rproc_subdev *subdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (c0c64278)
Location: drivers/remoteproc/remoteproc_core.c:2160
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
c0c62a54-c0c62a80: rproc_add_subdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void rproc_add_subdev(struct rproc *rproc, struct rproc_subdev *subdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (c000000000c5d5c0)
Location: drivers/remoteproc/remoteproc_core.c:2160
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
c000000000c5b470-c000000000c5b494: rproc_add_subdev (STB_GLOBAL)
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
void rproc_add_subdev(struct rproc *rproc, struct rproc_subdev *subdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81895e34)
Location: drivers/remoteproc/remoteproc_core.c:2160
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffffffff81894980-ffffffff818949a7: rproc_add_subdev (STB_GLOBAL)
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
void rproc_add_subdev(struct rproc *rproc, struct rproc_subdev *subdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81906594)
Location: drivers/remoteproc/remoteproc_core.c:2160
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
**Symbols:**

```
ffffffff819050e0-ffffffff81905107: rproc_add_subdev (STB_GLOBAL)
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
