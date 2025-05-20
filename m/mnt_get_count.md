# Function: <code>mnt_get_count</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int mnt_get_count(struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122ce60)
Location: fs/namespace.c:177
Inline: False
Direct callers:
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:do_umount
  - fs/namespace.c:finish_automount
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
```
**Symbols:**

```
ffffffff8122ce60-ffffffff8122ceb8: mnt_get_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int mnt_get_count(struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812555f0)
Location: fs/namespace.c:177
Inline: False
Direct callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount_tree
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
```
**Symbols:**

```
ffffffff812555f0-ffffffff81255648: mnt_get_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int mnt_get_count(struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812689e0)
Location: fs/namespace.c:176
Inline: False
Direct callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount_tree
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
```
**Symbols:**

```
ffffffff812689e0-ffffffff81268a3d: mnt_get_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int mnt_get_count(struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81276190)
Location: fs/namespace.c:179
Inline: False
Direct callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount_tree
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
```
**Symbols:**

```
ffffffff81276190-ffffffff812761eb: mnt_get_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int mnt_get_count(struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81298ae0)
Location: fs/namespace.c:179
Inline: False
Direct callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_umount
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
```
**Symbols:**

```
ffffffff81298ae0-ffffffff81298b2e: mnt_get_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int mnt_get_count(struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812becc0)
Location: fs/namespace.c:179
Inline: False
Direct callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:ksys_umount
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
```
**Symbols:**

```
ffffffff812becc0-ffffffff812bed0e: mnt_get_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int mnt_get_count(struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d3f90)
Location: fs/namespace.c:154
Inline: False
Direct callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:ksys_umount
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
```
**Symbols:**

```
ffffffff812d3f90-ffffffff812d3fde: mnt_get_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int mnt_get_count(struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f0f80)
Location: fs/namespace.c:159
Inline: False
Direct callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:mntput_no_expire
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
```
**Symbols:**

```
ffffffff812f0f80-ffffffff812f0fca: mnt_get_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int mnt_get_count(struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81302b20)
Location: fs/namespace.c:159
Inline: False
Direct callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:mntput_no_expire
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
```
**Symbols:**

```
ffffffff81302b20-ffffffff81302b6a: mnt_get_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int mnt_get_count(struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133fa0a)
Location: fs/namespace.c:159
Inline: True
Inline callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
Direct callers:
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
```
**Symbols:**

```
ffffffff8133d150-ffffffff8133d19a: mnt_get_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int mnt_get_count(struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134ba6a)
Location: fs/namespace.c:159
Inline: True
Inline callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
Direct callers:
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
```
**Symbols:**

```
ffffffff81349010-ffffffff8134905a: mnt_get_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int mnt_get_count(struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81352300)
Location: fs/namespace.c:179
Inline: True
Inline callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
Direct callers:
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
```
**Symbols:**

```
ffffffff8134fa00-ffffffff8134fa52: mnt_get_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int mnt_get_count(struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff813a06b4)
Location: fs/namespace.c:179
Inline: True
Inline callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
Direct callers:
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
```
**Symbols:**

```
ffffffff8139dd30-ffffffff8139ddb3: mnt_get_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int mnt_get_count(struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81423fd4)
Location: fs/namespace.c:180
Inline: True
Inline callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
Direct callers:
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
```
**Symbols:**

```
ffffffff81420d10-ffffffff81420d9b: mnt_get_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mnt_get_count(struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814abb50)
Location: fs/namespace.c:197
Inline: False
Direct callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
```
**Symbols:**

```
ffffffff814abb50-ffffffff814abbe8: mnt_get_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mnt_get_count(struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e0910)
Location: fs/namespace.c:181
Inline: False
Direct callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
```
**Symbols:**

```
ffffffff814e0910-ffffffff814e09a8: mnt_get_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mnt_get_count(struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff815149e0)
Location: fs/namespace.c:186
Inline: False
Direct callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
```
**Symbols:**

```
ffffffff815149e0-ffffffff81514a78: mnt_get_count (STB_GLOBAL)
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
unsigned int mnt_get_count(struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b5e58)
Location: fs/namespace.c:159
Inline: False
Direct callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:mntput_no_expire
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
```
**Symbols:**

```
ffff8000103b5e58-ffff8000103b5ed8: mnt_get_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int mnt_get_count(struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c05941e0)
Location: fs/namespace.c:159
Inline: False
Direct callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_umount
  - fs/namespace.c:mntput_no_expire
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
```
**Symbols:**

```
c05941e0-c0594248: mnt_get_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int mnt_get_count(struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b2270)
Location: fs/namespace.c:159
Inline: False
Direct callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:may_umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
```
**Symbols:**

```
c0000000004b2270-c0000000004b2320: mnt_get_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int mnt_get_count(struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe000278ba6)
Location: fs/namespace.c:159
Inline: False
Direct callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:mntput_no_expire
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
```
**Symbols:**

```
ffffffe000278ba6-ffffffe000278c20: mnt_get_count (STB_GLOBAL)
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
unsigned int mnt_get_count(struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fb100)
Location: fs/namespace.c:159
Inline: False
Direct callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:mntput_no_expire
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
```
**Symbols:**

```
ffffffff812fb100-ffffffff812fb14a: mnt_get_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int mnt_get_count(struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ebd20)
Location: fs/namespace.c:159
Inline: False
Direct callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:mntput_no_expire
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
```
**Symbols:**

```
ffffffff812ebd20-ffffffff812ebd6a: mnt_get_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int mnt_get_count(struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f8ef0)
Location: fs/namespace.c:159
Inline: False
Direct callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:mntput_no_expire
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
```
**Symbols:**

```
ffffffff812f8ef0-ffffffff812f8f3a: mnt_get_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int mnt_get_count(struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8130a210)
Location: fs/namespace.c:159
Inline: False
Direct callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:mntput_no_expire
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
  - fs/pnode.c:propagate_mount_busy
```
**Symbols:**

```
ffffffff8130a210-ffffffff8130a25a: mnt_get_count (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>unsigned int</code> ➡️ <code>int</code>
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
