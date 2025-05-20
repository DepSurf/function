# Function: <code>fsnotify_conn_inode</code>

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
In fs/notify/mark.c (ffffffff812fa813)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/notify/fdinfo.c (ffffffff812faeaa)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
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
In fs/notify/mark.c (ffffffff8131a987)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/notify/fdinfo.c (ffffffff8131b771)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
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
In fs/notify/mark.c (ffffffff8132de2e)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
  - fs/notify/mark.c:fsnotify_conn_mask
```
```
In fs/notify/fdinfo.c (ffffffff8132e531)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
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
In fs/notify/mark.c (ffffffff81367ea7)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
  - fs/notify/mark.c:__fsnotify_recalc_mask
  - fs/notify/mark.c:fsnotify_conn_mask
```
```
In fs/notify/fdinfo.c (ffffffff813683f1)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
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
In fs/notify/mark.c (ffffffff81375217)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
  - fs/notify/mark.c:__fsnotify_recalc_mask
  - fs/notify/mark.c:fsnotify_conn_mask
```
```
In fs/notify/fdinfo.c (ffffffff81375721)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
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
In fs/notify/mark.c (ffffffff8137bbc3)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
  - fs/notify/mark.c:__fsnotify_recalc_mask
  - fs/notify/mark.c:fsnotify_conn_mask
```
```
In fs/notify/fdinfo.c (ffffffff8137c0bc)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
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
In fs/notify/mark.c (ffffffff813c89c3)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
  - fs/notify/mark.c:fsnotify_put_sb_connectors
  - fs/notify/mark.c:__fsnotify_recalc_mask
  - fs/notify/mark.c:fsnotify_conn_mask
```
```
In fs/notify/fdinfo.c (ffffffff813c8f0c)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
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
In fs/notify/mark.c (ffffffff814500aa)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
  - fs/notify/mark.c:fsnotify_put_sb_connectors
  - fs/notify/mark.c:__fsnotify_recalc_mask
  - fs/notify/mark.c:__fsnotify_recalc_mask
  - fs/notify/mark.c:fsnotify_conn_mask
```
```
In fs/notify/fdinfo.c (ffffffff814506ae)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
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
In fs/notify/mark.c (ffffffff814dea3a)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
  - fs/notify/mark.c:fsnotify_put_sb_connectors
  - fs/notify/mark.c:__fsnotify_recalc_mask
  - fs/notify/mark.c:__fsnotify_recalc_mask
  - fs/notify/mark.c:fsnotify_conn_mask
```
```
In fs/notify/fdinfo.c (ffffffff814df189)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
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
In fs/notify/mark.c (ffffffff8151527a)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
  - fs/notify/mark.c:fsnotify_put_sb_connectors
  - fs/notify/mark.c:__fsnotify_recalc_mask
  - fs/notify/mark.c:__fsnotify_recalc_mask
  - fs/notify/mark.c:fsnotify_conn_mask
```
```
In fs/notify/fdinfo.c (ffffffff81515a19)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
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
In fs/notify/mark.c (ffffffff8154964f)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
  - fs/notify/mark.c:fsnotify_put_sb_connectors
  - fs/notify/mark.c:__fsnotify_recalc_mask
  - fs/notify/mark.c:__fsnotify_recalc_mask
  - fs/notify/mark.c:fsnotify_conn_mask
```
```
In fs/notify/fdinfo.c (ffffffff81549dd9)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8154ec3e)
Location: fs/notify/fsnotify.h:12
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
In fs/notify/mark.c (ffff8000103e98f0)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
  - fs/notify/mark.c:fsnotify_conn_mask
```
```
In fs/notify/fdinfo.c (ffff8000103eae24)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
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
In fs/notify/mark.c (c05c1090)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/notify/fdinfo.c (c05c1f5c)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
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
In fs/notify/mark.c (c0000000004f0ca0)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
  - fs/notify/mark.c:__fsnotify_recalc_mask
  - fs/notify/mark.c:fsnotify_conn_mask
```
```
In fs/notify/fdinfo.c (c0000000004f1f90)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
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
In fs/notify/mark.c (ffffffe00029e130)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
  - fs/notify/mark.c:fsnotify_conn_mask
```
```
In fs/notify/fdinfo.c (ffffffe00029f2de)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
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
In fs/notify/mark.c (ffffffff8132640e)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
  - fs/notify/mark.c:fsnotify_conn_mask
```
```
In fs/notify/fdinfo.c (ffffffff81326b11)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
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
In fs/notify/mark.c (ffffffff81316fae)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
  - fs/notify/mark.c:fsnotify_conn_mask
```
```
In fs/notify/fdinfo.c (ffffffff813176b1)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
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
In fs/notify/mark.c (ffffffff81323ede)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
  - fs/notify/mark.c:fsnotify_conn_mask
```
```
In fs/notify/fdinfo.c (ffffffff813245e1)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
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
In fs/notify/mark.c (ffffffff81335c0c)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
  - fs/notify/mark.c:fsnotify_conn_mask
```
```
In fs/notify/fdinfo.c (ffffffff81336361)
Location: fs/notify/fsnotify.h:12
Inline: True
Inline callers:
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
```
</details>
</li>
</ul>

## Differences
