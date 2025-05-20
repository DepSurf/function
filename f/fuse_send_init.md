# Function: <code>fuse_send_init</code>

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
In fs/fuse/inode.c (ffffffff8131c6b5)
Location: fs/fuse/inode.c:931
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super
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
In fs/fuse/inode.c (ffffffff8135117d)
Location: fs/fuse/inode.c:939
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super
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
In fs/fuse/inode.c (ffffffff81366b1a)
Location: fs/fuse/inode.c:947
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super
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
In fs/fuse/inode.c (ffffffff8137b1af)
Location: fs/fuse/inode.c:941
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super
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
In fs/fuse/inode.c (ffffffff813a0055)
Location: fs/fuse/inode.c:941
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super
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
In fs/fuse/inode.c (ffffffff813cf3f6)
Location: fs/fuse/inode.c:946
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super
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
In fs/fuse/inode.c (ffffffff813e8891)
Location: fs/fuse/inode.c:958
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super
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
In fs/fuse/inode.c (ffffffff81414944)
Location: fs/fuse/inode.c:958
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fuse_send_init(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8142cf50)
Location: fs/fuse/inode.c:973
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff8142cf50-ffffffff8142d022: fuse_send_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fuse_send_init(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8147d150)
Location: fs/fuse/inode.c:987
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff8147d150-ffffffff8147d23b: fuse_send_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fuse_send_init(struct fuse_mount *fm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81498320)
Location: fs/fuse/inode.c:1079
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff81498320-ffffffff81498449: fuse_send_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fuse_send_init(struct fuse_mount *fm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8149d550)
Location: fs/fuse/inode.c:1121
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff8149d550-ffffffff8149d679: fuse_send_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fuse_send_init(struct fuse_mount *fm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814f5000)
Location: fs/fuse/inode.c:1173
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff814f5000-ffffffff814f5129: fuse_send_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fuse_send_init(struct fuse_mount *fm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81584f20)
Location: fs/fuse/inode.c:1222
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff81584f20-ffffffff8158506f: fuse_send_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fuse_send_init(struct fuse_mount *fm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8162b0d0)
Location: fs/fuse/inode.c:1234
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff8162b0d0-ffffffff8162b21f: fuse_send_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fuse_send_init(struct fuse_mount *fm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff816632f0)
Location: fs/fuse/inode.c:1239
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff816632f0-ffffffff81663449: fuse_send_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fuse_send_init(struct fuse_mount *fm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8169d440)
Location: fs/fuse/inode.c:1318
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff8169d440-ffffffff8169d5c8: fuse_send_init (STB_GLOBAL)
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
void fuse_send_init(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffff800010512018)
Location: fs/fuse/inode.c:973
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffff800010512018-ffff800010512100: fuse_send_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fuse_send_init(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (c06cc638)
Location: fs/fuse/inode.c:973
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
c06cc638-c06cc720: fuse_send_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fuse_send_init(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (c000000000658a70)
Location: fs/fuse/inode.c:973
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
c000000000658a70-c000000000658ba8: fuse_send_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fuse_send_init(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffe00037b626)
Location: fs/fuse/inode.c:973
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffe00037b626-ffffffe00037b6f6: fuse_send_init (STB_GLOBAL)
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
void fuse_send_init(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81425530)
Location: fs/fuse/inode.c:973
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff81425530-ffffffff81425602: fuse_send_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fuse_send_init(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81415fb0)
Location: fs/fuse/inode.c:973
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff81415fb0-ffffffff81416082: fuse_send_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fuse_send_init(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814216d0)
Location: fs/fuse/inode.c:973
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff814216d0-ffffffff814217a2: fuse_send_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fuse_send_init(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81438550)
Location: fs/fuse/inode.c:973
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff81438550-ffffffff81438622: fuse_send_init (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fuse_mount *fm</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fuse_conn *fc</code>
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
