# Function: <code>ext4_clear_mount_flag</code>

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
In fs/ext4/super.c (ffffffff8144c6b9)
Location: fs/ext4/ext4.h:1733
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/fast_commit.c (ffffffff81455d65)
Location: fs/ext4/ext4.h:1733
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
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
In fs/ext4/super.c (ffffffff814521e5)
Location: fs/ext4/ext4.h:1742
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/fast_commit.c (ffffffff8145b997)
Location: fs/ext4/ext4.h:1742
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
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
In fs/ext4/super.c (ffffffff814a57e1)
Location: fs/ext4/ext4.h:1803
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/fast_commit.c (ffffffff814af2e1)
Location: fs/ext4/ext4.h:1803
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
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
In fs/ext4/super.c (ffffffff8152d82b)
Location: fs/ext4/ext4.h:1805
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
```
```
In fs/ext4/fast_commit.c (ffffffff8153634a)
Location: fs/ext4/ext4.h:1805
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
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
In fs/ext4/super.c (ffffffff815cb9ed)
Location: fs/ext4/ext4.h:1815
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
```
```
In fs/ext4/fast_commit.c (ffffffff815d484a)
Location: fs/ext4/ext4.h:1815
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
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
In fs/ext4/super.c (ffffffff81603498)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
```
```
In fs/ext4/fast_commit.c (ffffffff8160c43a)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
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
In fs/ext4/super.c (ffffffff8163c2b3)
Location: fs/ext4/ext4.h:1828
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
```
```
In fs/ext4/fast_commit.c (ffffffff816451fa)
Location: fs/ext4/ext4.h:1828
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
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
