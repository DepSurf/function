# Function: <code>dquot_writeback_dquots</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dquot_writeback_dquots(struct super_block *sb, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81273b70)
Location: fs/quota/dquot.c:605
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_sync_fs
```
**Symbols:**

```
ffffffff81273b70-ffffffff81273ddd: dquot_writeback_dquots (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dquot_writeback_dquots(struct super_block *sb, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8129f650)
Location: fs/quota/dquot.c:612
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_sync_fs
```
**Symbols:**

```
ffffffff8129f650-ffffffff8129f894: dquot_writeback_dquots (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dquot_writeback_dquots(struct super_block *sb, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff812b59c0)
Location: fs/quota/dquot.c:611
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_sync_fs
```
**Symbols:**

```
ffffffff812b59c0-ffffffff812b5c22: dquot_writeback_dquots (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dquot_writeback_dquots(struct super_block *sb, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff812c2a70)
Location: fs/quota/dquot.c:612
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_sync_fs
```
**Symbols:**

```
ffffffff812c2a70-ffffffff812c2c9d: dquot_writeback_dquots (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dquot_writeback_dquots(struct super_block *sb, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff812e4650)
Location: fs/quota/dquot.c:618
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_sync_fs
```
**Symbols:**

```
ffffffff812e4650-ffffffff812e48b4: dquot_writeback_dquots (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dquot_writeback_dquots(struct super_block *sb, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81311d80)
Location: fs/quota/dquot.c:618
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_sync_fs
```
**Symbols:**

```
ffffffff81311d80-ffffffff81311fea: dquot_writeback_dquots (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dquot_writeback_dquots(struct super_block *sb, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81328900)
Location: fs/quota/dquot.c:618
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_sync_fs
```
**Symbols:**

```
ffffffff81328900-ffffffff81328b6a: dquot_writeback_dquots (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dquot_writeback_dquots(struct super_block *sb, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (0)
Location: fs/quota/dquot.c:624
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_sync_fs
```
**Symbols:**

```
ffffffff81353304-ffffffff81353317: dquot_writeback_dquots.cold (STB_LOCAL)
ffffffff81350480-ffffffff813506d2: dquot_writeback_dquots (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dquot_writeback_dquots(struct super_block *sb, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81368790)
Location: fs/quota/dquot.c:624
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_sync_fs
```
**Symbols:**

```
ffffffff81368790-ffffffff81368a57: dquot_writeback_dquots (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dquot_writeback_dquots(struct super_block *sb, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813b0a60)
Location: fs/quota/dquot.c:623
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_sync_fs
```
**Symbols:**

```
ffffffff813b0a60-ffffffff813b0d04: dquot_writeback_dquots (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dquot_writeback_dquots(struct super_block *sb, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813c2060)
Location: fs/quota/dquot.c:624
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_sync_fs
```
**Symbols:**

```
ffffffff813c2060-ffffffff813c2304: dquot_writeback_dquots (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dquot_writeback_dquots(struct super_block *sb, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813c8c20)
Location: fs/quota/dquot.c:622
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_sync_fs
```
**Symbols:**

```
ffffffff813c8c20-ffffffff813c8ec4: dquot_writeback_dquots (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dquot_writeback_dquots(struct super_block *sb, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff814193a0)
Location: fs/quota/dquot.c:622
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_sync_fs
```
**Symbols:**

```
ffffffff814193a0-ffffffff814196bf: dquot_writeback_dquots (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dquot_writeback_dquots(struct super_block *sb, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8148fe20)
Location: fs/quota/dquot.c:632
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_sync_fs
```
**Symbols:**

```
ffffffff8148fe20-ffffffff8149011a: dquot_writeback_dquots (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dquot_writeback_dquots(struct super_block *sb, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81523970)
Location: fs/quota/dquot.c:632
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_sync_fs
```
**Symbols:**

```
ffffffff81523970-ffffffff81523c78: dquot_writeback_dquots (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dquot_writeback_dquots(struct super_block *sb, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8155bd30)
Location: fs/quota/dquot.c:676
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_sync_fs
```
**Symbols:**

```
ffffffff8155bd30-ffffffff8155c09b: dquot_writeback_dquots (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dquot_writeback_dquots(struct super_block *sb, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff815924b0)
Location: fs/quota/dquot.c:681
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_sync_fs
```
**Symbols:**

```
ffffffff815924b0-ffffffff8159285b: dquot_writeback_dquots (STB_GLOBAL)
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
int dquot_writeback_dquots(struct super_block *sb, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffff800010431278)
Location: fs/quota/dquot.c:624
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
```
**Symbols:**

```
ffff800010431278-ffff800010431680: dquot_writeback_dquots (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dquot_writeback_dquots(struct super_block *sb, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (c05fb020)
Location: fs/quota/dquot.c:624
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_sync_fs
```
**Symbols:**

```
c05fb020-c05fb410: dquot_writeback_dquots (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dquot_writeback_dquots(struct super_block *sb, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (c0000000005456c0)
Location: fs/quota/dquot.c:624
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
```
**Symbols:**

```
c0000000005456c0-c000000000545ba0: dquot_writeback_dquots (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dquot_writeback_dquots(struct super_block *sb, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffe0002ccbd6)
Location: fs/quota/dquot.c:624
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_sync_fs
```
**Symbols:**

```
ffffffe0002ccbd6-ffffffe0002ccf00: dquot_writeback_dquots (STB_GLOBAL)
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
int dquot_writeback_dquots(struct super_block *sb, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81360d70)
Location: fs/quota/dquot.c:624
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_sync_fs
```
**Symbols:**

```
ffffffff81360d70-ffffffff81361037: dquot_writeback_dquots (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dquot_writeback_dquots(struct super_block *sb, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81351a10)
Location: fs/quota/dquot.c:624
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_sync_fs
```
**Symbols:**

```
ffffffff81351a10-ffffffff81351cd7: dquot_writeback_dquots (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dquot_writeback_dquots(struct super_block *sb, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8135e840)
Location: fs/quota/dquot.c:624
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_sync_fs
```
**Symbols:**

```
ffffffff8135e840-ffffffff8135eb07: dquot_writeback_dquots (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dquot_writeback_dquots(struct super_block *sb, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813736e0)
Location: fs/quota/dquot.c:624
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_sync_fs
```
**Symbols:**

```
ffffffff813736e0-ffffffff813739a5: dquot_writeback_dquots (STB_GLOBAL)
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
