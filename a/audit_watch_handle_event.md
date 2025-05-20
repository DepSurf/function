# Function: <code>audit_watch_handle_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int audit_watch_handle_event(struct fsnotify_group *group, struct inode *to_tell, struct fsnotify_mark *inode_mark, struct fsnotify_mark *vfsmount_mark, u32 mask, void *data, int data_type, const unsigned char *dname, u32 cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81129fc0)
Location: kernel/audit_watch.c:470
Inline: False
```
**Symbols:**

```
ffffffff81129fc0-ffffffff8112a216: audit_watch_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int audit_watch_handle_event(struct fsnotify_group *group, struct inode *to_tell, struct fsnotify_mark *inode_mark, struct fsnotify_mark *vfsmount_mark, u32 mask, void *data, int data_type, const unsigned char *dname, u32 cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81132180)
Location: kernel/audit_watch.c:471
Inline: False
```
**Symbols:**

```
ffffffff81132180-ffffffff811323d3: audit_watch_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int audit_watch_handle_event(struct fsnotify_group *group, struct inode *to_tell, struct fsnotify_mark *inode_mark, struct fsnotify_mark *vfsmount_mark, u32 mask, const void *data, int data_type, const unsigned char *dname, u32 cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff8113bee0)
Location: kernel/audit_watch.c:470
Inline: False
```
**Symbols:**

```
ffffffff8113bee0-ffffffff8113c133: audit_watch_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int audit_watch_handle_event(struct fsnotify_group *group, struct inode *to_tell, struct fsnotify_mark *inode_mark, struct fsnotify_mark *vfsmount_mark, u32 mask, const void *data, int data_type, const unsigned char *dname, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff8113d580)
Location: kernel/audit_watch.c:473
Inline: False
```
**Symbols:**

```
ffffffff8113d580-ffffffff8113d7c9: audit_watch_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int audit_watch_handle_event(struct fsnotify_group *group, struct inode *to_tell, struct fsnotify_mark *inode_mark, struct fsnotify_mark *vfsmount_mark, u32 mask, const void *data, int data_type, const unsigned char *dname, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff8114a350)
Location: kernel/audit_watch.c:473
Inline: False
```
**Symbols:**

```
ffffffff8114a350-ffffffff8114a599: audit_watch_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int audit_watch_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const unsigned char *dname, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81158d60)
Location: kernel/audit_watch.c:483
Inline: False
```
**Symbols:**

```
ffffffff81158d60-ffffffff81158fc0: audit_watch_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int audit_watch_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const unsigned char *dname, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81165d00)
Location: kernel/audit_watch.c:482
Inline: False
```
**Symbols:**

```
ffffffff81165d00-ffffffff81165f56: audit_watch_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int audit_watch_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const struct qstr *dname, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81172880)
Location: kernel/audit_watch.c:469
Inline: False
```
**Symbols:**

```
ffffffff81172880-ffffffff81172add: audit_watch_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int audit_watch_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const struct qstr *dname, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff8117e730)
Location: kernel/audit_watch.c:469
Inline: False
```
**Symbols:**

```
ffffffff8117e730-ffffffff8117e98d: audit_watch_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int audit_watch_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const struct qstr *dname, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81191e00)
Location: kernel/audit_watch.c:467
Inline: False
```
**Symbols:**

```
ffffffff81191e00-ffffffff81191eaf: audit_watch_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int audit_watch_handle_event(struct fsnotify_mark *inode_mark, u32 mask, struct inode *inode, struct inode *dir, const struct qstr *dname, u32 cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff8118efb0)
Location: kernel/audit_watch.c:467
Inline: False
```
**Symbols:**

```
ffffffff8118efb0-ffffffff8118f03d: audit_watch_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int audit_watch_handle_event(struct fsnotify_mark *inode_mark, u32 mask, struct inode *inode, struct inode *dir, const struct qstr *dname, u32 cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff8118fde0)
Location: kernel/audit_watch.c:467
Inline: False
```
**Symbols:**

```
ffffffff8118fde0-ffffffff8118fe64: audit_watch_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int audit_watch_handle_event(struct fsnotify_mark *inode_mark, u32 mask, struct inode *inode, struct inode *dir, const struct qstr *dname, u32 cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff811b8cc0)
Location: kernel/audit_watch.c:467
Inline: False
```
**Symbols:**

```
ffffffff811b8cc0-ffffffff811b8d44: audit_watch_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int audit_watch_handle_event(struct fsnotify_mark *inode_mark, u32 mask, struct inode *inode, struct inode *dir, const struct qstr *dname, u32 cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff811ebc20)
Location: kernel/audit_watch.c:468
Inline: False
```
**Symbols:**

```
ffffffff811ebc20-ffffffff811ebd02: audit_watch_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int audit_watch_handle_event(struct fsnotify_mark *inode_mark, u32 mask, struct inode *inode, struct inode *dir, const struct qstr *dname, u32 cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81232040)
Location: kernel/audit_watch.c:468
Inline: False
```
**Symbols:**

```
ffffffff81232040-ffffffff81232122: audit_watch_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int audit_watch_handle_event(struct fsnotify_mark *inode_mark, u32 mask, struct inode *inode, struct inode *dir, const struct qstr *dname, u32 cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81248cd0)
Location: kernel/audit_watch.c:468
Inline: False
```
**Symbols:**

```
ffffffff81248cd0-ffffffff81248db2: audit_watch_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int audit_watch_handle_event(struct fsnotify_mark *inode_mark, u32 mask, struct inode *inode, struct inode *dir, const struct qstr *dname, u32 cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81262bb0)
Location: kernel/audit_watch.c:468
Inline: False
```
**Symbols:**

```
ffffffff81262bb0-ffffffff81262c92: audit_watch_handle_event (STB_LOCAL)
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
int audit_watch_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const struct qstr *dname, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffff8000101f3568)
Location: kernel/audit_watch.c:469
Inline: False
```
**Symbols:**

```
ffff8000101f3568-ffff8000101f381c: audit_watch_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int audit_watch_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const struct qstr *dname, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (c0433a88)
Location: kernel/audit_watch.c:469
Inline: False
```
**Symbols:**

```
c0433a88-c0433ce0: audit_watch_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int audit_watch_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const struct qstr *dname, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (c000000000268120)
Location: kernel/audit_watch.c:469
Inline: False
```
**Symbols:**

```
c000000000268120-c00000000026846c: audit_watch_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int audit_watch_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const struct qstr *dname, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffe000166a5a)
Location: kernel/audit_watch.c:469
Inline: False
```
**Symbols:**

```
ffffffe000166a5a-ffffffe000166c62: audit_watch_handle_event (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int audit_watch_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const struct qstr *dname, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81176d50)
Location: kernel/audit_watch.c:469
Inline: False
```
**Symbols:**

```
ffffffff81176d50-ffffffff81176fad: audit_watch_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int audit_watch_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const struct qstr *dname, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81169ef0)
Location: kernel/audit_watch.c:469
Inline: False
```
**Symbols:**

```
ffffffff81169ef0-ffffffff8116a14d: audit_watch_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int audit_watch_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const struct qstr *dname, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81174b20)
Location: kernel/audit_watch.c:469
Inline: False
```
**Symbols:**

```
ffffffff81174b20-ffffffff81174d7d: audit_watch_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int audit_watch_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const struct qstr *dname, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81182400)
Location: kernel/audit_watch.c:469
Inline: False
```
**Symbols:**

```
ffffffff81182400-ffffffff8118265d: audit_watch_handle_event (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void *data</code> ➡️ <code>const void *data</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fsnotify_iter_info *iter_info</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct fsnotify_mark *inode_mark</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fsnotify_mark *vfsmount_mark</code>
</li>
<li>
<b>Param reordered. </b>
<code>group, to_tell, inode_mark, vfsmount_mark, mask, data, data_type, dname, cookie, iter_info</code> ➡️ <code>group, to_tell, mask, data, data_type, dname, cookie, iter_info</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const unsigned char *dname</code> ➡️ <code>const struct qstr *dname</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fsnotify_mark *inode_mark</code>
</li>
<li>
<b>Param added. </b>
<code>struct inode *inode</code>
</li>
<li>
<b>Param added. </b>
<code>struct inode *dir</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fsnotify_group *group</code>
</li>
<li>
<b>Param removed. </b>
<code>struct inode *to_tell</code>
</li>
<li>
<b>Param removed. </b>
<code>const void *data</code>
</li>
<li>
<b>Param removed. </b>
<code>int data_type</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fsnotify_iter_info *iter_info</code>
</li>
<li>
<b>Param reordered. </b>
<code>group, to_tell, mask, data, data_type, dname, cookie, iter_info</code> ➡️ <code>inode_mark, mask, inode, dir, dname, cookie</code>
</li>
</ul>
</details>
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
