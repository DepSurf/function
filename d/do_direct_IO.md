# Function: <code>do_direct_IO</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff8124a478)
Location: fs/direct-io.c:911
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81272e53)
Location: fs/direct-io.c:920
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81286953)
Location: fs/direct-io.c:905
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81293fe6)
Location: fs/direct-io.c:908
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff812b6f49)
Location: fs/direct-io.c:948
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff812df8ff)
Location: fs/direct-io.c:969
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff812f4432)
Location: fs/direct-io.c:970
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_direct_IO(struct dio *dio, struct dio_submit *sdio, struct buffer_head *map_bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81315af0)
Location: fs/direct-io.c:963
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
**Symbols:**

```
ffffffff81315af0-ffffffff81316885: do_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_direct_IO(struct dio *dio, struct dio_submit *sdio, struct buffer_head *map_bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81328970)
Location: fs/direct-io.c:962
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
**Symbols:**

```
ffffffff81328970-ffffffff81329705: do_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_direct_IO(struct dio *dio, struct dio_submit *sdio, struct buffer_head *map_bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81362a60)
Location: fs/direct-io.c:943
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
**Symbols:**

```
ffffffff81362a60-ffffffff813634e4: do_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_direct_IO(struct dio *dio, struct dio_submit *sdio, struct buffer_head *map_bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff8136fd10)
Location: fs/direct-io.c:924
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
**Symbols:**

```
ffffffff8136fd10-ffffffff8137071a: do_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_direct_IO(struct dio *dio, struct dio_submit *sdio, struct buffer_head *map_bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff813765c0)
Location: fs/direct-io.c:927
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
**Symbols:**

```
ffffffff813765c0-ffffffff81377000: do_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int do_direct_IO(struct dio *dio, struct dio_submit *sdio, struct buffer_head *map_bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/direct-io.c (0)
Location: fs/direct-io.c:927
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
**Symbols:**

```
ffffffff813c2b00-ffffffff813c35c2: do_direct_IO (STB_LOCAL)
ffffffff81cc4ab4-ffffffff81cc4dde: do_direct_IO.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int do_direct_IO(struct dio *dio, struct dio_submit *sdio, struct buffer_head *map_bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/direct-io.c (0)
Location: fs/direct-io.c:917
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
**Symbols:**

```
ffffffff814499e0-ffffffff8144a348: do_direct_IO (STB_LOCAL)
ffffffff81e7748b-ffffffff81e777d1: do_direct_IO.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int do_direct_IO(struct dio *dio, struct dio_submit *sdio, struct buffer_head *map_bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/direct-io.c (0)
Location: fs/direct-io.c:920
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
**Symbols:**

```
ffffffff814d82b0-ffffffff814d8a48: do_direct_IO (STB_LOCAL)
ffffffff8206956d-ffffffff82069774: do_direct_IO.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int do_direct_IO(struct dio *dio, struct dio_submit *sdio, struct buffer_head *map_bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/direct-io.c (0)
Location: fs/direct-io.c:902
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
**Symbols:**

```
ffffffff81511060-ffffffff81511930: do_direct_IO (STB_LOCAL)
ffffffff820e968e-ffffffff820e999c: do_direct_IO.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int do_direct_IO(struct dio *dio, struct dio_submit *sdio, struct buffer_head *map_bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/direct-io.c (0)
Location: fs/direct-io.c:902
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
**Symbols:**

```
ffffffff81545500-ffffffff81545dd0: do_direct_IO (STB_LOCAL)
ffffffff821c61f9-ffffffff821c6507: do_direct_IO.cold (STB_LOCAL)
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
int do_direct_IO(struct dio *dio, struct dio_submit *sdio, struct buffer_head *map_bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffff8000103e3ed8)
Location: fs/direct-io.c:962
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
**Symbols:**

```
ffff8000103e3ed8-ffff8000103e4b64: do_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_direct_IO(struct dio *dio, struct dio_submit *sdio, struct buffer_head *map_bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (c05bbc7c)
Location: fs/direct-io.c:962
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
**Symbols:**

```
c05bbc7c-c05bca30: do_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_direct_IO(struct dio *dio, struct dio_submit *sdio, struct buffer_head *map_bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (c0000000004e9e90)
Location: fs/direct-io.c:962
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
**Symbols:**

```
c0000000004e9e90-c0000000004eae04: do_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_direct_IO(struct dio *dio, struct dio_submit *sdio, struct buffer_head *map_bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffe000299cec)
Location: fs/direct-io.c:962
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
**Symbols:**

```
ffffffe000299cec-ffffffe00029a742: do_direct_IO (STB_LOCAL)
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
int do_direct_IO(struct dio *dio, struct dio_submit *sdio, struct buffer_head *map_bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81320f50)
Location: fs/direct-io.c:962
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
**Symbols:**

```
ffffffff81320f50-ffffffff81321ce5: do_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_direct_IO(struct dio *dio, struct dio_submit *sdio, struct buffer_head *map_bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81311af0)
Location: fs/direct-io.c:962
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
**Symbols:**

```
ffffffff81311af0-ffffffff81312885: do_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_direct_IO(struct dio *dio, struct dio_submit *sdio, struct buffer_head *map_bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff8131ea20)
Location: fs/direct-io.c:962
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
**Symbols:**

```
ffffffff8131ea20-ffffffff8131f7b5: do_direct_IO (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_direct_IO(struct dio *dio, struct dio_submit *sdio, struct buffer_head *map_bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81330720)
Location: fs/direct-io.c:962
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
**Symbols:**

```
ffffffff81330720-ffffffff813314d3: do_direct_IO (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
