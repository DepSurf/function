# Function: <code>ext4_empty_dir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_empty_dir(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812a6eb0)
Location: fs/ext4/namei.c:2669
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/crypto_policy.c:ext4_process_policy
```
**Symbols:**

```
ffffffff812a6eb0-ffffffff812a7116: ext4_empty_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool ext4_empty_dir(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812d5f50)
Location: fs/ext4/namei.c:2693
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff812d5f50-ffffffff812d61b4: ext4_empty_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool ext4_empty_dir(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812ebc50)
Location: fs/ext4/namei.c:2695
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff812ebc50-ffffffff812ebeb4: ext4_empty_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool ext4_empty_dir(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8131b950)
Location: fs/ext4/namei.c:2674
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff8131b950-ffffffff8131bbaf: ext4_empty_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool ext4_empty_dir(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8133ff80)
Location: fs/ext4/namei.c:2669
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff8133ff80-ffffffff813401df: ext4_empty_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool ext4_empty_dir(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8136df30)
Location: fs/ext4/namei.c:2669
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff8136df30-ffffffff8136e1b0: ext4_empty_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool ext4_empty_dir(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813863b0)
Location: fs/ext4/namei.c:2670
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff813863b0-ffffffff81386630: ext4_empty_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool ext4_empty_dir(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813b0390)
Location: fs/ext4/namei.c:2807
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff813b0390-ffffffff813b05f3: ext4_empty_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool ext4_empty_dir(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813c9360)
Location: fs/ext4/namei.c:2815
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff813c9360-ffffffff813c962d: ext4_empty_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool ext4_empty_dir(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81414c80)
Location: fs/ext4/namei.c:2851
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff81414c80-ffffffff81414f9b: ext4_empty_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool ext4_empty_dir(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff814282d0)
Location: fs/ext4/namei.c:2843
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff814282d0-ffffffff814285eb: ext4_empty_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool ext4_empty_dir(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8142edd0)
Location: fs/ext4/namei.c:2972
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff8142edd0-ffffffff8142f0f0: ext4_empty_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool ext4_empty_dir(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (0)
Location: fs/ext4/namei.c:2980
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff81cccd82-ffffffff81cccda8: ext4_empty_dir.cold (STB_LOCAL)
ffffffff814838a0-ffffffff81483bc9: ext4_empty_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool ext4_empty_dir(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (0)
Location: fs/ext4/namei.c:3030
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rmdir
```
**Symbols:**

```
ffffffff81e7fc53-ffffffff81e7fc79: ext4_empty_dir.cold (STB_LOCAL)
ffffffff81506a20-ffffffff81506d37: ext4_empty_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool ext4_empty_dir(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (0)
Location: fs/ext4/namei.c:3043
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rmdir
```
**Symbols:**

```
ffffffff82070113-ffffffff82070139: ext4_empty_dir.cold (STB_LOCAL)
ffffffff815a1510-ffffffff815a1827: ext4_empty_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool ext4_empty_dir(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (0)
Location: fs/ext4/namei.c:3064
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rmdir
```
**Symbols:**

```
ffffffff820efc88-ffffffff820efcae: ext4_empty_dir.cold (STB_LOCAL)
ffffffff815d7e90-ffffffff815d81a7: ext4_empty_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool ext4_empty_dir(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (0)
Location: fs/ext4/namei.c:3065
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rmdir
```
**Symbols:**

```
ffffffff821ccd60-ffffffff821ccd86: ext4_empty_dir.cold (STB_LOCAL)
ffffffff81610500-ffffffff81610817: ext4_empty_dir (STB_GLOBAL)
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
bool ext4_empty_dir(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffff8000104a0ea0)
Location: fs/ext4/namei.c:2815
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffff8000104a0ea0-ffff8000104a1200: ext4_empty_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool ext4_empty_dir(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c0663048)
Location: fs/ext4/namei.c:2815
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
c0663048-c066338c: ext4_empty_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool ext4_empty_dir(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c0000000005cd5d0)
Location: fs/ext4/namei.c:2815
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
c0000000005cd5d0-c0000000005cdab8: ext4_empty_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool ext4_empty_dir(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffe000322fe2)
Location: fs/ext4/namei.c:2815
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffe000322fe2-ffffffe000323280: ext4_empty_dir (STB_GLOBAL)
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
bool ext4_empty_dir(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813c1940)
Location: fs/ext4/namei.c:2815
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff813c1940-ffffffff813c1c0d: ext4_empty_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool ext4_empty_dir(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813b23d0)
Location: fs/ext4/namei.c:2815
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff813b23d0-ffffffff813b269d: ext4_empty_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool ext4_empty_dir(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813bedf0)
Location: fs/ext4/namei.c:2815
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff813bedf0-ffffffff813bf0bd: ext4_empty_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool ext4_empty_dir(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813d3ed0)
Location: fs/ext4/namei.c:2815
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff813d3ed0-ffffffff813d419d: ext4_empty_dir (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
