# Function: <code>clear_IO_APIC_pin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void clear_IO_APIC_pin(unsigned int apic, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81056920)
Location: arch/x86/kernel/apic/io_apic.c:543
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff81056920-ffffffff81056a4f: clear_IO_APIC_pin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void clear_IO_APIC_pin(unsigned int apic, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81056ba0)
Location: arch/x86/kernel/apic/io_apic.c:543
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC
```
**Symbols:**

```
ffffffff81056ba0-ffffffff81056cd0: clear_IO_APIC_pin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void clear_IO_APIC_pin(unsigned int apic, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81059950)
Location: arch/x86/kernel/apic/io_apic.c:542
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC
```
**Symbols:**

```
ffffffff81059950-ffffffff81059a80: clear_IO_APIC_pin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void clear_IO_APIC_pin(unsigned int apic, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810590e0)
Location: arch/x86/kernel/apic/io_apic.c:542
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC
```
**Symbols:**

```
ffffffff810590e0-ffffffff8105920f: clear_IO_APIC_pin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void clear_IO_APIC_pin(unsigned int apic, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105d5c0)
Location: arch/x86/kernel/apic/io_apic.c:543
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC
```
**Symbols:**

```
ffffffff8105d5c0-ffffffff8105d6ef: clear_IO_APIC_pin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void clear_IO_APIC_pin(unsigned int apic, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:544
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC
```
**Symbols:**

```
ffffffff81060450-ffffffff81060560: clear_IO_APIC_pin (STB_LOCAL)
ffffffff81062068-ffffffff8106208a: clear_IO_APIC_pin.cold.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void clear_IO_APIC_pin(unsigned int apic, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:544
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC
```
**Symbols:**

```
ffffffff810662a0-ffffffff810663b0: clear_IO_APIC_pin (STB_LOCAL)
ffffffff81067d7c-ffffffff81067d9e: clear_IO_APIC_pin.cold.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void clear_IO_APIC_pin(unsigned int apic, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:545
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC
```
**Symbols:**

```
ffffffff810699b0-ffffffff81069ad1: clear_IO_APIC_pin (STB_LOCAL)
ffffffff8106b518-ffffffff8106b53a: clear_IO_APIC_pin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void clear_IO_APIC_pin(unsigned int apic, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:545
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC
```
**Symbols:**

```
ffffffff8106a270-ffffffff8106a391: clear_IO_APIC_pin (STB_LOCAL)
ffffffff8106bea8-ffffffff8106beca: clear_IO_APIC_pin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void clear_IO_APIC_pin(unsigned int apic, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:532
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC
```
**Symbols:**

```
ffffffff81071770-ffffffff81071950: clear_IO_APIC_pin (STB_LOCAL)
ffffffff810731da-ffffffff810731fc: clear_IO_APIC_pin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void clear_IO_APIC_pin(unsigned int apic, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:519
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC
```
**Symbols:**

```
ffffffff81072da0-ffffffff81072f80: clear_IO_APIC_pin (STB_LOCAL)
ffffffff81bd7322-ffffffff81bd7344: clear_IO_APIC_pin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void clear_IO_APIC_pin(unsigned int apic, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:519
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC
```
**Symbols:**

```
ffffffff81073870-ffffffff81073a4e: clear_IO_APIC_pin (STB_LOCAL)
ffffffff81bc94d5-ffffffff81bc94f7: clear_IO_APIC_pin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void clear_IO_APIC_pin(unsigned int apic, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81080900)
Location: arch/x86/kernel/apic/io_apic.c:519
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC
```
**Symbols:**

```
ffffffff81080900-ffffffff81080b15: clear_IO_APIC_pin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void clear_IO_APIC_pin(unsigned int apic, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81090610)
Location: arch/x86/kernel/apic/io_apic.c:520
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC
```
**Symbols:**

```
ffffffff81090610-ffffffff81090833: clear_IO_APIC_pin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void clear_IO_APIC_pin(unsigned int apic, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a50f0)
Location: arch/x86/kernel/apic/io_apic.c:520
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
```
**Symbols:**

```
ffffffff810a50f0-ffffffff810a5328: clear_IO_APIC_pin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void clear_IO_APIC_pin(unsigned int apic, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a81e0)
Location: arch/x86/kernel/apic/io_apic.c:521
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
```
**Symbols:**

```
ffffffff810a81e0-ffffffff810a841c: clear_IO_APIC_pin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void clear_IO_APIC_pin(unsigned int apic, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810af270)
Location: arch/x86/kernel/apic/io_apic.c:521
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
```
**Symbols:**

```
ffffffff810af270-ffffffff810af4ac: clear_IO_APIC_pin (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void clear_IO_APIC_pin(unsigned int apic, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:545
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC
```
**Symbols:**

```
ffffffff81069d60-ffffffff81069e81: clear_IO_APIC_pin (STB_LOCAL)
ffffffff8106b998-ffffffff8106b9ba: clear_IO_APIC_pin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void clear_IO_APIC_pin(unsigned int apic, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:545
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC
```
**Symbols:**

```
ffffffff8105a0c0-ffffffff8105a1e1: clear_IO_APIC_pin (STB_LOCAL)
ffffffff8105bcc8-ffffffff8105bcea: clear_IO_APIC_pin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void clear_IO_APIC_pin(unsigned int apic, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:545
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC
```
**Symbols:**

```
ffffffff8106a210-ffffffff8106a331: clear_IO_APIC_pin (STB_LOCAL)
ffffffff8106be48-ffffffff8106be6a: clear_IO_APIC_pin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void clear_IO_APIC_pin(unsigned int apic, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:545
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC
```
**Symbols:**

```
ffffffff8106b990-ffffffff8106bab1: clear_IO_APIC_pin (STB_LOCAL)
ffffffff8106d548-ffffffff8106d56a: clear_IO_APIC_pin.cold (STB_LOCAL)
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
