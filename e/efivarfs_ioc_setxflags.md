# Function: <code>efivarfs_ioc_setxflags</code>

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
In fs/efivarfs/file.c (ffffffff813214ef)
Location: fs/efivarfs/file.c:124
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
In fs/efivarfs/file.c (ffffffff813568bf)
Location: fs/efivarfs/file.c:124
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
In fs/efivarfs/file.c (ffffffff8136cd0f)
Location: fs/efivarfs/file.c:124
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
In fs/efivarfs/file.c (ffffffff8138124f)
Location: fs/efivarfs/file.c:124
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
In fs/efivarfs/file.c (ffffffff813a625f)
Location: fs/efivarfs/file.c:124
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
In fs/efivarfs/file.c (ffffffff813d5570)
Location: fs/efivarfs/file.c:130
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
In fs/efivarfs/file.c (ffffffff813efbc0)
Location: fs/efivarfs/file.c:130
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
In fs/efivarfs/file.c (ffffffff8141be9e)
Location: fs/efivarfs/file.c:133
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
In fs/efivarfs/file.c (ffffffff81435cee)
Location: fs/efivarfs/file.c:133
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int efivarfs_ioc_setxflags(struct file *file, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/file.c (ffffffff814856f0)
Location: fs/efivarfs/file.c:132
Inline: False
Direct callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
```
**Symbols:**

```
ffffffff814856f0-ffffffff81485817: efivarfs_ioc_setxflags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int efivarfs_ioc_setxflags(struct file *file, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/file.c (ffffffff814a2d00)
Location: fs/efivarfs/file.c:132
Inline: False
Direct callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
```
**Symbols:**

```
ffffffff814a2d00-ffffffff814a2e27: efivarfs_ioc_setxflags (STB_LOCAL)
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/efivarfs/file.c (ffff80001051bfbc)
Location: fs/efivarfs/file.c:133
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
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
In fs/efivarfs/file.c (c06d850c)
Location: fs/efivarfs/file.c:133
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
In fs/efivarfs/file.c (ffffffff8142e2ce)
Location: fs/efivarfs/file.c:133
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
In fs/efivarfs/file.c (ffffffff8141ed4e)
Location: fs/efivarfs/file.c:133
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
In fs/efivarfs/file.c (ffffffff8142a46e)
Location: fs/efivarfs/file.c:133
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
In fs/efivarfs/file.c (ffffffff8144132e)
Location: fs/efivarfs/file.c:133
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
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
