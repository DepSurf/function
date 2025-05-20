# Function: <code>acpi_power_off</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void acpi_power_off();
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff8147b71b)
Location: drivers/acpi/sleep.c:824
Inline: False
```
```
In drivers/acpi/power.c (ffffffff8148898f)
Location: drivers/acpi/power.c:302
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_on_list
  - drivers/acpi/power.c:acpi_power_transition
```
**Symbols:**

```
ffffffff8147b71b-ffffffff8147b74a: acpi_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void acpi_power_off();
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff814c9d86)
Location: drivers/acpi/sleep.c:881
Inline: False
```
```
In drivers/acpi/power.c (ffffffff814d7e4f)
Location: drivers/acpi/power.c:302
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff814c9d86-ffffffff814c9db5: acpi_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
void acpi_power_off();
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff814ebce1)
Location: drivers/acpi/sleep.c:864
Inline: False
```
```
In drivers/acpi/power.c (ffffffff814fa537)
Location: drivers/acpi/power.c:302
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff814ebce1-ffffffff814ebd10: acpi_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
void acpi_power_off();
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff814f80b0)
Location: drivers/acpi/sleep.c:1026
Inline: False
```
```
In drivers/acpi/power.c (ffffffff81508fc0)
Location: drivers/acpi/power.c:303
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff814f80b0-ffffffff814f80df: acpi_power_off (STB_LOCAL)
ffffffff81508fc0-ffffffff8150901f: acpi_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void acpi_power_off();
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815393e0)
Location: drivers/acpi/sleep.c:1228
Inline: False
```
```
In drivers/acpi/power.c (ffffffff8154be24)
Location: drivers/acpi/power.c:303
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff815393e0-ffffffff8153940f: acpi_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
void acpi_power_off();
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81570054)
Location: drivers/acpi/sleep.c:1260
Inline: False
```
```
In drivers/acpi/power.c (ffffffff81582446)
Location: drivers/acpi/power.c:303
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff81570054-ffffffff81570083: acpi_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
void acpi_power_off();
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81587c14)
Location: drivers/acpi/sleep.c:1266
Inline: False
```
```
In drivers/acpi/power.c (ffffffff8159a506)
Location: drivers/acpi/power.c:325
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff81587c14-ffffffff81587c43: acpi_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
void acpi_power_off();
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815b88f5)
Location: drivers/acpi/sleep.c:1269
Inline: False
```
```
In drivers/acpi/power.c (ffffffff815cbc5f)
Location: drivers/acpi/power.c:446
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff815b88f5-ffffffff815b8924: acpi_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void acpi_power_off();
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815d9b33)
Location: drivers/acpi/sleep.c:1310
Inline: False
```
```
In drivers/acpi/power.c (ffffffff815ecedf)
Location: drivers/acpi/power.c:446
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff815d9b33-ffffffff815d9b62: acpi_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void acpi_power_off();
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81683d72)
Location: drivers/acpi/sleep.c:1310
Inline: False
```
```
In drivers/acpi/power.c (ffffffff81698adc)
Location: drivers/acpi/power.c:444
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff81683d72-ffffffff81683da1: acpi_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
void acpi_power_off();
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81c00ce1)
Location: drivers/acpi/sleep.c:1029
Inline: False
```
```
In drivers/acpi/power.c (ffffffff816b5c0f)
Location: drivers/acpi/power.c:444
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff81c00ce1-ffffffff81c00d10: acpi_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void acpi_power_off();
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81bf270a)
Location: drivers/acpi/sleep.c:1027
Inline: False
```
```
In drivers/acpi/power.c (ffffffff81697bda)
Location: drivers/acpi/power.c:435
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff81bf270a-ffffffff81bf2739: acpi_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void acpi_power_off();
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff816f9370)
Location: drivers/acpi/sleep.c:1028
Inline: False
```
```
In drivers/acpi/power.c (ffffffff8170d98b)
Location: drivers/acpi/power.c:459
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff816f9370-ffffffff816f93aa: acpi_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
int acpi_power_off(struct sys_off_data *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81826630)
Location: drivers/acpi/sleep.c:1055
Inline: False
```
```
In drivers/acpi/power.c (ffffffff8183bfea)
Location: drivers/acpi/power.c:459
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff81826630-ffffffff81826675: acpi_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
int acpi_power_off(struct sys_off_data *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81958080)
Location: drivers/acpi/sleep.c:1062
Inline: False
```
```
In drivers/acpi/power.c (ffffffff8197184a)
Location: drivers/acpi/power.c:459
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff81958080-ffffffff819580c7: acpi_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
int acpi_power_off(struct sys_off_data *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff8199e560)
Location: drivers/acpi/sleep.c:1076
Inline: False
```
```
In drivers/acpi/power.c (ffffffff819b7eda)
Location: drivers/acpi/power.c:460
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff8199e560-ffffffff8199e5a7: acpi_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int acpi_power_off(struct sys_off_data *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff819e6c00)
Location: drivers/acpi/sleep.c:1076
Inline: False
```
```
In drivers/acpi/power.c (ffffffff81a024aa)
Location: drivers/acpi/power.c:460
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff819e6c00-ffffffff819e6c47: acpi_power_off (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int acpi_power_off(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffff800010777a40)
Location: drivers/acpi/power.c:446
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffff800010777a40-ffff800010777ab8: acpi_power_off (STB_LOCAL)
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
<summary>In <code>aws</code>: Collision ⚠️</summary>

```c
void acpi_power_off();
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815cc33e)
Location: drivers/acpi/sleep.c:1310
Inline: False
```
```
In drivers/acpi/power.c (ffffffff815db640)
Location: drivers/acpi/power.c:446
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff815cc33e-ffffffff815cc36d: acpi_power_off (STB_LOCAL)
ffffffff815db640-ffffffff815db699: acpi_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
void acpi_power_off();
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815b5e93)
Location: drivers/acpi/sleep.c:1310
Inline: False
```
```
In drivers/acpi/power.c (ffffffff815c6c80)
Location: drivers/acpi/power.c:446
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff815b5e93-ffffffff815b5ebc: acpi_power_off (STB_LOCAL)
ffffffff815c6c80-ffffffff815c6cd9: acpi_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
void acpi_power_off();
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815cde13)
Location: drivers/acpi/sleep.c:1310
Inline: False
```
```
In drivers/acpi/power.c (ffffffff815e11bf)
Location: drivers/acpi/power.c:446
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff815cde13-ffffffff815cde42: acpi_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
void acpi_power_off();
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815e7cd3)
Location: drivers/acpi/sleep.c:1310
Inline: False
```
```
In drivers/acpi/power.c (ffffffff815fb07f)
Location: drivers/acpi/power.c:446
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff815e7cd3-ffffffff815e7d02: acpi_power_off (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sys_off_data *data</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct acpi_power_resource *resource</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
