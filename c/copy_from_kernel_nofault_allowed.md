# Function: <code>copy_from_kernel_nofault_allowed</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool copy_from_kernel_nofault_allowed(const void *unsafe_src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/maccess.c (ffffffff8108bbc0)
Location: arch/x86/mm/maccess.c:12
Inline: False
Direct callers:
  - mm/maccess.c:strncpy_from_kernel_nofault
```
**Symbols:**

```
ffffffff8108bbc0-ffffffff8108bc16: copy_from_kernel_nofault_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool copy_from_kernel_nofault_allowed(const void *unsafe_src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/maccess.c (ffffffff8108bbe0)
Location: arch/x86/mm/maccess.c:12
Inline: False
Direct callers:
  - mm/maccess.c:strncpy_from_kernel_nofault
```
**Symbols:**

```
ffffffff8108bbe0-ffffffff8108bc36: copy_from_kernel_nofault_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool copy_from_kernel_nofault_allowed(const void *unsafe_src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/maccess.c (ffffffff8108c7f0)
Location: arch/x86/mm/maccess.c:12
Inline: False
Direct callers:
  - mm/maccess.c:strncpy_from_kernel_nofault
```
**Symbols:**

```
ffffffff8108c7f0-ffffffff8108c834: copy_from_kernel_nofault_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool copy_from_kernel_nofault_allowed(const void *unsafe_src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/maccess.c (ffffffff812a3d50)
Location: arch/x86/mm/maccess.c:12
Inline: False
Direct callers:
  - mm/maccess.c:strncpy_from_kernel_nofault
```
**Symbols:**

```
ffffffff81ca1219-ffffffff81ca124b: copy_from_kernel_nofault_allowed.cold (STB_LOCAL)
ffffffff8109c030-ffffffff8109c092: copy_from_kernel_nofault_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool copy_from_kernel_nofault_allowed(const void *unsafe_src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/maccess.c (ffffffff812fbda0)
Location: arch/x86/mm/maccess.c:7
Inline: False
Direct callers:
  - mm/maccess.c:strncpy_from_kernel_nofault
```
**Symbols:**

```
ffffffff81e50825-ffffffff81e50857: copy_from_kernel_nofault_allowed.cold (STB_LOCAL)
ffffffff810af620-ffffffff810af698: copy_from_kernel_nofault_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool copy_from_kernel_nofault_allowed(const void *unsafe_src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/maccess.c (ffffffff81365fa0)
Location: arch/x86/mm/maccess.c:7
Inline: False
Direct callers:
  - mm/maccess.c:strncpy_from_kernel_nofault
```
**Symbols:**

```
ffffffff82054caa-ffffffff82054cdc: copy_from_kernel_nofault_allowed.cold (STB_LOCAL)
ffffffff810c9ab0-ffffffff810c9b28: copy_from_kernel_nofault_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool copy_from_kernel_nofault_allowed(const void *unsafe_src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/maccess.c (ffffffff81398440)
Location: arch/x86/mm/maccess.c:7
Inline: False
Direct callers:
  - mm/maccess.c:strncpy_from_kernel_nofault
```
**Symbols:**

```
ffffffff820d327f-ffffffff820d32b2: copy_from_kernel_nofault_allowed.cold (STB_LOCAL)
ffffffff810cd120-ffffffff810cd194: copy_from_kernel_nofault_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool copy_from_kernel_nofault_allowed(const void *unsafe_src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/maccess.c (ffffffff813c2240)
Location: arch/x86/mm/maccess.c:9
Inline: False
Direct callers:
  - mm/maccess.c:strncpy_from_kernel_nofault
```
**Symbols:**

```
ffffffff821ae0ed-ffffffff821ae120: copy_from_kernel_nofault_allowed.cold (STB_LOCAL)
ffffffff810d57f0-ffffffff810d5880: copy_from_kernel_nofault_allowed (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
