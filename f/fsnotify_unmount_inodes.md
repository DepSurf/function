# Function: <code>fsnotify_unmount_inodes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fsnotify_unmount_inodes(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inode_mark.c (ffffffff81250060)
Location: fs/notify/inode_mark.c:151
Inline: False
Direct callers:
  - fs/super.c:generic_shutdown_super
```
**Symbols:**

```
ffffffff81250060-ffffffff8125022b: fsnotify_unmount_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fsnotify_unmount_inodes(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inode_mark.c (ffffffff812787c0)
Location: fs/notify/inode_mark.c:151
Inline: False
Direct callers:
  - fs/super.c:generic_shutdown_super
```
**Symbols:**

```
ffffffff812787c0-ffffffff8127897a: fsnotify_unmount_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fsnotify_unmount_inodes(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inode_mark.c (ffffffff8128c4a0)
Location: fs/notify/inode_mark.c:151
Inline: False
Direct callers:
  - fs/super.c:generic_shutdown_super
```
**Symbols:**

```
ffffffff8128c4a0-ffffffff8128c5a1: fsnotify_unmount_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fsnotify_unmount_inodes(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81298bf0)
Location: fs/notify/fsnotify.c:51
Inline: False
Direct callers:
  - fs/super.c:generic_shutdown_super
```
**Symbols:**

```
ffffffff81298bf0-ffffffff81298cf9: fsnotify_unmount_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fsnotify_unmount_inodes(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff812bbf80)
Location: fs/notify/fsnotify.c:51
Inline: False
Direct callers:
  - fs/super.c:generic_shutdown_super
```
**Symbols:**

```
ffffffff812bbf80-ffffffff812bc089: fsnotify_unmount_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fsnotify_unmount_inodes(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff812e4ba0)
Location: fs/notify/fsnotify.c:51
Inline: False
Direct callers:
  - fs/super.c:generic_shutdown_super
```
**Symbols:**

```
ffffffff812e4ba0-ffffffff812e4ca8: fsnotify_unmount_inodes (STB_GLOBAL)
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
In fs/notify/fsnotify.c (ffffffff812f9642)
Location: fs/notify/fsnotify.c:51
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
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
In fs/notify/fsnotify.c (ffffffff81319ca2)
Location: fs/notify/fsnotify.c:38
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
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
In fs/notify/fsnotify.c (ffffffff8132cad2)
Location: fs/notify/fsnotify.c:38
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fsnotify_unmount_inodes(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff813665f0)
Location: fs/notify/fsnotify.c:38
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
**Symbols:**

```
ffffffff813665f0-ffffffff81366794: fsnotify_unmount_inodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fsnotify_unmount_inodes(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81373750)
Location: fs/notify/fsnotify.c:38
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
**Symbols:**

```
ffffffff81373750-ffffffff8137390f: fsnotify_unmount_inodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fsnotify_unmount_inodes(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff8137a0b0)
Location: fs/notify/fsnotify.c:38
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
**Symbols:**

```
ffffffff8137a0b0-ffffffff8137a26f: fsnotify_unmount_inodes (STB_LOCAL)
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
In fs/notify/fsnotify.c (ffffffff813c6d92)
Location: fs/notify/fsnotify.c:38
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
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
In fs/notify/fsnotify.c (ffffffff8144e0d2)
Location: fs/notify/fsnotify.c:38
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
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
In fs/notify/fsnotify.c (ffffffff814dc7c2)
Location: fs/notify/fsnotify.c:38
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
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
In fs/notify/fsnotify.c (ffffffff81513012)
Location: fs/notify/fsnotify.c:38
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
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
In fs/notify/fsnotify.c (ffffffff815474c2)
Location: fs/notify/fsnotify.c:38
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
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
In fs/notify/fsnotify.c (ffff8000103e8490)
Location: fs/notify/fsnotify.c:38
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
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
In fs/notify/fsnotify.c (c05bfe74)
Location: fs/notify/fsnotify.c:38
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
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
In fs/notify/fsnotify.c (c0000000004eeea4)
Location: fs/notify/fsnotify.c:38
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
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
In fs/notify/fsnotify.c (ffffffe00029d172)
Location: fs/notify/fsnotify.c:38
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
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
In fs/notify/fsnotify.c (ffffffff813250b2)
Location: fs/notify/fsnotify.c:38
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
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
In fs/notify/fsnotify.c (ffffffff81315c52)
Location: fs/notify/fsnotify.c:38
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
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
In fs/notify/fsnotify.c (ffffffff81322b82)
Location: fs/notify/fsnotify.c:38
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
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
In fs/notify/fsnotify.c (ffffffff813348d2)
Location: fs/notify/fsnotify.c:38
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
