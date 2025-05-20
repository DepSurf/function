# Function: <code>rtc_allocate_device</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct rtc_device *rtc_allocate_device();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff817196f0)
Location: drivers/rtc/class.c:154
Inline: False
Direct callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:rtc_device_register
```
**Symbols:**

```
ffffffff817196f0-ffffffff81719846: rtc_allocate_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct rtc_device *rtc_allocate_device();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff8178a950)
Location: drivers/rtc/class.c:154
Inline: False
Direct callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:rtc_device_register
```
**Symbols:**

```
ffffffff8178a950-ffffffff8178aab1: rtc_allocate_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct rtc_device *rtc_allocate_device();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff817cbb50)
Location: drivers/rtc/class.c:154
Inline: False
Direct callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/rtc/class.c:rtc_device_register
```
**Symbols:**

```
ffffffff817cbb50-ffffffff817cbcb1: rtc_allocate_device (STB_LOCAL)
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
In drivers/rtc/class.c (ffffffff817f31b0)
Location: drivers/rtc/class.c:154
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
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
In drivers/rtc/class.c (ffffffff81833e30)
Location: drivers/rtc/class.c:149
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
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
In drivers/rtc/class.c (ffffffff818657a0)
Location: drivers/rtc/class.c:149
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rtc_device *rtc_allocate_device();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff81938fc0)
Location: drivers/rtc/class.c:193
Inline: False
Direct callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
**Symbols:**

```
ffffffff81938fc0-ffffffff81939131: rtc_allocate_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct rtc_device *rtc_allocate_device();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff8193f1a0)
Location: drivers/rtc/class.c:194
Inline: False
Direct callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
**Symbols:**

```
ffffffff8193f1a0-ffffffff8193f311: rtc_allocate_device (STB_LOCAL)
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
In drivers/rtc/class.c (ffffffff819229d5)
Location: drivers/rtc/class.c:194
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
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
In drivers/rtc/class.c (ffffffff819c5985)
Location: drivers/rtc/class.c:194
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct rtc_device *rtc_allocate_device();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff81b26130)
Location: drivers/rtc/class.c:203
Inline: False
Direct callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
**Symbols:**

```
ffffffff81b26130-ffffffff81b262a4: rtc_allocate_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct rtc_device *rtc_allocate_device();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff81cb9880)
Location: drivers/rtc/class.c:203
Inline: False
Direct callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
**Symbols:**

```
ffffffff81cb9880-ffffffff81cb99f4: rtc_allocate_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct rtc_device *rtc_allocate_device();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff81d20fb0)
Location: drivers/rtc/class.c:203
Inline: False
Direct callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
**Symbols:**

```
ffffffff81d20fb0-ffffffff81d21124: rtc_allocate_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct rtc_device *rtc_allocate_device();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff81dd6ce0)
Location: drivers/rtc/class.c:203
Inline: False
Direct callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
**Symbols:**

```
ffffffff81dd6ce0-ffffffff81dd6e83: rtc_allocate_device (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffff800010aa6b34)
Location: drivers/rtc/class.c:149
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (c0b8564c)
Location: drivers/rtc/class.c:149
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (c000000000b881fc)
Location: drivers/rtc/class.c:149
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffe0006b2fe2)
Location: drivers/rtc/class.c:149
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
</details>
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
In drivers/rtc/class.c (ffffffff81818450)
Location: drivers/rtc/class.c:149
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
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
In drivers/rtc/class.c (ffffffff817dfb40)
Location: drivers/rtc/class.c:149
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
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
In drivers/rtc/class.c (ffffffff81859930)
Location: drivers/rtc/class.c:149
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
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
In drivers/rtc/class.c (ffffffff81874a10)
Location: drivers/rtc/class.c:149
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
