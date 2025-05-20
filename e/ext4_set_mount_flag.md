# Function: <code>ext4_set_mount_flag</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff813fb033)
Location: fs/ext4/ext4.h:1728
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/super.c (ffffffff81447930)
Location: fs/ext4/ext4.h:1728
Inline: True
Inline callers:
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:ext4_handle_error
```
```
In fs/ext4/fast_commit.c (ffffffff81456b91)
Location: fs/ext4/ext4.h:1728
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_stop_ineligible
  - fs/ext4/fast_commit.c:ext4_fc_mark_ineligible
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
In fs/ext4/file.c (ffffffff81401503)
Location: fs/ext4/ext4.h:1737
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/super.c (ffffffff8144d14f)
Location: fs/ext4/ext4.h:1737
Inline: True
Inline callers:
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:ext4_handle_error
```
```
In fs/ext4/fast_commit.c (ffffffff8145bc4e)
Location: fs/ext4/ext4.h:1737
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_perform_commit
  - fs/ext4/fast_commit.c:ext4_fc_stop_ineligible
  - fs/ext4/fast_commit.c:ext4_fc_mark_ineligible
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
In fs/ext4/file.c (ffffffff81453a83)
Location: fs/ext4/ext4.h:1798
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/super.c (ffffffff814a11df)
Location: fs/ext4/ext4.h:1798
Inline: True
Inline callers:
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:ext4_handle_error
```
```
In fs/ext4/fast_commit.c (ffffffff814afb22)
Location: fs/ext4/ext4.h:1798
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_mark_ineligible
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
In fs/ext4/file.c (ffffffff814d0f68)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/super.c (ffffffff815257b1)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_handle_error
```
```
In fs/ext4/fast_commit.c (ffffffff815380a9)
Location: fs/ext4/ext4.h:1800
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_mark_ineligible
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
In fs/ext4/file.c (ffffffff815699a8)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/super.c (ffffffff815c2e31)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_handle_error
```
```
In fs/ext4/fast_commit.c (ffffffff815d62c9)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_mark_ineligible
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
In fs/ext4/file.c (ffffffff815a1798)
Location: fs/ext4/ext4.h:1805
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/super.c (ffffffff815fa591)
Location: fs/ext4/ext4.h:1805
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_handle_error
```
```
In fs/ext4/fast_commit.c (ffffffff8160de79)
Location: fs/ext4/ext4.h:1805
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_mark_ineligible
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
In fs/ext4/file.c (ffffffff815da548)
Location: fs/ext4/ext4.h:1823
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/fast_commit.c (ffffffff81646c39)
Location: fs/ext4/ext4.h:1823
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_mark_ineligible
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
