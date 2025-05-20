# Function: <code>scsi_put_command</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void scsi_put_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff815a75d0)
Location: drivers/scsi/scsi.c:279
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_prep_fn
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff815a75d0-ffffffff815a768b: scsi_put_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void scsi_put_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff815ff3b0)
Location: drivers/scsi/scsi.c:279
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_lib.c:scsi_prep_fn
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
**Symbols:**

```
ffffffff815ff3b0-ffffffff815ff479: scsi_put_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void scsi_put_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8162ea10)
Location: drivers/scsi/scsi.c:279
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_lib.c:scsi_prep_fn
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
**Symbols:**

```
ffffffff8162ea10-ffffffff8162ead9: scsi_put_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void scsi_put_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81643b90)
Location: drivers/scsi/scsi.c:109
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_lib.c:scsi_prep_fn
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
**Symbols:**

```
ffffffff81643b90-ffffffff81643baf: scsi_put_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void scsi_put_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816acca0)
Location: drivers/scsi/scsi.c:109
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_lib.c:scsi_prep_fn
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
**Symbols:**

```
ffffffff816acca0-ffffffff816accbf: scsi_put_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void scsi_put_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816e91d0)
Location: drivers/scsi/scsi.c:109
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_lib.c:scsi_prep_fn
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
**Symbols:**

```
ffffffff816e91d0-ffffffff816e91ef: scsi_put_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void scsi_put_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8170ccc0)
Location: drivers/scsi/scsi.c:109
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
```
**Symbols:**

```
ffffffff8170ccc0-ffffffff8170ccdf: scsi_put_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void scsi_put_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff817483a0)
Location: drivers/scsi/scsi.c:105
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
```
**Symbols:**

```
ffffffff817483a0-ffffffff817483bf: scsi_put_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void scsi_put_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8176c4f0)
Location: drivers/scsi/scsi.c:105
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
```
**Symbols:**

```
ffffffff8176c4f0-ffffffff8176c50f: scsi_put_command (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void scsi_put_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffff80001096ea98)
Location: drivers/scsi/scsi.c:105
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
```
**Symbols:**

```
ffff80001096ea98-ffff80001096ead0: scsi_put_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void scsi_put_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (c0a43f1c)
Location: drivers/scsi/scsi.c:105
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
```
**Symbols:**

```
c0a43f1c-c0a43f48: scsi_put_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void scsi_put_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (c000000000a27dd0)
Location: drivers/scsi/scsi.c:105
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
```
**Symbols:**

```
c000000000a27dd0-c000000000a27e1c: scsi_put_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void scsi_put_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffe0005d8c7a)
Location: drivers/scsi/scsi.c:105
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
```
**Symbols:**

```
ffffffe0005d8c7a-ffffffe0005d8cac: scsi_put_command (STB_GLOBAL)
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
void scsi_put_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81720be0)
Location: drivers/scsi/scsi.c:105
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
```
**Symbols:**

```
ffffffff81720be0-ffffffff81720bff: scsi_put_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void scsi_put_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816fa010)
Location: drivers/scsi/scsi.c:105
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
```
**Symbols:**

```
ffffffff816fa010-ffffffff816fa02f: scsi_put_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void scsi_put_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8175f9b0)
Location: drivers/scsi/scsi.c:105
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
```
**Symbols:**

```
ffffffff8175f9b0-ffffffff8175f9cf: scsi_put_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void scsi_put_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8177b010)
Location: drivers/scsi/scsi.c:105
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
```
**Symbols:**

```
ffffffff8177b010-ffffffff8177b02f: scsi_put_command (STB_GLOBAL)
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
