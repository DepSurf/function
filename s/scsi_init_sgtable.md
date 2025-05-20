# Function: <code>scsi_init_sgtable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int scsi_init_sgtable(struct request *req, struct scsi_data_buffer *sdb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff815ae5f0)
Location: drivers/scsi/scsi_lib.c:1080
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
**Symbols:**

```
ffffffff815ae5f0-ffffffff815ae664: scsi_init_sgtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int scsi_init_sgtable(struct request *req, struct scsi_data_buffer *sdb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81606870)
Location: drivers/scsi/scsi_lib.c:994
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
**Symbols:**

```
ffffffff81606870-ffffffff816068d9: scsi_init_sgtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int scsi_init_sgtable(struct request *req, struct scsi_data_buffer *sdb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81635fa0)
Location: drivers/scsi/scsi_lib.c:1003
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
**Symbols:**

```
ffffffff81635fa0-ffffffff81636026: scsi_init_sgtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int scsi_init_sgtable(struct request *req, struct scsi_data_buffer *sdb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8164afe0)
Location: drivers/scsi/scsi_lib.c:999
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
**Symbols:**

```
ffffffff8164afe0-ffffffff8164b066: scsi_init_sgtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int scsi_init_sgtable(struct request *req, struct scsi_data_buffer *sdb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816b4330)
Location: drivers/scsi/scsi_lib.c:1028
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
**Symbols:**

```
ffffffff816b4330-ffffffff816b43b6: scsi_init_sgtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int scsi_init_sgtable(struct request *req, struct scsi_data_buffer *sdb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816f0460)
Location: drivers/scsi/scsi_lib.c:1065
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
**Symbols:**

```
ffffffff816f0460-ffffffff816f04e2: scsi_init_sgtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
blk_status_t scsi_init_sgtable(struct request *req, struct scsi_data_buffer *sdb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81713be0)
Location: drivers/scsi/scsi_lib.c:1016
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
**Symbols:**

```
ffffffff81713be0-ffffffff81713c54: scsi_init_sgtable (STB_LOCAL)
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
In drivers/scsi/scsi_lib.c (ffffffff8174e418)
Location: drivers/scsi/scsi_lib.c:985
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
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
In drivers/scsi/scsi_lib.c (ffffffff817725c8)
Location: drivers/scsi/scsi_lib.c:985
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffff800010975b08)
Location: drivers/scsi/scsi_lib.c:985
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
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
In drivers/scsi/scsi_lib.c (c0a4a474)
Location: drivers/scsi/scsi_lib.c:985
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
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
In drivers/scsi/scsi_lib.c (c000000000a2fdac)
Location: drivers/scsi/scsi_lib.c:985
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
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
In drivers/scsi/scsi_lib.c (ffffffe0005de246)
Location: drivers/scsi/scsi_lib.c:985
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
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
In drivers/scsi/scsi_lib.c (ffffffff81726cb8)
Location: drivers/scsi/scsi_lib.c:985
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
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
In drivers/scsi/scsi_lib.c (ffffffff817000e8)
Location: drivers/scsi/scsi_lib.c:985
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
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
In drivers/scsi/scsi_lib.c (ffffffff81765a88)
Location: drivers/scsi/scsi_lib.c:985
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
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
In drivers/scsi/scsi_lib.c (ffffffff81781118)
Location: drivers/scsi/scsi_lib.c:985
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>blk_status_t</code>
</li>
</ul>
</details>
</li>
</ul>
