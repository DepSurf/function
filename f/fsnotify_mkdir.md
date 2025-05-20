# Function: <code>fsnotify_mkdir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8121857d)
Location: include/linux/fsnotify.h:181
Inline: True
Inline callers:
  - fs/namei.c:vfs_mkdir
```
```
In fs/debugfs/inode.c (ffffffff8131dd16)
Location: include/linux/fsnotify.h:181
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_dir
```
```
In fs/tracefs/inode.c (ffffffff8131f375)
Location: include/linux/fsnotify.h:181
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812403f3)
Location: include/linux/fsnotify.h:160
Inline: True
Inline callers:
  - fs/namei.c:vfs_mkdir
```
```
In fs/debugfs/inode.c (ffffffff813528c0)
Location: include/linux/fsnotify.h:160
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
```
```
In fs/tracefs/inode.c (ffffffff81354835)
Location: include/linux/fsnotify.h:160
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81253d03)
Location: include/linux/fsnotify.h:164
Inline: True
Inline callers:
  - fs/namei.c:vfs_mkdir
```
```
In fs/debugfs/inode.c (ffffffff81368b70)
Location: include/linux/fsnotify.h:164
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
```
```
In fs/tracefs/inode.c (ffffffff8136aaf5)
Location: include/linux/fsnotify.h:164
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125ff16)
Location: include/linux/fsnotify.h:164
Inline: True
Inline callers:
  - fs/namei.c:vfs_mkdir
```
```
In fs/debugfs/inode.c (ffffffff8137d200)
Location: include/linux/fsnotify.h:164
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
```
```
In fs/tracefs/inode.c (ffffffff8137f145)
Location: include/linux/fsnotify.h:164
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812825fc)
Location: include/linux/fsnotify.h:165
Inline: True
Inline callers:
  - fs/namei.c:vfs_mkdir
```
```
In fs/debugfs/inode.c (ffffffff813a2110)
Location: include/linux/fsnotify.h:165
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
```
```
In fs/tracefs/inode.c (ffffffff813a4185)
Location: include/linux/fsnotify.h:165
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a976c)
Location: include/linux/fsnotify.h:165
Inline: True
Inline callers:
  - fs/namei.c:vfs_mkdir
```
```
In fs/debugfs/inode.c (ffffffff813d136a)
Location: include/linux/fsnotify.h:165
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
```
```
In fs/tracefs/inode.c (ffffffff813d356f)
Location: include/linux/fsnotify.h:165
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bf25c)
Location: include/linux/fsnotify.h:177
Inline: True
Inline callers:
  - fs/namei.c:vfs_mkdir
```
```
In fs/debugfs/inode.c (ffffffff813ebc10)
Location: include/linux/fsnotify.h:177
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
```
```
In fs/tracefs/inode.c (ffffffff813edc5f)
Location: include/linux/fsnotify.h:177
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
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
In fs/namei.c (ffffffff812dbe63)
Location: include/linux/fsnotify.h:207
Inline: True
Inline callers:
  - fs/namei.c:vfs_mkdir
```
```
In fs/debugfs/inode.c (ffffffff81417cfe)
Location: include/linux/fsnotify.h:207
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
```
```
In fs/tracefs/inode.c (ffffffff81419eef)
Location: include/linux/fsnotify.h:207
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
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
In fs/namei.c (ffffffff812ed973)
Location: include/linux/fsnotify.h:207
Inline: True
Inline callers:
  - fs/namei.c:vfs_mkdir
```
```
In fs/debugfs/inode.c (ffffffff81431bbe)
Location: include/linux/fsnotify.h:207
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
```
```
In fs/tracefs/inode.c (ffffffff81433d3f)
Location: include/linux/fsnotify.h:207
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
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
In fs/namei.c (ffffffff81325117)
Location: include/linux/fsnotify.h:224
Inline: True
Inline callers:
  - fs/namei.c:vfs_mkdir
```
```
In fs/debugfs/inode.c (ffffffff814814aa)
Location: include/linux/fsnotify.h:224
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
```
```
In fs/tracefs/inode.c (ffffffff81483a6b)
Location: include/linux/fsnotify.h:224
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
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
In fs/namei.c (ffffffff813308bb)
Location: include/linux/fsnotify.h:222
Inline: True
Inline callers:
  - fs/namei.c:vfs_mkdir
```
```
In fs/debugfs/inode.c (ffffffff8149ef73)
Location: include/linux/fsnotify.h:222
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
```
```
In fs/tracefs/inode.c (ffffffff814a10df)
Location: include/linux/fsnotify.h:222
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
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
In fs/namei.c (ffffffff8133711d)
Location: include/linux/fsnotify.h:222
Inline: True
Inline callers:
  - fs/namei.c:vfs_mkdir
```
```
In fs/debugfs/inode.c (ffffffff814a4f53)
Location: include/linux/fsnotify.h:222
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
```
```
In fs/tracefs/inode.c (ffffffff814a720f)
Location: include/linux/fsnotify.h:222
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
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
In fs/namei.c (ffffffff81384b3d)
Location: include/linux/fsnotify.h:267
Inline: True
Inline callers:
  - fs/namei.c:vfs_mkdir
```
```
In fs/debugfs/inode.c (ffffffff814fd07c)
Location: include/linux/fsnotify.h:267
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
```
```
In fs/tracefs/inode.c (ffffffff814ff2bf)
Location: include/linux/fsnotify.h:267
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
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
In fs/namei.c (ffffffff81402387)
Location: include/linux/fsnotify.h:284
Inline: True
Inline callers:
  - fs/namei.c:vfs_mkdir
```
```
In fs/debugfs/inode.c (ffffffff8158d8cd)
Location: include/linux/fsnotify.h:284
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
```
```
In fs/tracefs/inode.c (ffffffff81590589)
Location: include/linux/fsnotify.h:284
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
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
In fs/namei.c (ffffffff8148c613)
Location: include/linux/fsnotify.h:284
Inline: True
Inline callers:
  - fs/namei.c:vfs_mkdir
```
```
In fs/debugfs/inode.c (ffffffff816347dd)
Location: include/linux/fsnotify.h:284
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
```
```
In fs/tracefs/inode.c (ffffffff81637a09)
Location: include/linux/fsnotify.h:284
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
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
In fs/namei.c (ffffffff814c2fad)
Location: include/linux/fsnotify.h:286
Inline: True
Inline callers:
  - fs/namei.c:vfs_mkdir
```
```
In fs/debugfs/inode.c (ffffffff8166caed)
Location: include/linux/fsnotify.h:286
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
```
```
In fs/tracefs/inode.c (ffffffff8166fe09)
Location: include/linux/fsnotify.h:286
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
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
In fs/namei.c (ffffffff814f5473)
Location: include/linux/fsnotify.h:324
Inline: True
Inline callers:
  - fs/namei.c:vfs_mkdir
```
```
In fs/debugfs/inode.c (ffffffff816a7079)
Location: include/linux/fsnotify.h:324
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
```
```
In fs/tracefs/inode.c (ffffffff816aaa1f)
Location: include/linux/fsnotify.h:324
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
```
```
In fs/tracefs/event_inode.c (ffffffff816abf1f)
Location: include/linux/fsnotify.h:324
Inline: True
Inline callers:
  - fs/tracefs/event_inode.c:eventfs_create_events_dir
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
In fs/namei.c (ffff8000103971c0)
Location: include/linux/fsnotify.h:207
Inline: True
Inline callers:
  - fs/namei.c:vfs_mkdir
```
```
In fs/debugfs/inode.c (ffff80001051691c)
Location: include/linux/fsnotify.h:207
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
```
```
In fs/tracefs/inode.c (ffff800010519800)
Location: include/linux/fsnotify.h:207
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
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
In fs/namei.c (c057c874)
Location: include/linux/fsnotify.h:207
Inline: True
Inline callers:
  - fs/namei.c:vfs_mkdir
```
```
In fs/debugfs/inode.c (c06d16d4)
Location: include/linux/fsnotify.h:207
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
```
```
In fs/tracefs/inode.c (c06d3f0c)
Location: include/linux/fsnotify.h:207
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
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
In fs/namei.c (c00000000048fb70)
Location: include/linux/fsnotify.h:207
Inline: True
Inline callers:
  - fs/namei.c:vfs_mkdir
```
```
In fs/debugfs/inode.c (c00000000065f8e8)
Location: include/linux/fsnotify.h:207
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
```
```
In fs/tracefs/inode.c (c000000000662e70)
Location: include/linux/fsnotify.h:207
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
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
In fs/namei.c (ffffffe00026533e)
Location: include/linux/fsnotify.h:207
Inline: True
Inline callers:
  - fs/namei.c:vfs_mkdir
```
```
In fs/debugfs/inode.c (ffffffe000380022)
Location: include/linux/fsnotify.h:207
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
```
```
In fs/tracefs/inode.c (ffffffe000382b1c)
Location: include/linux/fsnotify.h:207
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
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
In fs/namei.c (ffffffff812e5f53)
Location: include/linux/fsnotify.h:207
Inline: True
Inline callers:
  - fs/namei.c:vfs_mkdir
```
```
In fs/debugfs/inode.c (ffffffff8142a19e)
Location: include/linux/fsnotify.h:207
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
```
```
In fs/tracefs/inode.c (ffffffff8142c31f)
Location: include/linux/fsnotify.h:207
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
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
In fs/namei.c (ffffffff812d6b93)
Location: include/linux/fsnotify.h:207
Inline: True
Inline callers:
  - fs/namei.c:vfs_mkdir
```
```
In fs/debugfs/inode.c (ffffffff8141ac1e)
Location: include/linux/fsnotify.h:207
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
```
```
In fs/tracefs/inode.c (ffffffff8141cd9f)
Location: include/linux/fsnotify.h:207
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
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
In fs/namei.c (ffffffff812e3d63)
Location: include/linux/fsnotify.h:207
Inline: True
Inline callers:
  - fs/namei.c:vfs_mkdir
```
```
In fs/debugfs/inode.c (ffffffff8142633e)
Location: include/linux/fsnotify.h:207
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
```
```
In fs/tracefs/inode.c (ffffffff814284bf)
Location: include/linux/fsnotify.h:207
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
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
In fs/namei.c (ffffffff812f3e33)
Location: include/linux/fsnotify.h:207
Inline: True
Inline callers:
  - fs/namei.c:vfs_mkdir
```
```
In fs/debugfs/inode.c (ffffffff8143d1fe)
Location: include/linux/fsnotify.h:207
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
```
```
In fs/tracefs/inode.c (ffffffff8143f37f)
Location: include/linux/fsnotify.h:207
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
```
</details>
</li>
</ul>

## Differences
