# Function: <code>scsi_io_completion_action</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81714baf)
Location: drivers/scsi/scsi_lib.c:680
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
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
In drivers/scsi/scsi_lib.c (ffffffff817503b8)
Location: drivers/scsi/scsi_lib.c:673
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
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
In drivers/scsi/scsi_lib.c (ffffffff817745a8)
Location: drivers/scsi/scsi_lib.c:673
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void scsi_io_completion_action(struct scsi_cmnd *cmd, int result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81837520)
Location: drivers/scsi/scsi_lib.c:657
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff81837520-ffffffff818377fe: scsi_io_completion_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void scsi_io_completion_action(struct scsi_cmnd *cmd, int result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81847ea0)
Location: drivers/scsi/scsi_lib.c:677
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff81847ea0-ffffffff818481c3: scsi_io_completion_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void scsi_io_completion_action(struct scsi_cmnd *cmd, int result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8182b080)
Location: drivers/scsi/scsi_lib.c:645
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff8182b080-ffffffff8182b39a: scsi_io_completion_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void scsi_io_completion_action(struct scsi_cmnd *cmd, int result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818b6ba0)
Location: drivers/scsi/scsi_lib.c:645
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff818b6ba0-ffffffff818b7000: scsi_io_completion_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void scsi_io_completion_action(struct scsi_cmnd *cmd, int result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81a022d0)
Location: drivers/scsi/scsi_lib.c:687
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff81a022d0-ffffffff81a0270f: scsi_io_completion_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void scsi_io_completion_action(struct scsi_cmnd *cmd, int result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81b809c0)
Location: drivers/scsi/scsi_lib.c:691
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff81b809c0-ffffffff81b80ed1: scsi_io_completion_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void scsi_io_completion_action(struct scsi_cmnd *cmd, int result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81bd4a60)
Location: drivers/scsi/scsi_lib.c:690
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff81bd4a60-ffffffff81bd4e26: scsi_io_completion_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void scsi_io_completion_action(struct scsi_cmnd *cmd, int result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81c296d0)
Location: drivers/scsi/scsi_lib.c:688
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff81c296d0-ffffffff81c29a8b: scsi_io_completion_action (STB_LOCAL)
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
In drivers/scsi/scsi_lib.c (ffff8000109786b0)
Location: drivers/scsi/scsi_lib.c:673
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
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
In drivers/scsi/scsi_lib.c (c0a4c4d4)
Location: drivers/scsi/scsi_lib.c:673
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
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
In drivers/scsi/scsi_lib.c (c000000000a32c20)
Location: drivers/scsi/scsi_lib.c:673
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
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
In drivers/scsi/scsi_lib.c (ffffffe0005dfef2)
Location: drivers/scsi/scsi_lib.c:673
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
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
In drivers/scsi/scsi_lib.c (ffffffff81728c98)
Location: drivers/scsi/scsi_lib.c:673
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
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
In drivers/scsi/scsi_lib.c (ffffffff817020c8)
Location: drivers/scsi/scsi_lib.c:673
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
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
In drivers/scsi/scsi_lib.c (ffffffff81767a68)
Location: drivers/scsi/scsi_lib.c:673
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
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
In drivers/scsi/scsi_lib.c (ffffffff817831a8)
Location: drivers/scsi/scsi_lib.c:673
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
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
