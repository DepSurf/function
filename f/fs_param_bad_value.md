# Function: <code>fs_param_bad_value</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int fs_param_bad_value(struct p_log *log, struct fs_parameter *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff813581cd)
Location: fs/fs_parser.c:192
Inline: True
Inline callers:
  - fs/fs_parser.c:fs_param_is_fd
  - fs/fs_parser.c:fs_param_is_blob
  - fs/fs_parser.c:fs_param_is_string
  - fs/fs_parser.c:fs_param_is_u64
  - fs/fs_parser.c:fs_param_is_s32
  - fs/fs_parser.c:fs_param_is_u32
```
**Symbols:**

```
ffffffff81358360-ffffffff8135838e: fs_param_bad_value (STB_GLOBAL)
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
In fs/fs_parser.c (ffffffff81364c1d)
Location: fs/fs_parser.c:192
Inline: True
Inline callers:
  - fs/fs_parser.c:fs_param_is_fd
  - fs/fs_parser.c:fs_param_is_blob
  - fs/fs_parser.c:fs_param_is_string
  - fs/fs_parser.c:fs_param_is_u64
  - fs/fs_parser.c:fs_param_is_s32
  - fs/fs_parser.c:fs_param_is_u32
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
In fs/fs_parser.c (ffffffff8136b66d)
Location: fs/fs_parser.c:192
Inline: True
Inline callers:
  - fs/fs_parser.c:fs_param_is_fd
  - fs/fs_parser.c:fs_param_is_blob
  - fs/fs_parser.c:fs_param_is_string
  - fs/fs_parser.c:fs_param_is_u64
  - fs/fs_parser.c:fs_param_is_s32
  - fs/fs_parser.c:fs_param_is_u32
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
In fs/fs_parser.c (ffffffff813ba33d)
Location: fs/fs_parser.c:191
Inline: True
Inline callers:
  - fs/fs_parser.c:fs_param_is_fd
  - fs/fs_parser.c:fs_param_is_blob
  - fs/fs_parser.c:fs_param_is_string
  - fs/fs_parser.c:fs_param_is_u64
  - fs/fs_parser.c:fs_param_is_s32
  - fs/fs_parser.c:fs_param_is_u32
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
In fs/fs_parser.c (ffffffff8143fddd)
Location: fs/fs_parser.c:191
Inline: True
Inline callers:
  - fs/fs_parser.c:fs_param_is_fd
  - fs/fs_parser.c:fs_param_is_blob
  - fs/fs_parser.c:fs_param_is_string
  - fs/fs_parser.c:fs_param_is_u32
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
In fs/fs_parser.c (ffffffff814ceb6d)
Location: fs/fs_parser.c:192
Inline: True
Inline callers:
  - fs/fs_parser.c:fs_param_is_fd
  - fs/fs_parser.c:fs_param_is_blob
  - fs/fs_parser.c:fs_param_is_string
  - fs/fs_parser.c:fs_param_is_u32
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
In fs/fs_parser.c (ffffffff81504dc3)
Location: fs/fs_parser.c:192
Inline: True
Inline callers:
  - fs/fs_parser.c:fs_param_is_fd
  - fs/fs_parser.c:fs_param_is_blob
  - fs/fs_parser.c:fs_param_is_string
  - fs/fs_parser.c:fs_param_is_u32
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
In fs/fs_parser.c (ffffffff81539a83)
Location: fs/fs_parser.c:192
Inline: True
Inline callers:
  - fs/fs_parser.c:fs_param_is_fd
  - fs/fs_parser.c:fs_param_is_blob
  - fs/fs_parser.c:fs_param_is_string
  - fs/fs_parser.c:fs_param_is_u32
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
</ul>
