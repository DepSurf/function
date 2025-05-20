# Function: <code>mb_test_and_clear_bits</code>

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
In fs/ext4/mballoc.c (ffffffff812cfda7)
Location: fs/ext4/mballoc.c:1301
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
In fs/ext4/mballoc.c (ffffffff812ff977)
Location: fs/ext4/mballoc.c:1310
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
In fs/ext4/mballoc.c (ffffffff813159e7)
Location: fs/ext4/mballoc.c:1310
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
In fs/ext4/mballoc.c (ffffffff8130cd97)
Location: fs/ext4/mballoc.c:1308
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
In fs/ext4/mballoc.c (ffffffff813319f7)
Location: fs/ext4/mballoc.c:1308
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
In fs/ext4/mballoc.c (ffffffff81360013)
Location: fs/ext4/mballoc.c:1297
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
In fs/ext4/mballoc.c (ffffffff81378353)
Location: fs/ext4/mballoc.c:1297
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
In fs/ext4/mballoc.c (ffffffff813a1977)
Location: fs/ext4/mballoc.c:1297
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
In fs/ext4/mballoc.c (ffffffff813ba7e7)
Location: fs/ext4/mballoc.c:1297
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
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
In fs/ext4/mballoc.c (ffffffff81406561)
Location: fs/ext4/mballoc.c:1358
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mb_test_and_clear_bits(void *bm, int cur, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81415a00)
Location: fs/ext4/mballoc.c:1330
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:mb_free_blocks
```
**Symbols:**

```
ffffffff81415a00-ffffffff81415af5: mb_test_and_clear_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mb_test_and_clear_bits(void *bm, int cur, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8141bbc0)
Location: fs/ext4/mballoc.c:1664
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:mb_free_blocks
```
**Symbols:**

```
ffffffff8141bbc0-ffffffff8141bcc4: mb_test_and_clear_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mb_test_and_clear_bits(void *bm, int cur, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8146ef90)
Location: fs/ext4/mballoc.c:1668
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:mb_free_blocks
```
**Symbols:**

```
ffffffff8146ef90-ffffffff8146f091: mb_test_and_clear_bits (STB_LOCAL)
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
In fs/ext4/mballoc.c (ffffffff814f1e8d)
Location: fs/ext4/mballoc.c:1665
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
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
In fs/ext4/mballoc.c (ffffffff8158ca8c)
Location: fs/ext4/mballoc.c:1622
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
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
In fs/ext4/mballoc.c (ffffffff815c3518)
Location: fs/ext4/mballoc.c:1761
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
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
In fs/ext4/mballoc.c (ffffffff815fee6f)
Location: fs/ext4/mballoc.c:1777
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_free_blocks
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
In fs/ext4/mballoc.c (ffff800010490fa0)
Location: fs/ext4/mballoc.c:1297
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
In fs/ext4/mballoc.c (c0652110)
Location: fs/ext4/mballoc.c:1297
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
In fs/ext4/mballoc.c (c0000000005b8adc)
Location: fs/ext4/mballoc.c:1297
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
In fs/ext4/mballoc.c (ffffffe000315d9a)
Location: fs/ext4/mballoc.c:1297
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
In fs/ext4/mballoc.c (ffffffff813b2dc7)
Location: fs/ext4/mballoc.c:1297
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
In fs/ext4/mballoc.c (ffffffff813a3857)
Location: fs/ext4/mballoc.c:1297
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
In fs/ext4/mballoc.c (ffffffff813b0627)
Location: fs/ext4/mballoc.c:1297
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
In fs/ext4/mballoc.c (ffffffff813c50f7)
Location: fs/ext4/mballoc.c:1297
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
