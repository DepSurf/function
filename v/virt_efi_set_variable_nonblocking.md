# Function: <code>virt_efi_set_variable_nonblocking</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff816d4b60)
Location: drivers/firmware/efi/runtime-wrappers.c:198
Inline: False
```
**Symbols:**

```
ffffffff816d4b60-ffffffff816d4c22: virt_efi_set_variable_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81738b90)
Location: drivers/firmware/efi/runtime-wrappers.c:176
Inline: True
```
**Symbols:**

```
ffffffff81738b90-ffffffff81738cb6: virt_efi_set_variable_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff8176be40)
Location: drivers/firmware/efi/runtime-wrappers.c:185
Inline: True
```
**Symbols:**

```
ffffffff8176bd20-ffffffff8176be34: virt_efi_set_variable_nonblocking.part.6 (STB_LOCAL)
ffffffff8176be40-ffffffff8176beae: virt_efi_set_variable_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff8178a110)
Location: drivers/firmware/efi/runtime-wrappers.c:185
Inline: True
```
**Symbols:**

```
ffffffff8178a110-ffffffff8178a224: virt_efi_set_variable_nonblocking.part.6 (STB_LOCAL)
ffffffff8178a290-ffffffff8178a2f0: virt_efi_set_variable_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81800630)
Location: drivers/firmware/efi/runtime-wrappers.c:185
Inline: True
```
**Symbols:**

```
ffffffff81800630-ffffffff81800769: virt_efi_set_variable_nonblocking.part.5 (STB_LOCAL)
ffffffff818007d0-ffffffff81800830: virt_efi_set_variable_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81849c20)
Location: drivers/firmware/efi/runtime-wrappers.c:185
Inline: True
```
**Symbols:**

```
ffffffff81849c20-ffffffff81849d1a: virt_efi_set_variable_nonblocking.part.5 (STB_LOCAL)
ffffffff81849d80-ffffffff81849de0: virt_efi_set_variable_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81876f70)
Location: drivers/firmware/efi/runtime-wrappers.c:334
Inline: True
```
**Symbols:**

```
ffffffff81876f70-ffffffff8187708a: virt_efi_set_variable_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff818bb400)
Location: drivers/firmware/efi/runtime-wrappers.c:346
Inline: True
```
**Symbols:**

```
ffffffff818bb400-ffffffff818bb51d: virt_efi_set_variable_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff818edea0)
Location: drivers/firmware/efi/runtime-wrappers.c:346
Inline: True
```
**Symbols:**

```
ffffffff818edea0-ffffffff818edfbd: virt_efi_set_variable_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff819c1930)
Location: drivers/firmware/efi/runtime-wrappers.c:346
Inline: True
```
**Symbols:**

```
ffffffff819c1930-ffffffff819c1a29: virt_efi_set_variable_nonblocking.part.0 (STB_LOCAL)
ffffffff819c1a30-ffffffff819c1a8e: virt_efi_set_variable_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff819c2660)
Location: drivers/firmware/efi/runtime-wrappers.c:346
Inline: True
```
**Symbols:**

```
ffffffff819c2660-ffffffff819c273e: virt_efi_set_variable_nonblocking.part.0 (STB_LOCAL)
ffffffff819c2740-ffffffff819c279e: virt_efi_set_variable_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff819a6ae0)
Location: drivers/firmware/efi/runtime-wrappers.c:346
Inline: True
```
**Symbols:**

```
ffffffff819a6ae0-ffffffff819a6bd3: virt_efi_set_variable_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81a53e80)
Location: drivers/firmware/efi/runtime-wrappers.c:346
Inline: True
```
**Symbols:**

```
ffffffff81a53e80-ffffffff81a53f73: virt_efi_set_variable_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81bc3300)
Location: drivers/firmware/efi/runtime-wrappers.c:346
Inline: True
```
**Symbols:**

```
ffffffff81bc3300-ffffffff81bc33fe: virt_efi_set_variable_nonblocking.part.0 (STB_LOCAL)
ffffffff81bc3400-ffffffff81bc346b: virt_efi_set_variable_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81d67ee0)
Location: drivers/firmware/efi/runtime-wrappers.c:348
Inline: True
```
**Symbols:**

```
ffffffff81d67ee0-ffffffff81d67fde: virt_efi_set_variable_nonblocking.part.0 (STB_LOCAL)
ffffffff81d67ff0-ffffffff81d6805b: virt_efi_set_variable_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81dd3140)
Location: drivers/firmware/efi/runtime-wrappers.c:348
Inline: True
```
**Symbols:**

```
ffffffff81dd3020-ffffffff81dd312c: virt_efi_set_variable_nonblocking.part.0 (STB_LOCAL)
ffffffff8212b434-ffffffff8212b450: virt_efi_set_variable_nonblocking.part.0.cold (STB_LOCAL)
ffffffff81dd3140-ffffffff81dd31ab: virt_efi_set_variable_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffff800010b60d40)
Location: drivers/firmware/efi/runtime-wrappers.c:346
Inline: True
```
**Symbols:**

```
ffff800010b60d40-ffff800010b60e28: virt_efi_set_variable_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (c0c40110)
Location: drivers/firmware/efi/runtime-wrappers.c:346
Inline: True
```
**Symbols:**

```
c0c40110-c0c401b8: virt_efi_set_variable_nonblocking (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff8188fa80)
Location: drivers/firmware/efi/runtime-wrappers.c:346
Inline: True
```
**Symbols:**

```
ffffffff8188fa80-ffffffff8188fb9d: virt_efi_set_variable_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81848530)
Location: drivers/firmware/efi/runtime-wrappers.c:346
Inline: True
```
**Symbols:**

```
ffffffff81848530-ffffffff81848649: virt_efi_set_variable_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff818e2d00)
Location: drivers/firmware/efi/runtime-wrappers.c:346
Inline: True
```
**Symbols:**

```
ffffffff818e2d00-ffffffff818e2e1d: virt_efi_set_variable_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_set_variable_nonblocking(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff818ff920)
Location: drivers/firmware/efi/runtime-wrappers.c:346
Inline: True
```
**Symbols:**

```
ffffffff818ff920-ffffffff818ffa54: virt_efi_set_variable_nonblocking (STB_LOCAL)
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
