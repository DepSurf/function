# Function: <code>efi_thunk_set_variable_nonblocking</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
efi_status_t efi_thunk_set_variable_nonblocking(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff8108dc10)
Location: arch/x86/platform/efi/efi_64.c:835
Inline: False
```
**Symbols:**

```
ffffffff8108dc10-ffffffff8108dede: efi_thunk_set_variable_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
efi_status_t efi_thunk_set_variable_nonblocking(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (0)
Location: arch/x86/platform/efi/efi_64.c:838
Inline: False
```
**Symbols:**

```
ffffffff81091ac0-ffffffff81091d7f: efi_thunk_set_variable_nonblocking (STB_LOCAL)
ffffffff81092fe2-ffffffff8109301b: efi_thunk_set_variable_nonblocking.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
efi_status_t efi_thunk_set_variable_nonblocking(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff81092870)
Location: arch/x86/platform/efi/efi_64.c:849
Inline: False
```
**Symbols:**

```
ffffffff81092870-ffffffff81092ba4: efi_thunk_set_variable_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
efi_status_t efi_thunk_set_variable_nonblocking(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff81098420)
Location: arch/x86/platform/efi/efi_64.c:662
Inline: False
```
**Symbols:**

```
ffffffff81098420-ffffffff810987e8: efi_thunk_set_variable_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
efi_status_t efi_thunk_set_variable_nonblocking(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff81097590)
Location: arch/x86/platform/efi/efi_64.c:634
Inline: False
```
**Symbols:**

```
ffffffff81097590-ffffffff8109793a: efi_thunk_set_variable_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
efi_status_t efi_thunk_set_variable_nonblocking(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff81097df0)
Location: arch/x86/platform/efi/efi_64.c:637
Inline: False
```
**Symbols:**

```
ffffffff81097df0-ffffffff8109817d: efi_thunk_set_variable_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
efi_status_t efi_thunk_set_variable_nonblocking(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff810a7dc0)
Location: arch/x86/platform/efi/efi_64.c:637
Inline: False
```
**Symbols:**

```
ffffffff810a7dc0-ffffffff810a814d: efi_thunk_set_variable_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
efi_status_t efi_thunk_set_variable_nonblocking(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff810bd2c0)
Location: arch/x86/platform/efi/efi_64.c:638
Inline: False
```
**Symbols:**

```
ffffffff810bd2c0-ffffffff810bd6b0: efi_thunk_set_variable_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
efi_status_t efi_thunk_set_variable_nonblocking(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff810d88e0)
Location: arch/x86/platform/efi/efi_64.c:646
Inline: False
```
**Symbols:**

```
ffffffff810d88e0-ffffffff810d8cd0: efi_thunk_set_variable_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
efi_status_t efi_thunk_set_variable_nonblocking(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff810e3e70)
Location: arch/x86/platform/efi/efi_64.c:652
Inline: False
```
**Symbols:**

```
ffffffff810e3e70-ffffffff810e4260: efi_thunk_set_variable_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
efi_status_t efi_thunk_set_variable_nonblocking(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff810ec5f0)
Location: arch/x86/platform/efi/efi_64.c:667
Inline: False
```
**Symbols:**

```
ffffffff810ec5f0-ffffffff810ec91e: efi_thunk_set_variable_nonblocking (STB_LOCAL)
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
efi_status_t efi_thunk_set_variable_nonblocking(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff81091830)
Location: arch/x86/platform/efi/efi_64.c:849
Inline: False
```
**Symbols:**

```
ffffffff81091830-ffffffff81091b64: efi_thunk_set_variable_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
efi_status_t efi_thunk_set_variable_nonblocking(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff810802f0)
Location: arch/x86/platform/efi/efi_64.c:849
Inline: False
```
**Symbols:**

```
ffffffff810802f0-ffffffff81080610: efi_thunk_set_variable_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
efi_status_t efi_thunk_set_variable_nonblocking(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff810917e0)
Location: arch/x86/platform/efi/efi_64.c:849
Inline: False
```
**Symbols:**

```
ffffffff810917e0-ffffffff81091b14: efi_thunk_set_variable_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
efi_status_t efi_thunk_set_variable_nonblocking(efi_char16_t *name, efi_guid_t *vendor, u32 attr, long unsigned int data_size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff81093c50)
Location: arch/x86/platform/efi/efi_64.c:849
Inline: False
```
**Symbols:**

```
ffffffff81093c50-ffffffff81093fa2: efi_thunk_set_variable_nonblocking (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
