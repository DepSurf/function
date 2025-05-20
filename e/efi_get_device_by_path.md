# Function: <code>efi_get_device_by_path</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
struct device *efi_get_device_by_path(struct efi_dev_path **node, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/dev-path-parser.c (ffffffff82022fdb)
Location: drivers/firmware/efi/dev-path-parser.c:166
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff82022fdb-ffffffff82023245: efi_get_device_by_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct device *efi_get_device_by_path(struct efi_dev_path **node, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/dev-path-parser.c (ffffffff82105cf7)
Location: drivers/firmware/efi/dev-path-parser.c:166
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff82105cf7-ffffffff82105f7b: efi_get_device_by_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct device *efi_get_device_by_path(struct efi_dev_path **node, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/dev-path-parser.c (ffffffff8270f3c0)
Location: drivers/firmware/efi/dev-path-parser.c:166
Inline: False
```
**Symbols:**

```
ffffffff8270f3c0-ffffffff8270f644: efi_get_device_by_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct device *efi_get_device_by_path(struct efi_dev_path **node, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/dev-path-parser.c (ffffffff82739665)
Location: drivers/firmware/efi/dev-path-parser.c:166
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff82739665-ffffffff827398ec: efi_get_device_by_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct device *efi_get_device_by_path(struct efi_dev_path **node, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/dev-path-parser.c (ffffffff828f3634)
Location: drivers/firmware/efi/dev-path-parser.c:166
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff828f3634-ffffffff828f38bb: efi_get_device_by_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct device *efi_get_device_by_path(struct efi_dev_path **node, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/dev-path-parser.c (ffffffff8290ef3f)
Location: drivers/firmware/efi/dev-path-parser.c:159
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
**Symbols:**

```
ffffffff8290ef3f-ffffffff8290f1c8: efi_get_device_by_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct device *efi_get_device_by_path(struct efi_dev_path **node, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/dev-path-parser.c (ffffffff8291890e)
Location: drivers/firmware/efi/dev-path-parser.c:159
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
**Symbols:**

```
ffffffff8291890e-ffffffff82918b97: efi_get_device_by_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct device *efi_get_device_by_path(const struct efi_dev_path **node, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/dev-path-parser.c (ffffffff82d2ad65)
Location: drivers/firmware/efi/dev-path-parser.c:159
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
**Symbols:**

```
ffffffff82d2ad65-ffffffff82d2afee: efi_get_device_by_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct device *efi_get_device_by_path(const struct efi_dev_path **node, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/dev-path-parser.c (ffffffff83019499)
Location: drivers/firmware/efi/dev-path-parser.c:159
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
**Symbols:**

```
ffffffff83019499-ffffffff83019722: efi_get_device_by_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct device *efi_get_device_by_path(const struct efi_dev_path **node, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/dev-path-parser.c (ffffffff832244d7)
Location: drivers/firmware/efi/dev-path-parser.c:145
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
**Symbols:**

```
ffffffff832244d7-ffffffff8322476a: efi_get_device_by_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct device *efi_get_device_by_path(const struct efi_dev_path **node, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/dev-path-parser.c (ffffffff8330e2d1)
Location: drivers/firmware/efi/dev-path-parser.c:145
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
**Symbols:**

```
ffffffff8330e2d1-ffffffff8330e564: efi_get_device_by_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct device *efi_get_device_by_path(const struct efi_dev_path **node, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/dev-path-parser.c (ffffffff834c7fe0)
Location: drivers/firmware/efi/dev-path-parser.c:145
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
**Symbols:**

```
ffffffff834c7fe0-ffffffff834c82aa: efi_get_device_by_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct device *efi_get_device_by_path(const struct efi_dev_path **node, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/dev-path-parser.c (ffffffff83f09110)
Location: drivers/firmware/efi/dev-path-parser.c:147
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
**Symbols:**

```
ffffffff83f09110-ffffffff83f09421: efi_get_device_by_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct device *efi_get_device_by_path(const struct efi_dev_path **node, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/dev-path-parser.c (ffffffff8372f230)
Location: drivers/firmware/efi/dev-path-parser.c:147
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
**Symbols:**

```
ffffffff8372f230-ffffffff8372f550: efi_get_device_by_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct device *efi_get_device_by_path(const struct efi_dev_path **node, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/dev-path-parser.c (ffffffff83963720)
Location: drivers/firmware/efi/dev-path-parser.c:144
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
**Symbols:**

```
ffffffff83963720-ffffffff83963a4d: efi_get_device_by_path (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
struct device *efi_get_device_by_path(struct efi_dev_path **node, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/dev-path-parser.c (ffffffff828fdd14)
Location: drivers/firmware/efi/dev-path-parser.c:159
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
**Symbols:**

```
ffffffff828fdd14-ffffffff828fdf9d: efi_get_device_by_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct device *efi_get_device_by_path(struct efi_dev_path **node, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/dev-path-parser.c (ffffffff828f55b0)
Location: drivers/firmware/efi/dev-path-parser.c:159
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
**Symbols:**

```
ffffffff828f55b0-ffffffff828f5839: efi_get_device_by_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct device *efi_get_device_by_path(struct efi_dev_path **node, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/dev-path-parser.c (ffffffff82912f43)
Location: drivers/firmware/efi/dev-path-parser.c:159
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
**Symbols:**

```
ffffffff82912f43-ffffffff829131cc: efi_get_device_by_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct device *efi_get_device_by_path(struct efi_dev_path **node, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/dev-path-parser.c (ffffffff82919970)
Location: drivers/firmware/efi/dev-path-parser.c:159
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:unmarshal_devices
```
**Symbols:**

```
ffffffff82919970-ffffffff82919bf9: efi_get_device_by_path (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct efi_dev_path **node</code> ➡️ <code>const struct efi_dev_path **node</code>
</li>
</ul>
</details>
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
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
