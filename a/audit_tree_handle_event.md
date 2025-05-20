# Function: <code>audit_tree_handle_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int audit_tree_handle_event(struct fsnotify_group *group, struct inode *to_tell, struct fsnotify_mark *inode_mark, struct fsnotify_mark *vfsmount_mark, u32 mask, void *data, int data_type, const unsigned char *file_name, u32 cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8112aad0)
Location: kernel/audit_tree.c:949
Inline: False
```
**Symbols:**

```
ffffffff8112aad0-ffffffff8112aadd: audit_tree_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int audit_tree_handle_event(struct fsnotify_group *group, struct inode *to_tell, struct fsnotify_mark *inode_mark, struct fsnotify_mark *vfsmount_mark, u32 mask, void *data, int data_type, const unsigned char *file_name, u32 cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81132cc0)
Location: kernel/audit_tree.c:947
Inline: False
```
**Symbols:**

```
ffffffff81132cc0-ffffffff81132ccd: audit_tree_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int audit_tree_handle_event(struct fsnotify_group *group, struct inode *to_tell, struct fsnotify_mark *inode_mark, struct fsnotify_mark *vfsmount_mark, u32 mask, const void *data, int data_type, const unsigned char *file_name, u32 cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8113ca10)
Location: kernel/audit_tree.c:956
Inline: False
```
**Symbols:**

```
ffffffff8113ca10-ffffffff8113ca1d: audit_tree_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int audit_tree_handle_event(struct fsnotify_group *group, struct inode *to_tell, struct fsnotify_mark *inode_mark, struct fsnotify_mark *vfsmount_mark, u32 mask, const void *data, int data_type, const unsigned char *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8113e0a0)
Location: kernel/audit_tree.c:989
Inline: False
```
**Symbols:**

```
ffffffff8113e0a0-ffffffff8113e0ad: audit_tree_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int audit_tree_handle_event(struct fsnotify_group *group, struct inode *to_tell, struct fsnotify_mark *inode_mark, struct fsnotify_mark *vfsmount_mark, u32 mask, const void *data, int data_type, const unsigned char *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8114ae70)
Location: kernel/audit_tree.c:990
Inline: False
```
**Symbols:**

```
ffffffff8114ae70-ffffffff8114ae7d: audit_tree_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int audit_tree_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const unsigned char *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff811598f0)
Location: kernel/audit_tree.c:990
Inline: False
```
**Symbols:**

```
ffffffff811598f0-ffffffff811598fd: audit_tree_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int audit_tree_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const unsigned char *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81166850)
Location: kernel/audit_tree.c:1037
Inline: False
```
**Symbols:**

```
ffffffff81166850-ffffffff8116685d: audit_tree_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int audit_tree_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81173430)
Location: kernel/audit_tree.c:1040
Inline: False
```
**Symbols:**

```
ffffffff81173430-ffffffff8117343d: audit_tree_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int audit_tree_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8117f2a0)
Location: kernel/audit_tree.c:1040
Inline: False
```
**Symbols:**

```
ffffffff8117f2a0-ffffffff8117f2ad: audit_tree_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int audit_tree_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff811927b0)
Location: kernel/audit_tree.c:1040
Inline: False
```
**Symbols:**

```
ffffffff811927b0-ffffffff811927bd: audit_tree_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int audit_tree_handle_event(struct fsnotify_mark *mark, u32 mask, struct inode *inode, struct inode *dir, const struct qstr *file_name, u32 cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8118f920)
Location: kernel/audit_tree.c:1038
Inline: False
```
**Symbols:**

```
ffffffff8118f920-ffffffff8118f92d: audit_tree_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int audit_tree_handle_event(struct fsnotify_mark *mark, u32 mask, struct inode *inode, struct inode *dir, const struct qstr *file_name, u32 cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81190860)
Location: kernel/audit_tree.c:1038
Inline: False
```
**Symbols:**

```
ffffffff81190860-ffffffff8119086d: audit_tree_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int audit_tree_handle_event(struct fsnotify_mark *mark, u32 mask, struct inode *inode, struct inode *dir, const struct qstr *file_name, u32 cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff811b9740)
Location: kernel/audit_tree.c:1034
Inline: False
```
**Symbols:**

```
ffffffff811b9740-ffffffff811b974d: audit_tree_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int audit_tree_handle_event(struct fsnotify_mark *mark, u32 mask, struct inode *inode, struct inode *dir, const struct qstr *file_name, u32 cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff811ec840)
Location: kernel/audit_tree.c:1035
Inline: False
```
**Symbols:**

```
ffffffff811ec840-ffffffff811ec851: audit_tree_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int audit_tree_handle_event(struct fsnotify_mark *mark, u32 mask, struct inode *inode, struct inode *dir, const struct qstr *file_name, u32 cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81232d60)
Location: kernel/audit_tree.c:1035
Inline: False
```
**Symbols:**

```
ffffffff81232d60-ffffffff81232d71: audit_tree_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int audit_tree_handle_event(struct fsnotify_mark *mark, u32 mask, struct inode *inode, struct inode *dir, const struct qstr *file_name, u32 cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff812499e0)
Location: kernel/audit_tree.c:1035
Inline: False
```
**Symbols:**

```
ffffffff812499e0-ffffffff812499f1: audit_tree_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int audit_tree_handle_event(struct fsnotify_mark *mark, u32 mask, struct inode *inode, struct inode *dir, const struct qstr *file_name, u32 cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff812638f0)
Location: kernel/audit_tree.c:1035
Inline: False
```
**Symbols:**

```
ffffffff812638f0-ffffffff81263901: audit_tree_handle_event (STB_LOCAL)
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
int audit_tree_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffff8000101f4278)
Location: kernel/audit_tree.c:1040
Inline: False
```
**Symbols:**

```
ffff8000101f4278-ffff8000101f4294: audit_tree_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int audit_tree_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (c0434610)
Location: kernel/audit_tree.c:1040
Inline: False
```
**Symbols:**

```
c0434610-c043462c: audit_tree_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int audit_tree_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (c000000000269570)
Location: kernel/audit_tree.c:1040
Inline: False
```
**Symbols:**

```
c000000000269570-c000000000269580: audit_tree_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int audit_tree_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffe00016754a)
Location: kernel/audit_tree.c:1040
Inline: False
```
**Symbols:**

```
ffffffe00016754a-ffffffe000167566: audit_tree_handle_event (STB_LOCAL)
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
int audit_tree_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff811778c0)
Location: kernel/audit_tree.c:1040
Inline: False
```
**Symbols:**

```
ffffffff811778c0-ffffffff811778cd: audit_tree_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int audit_tree_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8116aa60)
Location: kernel/audit_tree.c:1040
Inline: False
```
**Symbols:**

```
ffffffff8116aa60-ffffffff8116aa6d: audit_tree_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int audit_tree_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81175690)
Location: kernel/audit_tree.c:1040
Inline: False
```
**Symbols:**

```
ffffffff81175690-ffffffff8117569d: audit_tree_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int audit_tree_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff81182f70)
Location: kernel/audit_tree.c:1040
Inline: False
```
**Symbols:**

```
ffffffff81182f70-ffffffff81182f7d: audit_tree_handle_event (STB_LOCAL)
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
<code>group, to_tell, inode_mark, vfsmount_mark, mask, data, data_type, file_name, cookie, iter_info</code> ➡️ <code>group, to_tell, mask, data, data_type, file_name, cookie, iter_info</code>
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
<code>const unsigned char *file_name</code> ➡️ <code>const struct qstr *file_name</code>
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
<code>struct fsnotify_mark *mark</code>
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
<code>group, to_tell, mask, data, data_type, file_name, cookie, iter_info</code> ➡️ <code>mark, mask, inode, dir, file_name, cookie</code>
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
