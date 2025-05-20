# Function: <code>efi_thunk_query_variable_info_nonblocking</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
efi_status_t efi_thunk_query_variable_info_nonblocking(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff8108d410)
Location: arch/x86/platform/efi/efi_64.c:954
Inline: True
```
**Symbols:**

```
ffffffff8108d410-ffffffff8108d694: efi_thunk_query_variable_info_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t efi_thunk_query_variable_info_nonblocking(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff810912ec)
Location: arch/x86/platform/efi/efi_64.c:957
Inline: True
```
**Symbols:**

```
ffffffff810912b0-ffffffff81091539: efi_thunk_query_variable_info_nonblocking (STB_LOCAL)
ffffffff81092f4a-ffffffff81092f83: efi_thunk_query_variable_info_nonblocking.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
efi_status_t efi_thunk_query_variable_info_nonblocking(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff81091ff0)
Location: arch/x86/platform/efi/efi_64.c:982
Inline: True
```
**Symbols:**

```
ffffffff81091ff0-ffffffff810922ab: efi_thunk_query_variable_info_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t efi_thunk_query_variable_info_nonblocking(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff81097c50)
Location: arch/x86/platform/efi/efi_64.c:784
Inline: True
```
**Symbols:**

```
ffffffff81097c50-ffffffff81097f3f: efi_thunk_query_variable_info_nonblocking.part.0 (STB_LOCAL)
ffffffff81097f40-ffffffff81097f67: efi_thunk_query_variable_info_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t efi_thunk_query_variable_info_nonblocking(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff81096e10)
Location: arch/x86/platform/efi/efi_64.c:756
Inline: True
```
**Symbols:**

```
ffffffff81096e10-ffffffff810970d7: efi_thunk_query_variable_info_nonblocking.part.0 (STB_LOCAL)
ffffffff810970e0-ffffffff81097107: efi_thunk_query_variable_info_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t efi_thunk_query_variable_info_nonblocking(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff81097680)
Location: arch/x86/platform/efi/efi_64.c:759
Inline: True
```
**Symbols:**

```
ffffffff81097680-ffffffff81097956: efi_thunk_query_variable_info_nonblocking.part.0 (STB_LOCAL)
ffffffff81097960-ffffffff81097987: efi_thunk_query_variable_info_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t efi_thunk_query_variable_info_nonblocking(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff810a7650)
Location: arch/x86/platform/efi/efi_64.c:759
Inline: True
```
**Symbols:**

```
ffffffff810a7650-ffffffff810a7926: efi_thunk_query_variable_info_nonblocking.part.0 (STB_LOCAL)
ffffffff810a7930-ffffffff810a7957: efi_thunk_query_variable_info_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t efi_thunk_query_variable_info_nonblocking(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff810bc9d0)
Location: arch/x86/platform/efi/efi_64.c:760
Inline: True
```
**Symbols:**

```
ffffffff810bc9d0-ffffffff810bcd1f: efi_thunk_query_variable_info_nonblocking.part.0 (STB_LOCAL)
ffffffff810bcd20-ffffffff810bcd5f: efi_thunk_query_variable_info_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t efi_thunk_query_variable_info_nonblocking(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff810d7fa0)
Location: arch/x86/platform/efi/efi_64.c:768
Inline: True
```
**Symbols:**

```
ffffffff810d7fa0-ffffffff810d82ef: efi_thunk_query_variable_info_nonblocking.part.0 (STB_LOCAL)
ffffffff810d8300-ffffffff810d833f: efi_thunk_query_variable_info_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t efi_thunk_query_variable_info_nonblocking(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff810e3530)
Location: arch/x86/platform/efi/efi_64.c:774
Inline: True
```
**Symbols:**

```
ffffffff810e3530-ffffffff810e387f: efi_thunk_query_variable_info_nonblocking.part.0 (STB_LOCAL)
ffffffff810e3890-ffffffff810e38cf: efi_thunk_query_variable_info_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t efi_thunk_query_variable_info_nonblocking(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff810ebeb0)
Location: arch/x86/platform/efi/efi_64.c:789
Inline: True
```
**Symbols:**

```
ffffffff810ebeb0-ffffffff810ec145: efi_thunk_query_variable_info_nonblocking.part.0 (STB_LOCAL)
ffffffff810ec160-ffffffff810ec19f: efi_thunk_query_variable_info_nonblocking (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
efi_status_t efi_thunk_query_variable_info_nonblocking(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff81090fb0)
Location: arch/x86/platform/efi/efi_64.c:982
Inline: True
```
**Symbols:**

```
ffffffff81090fb0-ffffffff8109126b: efi_thunk_query_variable_info_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
efi_status_t efi_thunk_query_variable_info_nonblocking(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff8107fa60)
Location: arch/x86/platform/efi/efi_64.c:982
Inline: True
```
**Symbols:**

```
ffffffff8107fa60-ffffffff8107fd23: efi_thunk_query_variable_info_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
efi_status_t efi_thunk_query_variable_info_nonblocking(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff81090f60)
Location: arch/x86/platform/efi/efi_64.c:982
Inline: True
```
**Symbols:**

```
ffffffff81090f60-ffffffff8109121b: efi_thunk_query_variable_info_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
efi_status_t efi_thunk_query_variable_info_nonblocking(u32 attr, u64 *storage_space, u64 *remaining_space, u64 *max_variable_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff81093350)
Location: arch/x86/platform/efi/efi_64.c:982
Inline: True
```
**Symbols:**

```
ffffffff81093350-ffffffff81093629: efi_thunk_query_variable_info_nonblocking (STB_LOCAL)
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
