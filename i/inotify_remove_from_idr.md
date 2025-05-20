# Function: <code>inotify_remove_from_idr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void inotify_remove_from_idr(struct fsnotify_group *group, struct inotify_inode_mark *i_mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff812520f0)
Location: fs/notify/inotify/inotify_user.c:419
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
**Symbols:**

```
ffffffff812520f0-ffffffff812522be: inotify_remove_from_idr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void inotify_remove_from_idr(struct fsnotify_group *group, struct inotify_inode_mark *i_mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8127a8b0)
Location: fs/notify/inotify/inotify_user.c:419
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff8127a8b0-ffffffff8127aa7d: inotify_remove_from_idr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void inotify_remove_from_idr(struct fsnotify_group *group, struct inotify_inode_mark *i_mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8128e460)
Location: fs/notify/inotify/inotify_user.c:419
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff8128e460-ffffffff8128e62d: inotify_remove_from_idr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void inotify_remove_from_idr(struct fsnotify_group *group, struct inotify_inode_mark *i_mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8129b330)
Location: fs/notify/inotify/inotify_user.c:402
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff8129b330-ffffffff8129b4b2: inotify_remove_from_idr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void inotify_remove_from_idr(struct fsnotify_group *group, struct inotify_inode_mark *i_mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff812be740)
Location: fs/notify/inotify/inotify_user.c:402
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff812be740-ffffffff812be8c2: inotify_remove_from_idr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void inotify_remove_from_idr(struct fsnotify_group *group, struct inotify_inode_mark *i_mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/inotify/inotify_user.c (0)
Location: fs/notify/inotify/inotify_user.c:416
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff812e7220-ffffffff812e7373: inotify_remove_from_idr (STB_LOCAL)
ffffffff812e7d2e-ffffffff812e7d50: inotify_remove_from_idr.cold.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void inotify_remove_from_idr(struct fsnotify_group *group, struct inotify_inode_mark *i_mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/inotify/inotify_user.c (0)
Location: fs/notify/inotify/inotify_user.c:417
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff812fc1e0-ffffffff812fc333: inotify_remove_from_idr (STB_LOCAL)
ffffffff812fc951-ffffffff812fc973: inotify_remove_from_idr.cold.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void inotify_remove_from_idr(struct fsnotify_group *group, struct inotify_inode_mark *i_mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/inotify/inotify_user.c (0)
Location: fs/notify/inotify/inotify_user.c:406
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff8131cb70-ffffffff8131ccc5: inotify_remove_from_idr (STB_LOCAL)
ffffffff8131d311-ffffffff8131d333: inotify_remove_from_idr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void inotify_remove_from_idr(struct fsnotify_group *group, struct inotify_inode_mark *i_mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/inotify/inotify_user.c (0)
Location: fs/notify/inotify/inotify_user.c:415
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff8132f9b0-ffffffff8132fb05: inotify_remove_from_idr (STB_LOCAL)
ffffffff81330151-ffffffff81330173: inotify_remove_from_idr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void inotify_remove_from_idr(struct fsnotify_group *group, struct inotify_inode_mark *i_mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/inotify/inotify_user.c (0)
Location: fs/notify/inotify/inotify_user.c:415
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff81369900-ffffffff81369a55: inotify_remove_from_idr (STB_LOCAL)
ffffffff8136a0e1-ffffffff8136a103: inotify_remove_from_idr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void inotify_remove_from_idr(struct fsnotify_group *group, struct inotify_inode_mark *i_mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/inotify/inotify_user.c (0)
Location: fs/notify/inotify/inotify_user.c:426
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff81376bf0-ffffffff81376d45: inotify_remove_from_idr (STB_LOCAL)
ffffffff81beabce-ffffffff81beabf0: inotify_remove_from_idr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void inotify_remove_from_idr(struct fsnotify_group *group, struct inotify_inode_mark *i_mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/inotify/inotify_user.c (0)
Location: fs/notify/inotify/inotify_user.c:425
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff8137d4f0-ffffffff8137d645: inotify_remove_from_idr (STB_LOCAL)
ffffffff81bdcbfb-ffffffff81bdcc1d: inotify_remove_from_idr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void inotify_remove_from_idr(struct fsnotify_group *group, struct inotify_inode_mark *i_mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/inotify/inotify_user.c (0)
Location: fs/notify/inotify/inotify_user.c:430
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff813ca3d0-ffffffff813ca588: inotify_remove_from_idr (STB_LOCAL)
ffffffff81cc555b-ffffffff81cc55b7: inotify_remove_from_idr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void inotify_remove_from_idr(struct fsnotify_group *group, struct inotify_inode_mark *i_mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/inotify/inotify_user.c (0)
Location: fs/notify/inotify/inotify_user.c:453
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff81451990-ffffffff81451bb5: inotify_remove_from_idr (STB_LOCAL)
ffffffff81e77f33-ffffffff81e77f91: inotify_remove_from_idr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void inotify_remove_from_idr(struct fsnotify_group *group, struct inotify_inode_mark *i_mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/inotify/inotify_user.c (0)
Location: fs/notify/inotify/inotify_user.c:453
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff814e06d0-ffffffff814e0917: inotify_remove_from_idr (STB_LOCAL)
ffffffff82069ef4-ffffffff82069f30: inotify_remove_from_idr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void inotify_remove_from_idr(struct fsnotify_group *group, struct inotify_inode_mark *i_mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/inotify/inotify_user.c (0)
Location: fs/notify/inotify/inotify_user.c:453
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff81516f80-ffffffff815171cc: inotify_remove_from_idr (STB_LOCAL)
ffffffff820e9dbc-ffffffff820e9df8: inotify_remove_from_idr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void inotify_remove_from_idr(struct fsnotify_group *group, struct inotify_inode_mark *i_mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/inotify/inotify_user.c (0)
Location: fs/notify/inotify/inotify_user.c:452
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff8154b370-ffffffff8154b5bc: inotify_remove_from_idr (STB_LOCAL)
ffffffff821c6871-ffffffff821c68ad: inotify_remove_from_idr.cold (STB_LOCAL)
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
void inotify_remove_from_idr(struct fsnotify_group *group, struct inotify_inode_mark *i_mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffff8000103ec820)
Location: fs/notify/inotify/inotify_user.c:415
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffff8000103ec820-ffff8000103eca4c: inotify_remove_from_idr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void inotify_remove_from_idr(struct fsnotify_group *group, struct inotify_inode_mark *i_mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (c05c2f40)
Location: fs/notify/inotify/inotify_user.c:415
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
c05c2f40-c05c3130: inotify_remove_from_idr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void inotify_remove_from_idr(struct fsnotify_group *group, struct inotify_inode_mark *i_mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (c0000000004f3290)
Location: fs/notify/inotify/inotify_user.c:415
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
c0000000004f3290-c0000000004f34f0: inotify_remove_from_idr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void inotify_remove_from_idr(struct fsnotify_group *group, struct inotify_inode_mark *i_mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffe0002a052a)
Location: fs/notify/inotify/inotify_user.c:415
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffe0002a052a-ffffffe0002a06c8: inotify_remove_from_idr (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void inotify_remove_from_idr(struct fsnotify_group *group, struct inotify_inode_mark *i_mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/inotify/inotify_user.c (0)
Location: fs/notify/inotify/inotify_user.c:415
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff81327f90-ffffffff813280e5: inotify_remove_from_idr (STB_LOCAL)
ffffffff81328731-ffffffff81328753: inotify_remove_from_idr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void inotify_remove_from_idr(struct fsnotify_group *group, struct inotify_inode_mark *i_mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/inotify/inotify_user.c (0)
Location: fs/notify/inotify/inotify_user.c:415
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff81318b30-ffffffff81318c85: inotify_remove_from_idr (STB_LOCAL)
ffffffff813192d1-ffffffff813192f3: inotify_remove_from_idr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void inotify_remove_from_idr(struct fsnotify_group *group, struct inotify_inode_mark *i_mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/inotify/inotify_user.c (0)
Location: fs/notify/inotify/inotify_user.c:415
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff81325a60-ffffffff81325bb5: inotify_remove_from_idr (STB_LOCAL)
ffffffff81326201-ffffffff81326223: inotify_remove_from_idr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void inotify_remove_from_idr(struct fsnotify_group *group, struct inotify_inode_mark *i_mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/inotify/inotify_user.c (0)
Location: fs/notify/inotify/inotify_user.c:415
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff813377c0-ffffffff81337940: inotify_remove_from_idr (STB_LOCAL)
ffffffff81338021-ffffffff81338043: inotify_remove_from_idr.cold (STB_LOCAL)
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
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
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
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
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
