# Function: <code>pat_get_cache_mode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff8106fcb5)
Location: arch/x86/mm/pat.c:156
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pat_init_cache_modes
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff8106f725)
Location: arch/x86/mm/pat.c:167
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:__init_cache_modes
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81073355)
Location: arch/x86/mm/pat.c:167
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:__init_cache_modes
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (0)
Location: arch/x86/mm/pat.c:166
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (0)
Location: arch/x86/mm/pat.c:166
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff8107aded)
Location: arch/x86/mm/pat.c:166
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:__init_cache_modes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff8108172d)
Location: arch/x86/mm/pat.c:166
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:__init_cache_modes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff810853bb)
Location: arch/x86/mm/pat.c:167
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:__init_cache_modes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff810860ab)
Location: arch/x86/mm/pat.c:167
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:__init_cache_modes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff8108f764)
Location: arch/x86/mm/pat/memtype.c:193
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:__init_cache_modes
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
In arch/x86/mm/pat/memtype.c (ffffffff8108f453)
Location: arch/x86/mm/pat/memtype.c:193
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:__init_cache_modes
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
In arch/x86/mm/pat/memtype.c (ffffffff8108ffe3)
Location: arch/x86/mm/pat/memtype.c:193
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:__init_cache_modes
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
In arch/x86/mm/pat/memtype.c (ffffffff8109fc2f)
Location: arch/x86/mm/pat/memtype.c:193
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:__init_cache_modes
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
In arch/x86/mm/pat/memtype.c (ffffffff810b3c23)
Location: arch/x86/mm/pat/memtype.c:195
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:__init_cache_modes
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum page_cache_mode pat_get_cache_mode(unsigned int pat_val, char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff83e9cbf0)
Location: arch/x86/mm/pat/memtype.c:189
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:init_cache_modes
```
**Symbols:**

```
ffffffff83e9cbf0-ffffffff83e9cc1a: pat_get_cache_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum page_cache_mode pat_get_cache_mode(unsigned int pat_val, char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff836c0710)
Location: arch/x86/mm/pat/memtype.c:189
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:init_cache_modes
```
**Symbols:**

```
ffffffff836c0710-ffffffff836c073a: pat_get_cache_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum page_cache_mode pat_get_cache_mode(unsigned int pat_val, char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff838f1230)
Location: arch/x86/mm/pat/memtype.c:189
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:init_cache_modes
```
**Symbols:**

```
ffffffff838f1230-ffffffff838f125a: pat_get_cache_mode (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff810850ab)
Location: arch/x86/mm/pat.c:167
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:__init_cache_modes
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81073d7b)
Location: arch/x86/mm/pat.c:167
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:__init_cache_modes
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff8108505b)
Location: arch/x86/mm/pat.c:167
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:__init_cache_modes
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff810871ab)
Location: arch/x86/mm/pat.c:167
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:__init_cache_modes
```
</details>
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
