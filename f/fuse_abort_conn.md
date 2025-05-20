# Function: <code>fuse_abort_conn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void fuse_abort_conn(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81310450)
Location: fs/fuse/dev.c:2140
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/inode.c:fuse_umount_begin
  - fs/fuse/inode.c:fuse_put_super
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff81310450-ffffffff813107a8: fuse_abort_conn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void fuse_abort_conn(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81344820)
Location: fs/fuse/dev.c:2113
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/inode.c:fuse_put_super
  - fs/fuse/inode.c:fuse_umount_begin
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff81344820-ffffffff81344b80: fuse_abort_conn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void fuse_abort_conn(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8135a5e0)
Location: fs/fuse/dev.c:2085
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/inode.c:fuse_put_super
  - fs/fuse/inode.c:fuse_umount_begin
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff8135a5e0-ffffffff8135a95e: fuse_abort_conn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void fuse_abort_conn(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8136f850)
Location: fs/fuse/dev.c:2089
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/inode.c:fuse_put_super
  - fs/fuse/inode.c:fuse_umount_begin
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff8136f850-ffffffff8136fbb2: fuse_abort_conn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void fuse_abort_conn(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81394560)
Location: fs/fuse/dev.c:2089
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/inode.c:fuse_put_super
  - fs/fuse/inode.c:fuse_umount_begin
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff81394560-ffffffff813948c9: fuse_abort_conn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fuse_abort_conn(struct fuse_conn *fc, bool is_abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813c35a0)
Location: fs/fuse/dev.c:2096
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/inode.c:fuse_sb_destroy
  - fs/fuse/inode.c:fuse_umount_begin
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff813c35a0-ffffffff813c3911: fuse_abort_conn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fuse_abort_conn(struct fuse_conn *fc, bool is_abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813dcd70)
Location: fs/fuse/dev.c:2162
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/inode.c:fuse_sb_destroy
  - fs/fuse/inode.c:fuse_umount_begin
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff813dcd70-ffffffff813dd0c0: fuse_abort_conn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fuse_abort_conn(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81408870)
Location: fs/fuse/dev.c:2180
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/inode.c:fuse_sb_destroy
  - fs/fuse/inode.c:fuse_umount_begin
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff81408870-ffffffff81408bea: fuse_abort_conn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fuse_abort_conn(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81420180)
Location: fs/fuse/dev.c:2088
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/inode.c:fuse_sb_destroy
  - fs/fuse/inode.c:fuse_umount_begin
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff81420180-ffffffff814204f4: fuse_abort_conn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fuse_abort_conn(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8146eec0)
Location: fs/fuse/dev.c:2093
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/inode.c:fuse_umount_begin
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff8146eec0-ffffffff8146f27b: fuse_abort_conn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fuse_abort_conn(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81489620)
Location: fs/fuse/dev.c:2104
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/inode.c:fuse_conn_destroy
  - fs/fuse/inode.c:fuse_umount_begin
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff81489620-ffffffff814899db: fuse_abort_conn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fuse_abort_conn(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8148eeb0)
Location: fs/fuse/dev.c:2110
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/inode.c:fuse_conn_destroy
  - fs/fuse/inode.c:fuse_umount_begin
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff8148eeb0-ffffffff8148f24a: fuse_abort_conn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fuse_abort_conn(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff814e6920)
Location: fs/fuse/dev.c:2130
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/inode.c:fuse_conn_destroy
  - fs/fuse/inode.c:fuse_umount_begin
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff814e6920-ffffffff814e6cba: fuse_abort_conn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fuse_abort_conn(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff815746a0)
Location: fs/fuse/dev.c:2122
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/inode.c:fuse_conn_destroy
  - fs/fuse/inode.c:fuse_umount_begin
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff815746a0-ffffffff81574a61: fuse_abort_conn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fuse_abort_conn(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8161a4a0)
Location: fs/fuse/dev.c:2123
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/inode.c:fuse_conn_destroy
  - fs/fuse/inode.c:fuse_umount_begin
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff8161a4a0-ffffffff8161a865: fuse_abort_conn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fuse_abort_conn(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff816527a0)
Location: fs/fuse/dev.c:2125
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/inode.c:fuse_conn_destroy
  - fs/fuse/inode.c:fuse_umount_begin
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff816527a0-ffffffff81652b61: fuse_abort_conn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fuse_abort_conn(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8168bdb0)
Location: fs/fuse/dev.c:2125
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/inode.c:fuse_conn_destroy
  - fs/fuse/inode.c:fuse_umount_begin
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff8168bdb0-ffffffff8168c171: fuse_abort_conn (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void fuse_abort_conn(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffff800010502b90)
Location: fs/fuse/dev.c:2088
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/inode.c:fuse_sb_destroy
  - fs/fuse/inode.c:fuse_umount_begin
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffff800010502b90-ffff8000105030b4: fuse_abort_conn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fuse_abort_conn(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (c06bef48)
Location: fs/fuse/dev.c:2088
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/inode.c:fuse_sb_destroy
  - fs/fuse/inode.c:fuse_umount_begin
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
c06bef48-c06bf2b8: fuse_abort_conn.part.0 (STB_LOCAL)
c06bf2b8-c06bf308: fuse_abort_conn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fuse_abort_conn(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (c000000000646fe0)
Location: fs/fuse/dev.c:2088
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/inode.c:fuse_sb_destroy
  - fs/fuse/inode.c:fuse_umount_begin
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
c000000000646fe0-c000000000647514: fuse_abort_conn.part.0 (STB_LOCAL)
c000000000647520-c0000000006475cc: fuse_abort_conn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fuse_abort_conn(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffe00036fa70)
Location: fs/fuse/dev.c:2088
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/inode.c:fuse_sb_destroy
  - fs/fuse/inode.c:fuse_umount_begin
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffe00036fa70-ffffffe00036fe82: fuse_abort_conn (STB_GLOBAL)
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
void fuse_abort_conn(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81418760)
Location: fs/fuse/dev.c:2088
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/inode.c:fuse_sb_destroy
  - fs/fuse/inode.c:fuse_umount_begin
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff81418760-ffffffff81418ad4: fuse_abort_conn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fuse_abort_conn(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff814091e0)
Location: fs/fuse/dev.c:2088
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/inode.c:fuse_sb_destroy
  - fs/fuse/inode.c:fuse_umount_begin
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff814091e0-ffffffff81409554: fuse_abort_conn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fuse_abort_conn(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81414900)
Location: fs/fuse/dev.c:2088
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/inode.c:fuse_sb_destroy
  - fs/fuse/inode.c:fuse_umount_begin
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff81414900-ffffffff81414c74: fuse_abort_conn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fuse_abort_conn(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8142b170)
Location: fs/fuse/dev.c:2088
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/inode.c:fuse_sb_destroy
  - fs/fuse/inode.c:fuse_umount_begin
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff8142b170-ffffffff8142b4de: fuse_abort_conn (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool is_abort</code>
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
<b>Param removed. </b>
<code>bool is_abort</code>
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
