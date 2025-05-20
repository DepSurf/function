# Function: <code>scsi_print_command</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void scsi_print_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff815b81c0)
Location: drivers/scsi/scsi_logging.c:220
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff815b81c0-ffffffff815b84bf: scsi_print_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void scsi_print_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81610a30)
Location: drivers/scsi/scsi_logging.c:220
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff81610a30-ffffffff81610d35: scsi_print_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void scsi_print_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff816402c0)
Location: drivers/scsi/scsi_logging.c:220
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff816402c0-ffffffff816405c5: scsi_print_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void scsi_print_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81654ce0)
Location: drivers/scsi/scsi_logging.c:220
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff81654ce0-ffffffff81654fa5: scsi_print_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void scsi_print_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff816be230)
Location: drivers/scsi/scsi_logging.c:220
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff816be230-ffffffff816be4f5: scsi_print_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void scsi_print_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff816fa800)
Location: drivers/scsi/scsi_logging.c:220
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff816fa800-ffffffff816faac5: scsi_print_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void scsi_print_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff8171d240)
Location: drivers/scsi/scsi_logging.c:220
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff8171d240-ffffffff8171d4fb: scsi_print_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void scsi_print_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:219
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff817590e6-ffffffff8175911f: scsi_print_command.cold (STB_LOCAL)
ffffffff817587e0-ffffffff81758aa8: scsi_print_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void scsi_print_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff8177ccbc)
Location: drivers/scsi/scsi_logging.c:177
Inline: True
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffffffff8177d194-ffffffff8177d20e: scsi_print_command.cold (STB_LOCAL)
ffffffff8177cc90-ffffffff8177ced7: scsi_print_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void scsi_print_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:177
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffffffff818406ad-ffffffff81840729: scsi_print_command.cold (STB_LOCAL)
ffffffff818403e0-ffffffff81840638: scsi_print_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void scsi_print_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:177
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffffffff81c16c93-ffffffff81c16cfd: scsi_print_command.cold (STB_LOCAL)
ffffffff81850a40-ffffffff81850c6f: scsi_print_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void scsi_print_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:177
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffffffff81c08ad9-ffffffff81c08b43: scsi_print_command.cold (STB_LOCAL)
ffffffff81833ad0-ffffffff81833cfa: scsi_print_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void scsi_print_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:178
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffffffff81d0cbbe-ffffffff81d0cc25: scsi_print_command.cold (STB_LOCAL)
ffffffff818bfae0-ffffffff818bfcf4: scsi_print_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void scsi_print_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81a0c070)
Location: drivers/scsi/scsi_logging.c:180
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffffffff81a0c070-ffffffff81a0c33d: scsi_print_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void scsi_print_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81b8b700)
Location: drivers/scsi/scsi_logging.c:180
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffffffff81b8b700-ffffffff81b8b9e1: scsi_print_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void scsi_print_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81bdf700)
Location: drivers/scsi/scsi_logging.c:180
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffffffff81bdf700-ffffffff81bdf9e1: scsi_print_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void scsi_print_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81c34680)
Location: drivers/scsi/scsi_logging.c:180
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffffffff81c34680-ffffffff81c3498a: scsi_print_command (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void scsi_print_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffff800010982ef8)
Location: drivers/scsi/scsi_logging.c:177
Inline: True
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffff800010982ef8-ffff800010983190: scsi_print_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void scsi_print_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (c0a55888)
Location: drivers/scsi/scsi_logging.c:177
Inline: True
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
c0a55888-c0a55b40: scsi_print_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void scsi_print_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (c000000000a3f750)
Location: drivers/scsi/scsi_logging.c:177
Inline: True
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
c000000000a3f750-c000000000a3fa90: scsi_print_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void scsi_print_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffe0005e866a)
Location: drivers/scsi/scsi_logging.c:177
Inline: True
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffffffe0005e866a-ffffffe0005e88b6: scsi_print_command (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void scsi_print_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff817313ac)
Location: drivers/scsi/scsi_logging.c:177
Inline: True
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffffffff81731884-ffffffff817318fe: scsi_print_command.cold (STB_LOCAL)
ffffffff81731380-ffffffff817315c7: scsi_print_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void scsi_print_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff8170a7cc)
Location: drivers/scsi/scsi_logging.c:177
Inline: True
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffffffff8170aca4-ffffffff8170ad1e: scsi_print_command.cold (STB_LOCAL)
ffffffff8170a7a0-ffffffff8170a9e7: scsi_print_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void scsi_print_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff8177017c)
Location: drivers/scsi/scsi_logging.c:177
Inline: True
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffffffff81770654-ffffffff817706ce: scsi_print_command.cold (STB_LOCAL)
ffffffff81770150-ffffffff81770397: scsi_print_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void scsi_print_command(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff8178b91c)
Location: drivers/scsi/scsi_logging.c:177
Inline: True
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi.c:scsi_log_send
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffffffff8178bdf4-ffffffff8178be6e: scsi_print_command.cold (STB_LOCAL)
ffffffff8178b8f0-ffffffff8178bb37: scsi_print_command (STB_GLOBAL)
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
