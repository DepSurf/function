# Function: <code>__find_get_block_slow</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct buffer_head *__find_get_block_slow(struct block_device *bdev, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81242d20)
Location: fs/buffer.c:202
Inline: False
Direct callers:
  - fs/buffer.c:unmap_underlying_metadata
```
**Symbols:**

```
ffffffff81242d20-ffffffff81242e78: __find_get_block_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct buffer_head *__find_get_block_slow(struct block_device *bdev, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126c3a0)
Location: fs/buffer.c:200
Inline: False
Direct callers:
  - fs/buffer.c:unmap_underlying_metadata
```
**Symbols:**

```
ffffffff8126c3a0-ffffffff8126c4f2: __find_get_block_slow (STB_LOCAL)
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
In fs/buffer.c (ffffffff8127fb12)
Location: fs/buffer.c:201
Inline: True
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
In fs/buffer.c (ffffffff8128cec1)
Location: fs/buffer.c:201
Inline: True
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
In fs/buffer.c (ffffffff812afb64)
Location: fs/buffer.c:201
Inline: True
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
In fs/buffer.c (ffffffff812d7e06)
Location: fs/buffer.c:193
Inline: True
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
In fs/buffer.c (ffffffff812ece46)
Location: fs/buffer.c:193
Inline: True
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
In fs/buffer.c (ffffffff8130e5f7)
Location: fs/buffer.c:194
Inline: True
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
In fs/buffer.c (ffffffff81321617)
Location: fs/buffer.c:194
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct buffer_head *__find_get_block_slow(struct block_device *bdev, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:189
Inline: False
```
**Symbols:**

```
ffffffff8135b700-ffffffff8135b86b: __find_get_block_slow (STB_LOCAL)
ffffffff8135e826-ffffffff8135e867: __find_get_block_slow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct buffer_head *__find_get_block_slow(struct block_device *bdev, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:189
Inline: False
```
**Symbols:**

```
ffffffff81369cd0-ffffffff81369e38: __find_get_block_slow (STB_LOCAL)
ffffffff81beaaca-ffffffff81beab0b: __find_get_block_slow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct buffer_head *__find_get_block_slow(struct block_device *bdev, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:189
Inline: False
```
**Symbols:**

```
ffffffff81370a00-ffffffff81370b65: __find_get_block_slow (STB_LOCAL)
ffffffff81bdcaf9-ffffffff81bdcb3a: __find_get_block_slow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct buffer_head *__find_get_block_slow(struct block_device *bdev, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:189
Inline: False
```
**Symbols:**

```
ffffffff813bf6d0-ffffffff813bf844: __find_get_block_slow (STB_LOCAL)
ffffffff81cc461d-ffffffff81cc469e: __find_get_block_slow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct buffer_head *__find_get_block_slow(struct block_device *bdev, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:189
Inline: False
```
**Symbols:**

```
ffffffff81444a70-ffffffff81444c04: __find_get_block_slow (STB_LOCAL)
ffffffff81e76ed5-ffffffff81e76f41: __find_get_block_slow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct buffer_head *__find_get_block_slow(struct block_device *bdev, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:189
Inline: False
```
**Symbols:**

```
ffffffff814d3e80-ffffffff814d4068: __find_get_block_slow (STB_LOCAL)
ffffffff8206906b-ffffffff820690a5: __find_get_block_slow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct buffer_head *__find_get_block_slow(struct block_device *bdev, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:189
Inline: False
```
**Symbols:**

```
ffffffff815096a0-ffffffff815097f8: __find_get_block_slow (STB_LOCAL)
ffffffff820e88fd-ffffffff820e8937: __find_get_block_slow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct buffer_head *__find_get_block_slow(struct block_device *bdev, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:190
Inline: False
```
**Symbols:**

```
ffffffff8153e440-ffffffff8153e595: __find_get_block_slow (STB_LOCAL)
ffffffff821c56e3-ffffffff821c571e: __find_get_block_slow.cold (STB_LOCAL)
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
In fs/buffer.c (ffff8000103d9f08)
Location: fs/buffer.c:194
Inline: True
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
In fs/buffer.c (c05b3424)
Location: fs/buffer.c:194
Inline: True
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
In fs/buffer.c (c0000000004ded3c)
Location: fs/buffer.c:194
Inline: True
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
In fs/buffer.c (ffffffe000292c40)
Location: fs/buffer.c:194
Inline: True
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
In fs/buffer.c (ffffffff81319bf7)
Location: fs/buffer.c:194
Inline: True
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
In fs/buffer.c (ffffffff8130a7a6)
Location: fs/buffer.c:194
Inline: True
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
In fs/buffer.c (ffffffff813176c7)
Location: fs/buffer.c:194
Inline: True
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
In fs/buffer.c (ffffffff813292cc)
Location: fs/buffer.c:194
Inline: True
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
