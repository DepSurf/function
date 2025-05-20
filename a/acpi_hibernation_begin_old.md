# Function: <code>acpi_hibernation_begin_old</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_hibernation_begin_old();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff8147bb63)
Location: drivers/acpi/sleep.c:757
Inline: False
```
**Symbols:**

```
ffffffff8147bb63-ffffffff8147bbb1: acpi_hibernation_begin_old (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_hibernation_begin_old();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff814ca11f)
Location: drivers/acpi/sleep.c:814
Inline: False
```
**Symbols:**

```
ffffffff814ca11f-ffffffff814ca16d: acpi_hibernation_begin_old (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_hibernation_begin_old();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff814ec07a)
Location: drivers/acpi/sleep.c:797
Inline: False
```
**Symbols:**

```
ffffffff814ec07a-ffffffff814ec0c8: acpi_hibernation_begin_old (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_hibernation_begin_old();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff814f8780)
Location: drivers/acpi/sleep.c:959
Inline: True
```
**Symbols:**

```
ffffffff814f8780-ffffffff814f87d1: acpi_hibernation_begin_old (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_hibernation_begin_old();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff8153a220)
Location: drivers/acpi/sleep.c:1161
Inline: True
```
**Symbols:**

```
ffffffff8153a220-ffffffff8153a271: acpi_hibernation_begin_old (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int acpi_hibernation_begin_old();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff8156ffb0)
Location: drivers/acpi/sleep.c:1193
Inline: True
```
**Symbols:**

```
ffffffff8156ffb0-ffffffff81570001: acpi_hibernation_begin_old (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int acpi_hibernation_begin_old();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81587b70)
Location: drivers/acpi/sleep.c:1199
Inline: True
```
**Symbols:**

```
ffffffff81587b70-ffffffff81587bc1: acpi_hibernation_begin_old (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int acpi_hibernation_begin_old(pm_message_t stage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815b85b0)
Location: drivers/acpi/sleep.c:1197
Inline: False
```
**Symbols:**

```
ffffffff815b85b0-ffffffff815b8615: acpi_hibernation_begin_old (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int acpi_hibernation_begin_old(pm_message_t stage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815d9820)
Location: drivers/acpi/sleep.c:1238
Inline: False
```
**Symbols:**

```
ffffffff815d9820-ffffffff815d9885: acpi_hibernation_begin_old (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_hibernation_begin_old(pm_message_t stage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:1236
Inline: False
```
**Symbols:**

```
ffffffff81683a70-ffffffff81683b04: acpi_hibernation_begin_old (STB_LOCAL)
ffffffff81683e5d-ffffffff81683e6e: acpi_hibernation_begin_old.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_hibernation_begin_old(pm_message_t stage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:955
Inline: False
```
**Symbols:**

```
ffffffff816a1960-ffffffff816a19f4: acpi_hibernation_begin_old (STB_LOCAL)
ffffffff81c00dcc-ffffffff81c00ddd: acpi_hibernation_begin_old.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int acpi_hibernation_begin_old(pm_message_t stage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:955
Inline: False
```
**Symbols:**

```
ffffffff81684920-ffffffff816849b4: acpi_hibernation_begin_old (STB_LOCAL)
ffffffff81bf2852-ffffffff81bf2863: acpi_hibernation_begin_old.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_hibernation_begin_old(pm_message_t stage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:956
Inline: False
```
**Symbols:**

```
ffffffff816f9bd0-ffffffff816f9c74: acpi_hibernation_begin_old (STB_LOCAL)
ffffffff81cef1b0-ffffffff81cef1d6: acpi_hibernation_begin_old.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_hibernation_begin_old(pm_message_t stage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81eb68de)
Location: drivers/acpi/sleep.c:966
Inline: False
```
**Symbols:**

```
ffffffff81eb68de-ffffffff81eb6988: acpi_hibernation_begin_old (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int acpi_hibernation_begin_old(pm_message_t stage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:973
Inline: False
```
**Symbols:**

```
ffffffff81958d60-ffffffff81958e11: acpi_hibernation_begin_old (STB_LOCAL)
ffffffff82091892-ffffffff820918a7: acpi_hibernation_begin_old.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int acpi_hibernation_begin_old(pm_message_t stage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:987
Inline: False
```
**Symbols:**

```
ffffffff8199f1d0-ffffffff8199f281: acpi_hibernation_begin_old (STB_LOCAL)
ffffffff82112188-ffffffff8211219d: acpi_hibernation_begin_old.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int acpi_hibernation_begin_old(pm_message_t stage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (0)
Location: drivers/acpi/sleep.c:987
Inline: False
```
**Symbols:**

```
ffffffff819e7870-ffffffff819e7921: acpi_hibernation_begin_old (STB_LOCAL)
ffffffff821efe8c-ffffffff821efea1: acpi_hibernation_begin_old.cold (STB_LOCAL)
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
int acpi_hibernation_begin_old(pm_message_t stage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815cc200)
Location: drivers/acpi/sleep.c:1238
Inline: True
```
**Symbols:**

```
ffffffff815cc200-ffffffff815cc258: acpi_hibernation_begin_old (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int acpi_hibernation_begin_old(pm_message_t stage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815b53a0)
Location: drivers/acpi/sleep.c:1238
Inline: False
```
**Symbols:**

```
ffffffff815b53a0-ffffffff815b5405: acpi_hibernation_begin_old (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int acpi_hibernation_begin_old(pm_message_t stage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815cdb00)
Location: drivers/acpi/sleep.c:1238
Inline: False
```
**Symbols:**

```
ffffffff815cdb00-ffffffff815cdb65: acpi_hibernation_begin_old (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int acpi_hibernation_begin_old(pm_message_t stage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815e79a0)
Location: drivers/acpi/sleep.c:1238
Inline: False
```
**Symbols:**

```
ffffffff815e79a0-ffffffff815e7a05: acpi_hibernation_begin_old (STB_LOCAL)
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
