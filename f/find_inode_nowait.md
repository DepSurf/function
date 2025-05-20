# Function: <code>find_inode_nowait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct inode *find_inode_nowait(struct super_block *sb, long unsigned int hashval, int (*match)(struct inode *, long unsigned int, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81226850)
Location: fs/inode.c:1314
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
**Symbols:**

```
ffffffff81226850-ffffffff81226910: find_inode_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct inode *find_inode_nowait(struct super_block *sb, long unsigned int hashval, int (*match)(struct inode *, long unsigned int, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8124ef10)
Location: fs/inode.c:1323
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
**Symbols:**

```
ffffffff8124ef10-ffffffff8124efd0: find_inode_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct inode *find_inode_nowait(struct super_block *sb, long unsigned int hashval, int (*match)(struct inode *, long unsigned int, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81261f20)
Location: fs/inode.c:1352
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
**Symbols:**

```
ffffffff81261f20-ffffffff81261fe0: find_inode_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct inode *find_inode_nowait(struct super_block *sb, long unsigned int hashval, int (*match)(struct inode *, long unsigned int, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8126f7d0)
Location: fs/inode.c:1353
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
**Symbols:**

```
ffffffff8126f7d0-ffffffff8126f88e: find_inode_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct inode *find_inode_nowait(struct super_block *sb, long unsigned int hashval, int (*match)(struct inode *, long unsigned int, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812920f0)
Location: fs/inode.c:1353
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
**Symbols:**

```
ffffffff812920f0-ffffffff812921b0: find_inode_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct inode *find_inode_nowait(struct super_block *sb, long unsigned int hashval, int (*match)(struct inode *, long unsigned int, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812b9400)
Location: fs/inode.c:1374
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
**Symbols:**

```
ffffffff812b9400-ffffffff812b94c0: find_inode_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct inode *find_inode_nowait(struct super_block *sb, long unsigned int hashval, int (*match)(struct inode *, long unsigned int, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812ce740)
Location: fs/inode.c:1407
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
**Symbols:**

```
ffffffff812ce740-ffffffff812ce800: find_inode_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct inode *find_inode_nowait(struct super_block *sb, long unsigned int hashval, int (*match)(struct inode *, long unsigned int, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812eb630)
Location: fs/inode.c:1420
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
**Symbols:**

```
ffffffff812eb630-ffffffff812eb6f4: find_inode_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct inode *find_inode_nowait(struct super_block *sb, long unsigned int hashval, int (*match)(struct inode *, long unsigned int, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fd160)
Location: fs/inode.c:1431
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
**Symbols:**

```
ffffffff812fd160-ffffffff812fd224: find_inode_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inode *find_inode_nowait(struct super_block *sb, long unsigned int hashval, int (*match)(struct inode *, long unsigned int, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81335ba0)
Location: fs/inode.c:1429
Inline: False
```
**Symbols:**

```
ffffffff81335ba0-ffffffff81335c64: find_inode_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inode *find_inode_nowait(struct super_block *sb, long unsigned int hashval, int (*match)(struct inode *, long unsigned int, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81341520)
Location: fs/inode.c:1428
Inline: False
```
**Symbols:**

```
ffffffff81341520-ffffffff813415e4: find_inode_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inode *find_inode_nowait(struct super_block *sb, long unsigned int hashval, int (*match)(struct inode *, long unsigned int, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813478a0)
Location: fs/inode.c:1435
Inline: False
```
**Symbols:**

```
ffffffff813478a0-ffffffff81347964: find_inode_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct inode *find_inode_nowait(struct super_block *sb, long unsigned int hashval, int (*match)(struct inode *, long unsigned int, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:1439
Inline: False
```
**Symbols:**

```
ffffffff81cc3c50-ffffffff81cc3c7c: find_inode_nowait.cold (STB_LOCAL)
ffffffff81395470-ffffffff81395545: find_inode_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct inode *find_inode_nowait(struct super_block *sb, long unsigned int hashval, int (*match)(struct inode *, long unsigned int, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:1520
Inline: False
```
**Symbols:**

```
ffffffff81e76523-ffffffff81e7654f: find_inode_nowait.cold (STB_LOCAL)
ffffffff814184c0-ffffffff8141859f: find_inode_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct inode *find_inode_nowait(struct super_block *sb, long unsigned int hashval, int (*match)(struct inode *, long unsigned int, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:1522
Inline: False
```
**Symbols:**

```
ffffffff82068a76-ffffffff82068aa2: find_inode_nowait.cold (STB_LOCAL)
ffffffff814a3c80-ffffffff814a3d5f: find_inode_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct inode *find_inode_nowait(struct super_block *sb, long unsigned int hashval, int (*match)(struct inode *, long unsigned int, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:1566
Inline: False
```
**Symbols:**

```
ffffffff820e83b4-ffffffff820e83e0: find_inode_nowait.cold (STB_LOCAL)
ffffffff814d8e00-ffffffff814d8edf: find_inode_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct inode *find_inode_nowait(struct super_block *sb, long unsigned int hashval, int (*match)(struct inode *, long unsigned int, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:1514
Inline: False
```
**Symbols:**

```
ffffffff821c50f1-ffffffff821c511d: find_inode_nowait.cold (STB_LOCAL)
ffffffff8150b500-ffffffff8150b5df: find_inode_nowait (STB_GLOBAL)
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
struct inode *find_inode_nowait(struct super_block *sb, long unsigned int hashval, int (*match)(struct inode *, long unsigned int, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103ad938)
Location: fs/inode.c:1431
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
**Symbols:**

```
ffff8000103ad938-ffff8000103ada70: find_inode_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct inode *find_inode_nowait(struct super_block *sb, long unsigned int hashval, int (*match)(struct inode *, long unsigned int, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058c0c4)
Location: fs/inode.c:1431
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
**Symbols:**

```
c058c0c4-c058c1a4: find_inode_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct inode *find_inode_nowait(struct super_block *sb, long unsigned int hashval, int (*match)(struct inode *, long unsigned int, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004aa240)
Location: fs/inode.c:1431
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
**Symbols:**

```
c0000000004aa240-c0000000004aa3c8: find_inode_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct inode *find_inode_nowait(struct super_block *sb, long unsigned int hashval, int (*match)(struct inode *, long unsigned int, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe00027231e)
Location: fs/inode.c:1431
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
**Symbols:**

```
ffffffe00027231e-ffffffe000272410: find_inode_nowait (STB_GLOBAL)
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
struct inode *find_inode_nowait(struct super_block *sb, long unsigned int hashval, int (*match)(struct inode *, long unsigned int, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f5740)
Location: fs/inode.c:1431
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
**Symbols:**

```
ffffffff812f5740-ffffffff812f5804: find_inode_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct inode *find_inode_nowait(struct super_block *sb, long unsigned int hashval, int (*match)(struct inode *, long unsigned int, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e6360)
Location: fs/inode.c:1431
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
**Symbols:**

```
ffffffff812e6360-ffffffff812e6424: find_inode_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct inode *find_inode_nowait(struct super_block *sb, long unsigned int hashval, int (*match)(struct inode *, long unsigned int, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f3550)
Location: fs/inode.c:1431
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
**Symbols:**

```
ffffffff812f3550-ffffffff812f3614: find_inode_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct inode *find_inode_nowait(struct super_block *sb, long unsigned int hashval, int (*match)(struct inode *, long unsigned int, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81303200)
Location: fs/inode.c:1431
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
**Symbols:**

```
ffffffff81303200-ffffffff813032c2: find_inode_nowait (STB_GLOBAL)
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
