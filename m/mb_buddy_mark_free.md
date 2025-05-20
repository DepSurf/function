# Function: <code>mb_buddy_mark_free</code>

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
In fs/ext4/mballoc.c (ffffffff812cff5c)
Location: fs/ext4/mballoc.c:1360
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
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
In fs/ext4/mballoc.c (ffffffff812ffb3e)
Location: fs/ext4/mballoc.c:1369
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
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
In fs/ext4/mballoc.c (ffffffff81315bad)
Location: fs/ext4/mballoc.c:1369
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
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
In fs/ext4/mballoc.c (ffffffff8130cff8)
Location: fs/ext4/mballoc.c:1367
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
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
In fs/ext4/mballoc.c (ffffffff81331c58)
Location: fs/ext4/mballoc.c:1367
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
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
In fs/ext4/mballoc.c (ffffffff813602b9)
Location: fs/ext4/mballoc.c:1356
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
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
In fs/ext4/mballoc.c (ffffffff813785f9)
Location: fs/ext4/mballoc.c:1356
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
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
In fs/ext4/mballoc.c (ffffffff813a1be9)
Location: fs/ext4/mballoc.c:1356
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
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
In fs/ext4/mballoc.c (ffffffff813baa59)
Location: fs/ext4/mballoc.c:1356
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mb_buddy_mark_free(struct ext4_buddy *e4b, int first, int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81403590)
Location: fs/ext4/mballoc.c:1417
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
**Symbols:**

```
ffffffff81403590-ffffffff8140372e: mb_buddy_mark_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mb_buddy_mark_free(struct ext4_buddy *e4b, int first, int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81416130)
Location: fs/ext4/mballoc.c:1386
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
**Symbols:**

```
ffffffff81416130-ffffffff814162ce: mb_buddy_mark_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mb_buddy_mark_free(struct ext4_buddy *e4b, int first, int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8141c740)
Location: fs/ext4/mballoc.c:1720
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
**Symbols:**

```
ffffffff8141c740-ffffffff8141c8ea: mb_buddy_mark_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mb_buddy_mark_free(struct ext4_buddy *e4b, int first, int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81470760)
Location: fs/ext4/mballoc.c:1724
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
**Symbols:**

```
ffffffff81470760-ffffffff814708fc: mb_buddy_mark_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mb_buddy_mark_free(struct ext4_buddy *e4b, int first, int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff814f1c20)
Location: fs/ext4/mballoc.c:1721
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
**Symbols:**

```
ffffffff814f1c20-ffffffff814f1dd3: mb_buddy_mark_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mb_buddy_mark_free(struct ext4_buddy *e4b, int first, int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8158c7e0)
Location: fs/ext4/mballoc.c:1678
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
**Symbols:**

```
ffffffff8158c7e0-ffffffff8158c9c2: mb_buddy_mark_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mb_buddy_mark_free(struct ext4_buddy *e4b, int first, int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff815c3280)
Location: fs/ext4/mballoc.c:1817
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
**Symbols:**

```
ffffffff815c3280-ffffffff815c3453: mb_buddy_mark_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mb_buddy_mark_free(struct ext4_buddy *e4b, int first, int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff815fbf00)
Location: fs/ext4/mballoc.c:1833
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
**Symbols:**

```
ffffffff815fbf00-ffffffff815fc0d3: mb_buddy_mark_free (STB_LOCAL)
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
In fs/ext4/mballoc.c (ffff800010491230)
Location: fs/ext4/mballoc.c:1356
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
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
In fs/ext4/mballoc.c (c06523d8)
Location: fs/ext4/mballoc.c:1356
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
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
In fs/ext4/mballoc.c (c0000000005b8e48)
Location: fs/ext4/mballoc.c:1356
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
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
In fs/ext4/mballoc.c (ffffffe000315ff0)
Location: fs/ext4/mballoc.c:1356
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
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
In fs/ext4/mballoc.c (ffffffff813b3039)
Location: fs/ext4/mballoc.c:1356
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
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
In fs/ext4/mballoc.c (ffffffff813a3ac9)
Location: fs/ext4/mballoc.c:1356
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
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
In fs/ext4/mballoc.c (ffffffff813b0899)
Location: fs/ext4/mballoc.c:1356
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
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
In fs/ext4/mballoc.c (ffffffff813c5369)
Location: fs/ext4/mballoc.c:1356
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
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
