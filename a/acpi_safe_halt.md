# Function: <code>acpi_safe_halt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_safe_halt();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff814acc5d)
Location: drivers/acpi/processor_idle.c:114
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
**Symbols:**

```
ffffffff814acc5d-ffffffff814acc88: acpi_safe_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_safe_halt();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff814fc4f8)
Location: drivers/acpi/processor_idle.c:118
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
**Symbols:**

```
ffffffff814fc4f8-ffffffff814fc523: acpi_safe_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_safe_halt();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff818d3fce)
Location: drivers/acpi/processor_idle.c:119
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
**Symbols:**

```
ffffffff818d3fce-ffffffff818d3ff5: acpi_safe_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81530c37)
Location: drivers/acpi/processor_idle.c:119
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
**Symbols:**

```
ffffffff8190b150-ffffffff8190b169: acpi_safe_halt.part.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_safe_halt();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff819954e0)
Location: drivers/acpi/processor_idle.c:121
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
**Symbols:**

```
ffffffff819954e0-ffffffff8199550b: acpi_safe_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_safe_halt();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff819f1a20)
Location: drivers/acpi/processor_idle.c:121
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
**Symbols:**

```
ffffffff819f1a20-ffffffff819f1a4b: acpi_safe_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_safe_halt();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81a2cf30)
Location: drivers/acpi/processor_idle.c:121
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
**Symbols:**

```
ffffffff81a2cf30-ffffffff81a2cf5b: acpi_safe_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_safe_halt();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81a9d0a0)
Location: drivers/acpi/processor_idle.c:108
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
**Symbols:**

```
ffffffff81a9d0a0-ffffffff81a9d0ca: acpi_safe_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_safe_halt();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81ad48f0)
Location: drivers/acpi/processor_idle.c:108
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
**Symbols:**

```
ffffffff81ad48f0-ffffffff81ad491a: acpi_safe_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_safe_halt();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81bcc8f0)
Location: drivers/acpi/processor_idle.c:108
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff81bcc8f0-ffffffff81bcc91a: acpi_safe_halt (STB_LOCAL)
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
In drivers/acpi/processor_idle.c (ffffffff81c45458)
Location: drivers/acpi/processor_idle.c:108
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
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
In drivers/acpi/processor_idle.c (ffffffff81c386d8)
Location: drivers/acpi/processor_idle.c:106
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
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
In drivers/acpi/processor_idle.c (ffffffff81d56fb8)
Location: drivers/acpi/processor_idle.c:106
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
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
In drivers/acpi/processor_idle.c (ffffffff81f294c4)
Location: drivers/acpi/processor_idle.c:108
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
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
In drivers/acpi/processor_idle.c (ffffffff820d52ed)
Location: drivers/acpi/processor_idle.c:109
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_safe_halt();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff82143910)
Location: drivers/acpi/processor_idle.c:109
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
**Symbols:**

```
ffffffff82143910-ffffffff82143967: acpi_safe_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_safe_halt();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff82226030)
Location: drivers/acpi/processor_idle.c:109
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
**Symbols:**

```
ffffffff82226030-ffffffff82226087: acpi_safe_halt (STB_LOCAL)
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
void acpi_safe_halt();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81a73760)
Location: drivers/acpi/processor_idle.c:108
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
**Symbols:**

```
ffffffff81a73760-ffffffff81a7378a: acpi_safe_halt (STB_LOCAL)
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
In drivers/acpi/processor_idle.c (ffffffff815efed2)
Location: drivers/acpi/processor_idle.c:108
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_safe_halt();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81adfb70)
Location: drivers/acpi/processor_idle.c:108
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
**Symbols:**

```
ffffffff81adfb70-ffffffff81adfb9a: acpi_safe_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_safe_halt();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81aec370)
Location: drivers/acpi/processor_idle.c:108
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_do_entry
```
**Symbols:**

```
ffffffff81aec370-ffffffff81aec39a: acpi_safe_halt (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
