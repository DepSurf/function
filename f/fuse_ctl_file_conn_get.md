# Function: <code>fuse_ctl_file_conn_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct fuse_conn *fuse_ctl_file_conn_get(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/control.c (ffffffff8131c8a0)
Location: fs/fuse/control.c:22
Inline: False
Direct callers:
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
```
**Symbols:**

```
ffffffff8131c8a0-ffffffff8131c8e6: fuse_ctl_file_conn_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct fuse_conn *fuse_ctl_file_conn_get(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/control.c (ffffffff813513a0)
Location: fs/fuse/control.c:22
Inline: False
Direct callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff813513a0-ffffffff813513e6: fuse_ctl_file_conn_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct fuse_conn *fuse_ctl_file_conn_get(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/control.c (ffffffff81366d40)
Location: fs/fuse/control.c:22
Inline: False
Direct callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff81366d40-ffffffff81366d86: fuse_ctl_file_conn_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct fuse_conn *fuse_ctl_file_conn_get(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/control.c (ffffffff8137b440)
Location: fs/fuse/control.c:22
Inline: False
Direct callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff8137b440-ffffffff8137b486: fuse_ctl_file_conn_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct fuse_conn *fuse_ctl_file_conn_get(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/control.c (ffffffff813a02e0)
Location: fs/fuse/control.c:22
Inline: False
Direct callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff813a02e0-ffffffff813a0326: fuse_ctl_file_conn_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct fuse_conn *fuse_ctl_file_conn_get(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/control.c (ffffffff813cf6a0)
Location: fs/fuse/control.c:22
Inline: False
Direct callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff813cf6a0-ffffffff813cf6e6: fuse_ctl_file_conn_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct fuse_conn *fuse_ctl_file_conn_get(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/control.c (ffffffff813e8b30)
Location: fs/fuse/control.c:22
Inline: False
Direct callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff813e8b30-ffffffff813e8b76: fuse_ctl_file_conn_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fuse_conn *fuse_ctl_file_conn_get(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/control.c (ffffffff81414c60)
Location: fs/fuse/control.c:23
Inline: False
Direct callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff81414c60-ffffffff81414ca9: fuse_ctl_file_conn_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fuse_conn *fuse_ctl_file_conn_get(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/control.c (ffffffff8142ea90)
Location: fs/fuse/control.c:23
Inline: False
Direct callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff8142ea90-ffffffff8142ead9: fuse_ctl_file_conn_get (STB_LOCAL)
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
In fs/fuse/control.c (ffffffff8147edf1)
Location: fs/fuse/control.c:23
Inline: True
Inline callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
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
In fs/fuse/control.c (ffffffff8149a451)
Location: fs/fuse/control.c:23
Inline: True
Inline callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
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
In fs/fuse/control.c (ffffffff8149f521)
Location: fs/fuse/control.c:23
Inline: True
Inline callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
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
In fs/fuse/control.c (ffffffff814f7521)
Location: fs/fuse/control.c:23
Inline: True
Inline callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
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
In fs/fuse/control.c (ffffffff81587627)
Location: fs/fuse/control.c:23
Inline: True
Inline callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
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
In fs/fuse/control.c (ffffffff8162d977)
Location: fs/fuse/control.c:23
Inline: True
Inline callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
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
In fs/fuse/control.c (ffffffff81665bb7)
Location: fs/fuse/control.c:23
Inline: True
Inline callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
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
In fs/fuse/control.c (ffffffff8169fe97)
Location: fs/fuse/control.c:23
Inline: True
Inline callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct fuse_conn *fuse_ctl_file_conn_get(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/control.c (ffff8000105132b8)
Location: fs/fuse/control.c:23
Inline: False
Direct callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffff8000105132b8-ffff800010513310: fuse_ctl_file_conn_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fuse_conn *fuse_ctl_file_conn_get(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/control.c (c06ce248)
Location: fs/fuse/control.c:23
Inline: False
Direct callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
c06ce248-c06ce29c: fuse_ctl_file_conn_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fuse_conn *fuse_ctl_file_conn_get(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/control.c (c00000000065b130)
Location: fs/fuse/control.c:23
Inline: False
Direct callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
c00000000065b130-c00000000065b1b4: fuse_ctl_file_conn_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fuse_conn *fuse_ctl_file_conn_get(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/control.c (ffffffe00037d12e)
Location: fs/fuse/control.c:23
Inline: False
Direct callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffe00037d12e-ffffffe00037d184: fuse_ctl_file_conn_get (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct fuse_conn *fuse_ctl_file_conn_get(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/control.c (ffffffff81427070)
Location: fs/fuse/control.c:23
Inline: False
Direct callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff81427070-ffffffff814270b9: fuse_ctl_file_conn_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fuse_conn *fuse_ctl_file_conn_get(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/control.c (ffffffff81417af0)
Location: fs/fuse/control.c:23
Inline: False
Direct callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff81417af0-ffffffff81417b39: fuse_ctl_file_conn_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fuse_conn *fuse_ctl_file_conn_get(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/control.c (ffffffff81423210)
Location: fs/fuse/control.c:23
Inline: False
Direct callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff81423210-ffffffff81423259: fuse_ctl_file_conn_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fuse_conn *fuse_ctl_file_conn_get(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/control.c (ffffffff8143a040)
Location: fs/fuse/control.c:23
Inline: False
Direct callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff8143a040-ffffffff8143a089: fuse_ctl_file_conn_get (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
