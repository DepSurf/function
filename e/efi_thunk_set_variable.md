# Function: <code>efi_thunk_set_variable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
efi_status_t efi_thunk_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff81079390)
Location: arch/x86/platform/efi/efi_64.c:487
Inline: False
```
**Symbols:**

```
ffffffff81079390-ffffffff810794a7: efi_thunk_set_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
efi_status_t efi_thunk_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff8107ac30)
Location: arch/x86/platform/efi/efi_64.c:602
Inline: False
```
**Symbols:**

```
ffffffff8107ac30-ffffffff8107adb5: efi_thunk_set_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
efi_status_t efi_thunk_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff8107ec90)
Location: arch/x86/platform/efi/efi_64.c:633
Inline: False
```
**Symbols:**

```
ffffffff8107ec90-ffffffff8107ef4c: efi_thunk_set_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
efi_status_t efi_thunk_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff8107d250)
Location: arch/x86/platform/efi/efi_64.c:764
Inline: False
```
**Symbols:**

```
ffffffff8107d250-ffffffff8107d4dc: efi_thunk_set_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
efi_status_t efi_thunk_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff81083e70)
Location: arch/x86/platform/efi/efi_64.c:791
Inline: False
```
**Symbols:**

```
ffffffff81083e70-ffffffff81084111: efi_thunk_set_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
efi_status_t efi_thunk_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff81086a40)
Location: arch/x86/platform/efi/efi_64.c:798
Inline: False
```
**Symbols:**

```
ffffffff81086a40-ffffffff81086c98: efi_thunk_set_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
efi_status_t efi_thunk_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff8108dee0)
Location: arch/x86/platform/efi/efi_64.c:812
Inline: False
```
**Symbols:**

```
ffffffff8108dee0-ffffffff8108e183: efi_thunk_set_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
efi_status_t efi_thunk_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (0)
Location: arch/x86/platform/efi/efi_64.c:815
Inline: False
```
**Symbols:**

```
ffffffff81091d80-ffffffff8109200c: efi_thunk_set_variable (STB_LOCAL)
ffffffff8109301b-ffffffff81093054: efi_thunk_set_variable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
efi_status_t efi_thunk_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff81092bb0)
Location: arch/x86/platform/efi/efi_64.c:820
Inline: False
```
**Symbols:**

```
ffffffff81092bb0-ffffffff81092ea3: efi_thunk_set_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
efi_status_t efi_thunk_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff810987f0)
Location: arch/x86/platform/efi/efi_64.c:633
Inline: False
```
**Symbols:**

```
ffffffff810987f0-ffffffff81098b86: efi_thunk_set_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
efi_status_t efi_thunk_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff81097940)
Location: arch/x86/platform/efi/efi_64.c:605
Inline: False
```
**Symbols:**

```
ffffffff81097940-ffffffff81097cbb: efi_thunk_set_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
efi_status_t efi_thunk_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff81098180)
Location: arch/x86/platform/efi/efi_64.c:608
Inline: False
```
**Symbols:**

```
ffffffff81098180-ffffffff810984d9: efi_thunk_set_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
efi_status_t efi_thunk_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff810a8150)
Location: arch/x86/platform/efi/efi_64.c:608
Inline: False
```
**Symbols:**

```
ffffffff810a8150-ffffffff810a84a9: efi_thunk_set_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
efi_status_t efi_thunk_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff810bd6b0)
Location: arch/x86/platform/efi/efi_64.c:609
Inline: False
```
**Symbols:**

```
ffffffff810bd6b0-ffffffff810bda76: efi_thunk_set_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
efi_status_t efi_thunk_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff810d8ce0)
Location: arch/x86/platform/efi/efi_64.c:617
Inline: False
```
**Symbols:**

```
ffffffff810d8ce0-ffffffff810d90a6: efi_thunk_set_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
efi_status_t efi_thunk_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff810e4270)
Location: arch/x86/platform/efi/efi_64.c:623
Inline: False
```
**Symbols:**

```
ffffffff810e4270-ffffffff810e4636: efi_thunk_set_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
efi_status_t efi_thunk_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff810ec930)
Location: arch/x86/platform/efi/efi_64.c:638
Inline: False
```
**Symbols:**

```
ffffffff810ec930-ffffffff810ecc34: efi_thunk_set_variable (STB_LOCAL)
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
efi_status_t efi_thunk_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff81091b70)
Location: arch/x86/platform/efi/efi_64.c:820
Inline: False
```
**Symbols:**

```
ffffffff81091b70-ffffffff81091e63: efi_thunk_set_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
efi_status_t efi_thunk_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff81080610)
Location: arch/x86/platform/efi/efi_64.c:820
Inline: False
```
**Symbols:**

```
ffffffff81080610-ffffffff81080903: efi_thunk_set_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
efi_status_t efi_thunk_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff81091b20)
Location: arch/x86/platform/efi/efi_64.c:820
Inline: False
```
**Symbols:**

```
ffffffff81091b20-ffffffff81091e13: efi_thunk_set_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
efi_status_t efi_thunk_set_variable(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff81093fb0)
Location: arch/x86/platform/efi/efi_64.c:820
Inline: False
```
**Symbols:**

```
ffffffff81093fb0-ffffffff810942c1: efi_thunk_set_variable (STB_LOCAL)
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
