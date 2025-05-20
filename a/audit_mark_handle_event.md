# Function: <code>audit_mark_handle_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int audit_mark_handle_event(struct fsnotify_group *group, struct inode *to_tell, struct fsnotify_mark *inode_mark, struct fsnotify_mark *vfsmount_mark, u32 mask, void *data, int data_type, const unsigned char *dname, u32 cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff8112a720)
Location: kernel/audit_fsnotify.c:167
Inline: False
```
**Symbols:**

```
ffffffff8112a720-ffffffff8112a8a2: audit_mark_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int audit_mark_handle_event(struct fsnotify_group *group, struct inode *to_tell, struct fsnotify_mark *inode_mark, struct fsnotify_mark *vfsmount_mark, u32 mask, void *data, int data_type, const unsigned char *dname, u32 cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff811328f0)
Location: kernel/audit_fsnotify.c:167
Inline: False
```
**Symbols:**

```
ffffffff811328f0-ffffffff81132a84: audit_mark_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int audit_mark_handle_event(struct fsnotify_group *group, struct inode *to_tell, struct fsnotify_mark *inode_mark, struct fsnotify_mark *vfsmount_mark, u32 mask, const void *data, int data_type, const unsigned char *dname, u32 cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff8113c650)
Location: kernel/audit_fsnotify.c:166
Inline: False
```
**Symbols:**

```
ffffffff8113c650-ffffffff8113c7d7: audit_mark_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int audit_mark_handle_event(struct fsnotify_group *group, struct inode *to_tell, struct fsnotify_mark *inode_mark, struct fsnotify_mark *vfsmount_mark, u32 mask, const void *data, int data_type, const unsigned char *dname, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff8113dd00)
Location: kernel/audit_fsnotify.c:166
Inline: False
```
**Symbols:**

```
ffffffff8113dd00-ffffffff8113de79: audit_mark_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int audit_mark_handle_event(struct fsnotify_group *group, struct inode *to_tell, struct fsnotify_mark *inode_mark, struct fsnotify_mark *vfsmount_mark, u32 mask, const void *data, int data_type, const unsigned char *dname, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff8114aad0)
Location: kernel/audit_fsnotify.c:166
Inline: False
```
**Symbols:**

```
ffffffff8114aad0-ffffffff8114ac49: audit_mark_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int audit_mark_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const unsigned char *dname, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff81159520)
Location: kernel/audit_fsnotify.c:166
Inline: False
```
**Symbols:**

```
ffffffff81159520-ffffffff811596b0: audit_mark_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int audit_mark_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const unsigned char *dname, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff811664c0)
Location: kernel/audit_fsnotify.c:164
Inline: False
```
**Symbols:**

```
ffffffff811664c0-ffffffff81166612: audit_mark_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int audit_mark_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const struct qstr *dname, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff81173070)
Location: kernel/audit_fsnotify.c:155
Inline: False
```
**Symbols:**

```
ffffffff81173070-ffffffff811731d5: audit_mark_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int audit_mark_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const struct qstr *dname, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff8117eee0)
Location: kernel/audit_fsnotify.c:155
Inline: False
```
**Symbols:**

```
ffffffff8117eee0-ffffffff8117f045: audit_mark_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int audit_mark_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const struct qstr *dname, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff811924b0)
Location: kernel/audit_fsnotify.c:155
Inline: False
```
**Symbols:**

```
ffffffff811924b0-ffffffff81192554: audit_mark_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int audit_mark_handle_event(struct fsnotify_mark *inode_mark, u32 mask, struct inode *inode, struct inode *dir, const struct qstr *dname, u32 cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff8118f640)
Location: kernel/audit_fsnotify.c:155
Inline: False
```
**Symbols:**

```
ffffffff8118f640-ffffffff8118f6c4: audit_mark_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int audit_mark_handle_event(struct fsnotify_mark *inode_mark, u32 mask, struct inode *inode, struct inode *dir, const struct qstr *dname, u32 cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff811904e0)
Location: kernel/audit_fsnotify.c:155
Inline: False
```
**Symbols:**

```
ffffffff811904e0-ffffffff8119060b: audit_mark_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int audit_mark_handle_event(struct fsnotify_mark *inode_mark, u32 mask, struct inode *inode, struct inode *dir, const struct qstr *dname, u32 cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff811b93c0)
Location: kernel/audit_fsnotify.c:155
Inline: False
```
**Symbols:**

```
ffffffff811b93c0-ffffffff811b94eb: audit_mark_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int audit_mark_handle_event(struct fsnotify_mark *inode_mark, u32 mask, struct inode *inode, struct inode *dir, const struct qstr *dname, u32 cookie);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff811ec430)
Location: kernel/audit_fsnotify.c:156
Inline: True
```
**Symbols:**

```
ffffffff811ec430-ffffffff811ec59b: audit_mark_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int audit_mark_handle_event(struct fsnotify_mark *inode_mark, u32 mask, struct inode *inode, struct inode *dir, const struct qstr *dname, u32 cookie);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff812328e0)
Location: kernel/audit_fsnotify.c:156
Inline: True
```
**Symbols:**

```
ffffffff812328e0-ffffffff81232a4b: audit_mark_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int audit_mark_handle_event(struct fsnotify_mark *inode_mark, u32 mask, struct inode *inode, struct inode *dir, const struct qstr *dname, u32 cookie);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff81249560)
Location: kernel/audit_fsnotify.c:156
Inline: True
```
**Symbols:**

```
ffffffff81249560-ffffffff812496cb: audit_mark_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int audit_mark_handle_event(struct fsnotify_mark *inode_mark, u32 mask, struct inode *inode, struct inode *dir, const struct qstr *dname, u32 cookie);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff81263450)
Location: kernel/audit_fsnotify.c:156
Inline: True
```
**Symbols:**

```
ffffffff81263450-ffffffff812635bb: audit_mark_handle_event (STB_LOCAL)
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
int audit_mark_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const struct qstr *dname, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffff8000101f3df8)
Location: kernel/audit_fsnotify.c:155
Inline: False
```
**Symbols:**

```
ffff8000101f3df8-ffff8000101f3f98: audit_mark_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int audit_mark_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const struct qstr *dname, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (c0434230)
Location: kernel/audit_fsnotify.c:155
Inline: False
```
**Symbols:**

```
c0434230-c043439c: audit_mark_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int audit_mark_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const struct qstr *dname, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (c000000000268e00)
Location: kernel/audit_fsnotify.c:155
Inline: False
```
**Symbols:**

```
c000000000268e00-c000000000269030: audit_mark_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int audit_mark_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const struct qstr *dname, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffe0001671a4)
Location: kernel/audit_fsnotify.c:155
Inline: False
```
**Symbols:**

```
ffffffe0001671a4-ffffffe0001672fe: audit_mark_handle_event (STB_LOCAL)
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
int audit_mark_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const struct qstr *dname, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff81177500)
Location: kernel/audit_fsnotify.c:155
Inline: False
```
**Symbols:**

```
ffffffff81177500-ffffffff81177665: audit_mark_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int audit_mark_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const struct qstr *dname, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff8116a6a0)
Location: kernel/audit_fsnotify.c:155
Inline: False
```
**Symbols:**

```
ffffffff8116a6a0-ffffffff8116a805: audit_mark_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int audit_mark_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const struct qstr *dname, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff811752d0)
Location: kernel/audit_fsnotify.c:155
Inline: False
```
**Symbols:**

```
ffffffff811752d0-ffffffff81175435: audit_mark_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int audit_mark_handle_event(struct fsnotify_group *group, struct inode *to_tell, u32 mask, const void *data, int data_type, const struct qstr *dname, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff81182bb0)
Location: kernel/audit_fsnotify.c:155
Inline: False
```
**Symbols:**

```
ffffffff81182bb0-ffffffff81182d15: audit_mark_handle_event (STB_LOCAL)
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
