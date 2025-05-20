# Function: <code>flush_tlb_one_user</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void flush_tlb_one_user(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108b835)
Location: arch/x86/mm/tlb.c:1102
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_one_kernel
Direct callers:
  - arch/x86/platform/uv/tlb_uv.c:bau_process_message
```
**Symbols:**

```
ffffffff8108b920-ffffffff8108b932: flush_tlb_one_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void flush_tlb_one_user(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108b885)
Location: arch/x86/mm/tlb.c:1038
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_one_kernel
```
**Symbols:**

```
ffffffff8108b970-ffffffff8108b982: flush_tlb_one_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void flush_tlb_one_user(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108c495)
Location: arch/x86/mm/tlb.c:1082
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_one_kernel
  - arch/x86/mm/tlb.c:flush_tlb_func
```
**Symbols:**

```
ffffffff8108c570-ffffffff8108c582: flush_tlb_one_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void flush_tlb_one_user(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8109bcd5)
Location: arch/x86/mm/tlb.c:1141
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_one_kernel
  - arch/x86/mm/tlb.c:flush_tlb_func
```
**Symbols:**

```
ffffffff8109bdb0-ffffffff8109bdc2: flush_tlb_one_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void flush_tlb_one_user(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810af1d5)
Location: arch/x86/mm/tlb.c:1115
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_one_kernel
  - arch/x86/mm/tlb.c:flush_tlb_func
```
**Symbols:**

```
ffffffff810af2e0-ffffffff810af30b: flush_tlb_one_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void flush_tlb_one_user(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810c95c5)
Location: arch/x86/mm/tlb.c:1139
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_one_kernel
  - arch/x86/mm/tlb.c:flush_tlb_func
```
**Symbols:**

```
ffffffff810c9700-ffffffff810c972b: flush_tlb_one_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void flush_tlb_one_user(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810ccc45)
Location: arch/x86/mm/tlb.c:1160
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_one_kernel
  - arch/x86/mm/tlb.c:flush_tlb_func
```
**Symbols:**

```
ffffffff810ccd80-ffffffff810ccdab: flush_tlb_one_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void flush_tlb_one_user(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810d5305)
Location: arch/x86/mm/tlb.c:1169
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_one_kernel
  - arch/x86/mm/tlb.c:flush_tlb_func
```
**Symbols:**

```
ffffffff810d5450-ffffffff810d547b: flush_tlb_one_user (STB_GLOBAL)
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
