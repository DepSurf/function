# Function: <code>get_more_blocks</code>

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
In fs/direct-io.c (ffffffff8124ad0d)
Location: fs/direct-io.c:598
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
In fs/direct-io.c (ffffffff812735c7)
Location: fs/direct-io.c:607
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
In fs/direct-io.c (ffffffff81287082)
Location: fs/direct-io.c:610
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
In fs/direct-io.c (ffffffff812945a3)
Location: fs/direct-io.c:613
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
In fs/direct-io.c (ffffffff812b7545)
Location: fs/direct-io.c:652
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
In fs/direct-io.c (ffffffff812e01cb)
Location: fs/direct-io.c:673
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
In fs/direct-io.c (ffffffff812f4d92)
Location: fs/direct-io.c:673
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81315f8a)
Location: fs/direct-io.c:666
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81328e0a)
Location: fs/direct-io.c:665
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81362ead)
Location: fs/direct-io.c:646
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81370014)
Location: fs/direct-io.c:627
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff813768b3)
Location: fs/direct-io.c:629
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff813c2e11)
Location: fs/direct-io.c:629
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81449c51)
Location: fs/direct-io.c:619
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int get_more_blocks(struct dio *dio, struct dio_submit *sdio, struct buffer_head *map_bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/direct-io.c (0)
Location: fs/direct-io.c:620
Inline: False
Direct callers:
  - fs/direct-io.c:do_direct_IO
```
**Symbols:**

```
ffffffff814d8140-ffffffff814d829f: get_more_blocks (STB_LOCAL)
ffffffff82069499-ffffffff8206956d: get_more_blocks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int get_more_blocks(struct dio *dio, struct dio_submit *sdio, struct buffer_head *map_bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/direct-io.c (0)
Location: fs/direct-io.c:602
Inline: False
Direct callers:
  - fs/direct-io.c:do_direct_IO
```
**Symbols:**

```
ffffffff815107a0-ffffffff815108ff: get_more_blocks (STB_LOCAL)
ffffffff820e940f-ffffffff820e94e3: get_more_blocks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int get_more_blocks(struct dio *dio, struct dio_submit *sdio, struct buffer_head *map_bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/direct-io.c (0)
Location: fs/direct-io.c:602
Inline: False
Direct callers:
  - fs/direct-io.c:do_direct_IO
```
**Symbols:**

```
ffffffff81544c40-ffffffff81544d9f: get_more_blocks (STB_LOCAL)
ffffffff821c5f7a-ffffffff821c604e: get_more_blocks.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffff8000103e435c)
Location: fs/direct-io.c:665
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (c05bc260)
Location: fs/direct-io.c:665
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (c0000000004ea430)
Location: fs/direct-io.c:665
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffe000299f8c)
Location: fs/direct-io.c:665
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff813213ea)
Location: fs/direct-io.c:665
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81311f8a)
Location: fs/direct-io.c:665
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff8131eeba)
Location: fs/direct-io.c:665
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81330bce)
Location: fs/direct-io.c:665
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
