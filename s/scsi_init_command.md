# Function: <code>scsi_init_command</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void scsi_init_command(struct scsi_device *dev, struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8164cbe0)
Location: drivers/scsi/scsi_lib.c:1152
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prep_fn
```
**Symbols:**

```
ffffffff8164cbe0-ffffffff8164ccba: scsi_init_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void scsi_init_command(struct scsi_device *dev, struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816b5f30)
Location: drivers/scsi/scsi_lib.c:1190
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prep_fn
```
**Symbols:**

```
ffffffff816b5f30-ffffffff816b6069: scsi_init_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void scsi_init_command(struct scsi_device *dev, struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816f21e0)
Location: drivers/scsi/scsi_lib.c:1226
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prep_fn
```
**Symbols:**

```
ffffffff816f21e0-ffffffff816f2319: scsi_init_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void scsi_init_command(struct scsi_device *dev, struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81714ea0)
Location: drivers/scsi/scsi_lib.c:1157
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffffffff81714ea0-ffffffff81714fd9: scsi_init_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void scsi_init_command(struct scsi_device *dev, struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81750670)
Location: drivers/scsi/scsi_lib.c:1122
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffffffff81750670-ffffffff817507ba: scsi_init_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void scsi_init_command(struct scsi_device *dev, struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81774890)
Location: drivers/scsi/scsi_lib.c:1134
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffffffff81774890-ffffffff817749da: scsi_init_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void scsi_init_command(struct scsi_device *dev, struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818379f0)
Location: drivers/scsi/scsi_lib.c:1106
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_lib.c:scsi_mq_prep_fn
```
**Symbols:**

```
ffffffff818379f0-ffffffff81837b5a: scsi_init_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void scsi_init_command(struct scsi_device *dev, struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818483c0)
Location: drivers/scsi/scsi_lib.c:1136
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
```
**Symbols:**

```
ffffffff818483c0-ffffffff8184852a: scsi_init_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void scsi_init_command(struct scsi_device *dev, struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8182b6e0)
Location: drivers/scsi/scsi_lib.c:1108
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
```
**Symbols:**

```
ffffffff8182b6e0-ffffffff8182b852: scsi_init_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void scsi_init_command(struct scsi_device *dev, struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818b72a0)
Location: drivers/scsi/scsi_lib.c:1113
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
```
**Symbols:**

```
ffffffff818b72a0-ffffffff818b743d: scsi_init_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void scsi_init_command(struct scsi_device *dev, struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81a029b0)
Location: drivers/scsi/scsi_lib.c:1153
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
```
**Symbols:**

```
ffffffff81a029b0-ffffffff81a02a53: scsi_init_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void scsi_init_command(struct scsi_device *dev, struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81b81380)
Location: drivers/scsi/scsi_lib.c:1158
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
```
**Symbols:**

```
ffffffff81b81380-ffffffff81b81423: scsi_init_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void scsi_init_command(struct scsi_device *dev, struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81bd5080)
Location: drivers/scsi/scsi_lib.c:1159
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
```
**Symbols:**

```
ffffffff81bd5080-ffffffff81bd5123: scsi_init_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void scsi_init_command(struct scsi_device *dev, struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81c29ce0)
Location: drivers/scsi/scsi_lib.c:1158
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
```
**Symbols:**

```
ffffffff81c29ce0-ffffffff81c29d83: scsi_init_command (STB_GLOBAL)
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
void scsi_init_command(struct scsi_device *dev, struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffff800010978988)
Location: drivers/scsi/scsi_lib.c:1134
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffff800010978988-ffff800010978a94: scsi_init_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void scsi_init_command(struct scsi_device *dev, struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c0a4c84c)
Location: drivers/scsi/scsi_lib.c:1134
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
c0a4c84c-c0a4c940: scsi_init_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void scsi_init_command(struct scsi_device *dev, struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c000000000a33010)
Location: drivers/scsi/scsi_lib.c:1134
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
c000000000a33010-c000000000a33174: scsi_init_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void scsi_init_command(struct scsi_device *dev, struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffe0005e02da)
Location: drivers/scsi/scsi_lib.c:1134
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffffffe0005e02da-ffffffe0005e03d2: scsi_init_command (STB_GLOBAL)
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
void scsi_init_command(struct scsi_device *dev, struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81728f80)
Location: drivers/scsi/scsi_lib.c:1134
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffffffff81728f80-ffffffff817290ca: scsi_init_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void scsi_init_command(struct scsi_device *dev, struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff817023b0)
Location: drivers/scsi/scsi_lib.c:1134
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffffffff817023b0-ffffffff817024fa: scsi_init_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void scsi_init_command(struct scsi_device *dev, struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81767d50)
Location: drivers/scsi/scsi_lib.c:1134
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffffffff81767d50-ffffffff81767e9a: scsi_init_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void scsi_init_command(struct scsi_device *dev, struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81783490)
Location: drivers/scsi/scsi_lib.c:1134
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffffffff81783490-ffffffff817835da: scsi_init_command (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
