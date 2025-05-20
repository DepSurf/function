# Function: <code>pat_disable</code>

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
In arch/x86/mm/pat.c (ffffffff81f78066)
Location: arch/x86/mm/pat.c:43
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:nopat
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:pat_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void pat_disable(const char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff8106fa60)
Location: arch/x86/mm/pat.c:44
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:nopat
```
**Symbols:**

```
ffffffff8106fa60-ffffffff8106fad4: pat_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void pat_disable(const char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81073690)
Location: arch/x86/mm/pat.c:44
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:nopat
```
**Symbols:**

```
ffffffff81073690-ffffffff81073704: pat_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void pat_disable(const char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81072c20)
Location: arch/x86/mm/pat.c:45
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:nopat
```
**Symbols:**

```
ffffffff81072c20-ffffffff81072c77: pat_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void pat_disable(const char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff810785a0)
Location: arch/x86/mm/pat.c:45
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:nopat
```
**Symbols:**

```
ffffffff810785a0-ffffffff810785f7: pat_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pat_disable(const char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (0)
Location: arch/x86/mm/pat.c:45
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:nopat
```
**Symbols:**

```
ffffffff8107be9a-ffffffff8107beb5: pat_disable.cold.13 (STB_LOCAL)
ffffffff8107b220-ffffffff8107b262: pat_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pat_disable(const char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff8108280a)
Location: arch/x86/mm/pat.c:45
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:nopat
```
**Symbols:**

```
ffffffff8108280a-ffffffff81082825: pat_disable.cold.12 (STB_LOCAL)
ffffffff81081b60-ffffffff81081ba2: pat_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pat_disable(const char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81086464)
Location: arch/x86/mm/pat.c:46
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:nopat
```
**Symbols:**

```
ffffffff81086464-ffffffff8108647f: pat_disable.cold (STB_LOCAL)
ffffffff81085800-ffffffff81085842: pat_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pat_disable(const char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81087154)
Location: arch/x86/mm/pat.c:46
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:nopat
```
**Symbols:**

```
ffffffff81087154-ffffffff8108716f: pat_disable.cold (STB_LOCAL)
ffffffff810864f0-ffffffff81086532: pat_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pat_disable(const char *msg_reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff8109087f)
Location: arch/x86/mm/pat/memtype.c:72
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
  - arch/x86/mm/pat/memtype.c:pat_init
  - arch/x86/mm/pat/memtype.c:pat_init
  - arch/x86/mm/pat/memtype.c:nopat
```
**Symbols:**

```
ffffffff8109087f-ffffffff8109089a: pat_disable.cold (STB_LOCAL)
ffffffff8108fc70-ffffffff8108fcb2: pat_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pat_disable(const char *msg_reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff81bd997c)
Location: arch/x86/mm/pat/memtype.c:72
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
  - arch/x86/mm/pat/memtype.c:pat_init
  - arch/x86/mm/pat/memtype.c:pat_init
  - arch/x86/mm/pat/memtype.c:nopat
```
**Symbols:**

```
ffffffff81bd997c-ffffffff81bd9997: pat_disable.cold (STB_LOCAL)
ffffffff8108f970-ffffffff8108f9b2: pat_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pat_disable(const char *msg_reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff81bcb999)
Location: arch/x86/mm/pat/memtype.c:72
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
  - arch/x86/mm/pat/memtype.c:pat_init
  - arch/x86/mm/pat/memtype.c:pat_init
  - arch/x86/mm/pat/memtype.c:nopat
```
**Symbols:**

```
ffffffff81bcb999-ffffffff81bcb9b4: pat_disable.cold (STB_LOCAL)
ffffffff81090470-ffffffff810904b2: pat_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pat_disable(const char *msg_reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff8109fe84)
Location: arch/x86/mm/pat/memtype.c:72
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
  - arch/x86/mm/pat/memtype.c:pat_init
  - arch/x86/mm/pat/memtype.c:pat_init
  - arch/x86/mm/pat/memtype.c:nopat
```
**Symbols:**

```
ffffffff81ca149c-ffffffff81ca14f3: pat_disable.cold (STB_LOCAL)
ffffffff8109fe60-ffffffff8109fece: pat_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pat_disable(const char *msg_reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff810b3dc7)
Location: arch/x86/mm/pat/memtype.c:73
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
  - arch/x86/mm/pat/memtype.c:pat_init
  - arch/x86/mm/pat/memtype.c:pat_init
  - arch/x86/mm/pat/memtype.c:nopat
```
**Symbols:**

```
ffffffff81e50aba-ffffffff81e50b13: pat_disable.cold (STB_LOCAL)
ffffffff810b3da0-ffffffff810b3e1e: pat_disable (STB_GLOBAL)
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
In arch/x86/mm/pat/memtype.c (ffffffff83e9ce78)
Location: arch/x86/mm/pat/memtype.c:71
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:pat_bp_init
  - arch/x86/mm/pat/memtype.c:pat_bp_init
  - arch/x86/mm/pat/memtype.c:nopat
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
In arch/x86/mm/pat/memtype.c (ffffffff836c0998)
Location: arch/x86/mm/pat/memtype.c:71
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:pat_bp_init
  - arch/x86/mm/pat/memtype.c:pat_bp_init
  - arch/x86/mm/pat/memtype.c:nopat
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
In arch/x86/mm/pat/memtype.c (ffffffff838f14b8)
Location: arch/x86/mm/pat/memtype.c:71
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:pat_bp_init
  - arch/x86/mm/pat/memtype.c:pat_bp_init
  - arch/x86/mm/pat/memtype.c:nopat
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pat_disable(const char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81086154)
Location: arch/x86/mm/pat.c:46
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:nopat
```
**Symbols:**

```
ffffffff81086154-ffffffff8108616f: pat_disable.cold (STB_LOCAL)
ffffffff810854f0-ffffffff81085532: pat_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pat_disable(const char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81074ed4)
Location: arch/x86/mm/pat.c:46
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:nopat
```
**Symbols:**

```
ffffffff81074ed4-ffffffff81074eef: pat_disable.cold (STB_LOCAL)
ffffffff810741c0-ffffffff81074202: pat_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pat_disable(const char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81086104)
Location: arch/x86/mm/pat.c:46
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:nopat
```
**Symbols:**

```
ffffffff81086104-ffffffff8108611f: pat_disable.cold (STB_LOCAL)
ffffffff810854a0-ffffffff810854e2: pat_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pat_disable(const char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81088254)
Location: arch/x86/mm/pat.c:46
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:pat_init
  - arch/x86/mm/pat.c:nopat
```
**Symbols:**

```
ffffffff81088254-ffffffff8108826f: pat_disable.cold (STB_LOCAL)
ffffffff810875f0-ffffffff81087632: pat_disable (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *msg_reason</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *reason</code>
</li>
</ul>
</details>
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
