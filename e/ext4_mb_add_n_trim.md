# Function: <code>ext4_mb_add_n_trim</code>

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
In fs/ext4/mballoc.c (ffffffff812d1431)
Location: fs/ext4/mballoc.c:4300
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
In fs/ext4/mballoc.c (ffffffff81304078)
Location: fs/ext4/mballoc.c:4314
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
In fs/ext4/mballoc.c (ffffffff8131a038)
Location: fs/ext4/mballoc.c:4321
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
In fs/ext4/mballoc.c (ffffffff813113ec)
Location: fs/ext4/mballoc.c:4382
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
In fs/ext4/mballoc.c (ffffffff81332fbc)
Location: fs/ext4/mballoc.c:4382
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
In fs/ext4/mballoc.c (ffffffff81364373)
Location: fs/ext4/mballoc.c:4352
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
In fs/ext4/mballoc.c (ffffffff8137c616)
Location: fs/ext4/mballoc.c:4351
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
In fs/ext4/mballoc.c (ffffffff813a2ebb)
Location: fs/ext4/mballoc.c:4352
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
In fs/ext4/mballoc.c (ffffffff813bbd1b)
Location: fs/ext4/mballoc.c:4371
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
void ext4_mb_add_n_trim(struct ext4_allocation_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff814071f0)
Location: fs/ext4/mballoc.c:4549
Inline: False
```
**Symbols:**

```
ffffffff814071f0-ffffffff8140734e: ext4_mb_add_n_trim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_mb_add_n_trim(struct ext4_allocation_context *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8141a440)
Location: fs/ext4/mballoc.c:4729
Inline: False
```
**Symbols:**

```
ffffffff8141a440-ffffffff8141a59e: ext4_mb_add_n_trim (STB_LOCAL)
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
In fs/ext4/mballoc.c (ffffffff81424b28)
Location: fs/ext4/mballoc.c:5262
Inline: True
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
In fs/ext4/mballoc.c (ffffffff81478797)
Location: fs/ext4/mballoc.c:5318
Inline: True
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
In fs/ext4/mballoc.c (ffffffff814faf49)
Location: fs/ext4/mballoc.c:5373
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff815956da)
Location: fs/ext4/mballoc.c:5344
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff815c6a25)
Location: fs/ext4/mballoc.c:5948
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8160118c)
Location: fs/ext4/mballoc.c:5912
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
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
In fs/ext4/mballoc.c (ffff80001049284c)
Location: fs/ext4/mballoc.c:4371
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
In fs/ext4/mballoc.c (c0653b8c)
Location: fs/ext4/mballoc.c:4371
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
In fs/ext4/mballoc.c (c0000000005baf34)
Location: fs/ext4/mballoc.c:4371
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
In fs/ext4/mballoc.c (ffffffe0003174dc)
Location: fs/ext4/mballoc.c:4371
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
In fs/ext4/mballoc.c (ffffffff813b42fb)
Location: fs/ext4/mballoc.c:4371
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
In fs/ext4/mballoc.c (ffffffff813a4d8b)
Location: fs/ext4/mballoc.c:4371
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
In fs/ext4/mballoc.c (ffffffff813b1b5b)
Location: fs/ext4/mballoc.c:4371
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
In fs/ext4/mballoc.c (ffffffff813c669f)
Location: fs/ext4/mballoc.c:4371
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
</ul>
