# Function: <code>acpi_hibernation_begin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_hibernation_begin();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff8147bc92)
Location: drivers/acpi/sleep.c:690
Inline: False
```
**Symbols:**

```
ffffffff8147bc92-ffffffff8147bccc: acpi_hibernation_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_hibernation_begin();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff814ca2b3)
Location: drivers/acpi/sleep.c:746
Inline: False
```
**Symbols:**

```
ffffffff814ca2b3-ffffffff814ca2ed: acpi_hibernation_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_hibernation_begin();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff814ec1cf)
Location: drivers/acpi/sleep.c:729
Inline: False
```
**Symbols:**

```
ffffffff814ec1cf-ffffffff814ec209: acpi_hibernation_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_hibernation_begin();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff814f8300)
Location: drivers/acpi/sleep.c:891
Inline: False
```
**Symbols:**

```
ffffffff814f8300-ffffffff814f8338: acpi_hibernation_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_hibernation_begin();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815397c0)
Location: drivers/acpi/sleep.c:1093
Inline: False
```
**Symbols:**

```
ffffffff815397c0-ffffffff815397f8: acpi_hibernation_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int acpi_hibernation_begin();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff8156f410)
Location: drivers/acpi/sleep.c:1125
Inline: False
```
**Symbols:**

```
ffffffff8156f410-ffffffff8156f448: acpi_hibernation_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int acpi_hibernation_begin();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81586ff0)
Location: drivers/acpi/sleep.c:1131
Inline: False
```
**Symbols:**

```
ffffffff81586ff0-ffffffff81587028: acpi_hibernation_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int acpi_hibernation_begin(pm_message_t stage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815b7c40)
Location: drivers/acpi/sleep.c:1125
Inline: False
```
**Symbols:**

```
ffffffff815b7c40-ffffffff815b7c8b: acpi_hibernation_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int acpi_hibernation_begin(pm_message_t stage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815d8e80)
Location: drivers/acpi/sleep.c:1166
Inline: False
```
**Symbols:**

```
ffffffff815d8e80-ffffffff815d8ecb: acpi_hibernation_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_hibernation_begin(pm_message_t stage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:1164
Inline: False
```
**Symbols:**

```
ffffffff81683b80-ffffffff81683be8: acpi_hibernation_begin (STB_LOCAL)
ffffffff81683e90-ffffffff81683ea1: acpi_hibernation_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_hibernation_begin(pm_message_t stage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:883
Inline: False
```
**Symbols:**

```
ffffffff816a1a70-ffffffff816a1ad8: acpi_hibernation_begin (STB_LOCAL)
ffffffff81c00dff-ffffffff81c00e10: acpi_hibernation_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int acpi_hibernation_begin(pm_message_t stage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:883
Inline: False
```
**Symbols:**

```
ffffffff81684710-ffffffff81684778: acpi_hibernation_begin (STB_LOCAL)
ffffffff81bf2841-ffffffff81bf2852: acpi_hibernation_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_hibernation_begin(pm_message_t stage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:884
Inline: False
```
**Symbols:**

```
ffffffff816f99b0-ffffffff816f9a27: acpi_hibernation_begin (STB_LOCAL)
ffffffff81cef18a-ffffffff81cef1b0: acpi_hibernation_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_hibernation_begin(pm_message_t stage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:896
Inline: False
```
**Symbols:**

```
ffffffff81826dc0-ffffffff81826e4b: acpi_hibernation_begin (STB_LOCAL)
ffffffff81eb6ad7-ffffffff81eb6afd: acpi_hibernation_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int acpi_hibernation_begin(pm_message_t stage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:903
Inline: False
```
**Symbols:**

```
ffffffff81958cb0-ffffffff81958d44: acpi_hibernation_begin (STB_LOCAL)
ffffffff8209187d-ffffffff82091892: acpi_hibernation_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int acpi_hibernation_begin(pm_message_t stage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:917
Inline: False
```
**Symbols:**

```
ffffffff8199f120-ffffffff8199f1b4: acpi_hibernation_begin (STB_LOCAL)
ffffffff82112173-ffffffff82112188: acpi_hibernation_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int acpi_hibernation_begin(pm_message_t stage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:917
Inline: False
```
**Symbols:**

```
ffffffff819e77c0-ffffffff819e7854: acpi_hibernation_begin (STB_LOCAL)
ffffffff821efe77-ffffffff821efe8c: acpi_hibernation_begin.cold (STB_LOCAL)
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
int acpi_hibernation_begin(pm_message_t stage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815cc0d0)
Location: drivers/acpi/sleep.c:1166
Inline: False
```
**Symbols:**

```
ffffffff815cc0d0-ffffffff815cc108: acpi_hibernation_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int acpi_hibernation_begin(pm_message_t stage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815b5230)
Location: drivers/acpi/sleep.c:1166
Inline: False
```
**Symbols:**

```
ffffffff815b5230-ffffffff815b527b: acpi_hibernation_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int acpi_hibernation_begin(pm_message_t stage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815cd160)
Location: drivers/acpi/sleep.c:1166
Inline: False
```
**Symbols:**

```
ffffffff815cd160-ffffffff815cd1ab: acpi_hibernation_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int acpi_hibernation_begin(pm_message_t stage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815e7000)
Location: drivers/acpi/sleep.c:1166
Inline: False
```
**Symbols:**

```
ffffffff815e7000-ffffffff815e704b: acpi_hibernation_begin (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>pm_message_t stage</code>
</li>
</ul>
</details>
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
