# Function: <code>scsi_done_internal</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void scsi_done_internal(struct scsi_cmnd *cmd, bool complete_directly);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81a01f90)
Location: drivers/scsi/scsi_lib.c:1608
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_done_direct
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
```
**Symbols:**

```
ffffffff81a01f90-ffffffff81a02053: scsi_done_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void scsi_done_internal(struct scsi_cmnd *cmd, bool complete_directly);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81b80650)
Location: drivers/scsi/scsi_lib.c:1608
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_done_direct
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
```
**Symbols:**

```
ffffffff81b80650-ffffffff81b8071a: scsi_done_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void scsi_done_internal(struct scsi_cmnd *cmd, bool complete_directly);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81bd46d0)
Location: drivers/scsi/scsi_lib.c:1613
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_done_direct
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
```
**Symbols:**

```
ffffffff81bd46d0-ffffffff81bd479a: scsi_done_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void scsi_done_internal(struct scsi_cmnd *cmd, bool complete_directly);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81c29340)
Location: drivers/scsi/scsi_lib.c:1610
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_done_direct
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
```
**Symbols:**

```
ffffffff81c29340-ffffffff81c29407: scsi_done_internal (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
