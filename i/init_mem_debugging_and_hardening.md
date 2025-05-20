# Function: <code>init_mem_debugging_and_hardening</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void init_mem_debugging_and_hardening();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:752
Inline: False
Direct callers:
  - init/main.c:start_kernel
```
**Symbols:**

```
ffffffff81be7c5e-ffffffff81be7c80: init_mem_debugging_and_hardening.cold (STB_LOCAL)
ffffffff812bb370-ffffffff812bb3d6: init_mem_debugging_and_hardening (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void init_mem_debugging_and_hardening();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:774
Inline: False
Direct callers:
  - init/main.c:start_kernel
```
**Symbols:**

```
ffffffff81bd9a3d-ffffffff81bd9a5c: init_mem_debugging_and_hardening.cold (STB_LOCAL)
ffffffff812c04c0-ffffffff812c0548: init_mem_debugging_and_hardening (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void init_mem_debugging_and_hardening();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:824
Inline: False
Direct callers:
  - init/main.c:start_kernel
```
**Symbols:**

```
ffffffff81cbd3ec-ffffffff81cbd471: init_mem_debugging_and_hardening.cold (STB_LOCAL)
ffffffff81303270-ffffffff81303337: init_mem_debugging_and_hardening (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void init_mem_debugging_and_hardening();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:821
Inline: False
Direct callers:
  - init/main.c:start_kernel
```
**Symbols:**

```
ffffffff81e6f2a5-ffffffff81e6f386: init_mem_debugging_and_hardening.cold (STB_LOCAL)
ffffffff8136ac30-ffffffff8136ad19: init_mem_debugging_and_hardening (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void init_mem_debugging_and_hardening();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff83ebe930)
Location: mm/page_alloc.c:889
Inline: False
Direct callers:
  - init/main.c:start_kernel
```
**Symbols:**

```
ffffffff83ebe930-ffffffff83ebeb00: init_mem_debugging_and_hardening (STB_GLOBAL)
```
</details>
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
</ul>
