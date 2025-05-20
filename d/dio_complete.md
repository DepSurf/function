# Function: <code>dio_complete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t dio_complete(struct dio *dio, loff_t offset, ssize_t ret, bool is_async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81249900)
Location: fs/direct-io.c:227
Inline: False
Direct callers:
  - fs/direct-io.c:dio_bio_end_aio
  - fs/direct-io.c:dio_aio_complete_work
  - fs/direct-io.c:do_blockdev_direct_IO
```
**Symbols:**

```
ffffffff81249900-ffffffff81249ab4: dio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t dio_complete(struct dio *dio, ssize_t ret, bool is_async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff812722c0)
Location: fs/direct-io.c:228
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
  - fs/direct-io.c:dio_aio_complete_work
```
**Symbols:**

```
ffffffff812722c0-ffffffff81272439: dio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t dio_complete(struct dio *dio, ssize_t ret, bool is_async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81285e20)
Location: fs/direct-io.c:228
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
  - fs/direct-io.c:dio_aio_complete_work
```
**Symbols:**

```
ffffffff81285e20-ffffffff81285fb8: dio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t dio_complete(struct dio *dio, ssize_t ret, bool is_async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81293480)
Location: fs/direct-io.c:228
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
  - fs/direct-io.c:dio_aio_complete_work
```
**Symbols:**

```
ffffffff81293480-ffffffff81293618: dio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t dio_complete(struct dio *dio, ssize_t ret, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff812b62d0)
Location: fs/direct-io.c:234
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
  - fs/direct-io.c:dio_aio_complete_work
```
**Symbols:**

```
ffffffff812b62d0-ffffffff812b64ec: dio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t dio_complete(struct dio *dio, ssize_t ret, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff812df280)
Location: fs/direct-io.c:255
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
  - fs/direct-io.c:dio_aio_complete_work
```
**Symbols:**

```
ffffffff812df280-ffffffff812df4a8: dio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t dio_complete(struct dio *dio, ssize_t ret, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff812f3d50)
Location: fs/direct-io.c:255
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
  - fs/direct-io.c:dio_aio_complete_work
```
**Symbols:**

```
ffffffff812f3d50-ffffffff812f3fa1: dio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t dio_complete(struct dio *dio, ssize_t ret, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff813156e0)
Location: fs/direct-io.c:256
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
  - fs/direct-io.c:dio_aio_complete_work
```
**Symbols:**

```
ffffffff813156e0-ffffffff81315920: dio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t dio_complete(struct dio *dio, ssize_t ret, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81328560)
Location: fs/direct-io.c:255
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
  - fs/direct-io.c:dio_aio_complete_work
```
**Symbols:**

```
ffffffff81328560-ffffffff813287a0: dio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t dio_complete(struct dio *dio, ssize_t ret, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81361d10)
Location: fs/direct-io.c:236
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
  - fs/direct-io.c:dio_aio_complete_work
```
**Symbols:**

```
ffffffff81361d10-ffffffff81361f61: dio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t dio_complete(struct dio *dio, ssize_t ret, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff8136f000)
Location: fs/direct-io.c:236
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
  - fs/direct-io.c:dio_aio_complete_work
```
**Symbols:**

```
ffffffff8136f000-ffffffff8136f255: dio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t dio_complete(struct dio *dio, ssize_t ret, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff813758b0)
Location: fs/direct-io.c:236
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
  - fs/direct-io.c:dio_aio_complete_work
```
**Symbols:**

```
ffffffff813758b0-ffffffff81375b05: dio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t dio_complete(struct dio *dio, ssize_t ret, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff813c1c00)
Location: fs/direct-io.c:236
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
  - fs/direct-io.c:dio_aio_complete_work
```
**Symbols:**

```
ffffffff813c1c00-ffffffff813c1e58: dio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t dio_complete(struct dio *dio, ssize_t ret, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81448a70)
Location: fs/direct-io.c:235
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
  - fs/direct-io.c:dio_aio_complete_work
```
**Symbols:**

```
ffffffff81448a70-ffffffff81448cd0: dio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t dio_complete(struct dio *dio, ssize_t ret, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff814d73f0)
Location: fs/direct-io.c:234
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
  - fs/direct-io.c:dio_aio_complete_work
```
**Symbols:**

```
ffffffff814d73f0-ffffffff814d762e: dio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t dio_complete(struct dio *dio, ssize_t ret, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff815103e0)
Location: fs/direct-io.c:245
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
  - fs/direct-io.c:dio_aio_complete_work
```
**Symbols:**

```
ffffffff815103e0-ffffffff815105e9: dio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t dio_complete(struct dio *dio, ssize_t ret, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81544880)
Location: fs/direct-io.c:245
Inline: False
Direct callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
  - fs/direct-io.c:dio_aio_complete_work
```
**Symbols:**

```
ffffffff81544880-ffffffff81544a89: dio_complete (STB_LOCAL)
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
ssize_t dio_complete(struct dio *dio, ssize_t ret, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffff8000103e39f0)
Location: fs/direct-io.c:255
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
  - fs/direct-io.c:dio_aio_complete_work
```
**Symbols:**

```
ffff8000103e39f0-ffff8000103e3c40: dio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t dio_complete(struct dio *dio, ssize_t ret, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (c05bb744)
Location: fs/direct-io.c:255
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
  - fs/direct-io.c:dio_aio_complete_work
```
**Symbols:**

```
c05bb744-c05bba38: dio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t dio_complete(struct dio *dio, ssize_t ret, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (c0000000004e9890)
Location: fs/direct-io.c:255
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
  - fs/direct-io.c:dio_aio_complete_work
```
**Symbols:**

```
c0000000004e9890-c0000000004e9b84: dio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t dio_complete(struct dio *dio, ssize_t ret, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffe000299934)
Location: fs/direct-io.c:255
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
  - fs/direct-io.c:dio_aio_complete_work
```
**Symbols:**

```
ffffffe000299934-ffffffe000299ada: dio_complete (STB_LOCAL)
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
ssize_t dio_complete(struct dio *dio, ssize_t ret, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81320b40)
Location: fs/direct-io.c:255
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
  - fs/direct-io.c:dio_aio_complete_work
```
**Symbols:**

```
ffffffff81320b40-ffffffff81320d80: dio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t dio_complete(struct dio *dio, ssize_t ret, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff813116e0)
Location: fs/direct-io.c:255
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
  - fs/direct-io.c:dio_aio_complete_work
```
**Symbols:**

```
ffffffff813116e0-ffffffff81311920: dio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t dio_complete(struct dio *dio, ssize_t ret, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff8131e610)
Location: fs/direct-io.c:255
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
  - fs/direct-io.c:dio_aio_complete_work
```
**Symbols:**

```
ffffffff8131e610-ffffffff8131e850: dio_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t dio_complete(struct dio *dio, ssize_t ret, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81330310)
Location: fs/direct-io.c:255
Inline: False
Direct callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:dio_bio_end_aio
  - fs/direct-io.c:dio_aio_complete_work
```
**Symbols:**

```
ffffffff81330310-ffffffff81330550: dio_complete (STB_LOCAL)
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
<b>Param removed. </b>
<code>loff_t offset</code>
</li>
<li>
<b>Param reordered. </b>
<code>dio, offset, ret, is_async</code> ➡️ <code>dio, ret, is_async</code>
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool is_async</code>
</li>
</ul>
</details>
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
