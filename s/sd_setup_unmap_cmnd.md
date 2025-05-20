# Function: <code>sd_setup_unmap_cmnd</code>

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
In drivers/scsi/sd.c (ffffffff8165a84b)
Location: drivers/scsi/sd.c:737
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
In drivers/scsi/sd.c (ffffffff816c3a11)
Location: drivers/scsi/sd.c:753
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
In drivers/scsi/sd.c (ffffffff816ffb7b)
Location: drivers/scsi/sd.c:753
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
In drivers/scsi/sd.c (ffffffff81723159)
Location: drivers/scsi/sd.c:760
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
In drivers/scsi/sd.c (ffffffff817605ab)
Location: drivers/scsi/sd.c:824
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
In drivers/scsi/sd.c (ffffffff8178453c)
Location: drivers/scsi/sd.c:824
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
blk_status_t sd_setup_unmap_cmnd(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81842900)
Location: drivers/scsi/sd.c:838
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff81842900-ffffffff81842a2d: sd_setup_unmap_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
blk_status_t sd_setup_unmap_cmnd(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81853340)
Location: drivers/scsi/sd.c:871
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff81853340-ffffffff8185347a: sd_setup_unmap_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
blk_status_t sd_setup_unmap_cmnd(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81836d60)
Location: drivers/scsi/sd.c:871
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff81836d60-ffffffff81836e9a: sd_setup_unmap_cmnd (STB_LOCAL)
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
In drivers/scsi/sd.c (ffffffff818c50f6)
Location: drivers/scsi/sd.c:871
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
In drivers/scsi/sd.c (ffffffff81a11bd5)
Location: drivers/scsi/sd.c:834
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
In drivers/scsi/sd.c (ffffffff81b91ea0)
Location: drivers/scsi/sd.c:834
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
In drivers/scsi/sd.c (ffffffff81be83c6)
Location: drivers/scsi/sd.c:849
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
In drivers/scsi/sd.c (ffffffff81c3d933)
Location: drivers/scsi/sd.c:889
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
In drivers/scsi/sd.c (ffff80001098ad00)
Location: drivers/scsi/sd.c:824
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
In drivers/scsi/sd.c (c0a5cf9c)
Location: drivers/scsi/sd.c:824
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
In drivers/scsi/sd.c (c000000000a4b720)
Location: drivers/scsi/sd.c:824
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
In drivers/scsi/sd.c (ffffffe0005ef0ce)
Location: drivers/scsi/sd.c:824
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
In drivers/scsi/sd.c (ffffffff81738c2c)
Location: drivers/scsi/sd.c:824
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
In drivers/scsi/sd.c (ffffffff8171a8cc)
Location: drivers/scsi/sd.c:824
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
In drivers/scsi/sd.c (ffffffff817793bc)
Location: drivers/scsi/sd.c:824
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
In drivers/scsi/sd.c (ffffffff817931dc)
Location: drivers/scsi/sd.c:824
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
