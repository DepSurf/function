# Function: <code>apic_intr_mode_select</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff826bcf07)
Location: arch/x86/kernel/apic/apic.c:1227
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
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
In arch/x86/kernel/apic/apic.c (ffffffff826e6cbe)
Location: arch/x86/kernel/apic/apic.c:1231
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
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
In arch/x86/kernel/apic/apic.c (ffffffff8289d807)
Location: arch/x86/kernel/apic/apic.c:1237
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
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
In arch/x86/kernel/apic/apic.c (ffffffff828b5292)
Location: arch/x86/kernel/apic/apic.c:1312
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void apic_intr_mode_select();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff828b8652)
Location: arch/x86/kernel/apic/apic.c:1397
Inline: False
```
**Symbols:**

```
ffffffff828b8652-ffffffff828b876a: apic_intr_mode_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void apic_intr_mode_select();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff82cdd7e1)
Location: arch/x86/kernel/apic/apic.c:1349
Inline: False
```
**Symbols:**

```
ffffffff82cdd7e1-ffffffff82cdd7f7: apic_intr_mode_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void apic_intr_mode_select();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff82fc9b75)
Location: arch/x86/kernel/apic/apic.c:1358
Inline: False
```
**Symbols:**

```
ffffffff82fc9b75-ffffffff82fc9b8b: apic_intr_mode_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void apic_intr_mode_select();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff831d43cf)
Location: arch/x86/kernel/apic/apic.c:1358
Inline: False
```
**Symbols:**

```
ffffffff831d43cf-ffffffff831d449f: apic_intr_mode_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void apic_intr_mode_select();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff832b6f5b)
Location: arch/x86/kernel/apic/apic.c:1355
Inline: False
```
**Symbols:**

```
ffffffff832b6f5b-ffffffff832b702b: apic_intr_mode_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void apic_intr_mode_select();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff83468aa4)
Location: arch/x86/kernel/apic/apic.c:1364
Inline: False
```
**Symbols:**

```
ffffffff83468aa4-ffffffff83468b7a: apic_intr_mode_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void apic_intr_mode_select();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff83e8d2b0)
Location: arch/x86/kernel/apic/apic.c:1360
Inline: False
```
**Symbols:**

```
ffffffff83e8d2b0-ffffffff83e8d3d5: apic_intr_mode_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void apic_intr_mode_select();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff836b0b40)
Location: arch/x86/kernel/apic/apic.c:1362
Inline: False
```
**Symbols:**

```
ffffffff836b0b40-ffffffff836b0c65: apic_intr_mode_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void apic_intr_mode_select();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff838e1270)
Location: arch/x86/kernel/apic/apic.c:1320
Inline: False
```
**Symbols:**

```
ffffffff838e1270-ffffffff838e1366: apic_intr_mode_select (STB_GLOBAL)
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
void apic_intr_mode_select();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff828a6659)
Location: arch/x86/kernel/apic/apic.c:1397
Inline: False
```
**Symbols:**

```
ffffffff828a6659-ffffffff828a6771: apic_intr_mode_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void apic_intr_mode_select();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8289e779)
Location: arch/x86/kernel/apic/apic.c:1397
Inline: False
```
**Symbols:**

```
ffffffff8289e779-ffffffff8289e891: apic_intr_mode_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void apic_intr_mode_select();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff828b9569)
Location: arch/x86/kernel/apic/apic.c:1397
Inline: False
```
**Symbols:**

```
ffffffff828b9569-ffffffff828b9681: apic_intr_mode_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void apic_intr_mode_select();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff828b966a)
Location: arch/x86/kernel/apic/apic.c:1397
Inline: False
```
**Symbols:**

```
ffffffff828b966a-ffffffff828b9782: apic_intr_mode_select (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
