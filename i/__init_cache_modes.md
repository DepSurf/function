# Function: <code>__init_cache_modes</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __init_cache_modes(u64 pat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff8106f6c0)
Location: arch/x86/mm/pat.c:194
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:pat_init
```
**Symbols:**

```
ffffffff8106f6c0-ffffffff8106f76c: __init_cache_modes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __init_cache_modes(u64 pat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff810732f0)
Location: arch/x86/mm/pat.c:194
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:pat_init
```
**Symbols:**

```
ffffffff810732f0-ffffffff8107339c: __init_cache_modes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __init_cache_modes(u64 pat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff810728f0)
Location: arch/x86/mm/pat.c:193
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:init_cache_modes
  - arch/x86/mm/pat.c:init_cache_modes
```
**Symbols:**

```
ffffffff810728f0-ffffffff81072995: __init_cache_modes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __init_cache_modes(u64 pat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81078250)
Location: arch/x86/mm/pat.c:193
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:init_cache_modes
  - arch/x86/mm/pat.c:init_cache_modes
```
**Symbols:**

```
ffffffff81078250-ffffffff810782f5: __init_cache_modes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __init_cache_modes(u64 pat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (0)
Location: arch/x86/mm/pat.c:193
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:init_cache_modes
  - arch/x86/mm/pat.c:init_cache_modes
```
**Symbols:**

```
ffffffff8107adb0-ffffffff8107ae23: __init_cache_modes (STB_LOCAL)
ffffffff8107be13-ffffffff8107be4b: __init_cache_modes.cold.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __init_cache_modes(u64 pat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (0)
Location: arch/x86/mm/pat.c:193
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:init_cache_modes
  - arch/x86/mm/pat.c:init_cache_modes
```
**Symbols:**

```
ffffffff810816f0-ffffffff81081763: __init_cache_modes (STB_LOCAL)
ffffffff81082783-ffffffff810827bb: __init_cache_modes.cold.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __init_cache_modes(u64 pat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (0)
Location: arch/x86/mm/pat.c:194
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:init_cache_modes
  - arch/x86/mm/pat.c:init_cache_modes
```
**Symbols:**

```
ffffffff81085390-ffffffff810853f7: __init_cache_modes (STB_LOCAL)
ffffffff810863e3-ffffffff81086417: __init_cache_modes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __init_cache_modes(u64 pat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (0)
Location: arch/x86/mm/pat.c:194
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:init_cache_modes
  - arch/x86/mm/pat.c:init_cache_modes
```
**Symbols:**

```
ffffffff81086080-ffffffff810860e7: __init_cache_modes (STB_LOCAL)
ffffffff810870d3-ffffffff81087107: __init_cache_modes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void __init_cache_modes(u64 pat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:220
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:pat_init
  - arch/x86/mm/pat/memtype.c:init_cache_modes
  - arch/x86/mm/pat/memtype.c:init_cache_modes
```
**Symbols:**

```
ffffffff8108f730-ffffffff8108f7a0: __init_cache_modes (STB_LOCAL)
ffffffff810907b3-ffffffff810907e7: __init_cache_modes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __init_cache_modes(u64 pat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:220
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:pat_init
  - arch/x86/mm/pat/memtype.c:init_cache_modes
  - arch/x86/mm/pat/memtype.c:init_cache_modes
```
**Symbols:**

```
ffffffff8108f410-ffffffff8108f480: __init_cache_modes (STB_LOCAL)
ffffffff81bd98b0-ffffffff81bd98e4: __init_cache_modes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __init_cache_modes(u64 pat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:220
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:pat_init
  - arch/x86/mm/pat/memtype.c:init_cache_modes
  - arch/x86/mm/pat/memtype.c:init_cache_modes
```
**Symbols:**

```
ffffffff8108ffa0-ffffffff81090010: __init_cache_modes (STB_LOCAL)
ffffffff81bcb918-ffffffff81bcb94c: __init_cache_modes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __init_cache_modes(u64 pat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:220
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:pat_init
  - arch/x86/mm/pat/memtype.c:init_cache_modes
```
**Symbols:**

```
ffffffff8109fbe0-ffffffff8109fc5c: __init_cache_modes (STB_LOCAL)
ffffffff81ca1454-ffffffff81ca149c: __init_cache_modes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __init_cache_modes(u64 pat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:222
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:pat_init
  - arch/x86/mm/pat/memtype.c:init_cache_modes
```
**Symbols:**

```
ffffffff810b3bb0-ffffffff810b3c50: __init_cache_modes (STB_LOCAL)
ffffffff81e50a66-ffffffff81e50aba: __init_cache_modes.cold (STB_LOCAL)
```
</details>
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
void __init_cache_modes(u64 pat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (0)
Location: arch/x86/mm/pat.c:194
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:init_cache_modes
  - arch/x86/mm/pat.c:init_cache_modes
```
**Symbols:**

```
ffffffff81085080-ffffffff810850e7: __init_cache_modes (STB_LOCAL)
ffffffff810860d3-ffffffff81086107: __init_cache_modes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __init_cache_modes(u64 pat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (0)
Location: arch/x86/mm/pat.c:194
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:init_cache_modes
  - arch/x86/mm/pat.c:init_cache_modes
```
**Symbols:**

```
ffffffff81073d50-ffffffff81073db7: __init_cache_modes (STB_LOCAL)
ffffffff81074e53-ffffffff81074e87: __init_cache_modes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __init_cache_modes(u64 pat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (0)
Location: arch/x86/mm/pat.c:194
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:init_cache_modes
  - arch/x86/mm/pat.c:init_cache_modes
```
**Symbols:**

```
ffffffff81085030-ffffffff81085097: __init_cache_modes (STB_LOCAL)
ffffffff81086083-ffffffff810860b7: __init_cache_modes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __init_cache_modes(u64 pat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (0)
Location: arch/x86/mm/pat.c:194
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:init_cache_modes
  - arch/x86/mm/pat.c:init_cache_modes
```
**Symbols:**

```
ffffffff81087180-ffffffff810871e7: __init_cache_modes (STB_LOCAL)
ffffffff810881d3-ffffffff81088207: __init_cache_modes.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
