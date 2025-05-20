# Function: <code>virt_efi_query_variable_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_query_variable_info(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff816d5130)
Location: drivers/firmware/efi/runtime-wrappers.c:215
Inline: True
```
**Symbols:**

```
ffffffff816d5130-ffffffff816d51c4: virt_efi_query_variable_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_query_variable_info(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81738870)
Location: drivers/firmware/efi/runtime-wrappers.c:192
Inline: True
```
**Symbols:**

```
ffffffff81738870-ffffffff81738998: virt_efi_query_variable_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t virt_efi_query_variable_info(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff8176b900)
Location: drivers/firmware/efi/runtime-wrappers.c:201
Inline: True
```
**Symbols:**

```
ffffffff8176b900-ffffffff8176ba04: virt_efi_query_variable_info.part.4 (STB_LOCAL)
ffffffff8176ba80-ffffffff8176baeb: virt_efi_query_variable_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t virt_efi_query_variable_info(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81789e00)
Location: drivers/firmware/efi/runtime-wrappers.c:201
Inline: True
```
**Symbols:**

```
ffffffff81789cf0-ffffffff81789df4: virt_efi_query_variable_info.part.4 (STB_LOCAL)
ffffffff81789e00-ffffffff81789e6a: virt_efi_query_variable_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t virt_efi_query_variable_info(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff818002d0)
Location: drivers/firmware/efi/runtime-wrappers.c:201
Inline: True
```
**Symbols:**

```
ffffffff818001a0-ffffffff818002cc: virt_efi_query_variable_info.part.3 (STB_LOCAL)
ffffffff818002d0-ffffffff8180033a: virt_efi_query_variable_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t virt_efi_query_variable_info(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81849950)
Location: drivers/firmware/efi/runtime-wrappers.c:201
Inline: True
```
**Symbols:**

```
ffffffff81849860-ffffffff81849947: virt_efi_query_variable_info.part.3 (STB_LOCAL)
ffffffff81849950-ffffffff818499b9: virt_efi_query_variable_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_query_variable_info(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:350
Inline: False
```
**Symbols:**

```
ffffffff81875ac0-ffffffff81875c11: virt_efi_query_variable_info (STB_LOCAL)
ffffffff818771a3-ffffffff818771da: virt_efi_query_variable_info.cold.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_query_variable_info(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:362
Inline: False
```
**Symbols:**

```
ffffffff818b9cc0-ffffffff818b9e12: virt_efi_query_variable_info (STB_LOCAL)
ffffffff818bb633-ffffffff818bb66a: virt_efi_query_variable_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_query_variable_info(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:362
Inline: False
```
**Symbols:**

```
ffffffff818ec760-ffffffff818ec8b2: virt_efi_query_variable_info (STB_LOCAL)
ffffffff818ee0d3-ffffffff818ee10a: virt_efi_query_variable_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_query_variable_info(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:362
Inline: False
```
**Symbols:**

```
ffffffff819c07c0-ffffffff819c0912: virt_efi_query_variable_info (STB_LOCAL)
ffffffff819c1cb6-ffffffff819c1ced: virt_efi_query_variable_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_query_variable_info(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:362
Inline: False
```
**Symbols:**

```
ffffffff819c11e0-ffffffff819c1332: virt_efi_query_variable_info (STB_LOCAL)
ffffffff81c2ca8d-ffffffff81c2cac4: virt_efi_query_variable_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_query_variable_info(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:362
Inline: False
```
**Symbols:**

```
ffffffff819a6040-ffffffff819a6192: virt_efi_query_variable_info (STB_LOCAL)
ffffffff81c1ee05-ffffffff81c1ee3c: virt_efi_query_variable_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_query_variable_info(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:362
Inline: False
```
**Symbols:**

```
ffffffff81a52be0-ffffffff81a52d3e: virt_efi_query_variable_info (STB_LOCAL)
ffffffff81d30276-ffffffff81d302b3: virt_efi_query_variable_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_query_variable_info(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:362
Inline: False
```
**Symbols:**

```
ffffffff81bc1b00-ffffffff81bc1c6a: virt_efi_query_variable_info (STB_LOCAL)
ffffffff81efc630-ffffffff81efc66d: virt_efi_query_variable_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_query_variable_info(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:364
Inline: False
```
**Symbols:**

```
ffffffff81d664f0-ffffffff81d666a2: virt_efi_query_variable_info (STB_LOCAL)
ffffffff820a9ebe-ffffffff820a9ed2: virt_efi_query_variable_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_query_variable_info(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:364
Inline: False
```
**Symbols:**

```
ffffffff81dd1600-ffffffff81dd17b2: virt_efi_query_variable_info (STB_LOCAL)
ffffffff8212b26c-ffffffff8212b280: virt_efi_query_variable_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
efi_status_t virt_efi_query_variable_info(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81e8a340)
Location: drivers/firmware/efi/runtime-wrappers.c:454
Inline: True
```
**Symbols:**

```
ffffffff81e8a340-ffffffff81e8a41c: virt_efi_query_variable_info (STB_LOCAL)
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
efi_status_t virt_efi_query_variable_info(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (ffff800010b5f980)
Location: drivers/firmware/efi/runtime-wrappers.c:362
Inline: False
```
**Symbols:**

```
ffff800010b5f980-ffff800010b5fb1c: virt_efi_query_variable_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
efi_status_t virt_efi_query_variable_info(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (c0c3efc0)
Location: drivers/firmware/efi/runtime-wrappers.c:362
Inline: False
```
**Symbols:**

```
c0c3efc0-c0c3f120: virt_efi_query_variable_info (STB_LOCAL)
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
efi_status_t virt_efi_query_variable_info(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:362
Inline: False
```
**Symbols:**

```
ffffffff8188e340-ffffffff8188e492: virt_efi_query_variable_info (STB_LOCAL)
ffffffff8188fcb3-ffffffff8188fcea: virt_efi_query_variable_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_query_variable_info(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:362
Inline: False
```
**Symbols:**

```
ffffffff81846e60-ffffffff81846fb2: virt_efi_query_variable_info (STB_LOCAL)
ffffffff81848763-ffffffff8184879a: virt_efi_query_variable_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_query_variable_info(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:362
Inline: False
```
**Symbols:**

```
ffffffff818e15c0-ffffffff818e1712: virt_efi_query_variable_info (STB_LOCAL)
ffffffff818e2f33-ffffffff818e2f6a: virt_efi_query_variable_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
efi_status_t virt_efi_query_variable_info(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/runtime-wrappers.c (0)
Location: drivers/firmware/efi/runtime-wrappers.c:362
Inline: False
```
**Symbols:**

```
ffffffff818fe060-ffffffff818fe1b2: virt_efi_query_variable_info (STB_LOCAL)
ffffffff818ffb73-ffffffff818ffbaa: virt_efi_query_variable_info.cold (STB_LOCAL)
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
