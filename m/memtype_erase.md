# Function: <code>memtype_erase</code>

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
struct memtype *memtype_erase(u64 start, u64 end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (ffffffff81091140)
Location: arch/x86/mm/pat/memtype_interval.c:131
Inline: False
```
**Symbols:**

```
ffffffff81091140-ffffffff810911bb: memtype_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct memtype *memtype_erase(u64 start, u64 end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (ffffffff81090b00)
Location: arch/x86/mm/pat/memtype_interval.c:131
Inline: False
```
**Symbols:**

```
ffffffff81090b00-ffffffff81090b7b: memtype_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct memtype *memtype_erase(u64 start, u64 end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (ffffffff81091640)
Location: arch/x86/mm/pat/memtype_interval.c:131
Inline: False
```
**Symbols:**

```
ffffffff81091640-ffffffff810916bb: memtype_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct memtype *memtype_erase(u64 start, u64 end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (ffffffff810a11c0)
Location: arch/x86/mm/pat/memtype_interval.c:131
Inline: False
```
**Symbols:**

```
ffffffff810a11c0-ffffffff810a123b: memtype_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct memtype *memtype_erase(u64 start, u64 end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (ffffffff810b5290)
Location: arch/x86/mm/pat/memtype_interval.c:131
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:memtype_free
```
**Symbols:**

```
ffffffff810b5290-ffffffff810b531c: memtype_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct memtype *memtype_erase(u64 start, u64 end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (ffffffff810d01e0)
Location: arch/x86/mm/pat/memtype_interval.c:131
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:memtype_free
```
**Symbols:**

```
ffffffff810d01e0-ffffffff810d026c: memtype_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct memtype *memtype_erase(u64 start, u64 end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (ffffffff810d3800)
Location: arch/x86/mm/pat/memtype_interval.c:131
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:memtype_free
```
**Symbols:**

```
ffffffff810d3800-ffffffff810d388c: memtype_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct memtype *memtype_erase(u64 start, u64 end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (ffffffff810dbf90)
Location: arch/x86/mm/pat/memtype_interval.c:131
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:memtype_free
```
**Symbols:**

```
ffffffff810dbf90-ffffffff810dc01c: memtype_erase (STB_GLOBAL)
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
