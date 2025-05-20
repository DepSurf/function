# Function: <code>pat_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pat_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff8106fd00)
Location: arch/x86/mm/pat.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
**Symbols:**

```
ffffffff8106fd00-ffffffff8106fe96: pat_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pat_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff8106fae0)
Location: arch/x86/mm/pat.c:303
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_bp_pat_init
```
**Symbols:**

```
ffffffff8106fae0-ffffffff8106fc0e: pat_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pat_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81073710)
Location: arch/x86/mm/pat.c:303
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_bp_pat_init
```
**Symbols:**

```
ffffffff81073710-ffffffff8107383e: pat_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pat_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81072cd0)
Location: arch/x86/mm/pat.c:302
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_bp_pat_init
```
**Symbols:**

```
ffffffff81072cd0-ffffffff81072ded: pat_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pat_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81078650)
Location: arch/x86/mm/pat.c:302
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_bp_pat_init
```
**Symbols:**

```
ffffffff81078650-ffffffff8107876d: pat_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void pat_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (0)
Location: arch/x86/mm/pat.c:302
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_bp_pat_init
```
**Symbols:**

```
ffffffff8107beb5-ffffffff8107bec1: pat_init.cold.14 (STB_LOCAL)
ffffffff8107b2c0-ffffffff8107b3f1: pat_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void pat_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (0)
Location: arch/x86/mm/pat.c:302
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_bp_pat_init
```
**Symbols:**

```
ffffffff81082825-ffffffff81082831: pat_init.cold.13 (STB_LOCAL)
ffffffff81081c00-ffffffff81081d31: pat_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pat_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (0)
Location: arch/x86/mm/pat.c:303
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_bp_pat_init
```
**Symbols:**

```
ffffffff8108647f-ffffffff8108648b: pat_init.cold (STB_LOCAL)
ffffffff810858a0-ffffffff810859d0: pat_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void pat_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (0)
Location: arch/x86/mm/pat.c:303
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_bp_pat_init
```
**Symbols:**

```
ffffffff8108716f-ffffffff8108717b: pat_init.cold (STB_LOCAL)
ffffffff81086590-ffffffff810866c0: pat_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void pat_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:331
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_bp_pat_init
```
**Symbols:**

```
ffffffff8109089a-ffffffff810908a6: pat_init.cold (STB_LOCAL)
ffffffff8108fd10-ffffffff8108fe40: pat_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pat_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:331
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_bp_pat_init
```
**Symbols:**

```
ffffffff81bd9997-ffffffff81bd99a3: pat_init.cold (STB_LOCAL)
ffffffff8108fa10-ffffffff8108fb40: pat_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pat_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:331
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_bp_pat_init
```
**Symbols:**

```
ffffffff81bcb9b4-ffffffff81bcb9c0: pat_init.cold (STB_LOCAL)
ffffffff81090510-ffffffff81090640: pat_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pat_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:331
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_bp_pat_init
```
**Symbols:**

```
ffffffff81ca1507-ffffffff81ca153b: pat_init.cold (STB_LOCAL)
ffffffff8109ff30-ffffffff810a0066: pat_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pat_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (0)
Location: arch/x86/mm/pat/memtype.c:339
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_bp_pat_init
```
**Symbols:**

```
ffffffff81e50b13-ffffffff81e50b48: pat_init.cold (STB_LOCAL)
ffffffff810b3e20-ffffffff810b3f92: pat_init (STB_GLOBAL)
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
void pat_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (0)
Location: arch/x86/mm/pat.c:303
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_bp_pat_init
```
**Symbols:**

```
ffffffff8108616f-ffffffff8108617b: pat_init.cold (STB_LOCAL)
ffffffff81085590-ffffffff810856c0: pat_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void pat_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (0)
Location: arch/x86/mm/pat.c:303
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_bp_pat_init
```
**Symbols:**

```
ffffffff81074eef-ffffffff81074efb: pat_init.cold (STB_LOCAL)
ffffffff81074290-ffffffff81074431: pat_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void pat_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (0)
Location: arch/x86/mm/pat.c:303
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_bp_pat_init
```
**Symbols:**

```
ffffffff8108611f-ffffffff8108612b: pat_init.cold (STB_LOCAL)
ffffffff81085540-ffffffff81085670: pat_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void pat_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (0)
Location: arch/x86/mm/pat.c:303
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_bp_pat_init
```
**Symbols:**

```
ffffffff8108826f-ffffffff8108827b: pat_init.cold (STB_LOCAL)
ffffffff81087690-ffffffff810877c0: pat_init (STB_GLOBAL)
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
