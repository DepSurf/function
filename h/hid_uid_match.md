# Function: <code>hid_uid_match</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool hid_uid_match(const char *hid1, const char *uid1, const char *hid2, const char *uid2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff8157ff20)
Location: drivers/acpi/acpi_lpss.c:456
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:match_hid_uid
```
**Symbols:**

```
ffffffff8157ff20-ffffffff8157ff6a: hid_uid_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool hid_uid_match(struct acpi_device *adev, const char *hid2, const char *uid2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff81597c60)
Location: drivers/acpi/acpi_lpss.c:482
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:match_hid_uid
```
**Symbols:**

```
ffffffff81597c60-ffffffff81597cc2: hid_uid_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool hid_uid_match(struct acpi_device *adev, const char *hid2, const char *uid2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815c8e00)
Location: drivers/acpi/acpi_lpss.c:479
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:match_hid_uid
```
**Symbols:**

```
ffffffff815c8e00-ffffffff815c8e62: hid_uid_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool hid_uid_match(struct acpi_device *adev, const char *hid2, const char *uid2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815ea020)
Location: drivers/acpi/acpi_lpss.c:502
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:match_hid_uid
```
**Symbols:**

```
ffffffff815ea020-ffffffff815ea082: hid_uid_match (STB_LOCAL)
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
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool hid_uid_match(struct acpi_device *adev, const char *hid2, const char *uid2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815c4a90)
Location: drivers/acpi/acpi_lpss.c:502
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:match_hid_uid
```
**Symbols:**

```
ffffffff815c4a90-ffffffff815c4af2: hid_uid_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool hid_uid_match(struct acpi_device *adev, const char *hid2, const char *uid2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815de300)
Location: drivers/acpi/acpi_lpss.c:502
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:match_hid_uid
```
**Symbols:**

```
ffffffff815de300-ffffffff815de362: hid_uid_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool hid_uid_match(struct acpi_device *adev, const char *hid2, const char *uid2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815f81c0)
Location: drivers/acpi/acpi_lpss.c:502
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:match_hid_uid
```
**Symbols:**

```
ffffffff815f81c0-ffffffff815f8222: hid_uid_match (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct acpi_device *adev</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *hid1</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *uid1</code>
</li>
<li>
<b>Param reordered. </b>
<code>hid1, uid1, hid2, uid2</code> ➡️ <code>adev, hid2, uid2</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
