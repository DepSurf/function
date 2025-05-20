# Function: <code>rproc_free_vring</code>

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
void rproc_free_vring(struct rproc_vring *rvring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff818f4710)
Location: drivers/remoteproc/remoteproc_core.c:400
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_release
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_release
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
```
**Symbols:**

```
ffffffff818f4710-ffffffff818f4789: rproc_free_vring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void rproc_free_vring(struct rproc_vring *rvring);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c9c2a)
Location: drivers/remoteproc/remoteproc_core.c:406
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rp_find_vq
```
**Symbols:**

```
ffffffff819cad10-ffffffff819cad8d: rproc_free_vring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rproc_free_vring(struct rproc_vring *rvring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c9d40)
Location: drivers/remoteproc/remoteproc_core.c:406
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/remoteproc/remoteproc_virtio.c:rp_find_vq
```
**Symbols:**

```
ffffffff819c9d40-ffffffff819c9dbd: rproc_free_vring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rproc_free_vring(struct rproc_vring *rvring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819aed50)
Location: drivers/remoteproc/remoteproc_core.c:409
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/remoteproc/remoteproc_virtio.c:rp_find_vq
```
**Symbols:**

```
ffffffff819aed50-ffffffff819aedcd: rproc_free_vring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rproc_free_vring(struct rproc_vring *rvring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5d350)
Location: drivers/remoteproc/remoteproc_core.c:411
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/remoteproc/remoteproc_virtio.c:rp_find_vq
```
**Symbols:**

```
ffffffff81a5d350-ffffffff81a5d3cd: rproc_free_vring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rproc_free_vring(struct rproc_vring *rvring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81bcd460)
Location: drivers/remoteproc/remoteproc_core.c:411
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_release
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_release
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/remoteproc/remoteproc_virtio.c:rp_find_vq
```
**Symbols:**

```
ffffffff81bcd460-ffffffff81bcd4eb: rproc_free_vring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rproc_free_vring(struct rproc_vring *rvring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d78ed0)
Location: drivers/remoteproc/remoteproc_core.c:410
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_remove
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_remove
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
  - drivers/remoteproc/remoteproc_virtio.c:rp_find_vq
```
**Symbols:**

```
ffffffff81d78ed0-ffffffff81d78f55: rproc_free_vring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rproc_free_vring(struct rproc_vring *rvring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de6e20)
Location: drivers/remoteproc/remoteproc_core.c:410
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_remove
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_remove
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
  - drivers/remoteproc/remoteproc_virtio.c:rp_find_vq
```
**Symbols:**

```
ffffffff81de6e20-ffffffff81de6ea5: rproc_free_vring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rproc_free_vring(struct rproc_vring *rvring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9d000)
Location: drivers/remoteproc/remoteproc_core.c:410
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_remove
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_remove
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
  - drivers/remoteproc/remoteproc_virtio.c:rp_find_vq
```
**Symbols:**

```
ffffffff81e9d000-ffffffff81e9d085: rproc_free_vring (STB_GLOBAL)
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
void rproc_free_vring(struct rproc_vring *rvring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffff800010b80898)
Location: drivers/remoteproc/remoteproc_core.c:400
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_release
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_release
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
```
**Symbols:**

```
ffff800010b80898-ffff800010b80918: rproc_free_vring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rproc_free_vring(struct rproc_vring *rvring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (c0c63e88)
Location: drivers/remoteproc/remoteproc_core.c:400
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_release
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_release
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
```
**Symbols:**

```
c0c63e88-c0c63f10: rproc_free_vring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rproc_free_vring(struct rproc_vring *rvring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (c000000000c5d0f0)
Location: drivers/remoteproc/remoteproc_core.c:400
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_release
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_release
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
```
**Symbols:**

```
c000000000c5d0f0-c000000000c5d1a0: rproc_free_vring (STB_GLOBAL)
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
void rproc_free_vring(struct rproc_vring *rvring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81895a40)
Location: drivers/remoteproc/remoteproc_core.c:400
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_release
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_release
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
```
**Symbols:**

```
ffffffff81895a40-ffffffff81895ab9: rproc_free_vring (STB_GLOBAL)
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
void rproc_free_vring(struct rproc_vring *rvring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819061a0)
Location: drivers/remoteproc/remoteproc_core.c:400
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_release
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_release
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
```
**Symbols:**

```
ffffffff819061a0-ffffffff81906219: rproc_free_vring (STB_GLOBAL)
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
