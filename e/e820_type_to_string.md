# Function: <code>e820_type_to_string</code>

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
In arch/x86/kernel/e820.c (ffffffff81f68426)
Location: arch/x86/kernel/e820.c:915
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820_reserve_resources
  - arch/x86/kernel/e820.c:e820_reserve_resources
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
In arch/x86/kernel/e820.c (ffffffff81f903d5)
Location: arch/x86/kernel/e820.c:915
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820_reserve_resources
  - arch/x86/kernel/e820.c:e820_reserve_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const char *e820_type_to_string(int e820_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81fca935)
Location: arch/x86/kernel/e820.c:940
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820_reserve_resources
  - arch/x86/kernel/e820.c:e820_reserve_resources
```
**Symbols:**

```
ffffffff81fca935-ffffffff81fca994: e820_type_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const char *e820_type_to_string(struct e820_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff820ab0bc)
Location: arch/x86/kernel/e820.c:975
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/e820.c:e820__reserve_resources
```
**Symbols:**

```
ffffffff820ab0bc-ffffffff820ab130: e820_type_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const char *e820_type_to_string(struct e820_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff826b1861)
Location: arch/x86/kernel/e820.c:995
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/e820.c:e820__reserve_resources
```
**Symbols:**

```
ffffffff826b1861-ffffffff826b18d5: e820_type_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const char *e820_type_to_string(struct e820_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff826daf1f)
Location: arch/x86/kernel/e820.c:1015
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/e820.c:e820__reserve_resources
```
**Symbols:**

```
ffffffff826daf1f-ffffffff826dafaf: e820_type_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const char *e820_type_to_string(struct e820_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82891306)
Location: arch/x86/kernel/e820.c:1014
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/e820.c:e820__reserve_resources
```
**Symbols:**

```
ffffffff82891306-ffffffff82891396: e820_type_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const char *e820_type_to_string(struct e820_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828a8857)
Location: arch/x86/kernel/e820.c:1029
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/e820.c:e820__reserve_resources
```
**Symbols:**

```
ffffffff828a8857-ffffffff828a88de: e820_type_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const char *e820_type_to_string(struct e820_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828ab8bb)
Location: arch/x86/kernel/e820.c:1029
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/e820.c:e820__reserve_resources
```
**Symbols:**

```
ffffffff828ab8bb-ffffffff828ab942: e820_type_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const char *e820_type_to_string(struct e820_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82cd0bd7)
Location: arch/x86/kernel/e820.c:1041
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/e820.c:e820__reserve_resources
```
**Symbols:**

```
ffffffff82cd0bd7-ffffffff82cd0c7e: e820_type_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *e820_type_to_string(struct e820_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82fbca17)
Location: arch/x86/kernel/e820.c:1055
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/e820.c:e820__reserve_resources
```
**Symbols:**

```
ffffffff82fbca17-ffffffff82fbcabe: e820_type_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *e820_type_to_string(struct e820_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff831c712d)
Location: arch/x86/kernel/e820.c:1055
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/e820.c:e820__reserve_resources
```
**Symbols:**

```
ffffffff831c712d-ffffffff831c71d4: e820_type_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *e820_type_to_string(struct e820_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff832a8025)
Location: arch/x86/kernel/e820.c:1074
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/e820.c:e820__reserve_resources
```
**Symbols:**

```
ffffffff832a8025-ffffffff832a80cc: e820_type_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *e820_type_to_string(struct e820_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff83457429)
Location: arch/x86/kernel/e820.c:1074
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/e820.c:e820__reserve_resources
```
**Symbols:**

```
ffffffff83457429-ffffffff834574d8: e820_type_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *e820_type_to_string(struct e820_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff83e75c00)
Location: arch/x86/kernel/e820.c:1074
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/e820.c:e820__reserve_resources
```
**Symbols:**

```
ffffffff83e75c00-ffffffff83e75cc9: e820_type_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *e820_type_to_string(struct e820_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff836976d0)
Location: arch/x86/kernel/e820.c:1074
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/e820.c:e820__reserve_resources
```
**Symbols:**

```
ffffffff836976d0-ffffffff836977a3: e820_type_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *e820_type_to_string(struct e820_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff838c7450)
Location: arch/x86/kernel/e820.c:1076
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/e820.c:e820__reserve_resources
```
**Symbols:**

```
ffffffff838c7450-ffffffff838c7523: e820_type_to_string (STB_LOCAL)
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
const char *e820_type_to_string(struct e820_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828998cd)
Location: arch/x86/kernel/e820.c:1029
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/e820.c:e820__reserve_resources
```
**Symbols:**

```
ffffffff828998cd-ffffffff82899954: e820_type_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const char *e820_type_to_string(struct e820_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82891b8b)
Location: arch/x86/kernel/e820.c:1029
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/e820.c:e820__reserve_resources
```
**Symbols:**

```
ffffffff82891b8b-ffffffff82891c12: e820_type_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const char *e820_type_to_string(struct e820_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828ac8ad)
Location: arch/x86/kernel/e820.c:1029
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/e820.c:e820__reserve_resources
```
**Symbols:**

```
ffffffff828ac8ad-ffffffff828ac934: e820_type_to_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const char *e820_type_to_string(struct e820_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828ac8cb)
Location: arch/x86/kernel/e820.c:1029
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/e820.c:e820__reserve_resources
```
**Symbols:**

```
ffffffff828ac8cb-ffffffff828ac952: e820_type_to_string (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct e820_entry *entry</code>
</li>
<li>
<b>Param removed. </b>
<code>int e820_type</code>
</li>
</ul>
</details>
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
