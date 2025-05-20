# Function: <code>fanotify_remove_vfsmount_mark</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fanotify_remove_vfsmount_mark(struct fsnotify_group *group, struct vfsmount *mnt, __u32 mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff812539a0)
Location: fs/notify/fanotify/fanotify_user.c:514
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark
```
**Symbols:**

```
ffffffff812539a0-ffffffff81253a7f: fanotify_remove_vfsmount_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fanotify_remove_vfsmount_mark(struct fsnotify_group *group, struct vfsmount *mnt, __u32 mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8127bfa0)
Location: fs/notify/fanotify/fanotify_user.c:527
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark
```
**Symbols:**

```
ffffffff8127bfa0-ffffffff8127c07f: fanotify_remove_vfsmount_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fanotify_remove_vfsmount_mark(struct fsnotify_group *group, struct vfsmount *mnt, __u32 mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8128fb50)
Location: fs/notify/fanotify/fanotify_user.c:527
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark
```
**Symbols:**

```
ffffffff8128fb50-ffffffff8128fc2f: fanotify_remove_vfsmount_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fanotify_remove_vfsmount_mark(struct fsnotify_group *group, struct vfsmount *mnt, __u32 mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8129c9c0)
Location: fs/notify/fanotify/fanotify_user.c:532
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark
```
**Symbols:**

```
ffffffff8129c9c0-ffffffff8129cabc: fanotify_remove_vfsmount_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fanotify_remove_vfsmount_mark(struct fsnotify_group *group, struct vfsmount *mnt, __u32 mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff812bfe30)
Location: fs/notify/fanotify/fanotify_user.c:527
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark
```
**Symbols:**

```
ffffffff812bfe30-ffffffff812bff2c: fanotify_remove_vfsmount_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff812e8a3a)
Location: fs/notify/fanotify/fanotify_user.c:527
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
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
In fs/notify/fanotify/fanotify_user.c (ffffffff812fdfc5)
Location: fs/notify/fanotify/fanotify_user.c:556
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
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
In fs/notify/fanotify/fanotify_user.c (ffffffff8131ed32)
Location: fs/notify/fanotify/fanotify_user.c:626
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
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
In fs/notify/fanotify/fanotify_user.c (ffffffff813317e7)
Location: fs/notify/fanotify/fanotify_user.c:634
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
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
In fs/notify/fanotify/fanotify_user.c (ffffffff8136c4ee)
Location: fs/notify/fanotify/fanotify_user.c:703
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
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
In fs/notify/fanotify/fanotify_user.c (ffffffff81379b4a)
Location: fs/notify/fanotify/fanotify_user.c:776
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
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
In fs/notify/fanotify/fanotify_user.c (ffffffff8138077b)
Location: fs/notify/fanotify/fanotify_user.c:869
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
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
In fs/notify/fanotify/fanotify_user.c (ffffffff813cd5d8)
Location: fs/notify/fanotify/fanotify_user.c:969
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
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
In fs/notify/fanotify/fanotify_user.c (ffffffff81456dcd)
Location: fs/notify/fanotify/fanotify_user.c:1060
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
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
In fs/notify/fanotify/fanotify_user.c (ffffffff814e5f49)
Location: fs/notify/fanotify/fanotify_user.c:1060
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
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
In fs/notify/fanotify/fanotify_user.c (ffffffff8151ca9c)
Location: fs/notify/fanotify/fanotify_user.c:1109
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
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
In fs/notify/fanotify/fanotify_user.c (ffffffff81550fd7)
Location: fs/notify/fanotify/fanotify_user.c:1108
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
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
In fs/notify/fanotify/fanotify_user.c (ffff8000103eedec)
Location: fs/notify/fanotify/fanotify_user.c:634
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
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
In fs/notify/fanotify/fanotify_user.c (c05c5e88)
Location: fs/notify/fanotify/fanotify_user.c:634
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
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
In fs/notify/fanotify/fanotify_user.c (c0000000004f77fc)
Location: fs/notify/fanotify/fanotify_user.c:634
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
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
In fs/notify/fanotify/fanotify_user.c (ffffffe0002a2cc8)
Location: fs/notify/fanotify/fanotify_user.c:634
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
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
In fs/notify/fanotify/fanotify_user.c (ffffffff81329dc7)
Location: fs/notify/fanotify/fanotify_user.c:634
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
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
In fs/notify/fanotify/fanotify_user.c (ffffffff8131a967)
Location: fs/notify/fanotify/fanotify_user.c:634
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
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
In fs/notify/fanotify/fanotify_user.c (ffffffff81327897)
Location: fs/notify/fanotify/fanotify_user.c:634
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
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
In fs/notify/fanotify/fanotify_user.c (ffffffff81339cb7)
Location: fs/notify/fanotify/fanotify_user.c:634
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
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
</ul>
