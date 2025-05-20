# Function: <code>rdev_dec_pending</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81691448)
Location: drivers/md/md.h:688
Inline: True
Inline callers:
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/bitmap.c (ffffffff8169d6b1)
Location: drivers/md/md.h:688
Inline: True
Inline callers:
  - drivers/md/bitmap.c:write_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff816f229e)
Location: drivers/md/md.h:666
Inline: True
Inline callers:
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/bitmap.c (ffffffff816fe9a9)
Location: drivers/md/md.h:666
Inline: True
Inline callers:
  - drivers/md/bitmap.c:write_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81727472)
Location: drivers/md/md.h:692
Inline: True
Inline callers:
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/bitmap.c (ffffffff81730608)
Location: drivers/md/md.h:692
Inline: True
Inline callers:
  - drivers/md/bitmap.c:write_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8173fbd2)
Location: drivers/md/md.h:699
Inline: True
Inline callers:
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/bitmap.c (ffffffff8174846e)
Location: drivers/md/md.h:699
Inline: True
Inline callers:
  - drivers/md/bitmap.c:write_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817b1bf2)
Location: drivers/md/md.h:706
Inline: True
Inline callers:
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/md-bitmap.c (ffffffff817ba6fe)
Location: drivers/md/md.h:706
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817f38c2)
Location: drivers/md/md.h:725
Inline: True
Inline callers:
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/md-bitmap.c (ffffffff81802686)
Location: drivers/md/md.h:725
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81821642)
Location: drivers/md/md.h:727
Inline: True
Inline callers:
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/md-bitmap.c (ffffffff8182e995)
Location: drivers/md/md.h:727
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81863ada)
Location: drivers/md/md.h:738
Inline: True
Inline callers:
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/md-bitmap.c (ffffffff81870dba)
Location: drivers/md/md.h:738
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8189581a)
Location: drivers/md/md.h:758
Inline: True
Inline callers:
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/md-bitmap.c (ffffffff818a2baa)
Location: drivers/md/md.h:758
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81965512)
Location: drivers/md/md.h:769
Inline: True
Inline callers:
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/md-bitmap.c (ffffffff819726c2)
Location: drivers/md/md.h:769
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_sb_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8196bf62)
Location: drivers/md/md.h:771
Inline: True
Inline callers:
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/md-bitmap.c (ffffffff819775d2)
Location: drivers/md/md.h:771
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_sb_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8194e272)
Location: drivers/md/md.h:770
Inline: True
Inline callers:
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/md-bitmap.c (ffffffff8195b532)
Location: drivers/md/md.h:770
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_sb_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff819f3672)
Location: drivers/md/md.h:778
Inline: True
Inline callers:
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/md-bitmap.c (ffffffff81a00d22)
Location: drivers/md/md.h:778
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_sb_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81b5d394)
Location: drivers/md/md.h:786
Inline: True
Inline callers:
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/md-bitmap.c (ffffffff81b67ad8)
Location: drivers/md/md.h:786
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_sb_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81cf49fe)
Location: drivers/md/md.h:803
Inline: True
Inline callers:
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/md-bitmap.c (ffffffff81d03488)
Location: drivers/md/md.h:803
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_sb_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81d5c80e)
Location: drivers/md/md.h:820
Inline: True
Inline callers:
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/md-bitmap.c (ffffffff81d6e950)
Location: drivers/md/md.h:820
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81e13e5e)
Location: drivers/md/md.h:798
Inline: True
Inline callers:
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/md-bitmap.c (ffffffff81e2469e)
Location: drivers/md/md.h:798
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_sb_page
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffff800010ae84bc)
Location: drivers/md/md.h:758
Inline: True
Inline callers:
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/md-bitmap.c (ffff800010af8688)
Location: drivers/md/md.h:758
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c0bcc9c4)
Location: drivers/md/md.h:758
Inline: True
Inline callers:
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/md-bitmap.c (c0bd8710)
Location: drivers/md/md.h:758
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c000000000bd6bf4)
Location: drivers/md/md.h:758
Inline: True
Inline callers:
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/md-bitmap.c (c000000000be4660)
Location: drivers/md/md.h:758
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffe0006dc26e)
Location: drivers/md/md.h:758
Inline: True
Inline callers:
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/md-bitmap.c (ffffffe0006e9714)
Location: drivers/md/md.h:758
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8183b69a)
Location: drivers/md/md.h:758
Inline: True
Inline callers:
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/md-bitmap.c (ffffffff81848a2a)
Location: drivers/md/md.h:758
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81802cfa)
Location: drivers/md/md.h:758
Inline: True
Inline callers:
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/md-bitmap.c (ffffffff8181008a)
Location: drivers/md/md.h:758
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8188acca)
Location: drivers/md/md.h:758
Inline: True
Inline callers:
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/md-bitmap.c (ffffffff8189805a)
Location: drivers/md/md.h:758
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818a9ee5)
Location: drivers/md/md.h:758
Inline: True
Inline callers:
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/md-bitmap.c (ffffffff818b425a)
Location: drivers/md/md.h:758
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
```
</details>
</li>
</ul>

## Differences
