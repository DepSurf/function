# Function: <code>acpi_of_match_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool acpi_of_match_device(struct acpi_device *adev, const struct of_device_id *of_match_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8147e0dd)
Location: drivers/acpi/bus.c:562
Inline: False
Direct callers:
  - drivers/acpi/bus.c:__acpi_match_device
```
**Symbols:**

```
ffffffff8147e0dd-ffffffff8147e175: acpi_of_match_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool acpi_of_match_device(struct acpi_device *adev, const struct of_device_id *of_match_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff814cc84a)
Location: drivers/acpi/bus.c:638
Inline: False
Direct callers:
  - drivers/acpi/bus.c:__acpi_match_device
```
**Symbols:**

```
ffffffff814cc84a-ffffffff814cc8ce: acpi_of_match_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool acpi_of_match_device(struct acpi_device *adev, const struct of_device_id *of_match_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff814ee778)
Location: drivers/acpi/bus.c:648
Inline: False
Direct callers:
  - drivers/acpi/bus.c:__acpi_match_device
```
**Symbols:**

```
ffffffff814ee778-ffffffff814ee7fc: acpi_of_match_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool acpi_of_match_device(struct acpi_device *adev, const struct of_device_id *of_match_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff814fb7a0)
Location: drivers/acpi/bus.c:634
Inline: False
Direct callers:
  - drivers/acpi/bus.c:__acpi_match_device
```
**Symbols:**

```
ffffffff814fb7a0-ffffffff814fb860: acpi_of_match_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool acpi_of_match_device(struct acpi_device *adev, const struct of_device_id *of_match_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8153d430)
Location: drivers/acpi/bus.c:661
Inline: False
Direct callers:
  - drivers/acpi/bus.c:__acpi_match_device
```
**Symbols:**

```
ffffffff8153d430-ffffffff8153d4f0: acpi_of_match_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/bus.c (ffffffff81573be0)
Location: drivers/acpi/bus.c:669
Inline: True
```
**Symbols:**

```
ffffffff81573be0-ffffffff81573ca3: acpi_of_match_device.constprop.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8158b800)
Location: drivers/acpi/bus.c:638
Inline: True
```
**Symbols:**

```
ffffffff8158b800-ffffffff8158b8c3: acpi_of_match_device.constprop.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool acpi_of_match_device(struct acpi_device *adev, const struct of_device_id *of_match_table, const struct of_device_id **of_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815bbc70)
Location: drivers/acpi/bus.c:625
Inline: False
```
**Symbols:**

```
ffffffff815bbc70-ffffffff815bbd4d: acpi_of_match_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool acpi_of_match_device(struct acpi_device *adev, const struct of_device_id *of_match_table, const struct of_device_id **of_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815dcf30)
Location: drivers/acpi/bus.c:625
Inline: False
```
**Symbols:**

```
ffffffff815dcf30-ffffffff815dd00d: acpi_of_match_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool acpi_of_match_device(struct acpi_device *adev, const struct of_device_id *of_match_table, const struct of_device_id **of_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff81687650)
Location: drivers/acpi/bus.c:625
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_device_get_match_data
```
**Symbols:**

```
ffffffff81687650-ffffffff8168772d: acpi_of_match_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool acpi_of_match_device(struct acpi_device *adev, const struct of_device_id *of_match_table, const struct of_device_id **of_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff816a53c0)
Location: drivers/acpi/bus.c:630
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_device_get_match_data
```
**Symbols:**

```
ffffffff816a53c0-ffffffff816a549d: acpi_of_match_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool acpi_of_match_device(struct acpi_device *adev, const struct of_device_id *of_match_table, const struct of_device_id **of_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff81688130)
Location: drivers/acpi/bus.c:709
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_device_get_match_data
```
**Symbols:**

```
ffffffff81688130-ffffffff8168820c: acpi_of_match_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool acpi_of_match_device(struct acpi_device *adev, const struct of_device_id *of_match_table, const struct of_device_id **of_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff816fd580)
Location: drivers/acpi/bus.c:711
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_device_get_match_data
```
**Symbols:**

```
ffffffff816fd580-ffffffff816fd65c: acpi_of_match_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool acpi_of_match_device(struct acpi_device *adev, const struct of_device_id *of_match_table, const struct of_device_id **of_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8182adb0)
Location: drivers/acpi/bus.c:748
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_device_get_match_data
```
**Symbols:**

```
ffffffff8182adb0-ffffffff8182aeb3: acpi_of_match_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool acpi_of_match_device(struct acpi_device *adev, const struct of_device_id *of_match_table, const struct of_device_id **of_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8195d390)
Location: drivers/acpi/bus.c:754
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_driver_match_device
  - drivers/acpi/bus.c:acpi_device_get_match_data
```
**Symbols:**

```
ffffffff8195d390-ffffffff8195d493: acpi_of_match_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool acpi_of_match_device(const struct acpi_device *adev, const struct of_device_id *of_match_table, const struct of_device_id **of_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff819a3840)
Location: drivers/acpi/bus.c:709
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_driver_match_device
  - drivers/acpi/bus.c:acpi_device_get_match_data
```
**Symbols:**

```
ffffffff819a3840-ffffffff819a392c: acpi_of_match_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool acpi_of_match_device(const struct acpi_device *adev, const struct of_device_id *of_match_table, const struct of_device_id **of_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff819ebf70)
Location: drivers/acpi/bus.c:759
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_driver_match_device
  - drivers/acpi/bus.c:acpi_device_get_match_data
```
**Symbols:**

```
ffffffff819ebf70-ffffffff819ec05c: acpi_of_match_device (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool acpi_of_match_device(struct acpi_device *adev, const struct of_device_id *of_match_table, const struct of_device_id **of_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffff800010769280)
Location: drivers/acpi/bus.c:625
Inline: False
```
**Symbols:**

```
ffff800010769280-ffff8000107693ac: acpi_of_match_device (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool acpi_of_match_device(struct acpi_device *adev, const struct of_device_id *of_match_table, const struct of_device_id **of_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815cf580)
Location: drivers/acpi/bus.c:625
Inline: False
```
**Symbols:**

```
ffffffff815cf580-ffffffff815cf65d: acpi_of_match_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool acpi_of_match_device(struct acpi_device *adev, const struct of_device_id *of_match_table, const struct of_device_id **of_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815b9140)
Location: drivers/acpi/bus.c:625
Inline: False
```
**Symbols:**

```
ffffffff815b9140-ffffffff815b921d: acpi_of_match_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool acpi_of_match_device(struct acpi_device *adev, const struct of_device_id *of_match_table, const struct of_device_id **of_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815d1210)
Location: drivers/acpi/bus.c:625
Inline: False
```
**Symbols:**

```
ffffffff815d1210-ffffffff815d12ed: acpi_of_match_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool acpi_of_match_device(struct acpi_device *adev, const struct of_device_id *of_match_table, const struct of_device_id **of_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815eb0d0)
Location: drivers/acpi/bus.c:625
Inline: False
```
**Symbols:**

```
ffffffff815eb0d0-ffffffff815eb1ad: acpi_of_match_device (STB_LOCAL)
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
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct acpi_device *adev</code> ➡️ <code>const struct acpi_device *adev</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
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
