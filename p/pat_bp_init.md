# Function: <code>pat_bp_init</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff8108fd8b)
Location: arch/x86/mm/pat/memtype.c:241
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:pat_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff8108fa8b)
Location: arch/x86/mm/pat/memtype.c:241
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:pat_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff8109058b)
Location: arch/x86/mm/pat/memtype.c:241
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:pat_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff8109ff9b)
Location: arch/x86/mm/pat/memtype.c:241
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:pat_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff810b3e8e)
Location: arch/x86/mm/pat/memtype.c:243
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:pat_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pat_bp_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff83e9ce00)
Location: arch/x86/mm/pat/memtype.c:254
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_bp_init
```
**Symbols:**

```
ffffffff83e9ce00-ffffffff83e9d078: pat_bp_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pat_bp_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff836c0920)
Location: arch/x86/mm/pat/memtype.c:254
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_bp_init
```
**Symbols:**

```
ffffffff836c0920-ffffffff836c0b6d: pat_bp_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pat_bp_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff838f1440)
Location: arch/x86/mm/pat/memtype.c:254
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_bp_init
```
**Symbols:**

```
ffffffff838f1440-ffffffff838f168d: pat_bp_init (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
