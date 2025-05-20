# Function: <code>dqget</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dquot *dqget(struct super_block *sb, struct kqid qid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81271990)
Location: fs/quota/dquot.c:832
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
```
**Symbols:**

```
ffffffff81271990-ffffffff81271e1d: dqget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dquot *dqget(struct super_block *sb, struct kqid qid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8129e150)
Location: fs/quota/dquot.c:839
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffff8129e150-ffffffff8129e5c9: dqget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dquot *dqget(struct super_block *sb, struct kqid qid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff812b3ab0)
Location: fs/quota/dquot.c:836
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffff812b3ab0-ffffffff812b3f29: dqget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dquot *dqget(struct super_block *sb, struct kqid qid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff812c0c50)
Location: fs/quota/dquot.c:837
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffff812c0c50-ffffffff812c10ce: dqget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dquot *dqget(struct super_block *sb, struct kqid qid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff812e49c0)
Location: fs/quota/dquot.c:844
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffff812e49c0-ffffffff812e4e23: dqget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dquot *dqget(struct super_block *sb, struct kqid qid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813120f0)
Location: fs/quota/dquot.c:841
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffff813120f0-ffffffff81312525: dqget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dquot *dqget(struct super_block *sb, struct kqid qid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81328c70)
Location: fs/quota/dquot.c:841
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffff81328c70-ffffffff813290a5: dqget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dquot *dqget(struct super_block *sb, struct kqid qid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813507e0)
Location: fs/quota/dquot.c:847
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffff813507e0-ffffffff81350c16: dqget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dquot *dqget(struct super_block *sb, struct kqid qid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81368b60)
Location: fs/quota/dquot.c:848
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffff81368b60-ffffffff81368f96: dqget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dquot *dqget(struct super_block *sb, struct kqid qid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813b0e80)
Location: fs/quota/dquot.c:846
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
```
**Symbols:**

```
ffffffff813b0e80-ffffffff813b1230: dqget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dquot *dqget(struct super_block *sb, struct kqid qid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813c2480)
Location: fs/quota/dquot.c:847
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
```
**Symbols:**

```
ffffffff813c2480-ffffffff813c2826: dqget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dquot *dqget(struct super_block *sb, struct kqid qid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813c8fd0)
Location: fs/quota/dquot.c:845
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffff813c8fd0-ffffffff813c93ff: dqget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct dquot *dqget(struct super_block *sb, struct kqid qid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (0)
Location: fs/quota/dquot.c:850
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffff81cc7d65-ffffffff81cc7e23: dqget.cold (STB_LOCAL)
ffffffff81419820-ffffffff81419c72: dqget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct dquot *dqget(struct super_block *sb, struct kqid qid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (0)
Location: fs/quota/dquot.c:860
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffff81e7a94f-ffffffff81e7aa0f: dqget.cold (STB_LOCAL)
ffffffff81490280-ffffffff814906dd: dqget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct dquot *dqget(struct super_block *sb, struct kqid qid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (0)
Location: fs/quota/dquot.c:860
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffff8206b863-ffffffff8206b923: dqget.cold (STB_LOCAL)
ffffffff81523e00-ffffffff8152425d: dqget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct dquot *dqget(struct super_block *sb, struct kqid qid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (0)
Location: fs/quota/dquot.c:918
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffff820eb764-ffffffff820eb7d7: dqget.cold (STB_LOCAL)
ffffffff8155c220-ffffffff8155c672: dqget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct dquot *dqget(struct super_block *sb, struct kqid qid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (0)
Location: fs/quota/dquot.c:924
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffff821c898e-ffffffff821c8a01: dqget.cold (STB_LOCAL)
ffffffff815929e0-ffffffff81592e3f: dqget (STB_GLOBAL)
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
struct dquot *dqget(struct super_block *sb, struct kqid qid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffff80001042ff88)
Location: fs/quota/dquot.c:848
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffff80001042ff88-ffff800010430464: dqget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dquot *dqget(struct super_block *sb, struct kqid qid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (c05f8c3c)
Location: fs/quota/dquot.c:848
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
c05f8c3c-c05f911c: dqget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dquot *dqget(struct super_block *sb, struct kqid qid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (c000000000541ac0)
Location: fs/quota/dquot.c:848
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
c000000000541ac0-c000000000542208: dqget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dquot *dqget(struct super_block *sb, struct kqid qid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffe0002ccfe2)
Location: fs/quota/dquot.c:848
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffe0002ccfe2-ffffffe0002cd534: dqget (STB_GLOBAL)
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
struct dquot *dqget(struct super_block *sb, struct kqid qid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81361140)
Location: fs/quota/dquot.c:848
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffff81361140-ffffffff81361576: dqget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dquot *dqget(struct super_block *sb, struct kqid qid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81351de0)
Location: fs/quota/dquot.c:848
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffff81351de0-ffffffff81352216: dqget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dquot *dqget(struct super_block *sb, struct kqid qid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8135ec10)
Location: fs/quota/dquot.c:848
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffff8135ec10-ffffffff8135f046: dqget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dquot *dqget(struct super_block *sb, struct kqid qid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81371640)
Location: fs/quota/dquot.c:848
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffff81371640-ffffffff81371a6b: dqget (STB_GLOBAL)
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
