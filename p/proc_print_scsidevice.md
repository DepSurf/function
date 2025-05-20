# Function: <code>proc_print_scsidevice</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_proc.c (ffffffff815b6e22)
Location: drivers/scsi/scsi_proc.c:177
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_proc.c (ffffffff8160f552)
Location: drivers/scsi/scsi_proc.c:177
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_proc.c (ffffffff8163edef)
Location: drivers/scsi/scsi_proc.c:177
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_proc.c (ffffffff8165386f)
Location: drivers/scsi/scsi_proc.c:177
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_show
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
In drivers/scsi/scsi_proc.c (ffffffff816bcd2f)
Location: drivers/scsi/scsi_proc.c:178
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_show
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
In drivers/scsi/scsi_proc.c (ffffffff816f934f)
Location: drivers/scsi/scsi_proc.c:178
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_show
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
In drivers/scsi/scsi_proc.c (ffffffff8171bb4f)
Location: drivers/scsi/scsi_proc.c:178
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_show
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
In drivers/scsi/scsi_proc.c (ffffffff8175717f)
Location: drivers/scsi/scsi_proc.c:178
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_show
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
In drivers/scsi/scsi_proc.c (ffffffff8177b4df)
Location: drivers/scsi/scsi_proc.c:178
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int proc_print_scsidevice(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_proc.c (ffffffff8183e810)
Location: drivers/scsi/scsi_proc.c:178
Inline: False
Direct callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_show
```
**Symbols:**

```
ffffffff8183e810-ffffffff8183e993: proc_print_scsidevice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int proc_print_scsidevice(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_proc.c (ffffffff8184eeb0)
Location: drivers/scsi/scsi_proc.c:178
Inline: False
Direct callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_show
```
**Symbols:**

```
ffffffff8184eeb0-ffffffff8184f033: proc_print_scsidevice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int proc_print_scsidevice(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_proc.c (ffffffff81832350)
Location: drivers/scsi/scsi_proc.c:178
Inline: False
Direct callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_show
```
**Symbols:**

```
ffffffff81832350-ffffffff818324d3: proc_print_scsidevice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int proc_print_scsidevice(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_proc.c (ffffffff818be470)
Location: drivers/scsi/scsi_proc.c:178
Inline: False
Direct callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_show
```
**Symbols:**

```
ffffffff818be470-ffffffff818be5f3: proc_print_scsidevice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int proc_print_scsidevice(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_proc.c (ffffffff81a0a790)
Location: drivers/scsi/scsi_proc.c:178
Inline: False
Direct callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
```
**Symbols:**

```
ffffffff81a0a790-ffffffff81a0a949: proc_print_scsidevice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int proc_print_scsidevice(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_proc.c (ffffffff81b89ee0)
Location: drivers/scsi/scsi_proc.c:273
Inline: False
Direct callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
```
**Symbols:**

```
ffffffff81b89ee0-ffffffff81b8a099: proc_print_scsidevice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int proc_print_scsidevice(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_proc.c (ffffffff81bdde70)
Location: drivers/scsi/scsi_proc.c:273
Inline: False
Direct callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
```
**Symbols:**

```
ffffffff81bdde70-ffffffff81bde029: proc_print_scsidevice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int proc_print_scsidevice(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_proc.c (ffffffff81c32c30)
Location: drivers/scsi/scsi_proc.c:273
Inline: False
Direct callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
```
**Symbols:**

```
ffffffff81c32c30-ffffffff81c32de9: proc_print_scsidevice (STB_LOCAL)
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
In drivers/scsi/scsi_proc.c (ffff8000109811ac)
Location: drivers/scsi/scsi_proc.c:178
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_show
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
In drivers/scsi/scsi_proc.c (c0a53c1c)
Location: drivers/scsi/scsi_proc.c:178
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_show
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
In drivers/scsi/scsi_proc.c (c000000000a3d0c8)
Location: drivers/scsi/scsi_proc.c:178
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_show
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
In drivers/scsi/scsi_proc.c (ffffffe0005e6c3c)
Location: drivers/scsi/scsi_proc.c:178
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_show
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
In drivers/scsi/scsi_proc.c (ffffffff8172fbcf)
Location: drivers/scsi/scsi_proc.c:178
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_show
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
In drivers/scsi/scsi_proc.c (ffffffff81708fef)
Location: drivers/scsi/scsi_proc.c:178
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_show
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
In drivers/scsi/scsi_proc.c (ffffffff8176e99f)
Location: drivers/scsi/scsi_proc.c:178
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_show
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
In drivers/scsi/scsi_proc.c (ffffffff8178a13f)
Location: drivers/scsi/scsi_proc.c:178
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_show
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
