# Function: <code>cpa_flush_all</code>

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
In arch/x86/mm/pageattr.c (ffffffff8106e4e8)
Location: arch/x86/mm/pageattr.c:160
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
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
In arch/x86/mm/pageattr.c (ffffffff8106e2b9)
Location: arch/x86/mm/pageattr.c:166
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
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
In arch/x86/mm/pageattr.c (ffffffff81071f51)
Location: arch/x86/mm/pageattr.c:166
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
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
In arch/x86/mm/pageattr.c (ffffffff81071630)
Location: arch/x86/mm/pageattr.c:173
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void cpa_flush_all(long unsigned int cache);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81074870)
Location: arch/x86/mm/pageattr.c:173
Inline: True
Direct callers:
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
```
**Symbols:**

```
ffffffff81074870-ffffffff8107489d: cpa_flush_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void cpa_flush_all(long unsigned int cache);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810772e0)
Location: arch/x86/mm/pageattr.c:191
Inline: True
Direct callers:
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
```
**Symbols:**

```
ffffffff810772e0-ffffffff81077316: cpa_flush_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void cpa_flush_all(long unsigned int cache);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8107dac0)
Location: arch/x86/mm/pageattr.c:326
Inline: True
Direct callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:cpa_flush
```
**Symbols:**

```
ffffffff8107dac0-ffffffff8107daf6: cpa_flush_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void cpa_flush_all(long unsigned int cache);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810813c0)
Location: arch/x86/mm/pageattr.c:327
Inline: True
Direct callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:cpa_flush
```
**Symbols:**

```
ffffffff810813c0-ffffffff810813f6: cpa_flush_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void cpa_flush_all(long unsigned int cache);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81082480)
Location: arch/x86/mm/pageattr.c:327
Inline: True
Direct callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:cpa_flush
```
**Symbols:**

```
ffffffff81082480-ffffffff810824b6: cpa_flush_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void cpa_flush_all(long unsigned int cache);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108bcb0)
Location: arch/x86/mm/pat/set_memory.c:336
Inline: True
Direct callers:
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
**Symbols:**

```
ffffffff8108bcb0-ffffffff8108bce6: cpa_flush_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void cpa_flush_all(long unsigned int cache);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108bcd0)
Location: arch/x86/mm/pat/set_memory.c:336
Inline: True
Direct callers:
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
**Symbols:**

```
ffffffff8108bcd0-ffffffff8108bd06: cpa_flush_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void cpa_flush_all(long unsigned int cache);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108cb00)
Location: arch/x86/mm/pat/set_memory.c:344
Inline: True
Direct callers:
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
**Symbols:**

```
ffffffff8108cb00-ffffffff8108cb3f: cpa_flush_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void cpa_flush_all(long unsigned int cache);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/mm/pat/set_memory.c:344
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
**Symbols:**

```
ffffffff8109c360-ffffffff8109c3b4: cpa_flush_all (STB_LOCAL)
ffffffff81ca124b-ffffffff81ca1267: cpa_flush_all.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void cpa_flush_all(long unsigned int cache);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/mm/pat/set_memory.c:347
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
**Symbols:**

```
ffffffff810af780-ffffffff810af7e4: cpa_flush_all (STB_LOCAL)
ffffffff81e50857-ffffffff81e50873: cpa_flush_all.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void cpa_flush_all(long unsigned int cache);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/mm/pat/set_memory.c:382
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
**Symbols:**

```
ffffffff810c9d30-ffffffff810c9d97: cpa_flush_all (STB_LOCAL)
ffffffff82054cdc-ffffffff82054cf1: cpa_flush_all.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void cpa_flush_all(long unsigned int cache);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/mm/pat/set_memory.c:383
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
**Symbols:**

```
ffffffff810cd320-ffffffff810cd387: cpa_flush_all (STB_LOCAL)
ffffffff820d32b2-ffffffff820d32c7: cpa_flush_all.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void cpa_flush_all(long unsigned int cache);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/mm/pat/set_memory.c:383
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
**Symbols:**

```
ffffffff810d5a00-ffffffff810d5a67: cpa_flush_all (STB_LOCAL)
ffffffff821ae120-ffffffff821ae135: cpa_flush_all.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void cpa_flush_all(long unsigned int cache);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81081480)
Location: arch/x86/mm/pageattr.c:327
Inline: True
Direct callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:cpa_flush
```
**Symbols:**

```
ffffffff81081480-ffffffff810814b6: cpa_flush_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void cpa_flush_all(long unsigned int cache);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810706c0)
Location: arch/x86/mm/pageattr.c:327
Inline: True
Direct callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:cpa_flush
```
**Symbols:**

```
ffffffff810706c0-ffffffff810706f1: cpa_flush_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void cpa_flush_all(long unsigned int cache);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81081430)
Location: arch/x86/mm/pageattr.c:327
Inline: True
Direct callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:cpa_flush
```
**Symbols:**

```
ffffffff81081430-ffffffff81081466: cpa_flush_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void cpa_flush_all(long unsigned int cache);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81083550)
Location: arch/x86/mm/pageattr.c:327
Inline: True
Direct callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:cpa_flush
```
**Symbols:**

```
ffffffff81083550-ffffffff81083586: cpa_flush_all (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
