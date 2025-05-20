# Function: <code>efivarfs_ioc_getxflags</code>

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
In fs/efivarfs/file.c (ffffffff813214b0)
Location: fs/efivarfs/file.c:108
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
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
In fs/efivarfs/file.c (ffffffff81356880)
Location: fs/efivarfs/file.c:108
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
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
In fs/efivarfs/file.c (ffffffff8136ccd0)
Location: fs/efivarfs/file.c:108
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
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
In fs/efivarfs/file.c (ffffffff81381210)
Location: fs/efivarfs/file.c:108
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
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
In fs/efivarfs/file.c (ffffffff813a6220)
Location: fs/efivarfs/file.c:108
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
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
In fs/efivarfs/file.c (ffffffff813d5510)
Location: fs/efivarfs/file.c:114
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
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
In fs/efivarfs/file.c (ffffffff813efb60)
Location: fs/efivarfs/file.c:114
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
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
In fs/efivarfs/file.c (ffffffff8141be42)
Location: fs/efivarfs/file.c:122
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
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
In fs/efivarfs/file.c (ffffffff81435c92)
Location: fs/efivarfs/file.c:122
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
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
In fs/efivarfs/file.c (ffffffff81485af6)
Location: fs/efivarfs/file.c:121
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
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
In fs/efivarfs/file.c (ffffffff814a3106)
Location: fs/efivarfs/file.c:121
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/efivarfs/file.c (ffff80001051bd88)
Location: fs/efivarfs/file.c:122
Inline: True
Direct callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
```
**Symbols:**

```
ffff80001051bd88-ffff80001051bf30: efivarfs_ioc_getxflags.isra.0 (STB_LOCAL)
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
In fs/efivarfs/file.c (c06d84a8)
Location: fs/efivarfs/file.c:122
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
```
</details>
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/efivarfs/file.c (ffffffff8142e272)
Location: fs/efivarfs/file.c:122
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
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
In fs/efivarfs/file.c (ffffffff8141ecf2)
Location: fs/efivarfs/file.c:122
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
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
In fs/efivarfs/file.c (ffffffff8142a412)
Location: fs/efivarfs/file.c:122
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
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
In fs/efivarfs/file.c (ffffffff814412d2)
Location: fs/efivarfs/file.c:122
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
```
</details>
</li>
</ul>

## Differences
