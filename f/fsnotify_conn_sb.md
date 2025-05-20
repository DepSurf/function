# Function: <code>fsnotify_conn_sb</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812f9e30)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/notify/fdinfo.c (ffffffff812faf17)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8131a50f)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/notify/fdinfo.c (ffffffff8131b7db)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8132d32f)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/notify/fdinfo.c (ffffffff8132e59b)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff813670df)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/notify/fdinfo.c (ffffffff8136845b)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8137442f)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
  - fs/notify/mark.c:__fsnotify_recalc_mask
  - fs/notify/mark.c:fsnotify_conn_mask
```
```
In fs/notify/fdinfo.c (ffffffff8137578b)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8137addf)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
  - fs/notify/mark.c:__fsnotify_recalc_mask
  - fs/notify/mark.c:fsnotify_conn_mask
```
```
In fs/notify/fdinfo.c (ffffffff8137c126)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff813c7fd3)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
  - fs/notify/mark.c:fsnotify_put_sb_connectors
  - fs/notify/mark.c:__fsnotify_recalc_mask
  - fs/notify/mark.c:fsnotify_conn_mask
```
```
In fs/notify/fdinfo.c (ffffffff813c8f76)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8144f171)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
  - fs/notify/mark.c:fsnotify_put_sb_connectors
```
```
In fs/notify/fdinfo.c (ffffffff8145072d)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff814dd991)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
  - fs/notify/mark.c:fsnotify_put_sb_connectors
```
```
In fs/notify/fdinfo.c (ffffffff814df208)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff815141f1)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
  - fs/notify/mark.c:fsnotify_put_sb_connectors
```
```
In fs/notify/fdinfo.c (ffffffff81515a98)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff815486c1)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
  - fs/notify/mark.c:fsnotify_put_sb_connectors
```
```
In fs/notify/fdinfo.c (ffffffff81549e58)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8154ec78)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_new_mark
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffff8000103e9454)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/notify/fdinfo.c (ffff8000103eae90)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (c05c0858)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
  - fs/notify/mark.c:fsnotify_conn_mask
```
```
In fs/notify/fdinfo.c (c05c1fc4)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (c0000000004efeb4)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/notify/fdinfo.c (c0000000004f2030)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffe00029dcb8)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/notify/fdinfo.c (ffffffe00029f342)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8132590f)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/notify/fdinfo.c (ffffffff81326b7b)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff813164af)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/notify/fdinfo.c (ffffffff8131771b)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff813233df)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/notify/fdinfo.c (ffffffff8132464b)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8133512f)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/notify/fdinfo.c (ffffffff813363cb)
Location: fs/notify/fsnotify.h:24
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
```
</details>
</li>
</ul>

## Differences
