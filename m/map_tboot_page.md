# Function: <code>map_tboot_page</code>

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
In arch/x86/kernel/tboot.c (ffffffff81f6a326)
Location: arch/x86/kernel/tboot.c:123
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
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
In arch/x86/kernel/tboot.c (ffffffff81f9259b)
Location: arch/x86/kernel/tboot.c:117
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
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
In arch/x86/kernel/tboot.c (ffffffff81fcd867)
Location: arch/x86/kernel/tboot.c:117
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
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
In arch/x86/kernel/tboot.c (ffffffff820adea8)
Location: arch/x86/kernel/tboot.c:117
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
In arch/x86/kernel/tboot.c (ffffffff826b43a6)
Location: arch/x86/kernel/tboot.c:117
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
In arch/x86/kernel/tboot.c (ffffffff826ddd0b)
Location: arch/x86/kernel/tboot.c:117
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
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
In arch/x86/kernel/tboot.c (ffffffff82894151)
Location: arch/x86/kernel/tboot.c:117
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
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
In arch/x86/kernel/tboot.c (ffffffff828ab904)
Location: arch/x86/kernel/tboot.c:104
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
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
In arch/x86/kernel/tboot.c (ffffffff828ae912)
Location: arch/x86/kernel/tboot.c:104
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int map_tboot_page(long unsigned int vaddr, long unsigned int pfn, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff8104793d)
Location: arch/x86/kernel/tboot.c:106
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_create_trampoline
```
**Symbols:**

```
ffffffff8104793d-ffffffff81047b8b: map_tboot_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int map_tboot_page(long unsigned int vaddr, long unsigned int pfn, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff81bd4bc1)
Location: arch/x86/kernel/tboot.c:107
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_create_trampoline
```
**Symbols:**

```
ffffffff81bd4bc1-ffffffff81bd4e02: map_tboot_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int map_tboot_page(long unsigned int vaddr, long unsigned int pfn, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff81bc704b)
Location: arch/x86/kernel/tboot.c:115
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
**Symbols:**

```
ffffffff81bc704b-ffffffff81bc7252: map_tboot_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int map_tboot_page(long unsigned int vaddr, long unsigned int pfn, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff81c9a630)
Location: arch/x86/kernel/tboot.c:115
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
**Symbols:**

```
ffffffff81c9a630-ffffffff81c9a84a: map_tboot_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int map_tboot_page(long unsigned int vaddr, long unsigned int pfn, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff81e49a9b)
Location: arch/x86/kernel/tboot.c:114
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
**Symbols:**

```
ffffffff81e49a9b-ffffffff81e49ccc: map_tboot_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int map_tboot_page(long unsigned int vaddr, long unsigned int pfn, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/kernel/tboot.c:113
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
**Symbols:**

```
ffffffff81067e20-ffffffff810680a2: map_tboot_page (STB_LOCAL)
ffffffff82052712-ffffffff8205272e: map_tboot_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int map_tboot_page(long unsigned int vaddr, long unsigned int pfn, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/kernel/tboot.c:113
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
**Symbols:**

```
ffffffff810696d0-ffffffff81069929: map_tboot_page (STB_LOCAL)
ffffffff820d0bdf-ffffffff820d0bfb: map_tboot_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int map_tboot_page(long unsigned int vaddr, long unsigned int pfn, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/kernel/tboot.c:113
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
**Symbols:**

```
ffffffff81070c10-ffffffff81070e58: map_tboot_page (STB_LOCAL)
ffffffff821ab708-ffffffff821ab724: map_tboot_page.cold (STB_LOCAL)
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
In arch/x86/kernel/tboot.c (ffffffff8289c931)
Location: arch/x86/kernel/tboot.c:104
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
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
In arch/x86/kernel/tboot.c (ffffffff82894ae7)
Location: arch/x86/kernel/tboot.c:104
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
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
In arch/x86/kernel/tboot.c (ffffffff828af8f4)
Location: arch/x86/kernel/tboot.c:104
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
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
In arch/x86/kernel/tboot.c (ffffffff828af922)
Location: arch/x86/kernel/tboot.c:104
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
</details>
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
