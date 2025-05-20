# Function: <code>sdev_format_header</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
size_t sdev_format_header(char *logbuf, size_t logbuf_len, const char *name, int tag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff815b7bc0)
Location: drivers/scsi/scsi_logging.c:78
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_print_result
```
**Symbols:**

```
ffffffff815b7bc0-ffffffff815b7c44: sdev_format_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
size_t sdev_format_header(char *logbuf, size_t logbuf_len, const char *name, int tag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81610450)
Location: drivers/scsi/scsi_logging.c:78
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scmd_printk
```
**Symbols:**

```
ffffffff81610450-ffffffff816104d4: sdev_format_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
size_t sdev_format_header(char *logbuf, size_t logbuf_len, const char *name, int tag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff8163fce0)
Location: drivers/scsi/scsi_logging.c:78
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scmd_printk
```
**Symbols:**

```
ffffffff8163fce0-ffffffff8163fd64: sdev_format_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
size_t sdev_format_header(char *logbuf, size_t logbuf_len, const char *name, int tag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81654730)
Location: drivers/scsi/scsi_logging.c:78
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scmd_printk
```
**Symbols:**

```
ffffffff81654730-ffffffff816547a5: sdev_format_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
size_t sdev_format_header(char *logbuf, size_t logbuf_len, const char *name, int tag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff816bdc80)
Location: drivers/scsi/scsi_logging.c:78
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scmd_printk
```
**Symbols:**

```
ffffffff816bdc80-ffffffff816bdcf5: sdev_format_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
size_t sdev_format_header(char *logbuf, size_t logbuf_len, const char *name, int tag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff816fa260)
Location: drivers/scsi/scsi_logging.c:78
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scmd_printk
```
**Symbols:**

```
ffffffff816fa260-ffffffff816fa2cb: sdev_format_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
size_t sdev_format_header(char *logbuf, size_t logbuf_len, const char *name, int tag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff8171cca0)
Location: drivers/scsi/scsi_logging.c:78
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scmd_printk
```
**Symbols:**

```
ffffffff8171cca0-ffffffff8171cd0b: sdev_format_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
size_t sdev_format_header(char *logbuf, size_t logbuf_len, const char *name, int tag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:77
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scmd_printk
```
**Symbols:**

```
ffffffff81758260-ffffffff817582cc: sdev_format_header (STB_LOCAL)
ffffffff81759070-ffffffff81759083: sdev_format_header.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff8177c6c0)
Location: drivers/scsi/scsi_logging.c:35
Inline: True
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scmd_printk
```
**Symbols:**

```
ffffffff8177c6c0-ffffffff8177c734: sdev_format_header.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t sdev_format_header(char *logbuf, size_t logbuf_len, const char *name, int tag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff8183f6c0)
Location: drivers/scsi/scsi_logging.c:35
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scmd_printk
```
**Symbols:**

```
ffffffff8183f6c0-ffffffff8183f736: sdev_format_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t sdev_format_header(char *logbuf, size_t logbuf_len, const char *name, int tag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff8184fd20)
Location: drivers/scsi/scsi_logging.c:35
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scmd_printk
```
**Symbols:**

```
ffffffff8184fd20-ffffffff8184fd96: sdev_format_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t sdev_format_header(char *logbuf, size_t logbuf_len, const char *name, int tag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81832fa0)
Location: drivers/scsi/scsi_logging.c:35
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scmd_printk
```
**Symbols:**

```
ffffffff81832fa0-ffffffff81833016: sdev_format_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
size_t sdev_format_header(char *logbuf, size_t logbuf_len, const char *name, int tag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff818beff0)
Location: drivers/scsi/scsi_logging.c:36
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scmd_printk
```
**Symbols:**

```
ffffffff818beff0-ffffffff818bf066: sdev_format_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t sdev_format_header(char *logbuf, size_t logbuf_len, const char *name, int tag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81a0b410)
Location: drivers/scsi/scsi_logging.c:38
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scmd_printk
```
**Symbols:**

```
ffffffff81a0b410-ffffffff81a0b49d: sdev_format_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t sdev_format_header(char *logbuf, size_t logbuf_len, const char *name, int tag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81b8ae50)
Location: drivers/scsi/scsi_logging.c:38
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scmd_printk
```
**Symbols:**

```
ffffffff81b8ae50-ffffffff81b8aedd: sdev_format_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t sdev_format_header(char *logbuf, size_t logbuf_len, const char *name, int tag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81bdee60)
Location: drivers/scsi/scsi_logging.c:38
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scmd_printk
```
**Symbols:**

```
ffffffff81bdee60-ffffffff81bdeeed: sdev_format_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t sdev_format_header(char *logbuf, size_t logbuf_len, const char *name, int tag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81c33d50)
Location: drivers/scsi/scsi_logging.c:38
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scmd_printk
```
**Symbols:**

```
ffffffff81c33d50-ffffffff81c33ddd: sdev_format_header (STB_LOCAL)
```
</details>
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
In drivers/scsi/scsi_logging.c (ffff800010982718)
Location: drivers/scsi/scsi_logging.c:35
Inline: True
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scmd_printk
```
**Symbols:**

```
ffff800010982718-ffff8000109827b8: sdev_format_header.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (c0a55138)
Location: drivers/scsi/scsi_logging.c:35
Inline: True
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scmd_printk
```
**Symbols:**

```
c0a55138-c0a551c8: sdev_format_header.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (c000000000a3ee00)
Location: drivers/scsi/scsi_logging.c:35
Inline: True
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scmd_printk
```
**Symbols:**

```
c000000000a3ee00-c000000000a3eec8: sdev_format_header.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffe0005e7fa0)
Location: drivers/scsi/scsi_logging.c:35
Inline: True
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scmd_printk
```
**Symbols:**

```
ffffffe0005e7fa0-ffffffe0005e8028: sdev_format_header.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81730db0)
Location: drivers/scsi/scsi_logging.c:35
Inline: True
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scmd_printk
```
**Symbols:**

```
ffffffff81730db0-ffffffff81730e24: sdev_format_header.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff8170a1d0)
Location: drivers/scsi/scsi_logging.c:35
Inline: True
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scmd_printk
```
**Symbols:**

```
ffffffff8170a1d0-ffffffff8170a244: sdev_format_header.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff8176fb80)
Location: drivers/scsi/scsi_logging.c:35
Inline: True
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scmd_printk
```
**Symbols:**

```
ffffffff8176fb80-ffffffff8176fbf4: sdev_format_header.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff8178b320)
Location: drivers/scsi/scsi_logging.c:35
Inline: True
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scmd_printk
```
**Symbols:**

```
ffffffff8178b320-ffffffff8178b394: sdev_format_header.constprop.0 (STB_LOCAL)
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
