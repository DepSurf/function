# Function: <code>verify_patch</code>

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
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int verify_patch(u8 family, const u8 *buf, size_t buf_size, u32 *patch_size, bool early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:238
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
```
**Symbols:**

```
ffffffff81054900-ffffffff81054ab6: verify_patch (STB_LOCAL)
ffffffff81055625-ffffffff8105563c: verify_patch.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int verify_patch(u8 family, const u8 *buf, size_t buf_size, u32 *patch_size, bool early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:236
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
```
**Symbols:**

```
ffffffff81057b40-ffffffff81057cf9: verify_patch (STB_LOCAL)
ffffffff81058857-ffffffff8105886e: verify_patch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int verify_patch(u8 family, const u8 *buf, size_t buf_size, u32 *patch_size, bool early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:236
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
```
**Symbols:**

```
ffffffff81058410-ffffffff810585c9: verify_patch (STB_LOCAL)
ffffffff81059127-ffffffff8105913e: verify_patch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int verify_patch(u8 family, const u8 *buf, size_t buf_size, u32 *patch_size, bool early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:236
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:parse_container
```
**Symbols:**

```
ffffffff8105d480-ffffffff8105d643: verify_patch (STB_LOCAL)
ffffffff8105e385-ffffffff8105e39c: verify_patch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int verify_patch(u8 family, const u8 *buf, size_t buf_size, u32 *patch_size, bool early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:235
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:parse_container
```
**Symbols:**

```
ffffffff8105bb20-ffffffff8105bce3: verify_patch (STB_LOCAL)
ffffffff81bd615d-ffffffff81bd6174: verify_patch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int verify_patch(u8 family, const u8 *buf, size_t buf_size, u32 *patch_size, bool early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:235
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
```
**Symbols:**

```
ffffffff8105c4e0-ffffffff8105c6b4: verify_patch (STB_LOCAL)
ffffffff81bc8503-ffffffff81bc851a: verify_patch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int verify_patch(u8 family, const u8 *buf, size_t buf_size, u32 *patch_size, bool early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:235
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
```
**Symbols:**

```
ffffffff81065ba0-ffffffff81065d6e: verify_patch (STB_LOCAL)
ffffffff81c9c3fb-ffffffff81c9c412: verify_patch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int verify_patch(u8 family, const u8 *buf, size_t buf_size, u32 *patch_size, bool early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:235
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
```
**Symbols:**

```
ffffffff810727d0-ffffffff81072988: verify_patch (STB_LOCAL)
ffffffff81e4b72e-ffffffff81e4b742: verify_patch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int verify_patch(u8 family, const u8 *buf, size_t buf_size, u32 *patch_size, bool early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81082720)
Location: arch/x86/kernel/cpu/microcode/amd.c:237
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
```
**Symbols:**

```
ffffffff81082720-ffffffff810828d6: verify_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int verify_patch(u8 family, const u8 *buf, size_t buf_size, u32 *patch_size, bool early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81084af0)
Location: arch/x86/kernel/cpu/microcode/amd.c:235
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
```
**Symbols:**

```
ffffffff81084af0-ffffffff81084c98: verify_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int verify_patch(u8 family, const u8 *buf, size_t buf_size, u32 *patch_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8108bee0)
Location: arch/x86/kernel/cpu/microcode/amd.c:264
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
```
**Symbols:**

```
ffffffff8108bee0-ffffffff8108c091: verify_patch (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int verify_patch(u8 family, const u8 *buf, size_t buf_size, u32 *patch_size, bool early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:236
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
```
**Symbols:**

```
ffffffff81057f90-ffffffff81058149: verify_patch (STB_LOCAL)
ffffffff81058ca7-ffffffff81058cbe: verify_patch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int verify_patch(u8 family, const u8 *buf, size_t buf_size, u32 *patch_size, bool early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:236
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
```
**Symbols:**

```
ffffffff810480b0-ffffffff81048269: verify_patch (STB_LOCAL)
ffffffff81048e79-ffffffff81048e90: verify_patch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int verify_patch(u8 family, const u8 *buf, size_t buf_size, u32 *patch_size, bool early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:236
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
```
**Symbols:**

```
ffffffff810583c0-ffffffff81058579: verify_patch (STB_LOCAL)
ffffffff810590d7-ffffffff810590ee: verify_patch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int verify_patch(u8 family, const u8 *buf, size_t buf_size, u32 *patch_size, bool early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:236
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
```
**Symbols:**

```
ffffffff81059860-ffffffff81059a19: verify_patch (STB_LOCAL)
ffffffff8105a577-ffffffff8105a58e: verify_patch.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool early</code>
</li>
</ul>
</details>
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
