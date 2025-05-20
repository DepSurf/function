# Function: <code>memtype_lookup</code>

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
struct memtype *memtype_lookup(u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (ffffffff810911c0)
Location: arch/x86/mm/pat/memtype_interval.c:164
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:lookup_memtype
```
**Symbols:**

```
ffffffff810911c0-ffffffff81091201: memtype_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct memtype *memtype_lookup(u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (ffffffff81090b80)
Location: arch/x86/mm/pat/memtype_interval.c:164
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:lookup_memtype
```
**Symbols:**

```
ffffffff81090b80-ffffffff81090bc1: memtype_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct memtype *memtype_lookup(u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (ffffffff810916c0)
Location: arch/x86/mm/pat/memtype_interval.c:164
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:lookup_memtype
```
**Symbols:**

```
ffffffff810916c0-ffffffff81091701: memtype_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct memtype *memtype_lookup(u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (ffffffff810a1240)
Location: arch/x86/mm/pat/memtype_interval.c:164
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:lookup_memtype
```
**Symbols:**

```
ffffffff810a1240-ffffffff810a1281: memtype_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct memtype *memtype_lookup(u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (ffffffff810b5320)
Location: arch/x86/mm/pat/memtype_interval.c:164
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:lookup_memtype
```
**Symbols:**

```
ffffffff810b5320-ffffffff810b5385: memtype_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct memtype *memtype_lookup(u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (ffffffff810d0280)
Location: arch/x86/mm/pat/memtype_interval.c:164
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:lookup_memtype
```
**Symbols:**

```
ffffffff810d0280-ffffffff810d02e5: memtype_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct memtype *memtype_lookup(u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (ffffffff810d38a0)
Location: arch/x86/mm/pat/memtype_interval.c:164
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:lookup_memtype
```
**Symbols:**

```
ffffffff810d38a0-ffffffff810d3905: memtype_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct memtype *memtype_lookup(u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (ffffffff810dc030)
Location: arch/x86/mm/pat/memtype_interval.c:164
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:lookup_memtype
```
**Symbols:**

```
ffffffff810dc030-ffffffff810dc095: memtype_lookup (STB_GLOBAL)
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
