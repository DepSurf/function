# Function: <code>get_kmmio_fault_page</code>

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
Location: arch/x86/mm/kmmio.c:101
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct kmmio_fault_page *get_kmmio_fault_page(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff81074420)
Location: arch/x86/mm/kmmio.c:108
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
```
**Symbols:**

```
ffffffff81074420-ffffffff810744a8: get_kmmio_fault_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct kmmio_fault_page *get_kmmio_fault_page(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff81077fa0)
Location: arch/x86/mm/kmmio.c:108
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
```
**Symbols:**

```
ffffffff81077fa0-ffffffff81078028: get_kmmio_fault_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct kmmio_fault_page *get_kmmio_fault_page(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff810768c0)
Location: arch/x86/mm/kmmio.c:108
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
```
**Symbols:**

```
ffffffff810768c0-ffffffff8107694c: get_kmmio_fault_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct kmmio_fault_page *get_kmmio_fault_page(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff8107cbc0)
Location: arch/x86/mm/kmmio.c:109
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
```
**Symbols:**

```
ffffffff8107cbc0-ffffffff8107cc4c: get_kmmio_fault_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct kmmio_fault_page *get_kmmio_fault_page(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff8107fb90)
Location: arch/x86/mm/kmmio.c:109
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
```
**Symbols:**

```
ffffffff8107fb90-ffffffff8107fc1c: get_kmmio_fault_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct kmmio_fault_page *get_kmmio_fault_page(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff810866d0)
Location: arch/x86/mm/kmmio.c:109
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
```
**Symbols:**

```
ffffffff810866d0-ffffffff8108675c: get_kmmio_fault_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct kmmio_fault_page *get_kmmio_fault_page(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff8108a2e0)
Location: arch/x86/mm/kmmio.c:109
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
```
**Symbols:**

```
ffffffff8108a2e0-ffffffff8108a368: get_kmmio_fault_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct kmmio_fault_page *get_kmmio_fault_page(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff8108af50)
Location: arch/x86/mm/kmmio.c:109
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
```
**Symbols:**

```
ffffffff8108af50-ffffffff8108afd8: get_kmmio_fault_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct kmmio_fault_page *get_kmmio_fault_page(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff81092370)
Location: arch/x86/mm/kmmio.c:109
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:add_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_handler
```
**Symbols:**

```
ffffffff81092370-ffffffff8109243e: get_kmmio_fault_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct kmmio_fault_page *get_kmmio_fault_page(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff81091a10)
Location: arch/x86/mm/kmmio.c:109
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:add_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_handler
```
**Symbols:**

```
ffffffff81091a10-ffffffff81091ade: get_kmmio_fault_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct kmmio_fault_page *get_kmmio_fault_page(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff81092550)
Location: arch/x86/mm/kmmio.c:109
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
```
**Symbols:**

```
ffffffff81092550-ffffffff8109261e: get_kmmio_fault_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct kmmio_fault_page *get_kmmio_fault_page(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:109
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
```
**Symbols:**

```
ffffffff810a2250-ffffffff810a22e1: get_kmmio_fault_page (STB_LOCAL)
ffffffff81ca1da6-ffffffff81ca1dc5: get_kmmio_fault_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct kmmio_fault_page *get_kmmio_fault_page(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:109
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
```
**Symbols:**

```
ffffffff810b67e0-ffffffff810b6884: get_kmmio_fault_page (STB_LOCAL)
ffffffff81e51407-ffffffff81e51426: get_kmmio_fault_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct kmmio_fault_page *get_kmmio_fault_page(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:115
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
```
**Symbols:**

```
ffffffff810d1a10-ffffffff810d1ab4: get_kmmio_fault_page (STB_LOCAL)
ffffffff82055168-ffffffff82055187: get_kmmio_fault_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct kmmio_fault_page *get_kmmio_fault_page(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:115
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
```
**Symbols:**

```
ffffffff810d4ec0-ffffffff810d4f64: get_kmmio_fault_page (STB_LOCAL)
ffffffff820d3737-ffffffff820d3756: get_kmmio_fault_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct kmmio_fault_page *get_kmmio_fault_page(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:115
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
```
**Symbols:**

```
ffffffff810dd660-ffffffff810dd704: get_kmmio_fault_page (STB_LOCAL)
ffffffff821ae5a5-ffffffff821ae5c4: get_kmmio_fault_page.cold (STB_LOCAL)
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
struct kmmio_fault_page *get_kmmio_fault_page(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff81089f10)
Location: arch/x86/mm/kmmio.c:109
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
```
**Symbols:**

```
ffffffff81089f10-ffffffff81089f98: get_kmmio_fault_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct kmmio_fault_page *get_kmmio_fault_page(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff81078af0)
Location: arch/x86/mm/kmmio.c:109
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
```
**Symbols:**

```
ffffffff81078af0-ffffffff81078b78: get_kmmio_fault_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct kmmio_fault_page *get_kmmio_fault_page(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff81089ec0)
Location: arch/x86/mm/kmmio.c:109
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
```
**Symbols:**

```
ffffffff81089ec0-ffffffff81089f48: get_kmmio_fault_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct kmmio_fault_page *get_kmmio_fault_page(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff8108c160)
Location: arch/x86/mm/kmmio.c:109
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
```
**Symbols:**

```
ffffffff8108c160-ffffffff8108c1e8: get_kmmio_fault_page (STB_LOCAL)
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
