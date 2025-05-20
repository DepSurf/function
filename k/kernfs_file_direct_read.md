# Function: <code>kernfs_file_direct_read</code>

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
In fs/kernfs/file.c (ffffffff8128b8d7)
Location: fs/kernfs/file.c:184
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_read
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
In fs/kernfs/file.c (ffffffff812b9327)
Location: fs/kernfs/file.c:184
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_read
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
In fs/kernfs/file.c (ffffffff812cea74)
Location: fs/kernfs/file.c:184
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_read
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
In fs/kernfs/file.c (ffffffff812dba74)
Location: fs/kernfs/file.c:184
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_read
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
In fs/kernfs/file.c (ffffffff81300394)
Location: fs/kernfs/file.c:184
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_read
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
In fs/kernfs/file.c (ffffffff8132e8ca)
Location: fs/kernfs/file.c:184
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_read
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
In fs/kernfs/file.c (ffffffff81345c7a)
Location: fs/kernfs/file.c:184
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_read
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
In fs/kernfs/file.c (ffffffff8136dcda)
Location: fs/kernfs/file.c:183
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_read
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
In fs/kernfs/file.c (ffffffff813858fa)
Location: fs/kernfs/file.c:183
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t kernfs_file_direct_read(struct kernfs_open_file *of, char *user_buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff813d0270)
Location: fs/kernfs/file.c:183
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_read
```
**Symbols:**

```
ffffffff813d0270-ffffffff813d03da: kernfs_file_direct_read (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
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
In fs/kernfs/file.c (ffff800010455768)
Location: fs/kernfs/file.c:183
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_read
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
In fs/kernfs/file.c (c061736c)
Location: fs/kernfs/file.c:183
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_read
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
In fs/kernfs/file.c (c00000000056e848)
Location: fs/kernfs/file.c:183
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_read
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
In fs/kernfs/file.c (ffffffe0002e742e)
Location: fs/kernfs/file.c:183
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_read
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
In fs/kernfs/file.c (ffffffff8137deda)
Location: fs/kernfs/file.c:183
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_read
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
In fs/kernfs/file.c (ffffffff8136e98a)
Location: fs/kernfs/file.c:183
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_read
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
In fs/kernfs/file.c (ffffffff8137b9aa)
Location: fs/kernfs/file.c:183
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_read
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
In fs/kernfs/file.c (ffffffff8138f9ea)
Location: fs/kernfs/file.c:183
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_read
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
