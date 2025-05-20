# Function: <code>sd_setup_write_zeroes_cmnd</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8165a490)
Location: drivers/scsi/sd.c:831
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
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
In drivers/scsi/sd.c (ffffffff816c364e)
Location: drivers/scsi/sd.c:847
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
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
In drivers/scsi/sd.c (ffffffff816ff8b8)
Location: drivers/scsi/sd.c:847
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
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
In drivers/scsi/sd.c (ffffffff817230a3)
Location: drivers/scsi/sd.c:859
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
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
In drivers/scsi/sd.c (ffffffff8176031a)
Location: drivers/scsi/sd.c:920
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
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
In drivers/scsi/sd.c (ffffffff8178427a)
Location: drivers/scsi/sd.c:920
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
blk_status_t sd_setup_write_zeroes_cmnd(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff818445d0)
Location: drivers/scsi/sd.c:934
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff818445d0-ffffffff818446a8: sd_setup_write_zeroes_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
blk_status_t sd_setup_write_zeroes_cmnd(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81854900)
Location: drivers/scsi/sd.c:970
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff81854900-ffffffff818549b4: sd_setup_write_zeroes_cmnd (STB_LOCAL)
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
In drivers/scsi/sd.c (ffffffff81838365)
Location: drivers/scsi/sd.c:970
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
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
In drivers/scsi/sd.c (ffffffff818c4d05)
Location: drivers/scsi/sd.c:970
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
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
In drivers/scsi/sd.c (ffffffff81a11a33)
Location: drivers/scsi/sd.c:933
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
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
In drivers/scsi/sd.c (ffffffff81b91cfe)
Location: drivers/scsi/sd.c:933
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
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
In drivers/scsi/sd.c (ffffffff81be815f)
Location: drivers/scsi/sd.c:933
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
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
In drivers/scsi/sd.c (ffffffff81c3d683)
Location: drivers/scsi/sd.c:973
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
```
</details>
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
In drivers/scsi/sd.c (ffff80001098aa38)
Location: drivers/scsi/sd.c:920
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
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
In drivers/scsi/sd.c (c0a5cde0)
Location: drivers/scsi/sd.c:920
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
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
In drivers/scsi/sd.c (c000000000a4b5b0)
Location: drivers/scsi/sd.c:920
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
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
In drivers/scsi/sd.c (ffffffe0005eefa8)
Location: drivers/scsi/sd.c:920
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
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
In drivers/scsi/sd.c (ffffffff8173896a)
Location: drivers/scsi/sd.c:920
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
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
In drivers/scsi/sd.c (ffffffff8171a60a)
Location: drivers/scsi/sd.c:920
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
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
In drivers/scsi/sd.c (ffffffff817790fa)
Location: drivers/scsi/sd.c:920
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
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
In drivers/scsi/sd.c (ffffffff81792f1a)
Location: drivers/scsi/sd.c:920
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
