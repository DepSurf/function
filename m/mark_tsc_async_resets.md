# Function: <code>mark_tsc_async_resets</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mark_tsc_async_resets(char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (ffffffff81058b40)
Location: arch/x86/kernel/tsc_sync.c:40
Inline: False
```
**Symbols:**

```
ffffffff81058b40-ffffffff81058b6c: mark_tsc_async_resets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void mark_tsc_async_resets(char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:40
Inline: False
```
**Symbols:**

```
ffffffff8105bf19-ffffffff8105bf34: mark_tsc_async_resets.cold.3 (STB_LOCAL)
ffffffff8105ba60-ffffffff8105ba78: mark_tsc_async_resets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void mark_tsc_async_resets(char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:40
Inline: False
```
**Symbols:**

```
ffffffff81061bf9-ffffffff81061c14: mark_tsc_async_resets.cold.3 (STB_LOCAL)
ffffffff810616e0-ffffffff810616f8: mark_tsc_async_resets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void mark_tsc_async_resets(char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:40
Inline: False
```
**Symbols:**

```
ffffffff81065247-ffffffff81065262: mark_tsc_async_resets.cold (STB_LOCAL)
ffffffff81064df0-ffffffff81064e08: mark_tsc_async_resets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void mark_tsc_async_resets(char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:40
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
```
**Symbols:**

```
ffffffff810658b7-ffffffff810658d2: mark_tsc_async_resets.cold (STB_LOCAL)
ffffffff81065460-ffffffff81065478: mark_tsc_async_resets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void mark_tsc_async_resets(char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:40
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_tsc_check_sync
```
**Symbols:**

```
ffffffff8106c20a-ffffffff8106c225: mark_tsc_async_resets.cold (STB_LOCAL)
ffffffff8106bda0-ffffffff8106bdb8: mark_tsc_async_resets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void mark_tsc_async_resets(char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:40
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_tsc_check_sync
```
**Symbols:**

```
ffffffff81bd6b51-ffffffff81bd6b6c: mark_tsc_async_resets.cold (STB_LOCAL)
ffffffff8106d680-ffffffff8106d698: mark_tsc_async_resets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void mark_tsc_async_resets(char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:40
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
**Symbols:**

```
ffffffff81bc8d2b-ffffffff81bc8d47: mark_tsc_async_resets.cold (STB_LOCAL)
ffffffff8106e0f0-ffffffff8106e103: mark_tsc_async_resets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void mark_tsc_async_resets(char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:41
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
**Symbols:**

```
ffffffff81c9d6e5-ffffffff81c9d714: mark_tsc_async_resets.cold (STB_LOCAL)
ffffffff81079910-ffffffff8107993d: mark_tsc_async_resets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void mark_tsc_async_resets(char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:41
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
**Symbols:**

```
ffffffff81e4cb3d-ffffffff81e4cb6d: mark_tsc_async_resets.cold (STB_LOCAL)
ffffffff810886c0-ffffffff810886fa: mark_tsc_async_resets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void mark_tsc_async_resets(char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:41
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
**Symbols:**

```
ffffffff82053bc4-ffffffff82053bd9: mark_tsc_async_resets.cold (STB_LOCAL)
ffffffff8109c180-ffffffff8109c1cc: mark_tsc_async_resets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void mark_tsc_async_resets(char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:41
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
**Symbols:**

```
ffffffff820d21b5-ffffffff820d21ca: mark_tsc_async_resets.cold (STB_LOCAL)
ffffffff8109f2c0-ffffffff8109f30c: mark_tsc_async_resets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void mark_tsc_async_resets(char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:42
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
**Symbols:**

```
ffffffff821ace19-ffffffff821ace2e: mark_tsc_async_resets.cold (STB_LOCAL)
ffffffff810a6750-ffffffff810a679c: mark_tsc_async_resets (STB_GLOBAL)
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
void mark_tsc_async_resets(char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:40
Inline: False
```
**Symbols:**

```
ffffffff810653a7-ffffffff810653c2: mark_tsc_async_resets.cold (STB_LOCAL)
ffffffff81064f50-ffffffff81064f68: mark_tsc_async_resets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void mark_tsc_async_resets(char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:40
Inline: False
```
**Symbols:**

```
ffffffff810556f7-ffffffff81055712: mark_tsc_async_resets.cold (STB_LOCAL)
ffffffff81055230-ffffffff81055248: mark_tsc_async_resets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void mark_tsc_async_resets(char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:40
Inline: False
```
**Symbols:**

```
ffffffff81065857-ffffffff81065872: mark_tsc_async_resets.cold (STB_LOCAL)
ffffffff81065400-ffffffff81065418: mark_tsc_async_resets (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void mark_tsc_async_resets(char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/kernel/tsc_sync.c:40
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
```
**Symbols:**

```
ffffffff81066e37-ffffffff81066e52: mark_tsc_async_resets.cold (STB_LOCAL)
ffffffff810669e0-ffffffff810669f8: mark_tsc_async_resets (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
