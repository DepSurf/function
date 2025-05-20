# Function: <code>special_hex_number</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (ffffffff8143b9a0)
Location: lib/vsprintf.c:522
Inline: True
Direct callers:
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
```
**Symbols:**

```
ffffffff8143b9a0-ffffffff8143b9b5: special_hex_number.constprop.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (ffffffff81458980)
Location: lib/vsprintf.c:522
Inline: True
Direct callers:
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
```
**Symbols:**

```
ffffffff81458980-ffffffff81458995: special_hex_number.constprop.7 (STB_LOCAL)
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
In lib/vsprintf.c (ffffffff818fa360)
Location: lib/vsprintf.c:523
Inline: True
Direct callers:
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
```
**Symbols:**

```
ffffffff818fa360-ffffffff818fa375: special_hex_number.constprop.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (ffffffff81980fe0)
Location: lib/vsprintf.c:525
Inline: True
Direct callers:
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
```
**Symbols:**

```
ffffffff81980fe0-ffffffff81980ff5: special_hex_number.constprop.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (ffffffff819dd0b0)
Location: lib/vsprintf.c:534
Inline: True
Direct callers:
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
```
**Symbols:**

```
ffffffff819dd0b0-ffffffff819dd0c5: special_hex_number.constprop.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (ffffffff81a15590)
Location: lib/vsprintf.c:535
Inline: True
Direct callers:
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
```
**Symbols:**

```
ffffffff81a15590-ffffffff81a155a5: special_hex_number.constprop.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (ffffffff81a85040)
Location: lib/vsprintf.c:537
Inline: True
Direct callers:
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
```
**Symbols:**

```
ffffffff81a85040-ffffffff81a85055: special_hex_number.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (ffffffff81abc2b0)
Location: lib/vsprintf.c:537
Inline: True
Direct callers:
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
```
**Symbols:**

```
ffffffff81abc2b0-ffffffff81abc2c5: special_hex_number.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (ffffffff815f4a70)
Location: lib/vsprintf.c:540
Inline: True
Direct callers:
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
```
**Symbols:**

```
ffffffff815f4a70-ffffffff815f4a85: special_hex_number.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (ffffffff816190e0)
Location: lib/vsprintf.c:543
Inline: True
Direct callers:
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
```
**Symbols:**

```
ffffffff816190e0-ffffffff816190f5: special_hex_number.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *special_hex_number(char *buf, char *end, long long unsigned int num, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815fbbd0)
Location: lib/vsprintf.c:569
Inline: False
Direct callers:
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:fourcc_string
  - lib/vsprintf.c:netdev_bits
```
**Symbols:**

```
ffffffff815fbbd0-ffffffff815fbbf5: special_hex_number (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *special_hex_number(char *buf, char *end, long long unsigned int num, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81669680)
Location: lib/vsprintf.c:570
Inline: False
Direct callers:
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:fourcc_string
  - lib/vsprintf.c:netdev_bits
```
**Symbols:**

```
ffffffff81669680-ffffffff816696a5: special_hex_number (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *special_hex_number(char *buf, char *end, long long unsigned int num, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff817831b0)
Location: lib/vsprintf.c:575
Inline: False
Direct callers:
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:fourcc_string
  - lib/vsprintf.c:netdev_bits
```
**Symbols:**

```
ffffffff817831b0-ffffffff817831e1: special_hex_number (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *special_hex_number(char *buf, char *end, long long unsigned int num, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff82040170)
Location: lib/vsprintf.c:576
Inline: False
Direct callers:
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:fourcc_string
  - lib/vsprintf.c:netdev_bits
```
**Symbols:**

```
ffffffff82040170-ffffffff820401a1: special_hex_number (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *special_hex_number(char *buf, char *end, long long unsigned int num, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff820be680)
Location: lib/vsprintf.c:576
Inline: False
Direct callers:
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:fourcc_string
  - lib/vsprintf.c:netdev_bits
```
**Symbols:**

```
ffffffff820be680-ffffffff820be6b1: special_hex_number (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *special_hex_number(char *buf, char *end, long long unsigned int num, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff82198f00)
Location: lib/vsprintf.c:578
Inline: False
Direct callers:
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:fourcc_string
  - lib/vsprintf.c:netdev_bits
```
**Symbols:**

```
ffffffff82198f00-ffffffff82198f31: special_hex_number (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (ffff800010d966d0)
Location: lib/vsprintf.c:537
Inline: True
Direct callers:
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
```
**Symbols:**

```
ffff800010d966d0-ffff800010d966f0: special_hex_number.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *special_hex_number(char *buf, char *end, long long unsigned int num, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c0e91a68)
Location: lib/vsprintf.c:537
Inline: False
Direct callers:
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
```
**Symbols:**

```
c0e91a68-c0e91adc: special_hex_number (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (c000000000edc8f0)
Location: lib/vsprintf.c:537
Inline: True
Direct callers:
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
```
**Symbols:**

```
c000000000edc8f0-c000000000edc90c: special_hex_number.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (ffffffe0008c07c8)
Location: lib/vsprintf.c:537
Inline: True
Direct callers:
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
```
**Symbols:**

```
ffffffe0008c07c8-ffffffe0008c07e8: special_hex_number.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (ffffffff81a5b100)
Location: lib/vsprintf.c:537
Inline: True
Direct callers:
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
```
**Symbols:**

```
ffffffff81a5b100-ffffffff81a5b115: special_hex_number.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (ffffffff81a181e0)
Location: lib/vsprintf.c:537
Inline: True
Direct callers:
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
```
**Symbols:**

```
ffffffff81a181e0-ffffffff81a181f5: special_hex_number.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (ffffffff81ac74f0)
Location: lib/vsprintf.c:537
Inline: True
Direct callers:
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
```
**Symbols:**

```
ffffffff81ac74f0-ffffffff81ac7505: special_hex_number.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (ffffffff81ad39d0)
Location: lib/vsprintf.c:537
Inline: True
Direct callers:
  - lib/vsprintf.c:address_val
  - lib/vsprintf.c:netdev_bits
```
**Symbols:**

```
ffffffff81ad39d0-ffffffff81ad39e5: special_hex_number.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
