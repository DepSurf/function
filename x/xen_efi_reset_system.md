# Function: <code>xen_efi_reset_system</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void xen_efi_reset_system(int reset_type, efi_status_t status, long unsigned int data_size, efi_char16_t *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/efi.c (ffffffff81568cb0)
Location: drivers/xen/efi.c:268
Inline: True
```
**Symbols:**

```
ffffffff81568cb0-ffffffff81568cde: xen_efi_reset_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void xen_efi_reset_system(int reset_type, efi_status_t status, long unsigned int data_size, efi_char16_t *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/efi.c (ffffffff815cce60)
Location: drivers/xen/efi.c:268
Inline: True
```
**Symbols:**

```
ffffffff815cce60-ffffffff815cce8e: xen_efi_reset_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void xen_efi_reset_system(int reset_type, efi_status_t status, long unsigned int data_size, efi_char16_t *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/efi.c (ffffffff81605570)
Location: drivers/xen/efi.c:268
Inline: True
```
**Symbols:**

```
ffffffff81605570-ffffffff8160559e: xen_efi_reset_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void xen_efi_reset_system(int reset_type, efi_status_t status, long unsigned int data_size, efi_char16_t *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/efi.c (ffffffff81620650)
Location: drivers/xen/efi.c:268
Inline: True
```
**Symbols:**

```
ffffffff81620650-ffffffff8162067e: xen_efi_reset_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void xen_efi_reset_system(int reset_type, efi_status_t status, long unsigned int data_size, efi_char16_t *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/efi.c (ffffffff81653b60)
Location: drivers/xen/efi.c:269
Inline: True
```
**Symbols:**

```
ffffffff81653b60-ffffffff81653b8e: xen_efi_reset_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void xen_efi_reset_system(int reset_type, efi_status_t status, long unsigned int data_size, efi_char16_t *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/efi.c (ffffffff81676100)
Location: drivers/xen/efi.c:258
Inline: True
```
**Symbols:**

```
ffffffff81676100-ffffffff8167612e: xen_efi_reset_system (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void xen_efi_reset_system(int reset_type, efi_status_t status, long unsigned int data_size, efi_char16_t *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/efi.c (ffffffff81726bd0)
Location: drivers/xen/efi.c:258
Inline: True
```
**Symbols:**

```
ffffffff81726bd0-ffffffff81726bfe: xen_efi_reset_system (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void xen_efi_reset_system(int reset_type, efi_status_t status, long unsigned int data_size, efi_char16_t *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/efi.c (ffffffff81743130)
Location: drivers/xen/efi.c:258
Inline: True
```
**Symbols:**

```
ffffffff81743130-ffffffff8174315e: xen_efi_reset_system (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void xen_efi_reset_system(int reset_type, efi_status_t status, long unsigned int data_size, efi_char16_t *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/efi.c (ffffffff81726b20)
Location: drivers/xen/efi.c:258
Inline: True
```
**Symbols:**

```
ffffffff81726b20-ffffffff81726b4e: xen_efi_reset_system (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xen_efi_reset_system(int reset_type, efi_status_t status, long unsigned int data_size, efi_char16_t *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/efi.c (ffffffff817a55c0)
Location: drivers/xen/efi.c:258
Inline: False
```
**Symbols:**

```
ffffffff817a55c0-ffffffff817a55ee: xen_efi_reset_system (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void xen_efi_reset_system(int reset_type, efi_status_t status, long unsigned int data_size, efi_char16_t *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/efi.c (ffffffff818df9f0)
Location: drivers/xen/efi.c:258
Inline: True
```
**Symbols:**

```
ffffffff818df9f0-ffffffff818dfa2a: xen_efi_reset_system (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void xen_efi_reset_system(int reset_type, efi_status_t status, long unsigned int data_size, efi_char16_t *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/efi.c (ffffffff81a33e00)
Location: drivers/xen/efi.c:258
Inline: True
```
**Symbols:**

```
ffffffff81a33e00-ffffffff81a33e3a: xen_efi_reset_system (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void xen_efi_reset_system(int reset_type, efi_status_t status, long unsigned int data_size, efi_char16_t *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/efi.c (ffffffff81a7d6f0)
Location: drivers/xen/efi.c:259
Inline: True
```
**Symbols:**

```
ffffffff81a7d6f0-ffffffff81a7d72a: xen_efi_reset_system (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void xen_efi_reset_system(int reset_type, efi_status_t status, long unsigned int data_size, efi_char16_t *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/efi.c (ffffffff81acfb90)
Location: drivers/xen/efi.c:259
Inline: True
```
**Symbols:**

```
ffffffff81acfb90-ffffffff81acfbca: xen_efi_reset_system (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void xen_efi_reset_system(int reset_type, efi_status_t status, long unsigned int data_size, efi_char16_t *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/efi.c (ffff80001083ee00)
Location: drivers/xen/efi.c:258
Inline: True
```
**Symbols:**

```
ffff80001083ee00-ffff80001083ee58: xen_efi_reset_system (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void xen_efi_reset_system(int reset_type, efi_status_t status, long unsigned int data_size, efi_char16_t *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/efi.c (ffffffff8163bdf0)
Location: drivers/xen/efi.c:258
Inline: True
```
**Symbols:**

```
ffffffff8163bdf0-ffffffff8163be1e: xen_efi_reset_system (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void xen_efi_reset_system(int reset_type, efi_status_t status, long unsigned int data_size, efi_char16_t *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/efi.c (ffffffff81669f40)
Location: drivers/xen/efi.c:258
Inline: True
```
**Symbols:**

```
ffffffff81669f40-ffffffff81669f6e: xen_efi_reset_system (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void xen_efi_reset_system(int reset_type, efi_status_t status, long unsigned int data_size, efi_char16_t *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/efi.c (ffffffff81684500)
Location: drivers/xen/efi.c:258
Inline: True
```
**Symbols:**

```
ffffffff81684500-ffffffff8168452e: xen_efi_reset_system (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
