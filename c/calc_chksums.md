# Function: <code>calc_chksums</code>

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
In fs/jbd2/recovery.c (ffffffff812ebc66)
Location: fs/jbd2/recovery.c:354
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffffffff813195a6)
Location: fs/jbd2/recovery.c:353
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffffffff8132f596)
Location: fs/jbd2/recovery.c:353
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffffffff813447ca)
Location: fs/jbd2/recovery.c:353
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffffffff81368e6a)
Location: fs/jbd2/recovery.c:353
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffffffff813974de)
Location: fs/jbd2/recovery.c:350
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffffffff813b044d)
Location: fs/jbd2/recovery.c:350
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffffffff813da8c7)
Location: fs/jbd2/recovery.c:350
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffffffff813f4917)
Location: fs/jbd2/recovery.c:350
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int calc_chksums(journal_t *journal, struct buffer_head *bh, long unsigned int *next_log_block, __u32 *crc32_sum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/recovery.c (0)
Location: fs/jbd2/recovery.c:350
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff814418e0-ffffffff814419be: calc_chksums (STB_LOCAL)
ffffffff81442606-ffffffff81442621: calc_chksums.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int calc_chksums(journal_t *journal, struct buffer_head *bh, long unsigned int *next_log_block, __u32 *crc32_sum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/recovery.c (0)
Location: fs/jbd2/recovery.c:390
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:do_one_pass
```
**Symbols:**

```
ffffffff8145dad0-ffffffff8145dbd0: calc_chksums (STB_LOCAL)
ffffffff81becd91-ffffffff81becdac: calc_chksums.cold (STB_LOCAL)
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
In fs/jbd2/recovery.c (ffffffff81463730)
Location: fs/jbd2/recovery.c:389
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffffffff814b8cb9)
Location: fs/jbd2/recovery.c:389
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffffffff81542bee)
Location: fs/jbd2/recovery.c:389
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffffffff815e1911)
Location: fs/jbd2/recovery.c:395
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffffffff81618e26)
Location: fs/jbd2/recovery.c:401
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffffffff81652218)
Location: fs/jbd2/recovery.c:400
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffff8000104d0424)
Location: fs/jbd2/recovery.c:350
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (c0692e50)
Location: fs/jbd2/recovery.c:350
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (c0000000006094ac)
Location: fs/jbd2/recovery.c:350
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffffffe00034789a)
Location: fs/jbd2/recovery.c:350
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffffffff813ecef7)
Location: fs/jbd2/recovery.c:350
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffffffff813dd977)
Location: fs/jbd2/recovery.c:350
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffffffff813ea277)
Location: fs/jbd2/recovery.c:350
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
In fs/jbd2/recovery.c (ffffffff813ffbd6)
Location: fs/jbd2/recovery.c:350
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
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
