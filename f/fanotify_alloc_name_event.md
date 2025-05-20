# Function: <code>fanotify_alloc_name_event</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fanotify_event *fanotify_alloc_name_event(struct inode *id, __kernel_fsid_t *fsid, const struct qstr *file_name, struct inode *child, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff81377970)
Location: fs/notify/fanotify/fanotify.c:479
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
**Symbols:**

```
ffffffff81377970-ffffffff81377b45: fanotify_alloc_name_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fanotify_event *fanotify_alloc_name_event(struct inode *id, __kernel_fsid_t *fsid, const struct qstr *name, struct inode *child, unsigned int *hash, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff8137e390)
Location: fs/notify/fanotify/fanotify.c:517
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
**Symbols:**

```
ffffffff8137e390-ffffffff8137e5dc: fanotify_alloc_name_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fanotify_event *fanotify_alloc_name_event(struct inode *id, __kernel_fsid_t *fsid, const struct qstr *name, struct inode *child, unsigned int *hash, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff813cb470)
Location: fs/notify/fanotify/fanotify.c:517
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
**Symbols:**

```
ffffffff813cb470-ffffffff813cb6b9: fanotify_alloc_name_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff81453670)
Location: fs/notify/fanotify/fanotify.c:590
Inline: True
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
**Symbols:**

```
ffffffff81453670-ffffffff81453c30: fanotify_alloc_name_event.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff814e2560)
Location: fs/notify/fanotify/fanotify.c:593
Inline: True
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
**Symbols:**

```
ffffffff814e2560-ffffffff814e2ac8: fanotify_alloc_name_event.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff81518e30)
Location: fs/notify/fanotify/fanotify.c:597
Inline: True
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
**Symbols:**

```
ffffffff81518e30-ffffffff815193aa: fanotify_alloc_name_event.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff8154d210)
Location: fs/notify/fanotify/fanotify.c:591
Inline: True
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
**Symbols:**

```
ffffffff8154d210-ffffffff8154d78a: fanotify_alloc_name_event.constprop.0 (STB_LOCAL)
```
</details>
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
In <code>ppc64el</code>: Absent ⚠️
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
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct qstr *name</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int *hash</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct qstr *file_name</code>
</li>
<li>
<b>Param reordered. </b>
<code>id, fsid, file_name, child, gfp</code> ➡️ <code>id, fsid, name, child, hash, gfp</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
