# Function: <code>unmarshal_key_value_pairs</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/apple-properties.c (ffffffff82023500)
Location: drivers/firmware/efi/apple-properties.c:57
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
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
In drivers/firmware/efi/apple-properties.c (ffffffff8210611a)
Location: drivers/firmware/efi/apple-properties.c:57
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
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
In drivers/firmware/efi/apple-properties.c (ffffffff8270f816)
Location: drivers/firmware/efi/apple-properties.c:57
Inline: True
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
In drivers/firmware/efi/apple-properties.c (ffffffff82739bc8)
Location: drivers/firmware/efi/apple-properties.c:59
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
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
In drivers/firmware/efi/apple-properties.c (ffffffff828f3b97)
Location: drivers/firmware/efi/apple-properties.c:59
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
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
In drivers/firmware/efi/apple-properties.c (ffffffff8290f353)
Location: drivers/firmware/efi/apple-properties.c:48
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
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
In drivers/firmware/efi/apple-properties.c (ffffffff82918d22)
Location: drivers/firmware/efi/apple-properties.c:48
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void unmarshal_key_value_pairs(struct dev_header *dev_header, struct device *dev, const void *ptr, struct property_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/apple-properties.c (ffffffff82d2b055)
Location: drivers/firmware/efi/apple-properties.c:48
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
**Symbols:**

```
ffffffff82d2b055-ffffffff82d2b245: unmarshal_key_value_pairs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void unmarshal_key_value_pairs(struct dev_header *dev_header, struct device *dev, const void *ptr, struct property_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/apple-properties.c (ffffffff83019789)
Location: drivers/firmware/efi/apple-properties.c:49
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
**Symbols:**

```
ffffffff83019789-ffffffff8301998d: unmarshal_key_value_pairs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void unmarshal_key_value_pairs(struct dev_header *dev_header, struct device *dev, const void *ptr, struct property_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/apple-properties.c (ffffffff832247d1)
Location: drivers/firmware/efi/apple-properties.c:49
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
**Symbols:**

```
ffffffff832247d1-ffffffff832249d5: unmarshal_key_value_pairs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void unmarshal_key_value_pairs(struct dev_header *dev_header, struct device *dev, const void *ptr, struct property_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/apple-properties.c (ffffffff8330e5cb)
Location: drivers/firmware/efi/apple-properties.c:49
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
**Symbols:**

```
ffffffff8330e5cb-ffffffff8330e7ee: unmarshal_key_value_pairs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void unmarshal_key_value_pairs(struct dev_header *dev_header, struct device *dev, const void *ptr, struct property_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/apple-properties.c (ffffffff834c832c)
Location: drivers/firmware/efi/apple-properties.c:49
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
**Symbols:**

```
ffffffff834c832c-ffffffff834c8558: unmarshal_key_value_pairs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void unmarshal_key_value_pairs(struct dev_header *dev_header, struct device *dev, const void *ptr, struct property_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/apple-properties.c (ffffffff83f09500)
Location: drivers/firmware/efi/apple-properties.c:49
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
**Symbols:**

```
ffffffff83f09500-ffffffff83f09812: unmarshal_key_value_pairs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void unmarshal_key_value_pairs(struct dev_header *dev_header, struct device *dev, const void *ptr, struct property_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/apple-properties.c (ffffffff8372f620)
Location: drivers/firmware/efi/apple-properties.c:49
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
**Symbols:**

```
ffffffff8372f620-ffffffff8372f932: unmarshal_key_value_pairs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void unmarshal_key_value_pairs(struct dev_header *dev_header, struct device *dev, const void *ptr, struct property_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/apple-properties.c (ffffffff83963b20)
Location: drivers/firmware/efi/apple-properties.c:49
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
**Symbols:**

```
ffffffff83963b20-ffffffff83963e32: unmarshal_key_value_pairs (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/apple-properties.c (ffffffff828fe128)
Location: drivers/firmware/efi/apple-properties.c:48
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
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
In drivers/firmware/efi/apple-properties.c (ffffffff828f59c4)
Location: drivers/firmware/efi/apple-properties.c:48
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
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
In drivers/firmware/efi/apple-properties.c (ffffffff82913357)
Location: drivers/firmware/efi/apple-properties.c:48
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
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
In drivers/firmware/efi/apple-properties.c (ffffffff82919d84)
Location: drivers/firmware/efi/apple-properties.c:48
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
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
