# Function: <code>sb_init_dio_done_wq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sb_init_dio_done_wq(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81249c20)
Location: fs/direct-io.c:545
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
**Symbols:**

```
ffffffff81249c20-ffffffff81249c77: sb_init_dio_done_wq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sb_init_dio_done_wq(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81272460)
Location: fs/direct-io.c:554
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
**Symbols:**

```
ffffffff81272460-ffffffff812724b7: sb_init_dio_done_wq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sb_init_dio_done_wq(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81286630)
Location: fs/direct-io.c:557
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap.c:iomap_dio_rw
```
**Symbols:**

```
ffffffff81286630-ffffffff81286687: sb_init_dio_done_wq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sb_init_dio_done_wq(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81293cb0)
Location: fs/direct-io.c:560
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap.c:iomap_dio_rw
```
**Symbols:**

```
ffffffff81293cb0-ffffffff81293d07: sb_init_dio_done_wq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sb_init_dio_done_wq(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff812b6c10)
Location: fs/direct-io.c:599
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap.c:iomap_dio_rw
```
**Symbols:**

```
ffffffff812b6c10-ffffffff812b6c67: sb_init_dio_done_wq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sb_init_dio_done_wq(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff812df610)
Location: fs/direct-io.c:620
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap.c:iomap_dio_rw
```
**Symbols:**

```
ffffffff812df610-ffffffff812df66c: sb_init_dio_done_wq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sb_init_dio_done_wq(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff812f4110)
Location: fs/direct-io.c:620
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/iomap.c:iomap_dio_rw
```
**Symbols:**

```
ffffffff812f4110-ffffffff812f4167: sb_init_dio_done_wq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sb_init_dio_done_wq(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81315a90)
Location: fs/direct-io.c:613
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
```
**Symbols:**

```
ffffffff81315a90-ffffffff81315ae9: sb_init_dio_done_wq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sb_init_dio_done_wq(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81328910)
Location: fs/direct-io.c:612
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
```
**Symbols:**

```
ffffffff81328910-ffffffff81328969: sb_init_dio_done_wq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sb_init_dio_done_wq(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81362a00)
Location: fs/direct-io.c:593
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
```
**Symbols:**

```
ffffffff81362a00-ffffffff81362a59: sb_init_dio_done_wq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sb_init_dio_done_wq(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff8136fcb0)
Location: fs/direct-io.c:574
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
**Symbols:**

```
ffffffff8136fcb0-ffffffff8136fd09: sb_init_dio_done_wq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sb_init_dio_done_wq(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81376560)
Location: fs/direct-io.c:576
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
**Symbols:**

```
ffffffff81376560-ffffffff813765b9: sb_init_dio_done_wq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sb_init_dio_done_wq(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff813c2aa0)
Location: fs/direct-io.c:576
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
**Symbols:**

```
ffffffff813c2aa0-ffffffff813c2af9: sb_init_dio_done_wq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sb_init_dio_done_wq(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81449980)
Location: fs/direct-io.c:566
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
**Symbols:**

```
ffffffff81449980-ffffffff814499df: sb_init_dio_done_wq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sb_init_dio_done_wq(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff814d80d0)
Location: fs/direct-io.c:567
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:get_more_blocks
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
**Symbols:**

```
ffffffff814d80d0-ffffffff814d812f: sb_init_dio_done_wq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sb_init_dio_done_wq(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814b4d40)
Location: fs/super.c:1801
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:get_more_blocks
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
**Symbols:**

```
ffffffff814b4d40-ffffffff814b4d9f: sb_init_dio_done_wq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sb_init_dio_done_wq(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814e3940)
Location: fs/super.c:2193
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:get_more_blocks
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
**Symbols:**

```
ffffffff814e3940-ffffffff814e399f: sb_init_dio_done_wq (STB_GLOBAL)
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
int sb_init_dio_done_wq(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffff8000103e3e38)
Location: fs/direct-io.c:612
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
```
**Symbols:**

```
ffff8000103e3e38-ffff8000103e3ed8: sb_init_dio_done_wq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sb_init_dio_done_wq(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (c05bbba8)
Location: fs/direct-io.c:612
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_set_defer_completion
  - fs/iomap/direct-io.c:iomap_dio_rw
```
**Symbols:**

```
c05bbba8-c05bbc2c: sb_init_dio_done_wq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sb_init_dio_done_wq(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (c0000000004e9d80)
Location: fs/direct-io.c:612
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_set_defer_completion
  - fs/iomap/direct-io.c:iomap_dio_rw
```
**Symbols:**

```
c0000000004e9d80-c0000000004e9e38: sb_init_dio_done_wq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sb_init_dio_done_wq(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffe000299c4a)
Location: fs/direct-io.c:612
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_set_defer_completion
  - fs/iomap/direct-io.c:iomap_dio_rw
```
**Symbols:**

```
ffffffe000299c4a-ffffffe000299caa: sb_init_dio_done_wq (STB_GLOBAL)
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
int sb_init_dio_done_wq(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81320ef0)
Location: fs/direct-io.c:612
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
```
**Symbols:**

```
ffffffff81320ef0-ffffffff81320f49: sb_init_dio_done_wq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sb_init_dio_done_wq(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81311a90)
Location: fs/direct-io.c:612
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
```
**Symbols:**

```
ffffffff81311a90-ffffffff81311ae9: sb_init_dio_done_wq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sb_init_dio_done_wq(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff8131e9c0)
Location: fs/direct-io.c:612
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
```
**Symbols:**

```
ffffffff8131e9c0-ffffffff8131ea19: sb_init_dio_done_wq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sb_init_dio_done_wq(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff813306c0)
Location: fs/direct-io.c:612
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/iomap/direct-io.c:iomap_dio_rw
```
**Symbols:**

```
ffffffff813306c0-ffffffff81330719: sb_init_dio_done_wq (STB_GLOBAL)
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
