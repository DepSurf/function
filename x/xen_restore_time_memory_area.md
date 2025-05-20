# Function: <code>xen_restore_time_memory_area</code>

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
void xen_restore_time_memory_area();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8101bbe0)
Location: arch/x86/xen/time.c:394
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff8101bbe0-ffffffff8101bc41: xen_restore_time_memory_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void xen_restore_time_memory_area();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/time.c (0)
Location: arch/x86/xen/time.c:394
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff8101c608-ffffffff8101c61b: xen_restore_time_memory_area.cold.7 (STB_LOCAL)
ffffffff8101c5a0-ffffffff8101c5f5: xen_restore_time_memory_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void xen_restore_time_memory_area();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/time.c (0)
Location: arch/x86/xen/time.c:402
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff8101c15c-ffffffff8101c16f: xen_restore_time_memory_area.cold.7 (STB_LOCAL)
ffffffff8101c0d0-ffffffff8101c149: xen_restore_time_memory_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void xen_restore_time_memory_area();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/time.c (0)
Location: arch/x86/xen/time.c:402
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff8101dcbc-ffffffff8101dccf: xen_restore_time_memory_area.cold (STB_LOCAL)
ffffffff8101db40-ffffffff8101dbb9: xen_restore_time_memory_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void xen_restore_time_memory_area();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/time.c (0)
Location: arch/x86/xen/time.c:402
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff8101e636-ffffffff8101e649: xen_restore_time_memory_area.cold (STB_LOCAL)
ffffffff8101e4e0-ffffffff8101e559: xen_restore_time_memory_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void xen_restore_time_memory_area();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/time.c (0)
Location: arch/x86/xen/time.c:409
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff81020bb1-ffffffff81020bc4: xen_restore_time_memory_area.cold (STB_LOCAL)
ffffffff81020990-ffffffff81020a07: xen_restore_time_memory_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void xen_restore_time_memory_area();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/time.c (0)
Location: arch/x86/xen/time.c:410
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff81bd289e-ffffffff81bd28b1: xen_restore_time_memory_area.cold (STB_LOCAL)
ffffffff810213d0-ffffffff81021447: xen_restore_time_memory_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void xen_restore_time_memory_area();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/time.c (0)
Location: arch/x86/xen/time.c:405
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff81bc4a3e-ffffffff81bc4a4f: xen_restore_time_memory_area.cold (STB_LOCAL)
ffffffff81023770-ffffffff810237e9: xen_restore_time_memory_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void xen_restore_time_memory_area();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/time.c (0)
Location: arch/x86/xen/time.c:405
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff81c970bf-ffffffff81c970d0: xen_restore_time_memory_area.cold (STB_LOCAL)
ffffffff81027a10-ffffffff81027a89: xen_restore_time_memory_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void xen_restore_time_memory_area();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/time.c (0)
Location: arch/x86/xen/time.c:405
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff81e464d2-ffffffff81e464e3: xen_restore_time_memory_area.cold (STB_LOCAL)
ffffffff8102be00-ffffffff8102beac: xen_restore_time_memory_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_restore_time_memory_area();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff81032ce0)
Location: arch/x86/xen/time.c:405
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff81032ce0-ffffffff81032d96: xen_restore_time_memory_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_restore_time_memory_area();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff81032c80)
Location: arch/x86/xen/time.c:413
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff81032c80-ffffffff81032d36: xen_restore_time_memory_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_restore_time_memory_area();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff81038f70)
Location: arch/x86/xen/time.c:413
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff81038f70-ffffffff81039026: xen_restore_time_memory_area (STB_GLOBAL)
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
void xen_restore_time_memory_area();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/time.c (0)
Location: arch/x86/xen/time.c:402
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff8101e646-ffffffff8101e659: xen_restore_time_memory_area.cold (STB_LOCAL)
ffffffff8101e4f0-ffffffff8101e569: xen_restore_time_memory_area (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void xen_restore_time_memory_area();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/time.c (0)
Location: arch/x86/xen/time.c:402
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff8101e5f6-ffffffff8101e609: xen_restore_time_memory_area.cold (STB_LOCAL)
ffffffff8101e4a0-ffffffff8101e519: xen_restore_time_memory_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void xen_restore_time_memory_area();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/time.c (0)
Location: arch/x86/xen/time.c:402
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff8101e84a-ffffffff8101e85d: xen_restore_time_memory_area.cold (STB_LOCAL)
ffffffff8101e700-ffffffff8101e76d: xen_restore_time_memory_area (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
