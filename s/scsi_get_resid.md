# Function: <code>scsi_get_resid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (0)
Location: include/scsi/scsi_cmnd.h:191
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/scsi/scsi_cmnd.h:191
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff815ba7d7)
Location: include/scsi/scsi_cmnd.h:191
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_completed_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (0)
Location: include/scsi/scsi_cmnd.h:191
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/scsi/scsi_cmnd.h:191
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81612f17)
Location: include/scsi/scsi_cmnd.h:191
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_completed_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (0)
Location: include/scsi/scsi_cmnd.h:191
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/scsi/scsi_cmnd.h:191
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81643147)
Location: include/scsi/scsi_cmnd.h:191
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_completed_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (0)
Location: include/scsi/scsi_cmnd.h:196
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/scsi/scsi_cmnd.h:196
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/scsi/scsi_cmnd.h:196
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (0)
Location: include/scsi/scsi_cmnd.h:202
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/scsi/scsi_cmnd.h:202
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/scsi/scsi_cmnd.h:202
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816e93d0)
Location: include/scsi/scsi_cmnd.h:205
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_lib.c (ffffffff816f1c21)
Location: include/scsi/scsi_cmnd.h:205
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/sd.c (ffffffff81700645)
Location: include/scsi/scsi_cmnd.h:205
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8170ced0)
Location: include/scsi/scsi_cmnd.h:208
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_lib.c (ffffffff81714946)
Location: include/scsi/scsi_cmnd.h:208
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
```
In drivers/scsi/sd.c (ffffffff81723412)
Location: include/scsi/scsi_cmnd.h:208
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff817485b0)
Location: include/scsi/scsi_cmnd.h:197
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (ffffffff8175eafb)
Location: include/scsi/scsi_cmnd.h:197
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8176c700)
Location: include/scsi/scsi_cmnd.h:198
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (ffffffff81782b60)
Location: include/scsi/scsi_cmnd.h:198
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8182ea03)
Location: include/scsi/scsi_cmnd.h:198
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (ffffffff818461a3)
Location: include/scsi/scsi_cmnd.h:198
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8183fa40)
Location: include/scsi/scsi_cmnd.h:199
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (ffffffff81856121)
Location: include/scsi/scsi_cmnd.h:199
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81822ca0)
Location: include/scsi/scsi_cmnd.h:201
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (ffffffff81838ecd)
Location: include/scsi/scsi_cmnd.h:201
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff818ad5c0)
Location: include/scsi/scsi_cmnd.h:205
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (ffffffff818c552d)
Location: include/scsi/scsi_cmnd.h:205
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff819f82cd)
Location: include/scsi/scsi_cmnd.h:195
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (ffffffff81a11ede)
Location: include/scsi/scsi_cmnd.h:195
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81b75c9d)
Location: include/scsi/scsi_cmnd.h:196
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (ffffffff81b921ce)
Location: include/scsi/scsi_cmnd.h:196
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81bc95bd)
Location: include/scsi/scsi_cmnd.h:201
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (ffffffff81be8769)
Location: include/scsi/scsi_cmnd.h:201
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81c1e1ad)
Location: include/scsi/scsi_cmnd.h:201
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (ffffffff81c3dcc7)
Location: include/scsi/scsi_cmnd.h:201
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffff80001096ecfc)
Location: include/scsi/scsi_cmnd.h:198
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (ffff80001098979c)
Location: include/scsi/scsi_cmnd.h:198
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (c0a44174)
Location: include/scsi/scsi_cmnd.h:198
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (c0a5b8f4)
Location: include/scsi/scsi_cmnd.h:198
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (c000000000a28110)
Location: include/scsi/scsi_cmnd.h:198
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (c000000000a499c4)
Location: include/scsi/scsi_cmnd.h:198
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffe0005d8eac)
Location: include/scsi/scsi_cmnd.h:198
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (ffffffe0005ed9e2)
Location: include/scsi/scsi_cmnd.h:198
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81720df0)
Location: include/scsi/scsi_cmnd.h:198
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (ffffffff81737250)
Location: include/scsi/scsi_cmnd.h:198
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816fa220)
Location: include/scsi/scsi_cmnd.h:198
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (ffffffff81718ef0)
Location: include/scsi/scsi_cmnd.h:198
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8175fbc0)
Location: include/scsi/scsi_cmnd.h:198
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (ffffffff817779e0)
Location: include/scsi/scsi_cmnd.h:198
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8177b220)
Location: include/scsi/scsi_cmnd.h:198
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (ffffffff81791800)
Location: include/scsi/scsi_cmnd.h:198
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
```
</details>
</li>
</ul>

## Differences
