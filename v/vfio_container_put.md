# Function: <code>vfio_container_put</code>

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
In drivers/vfio/vfio.c (ffffffff817d0daf)
Location: drivers/vfio/vfio.c:304
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:__vfio_group_unset_container
  - drivers/vfio/vfio.c:vfio_fops_release
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
In drivers/vfio/vfio.c (ffffffff8189b55f)
Location: drivers/vfio/vfio.c:305
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:__vfio_group_unset_container
  - drivers/vfio/vfio.c:vfio_fops_release
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
In drivers/vfio/vfio.c (ffffffff818aa2ff)
Location: drivers/vfio/vfio.c:305
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:__vfio_group_unset_container
  - drivers/vfio/vfio.c:vfio_fops_release
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
In drivers/vfio/vfio.c (ffffffff8188d50f)
Location: drivers/vfio/vfio.c:295
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:__vfio_group_unset_container
  - drivers/vfio/vfio.c:vfio_fops_release
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
In drivers/vfio/vfio.c (ffffffff81920a6f)
Location: drivers/vfio/vfio.c:368
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:__vfio_group_unset_container
  - drivers/vfio/vfio.c:vfio_fops_release
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
In drivers/vfio/vfio.c (ffffffff81a77179)
Location: drivers/vfio/vfio.c:297
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:__vfio_group_unset_container
  - drivers/vfio/vfio.c:vfio_fops_release
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void vfio_container_put(struct vfio_container *container);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (c000000000aae260)
Location: drivers/vfio/vfio.c:304
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:__vfio_group_unset_container
  - drivers/vfio/vfio.c:__vfio_group_unset_container
  - drivers/vfio/vfio.c:__vfio_group_unset_container
  - drivers/vfio/vfio.c:vfio_fops_release
```
**Symbols:**

```
c000000000aae260-c000000000aae2b8: vfio_container_put (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8177ae5f)
Location: drivers/vfio/vfio.c:304
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:__vfio_group_unset_container
  - drivers/vfio/vfio.c:vfio_fops_release
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817c5c2f)
Location: drivers/vfio/vfio.c:304
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:__vfio_group_unset_container
  - drivers/vfio/vfio.c:vfio_fops_release
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817dfecf)
Location: drivers/vfio/vfio.c:304
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:__vfio_group_unset_container
  - drivers/vfio/vfio.c:vfio_fops_release
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
