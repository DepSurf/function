# Function: <code>virt_efi_get_next_variable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
efi_status_t virt_efi_get_next_variable(long unsigned int *name_size, efi_char16_t *name, efi_guid_t *vendor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff816d4cc0)
Location: drivers/firmware/efi/runtime-wrappers.c:168
Inline: False
```
**Symbols:**

```
ffffffff816d4cc0-ffffffff816d4d32: virt_efi_get_next_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
efi_status_t virt_efi_get_next_variable(long unsigned int *name_size, efi_char16_t *name, efi_guid_t *vendor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81738de0)
Location: drivers/firmware/efi/runtime-wrappers.c:148
Inline: False
```
**Symbols:**

```
ffffffff81738de0-ffffffff81738edb: virt_efi_get_next_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_get_next_variable(long unsigned int *name_size, efi_char16_t *name, efi_guid_t *vendor);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff8176bf20)
Location: drivers/firmware/efi/runtime-wrappers.c:155
Inline: True
```
**Symbols:**

```
ffffffff8176bf20-ffffffff8176c046: virt_efi_get_next_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_get_next_variable(long unsigned int *name_size, efi_char16_t *name, efi_guid_t *vendor);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff8178a2f0)
Location: drivers/firmware/efi/runtime-wrappers.c:155
Inline: True
```
**Symbols:**

```
ffffffff8178a2f0-ffffffff8178a409: virt_efi_get_next_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_get_next_variable(long unsigned int *name_size, efi_char16_t *name, efi_guid_t *vendor);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81800830)
Location: drivers/firmware/efi/runtime-wrappers.c:155
Inline: True
```
**Symbols:**

```
ffffffff81800830-ffffffff81800972: virt_efi_get_next_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_get_next_variable(long unsigned int *name_size, efi_char16_t *name, efi_guid_t *vendor);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81849de0)
Location: drivers/firmware/efi/runtime-wrappers.c:155
Inline: True
```
**Symbols:**

```
ffffffff81849de0-ffffffff81849ee2: virt_efi_get_next_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_next_variable(long unsigned int *name_size, efi_char16_t *name, efi_guid_t *vendor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:303
Inline: False
```
**Symbols:**

```
ffffffff81875ea0-ffffffff81875fd6: virt_efi_get_next_variable (STB_LOCAL)
ffffffff81877248-ffffffff8187727f: virt_efi_get_next_variable.cold.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_next_variable(long unsigned int *name_size, efi_char16_t *name, efi_guid_t *vendor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:315
Inline: False
```
**Symbols:**

```
ffffffff818ba0b0-ffffffff818ba1e7: virt_efi_get_next_variable (STB_LOCAL)
ffffffff818bb6d8-ffffffff818bb70f: virt_efi_get_next_variable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_next_variable(long unsigned int *name_size, efi_char16_t *name, efi_guid_t *vendor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:315
Inline: False
```
**Symbols:**

```
ffffffff818ecb50-ffffffff818ecc87: virt_efi_get_next_variable (STB_LOCAL)
ffffffff818ee178-ffffffff818ee1af: virt_efi_get_next_variable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_next_variable(long unsigned int *name_size, efi_char16_t *name, efi_guid_t *vendor);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff819c01d0)
Location: drivers/firmware/efi/runtime-wrappers.c:315
Inline: True
```
**Symbols:**

```
ffffffff819c00a0-ffffffff819c01c7: virt_efi_get_next_variable.part.0 (STB_LOCAL)
ffffffff819c1ba3-ffffffff819c1bda: virt_efi_get_next_variable.part.0.cold (STB_LOCAL)
ffffffff819c01d0-ffffffff819c021c: virt_efi_get_next_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_next_variable(long unsigned int *name_size, efi_char16_t *name, efi_guid_t *vendor);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff819c18a0)
Location: drivers/firmware/efi/runtime-wrappers.c:315
Inline: True
```
**Symbols:**

```
ffffffff819c1770-ffffffff819c1897: virt_efi_get_next_variable.part.0 (STB_LOCAL)
ffffffff81c2cb69-ffffffff81c2cba0: virt_efi_get_next_variable.part.0.cold (STB_LOCAL)
ffffffff819c18a0-ffffffff819c18ec: virt_efi_get_next_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_next_variable(long unsigned int *name_size, efi_char16_t *name, efi_guid_t *vendor);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff819a5b63)
Location: drivers/firmware/efi/runtime-wrappers.c:315
Inline: True
```
**Symbols:**

```
ffffffff819a5b30-ffffffff819a5c67: virt_efi_get_next_variable (STB_LOCAL)
ffffffff81c1ed29-ffffffff81c1ed60: virt_efi_get_next_variable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_next_variable(long unsigned int *name_size, efi_char16_t *name, efi_guid_t *vendor);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81a53173)
Location: drivers/firmware/efi/runtime-wrappers.c:315
Inline: True
```
**Symbols:**

```
ffffffff81a53140-ffffffff81a53283: virt_efi_get_next_variable (STB_LOCAL)
ffffffff81d3036a-ffffffff81d303a7: virt_efi_get_next_variable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_next_variable(long unsigned int *name_size, efi_char16_t *name, efi_guid_t *vendor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:315
Inline: False
```
**Symbols:**

```
ffffffff81bc1f30-ffffffff81bc207d: virt_efi_get_next_variable (STB_LOCAL)
ffffffff81efc6e7-ffffffff81efc724: virt_efi_get_next_variable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_next_variable(long unsigned int *name_size, efi_char16_t *name, efi_guid_t *vendor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:317
Inline: False
```
**Symbols:**

```
ffffffff81d66a20-ffffffff81d66bb5: virt_efi_get_next_variable (STB_LOCAL)
ffffffff820a9efa-ffffffff820a9f0e: virt_efi_get_next_variable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_next_variable(long unsigned int *name_size, efi_char16_t *name, efi_guid_t *vendor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:317
Inline: False
```
**Symbols:**

```
ffffffff81dd1b30-ffffffff81dd1cc5: virt_efi_get_next_variable (STB_LOCAL)
ffffffff8212b2a8-ffffffff8212b2bc: virt_efi_get_next_variable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_get_next_variable(long unsigned int *name_size, efi_char16_t *name, efi_guid_t *vendor);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81e8a5d0)
Location: drivers/firmware/efi/runtime-wrappers.c:409
Inline: True
```
**Symbols:**

```
ffffffff81e8a5d0-ffffffff81e8a686: virt_efi_get_next_variable (STB_LOCAL)
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
efi_status_t virt_efi_get_next_variable(long unsigned int *name_size, efi_char16_t *name, efi_guid_t *vendor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffff800010b5fde8)
Location: drivers/firmware/efi/runtime-wrappers.c:315
Inline: False
```
**Symbols:**

```
ffff800010b5fde8-ffff800010b5ff4c: virt_efi_get_next_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
efi_status_t virt_efi_get_next_variable(long unsigned int *name_size, efi_char16_t *name, efi_guid_t *vendor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (c0c3f3b0)
Location: drivers/firmware/efi/runtime-wrappers.c:315
Inline: False
```
**Symbols:**

```
c0c3f3b0-c0c3f4f0: virt_efi_get_next_variable (STB_LOCAL)
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
efi_status_t virt_efi_get_next_variable(long unsigned int *name_size, efi_char16_t *name, efi_guid_t *vendor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:315
Inline: False
```
**Symbols:**

```
ffffffff8188e730-ffffffff8188e867: virt_efi_get_next_variable (STB_LOCAL)
ffffffff8188fd58-ffffffff8188fd8f: virt_efi_get_next_variable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_next_variable(long unsigned int *name_size, efi_char16_t *name, efi_guid_t *vendor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:315
Inline: False
```
**Symbols:**

```
ffffffff81847250-ffffffff81847387: virt_efi_get_next_variable (STB_LOCAL)
ffffffff81848808-ffffffff8184883f: virt_efi_get_next_variable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_next_variable(long unsigned int *name_size, efi_char16_t *name, efi_guid_t *vendor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:315
Inline: False
```
**Symbols:**

```
ffffffff818e19b0-ffffffff818e1ae7: virt_efi_get_next_variable (STB_LOCAL)
ffffffff818e2fd8-ffffffff818e300f: virt_efi_get_next_variable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_get_next_variable(long unsigned int *name_size, efi_char16_t *name, efi_guid_t *vendor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:315
Inline: False
```
**Symbols:**

```
ffffffff818fe450-ffffffff818fe587: virt_efi_get_next_variable (STB_LOCAL)
ffffffff818ffc18-ffffffff818ffc4f: virt_efi_get_next_variable.cold (STB_LOCAL)
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
