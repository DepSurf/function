# Function: <code>ext4_fname_setup_filename</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_fname_setup_filename(struct inode *dir, const struct qstr *iname, int lookup, struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/crypto_fname.c (ffffffff812e6800)
Location: fs/ext4/crypto_fname.c:395
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_add_entry
```
**Symbols:**

```
ffffffff812e6800-ffffffff812e6abc: ext4_fname_setup_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_fname_setup_filename(struct inode *dir, const struct qstr *iname, int lookup, struct ext4_filename *fname);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812d2cf3)
Location: fs/ext4/ext4.h:2301
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
```
**Symbols:**

```
ffffffff812d0740-ffffffff812d07ca: ext4_fname_setup_filename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ext4_fname_setup_filename(struct inode *dir, const struct qstr *iname, int lookup, struct ext4_filename *fname);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812e8a43)
Location: fs/ext4/ext4.h:2281
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
```
**Symbols:**

```
ffffffff812e64e0-ffffffff812e656a: ext4_fname_setup_filename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ext4_fname_setup_filename(struct inode *dir, const struct qstr *iname, int lookup, struct ext4_filename *fname);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813183db)
Location: fs/ext4/ext4.h:2317
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
```
**Symbols:**

```
ffffffff81316170-ffffffff813161f7: ext4_fname_setup_filename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ext4_fname_setup_filename(struct inode *dir, const struct qstr *iname, int lookup, struct ext4_filename *fname);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8133cc3b)
Location: fs/ext4/ext4.h:2277
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
```
**Symbols:**

```
ffffffff8133a9e0-ffffffff8133aa67: ext4_fname_setup_filename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ext4_fname_setup_filename(struct inode *dir, const struct qstr *iname, int lookup, struct ext4_filename *fname);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8136b19f)
Location: fs/ext4/ext4.h:2278
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
```
**Symbols:**

```
ffffffff81368f40-ffffffff81368fc5: ext4_fname_setup_filename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ext4_fname_setup_filename(struct inode *dir, const struct qstr *iname, int lookup, struct ext4_filename *fname);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8138365f)
Location: fs/ext4/ext4.h:2291
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
```
**Symbols:**

```
ffffffff813813e0-ffffffff81381465: ext4_fname_setup_filename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_fname_setup_filename(struct inode *dir, const struct qstr *iname, int lookup, struct ext4_filename *fname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813ac870)
Location: fs/ext4/ext4.h:2328
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff813ac870-ffffffff813ac936: ext4_fname_setup_filename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_fname_setup_filename(struct inode *dir, const struct qstr *iname, int lookup, struct ext4_filename *fname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813c57b0)
Location: fs/ext4/ext4.h:2386
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff813c57b0-ffffffff813c5876: ext4_fname_setup_filename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_fname_setup_filename(struct inode *dir, const struct qstr *iname, int lookup, struct ext4_filename *fname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81411c20)
Location: fs/ext4/ext4.h:2484
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff81411c20-ffffffff81411cd0: ext4_fname_setup_filename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_fname_setup_filename(struct inode *dir, const struct qstr *iname, int lookup, struct ext4_filename *fname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff814250c0)
Location: fs/ext4/ext4.h:2616
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff814250c0-ffffffff81425170: ext4_fname_setup_filename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_fname_setup_filename(struct inode *dir, const struct qstr *iname, int lookup, struct ext4_filename *fname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8142bdd0)
Location: fs/ext4/ext4.h:2668
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff8142bdd0-ffffffff8142be7e: ext4_fname_setup_filename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_fname_setup_filename(struct inode *dir, const struct qstr *iname, int lookup, struct ext4_filename *fname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8147fc70)
Location: fs/ext4/ext4.h:2738
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff8147fc70-ffffffff8147fd1e: ext4_fname_setup_filename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_fname_setup_filename(struct inode *dir, const struct qstr *iname, int lookup, struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/crypto.c (ffffffff8153ca90)
Location: fs/ext4/crypto.c:22
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_get_parent
```
**Symbols:**

```
ffffffff8153ca90-ffffffff8153cb20: ext4_fname_setup_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_fname_setup_filename(struct inode *dir, const struct qstr *iname, int lookup, struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/crypto.c (ffffffff815db220)
Location: fs/ext4/crypto.c:22
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_get_parent
```
**Symbols:**

```
ffffffff815db220-ffffffff815db2b0: ext4_fname_setup_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_fname_setup_filename(struct inode *dir, const struct qstr *iname, int lookup, struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/crypto.c (ffffffff81612cd0)
Location: fs/ext4/crypto.c:22
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_get_parent
```
**Symbols:**

```
ffffffff81612cd0-ffffffff81612d60: ext4_fname_setup_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_fname_setup_filename(struct inode *dir, const struct qstr *iname, int lookup, struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/crypto.c (ffffffff8164ba50)
Location: fs/ext4/crypto.c:22
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_get_parent
```
**Symbols:**

```
ffffffff8164ba50-ffffffff8164bb1d: ext4_fname_setup_filename (STB_GLOBAL)
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
int ext4_fname_setup_filename(struct inode *dir, const struct qstr *iname, int lookup, struct ext4_filename *fname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffff80001049d2f8)
Location: fs/ext4/ext4.h:2386
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffff80001049d2f8-ffff80001049d3a0: ext4_fname_setup_filename (STB_LOCAL)
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
In fs/ext4/namei.c (c06618f8)
Location: fs/ext4/ext4.h:2386
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_fname_setup_filename(struct inode *dir, const struct qstr *iname, int lookup, struct ext4_filename *fname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c0000000005c8730)
Location: fs/ext4/ext4.h:2386
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
c0000000005c8730-c0000000005c8810: ext4_fname_setup_filename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_fname_setup_filename(struct inode *dir, const struct qstr *iname, int lookup, struct ext4_filename *fname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffe000320112)
Location: fs/ext4/ext4.h:2386
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffe000320112-ffffffe000320190: ext4_fname_setup_filename (STB_LOCAL)
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
int ext4_fname_setup_filename(struct inode *dir, const struct qstr *iname, int lookup, struct ext4_filename *fname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813bdd90)
Location: fs/ext4/ext4.h:2386
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff813bdd90-ffffffff813bde56: ext4_fname_setup_filename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_fname_setup_filename(struct inode *dir, const struct qstr *iname, int lookup, struct ext4_filename *fname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813ae820)
Location: fs/ext4/ext4.h:2386
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff813ae820-ffffffff813ae8e6: ext4_fname_setup_filename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_fname_setup_filename(struct inode *dir, const struct qstr *iname, int lookup, struct ext4_filename *fname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813b9490)
Location: fs/ext4/ext4.h:2386
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff813b9490-ffffffff813b9518: ext4_fname_setup_filename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_fname_setup_filename(struct inode *dir, const struct qstr *iname, int lookup, struct ext4_filename *fname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813d0320)
Location: fs/ext4/ext4.h:2386
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff813d0320-ffffffff813d03e6: ext4_fname_setup_filename (STB_LOCAL)
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
