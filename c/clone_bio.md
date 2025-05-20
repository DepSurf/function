# Function: <code>clone_bio</code>

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
In drivers/md/dm.c (ffffffff816a29aa)
Location: drivers/md/dm.c:1525
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
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
In drivers/md/dm.c (ffffffff817032c4)
Location: drivers/md/dm.c:1027
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
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
In drivers/md/dm.c (ffffffff81735191)
Location: drivers/md/dm.c:1082
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
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
In drivers/md/dm.c (ffffffff8174d3c6)
Location: drivers/md/dm.c:1244
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
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
In drivers/md/dm.c (ffffffff817bf5a6)
Location: drivers/md/dm.c:1235
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
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
In drivers/md/dm.c (ffffffff81808725)
Location: drivers/md/dm.c:1292
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
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
In drivers/md/dm.c (ffffffff818345d9)
Location: drivers/md/dm.c:1316
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
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
In drivers/md/dm.c (ffffffff818763b0)
Location: drivers/md/dm.c:1321
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
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
In drivers/md/dm.c (ffffffff818a81af)
Location: drivers/md/dm.c:1321
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int clone_bio(struct dm_target_io *tio, struct bio *bio, sector_t sector, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:1330
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff81977090-ffffffff8197714e: clone_bio (STB_LOCAL)
ffffffff8197b544-ffffffff8197b56d: clone_bio.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int clone_bio(struct dm_target_io *tio, struct bio *bio, sector_t sector, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:1360
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff8197bc90-ffffffff8197bd58: clone_bio (STB_LOCAL)
ffffffff81c2802f-ffffffff81c28058: clone_bio.cold (STB_LOCAL)
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
In drivers/md/dm.c (ffffffff819611d7)
Location: drivers/md/dm.c:1368
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
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
In drivers/md/dm.c (ffffffff81a0adf7)
Location: drivers/md/dm.c:1264
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/md/dm.c (ffff800010afef0c)
Location: drivers/md/dm.c:1321
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
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
In drivers/md/dm.c (c0bddd74)
Location: drivers/md/dm.c:1321
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
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
In drivers/md/dm.c (c000000000becd60)
Location: drivers/md/dm.c:1321
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
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
In drivers/md/dm.c (ffffffe0006ee64c)
Location: drivers/md/dm.c:1321
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
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
In drivers/md/dm.c (ffffffff8184e02f)
Location: drivers/md/dm.c:1321
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
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
In drivers/md/dm.c (ffffffff8181564f)
Location: drivers/md/dm.c:1321
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
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
In drivers/md/dm.c (ffffffff8189d65f)
Location: drivers/md/dm.c:1321
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
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
In drivers/md/dm.c (ffffffff818b99bf)
Location: drivers/md/dm.c:1321
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
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
