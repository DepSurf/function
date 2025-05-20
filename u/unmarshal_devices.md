# Function: <code>unmarshal_devices</code>

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
In drivers/firmware/efi/apple-properties.c (ffffffff820233e3)
Location: drivers/firmware/efi/apple-properties.c:128
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
In drivers/firmware/efi/apple-properties.c (ffffffff82106112)
Location: drivers/firmware/efi/apple-properties.c:128
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
In drivers/firmware/efi/apple-properties.c (ffffffff8270f80e)
Location: drivers/firmware/efi/apple-properties.c:128
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
In drivers/firmware/efi/apple-properties.c (0)
Location: drivers/firmware/efi/apple-properties.c:126
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
In drivers/firmware/efi/apple-properties.c (0)
Location: drivers/firmware/efi/apple-properties.c:126
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int unmarshal_devices(struct properties_header *properties);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/apple-properties.c (ffffffff8290f22f)
Location: drivers/firmware/efi/apple-properties.c:115
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff8290f22f-ffffffff8290f5b3: unmarshal_devices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int unmarshal_devices(struct properties_header *properties);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/apple-properties.c (ffffffff82918bfe)
Location: drivers/firmware/efi/apple-properties.c:115
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff82918bfe-ffffffff82918f82: unmarshal_devices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int unmarshal_devices(struct properties_header *properties);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/apple-properties.c (ffffffff82d2b245)
Location: drivers/firmware/efi/apple-properties.c:113
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff82d2b245-ffffffff82d2b3f2: unmarshal_devices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int unmarshal_devices(struct properties_header *properties);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/apple-properties.c (ffffffff8301998d)
Location: drivers/firmware/efi/apple-properties.c:118
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff8301998d-ffffffff83019b3a: unmarshal_devices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int unmarshal_devices(struct properties_header *properties);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/apple-properties.c (ffffffff832249d5)
Location: drivers/firmware/efi/apple-properties.c:118
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff832249d5-ffffffff83224b82: unmarshal_devices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int unmarshal_devices(struct properties_header *properties);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/apple-properties.c (ffffffff8330e7ee)
Location: drivers/firmware/efi/apple-properties.c:118
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff8330e7ee-ffffffff8330e99d: unmarshal_devices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int unmarshal_devices(struct properties_header *properties);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/apple-properties.c (ffffffff834c8558)
Location: drivers/firmware/efi/apple-properties.c:118
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff834c8558-ffffffff834c8723: unmarshal_devices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int unmarshal_devices(struct properties_header *properties);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/apple-properties.c (ffffffff83f09830)
Location: drivers/firmware/efi/apple-properties.c:118
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff83f09830-ffffffff83f09a60: unmarshal_devices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int unmarshal_devices(struct properties_header *properties);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/apple-properties.c (ffffffff8372f950)
Location: drivers/firmware/efi/apple-properties.c:118
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff8372f950-ffffffff8372fb80: unmarshal_devices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int unmarshal_devices(struct properties_header *properties);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/apple-properties.c (ffffffff83963e50)
Location: drivers/firmware/efi/apple-properties.c:118
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff83963e50-ffffffff83964080: unmarshal_devices (STB_LOCAL)
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
int unmarshal_devices(struct properties_header *properties);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/apple-properties.c (ffffffff828fe004)
Location: drivers/firmware/efi/apple-properties.c:115
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff828fe004-ffffffff828fe388: unmarshal_devices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int unmarshal_devices(struct properties_header *properties);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/apple-properties.c (ffffffff828f58a0)
Location: drivers/firmware/efi/apple-properties.c:115
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff828f58a0-ffffffff828f5c24: unmarshal_devices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int unmarshal_devices(struct properties_header *properties);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/apple-properties.c (ffffffff82913233)
Location: drivers/firmware/efi/apple-properties.c:115
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff82913233-ffffffff829135b7: unmarshal_devices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int unmarshal_devices(struct properties_header *properties);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/apple-properties.c (ffffffff82919c60)
Location: drivers/firmware/efi/apple-properties.c:115
Inline: False
Direct callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff82919c60-ffffffff82919fe4: unmarshal_devices (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
