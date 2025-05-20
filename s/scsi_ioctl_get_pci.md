# Function: <code>scsi_ioctl_get_pci</code>

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
In drivers/scsi/scsi_ioctl.c (ffffffff815a8edf)
Location: drivers/scsi/scsi_ioctl.c:172
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
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
In drivers/scsi/scsi_ioctl.c (ffffffff81600d8f)
Location: drivers/scsi/scsi_ioctl.c:172
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
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
In drivers/scsi/scsi_ioctl.c (ffffffff8163047f)
Location: drivers/scsi/scsi_ioctl.c:172
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
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
In drivers/scsi/scsi_ioctl.c (ffffffff81645201)
Location: drivers/scsi/scsi_ioctl.c:172
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
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
In drivers/scsi/scsi_ioctl.c (ffffffff816ae186)
Location: drivers/scsi/scsi_ioctl.c:174
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
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
In drivers/scsi/scsi_ioctl.c (ffffffff816ea5cf)
Location: drivers/scsi/scsi_ioctl.c:174
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
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
In drivers/scsi/scsi_ioctl.c (ffffffff8170e089)
Location: drivers/scsi/scsi_ioctl.c:174
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
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
In drivers/scsi/scsi_ioctl.c (ffffffff817497b4)
Location: drivers/scsi/scsi_ioctl.c:175
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
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
In drivers/scsi/scsi_ioctl.c (ffffffff8176d8e4)
Location: drivers/scsi/scsi_ioctl.c:175
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int scsi_ioctl_get_pci(struct scsi_device *sdev, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (ffffffff8182fed0)
Location: drivers/scsi/scsi_ioctl.c:175
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl_common
```
**Symbols:**

```
ffffffff8182fed0-ffffffff8182ff4a: scsi_ioctl_get_pci (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int scsi_ioctl_get_pci(struct scsi_device *sdev, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (ffffffff81840b90)
Location: drivers/scsi/scsi_ioctl.c:175
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl_common
```
**Symbols:**

```
ffffffff81840b90-ffffffff81840c0a: scsi_ioctl_get_pci (STB_LOCAL)
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
In drivers/scsi/scsi_ioctl.c (ffffffff81823e13)
Location: drivers/scsi/scsi_ioctl.c:175
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl_common
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
In drivers/scsi/scsi_ioctl.c (ffffffff818af815)
Location: drivers/scsi/scsi_ioctl.c:154
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
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
In drivers/scsi/scsi_ioctl.c (ffffffff819fa7bc)
Location: drivers/scsi/scsi_ioctl.c:154
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
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
In drivers/scsi/scsi_ioctl.c (ffffffff81b7872b)
Location: drivers/scsi/scsi_ioctl.c:154
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
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
In drivers/scsi/scsi_ioctl.c (ffffffff81bcc2bd)
Location: drivers/scsi/scsi_ioctl.c:157
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
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
In drivers/scsi/scsi_ioctl.c (ffffffff81c20eed)
Location: drivers/scsi/scsi_ioctl.c:157
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
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
In drivers/scsi/scsi_ioctl.c (ffff8000109700e8)
Location: drivers/scsi/scsi_ioctl.c:175
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
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
In drivers/scsi/scsi_ioctl.c (c0a45300)
Location: drivers/scsi/scsi_ioctl.c:175
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
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
In drivers/scsi/scsi_ioctl.c (c000000000a2993c)
Location: drivers/scsi/scsi_ioctl.c:175
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
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
In drivers/scsi/scsi_ioctl.c (ffffffe0005d9fa0)
Location: drivers/scsi/scsi_ioctl.c:175
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
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
In drivers/scsi/scsi_ioctl.c (ffffffff81721fd4)
Location: drivers/scsi/scsi_ioctl.c:175
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
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
In drivers/scsi/scsi_ioctl.c (ffffffff816fb404)
Location: drivers/scsi/scsi_ioctl.c:175
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
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
In drivers/scsi/scsi_ioctl.c (ffffffff81760da4)
Location: drivers/scsi/scsi_ioctl.c:175
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
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
In drivers/scsi/scsi_ioctl.c (ffffffff8177c404)
Location: drivers/scsi/scsi_ioctl.c:175
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
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
