# Function: <code>ext4_mb_collect_stats</code>

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
In fs/ext4/mballoc.c (ffffffff812d110f)
Location: fs/ext4/mballoc.c:3206
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
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
In fs/ext4/mballoc.c (ffffffff81303d5e)
Location: fs/ext4/mballoc.c:3220
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
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
In fs/ext4/mballoc.c (ffffffff81319d1e)
Location: fs/ext4/mballoc.c:3227
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
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
In fs/ext4/mballoc.c (ffffffff8131100d)
Location: fs/ext4/mballoc.c:3283
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
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
In fs/ext4/mballoc.c (ffffffff81332d56)
Location: fs/ext4/mballoc.c:3283
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
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
In fs/ext4/mballoc.c (ffffffff81363fc3)
Location: fs/ext4/mballoc.c:3253
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
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
In fs/ext4/mballoc.c (ffffffff8137c265)
Location: fs/ext4/mballoc.c:3253
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
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
In fs/ext4/mballoc.c (ffffffff813a2cda)
Location: fs/ext4/mballoc.c:3255
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
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
In fs/ext4/mballoc.c (ffffffff813bbb3a)
Location: fs/ext4/mballoc.c:3274
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ext4_mb_collect_stats(struct ext4_allocation_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81403930)
Location: fs/ext4/mballoc.c:3400
Inline: False
```
**Symbols:**

```
ffffffff81403930-ffffffff81403a5d: ext4_mb_collect_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_mb_collect_stats(struct ext4_allocation_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81416ba0)
Location: fs/ext4/mballoc.c:3582
Inline: False
```
**Symbols:**

```
ffffffff81416ba0-ffffffff81416c8f: ext4_mb_collect_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_mb_collect_stats(struct ext4_allocation_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8141caf0)
Location: fs/ext4/mballoc.c:4114
Inline: False
```
**Symbols:**

```
ffffffff8141caf0-ffffffff8141cbeb: ext4_mb_collect_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_mb_collect_stats(struct ext4_allocation_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8146fb40)
Location: fs/ext4/mballoc.c:4185
Inline: False
```
**Symbols:**

```
ffffffff8146fb40-ffffffff8146fc31: ext4_mb_collect_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_mb_collect_stats(struct ext4_allocation_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff814f0b90)
Location: fs/ext4/mballoc.c:4240
Inline: False
```
**Symbols:**

```
ffffffff814f0b90-ffffffff814f0cc8: ext4_mb_collect_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_mb_collect_stats(struct ext4_allocation_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8158b3a0)
Location: fs/ext4/mballoc.c:4210
Inline: False
```
**Symbols:**

```
ffffffff8158b3a0-ffffffff8158b4ea: ext4_mb_collect_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_mb_collect_stats(struct ext4_allocation_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff815c2430)
Location: fs/ext4/mballoc.c:4572
Inline: False
```
**Symbols:**

```
ffffffff815c2430-ffffffff815c262c: ext4_mb_collect_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_mb_collect_stats(struct ext4_allocation_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff815fb0b0)
Location: fs/ext4/mballoc.c:4584
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
```
**Symbols:**

```
ffffffff815fb0b0-ffffffff815fb2ac: ext4_mb_collect_stats (STB_LOCAL)
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
In fs/ext4/mballoc.c (ffff800010492550)
Location: fs/ext4/mballoc.c:3274
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
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
In fs/ext4/mballoc.c (c0653908)
Location: fs/ext4/mballoc.c:3274
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
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
In fs/ext4/mballoc.c (c0000000005baa94)
Location: fs/ext4/mballoc.c:3274
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
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
In fs/ext4/mballoc.c (ffffffe000317286)
Location: fs/ext4/mballoc.c:3274
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
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
In fs/ext4/mballoc.c (ffffffff813b411a)
Location: fs/ext4/mballoc.c:3274
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
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
In fs/ext4/mballoc.c (ffffffff813a4baa)
Location: fs/ext4/mballoc.c:3274
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
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
In fs/ext4/mballoc.c (ffffffff813b197a)
Location: fs/ext4/mballoc.c:3274
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
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
In fs/ext4/mballoc.c (ffffffff813c64ae)
Location: fs/ext4/mballoc.c:3274
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
