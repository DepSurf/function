# Function: <code>fsnotify_conn_mount</code>

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
In fs/notify/mark.c (ffffffff812f9e3d)
Location: fs/notify/fsnotify.h:18
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/notify/fdinfo.c (ffffffff812faf43)
Location: fs/notify/fsnotify.h:18
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
In fs/notify/mark.c (ffffffff8131a51c)
Location: fs/notify/fsnotify.h:18
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/notify/fdinfo.c (ffffffff8131b808)
Location: fs/notify/fsnotify.h:18
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
In fs/notify/mark.c (ffffffff8132d33c)
Location: fs/notify/fsnotify.h:18
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/notify/fdinfo.c (ffffffff8132e5c8)
Location: fs/notify/fsnotify.h:18
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
In fs/notify/mark.c (ffffffff813670ec)
Location: fs/notify/fsnotify.h:18
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/notify/fdinfo.c (ffffffff81368488)
Location: fs/notify/fsnotify.h:18
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
In fs/notify/mark.c (ffffffff8137443c)
Location: fs/notify/fsnotify.h:18
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
  - fs/notify/mark.c:__fsnotify_recalc_mask
  - fs/notify/mark.c:fsnotify_conn_mask
```
```
In fs/notify/fdinfo.c (ffffffff813757b8)
Location: fs/notify/fsnotify.h:18
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
In fs/notify/mark.c (ffffffff8137adec)
Location: fs/notify/fsnotify.h:18
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
  - fs/notify/mark.c:__fsnotify_recalc_mask
  - fs/notify/mark.c:fsnotify_conn_mask
```
```
In fs/notify/fdinfo.c (ffffffff8137c150)
Location: fs/notify/fsnotify.h:18
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
In fs/notify/mark.c (ffffffff813c7f98)
Location: fs/notify/fsnotify.h:18
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
  - fs/notify/mark.c:fsnotify_put_sb_connectors
  - fs/notify/mark.c:__fsnotify_recalc_mask
  - fs/notify/mark.c:fsnotify_conn_mask
```
```
In fs/notify/fdinfo.c (ffffffff813c8fa0)
Location: fs/notify/fsnotify.h:18
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
In fs/notify/mark.c (ffffffff8144f17e)
Location: fs/notify/fsnotify.h:18
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
  - fs/notify/mark.c:fsnotify_put_sb_connectors
```
```
In fs/notify/fdinfo.c (ffffffff8145076d)
Location: fs/notify/fsnotify.h:18
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
In fs/notify/mark.c (ffffffff814dd99e)
Location: fs/notify/fsnotify.h:18
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
  - fs/notify/mark.c:fsnotify_put_sb_connectors
```
```
In fs/notify/fdinfo.c (ffffffff814df248)
Location: fs/notify/fsnotify.h:18
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
In fs/notify/mark.c (ffffffff815141fe)
Location: fs/notify/fsnotify.h:18
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
  - fs/notify/mark.c:fsnotify_put_sb_connectors
```
```
In fs/notify/fdinfo.c (ffffffff81515ad8)
Location: fs/notify/fsnotify.h:18
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
In fs/notify/mark.c (ffffffff815486ce)
Location: fs/notify/fsnotify.h:18
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
  - fs/notify/mark.c:fsnotify_put_sb_connectors
```
```
In fs/notify/fdinfo.c (ffffffff81549e98)
Location: fs/notify/fsnotify.h:18
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8154ed04)
Location: fs/notify/fsnotify.h:18
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
In fs/notify/mark.c (ffff8000103e9460)
Location: fs/notify/fsnotify.h:18
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/notify/fdinfo.c (ffff8000103eaec8)
Location: fs/notify/fsnotify.h:18
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
In fs/notify/mark.c (0)
Location: fs/notify/fsnotify.h:18
Inline: True
```
```
In fs/notify/fdinfo.c (c05c1ff0)
Location: fs/notify/fsnotify.h:18
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
In fs/notify/mark.c (c0000000004efee0)
Location: fs/notify/fsnotify.h:18
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
  - fs/notify/mark.c:__fsnotify_recalc_mask
  - fs/notify/mark.c:fsnotify_conn_mask
```
```
In fs/notify/fdinfo.c (c0000000004f2080)
Location: fs/notify/fsnotify.h:18
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
In fs/notify/mark.c (ffffffe00029dcc0)
Location: fs/notify/fsnotify.h:18
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
  - fs/notify/mark.c:fsnotify_conn_mask
```
```
In fs/notify/fdinfo.c (ffffffe00029f370)
Location: fs/notify/fsnotify.h:18
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
In fs/notify/mark.c (ffffffff8132591c)
Location: fs/notify/fsnotify.h:18
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/notify/fdinfo.c (ffffffff81326ba8)
Location: fs/notify/fsnotify.h:18
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
In fs/notify/mark.c (ffffffff813164bc)
Location: fs/notify/fsnotify.h:18
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/notify/fdinfo.c (ffffffff81317748)
Location: fs/notify/fsnotify.h:18
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
In fs/notify/mark.c (ffffffff813233ec)
Location: fs/notify/fsnotify.h:18
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/notify/fdinfo.c (ffffffff81324678)
Location: fs/notify/fsnotify.h:18
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
In fs/notify/mark.c (ffffffff8133513c)
Location: fs/notify/fsnotify.h:18
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/notify/fdinfo.c (ffffffff813363f8)
Location: fs/notify/fsnotify.h:18
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
```
</details>
</li>
</ul>

## Differences
