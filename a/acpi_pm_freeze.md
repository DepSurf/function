# Function: <code>acpi_pm_freeze</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_pm_freeze();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff8147b85e)
Location: drivers/acpi/sleep.c:337
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_pm_pre_suspend
```
**Symbols:**

```
ffffffff8147b85e-ffffffff8147b87a: acpi_pm_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_pm_freeze();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff814c9ec9)
Location: drivers/acpi/sleep.c:360
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_pm_pre_suspend
```
**Symbols:**

```
ffffffff814c9ec9-ffffffff814c9ee5: acpi_pm_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_pm_freeze();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff814ebe24)
Location: drivers/acpi/sleep.c:343
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_pm_pre_suspend
```
**Symbols:**

```
ffffffff814ebe24-ffffffff814ebe40: acpi_pm_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_pm_freeze();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff814f8269)
Location: drivers/acpi/sleep.c:362
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_pm_pre_suspend
```
**Symbols:**

```
ffffffff814f8240-ffffffff814f825c: acpi_pm_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_pm_freeze();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81539729)
Location: drivers/acpi/sleep.c:383
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_pm_pre_suspend
```
**Symbols:**

```
ffffffff81539700-ffffffff8153971c: acpi_pm_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int acpi_pm_freeze();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff8156f375)
Location: drivers/acpi/sleep.c:412
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_pm_pre_suspend
```
**Symbols:**

```
ffffffff8156f350-ffffffff8156f36c: acpi_pm_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int acpi_pm_freeze();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81586f55)
Location: drivers/acpi/sleep.c:412
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_pm_pre_suspend
```
**Symbols:**

```
ffffffff81586f30-ffffffff81586f4c: acpi_pm_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int acpi_pm_freeze();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815b7bb5)
Location: drivers/acpi/sleep.c:410
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_pm_pre_suspend
```
**Symbols:**

```
ffffffff815b7b90-ffffffff815b7bac: acpi_pm_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int acpi_pm_freeze();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815d8df5)
Location: drivers/acpi/sleep.c:401
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_pm_pre_suspend
```
**Symbols:**

```
ffffffff815d8dd0-ffffffff815d8dec: acpi_pm_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_pm_freeze();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81682f80)
Location: drivers/acpi/sleep.c:404
Inline: True
```
**Symbols:**

```
ffffffff81682f80-ffffffff81682f9c: acpi_pm_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int acpi_pm_freeze();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff816a1440)
Location: drivers/acpi/sleep.c:400
Inline: True
```
**Symbols:**

```
ffffffff816a1440-ffffffff816a145c: acpi_pm_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_pm_freeze();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81684230)
Location: drivers/acpi/sleep.c:400
Inline: True
```
**Symbols:**

```
ffffffff81684230-ffffffff8168424c: acpi_pm_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_pm_freeze();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff816f9450)
Location: drivers/acpi/sleep.c:401
Inline: True
```
**Symbols:**

```
ffffffff816f9450-ffffffff816f946c: acpi_pm_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int acpi_pm_freeze();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81826780)
Location: drivers/acpi/sleep.c:420
Inline: True
```
**Symbols:**

```
ffffffff81826780-ffffffff818267a0: acpi_pm_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int acpi_pm_freeze();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff819582a0)
Location: drivers/acpi/sleep.c:424
Inline: True
```
**Symbols:**

```
ffffffff819582a0-ffffffff819582c0: acpi_pm_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int acpi_pm_freeze();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff8199e780)
Location: drivers/acpi/sleep.c:424
Inline: True
```
**Symbols:**

```
ffffffff8199e780-ffffffff8199e7a0: acpi_pm_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_pm_freeze();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff819e6e20)
Location: drivers/acpi/sleep.c:424
Inline: True
```
**Symbols:**

```
ffffffff819e6e20-ffffffff819e6e40: acpi_pm_freeze (STB_LOCAL)
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
int acpi_pm_freeze();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815cc085)
Location: drivers/acpi/sleep.c:401
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_pm_pre_suspend
```
**Symbols:**

```
ffffffff815cc020-ffffffff815cc03c: acpi_pm_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int acpi_pm_freeze();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815b51a5)
Location: drivers/acpi/sleep.c:401
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_pm_pre_suspend
```
**Symbols:**

```
ffffffff815b5180-ffffffff815b519c: acpi_pm_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int acpi_pm_freeze();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815cd0d5)
Location: drivers/acpi/sleep.c:401
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_pm_pre_suspend
```
**Symbols:**

```
ffffffff815cd0b0-ffffffff815cd0cc: acpi_pm_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int acpi_pm_freeze();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815e6f75)
Location: drivers/acpi/sleep.c:401
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_pm_pre_suspend
```
**Symbols:**

```
ffffffff815e6f50-ffffffff815e6f6c: acpi_pm_freeze (STB_LOCAL)
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
