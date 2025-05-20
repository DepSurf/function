# Function: <code>scsi_release_buffers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void scsi_release_buffers(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff815ad7c0)
Location: drivers/scsi/scsi_lib.c:668
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_prep_fn
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff815ad7c0-ffffffff815ad840: scsi_release_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void scsi_release_buffers(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816056d0)
Location: drivers/scsi/scsi_lib.c:579
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_prep_fn
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
**Symbols:**

```
ffffffff816056d0-ffffffff81605738: scsi_release_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void scsi_release_buffers(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81634bf0)
Location: drivers/scsi/scsi_lib.c:588
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_prep_fn
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
**Symbols:**

```
ffffffff81634bf0-ffffffff81634c58: scsi_release_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void scsi_release_buffers(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81649b90)
Location: drivers/scsi/scsi_lib.c:607
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_prep_fn
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
**Symbols:**

```
ffffffff81649b90-ffffffff81649bfd: scsi_release_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void scsi_release_buffers(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816b2310)
Location: drivers/scsi/scsi_lib.c:632
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_prep_fn
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
**Symbols:**

```
ffffffff816b2310-ffffffff816b237d: scsi_release_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void scsi_release_buffers(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816eef20)
Location: drivers/scsi/scsi_lib.c:645
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_prep_fn
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
**Symbols:**

```
ffffffff816eef20-ffffffff816eef8d: scsi_release_buffers (STB_LOCAL)
```
</details>
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
</ul>
