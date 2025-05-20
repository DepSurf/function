# Function: <code>sg_fill_request_table</code>

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
In drivers/scsi/sg.c (ffffffff81663d96)
Location: drivers/scsi/sg.c:832
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
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
In drivers/scsi/sg.c (ffffffff816cd3e6)
Location: drivers/scsi/sg.c:832
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
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
In drivers/scsi/sg.c (ffffffff81709e51)
Location: drivers/scsi/sg.c:869
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
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
In drivers/scsi/sg.c (ffffffff8172c33f)
Location: drivers/scsi/sg.c:869
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
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
In drivers/scsi/sg.c (ffffffff81767dc2)
Location: drivers/scsi/sg.c:864
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
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
In drivers/scsi/sg.c (ffffffff8178bdb2)
Location: drivers/scsi/sg.c:864
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sg_fill_request_table(Sg_fd *sfp, sg_req_info_t *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8184cd90)
Location: drivers/scsi/sg.c:858
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl_common
```
**Symbols:**

```
ffffffff8184cd90-ffffffff8184ce67: sg_fill_request_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sg_fill_request_table(Sg_fd *sfp, sg_req_info_t *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8185d1b0)
Location: drivers/scsi/sg.c:858
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl_common
```
**Symbols:**

```
ffffffff8185d1b0-ffffffff8185d287: sg_fill_request_table (STB_LOCAL)
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
In drivers/scsi/sg.c (ffffffff81843d6e)
Location: drivers/scsi/sg.c:857
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
In drivers/scsi/sg.c (ffffffff818d0837)
Location: drivers/scsi/sg.c:861
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
In drivers/scsi/sg.c (ffffffff81a1dc65)
Location: drivers/scsi/sg.c:857
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
In drivers/scsi/sg.c (ffffffff81b9ef75)
Location: drivers/scsi/sg.c:857
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
In drivers/scsi/sg.c (ffffffff81bf5435)
Location: drivers/scsi/sg.c:857
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
In drivers/scsi/sg.c (ffffffff81c4ada4)
Location: drivers/scsi/sg.c:857
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffff800010993f9c)
Location: drivers/scsi/sg.c:864
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
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
In drivers/scsi/sg.c (c0a64ac0)
Location: drivers/scsi/sg.c:864
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
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
In drivers/scsi/sg.c (c000000000a55f14)
Location: drivers/scsi/sg.c:864
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
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
In drivers/scsi/sg.c (ffffffe0005f5ea0)
Location: drivers/scsi/sg.c:864
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
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
In drivers/scsi/sg.c (ffffffff817404a2)
Location: drivers/scsi/sg.c:864
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
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
In drivers/scsi/sg.c (ffffffff81722136)
Location: drivers/scsi/sg.c:864
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
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
In drivers/scsi/sg.c (ffffffff81780c32)
Location: drivers/scsi/sg.c:864
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
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
In drivers/scsi/sg.c (ffffffff8179aacd)
Location: drivers/scsi/sg.c:864
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
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
