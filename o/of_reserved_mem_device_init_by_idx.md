# Function: <code>of_reserved_mem_device_init_by_idx</code>

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
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: include/linux/of_reserved_mem.h:43
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: include/linux/of_reserved_mem.h:47
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: include/linux/of_reserved_mem.h:47
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: include/linux/of_reserved_mem.h:47
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: include/linux/of_reserved_mem.h:48
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: include/linux/of_reserved_mem.h:48
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: include/linux/of_reserved_mem.h:48
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: include/linux/of_reserved_mem.h:48
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: include/linux/of_reserved_mem.h:48
Inline: True
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
int of_reserved_mem_device_init_by_idx(struct device *dev, struct device_node *np, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/of_reserved_mem.c (ffff800010b76550)
Location: drivers/of/of_reserved_mem.c:312
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
```
**Symbols:**

```
ffff800010b76550-ffff800010b76750: of_reserved_mem_device_init_by_idx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_reserved_mem_device_init_by_idx(struct device *dev, struct device_node *np, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/of_reserved_mem.c (c0c588e4)
Location: drivers/of/of_reserved_mem.c:312
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
```
**Symbols:**

```
c0c588e4-c0c58a90: of_reserved_mem_device_init_by_idx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_reserved_mem_device_init_by_idx(struct device *dev, struct device_node *np, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/of_reserved_mem.c (c000000000c542d0)
Location: drivers/of/of_reserved_mem.c:312
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
```
**Symbols:**

```
c000000000c542d0-c000000000c54598: of_reserved_mem_device_init_by_idx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_reserved_mem_device_init_by_idx(struct device *dev, struct device_node *np, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/of_reserved_mem.c (ffffffe000729992)
Location: drivers/of/of_reserved_mem.c:312
Inline: False
```
**Symbols:**

```
ffffffe000729992-ffffffe000729b14: of_reserved_mem_device_init_by_idx (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: include/linux/of_reserved_mem.h:43
Inline: True
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
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: include/linux/of_reserved_mem.h:43
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
