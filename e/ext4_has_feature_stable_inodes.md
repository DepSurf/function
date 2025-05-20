# Function: <code>ext4_has_feature_stable_inodes</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8141d135)
Location: fs/ext4/ext4.h:1898
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_has_stable_inodes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81433775)
Location: fs/ext4/ext4.h:2023
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_has_stable_inodes
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
In fs/ext4/super.c (ffffffff81439f55)
Location: fs/ext4/ext4.h:2032
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_has_stable_inodes
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
In fs/ext4/super.c (ffffffff8148dbd5)
Location: fs/ext4/ext4.h:2097
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_has_stable_inodes
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
In fs/ext4/crypto.c (ffffffff8153c715)
Location: fs/ext4/ext4.h:2099
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_has_stable_inodes
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
In fs/ext4/ioctl.c (ffffffff81588ed1)
Location: fs/ext4/ext4.h:2109
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/crypto.c (ffffffff815dae55)
Location: fs/ext4/ext4.h:2109
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_has_stable_inodes
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
In fs/ext4/ioctl.c (ffffffff815bf452)
Location: fs/ext4/ext4.h:2103
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/crypto.c (ffffffff81612905)
Location: fs/ext4/ext4.h:2103
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_has_stable_inodes
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
In fs/ext4/ioctl.c (ffffffff815f81f8)
Location: fs/ext4/ext4.h:2121
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/crypto.c (ffffffff8164b6b5)
Location: fs/ext4/ext4.h:2121
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_has_stable_inodes
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
