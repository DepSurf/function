# Function: <code>fanotify_mark_remove_from_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
__u32 fanotify_mark_remove_from_mask(struct fsnotify_mark *fsn_mark, __u32 mask, unsigned int flags, int *destroy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff812538f0)
Location: fs/notify/fanotify/fanotify_user.c:485
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_vfsmount_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_inode_mark
```
**Symbols:**

```
ffffffff812538f0-ffffffff8125399f: fanotify_mark_remove_from_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
__u32 fanotify_mark_remove_from_mask(struct fsnotify_mark *fsn_mark, __u32 mask, unsigned int flags, int *destroy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8127bef0)
Location: fs/notify/fanotify/fanotify_user.c:498
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_inode_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_vfsmount_mark
```
**Symbols:**

```
ffffffff8127bef0-ffffffff8127bf95: fanotify_mark_remove_from_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
__u32 fanotify_mark_remove_from_mask(struct fsnotify_mark *fsn_mark, __u32 mask, unsigned int flags, int *destroy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8128faa0)
Location: fs/notify/fanotify/fanotify_user.c:498
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_inode_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_vfsmount_mark
```
**Symbols:**

```
ffffffff8128faa0-ffffffff8128fb45: fanotify_mark_remove_from_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
__u32 fanotify_mark_remove_from_mask(struct fsnotify_mark *fsn_mark, __u32 mask, unsigned int flags, int *destroy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8129bf00)
Location: fs/notify/fanotify/fanotify_user.c:504
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_inode_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_vfsmount_mark
```
**Symbols:**

```
ffffffff8129bf00-ffffffff8129bfa0: fanotify_mark_remove_from_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
__u32 fanotify_mark_remove_from_mask(struct fsnotify_mark *fsn_mark, __u32 mask, unsigned int flags, int *destroy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff812bf390)
Location: fs/notify/fanotify/fanotify_user.c:499
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_inode_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_vfsmount_mark
```
**Symbols:**

```
ffffffff812bf390-ffffffff812bf430: fanotify_mark_remove_from_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
__u32 fanotify_mark_remove_from_mask(struct fsnotify_mark *fsn_mark, __u32 mask, unsigned int flags, int *destroy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff812e8630)
Location: fs/notify/fanotify/fanotify_user.c:499
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff812e8630-ffffffff812e86d0: fanotify_mark_remove_from_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff812fd949)
Location: fs/notify/fanotify/fanotify_user.c:506
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8131e5f8)
Location: fs/notify/fanotify/fanotify_user.c:576
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff81331438)
Location: fs/notify/fanotify/fanotify_user.c:584
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
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
In fs/notify/fanotify/fanotify_user.c (ffffffff8136bcc8)
Location: fs/notify/fanotify/fanotify_user.c:653
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
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
In fs/notify/fanotify/fanotify_user.c (ffffffff8137955e)
Location: fs/notify/fanotify/fanotify_user.c:719
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
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
In fs/notify/fanotify/fanotify_user.c (ffffffff813800d0)
Location: fs/notify/fanotify/fanotify_user.c:812
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
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
In fs/notify/fanotify/fanotify_user.c (ffffffff813cd040)
Location: fs/notify/fanotify/fanotify_user.c:912
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
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
In fs/notify/fanotify/fanotify_user.c (ffffffff8145618c)
Location: fs/notify/fanotify/fanotify_user.c:1002
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
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
In fs/notify/fanotify/fanotify_user.c (ffffffff814e513c)
Location: fs/notify/fanotify/fanotify_user.c:1002
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
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
In fs/notify/fanotify/fanotify_user.c (ffffffff8151b99c)
Location: fs/notify/fanotify/fanotify_user.c:1051
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
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
In fs/notify/fanotify/fanotify_user.c (ffffffff8154ff9c)
Location: fs/notify/fanotify/fanotify_user.c:1050
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffff8000103ee5cc)
Location: fs/notify/fanotify/fanotify_user.c:584
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (c05c4900)
Location: fs/notify/fanotify/fanotify_user.c:584
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (c0000000004f6f88)
Location: fs/notify/fanotify/fanotify_user.c:584
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffe0002a1d00)
Location: fs/notify/fanotify/fanotify_user.c:584
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
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
In fs/notify/fanotify/fanotify_user.c (ffffffff81329a18)
Location: fs/notify/fanotify/fanotify_user.c:584
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8131a5b8)
Location: fs/notify/fanotify/fanotify_user.c:584
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
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
In fs/notify/fanotify/fanotify_user.c (ffffffff813274e8)
Location: fs/notify/fanotify/fanotify_user.c:584
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
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
In fs/notify/fanotify/fanotify_user.c (ffffffff81339158)
Location: fs/notify/fanotify/fanotify_user.c:584
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_mark
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
