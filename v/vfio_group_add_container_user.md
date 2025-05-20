# Function: <code>vfio_group_add_container_user</code>

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
int vfio_group_add_container_user(struct vfio_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817d0690)
Location: drivers/vfio/vfio.c:1432
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_unpin_pages
  - drivers/vfio/vfio.c:vfio_pin_pages
  - drivers/vfio/vfio.c:vfio_group_get_external_user
```
**Symbols:**

```
ffffffff817d0690-ffffffff817d06fd: vfio_group_add_container_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfio_group_add_container_user(struct vfio_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8189b7f0)
Location: drivers/vfio/vfio.c:1436
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_unpin_pages
  - drivers/vfio/vfio.c:vfio_pin_pages
  - drivers/vfio/vfio.c:vfio_group_get_external_user_from_dev
  - drivers/vfio/vfio.c:vfio_group_get_external_user
```
**Symbols:**

```
ffffffff8189b7f0-ffffffff8189b865: vfio_group_add_container_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_group_add_container_user(struct vfio_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff818aa400)
Location: drivers/vfio/vfio.c:1437
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_unpin_pages
  - drivers/vfio/vfio.c:vfio_pin_pages
  - drivers/vfio/vfio.c:vfio_group_get_external_user_from_dev
  - drivers/vfio/vfio.c:vfio_group_get_external_user
```
**Symbols:**

```
ffffffff818aa400-ffffffff818aa475: vfio_group_add_container_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfio_group_add_container_user(struct vfio_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8188d750)
Location: drivers/vfio/vfio.c:1336
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_unpin_pages
  - drivers/vfio/vfio.c:vfio_pin_pages
  - drivers/vfio/vfio.c:vfio_group_get_external_user_from_dev
  - drivers/vfio/vfio.c:vfio_group_get_external_user
```
**Symbols:**

```
ffffffff8188d750-ffffffff8188d7c5: vfio_group_add_container_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vfio_group_add_container_user(struct vfio_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio.c (0)
Location: drivers/vfio/vfio.c:1422
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_unpin_pages
  - drivers/vfio/vfio.c:vfio_pin_pages
  - drivers/vfio/vfio.c:vfio_group_get_external_user_from_dev
  - drivers/vfio/vfio.c:vfio_group_get_external_user
```
**Symbols:**

```
ffffffff81920cb0-ffffffff81920d3d: vfio_group_add_container_user (STB_LOCAL)
ffffffff81d116a7-ffffffff81d116bc: vfio_group_add_container_user.cold (STB_LOCAL)
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
int vfio_group_add_container_user(struct vfio_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (c000000000aaec90)
Location: drivers/vfio/vfio.c:1432
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_unpin_pages
  - drivers/vfio/vfio.c:vfio_pin_pages
  - drivers/vfio/vfio.c:vfio_group_get_external_user
```
**Symbols:**

```
c000000000aaec90-c000000000aaed9c: vfio_group_add_container_user (STB_LOCAL)
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
int vfio_group_add_container_user(struct vfio_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8177a740)
Location: drivers/vfio/vfio.c:1432
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_unpin_pages
  - drivers/vfio/vfio.c:vfio_pin_pages
  - drivers/vfio/vfio.c:vfio_group_get_external_user
```
**Symbols:**

```
ffffffff8177a740-ffffffff8177a7ad: vfio_group_add_container_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfio_group_add_container_user(struct vfio_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817c5510)
Location: drivers/vfio/vfio.c:1432
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_unpin_pages
  - drivers/vfio/vfio.c:vfio_pin_pages
  - drivers/vfio/vfio.c:vfio_group_get_external_user
```
**Symbols:**

```
ffffffff817c5510-ffffffff817c557d: vfio_group_add_container_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfio_group_add_container_user(struct vfio_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817df7b0)
Location: drivers/vfio/vfio.c:1432
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_unpin_pages
  - drivers/vfio/vfio.c:vfio_pin_pages
  - drivers/vfio/vfio.c:vfio_group_get_external_user
```
**Symbols:**

```
ffffffff817df7b0-ffffffff817df81d: vfio_group_add_container_user (STB_LOCAL)
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
