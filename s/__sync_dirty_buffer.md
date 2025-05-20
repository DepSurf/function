# Function: <code>__sync_dirty_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int __sync_dirty_buffer(struct buffer_head *bh, int rw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81246820)
Location: fs/buffer.c:3133
Inline: True
Direct callers:
  - fs/buffer.c:sync_dirty_buffer
  - fs/ext4/super.c:ext4_commit_super
```
**Symbols:**

```
ffffffff81246820-ffffffff81246911: __sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int __sync_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126f780)
Location: fs/buffer.c:3192
Inline: True
Direct callers:
  - fs/buffer.c:sync_dirty_buffer
  - fs/ext4/super.c:ext4_commit_super
```
**Symbols:**

```
ffffffff8126f780-ffffffff8126f87d: __sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __sync_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81282980)
Location: fs/buffer.c:3233
Inline: True
Direct callers:
  - fs/buffer.c:sync_dirty_buffer
  - fs/ext4/super.c:ext4_commit_super
```
**Symbols:**

```
ffffffff81282980-ffffffff81282a7d: __sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __sync_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81290080)
Location: fs/buffer.c:3220
Inline: True
Direct callers:
  - fs/buffer.c:sync_dirty_buffer
  - fs/ext4/super.c:ext4_commit_super
```
**Symbols:**

```
ffffffff81290080-ffffffff8129016e: __sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __sync_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812b2d90)
Location: fs/buffer.c:3188
Inline: True
Direct callers:
  - fs/buffer.c:sync_dirty_buffer
  - fs/ext4/super.c:ext4_commit_super
```
**Symbols:**

```
ffffffff812b2d90-ffffffff812b2e7e: __sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __sync_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812dac80)
Location: fs/buffer.c:3159
Inline: True
Direct callers:
  - fs/buffer.c:sync_dirty_buffer
  - fs/ext4/super.c:ext4_commit_super
```
**Symbols:**

```
ffffffff812dac80-ffffffff812dad69: __sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __sync_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812f0160)
Location: fs/buffer.c:3171
Inline: True
Direct callers:
  - fs/buffer.c:sync_dirty_buffer
  - fs/ext4/super.c:ext4_commit_super
```
**Symbols:**

```
ffffffff812f0160-ffffffff812f0249: __sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __sync_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff81311a59)
Location: fs/buffer.c:3178
Inline: True
Direct callers:
  - fs/buffer.c:sync_dirty_buffer
  - fs/ext4/super.c:ext4_commit_super
```
**Symbols:**

```
ffffffff81311dbe-ffffffff81311dd1: __sync_dirty_buffer.cold (STB_LOCAL)
ffffffff81311a20-ffffffff81311b16: __sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __sync_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81324a40)
Location: fs/buffer.c:3155
Inline: True
Direct callers:
  - fs/buffer.c:sync_dirty_buffer
  - fs/ext4/super.c:ext4_commit_super
```
**Symbols:**

```
ffffffff81324a40-ffffffff81324b3d: __sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __sync_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8135d810)
Location: fs/buffer.c:3156
Inline: False
Direct callers:
  - fs/buffer.c:sync_dirty_buffer
  - fs/ext4/super.c:ext4_commit_super
```
**Symbols:**

```
ffffffff8135d810-ffffffff8135d94b: __sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __sync_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136b400)
Location: fs/buffer.c:3137
Inline: False
Direct callers:
  - fs/buffer.c:sync_dirty_buffer
  - fs/ext4/super.c:ext4_commit_super
```
**Symbols:**

```
ffffffff8136b400-ffffffff8136b53b: __sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __sync_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81371ca0)
Location: fs/buffer.c:3158
Inline: False
Direct callers:
  - fs/buffer.c:sync_dirty_buffer
  - fs/ext4/super.c:ext4_commit_super
```
**Symbols:**

```
ffffffff81371ca0-ffffffff81371ddb: __sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __sync_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813c0cc0)
Location: fs/buffer.c:3137
Inline: False
Direct callers:
  - fs/buffer.c:sync_dirty_buffer
  - fs/ext4/super.c:ext4_commit_super
```
**Symbols:**

```
ffffffff813c0cc0-ffffffff813c0dfb: __sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __sync_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81447970)
Location: fs/buffer.c:3122
Inline: False
Direct callers:
  - fs/buffer.c:sync_dirty_buffer
```
**Symbols:**

```
ffffffff81447970-ffffffff81447a9a: __sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __sync_dirty_buffer(struct buffer_head *bh, blk_opf_t op_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814d64d0)
Location: fs/buffer.c:2729
Inline: False
Direct callers:
  - fs/buffer.c:sync_dirty_buffer
```
**Symbols:**

```
ffffffff814d64d0-ffffffff814d65de: __sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __sync_dirty_buffer(struct buffer_head *bh, blk_opf_t op_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8150ca40)
Location: fs/buffer.c:2867
Inline: False
Direct callers:
  - fs/buffer.c:sync_dirty_buffer
```
**Symbols:**

```
ffffffff8150ca40-ffffffff8150cb4e: __sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __sync_dirty_buffer(struct buffer_head *bh, blk_opf_t op_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff815416b0)
Location: fs/buffer.c:2827
Inline: False
Direct callers:
  - fs/buffer.c:sync_dirty_buffer
```
**Symbols:**

```
ffffffff815416b0-ffffffff815417be: __sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int __sync_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103ddfa0)
Location: fs/buffer.c:3155
Inline: True
Direct callers:
  - fs/buffer.c:sync_dirty_buffer
  - fs/ext4/super.c:ext4_commit_super
```
**Symbols:**

```
ffff8000103ddfa0-ffff8000103de154: __sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __sync_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b733c)
Location: fs/buffer.c:3155
Inline: True
Direct callers:
  - fs/buffer.c:sync_dirty_buffer
  - fs/ext4/super.c:ext4_commit_super
```
**Symbols:**

```
c05b733c-c05b74dc: __sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __sync_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004e3c20)
Location: fs/buffer.c:3155
Inline: False
Direct callers:
  - fs/buffer.c:sync_dirty_buffer
  - fs/ext4/super.c:ext4_commit_super
```
**Symbols:**

```
c0000000004e3c20-c0000000004e3e00: __sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __sync_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe000295e18)
Location: fs/buffer.c:3155
Inline: True
Direct callers:
  - fs/buffer.c:sync_dirty_buffer
  - fs/ext4/super.c:ext4_commit_super
```
**Symbols:**

```
ffffffe000295e18-ffffffe000295f3e: __sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int __sync_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8131d020)
Location: fs/buffer.c:3155
Inline: True
Direct callers:
  - fs/buffer.c:sync_dirty_buffer
  - fs/ext4/super.c:ext4_commit_super
```
**Symbols:**

```
ffffffff8131d020-ffffffff8131d11d: __sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __sync_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130dbc0)
Location: fs/buffer.c:3155
Inline: True
Direct callers:
  - fs/buffer.c:sync_dirty_buffer
  - fs/ext4/super.c:ext4_commit_super
```
**Symbols:**

```
ffffffff8130dbc0-ffffffff8130dcbd: __sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __sync_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8131aaf0)
Location: fs/buffer.c:3155
Inline: True
Direct callers:
  - fs/buffer.c:sync_dirty_buffer
  - fs/ext4/super.c:ext4_commit_super
```
**Symbols:**

```
ffffffff8131aaf0-ffffffff8131abed: __sync_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __sync_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8132c7b0)
Location: fs/buffer.c:3155
Inline: True
Direct callers:
  - fs/buffer.c:sync_dirty_buffer
  - fs/ext4/super.c:ext4_commit_super
```
**Symbols:**

```
ffffffff8132c7b0-ffffffff8132c899: __sync_dirty_buffer (STB_GLOBAL)
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
<b>Param added. </b>
<code>int op_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int rw</code>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int op_flags</code> ➡️ <code>blk_opf_t op_flags</code>
</li>
</ul>
</details>
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
