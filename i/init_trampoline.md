# Function: <code>init_trampoline</code>

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
void init_trampoline();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kaslr.c (ffffffff81896e1f)
Location: arch/x86/mm/kaslr.c:141
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff81896e1f-ffffffff81896f0e: init_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void init_trampoline();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kaslr.c (ffffffff818cb508)
Location: arch/x86/mm/kaslr.c:163
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff818cb508-ffffffff818cb5f7: init_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void init_trampoline();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kaslr.c (ffffffff81902af3)
Location: arch/x86/mm/kaslr.c:225
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff81902af3-ffffffff81902be1: init_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void init_trampoline();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kaslr.c (ffffffff8198ca27)
Location: arch/x86/mm/kaslr.c:212
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff8198ca27-ffffffff8198cb29: init_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void init_trampoline();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kaslr.c (ffffffff819e9340)
Location: arch/x86/mm/kaslr.c:207
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff819e9340-ffffffff819e9435: init_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void init_trampoline();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kaslr.c (ffffffff81a24c86)
Location: arch/x86/mm/kaslr.c:208
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff81a24c86-ffffffff81a24d7b: init_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void init_trampoline();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kaslr.c (ffffffff81a95053)
Location: arch/x86/mm/kaslr.c:205
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff81a95053-ffffffff81a95124: init_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void init_trampoline();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kaslr.c (ffffffff81acc933)
Location: arch/x86/mm/kaslr.c:205
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff81acc933-ffffffff81acca04: init_trampoline (STB_GLOBAL)
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
In arch/x86/mm/init.c (ffffffff82ce5648)
Location: arch/x86/mm/init.c:695
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
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
In arch/x86/mm/init.c (ffffffff82fd2e9e)
Location: arch/x86/mm/init.c:698
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
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
In arch/x86/mm/init.c (ffffffff831ddaed)
Location: arch/x86/mm/init.c:707
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
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
In arch/x86/mm/init.c (ffffffff832c0d0d)
Location: arch/x86/mm/init.c:714
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
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
In arch/x86/mm/init.c (ffffffff83473302)
Location: arch/x86/mm/init.c:723
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff83e9ab9d)
Location: arch/x86/mm/init.c:724
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff836be595)
Location: arch/x86/mm/init.c:749
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff838ef055)
Location: arch/x86/mm/init.c:739
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
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
<summary>In <code>aws</code>: ✅</summary>

```c
void init_trampoline();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kaslr.c (ffffffff81a6b7a3)
Location: arch/x86/mm/kaslr.c:205
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff81a6b7a3-ffffffff81a6b874: init_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void init_trampoline();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kaslr.c (ffffffff81a27cf2)
Location: arch/x86/mm/kaslr.c:205
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff81a27cf2-ffffffff81a27dbb: init_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void init_trampoline();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kaslr.c (ffffffff81ad7bb3)
Location: arch/x86/mm/kaslr.c:205
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff81ad7bb3-ffffffff81ad7c84: init_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void init_trampoline();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kaslr.c (ffffffff81ae4073)
Location: arch/x86/mm/kaslr.c:205
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff81ae4073-ffffffff81ae4144: init_trampoline (STB_GLOBAL)
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
