# Function: <code>ext4_zero_partial_blocks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_zero_partial_blocks(handle_t *handle, struct inode *inode, loff_t lstart, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81299a40)
Location: fs/ext4/inode.c:3540
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
ffffffff81299a40-ffffffff81299b11: ext4_zero_partial_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_zero_partial_blocks(handle_t *handle, struct inode *inode, loff_t lstart, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c7120)
Location: fs/ext4/inode.c:3814
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
ffffffff812c7120-ffffffff812c71f1: ext4_zero_partial_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_zero_partial_blocks(handle_t *handle, struct inode *inode, loff_t lstart, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812dcc20)
Location: fs/ext4/inode.c:3940
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
ffffffff812dcc20-ffffffff812dccf1: ext4_zero_partial_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_zero_partial_blocks(handle_t *handle, struct inode *inode, loff_t lstart, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813014a0)
Location: fs/ext4/inode.c:4060
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff813014a0-ffffffff81301571: ext4_zero_partial_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_zero_partial_blocks(handle_t *handle, struct inode *inode, loff_t lstart, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81325e50)
Location: fs/ext4/inode.c:4109
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff81325e50-ffffffff81325f21: ext4_zero_partial_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_zero_partial_blocks(handle_t *handle, struct inode *inode, loff_t lstart, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813540f0)
Location: fs/ext4/inode.c:4121
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff813540f0-ffffffff813541c1: ext4_zero_partial_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_zero_partial_blocks(handle_t *handle, struct inode *inode, loff_t lstart, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8136c360)
Location: fs/ext4/inode.c:4154
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff8136c360-ffffffff8136c431: ext4_zero_partial_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_zero_partial_blocks(handle_t *handle, struct inode *inode, loff_t lstart, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81395930)
Location: fs/ext4/inode.c:4166
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff81395930-ffffffff81395a02: ext4_zero_partial_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_zero_partial_blocks(handle_t *handle, struct inode *inode, loff_t lstart, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813ae300)
Location: fs/ext4/inode.c:4143
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff813ae300-ffffffff813ae3d2: ext4_zero_partial_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_zero_partial_blocks(handle_t *handle, struct inode *inode, loff_t lstart, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813fa2a0)
Location: fs/ext4/inode.c:3839
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff813fa2a0-ffffffff813fa372: ext4_zero_partial_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_zero_partial_blocks(handle_t *handle, struct inode *inode, loff_t lstart, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140c870)
Location: fs/ext4/inode.c:3874
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff8140c870-ffffffff8140c942: ext4_zero_partial_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_zero_partial_blocks(handle_t *handle, struct inode *inode, loff_t lstart, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814129f0)
Location: fs/ext4/inode.c:3873
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff814129f0-ffffffff81412ac2: ext4_zero_partial_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_zero_partial_blocks(handle_t *handle, struct inode *inode, loff_t lstart, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:3797
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff81ccadcc-ffffffff81ccae44: ext4_zero_partial_blocks.cold (STB_LOCAL)
ffffffff81465ce0-ffffffff81465def: ext4_zero_partial_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_zero_partial_blocks(handle_t *handle, struct inode *inode, loff_t lstart, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:3862
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff81e7dc68-ffffffff81e7dce0: ext4_zero_partial_blocks.cold (STB_LOCAL)
ffffffff814e56e0-ffffffff814e5845: ext4_zero_partial_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ext4_zero_partial_blocks(handle_t *handle, struct inode *inode, loff_t lstart, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:3948
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff8206e131-ffffffff8206e1a9: ext4_zero_partial_blocks.cold (STB_LOCAL)
ffffffff8157ede0-ffffffff8157ef45: ext4_zero_partial_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ext4_zero_partial_blocks(handle_t *handle, struct inode *inode, loff_t lstart, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:3737
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff820ede75-ffffffff820edeed: ext4_zero_partial_blocks.cold (STB_LOCAL)
ffffffff815b6290-ffffffff815b63f5: ext4_zero_partial_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ext4_zero_partial_blocks(handle_t *handle, struct inode *inode, loff_t lstart, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:3754
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff821cafd0-ffffffff821cb048: ext4_zero_partial_blocks.cold (STB_LOCAL)
ffffffff815ef030-ffffffff815ef195: ext4_zero_partial_blocks (STB_GLOBAL)
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
int ext4_zero_partial_blocks(handle_t *handle, struct inode *inode, loff_t lstart, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff800010482dd0)
Location: fs/ext4/inode.c:4143
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffff800010482dd0-ffff800010482ef8: ext4_zero_partial_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_zero_partial_blocks(handle_t *handle, struct inode *inode, loff_t lstart, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0644258)
Location: fs/ext4/inode.c:4143
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
c0644258-c06443b4: ext4_zero_partial_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_zero_partial_blocks(handle_t *handle, struct inode *inode, loff_t lstart, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a7b00)
Location: fs/ext4/inode.c:4143
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
c0000000005a7b00-c0000000005a7c6c: ext4_zero_partial_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_zero_partial_blocks(handle_t *handle, struct inode *inode, loff_t lstart, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe00030b5a2)
Location: fs/ext4/inode.c:4143
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffe00030b5a2-ffffffe00030b67c: ext4_zero_partial_blocks (STB_GLOBAL)
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
int ext4_zero_partial_blocks(handle_t *handle, struct inode *inode, loff_t lstart, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a68e0)
Location: fs/ext4/inode.c:4143
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff813a68e0-ffffffff813a69b2: ext4_zero_partial_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_zero_partial_blocks(handle_t *handle, struct inode *inode, loff_t lstart, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81397370)
Location: fs/ext4/inode.c:4143
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff81397370-ffffffff81397442: ext4_zero_partial_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_zero_partial_blocks(handle_t *handle, struct inode *inode, loff_t lstart, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a4140)
Location: fs/ext4/inode.c:4143
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff813a4140-ffffffff813a4212: ext4_zero_partial_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_zero_partial_blocks(handle_t *handle, struct inode *inode, loff_t lstart, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b8840)
Location: fs/ext4/inode.c:4143
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff813b8840-ffffffff813b8912: ext4_zero_partial_blocks (STB_GLOBAL)
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
