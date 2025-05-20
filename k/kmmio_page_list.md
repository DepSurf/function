# Function: <code>kmmio_page_list</code>

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
In arch/x86/mm/kmmio.c (ffffffff81073147)
Location: arch/x86/mm/kmmio.c:73
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct list_head *kmmio_page_list(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff810743a0)
Location: arch/x86/mm/kmmio.c:73
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
```
**Symbols:**

```
ffffffff810743a0-ffffffff81074420: kmmio_page_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct list_head *kmmio_page_list(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff81077f20)
Location: arch/x86/mm/kmmio.c:73
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
```
**Symbols:**

```
ffffffff81077f20-ffffffff81077fa0: kmmio_page_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct list_head *kmmio_page_list(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff81076840)
Location: arch/x86/mm/kmmio.c:73
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
```
**Symbols:**

```
ffffffff81076840-ffffffff810768c0: kmmio_page_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct list_head *kmmio_page_list(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff8107cb40)
Location: arch/x86/mm/kmmio.c:74
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
```
**Symbols:**

```
ffffffff8107cb40-ffffffff8107cbc0: kmmio_page_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct list_head *kmmio_page_list(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff8107fb10)
Location: arch/x86/mm/kmmio.c:74
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
```
**Symbols:**

```
ffffffff8107fb10-ffffffff8107fb90: kmmio_page_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct list_head *kmmio_page_list(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff81086650)
Location: arch/x86/mm/kmmio.c:74
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
```
**Symbols:**

```
ffffffff81086650-ffffffff810866cc: kmmio_page_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct list_head *kmmio_page_list(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff8108a260)
Location: arch/x86/mm/kmmio.c:74
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
```
**Symbols:**

```
ffffffff8108a260-ffffffff8108a2dc: kmmio_page_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct list_head *kmmio_page_list(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff8108aed0)
Location: arch/x86/mm/kmmio.c:74
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
```
**Symbols:**

```
ffffffff8108aed0-ffffffff8108af4c: kmmio_page_list (STB_LOCAL)
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
In arch/x86/mm/kmmio.c (ffffffff8109294f)
Location: arch/x86/mm/kmmio.c:74
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:add_kmmio_fault_page
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
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
In arch/x86/mm/kmmio.c (ffffffff81091fdf)
Location: arch/x86/mm/kmmio.c:74
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:add_kmmio_fault_page
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
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
In arch/x86/mm/kmmio.c (ffffffff81092b93)
Location: arch/x86/mm/kmmio.c:74
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct list_head *kmmio_page_list(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:74
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
```
**Symbols:**

```
ffffffff810a21c0-ffffffff810a2241: kmmio_page_list (STB_LOCAL)
ffffffff81ca1d87-ffffffff81ca1da6: kmmio_page_list.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct list_head *kmmio_page_list(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:74
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
```
**Symbols:**

```
ffffffff810b6740-ffffffff810b67d4: kmmio_page_list (STB_LOCAL)
ffffffff81e513e8-ffffffff81e51407: kmmio_page_list.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct list_head *kmmio_page_list(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:80
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
```
**Symbols:**

```
ffffffff810d1960-ffffffff810d19f4: kmmio_page_list (STB_LOCAL)
ffffffff82055149-ffffffff82055168: kmmio_page_list.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct list_head *kmmio_page_list(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:80
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
```
**Symbols:**

```
ffffffff810d4e10-ffffffff810d4ea4: kmmio_page_list (STB_LOCAL)
ffffffff820d3718-ffffffff820d3737: kmmio_page_list.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct list_head *kmmio_page_list(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:80
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
```
**Symbols:**

```
ffffffff810dd5b0-ffffffff810dd644: kmmio_page_list (STB_LOCAL)
ffffffff821ae586-ffffffff821ae5a5: kmmio_page_list.cold (STB_LOCAL)
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
struct list_head *kmmio_page_list(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff81089e90)
Location: arch/x86/mm/kmmio.c:74
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
```
**Symbols:**

```
ffffffff81089e90-ffffffff81089f0c: kmmio_page_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct list_head *kmmio_page_list(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff81078a70)
Location: arch/x86/mm/kmmio.c:74
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
```
**Symbols:**

```
ffffffff81078a70-ffffffff81078aec: kmmio_page_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct list_head *kmmio_page_list(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff81089e40)
Location: arch/x86/mm/kmmio.c:74
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
```
**Symbols:**

```
ffffffff81089e40-ffffffff81089ebc: kmmio_page_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct list_head *kmmio_page_list(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff8108c0e0)
Location: arch/x86/mm/kmmio.c:74
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
```
**Symbols:**

```
ffffffff8108c0e0-ffffffff8108c15c: kmmio_page_list (STB_LOCAL)
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
