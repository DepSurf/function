# Function: <code>fuse_dev_install</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fuse_dev_install(struct fuse_dev *fud, struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8142ddc0)
Location: fs/fuse/inode.c:1081
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff8142ddc0-ffffffff8142de1b: fuse_dev_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void fuse_dev_install(struct fuse_dev *fud, struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8147e0d5)
Location: fs/fuse/inode.c:1095
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff8147d550-ffffffff8147d5d4: fuse_dev_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void fuse_dev_install(struct fuse_dev *fud, struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81499421)
Location: fs/fuse/inode.c:1195
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff81498520-ffffffff814985a4: fuse_dev_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void fuse_dev_install(struct fuse_dev *fud, struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8149e661)
Location: fs/fuse/inode.c:1237
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff8149da00-ffffffff8149da84: fuse_dev_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void fuse_dev_install(struct fuse_dev *fud, struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814f6991)
Location: fs/fuse/inode.c:1289
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff814f5ba0-ffffffff814f5c24: fuse_dev_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void fuse_dev_install(struct fuse_dev *fud, struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff815867ce)
Location: fs/fuse/inode.c:1345
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff81585170-ffffffff81585201: fuse_dev_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void fuse_dev_install(struct fuse_dev *fud, struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8162ca46)
Location: fs/fuse/inode.c:1357
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff8162b350-ffffffff8162b3e1: fuse_dev_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void fuse_dev_install(struct fuse_dev *fud, struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81664c7b)
Location: fs/fuse/inode.c:1363
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff81663580-ffffffff81663611: fuse_dev_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void fuse_dev_install(struct fuse_dev *fud, struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8169ef74)
Location: fs/fuse/inode.c:1442
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff8169d670-ffffffff8169d701: fuse_dev_install (STB_GLOBAL)
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
void fuse_dev_install(struct fuse_dev *fud, struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffff800010512210)
Location: fs/fuse/inode.c:1081
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffff800010512210-ffff8000105122a8: fuse_dev_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fuse_dev_install(struct fuse_dev *fud, struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (c06cc18c)
Location: fs/fuse/inode.c:1081
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
c06cc18c-c06cc1f0: fuse_dev_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fuse_dev_install(struct fuse_dev *fud, struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (c000000000658200)
Location: fs/fuse/inode.c:1081
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
c000000000658200-c0000000006582ec: fuse_dev_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fuse_dev_install(struct fuse_dev *fud, struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffe00037c414)
Location: fs/fuse/inode.c:1081
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffe00037c414-ffffffe00037c4ac: fuse_dev_install (STB_GLOBAL)
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
void fuse_dev_install(struct fuse_dev *fud, struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814263a0)
Location: fs/fuse/inode.c:1081
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff814263a0-ffffffff814263fb: fuse_dev_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fuse_dev_install(struct fuse_dev *fud, struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81416e20)
Location: fs/fuse/inode.c:1081
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff81416e20-ffffffff81416e7b: fuse_dev_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fuse_dev_install(struct fuse_dev *fud, struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81422540)
Location: fs/fuse/inode.c:1081
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff81422540-ffffffff8142259b: fuse_dev_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fuse_dev_install(struct fuse_dev *fud, struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81437de0)
Location: fs/fuse/inode.c:1081
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff81437de0-ffffffff81437e39: fuse_dev_install (STB_GLOBAL)
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
