# Function: <code>fsverity_read_buffer</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/verity/read_metadata.c (ffffffff813b083a)
Location: fs/verity/read_metadata.c:81
Inline: True
Inline callers:
  - fs/verity/read_metadata.c:fsverity_ioctl_read_metadata
  - fs/verity/read_metadata.c:fsverity_ioctl_read_metadata
Direct callers:
  - fs/verity/read_metadata.c:fsverity_ioctl_read_metadata
```
**Symbols:**

```
ffffffff813b0480-ffffffff813b04e2: fsverity_read_buffer.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/verity/read_metadata.c (ffffffff8140041a)
Location: fs/verity/read_metadata.c:81
Inline: True
Inline callers:
  - fs/verity/read_metadata.c:fsverity_ioctl_read_metadata
  - fs/verity/read_metadata.c:fsverity_ioctl_read_metadata
Direct callers:
  - fs/verity/read_metadata.c:fsverity_ioctl_read_metadata
```
**Symbols:**

```
ffffffff81400070-ffffffff814000d2: fsverity_read_buffer.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fsverity_read_buffer(void *dst, u64 offset, int length, const void *src, size_t src_length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/read_metadata.c (ffffffff81473e80)
Location: fs/verity/read_metadata.c:81
Inline: False
Direct callers:
  - fs/verity/read_metadata.c:fsverity_ioctl_read_metadata
  - fs/verity/read_metadata.c:fsverity_ioctl_read_metadata
```
**Symbols:**

```
ffffffff81473e80-ffffffff81473ef7: fsverity_read_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fsverity_read_buffer(void *dst, u64 offset, int length, const void *src, size_t src_length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/read_metadata.c (ffffffff815060c0)
Location: fs/verity/read_metadata.c:81
Inline: False
Direct callers:
  - fs/verity/read_metadata.c:fsverity_ioctl_read_metadata
  - fs/verity/read_metadata.c:fsverity_ioctl_read_metadata
```
**Symbols:**

```
ffffffff815060c0-ffffffff81506137: fsverity_read_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fsverity_read_buffer(void *dst, u64 offset, int length, const void *src, size_t src_length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/read_metadata.c (ffffffff8153d3f0)
Location: fs/verity/read_metadata.c:81
Inline: False
Direct callers:
  - fs/verity/read_metadata.c:fsverity_ioctl_read_metadata
  - fs/verity/read_metadata.c:fsverity_ioctl_read_metadata
```
**Symbols:**

```
ffffffff8153d3f0-ffffffff8153d467: fsverity_read_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fsverity_read_buffer(void *dst, u64 offset, int length, const void *src, size_t src_length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/read_metadata.c (ffffffff81572850)
Location: fs/verity/read_metadata.c:81
Inline: False
Direct callers:
  - fs/verity/read_metadata.c:fsverity_ioctl_read_metadata
  - fs/verity/read_metadata.c:fsverity_ioctl_read_metadata
```
**Symbols:**

```
ffffffff81572850-ffffffff815728c7: fsverity_read_buffer (STB_LOCAL)
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
<b>Regular</b>
<ul>
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
