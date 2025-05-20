# Function: <code>efi_thunk_get_variable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
efi_status_t efi_thunk_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff810795b0)
Location: arch/x86/platform/efi/efi_64.c:467
Inline: False
```
**Symbols:**

```
ffffffff810795b0-ffffffff810796e3: efi_thunk_get_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
efi_status_t efi_thunk_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff8107b0b0)
Location: arch/x86/platform/efi/efi_64.c:582
Inline: False
```
**Symbols:**

```
ffffffff8107b0b0-ffffffff8107b286: efi_thunk_get_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
efi_status_t efi_thunk_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff8107f380)
Location: arch/x86/platform/efi/efi_64.c:613
Inline: False
```
**Symbols:**

```
ffffffff8107f380-ffffffff8107f72f: efi_thunk_get_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
efi_status_t efi_thunk_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff8107d8e0)
Location: arch/x86/platform/efi/efi_64.c:744
Inline: False
```
**Symbols:**

```
ffffffff8107d8e0-ffffffff8107dc46: efi_thunk_get_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
efi_status_t efi_thunk_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff81084120)
Location: arch/x86/platform/efi/efi_64.c:771
Inline: False
```
**Symbols:**

```
ffffffff81084120-ffffffff8108449b: efi_thunk_get_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
efi_status_t efi_thunk_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff81086eb0)
Location: arch/x86/platform/efi/efi_64.c:778
Inline: False
```
**Symbols:**

```
ffffffff81086eb0-ffffffff810871d8: efi_thunk_get_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
efi_status_t efi_thunk_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff8108e400)
Location: arch/x86/platform/efi/efi_64.c:787
Inline: False
```
**Symbols:**

```
ffffffff8108e400-ffffffff8108e769: efi_thunk_get_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
efi_status_t efi_thunk_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (0)
Location: arch/x86/platform/efi/efi_64.c:790
Inline: False
```
**Symbols:**

```
ffffffff81092270-ffffffff810925c2: efi_thunk_get_variable (STB_LOCAL)
ffffffff8109308d-ffffffff810930ec: efi_thunk_get_variable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
efi_status_t efi_thunk_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff810931a0)
Location: arch/x86/platform/efi/efi_64.c:788
Inline: False
```
**Symbols:**

```
ffffffff810931a0-ffffffff810935bd: efi_thunk_get_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
efi_status_t efi_thunk_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff81098ec0)
Location: arch/x86/platform/efi/efi_64.c:601
Inline: False
```
**Symbols:**

```
ffffffff81098ec0-ffffffff81099317: efi_thunk_get_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
efi_status_t efi_thunk_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff81097fd0)
Location: arch/x86/platform/efi/efi_64.c:573
Inline: False
```
**Symbols:**

```
ffffffff81097fd0-ffffffff8109840f: efi_thunk_get_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
efi_status_t efi_thunk_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff810987e0)
Location: arch/x86/platform/efi/efi_64.c:576
Inline: False
```
**Symbols:**

```
ffffffff810987e0-ffffffff81098c13: efi_thunk_get_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
efi_status_t efi_thunk_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff810a87b0)
Location: arch/x86/platform/efi/efi_64.c:576
Inline: False
```
**Symbols:**

```
ffffffff810a87b0-ffffffff810a8be3: efi_thunk_get_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
efi_status_t efi_thunk_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff810bde10)
Location: arch/x86/platform/efi/efi_64.c:577
Inline: False
```
**Symbols:**

```
ffffffff810bde10-ffffffff810be2dd: efi_thunk_get_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
efi_status_t efi_thunk_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff810d9460)
Location: arch/x86/platform/efi/efi_64.c:585
Inline: False
```
**Symbols:**

```
ffffffff810d9460-ffffffff810d992d: efi_thunk_get_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
efi_status_t efi_thunk_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff810e49f0)
Location: arch/x86/platform/efi/efi_64.c:591
Inline: False
```
**Symbols:**

```
ffffffff810e49f0-ffffffff810e4ebd: efi_thunk_get_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
efi_status_t efi_thunk_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff810ecf20)
Location: arch/x86/platform/efi/efi_64.c:606
Inline: False
```
**Symbols:**

```
ffffffff810ecf20-ffffffff810ed324: efi_thunk_get_variable (STB_LOCAL)
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
efi_status_t efi_thunk_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff81092160)
Location: arch/x86/platform/efi/efi_64.c:788
Inline: False
```
**Symbols:**

```
ffffffff81092160-ffffffff8109257d: efi_thunk_get_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
efi_status_t efi_thunk_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff81080c00)
Location: arch/x86/platform/efi/efi_64.c:788
Inline: False
```
**Symbols:**

```
ffffffff81080c00-ffffffff8108101d: efi_thunk_get_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
efi_status_t efi_thunk_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff81092110)
Location: arch/x86/platform/efi/efi_64.c:788
Inline: False
```
**Symbols:**

```
ffffffff81092110-ffffffff8109252d: efi_thunk_get_variable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
efi_status_t efi_thunk_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff810945d0)
Location: arch/x86/platform/efi/efi_64.c:788
Inline: False
```
**Symbols:**

```
ffffffff810945d0-ffffffff81094a0a: efi_thunk_get_variable (STB_LOCAL)
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
