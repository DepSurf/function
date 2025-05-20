# Function: <code>virt_efi_set_variable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
efi_status_t virt_efi_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff816d4c30)
Location: drivers/firmware/efi/runtime-wrappers.c:181
Inline: False
```
**Symbols:**

```
ffffffff816d4c30-ffffffff816d4cbf: virt_efi_set_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
efi_status_t virt_efi_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81738cc0)
Location: drivers/firmware/efi/runtime-wrappers.c:160
Inline: False
```
**Symbols:**

```
ffffffff81738cc0-ffffffff81738dd5: virt_efi_set_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff8176bd20)
Location: drivers/firmware/efi/runtime-wrappers.c:168
Inline: True
```
**Symbols:**

```
ffffffff8176bd20-ffffffff8176be34: virt_efi_set_variable.part.7 (STB_LOCAL)
ffffffff8176beb0-ffffffff8176bf1e: virt_efi_set_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff8178a230)
Location: drivers/firmware/efi/runtime-wrappers.c:168
Inline: True
```
**Symbols:**

```
ffffffff8178a110-ffffffff8178a224: virt_efi_set_variable.part.7 (STB_LOCAL)
ffffffff8178a230-ffffffff8178a290: virt_efi_set_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81800770)
Location: drivers/firmware/efi/runtime-wrappers.c:168
Inline: True
```
**Symbols:**

```
ffffffff81800630-ffffffff81800769: virt_efi_set_variable.part.6 (STB_LOCAL)
ffffffff81800770-ffffffff818007d0: virt_efi_set_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81849d20)
Location: drivers/firmware/efi/runtime-wrappers.c:168
Inline: True
```
**Symbols:**

```
ffffffff81849c20-ffffffff81849d1a: virt_efi_set_variable.part.6 (STB_LOCAL)
ffffffff81849d20-ffffffff81849d80: virt_efi_set_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
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
ffffffff81875d50-ffffffff81875e95: virt_efi_set_variable (STB_LOCAL)
ffffffff81877211-ffffffff81877248: virt_efi_set_variable.cold.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:329
Inline: False
```
**Symbols:**

```
ffffffff818b9f60-ffffffff818ba0a6: virt_efi_set_variable (STB_LOCAL)
ffffffff818bb6a1-ffffffff818bb6d8: virt_efi_set_variable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:329
Inline: False
```
**Symbols:**

```
ffffffff818eca00-ffffffff818ecb46: virt_efi_set_variable (STB_LOCAL)
ffffffff818ee141-ffffffff818ee178: virt_efi_set_variable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:329
Inline: False
```
**Symbols:**

```
ffffffff819c0670-ffffffff819c07b6: virt_efi_set_variable (STB_LOCAL)
ffffffff819c1c7f-ffffffff819c1cb6: virt_efi_set_variable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:329
Inline: False
```
**Symbols:**

```
ffffffff819c1090-ffffffff819c11d6: virt_efi_set_variable (STB_LOCAL)
ffffffff81c2ca56-ffffffff81c2ca8d: virt_efi_set_variable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:329
Inline: False
```
**Symbols:**

```
ffffffff819a5360-ffffffff819a54a6: virt_efi_set_variable (STB_LOCAL)
ffffffff81c1ebdf-ffffffff81c1ec16: virt_efi_set_variable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:329
Inline: False
```
**Symbols:**

```
ffffffff81a52a80-ffffffff81a52bd2: virt_efi_set_variable (STB_LOCAL)
ffffffff81d30239-ffffffff81d30276: virt_efi_set_variable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:329
Inline: False
```
**Symbols:**

```
ffffffff81bc1dc0-ffffffff81bc1f21: virt_efi_set_variable (STB_LOCAL)
ffffffff81efc6aa-ffffffff81efc6e7: virt_efi_set_variable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:331
Inline: False
```
**Symbols:**

```
ffffffff81d66860-ffffffff81d66a09: virt_efi_set_variable (STB_LOCAL)
ffffffff820a9ee6-ffffffff820a9efa: virt_efi_set_variable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:331
Inline: False
```
**Symbols:**

```
ffffffff81dd1970-ffffffff81dd1b19: virt_efi_set_variable (STB_LOCAL)
ffffffff8212b294-ffffffff8212b2a8: virt_efi_set_variable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81e8a4f0)
Location: drivers/firmware/efi/runtime-wrappers.c:422
Inline: True
```
**Symbols:**

```
ffffffff81e8a4f0-ffffffff81e8a5b6: virt_efi_set_variable (STB_LOCAL)
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
efi_status_t virt_efi_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffff800010b5fc70)
Location: drivers/firmware/efi/runtime-wrappers.c:329
Inline: False
```
**Symbols:**

```
ffff800010b5fc70-ffff800010b5fde4: virt_efi_set_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
efi_status_t virt_efi_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (c0c3f258)
Location: drivers/firmware/efi/runtime-wrappers.c:329
Inline: False
```
**Symbols:**

```
c0c3f258-c0c3f3b0: virt_efi_set_variable (STB_LOCAL)
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
efi_status_t virt_efi_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:329
Inline: False
```
**Symbols:**

```
ffffffff8188e5e0-ffffffff8188e726: virt_efi_set_variable (STB_LOCAL)
ffffffff8188fd21-ffffffff8188fd58: virt_efi_set_variable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:329
Inline: False
```
**Symbols:**

```
ffffffff81847100-ffffffff81847246: virt_efi_set_variable (STB_LOCAL)
ffffffff818487d1-ffffffff81848808: virt_efi_set_variable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:329
Inline: False
```
**Symbols:**

```
ffffffff818e1860-ffffffff818e19a6: virt_efi_set_variable (STB_LOCAL)
ffffffff818e2fa1-ffffffff818e2fd8: virt_efi_set_variable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:329
Inline: False
```
**Symbols:**

```
ffffffff818fe300-ffffffff818fe446: virt_efi_set_variable (STB_LOCAL)
ffffffff818ffbe1-ffffffff818ffc18: virt_efi_set_variable.cold (STB_LOCAL)
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
