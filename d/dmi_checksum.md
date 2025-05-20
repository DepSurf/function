# Function: <code>dmi_checksum</code>

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
In drivers/firmware/dmi_scan.c (ffffffff81fb571c)
Location: drivers/firmware/dmi_scan.c:157
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:dmi_present
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
In drivers/firmware/dmi_scan.c (ffffffff81fe28ce)
Location: drivers/firmware/dmi_scan.c:157
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:dmi_present
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
In drivers/firmware/dmi_scan.c (ffffffff8202069d)
Location: drivers/firmware/dmi_scan.c:157
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:dmi_present
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
In drivers/firmware/dmi_scan.c (ffffffff821035df)
Location: drivers/firmware/dmi_scan.c:157
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:dmi_present
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
In drivers/firmware/dmi_scan.c (ffffffff8270ccc0)
Location: drivers/firmware/dmi_scan.c:157
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:dmi_present
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
In drivers/firmware/dmi_scan.c (ffffffff82736eaf)
Location: drivers/firmware/dmi_scan.c:149
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:dmi_present
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
In drivers/firmware/dmi_scan.c (ffffffff828f0ddb)
Location: drivers/firmware/dmi_scan.c:149
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:dmi_present
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
In drivers/firmware/dmi_scan.c (ffffffff8290c422)
Location: drivers/firmware/dmi_scan.c:150
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:dmi_present
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
In drivers/firmware/dmi_scan.c (ffffffff82915df1)
Location: drivers/firmware/dmi_scan.c:150
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:dmi_present
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dmi_checksum(const u8 *buf, u8 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff82d2760c)
Location: drivers/firmware/dmi_scan.c:155
Inline: False
Direct callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:dmi_present
```
**Symbols:**

```
ffffffff82d2760c-ffffffff82d27632: dmi_checksum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dmi_checksum(const u8 *buf, u8 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff83015d24)
Location: drivers/firmware/dmi_scan.c:155
Inline: False
Direct callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:dmi_present
```
**Symbols:**

```
ffffffff83015d24-ffffffff83015d4a: dmi_checksum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dmi_checksum(const u8 *buf, u8 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff83220d46)
Location: drivers/firmware/dmi_scan.c:155
Inline: False
Direct callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:dmi_present
```
**Symbols:**

```
ffffffff83220d46-ffffffff83220d6c: dmi_checksum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dmi_checksum(const u8 *buf, u8 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff8330a72a)
Location: drivers/firmware/dmi_scan.c:155
Inline: False
Direct callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:dmi_present
```
**Symbols:**

```
ffffffff8330a72a-ffffffff8330a750: dmi_checksum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dmi_checksum(const u8 *buf, u8 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff834c3fde)
Location: drivers/firmware/dmi_scan.c:155
Inline: False
Direct callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:dmi_present
```
**Symbols:**

```
ffffffff834c3fde-ffffffff834c400e: dmi_checksum (STB_LOCAL)
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
In drivers/firmware/dmi_scan.c (ffffffff83f04e33)
Location: drivers/firmware/dmi_scan.c:155
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:dmi_present
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
In drivers/firmware/dmi_scan.c (ffffffff8372ab67)
Location: drivers/firmware/dmi_scan.c:155
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:dmi_present
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
In drivers/firmware/dmi_scan.c (ffffffff8395eb27)
Location: drivers/firmware/dmi_scan.c:155
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:dmi_present
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
In drivers/firmware/dmi_scan.c (ffff8000114a3fd0)
Location: drivers/firmware/dmi_scan.c:150
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
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
In drivers/firmware/dmi_scan.c (c15a6918)
Location: drivers/firmware/dmi_scan.c:150
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
```
</details>
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff828fb345)
Location: drivers/firmware/dmi_scan.c:150
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:dmi_present
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
In drivers/firmware/dmi_scan.c (ffffffff828f2be1)
Location: drivers/firmware/dmi_scan.c:150
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:dmi_present
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
In drivers/firmware/dmi_scan.c (ffffffff82910426)
Location: drivers/firmware/dmi_scan.c:150
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:dmi_present
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
In drivers/firmware/dmi_scan.c (ffffffff82916e53)
Location: drivers/firmware/dmi_scan.c:150
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_smbios3_present
  - drivers/firmware/dmi_scan.c:dmi_present
  - drivers/firmware/dmi_scan.c:dmi_present
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
</ul>
