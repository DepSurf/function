# Function: <code>acpi_reboot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_reboot();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/reboot.c (ffffffff8147b174)
Location: drivers/acpi/reboot.c:6
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff8147b174-ffffffff8147b223: acpi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_reboot();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/reboot.c (ffffffff814c977c)
Location: drivers/acpi/reboot.c:6
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff814c977c-ffffffff814c982f: acpi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_reboot();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/reboot.c (ffffffff814eb6c0)
Location: drivers/acpi/reboot.c:6
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff814eb6c0-ffffffff814eb773: acpi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_reboot();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/reboot.c (ffffffff814f7990)
Location: drivers/acpi/reboot.c:6
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff814f7990-ffffffff814f7a43: acpi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_reboot();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/reboot.c (ffffffff81538d40)
Location: drivers/acpi/reboot.c:7
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff81538d40-ffffffff81538df3: acpi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void acpi_reboot();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/reboot.c (0)
Location: drivers/acpi/reboot.c:7
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff8156ebe9-ffffffff8156ec47: acpi_reboot.cold.0 (STB_LOCAL)
ffffffff8156eb80-ffffffff8156ebe9: acpi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void acpi_reboot();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/reboot.c (0)
Location: drivers/acpi/reboot.c:33
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff815867f3-ffffffff81586809: acpi_reboot.cold.1 (STB_LOCAL)
ffffffff81586740-ffffffff815867f3: acpi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void acpi_reboot();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/reboot.c (0)
Location: drivers/acpi/reboot.c:33
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff815b749d-ffffffff815b74b3: acpi_reboot.cold (STB_LOCAL)
ffffffff815b73e0-ffffffff815b749d: acpi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void acpi_reboot();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/reboot.c (0)
Location: drivers/acpi/reboot.c:33
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff815d86cd-ffffffff815d86e3: acpi_reboot.cold (STB_LOCAL)
ffffffff815d8610-ffffffff815d86cd: acpi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void acpi_reboot();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/reboot.c (0)
Location: drivers/acpi/reboot.c:33
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff8168258d-ffffffff816825a3: acpi_reboot.cold (STB_LOCAL)
ffffffff816824d0-ffffffff8168258d: acpi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void acpi_reboot();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/reboot.c (0)
Location: drivers/acpi/reboot.c:34
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff81c00aa5-ffffffff81c00abb: acpi_reboot.cold (STB_LOCAL)
ffffffff816a0d60-ffffffff816a0e38: acpi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void acpi_reboot();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/reboot.c (0)
Location: drivers/acpi/reboot.c:34
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff81bf24fc-ffffffff81bf2512: acpi_reboot.cold (STB_LOCAL)
ffffffff81683b50-ffffffff81683c28: acpi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_reboot();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/reboot.c (ffffffff816f8ce0)
Location: drivers/acpi/reboot.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff816f8ce0-ffffffff816f8dcf: acpi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_reboot();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/reboot.c (ffffffff81825eb0)
Location: drivers/acpi/reboot.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff81825eb0-ffffffff81825fba: acpi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_reboot();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/reboot.c (ffffffff819575c0)
Location: drivers/acpi/reboot.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff819575c0-ffffffff819576ca: acpi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_reboot();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/reboot.c (ffffffff8199da90)
Location: drivers/acpi/reboot.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff8199da90-ffffffff8199db8b: acpi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_reboot();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/reboot.c (ffffffff819e60a0)
Location: drivers/acpi/reboot.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff819e60a0-ffffffff819e619b: acpi_reboot (STB_GLOBAL)
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
void acpi_reboot();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/reboot.c (ffff800010765c00)
Location: drivers/acpi/reboot.c:33
Inline: False
```
**Symbols:**

```
ffff800010765c00-ffff800010765cf4: acpi_reboot (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void acpi_reboot();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/reboot.c (0)
Location: drivers/acpi/reboot.c:33
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff815cb9fd-ffffffff815cba13: acpi_reboot.cold (STB_LOCAL)
ffffffff815cb940-ffffffff815cb9fd: acpi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void acpi_reboot();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/reboot.c (0)
Location: drivers/acpi/reboot.c:33
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff815b4a4d-ffffffff815b4a63: acpi_reboot.cold (STB_LOCAL)
ffffffff815b4990-ffffffff815b4a4d: acpi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void acpi_reboot();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/reboot.c (0)
Location: drivers/acpi/reboot.c:33
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff815cc9ad-ffffffff815cc9c3: acpi_reboot.cold (STB_LOCAL)
ffffffff815cc8f0-ffffffff815cc9ad: acpi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void acpi_reboot();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/reboot.c (0)
Location: drivers/acpi/reboot.c:33
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff815e684d-ffffffff815e6863: acpi_reboot.cold (STB_LOCAL)
ffffffff815e6790-ffffffff815e684d: acpi_reboot (STB_GLOBAL)
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
