# Function: <code>vfio_group_unlock_and_free</code>

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
void vfio_group_unlock_and_free(struct vfio_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817d03a0)
Location: drivers/vfio/vfio.c:309
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_group_put
```
**Symbols:**

```
ffffffff817d03a0-ffffffff817d03d5: vfio_group_unlock_and_free (STB_LOCAL)
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
In drivers/vfio/vfio.c (ffffffff8189b968)
Location: drivers/vfio/vfio.c:310
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_release
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/vfio/vfio.c:vfio_create_group
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
In drivers/vfio/vfio.c (ffffffff818aa578)
Location: drivers/vfio/vfio.c:310
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_release
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/vfio/vfio.c:vfio_create_group
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
In drivers/vfio/vfio.c (ffffffff8188dda8)
Location: drivers/vfio/vfio.c:300
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_release
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/vfio/vfio.c:vfio_create_group
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
In drivers/vfio/vfio.c (ffffffff819213e8)
Location: drivers/vfio/vfio.c:373
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_release
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/vfio/vfio.c:vfio_create_group
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
void vfio_group_unlock_and_free(struct vfio_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (c000000000aae300)
Location: drivers/vfio/vfio.c:309
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_group_put
```
**Symbols:**

```
c000000000aae300-c000000000aae364: vfio_group_unlock_and_free (STB_LOCAL)
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
<summary>In <code>azure</code>: ✅</summary>

```c
void vfio_group_unlock_and_free(struct vfio_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8177a450)
Location: drivers/vfio/vfio.c:309
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_group_put
```
**Symbols:**

```
ffffffff8177a450-ffffffff8177a485: vfio_group_unlock_and_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void vfio_group_unlock_and_free(struct vfio_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817c5220)
Location: drivers/vfio/vfio.c:309
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_group_put
```
**Symbols:**

```
ffffffff817c5220-ffffffff817c5255: vfio_group_unlock_and_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void vfio_group_unlock_and_free(struct vfio_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817df4c0)
Location: drivers/vfio/vfio.c:309
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_group_put
```
**Symbols:**

```
ffffffff817df4c0-ffffffff817df4f5: vfio_group_unlock_and_free (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
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
