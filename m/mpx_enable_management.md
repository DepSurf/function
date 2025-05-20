# Function: <code>mpx_enable_management</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mpx_enable_management();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff81075ba0)
Location: arch/x86/mm/mpx.c:338
Inline: False
Direct callers:
  - kernel/sys.c:SyS_prctl
```
**Symbols:**

```
ffffffff81075ba0-ffffffff81075c30: mpx_enable_management (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mpx_enable_management();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff810770d0)
Location: arch/x86/mm/mpx.c:338
Inline: False
Direct callers:
  - kernel/sys.c:SyS_prctl
```
**Symbols:**

```
ffffffff810770d0-ffffffff81077165: mpx_enable_management (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mpx_enable_management();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff8107ac80)
Location: arch/x86/mm/mpx.c:338
Inline: False
Direct callers:
  - kernel/sys.c:SyS_prctl
```
**Symbols:**

```
ffffffff8107ac80-ffffffff8107ad15: mpx_enable_management (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mpx_enable_management();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff81079490)
Location: arch/x86/mm/mpx.c:339
Inline: False
Direct callers:
  - kernel/sys.c:SyS_prctl
```
**Symbols:**

```
ffffffff81079490-ffffffff81079547: mpx_enable_management (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mpx_enable_management();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff8107f640)
Location: arch/x86/mm/mpx.c:224
Inline: False
Direct callers:
  - kernel/sys.c:SyS_prctl
```
**Symbols:**

```
ffffffff8107f640-ffffffff8107f74a: mpx_enable_management (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int mpx_enable_management();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mpx.c (0)
Location: arch/x86/mm/mpx.c:224
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
**Symbols:**

```
ffffffff81082fa5-ffffffff81082fd8: mpx_enable_management.cold.9 (STB_LOCAL)
ffffffff81082760-ffffffff8108285c: mpx_enable_management (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int mpx_enable_management();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mpx.c (0)
Location: arch/x86/mm/mpx.c:212
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
**Symbols:**

```
ffffffff81089b55-ffffffff81089b88: mpx_enable_management.cold.7 (STB_LOCAL)
ffffffff81089310-ffffffff8108940c: mpx_enable_management (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mpx_enable_management();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mpx.c (0)
Location: arch/x86/mm/mpx.c:212
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
**Symbols:**

```
ffffffff8108d8b0-ffffffff8108d8e4: mpx_enable_management.cold (STB_LOCAL)
ffffffff8108d450-ffffffff8108d555: mpx_enable_management (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int mpx_enable_management();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mpx.c (0)
Location: arch/x86/mm/mpx.c:212
Inline: False
```
**Symbols:**

```
ffffffff8108e510-ffffffff8108e544: mpx_enable_management.cold (STB_LOCAL)
ffffffff8108e0b0-ffffffff8108e1b5: mpx_enable_management (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
int mpx_enable_management();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mpx.c (0)
Location: arch/x86/mm/mpx.c:212
Inline: False
```
**Symbols:**

```
ffffffff8108d4d0-ffffffff8108d504: mpx_enable_management.cold (STB_LOCAL)
ffffffff8108d070-ffffffff8108d175: mpx_enable_management (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int mpx_enable_management();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mpx.c (0)
Location: arch/x86/mm/mpx.c:212
Inline: False
```
**Symbols:**

```
ffffffff8107c000-ffffffff8107c034: mpx_enable_management.cold (STB_LOCAL)
ffffffff8107bba0-ffffffff8107bca5: mpx_enable_management (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int mpx_enable_management();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mpx.c (0)
Location: arch/x86/mm/mpx.c:212
Inline: False
```
**Symbols:**

```
ffffffff8108d480-ffffffff8108d4b4: mpx_enable_management.cold (STB_LOCAL)
ffffffff8108d020-ffffffff8108d125: mpx_enable_management (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int mpx_enable_management();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mpx.c (0)
Location: arch/x86/mm/mpx.c:212
Inline: False
```
**Symbols:**

```
ffffffff8108f840-ffffffff8108f874: mpx_enable_management.cold (STB_LOCAL)
ffffffff8108f3c0-ffffffff8108f4c5: mpx_enable_management (STB_GLOBAL)
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
