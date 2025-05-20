# Function: <code>ext4_write_inline_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ext4_write_inline_data(struct inode *inode, struct ext4_iloc *iloc, void *buffer, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff812df650)
Location: fs/ext4/inline.c:210
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
```
**Symbols:**

```
ffffffff812df650-ffffffff812df739: ext4_write_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ext4_write_inline_data(struct inode *inode, struct ext4_iloc *iloc, void *buffer, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8130f2e0)
Location: fs/ext4/inline.c:210
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
**Symbols:**

```
ffffffff8130f2e0-ffffffff8130f3c5: ext4_write_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ext4_write_inline_data(struct inode *inode, struct ext4_iloc *iloc, void *buffer, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81325100)
Location: fs/ext4/inline.c:210
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
**Symbols:**

```
ffffffff81325100-ffffffff813251e5: ext4_write_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ext4_write_inline_data(struct inode *inode, struct ext4_iloc *iloc, void *buffer, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff812f9180)
Location: fs/ext4/inline.c:210
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
**Symbols:**

```
ffffffff812f9180-ffffffff812f9270: ext4_write_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ext4_write_inline_data(struct inode *inode, struct ext4_iloc *iloc, void *buffer, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8131d7c0)
Location: fs/ext4/inline.c:211
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
**Symbols:**

```
ffffffff8131d7c0-ffffffff8131d8b0: ext4_write_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ext4_write_inline_data(struct inode *inode, struct ext4_iloc *iloc, void *buffer, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8134b750)
Location: fs/ext4/inline.c:210
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
**Symbols:**

```
ffffffff8134b750-ffffffff8134b842: ext4_write_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ext4_write_inline_data(struct inode *inode, struct ext4_iloc *iloc, void *buffer, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81363890)
Location: fs/ext4/inline.c:210
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
**Symbols:**

```
ffffffff81363890-ffffffff81363982: ext4_write_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ext4_write_inline_data(struct inode *inode, struct ext4_iloc *iloc, void *buffer, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8138cb20)
Location: fs/ext4/inline.c:210
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
**Symbols:**

```
ffffffff8138cb20-ffffffff8138cc13: ext4_write_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ext4_write_inline_data(struct inode *inode, struct ext4_iloc *iloc, void *buffer, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813a5570)
Location: fs/ext4/inline.c:210
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
**Symbols:**

```
ffffffff813a5570-ffffffff813a5663: ext4_write_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ext4_write_inline_data(struct inode *inode, struct ext4_iloc *iloc, void *buffer, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813f13b0)
Location: fs/ext4/inline.c:210
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
**Symbols:**

```
ffffffff813f13b0-ffffffff813f14a1: ext4_write_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_write_inline_data(struct inode *inode, struct ext4_iloc *iloc, void *buffer, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81403a90)
Location: fs/ext4/inline.c:210
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
**Symbols:**

```
ffffffff81403a90-ffffffff81403b81: ext4_write_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_write_inline_data(struct inode *inode, struct ext4_iloc *iloc, void *buffer, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8140a130)
Location: fs/ext4/inline.c:210
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
**Symbols:**

```
ffffffff8140a130-ffffffff8140a221: ext4_write_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_write_inline_data(struct inode *inode, struct ext4_iloc *iloc, void *buffer, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8145ccc0)
Location: fs/ext4/inline.c:211
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
**Symbols:**

```
ffffffff8145ccc0-ffffffff8145cdb1: ext4_write_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_write_inline_data(struct inode *inode, struct ext4_iloc *iloc, void *buffer, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff814dafd0)
Location: fs/ext4/inline.c:215
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
**Symbols:**

```
ffffffff814dafd0-ffffffff814db0d5: ext4_write_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_write_inline_data(struct inode *inode, struct ext4_iloc *iloc, void *buffer, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81574480)
Location: fs/ext4/inline.c:214
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
**Symbols:**

```
ffffffff81574480-ffffffff81574585: ext4_write_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ext4_write_inline_data(struct inode *inode, struct ext4_iloc *iloc, void *buffer, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (0)
Location: fs/ext4/inline.c:223
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
**Symbols:**

```
ffffffff815ac2d0-ffffffff815ac444: ext4_write_inline_data (STB_LOCAL)
ffffffff820ed5b8-ffffffff820ed5eb: ext4_write_inline_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ext4_write_inline_data(struct inode *inode, struct ext4_iloc *iloc, void *buffer, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (0)
Location: fs/ext4/inline.c:223
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
**Symbols:**

```
ffffffff815e5060-ffffffff815e51d4: ext4_write_inline_data (STB_LOCAL)
ffffffff821ca6e3-ffffffff821ca716: ext4_write_inline_data.cold (STB_LOCAL)
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
void ext4_write_inline_data(struct inode *inode, struct ext4_iloc *iloc, void *buffer, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffff800010478ba0)
Location: fs/ext4/inline.c:210
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
**Symbols:**

```
ffff800010478ba0-ffff800010478ca0: ext4_write_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ext4_write_inline_data(struct inode *inode, struct ext4_iloc *iloc, void *buffer, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (c063a69c)
Location: fs/ext4/inline.c:210
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
**Symbols:**

```
c063a69c-c063a7c0: ext4_write_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ext4_write_inline_data(struct inode *inode, struct ext4_iloc *iloc, void *buffer, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (c00000000059b3d0)
Location: fs/ext4/inline.c:210
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
**Symbols:**

```
c00000000059b3d0-c00000000059b50c: ext4_write_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ext4_write_inline_data(struct inode *inode, struct ext4_iloc *iloc, void *buffer, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffe000303a82)
Location: fs/ext4/inline.c:210
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
**Symbols:**

```
ffffffe000303a82-ffffffe000303b68: ext4_write_inline_data (STB_LOCAL)
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
void ext4_write_inline_data(struct inode *inode, struct ext4_iloc *iloc, void *buffer, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8139db50)
Location: fs/ext4/inline.c:210
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
**Symbols:**

```
ffffffff8139db50-ffffffff8139dc43: ext4_write_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ext4_write_inline_data(struct inode *inode, struct ext4_iloc *iloc, void *buffer, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8138e5e0)
Location: fs/ext4/inline.c:210
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
**Symbols:**

```
ffffffff8138e5e0-ffffffff8138e6d3: ext4_write_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ext4_write_inline_data(struct inode *inode, struct ext4_iloc *iloc, void *buffer, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8139b3b0)
Location: fs/ext4/inline.c:210
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
**Symbols:**

```
ffffffff8139b3b0-ffffffff8139b4a3: ext4_write_inline_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ext4_write_inline_data(struct inode *inode, struct ext4_iloc *iloc, void *buffer, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813af870)
Location: fs/ext4/inline.c:210
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
**Symbols:**

```
ffffffff813af870-ffffffff813af963: ext4_write_inline_data (STB_LOCAL)
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
