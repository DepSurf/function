# Function: <code>fsverity_cleanup_inode</code>

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
void fsverity_cleanup_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff81350940)
Location: fs/verity/open.c:335
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff81350940-ffffffff8135096c: fsverity_cleanup_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fsverity_cleanup_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff81397320)
Location: fs/verity/open.c:337
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff81397320-ffffffff81397364: fsverity_cleanup_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fsverity_cleanup_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff813a8d90)
Location: fs/verity/open.c:346
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff813a8d90-ffffffff813a8dd4: fsverity_cleanup_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fsverity_cleanup_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff813afe00)
Location: fs/verity/open.c:387
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff813afe00-ffffffff813afe44: fsverity_cleanup_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fsverity_cleanup_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff813ff9f0)
Location: fs/verity/open.c:387
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff813ff9f0-ffffffff813ffa34: fsverity_cleanup_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fsverity_cleanup_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff814737b0)
Location: fs/verity/open.c:383
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff814737b0-ffffffff814737fc: fsverity_cleanup_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fsverity_cleanup_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff815056e0)
Location: fs/verity/open.c:383
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff815056e0-ffffffff8150572c: fsverity_cleanup_inode (STB_GLOBAL)
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
In fs/ext4/super.c (ffffffff8160070c)
Location: include/linux/fsverity.h:161
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_clear_inode
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
In fs/ext4/super.c (ffffffff8163945a)
Location: include/linux/fsverity.h:161
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_clear_inode
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
void fsverity_cleanup_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffff8000104128d8)
Location: fs/verity/open.c:335
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffff8000104128d8-ffff80001041290c: fsverity_cleanup_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fsverity_cleanup_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (c05dec50)
Location: fs/verity/open.c:335
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
c05dec50-c05dec84: fsverity_cleanup_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fsverity_cleanup_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (c000000000520440)
Location: fs/verity/open.c:335
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
c000000000520440-c000000000520490: fsverity_cleanup_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fsverity_cleanup_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffe0002ba554)
Location: fs/verity/open.c:335
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffe0002ba554-ffffffe0002ba586: fsverity_cleanup_inode (STB_GLOBAL)
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
void fsverity_cleanup_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff81348f20)
Location: fs/verity/open.c:335
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff81348f20-ffffffff81348f4c: fsverity_cleanup_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fsverity_cleanup_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff81339c00)
Location: fs/verity/open.c:335
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff81339c00-ffffffff81339c2c: fsverity_cleanup_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fsverity_cleanup_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff813469f0)
Location: fs/verity/open.c:335
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff813469f0-ffffffff81346a1c: fsverity_cleanup_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fsverity_cleanup_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff81359cd0)
Location: fs/verity/open.c:335
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff81359cd0-ffffffff81359cfc: fsverity_cleanup_inode (STB_GLOBAL)
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
