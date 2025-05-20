# Function: <code>info_idq_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (ffffffff81271370)
Location: fs/quota/dquot.c:1357
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_transfer
Direct callers:
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_transfer
```
**Symbols:**

```
ffffffff81271370-ffffffff812713d7: info_idq_free.part.9.constprop.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (ffffffff812a0ccc)
Location: fs/quota/dquot.c:1366
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
```
**Symbols:**

```
ffffffff8129d860-ffffffff8129d8c7: info_idq_free.part.9.constprop.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (ffffffff812b667c)
Location: fs/quota/dquot.c:1363
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
```
**Symbols:**

```
ffffffff812b31a0-ffffffff812b3207: info_idq_free.part.11.constprop.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (ffffffff812c39be)
Location: fs/quota/dquot.c:1369
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
```
**Symbols:**

```
ffffffff812c0130-ffffffff812c0199: info_idq_free.part.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (ffffffff812e76b3)
Location: fs/quota/dquot.c:1371
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
```
**Symbols:**

```
ffffffff812e3ae0-ffffffff812e3b43: info_idq_free.part.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int info_idq_free(struct dquot *dquot, qsize_t inodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8130fef0)
Location: fs/quota/dquot.c:1368
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
```
**Symbols:**

```
ffffffff8130fef0-ffffffff8130ff5d: info_idq_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int info_idq_free(struct dquot *dquot, qsize_t inodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81326e80)
Location: fs/quota/dquot.c:1368
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
```
**Symbols:**

```
ffffffff81326e80-ffffffff81326eed: info_idq_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int info_idq_free(struct dquot *dquot, qsize_t inodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8134ea20)
Location: fs/quota/dquot.c:1378
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
```
**Symbols:**

```
ffffffff8134ea20-ffffffff8134ea8d: info_idq_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int info_idq_free(struct dquot *dquot, qsize_t inodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81366d10)
Location: fs/quota/dquot.c:1380
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
```
**Symbols:**

```
ffffffff81366d10-ffffffff81366d7d: info_idq_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int info_idq_free(struct dquot *dquot, qsize_t inodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813ae7c0)
Location: fs/quota/dquot.c:1378
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
```
**Symbols:**

```
ffffffff813ae7c0-ffffffff813ae831: info_idq_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int info_idq_free(struct dquot *dquot, qsize_t inodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813bfdb0)
Location: fs/quota/dquot.c:1379
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
```
**Symbols:**

```
ffffffff813bfdb0-ffffffff813bfe21: info_idq_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int info_idq_free(struct dquot *dquot, qsize_t inodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813c6c50)
Location: fs/quota/dquot.c:1377
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
```
**Symbols:**

```
ffffffff813c6c50-ffffffff813c6cc1: info_idq_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int info_idq_free(struct dquot *dquot, qsize_t inodes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (ffffffff81417577)
Location: fs/quota/dquot.c:1382
Inline: True
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
```
**Symbols:**

```
ffffffff81417510-ffffffff814175ad: info_idq_free (STB_LOCAL)
ffffffff81cc7c4b-ffffffff81cc7c6a: info_idq_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int info_idq_free(struct dquot *dquot, qsize_t inodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (0)
Location: fs/quota/dquot.c:1392
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
```
**Symbols:**

```
ffffffff8148e8b0-ffffffff8148e97a: info_idq_free (STB_LOCAL)
ffffffff81e7a857-ffffffff81e7a876: info_idq_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int info_idq_free(struct dquot *dquot, qsize_t inodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (0)
Location: fs/quota/dquot.c:1392
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
```
**Symbols:**

```
ffffffff815223c0-ffffffff8152248a: info_idq_free (STB_LOCAL)
ffffffff8206b76b-ffffffff8206b78a: info_idq_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int info_idq_free(struct dquot *dquot, qsize_t inodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (0)
Location: fs/quota/dquot.c:1450
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
```
**Symbols:**

```
ffffffff8155a430-ffffffff8155a4d0: info_idq_free (STB_LOCAL)
ffffffff820eb68a-ffffffff820eb6a5: info_idq_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int info_idq_free(struct dquot *dquot, qsize_t inodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (0)
Location: fs/quota/dquot.c:1404
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
```
**Symbols:**

```
ffffffff81590bf0-ffffffff81590c90: info_idq_free (STB_LOCAL)
ffffffff821c88b4-ffffffff821c88cf: info_idq_free.cold (STB_LOCAL)
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
int info_idq_free(struct dquot *dquot, qsize_t inodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffff80001042e418)
Location: fs/quota/dquot.c:1380
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
```
**Symbols:**

```
ffff80001042e418-ffff80001042e4ac: info_idq_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int info_idq_free(struct dquot *dquot, qsize_t inodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (c05f77ec)
Location: fs/quota/dquot.c:1380
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
```
**Symbols:**

```
c05f77ec-c05f7894: info_idq_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int info_idq_free(struct dquot *dquot, qsize_t inodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (c00000000053fa80)
Location: fs/quota/dquot.c:1380
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
```
**Symbols:**

```
c00000000053fa80-c00000000053fb08: info_idq_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int info_idq_free(struct dquot *dquot, qsize_t inodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffe0002cac82)
Location: fs/quota/dquot.c:1380
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
```
**Symbols:**

```
ffffffe0002cac82-ffffffe0002cacf6: info_idq_free (STB_LOCAL)
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
int info_idq_free(struct dquot *dquot, qsize_t inodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8135f2f0)
Location: fs/quota/dquot.c:1380
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
```
**Symbols:**

```
ffffffff8135f2f0-ffffffff8135f35d: info_idq_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int info_idq_free(struct dquot *dquot, qsize_t inodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8134ff90)
Location: fs/quota/dquot.c:1380
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
```
**Symbols:**

```
ffffffff8134ff90-ffffffff8134fffd: info_idq_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int info_idq_free(struct dquot *dquot, qsize_t inodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8135cdc0)
Location: fs/quota/dquot.c:1380
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
```
**Symbols:**

```
ffffffff8135cdc0-ffffffff8135ce2d: info_idq_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int info_idq_free(struct dquot *dquot, qsize_t inodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81370630)
Location: fs/quota/dquot.c:1380
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
```
**Symbols:**

```
ffffffff81370630-ffffffff8137069d: info_idq_free (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
