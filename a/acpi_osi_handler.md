# Function: <code>acpi_osi_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u32 acpi_osi_handler(acpi_string interface, u32 supported);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8147998a)
Location: drivers/acpi/osl.c:142
Inline: False
```
**Symbols:**

```
ffffffff8147998a-ffffffff81479a2d: acpi_osi_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
u32 acpi_osi_handler(acpi_string interface, u32 supported);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff814c7e39)
Location: drivers/acpi/osi.c:61
Inline: True
```
**Symbols:**

```
ffffffff814c7e39-ffffffff814c7f21: acpi_osi_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
u32 acpi_osi_handler(acpi_string interface, u32 supported);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff814e9d49)
Location: drivers/acpi/osi.c:61
Inline: True
```
**Symbols:**

```
ffffffff814e9d49-ffffffff814e9e31: acpi_osi_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
u32 acpi_osi_handler(acpi_string interface, u32 supported);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff814f5a00)
Location: drivers/acpi/osi.c:61
Inline: True
```
**Symbols:**

```
ffffffff814f5a00-ffffffff814f5af0: acpi_osi_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
u32 acpi_osi_handler(acpi_string interface, u32 supported);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff81536290)
Location: drivers/acpi/osi.c:62
Inline: True
```
**Symbols:**

```
ffffffff81536290-ffffffff81536380: acpi_osi_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 acpi_osi_handler(acpi_string interface, u32 supported);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/osi.c (0)
Location: drivers/acpi/osi.c:79
Inline: True
```
**Symbols:**

```
ffffffff8156be30-ffffffff8156be95: acpi_osi_handler (STB_LOCAL)
ffffffff8156be95-ffffffff8156bf41: acpi_osi_handler.cold.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 acpi_osi_handler(acpi_string interface, u32 supported);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/osi.c (ffffffff81583a40)
Location: drivers/acpi/osi.c:86
Inline: True
```
**Symbols:**

```
ffffffff815839f0-ffffffff81583a55: acpi_osi_handler (STB_LOCAL)
ffffffff81583a55-ffffffff81583b01: acpi_osi_handler.cold.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 acpi_osi_handler(acpi_string interface, u32 supported);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/osi.c (ffffffff815b4610)
Location: drivers/acpi/osi.c:73
Inline: True
```
**Symbols:**

```
ffffffff815b45c0-ffffffff815b4625: acpi_osi_handler (STB_LOCAL)
ffffffff815b4625-ffffffff815b46d1: acpi_osi_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 acpi_osi_handler(acpi_string interface, u32 supported);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/osi.c (ffffffff815d5840)
Location: drivers/acpi/osi.c:73
Inline: True
```
**Symbols:**

```
ffffffff815d57f0-ffffffff815d5855: acpi_osi_handler (STB_LOCAL)
ffffffff815d5855-ffffffff815d5901: acpi_osi_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
u32 acpi_osi_handler(acpi_string interface, u32 supported);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osi.c (0)
Location: drivers/acpi/osi.c:73
Inline: False
```
**Symbols:**

```
ffffffff8167f4a0-ffffffff8167f505: acpi_osi_handler (STB_LOCAL)
ffffffff8167f505-ffffffff8167f5b1: acpi_osi_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
u32 acpi_osi_handler(acpi_string interface, u32 supported);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osi.c (0)
Location: drivers/acpi/osi.c:73
Inline: False
```
**Symbols:**

```
ffffffff8169dfc0-ffffffff8169e025: acpi_osi_handler (STB_LOCAL)
ffffffff81c007b0-ffffffff81c0085c: acpi_osi_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
u32 acpi_osi_handler(acpi_string interface, u32 supported);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osi.c (0)
Location: drivers/acpi/osi.c:73
Inline: False
```
**Symbols:**

```
ffffffff81680d10-ffffffff81680d6c: acpi_osi_handler (STB_LOCAL)
ffffffff81bf2293-ffffffff81bf233f: acpi_osi_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u32 acpi_osi_handler(acpi_string interface, u32 supported);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osi.c (0)
Location: drivers/acpi/osi.c:73
Inline: False
```
**Symbols:**

```
ffffffff816f5dd0-ffffffff816f5e49: acpi_osi_handler (STB_LOCAL)
ffffffff81ceeaf5-ffffffff81ceebcd: acpi_osi_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u32 acpi_osi_handler(acpi_string interface, u32 supported);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osi.c (0)
Location: drivers/acpi/osi.c:73
Inline: False
```
**Symbols:**

```
ffffffff81822b90-ffffffff81822c15: acpi_osi_handler (STB_LOCAL)
ffffffff81eb6250-ffffffff81eb6328: acpi_osi_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u32 acpi_osi_handler(acpi_string interface, u32 supported);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osi.c (0)
Location: drivers/acpi/osi.c:49
Inline: False
```
**Symbols:**

```
ffffffff81953ac0-ffffffff81953be2: acpi_osi_handler (STB_LOCAL)
ffffffff820916de-ffffffff82091707: acpi_osi_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u32 acpi_osi_handler(acpi_string interface, u32 supported);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osi.c (0)
Location: drivers/acpi/osi.c:49
Inline: False
```
**Symbols:**

```
ffffffff81999ec0-ffffffff81999fe2: acpi_osi_handler (STB_LOCAL)
ffffffff82112051-ffffffff8211207a: acpi_osi_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u32 acpi_osi_handler(acpi_string interface, u32 supported);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osi.c (0)
Location: drivers/acpi/osi.c:49
Inline: False
```
**Symbols:**

```
ffffffff819e2340-ffffffff819e2462: acpi_osi_handler (STB_LOCAL)
ffffffff821efd55-ffffffff821efd7e: acpi_osi_handler.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
u32 acpi_osi_handler(acpi_string interface, u32 supported);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffff800010762da8)
Location: drivers/acpi/osi.c:73
Inline: True
```
**Symbols:**

```
ffff800010762da8-ffff800010762ed8: acpi_osi_handler (STB_LOCAL)
```
</details>
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 acpi_osi_handler(acpi_string interface, u32 supported);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/osi.c (ffffffff815c9590)
Location: drivers/acpi/osi.c:73
Inline: True
```
**Symbols:**

```
ffffffff815c9540-ffffffff815c95a5: acpi_osi_handler (STB_LOCAL)
ffffffff815c95a5-ffffffff815c9651: acpi_osi_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 acpi_osi_handler(acpi_string interface, u32 supported);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/osi.c (ffffffff815b2620)
Location: drivers/acpi/osi.c:73
Inline: True
```
**Symbols:**

```
ffffffff815b25d0-ffffffff815b2635: acpi_osi_handler (STB_LOCAL)
ffffffff815b2635-ffffffff815b26e1: acpi_osi_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 acpi_osi_handler(acpi_string interface, u32 supported);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/osi.c (ffffffff815c9b20)
Location: drivers/acpi/osi.c:73
Inline: True
```
**Symbols:**

```
ffffffff815c9ad0-ffffffff815c9b35: acpi_osi_handler (STB_LOCAL)
ffffffff815c9b35-ffffffff815c9be1: acpi_osi_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 acpi_osi_handler(acpi_string interface, u32 supported);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/osi.c (ffffffff815e3980)
Location: drivers/acpi/osi.c:73
Inline: True
```
**Symbols:**

```
ffffffff815e3930-ffffffff815e3995: acpi_osi_handler (STB_LOCAL)
ffffffff815e3995-ffffffff815e3a41: acpi_osi_handler.cold (STB_LOCAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
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
