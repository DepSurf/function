# Function: <code>put_compat_request_table</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (0)
Location: drivers/scsi/sg.c:902
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int put_compat_request_table(struct compat_sg_req_info *o, struct sg_req_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8185d2b0)
Location: drivers/scsi/sg.c:902
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl_common
```
**Symbols:**

```
ffffffff8185d2b0-ffffffff8185d33e: put_compat_request_table (STB_LOCAL)
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
In drivers/scsi/sg.c (ffffffff8184408f)
Location: drivers/scsi/sg.c:901
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
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
In drivers/scsi/sg.c (ffffffff818d0b58)
Location: drivers/scsi/sg.c:905
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
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
In drivers/scsi/sg.c (ffffffff81a1dd36)
Location: drivers/scsi/sg.c:901
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
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
In drivers/scsi/sg.c (ffffffff81b9f046)
Location: drivers/scsi/sg.c:901
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
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
In drivers/scsi/sg.c (ffffffff81bf5515)
Location: drivers/scsi/sg.c:901
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
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
In drivers/scsi/sg.c (ffffffff81c4ae84)
Location: drivers/scsi/sg.c:901
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
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
</ul>
