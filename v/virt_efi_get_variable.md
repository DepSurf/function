# Function: <code>virt_efi_get_variable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
efi_status_t virt_efi_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff816d4d40)
Location: drivers/firmware/efi/runtime-wrappers.c:152
Inline: False
```
**Symbols:**

```
ffffffff816d4d40-ffffffff816d4dcf: virt_efi_get_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
efi_status_t virt_efi_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81738ee0)
Location: drivers/firmware/efi/runtime-wrappers.c:133
Inline: False
```
**Symbols:**

```
ffffffff81738ee0-ffffffff81738ff5: virt_efi_get_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff8176c050)
Location: drivers/firmware/efi/runtime-wrappers.c:139
Inline: True
```
**Symbols:**

```
ffffffff8176c050-ffffffff8176c185: virt_efi_get_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff8178a410)
Location: drivers/firmware/efi/runtime-wrappers.c:139
Inline: True
```
**Symbols:**

```
ffffffff8178a410-ffffffff8178a544: virt_efi_get_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81800980)
Location: drivers/firmware/efi/runtime-wrappers.c:139
Inline: True
```
**Symbols:**

```
ffffffff81800980-ffffffff81800ada: virt_efi_get_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81849ef0)
Location: drivers/firmware/efi/runtime-wrappers.c:139
Inline: True
```
**Symbols:**

```
ffffffff81849ef0-ffffffff8184a00a: virt_efi_get_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:287
Inline: False
```
**Symbols:**

```
ffffffff81875fe0-ffffffff81876125: virt_efi_get_variable (STB_LOCAL)
ffffffff8187727f-ffffffff818772b6: virt_efi_get_variable.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:299
Inline: False
```
**Symbols:**

```
ffffffff818ba1f0-ffffffff818ba33b: virt_efi_get_variable (STB_LOCAL)
ffffffff818bb70f-ffffffff818bb746: virt_efi_get_variable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:299
Inline: False
```
**Symbols:**

```
ffffffff818ecc90-ffffffff818ecddb: virt_efi_get_variable (STB_LOCAL)
ffffffff818ee1af-ffffffff818ee1e6: virt_efi_get_variable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff819c0350)
Location: drivers/firmware/efi/runtime-wrappers.c:299
Inline: True
```
**Symbols:**

```
ffffffff819c0220-ffffffff819c034d: virt_efi_get_variable.part.0 (STB_LOCAL)
ffffffff819c1bda-ffffffff819c1c11: virt_efi_get_variable.part.0.cold (STB_LOCAL)
ffffffff819c0350-ffffffff819c03ae: virt_efi_get_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff819c1a20)
Location: drivers/firmware/efi/runtime-wrappers.c:299
Inline: True
```
**Symbols:**

```
ffffffff819c18f0-ffffffff819c1a1d: virt_efi_get_variable.part.0 (STB_LOCAL)
ffffffff81c2cba0-ffffffff81c2cbd7: virt_efi_get_variable.part.0.cold (STB_LOCAL)
ffffffff819c1a20-ffffffff819c1a7e: virt_efi_get_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff819a5cb3)
Location: drivers/firmware/efi/runtime-wrappers.c:299
Inline: True
```
**Symbols:**

```
ffffffff819a5c70-ffffffff819a5dbb: virt_efi_get_variable (STB_LOCAL)
ffffffff81c1ed60-ffffffff81c1ed97: virt_efi_get_variable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81a532d3)
Location: drivers/firmware/efi/runtime-wrappers.c:299
Inline: True
```
**Symbols:**

```
ffffffff81a53290-ffffffff81a533e6: virt_efi_get_variable (STB_LOCAL)
ffffffff81d303a7-ffffffff81d303e4: virt_efi_get_variable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:299
Inline: False
```
**Symbols:**

```
ffffffff81bc2080-ffffffff81bc21e3: virt_efi_get_variable (STB_LOCAL)
ffffffff81efc724-ffffffff81efc761: virt_efi_get_variable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:301
Inline: False
```
**Symbols:**

```
ffffffff81d66bd0-ffffffff81d66d7b: virt_efi_get_variable (STB_LOCAL)
ffffffff820a9f0e-ffffffff820a9f22: virt_efi_get_variable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:301
Inline: False
```
**Symbols:**

```
ffffffff81dd1ce0-ffffffff81dd1e8b: virt_efi_get_variable (STB_LOCAL)
ffffffff8212b2bc-ffffffff8212b2d0: virt_efi_get_variable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81e8a6a0)
Location: drivers/firmware/efi/runtime-wrappers.c:393
Inline: True
```
**Symbols:**

```
ffffffff81e8a6a0-ffffffff81e8a766: virt_efi_get_variable (STB_LOCAL)
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
efi_status_t virt_efi_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffff800010b5ff50)
Location: drivers/firmware/efi/runtime-wrappers.c:299
Inline: False
```
**Symbols:**

```
ffff800010b5ff50-ffff800010b600cc: virt_efi_get_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
efi_status_t virt_efi_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (c0c3f4f0)
Location: drivers/firmware/efi/runtime-wrappers.c:299
Inline: False
```
**Symbols:**

```
c0c3f4f0-c0c3f638: virt_efi_get_variable (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:299
Inline: False
```
**Symbols:**

```
ffffffff8188e870-ffffffff8188e9bb: virt_efi_get_variable (STB_LOCAL)
ffffffff8188fd8f-ffffffff8188fdc6: virt_efi_get_variable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:299
Inline: False
```
**Symbols:**

```
ffffffff81847390-ffffffff818474db: virt_efi_get_variable (STB_LOCAL)
ffffffff8184883f-ffffffff81848876: virt_efi_get_variable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:299
Inline: False
```
**Symbols:**

```
ffffffff818e1af0-ffffffff818e1c3b: virt_efi_get_variable (STB_LOCAL)
ffffffff818e300f-ffffffff818e3046: virt_efi_get_variable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:299
Inline: False
```
**Symbols:**

```
ffffffff818fe590-ffffffff818fe6db: virt_efi_get_variable (STB_LOCAL)
ffffffff818ffc4f-ffffffff818ffc86: virt_efi_get_variable.cold (STB_LOCAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
