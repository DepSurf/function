# Function: <code>rproc_vdev_release</code>

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
void rproc_vdev_release(struct kref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff818f4b60)
Location: drivers/remoteproc/remoteproc_core.c:570
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release
```
**Symbols:**

```
ffffffff818f4b60-ffffffff818f4bdf: rproc_vdev_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void rproc_vdev_release(struct kref *ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819cad90)
Location: drivers/remoteproc/remoteproc_core.c:577
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release
```
**Symbols:**

```
ffffffff819cad90-ffffffff819caece: rproc_vdev_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void rproc_vdev_release(struct kref *ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819ca800)
Location: drivers/remoteproc/remoteproc_core.c:610
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release
```
**Symbols:**

```
ffffffff819ca800-ffffffff819ca882: rproc_vdev_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void rproc_vdev_release(struct kref *ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819af43b)
Location: drivers/remoteproc/remoteproc_core.c:614
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release
```
**Symbols:**

```
ffffffff819af990-ffffffff819afa12: rproc_vdev_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void rproc_vdev_release(struct kref *ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5da6b)
Location: drivers/remoteproc/remoteproc_core.c:618
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release
```
**Symbols:**

```
ffffffff81a5dff0-ffffffff81a5e072: rproc_vdev_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void rproc_vdev_release(struct kref *ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81bcdb97)
Location: drivers/remoteproc/remoteproc_core.c:618
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release
```
**Symbols:**

```
ffffffff81bce200-ffffffff81bce290: rproc_vdev_release (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void rproc_vdev_release(struct kref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffff800010b80d30)
Location: drivers/remoteproc/remoteproc_core.c:570
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release
```
**Symbols:**

```
ffff800010b80d30-ffff800010b80da4: rproc_vdev_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rproc_vdev_release(struct kref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (c0c64388)
Location: drivers/remoteproc/remoteproc_core.c:570
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release
```
**Symbols:**

```
c0c64388-c0c643f0: rproc_vdev_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rproc_vdev_release(struct kref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (c000000000c5d6a0)
Location: drivers/remoteproc/remoteproc_core.c:570
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release
```
**Symbols:**

```
c000000000c5d6a0-c000000000c5d74c: rproc_vdev_release (STB_GLOBAL)
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
void rproc_vdev_release(struct kref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81895e90)
Location: drivers/remoteproc/remoteproc_core.c:570
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release
```
**Symbols:**

```
ffffffff81895e90-ffffffff81895f0f: rproc_vdev_release (STB_GLOBAL)
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
void rproc_vdev_release(struct kref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819065f0)
Location: drivers/remoteproc/remoteproc_core.c:570
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release
```
**Symbols:**

```
ffffffff819065f0-ffffffff8190666f: rproc_vdev_release (STB_GLOBAL)
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
