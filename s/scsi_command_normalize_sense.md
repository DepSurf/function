# Function: <code>scsi_command_normalize_sense</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool scsi_command_normalize_sense(const struct scsi_cmnd *cmd, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff815aa030)
Location: drivers/scsi/scsi_error.c:2420
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffffffff815aa030-ffffffff815aa04f: scsi_command_normalize_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool scsi_command_normalize_sense(const struct scsi_cmnd *cmd, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81601fc6)
Location: drivers/scsi/scsi_error.c:2423
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffffffff81601fa0-ffffffff81601fbf: scsi_command_normalize_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool scsi_command_normalize_sense(const struct scsi_cmnd *cmd, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816316b6)
Location: drivers/scsi/scsi_error.c:2423
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffffffff81631690-ffffffff816316af: scsi_command_normalize_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool scsi_command_normalize_sense(const struct scsi_cmnd *cmd, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816461c6)
Location: drivers/scsi/scsi_error.c:2355
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffffffff816461a0-ffffffff816461bf: scsi_command_normalize_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool scsi_command_normalize_sense(const struct scsi_cmnd *cmd, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816af1a6)
Location: drivers/scsi/scsi_error.c:2380
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffffffff816af180-ffffffff816af19f: scsi_command_normalize_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool scsi_command_normalize_sense(const struct scsi_cmnd *cmd, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816eb588)
Location: drivers/scsi/scsi_error.c:2404
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffffffff816eb530-ffffffff816eb54f: scsi_command_normalize_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool scsi_command_normalize_sense(const struct scsi_cmnd *cmd, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff8170f028)
Location: drivers/scsi/scsi_error.c:2401
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffffffff8170efd0-ffffffff8170efef: scsi_command_normalize_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool scsi_command_normalize_sense(const struct scsi_cmnd *cmd, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff8174a7b8)
Location: drivers/scsi/scsi_error.c:2420
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffffffff8174a760-ffffffff8174a77f: scsi_command_normalize_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool scsi_command_normalize_sense(const struct scsi_cmnd *cmd, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff8176e928)
Location: drivers/scsi/scsi_error.c:2423
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffffffff8176e8d0-ffffffff8176e8ef: scsi_command_normalize_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool scsi_command_normalize_sense(const struct scsi_cmnd *cmd, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81831186)
Location: drivers/scsi/scsi_error.c:2424
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffffffff81830ec0-ffffffff81830edf: scsi_command_normalize_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool scsi_command_normalize_sense(const struct scsi_cmnd *cmd, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81841dc6)
Location: drivers/scsi/scsi_error.c:2437
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffffffff81841b00-ffffffff81841b1f: scsi_command_normalize_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool scsi_command_normalize_sense(const struct scsi_cmnd *cmd, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81824fc6)
Location: drivers/scsi/scsi_error.c:2460
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffffffff81824b00-ffffffff81824b1f: scsi_command_normalize_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool scsi_command_normalize_sense(const struct scsi_cmnd *cmd, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff818b0846)
Location: drivers/scsi/scsi_error.c:2471
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffffffff818b0380-ffffffff818b039f: scsi_command_normalize_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool scsi_command_normalize_sense(const struct scsi_cmnd *cmd, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff819fb97d)
Location: drivers/scsi/scsi_error.c:2470
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffffffff819fb440-ffffffff819fb469: scsi_command_normalize_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool scsi_command_normalize_sense(const struct scsi_cmnd *cmd, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81b79abd)
Location: drivers/scsi/scsi_error.c:2479
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffffffff81b79170-ffffffff81b79199: scsi_command_normalize_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool scsi_command_normalize_sense(const struct scsi_cmnd *cmd, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81bcd74d)
Location: drivers/scsi/scsi_error.c:2525
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
Direct callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffffffff81bcce00-ffffffff81bcce29: scsi_command_normalize_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool scsi_command_normalize_sense(const struct scsi_cmnd *cmd, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81c2237d)
Location: drivers/scsi/scsi_error.c:2532
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
Direct callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffffffff81c21a30-ffffffff81c21a59: scsi_command_normalize_sense (STB_GLOBAL)
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
bool scsi_command_normalize_sense(const struct scsi_cmnd *cmd, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffff800010971614)
Location: drivers/scsi/scsi_error.c:2423
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffff8000109715a0-ffff8000109715d8: scsi_command_normalize_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool scsi_command_normalize_sense(const struct scsi_cmnd *cmd, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (c0a4645c)
Location: drivers/scsi/scsi_error.c:2423
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
c0a463f4-c0a4641c: scsi_command_normalize_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool scsi_command_normalize_sense(const struct scsi_cmnd *cmd, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (c000000000a2afb8)
Location: drivers/scsi/scsi_error.c:2423
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
c000000000a2af30-c000000000a2af70: scsi_command_normalize_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool scsi_command_normalize_sense(const struct scsi_cmnd *cmd, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffe0005dade4)
Location: drivers/scsi/scsi_error.c:2423
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffffffe0005dad92-ffffffe0005dadca: scsi_command_normalize_sense (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool scsi_command_normalize_sense(const struct scsi_cmnd *cmd, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81723018)
Location: drivers/scsi/scsi_error.c:2423
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffffffff81722fc0-ffffffff81722fdf: scsi_command_normalize_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool scsi_command_normalize_sense(const struct scsi_cmnd *cmd, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816fc448)
Location: drivers/scsi/scsi_error.c:2423
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffffffff816fc3f0-ffffffff816fc40f: scsi_command_normalize_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool scsi_command_normalize_sense(const struct scsi_cmnd *cmd, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81761de8)
Location: drivers/scsi/scsi_error.c:2423
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffffffff81761d90-ffffffff81761daf: scsi_command_normalize_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool scsi_command_normalize_sense(const struct scsi_cmnd *cmd, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff8177d448)
Location: drivers/scsi/scsi_error.c:2423
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/sd.c:sd_done
```
**Symbols:**

```
ffffffff8177d3f0-ffffffff8177d40f: scsi_command_normalize_sense (STB_GLOBAL)
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
