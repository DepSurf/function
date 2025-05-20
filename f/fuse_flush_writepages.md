# Function: <code>fuse_flush_writepages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fuse_flush_writepages(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813199b0)
Location: fs/fuse/file.c:1503
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepages_send
```
**Symbols:**

```
ffffffff813199b0-ffffffff81319a31: fuse_flush_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fuse_flush_writepages(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8134e4b0)
Location: fs/fuse/file.c:1516
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff8134e4b0-ffffffff8134e52b: fuse_flush_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fuse_flush_writepages(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81363db0)
Location: fs/fuse/file.c:1517
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff81363db0-ffffffff81363e2b: fuse_flush_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fuse_flush_writepages(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81378630)
Location: fs/fuse/file.c:1512
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff81378630-ffffffff813786ab: fuse_flush_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fuse_flush_writepages(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8139d4d0)
Location: fs/fuse/file.c:1520
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff8139d4d0-ffffffff8139d54b: fuse_flush_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fuse_flush_writepages(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813cc8b0)
Location: fs/fuse/file.c:1521
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff813cc8b0-ffffffff813cc92b: fuse_flush_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fuse_flush_writepages(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813e5be0)
Location: fs/fuse/file.c:1527
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff813e5be0-ffffffff813e5c5b: fuse_flush_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fuse_flush_writepages(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81411b50)
Location: fs/fuse/file.c:1592
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff81411b50-ffffffff81411bcb: fuse_flush_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fuse_flush_writepages(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8142b840)
Location: fs/fuse/file.c:1688
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff8142b840-ffffffff8142b8c2: fuse_flush_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fuse_flush_writepages(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8147b5f0)
Location: fs/fuse/file.c:1661
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff8147b5f0-ffffffff8147b672: fuse_flush_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fuse_flush_writepages(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81496370)
Location: fs/fuse/file.c:1701
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff81496370-ffffffff814963f2: fuse_flush_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fuse_flush_writepages(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8149b400)
Location: fs/fuse/file.c:1703
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff8149b400-ffffffff8149b482: fuse_flush_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fuse_flush_writepages(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814f2e50)
Location: fs/fuse/file.c:1709
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff814f2e50-ffffffff814f2ed2: fuse_flush_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fuse_flush_writepages(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff815828b0)
Location: fs/fuse/file.c:1724
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff815828b0-ffffffff81582940: fuse_flush_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fuse_flush_writepages(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff816287e0)
Location: fs/fuse/file.c:1759
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff816287e0-ffffffff81628870: fuse_flush_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fuse_flush_writepages(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81660a10)
Location: fs/fuse/file.c:1736
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff81660a10-ffffffff81660aa0: fuse_flush_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fuse_flush_writepages(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8169a8d0)
Location: fs/fuse/file.c:1756
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff8169a8d0-ffffffff8169a960: fuse_flush_writepages (STB_GLOBAL)
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
void fuse_flush_writepages(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffff80001050f6a8)
Location: fs/fuse/file.c:1688
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffff80001050f6a8-ffff80001050f730: fuse_flush_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fuse_flush_writepages(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c06caf24)
Location: fs/fuse/file.c:1688
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
c06caf24-c06caff0: fuse_flush_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fuse_flush_writepages(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c000000000656cb0)
Location: fs/fuse/file.c:1688
Inline: False
Direct callers:
  - fs/fuse/dir.c:__fuse_release_nowrite
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
c000000000656cb0-c000000000656d64: fuse_flush_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fuse_flush_writepages(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffe000379fb0)
Location: fs/fuse/file.c:1688
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffe000379fb0-ffffffe00037a024: fuse_flush_writepages (STB_GLOBAL)
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
void fuse_flush_writepages(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81423e20)
Location: fs/fuse/file.c:1688
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff81423e20-ffffffff81423ea2: fuse_flush_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fuse_flush_writepages(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814148a0)
Location: fs/fuse/file.c:1688
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff814148a0-ffffffff81414922: fuse_flush_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fuse_flush_writepages(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8141ffc0)
Location: fs/fuse/file.c:1688
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff8141ffc0-ffffffff81420042: fuse_flush_writepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fuse_flush_writepages(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81436d40)
Location: fs/fuse/file.c:1688
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_release_nowrite
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff81436d40-ffffffff81436dc2: fuse_flush_writepages (STB_GLOBAL)
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
