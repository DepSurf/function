# Function: <code>inotify_new_watch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff81252616)
Location: fs/notify/inotify/inotify_user.c:567
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8127add3)
Location: fs/notify/inotify/inotify_user.c:567
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8128e983)
Location: fs/notify/inotify/inotify_user.c:567
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8129b7dd)
Location: fs/notify/inotify/inotify_user.c:535
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff812bebed)
Location: fs/notify/inotify/inotify_user.c:535
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
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
In fs/notify/inotify/inotify_user.c (ffffffff812e745f)
Location: fs/notify/inotify/inotify_user.c:553
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
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
In fs/notify/inotify/inotify_user.c (ffffffff812fc43f)
Location: fs/notify/inotify/inotify_user.c:560
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
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
In fs/notify/inotify/inotify_user.c (ffffffff8131cdc3)
Location: fs/notify/inotify/inotify_user.c:549
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
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
In fs/notify/inotify/inotify_user.c (ffffffff8132fc03)
Location: fs/notify/inotify/inotify_user.c:558
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int inotify_new_watch(struct fsnotify_group *group, struct inode *inode, u32 arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff81369a60)
Location: fs/notify/inotify/inotify_user.c:558
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
```
**Symbols:**

```
ffffffff81369a60-ffffffff81369ba5: inotify_new_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int inotify_new_watch(struct fsnotify_group *group, struct inode *inode, u32 arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff81376d50)
Location: fs/notify/inotify/inotify_user.c:565
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
```
**Symbols:**

```
ffffffff81376d50-ffffffff81376ea9: inotify_new_watch (STB_LOCAL)
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
In fs/notify/inotify/inotify_user.c (ffffffff8137d887)
Location: fs/notify/inotify/inotify_user.c:564
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
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
In fs/notify/inotify/inotify_user.c (ffffffff813ca7c7)
Location: fs/notify/inotify/inotify_user.c:569
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int inotify_new_watch(struct fsnotify_group *group, struct inode *inode, u32 arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff81451bc0)
Location: fs/notify/inotify/inotify_user.c:591
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
```
**Symbols:**

```
ffffffff81451bc0-ffffffff81451d62: inotify_new_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int inotify_new_watch(struct fsnotify_group *group, struct inode *inode, u32 arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff814e0930)
Location: fs/notify/inotify/inotify_user.c:591
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
```
**Symbols:**

```
ffffffff814e0930-ffffffff814e0ad2: inotify_new_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int inotify_new_watch(struct fsnotify_group *group, struct inode *inode, u32 arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff815171e0)
Location: fs/notify/inotify/inotify_user.c:591
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
```
**Symbols:**

```
ffffffff815171e0-ffffffff81517382: inotify_new_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int inotify_new_watch(struct fsnotify_group *group, struct inode *inode, u32 arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8154b5d0)
Location: fs/notify/inotify/inotify_user.c:590
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
```
**Symbols:**

```
ffffffff8154b5d0-ffffffff8154b76f: inotify_new_watch (STB_LOCAL)
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
In fs/notify/inotify/inotify_user.c (ffff8000103ecfb0)
Location: fs/notify/inotify/inotify_user.c:558
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch
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
In fs/notify/inotify/inotify_user.c (c05c3908)
Location: fs/notify/inotify/inotify_user.c:558
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
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
In fs/notify/inotify/inotify_user.c (c0000000004f3fd8)
Location: fs/notify/inotify/inotify_user.c:558
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
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
In fs/notify/inotify/inotify_user.c (ffffffe0002a0b3e)
Location: fs/notify/inotify/inotify_user.c:558
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
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
In fs/notify/inotify/inotify_user.c (ffffffff813281e3)
Location: fs/notify/inotify/inotify_user.c:558
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
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
In fs/notify/inotify/inotify_user.c (ffffffff81318d83)
Location: fs/notify/inotify/inotify_user.c:558
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
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
In fs/notify/inotify/inotify_user.c (ffffffff81325cb3)
Location: fs/notify/inotify/inotify_user.c:558
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
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
In fs/notify/inotify/inotify_user.c (ffffffff81337b11)
Location: fs/notify/inotify/inotify_user.c:558
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
