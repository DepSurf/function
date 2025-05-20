# Function: <code>acpi_osi_setup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void acpi_osi_setup(char *str);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81fa1223)
Location: drivers/acpi/osl.c:1430
Inline: True
Direct callers:
  - drivers/acpi/blacklist.c:dmi_disable_osi_win8
  - drivers/acpi/blacklist.c:dmi_disable_osi_win7
  - drivers/acpi/blacklist.c:dmi_disable_osi_vista
  - drivers/acpi/blacklist.c:dmi_disable_osi_vista
  - drivers/acpi/blacklist.c:dmi_disable_osi_vista
  - drivers/acpi/osl.c:set_osi_linux
  - drivers/acpi/osl.c:osi_setup
```
**Symbols:**

```
ffffffff81fa1223-ffffffff81fa130b: acpi_osi_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_osi_setup(char *str);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff81fccb24)
Location: drivers/acpi/osi.c:81
Inline: True
Direct callers:
  - drivers/acpi/osi.c:dmi_disable_osi_win8
  - drivers/acpi/osi.c:dmi_disable_osi_win7
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:acpi_osi_dmi_linux
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:acpi_osi_setup_linux
```
**Symbols:**

```
ffffffff81fccb24-ffffffff81fccc26: acpi_osi_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void acpi_osi_setup(char *str);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff82009b1e)
Location: drivers/acpi/osi.c:81
Inline: True
Direct callers:
  - drivers/acpi/osi.c:dmi_disable_osi_win8
  - drivers/acpi/osi.c:dmi_disable_osi_win7
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:acpi_osi_dmi_linux
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:acpi_osi_setup_linux
```
**Symbols:**

```
ffffffff82009b1e-ffffffff82009c20: acpi_osi_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void acpi_osi_setup(char *str);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff820eb1ac)
Location: drivers/acpi/osi.c:81
Inline: True
Direct callers:
  - drivers/acpi/osi.c:dmi_disable_osi_win8
  - drivers/acpi/osi.c:dmi_disable_osi_win7
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_enable_osi_linux
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:acpi_osi_setup_linux
  - drivers/acpi/osi.c:acpi_osi_setup_linux
```
**Symbols:**

```
ffffffff820eb1ac-ffffffff820eb2b4: acpi_osi_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void acpi_osi_setup(char *str);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff826f4053)
Location: drivers/acpi/osi.c:82
Inline: True
Direct callers:
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/osi.c:dmi_disable_osi_win8
  - drivers/acpi/osi.c:dmi_disable_osi_win7
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_enable_osi_linux
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:acpi_osi_setup_linux
  - drivers/acpi/osi.c:acpi_osi_setup_linux
  - drivers/acpi/osi.c:acpi_osi_setup_darwin
  - drivers/acpi/osi.c:acpi_osi_setup_darwin
  - drivers/acpi/osi.c:acpi_osi_setup_darwin
  - drivers/acpi/osi.c:acpi_osi_setup_darwin
```
**Symbols:**

```
ffffffff826f4053-ffffffff826f415b: acpi_osi_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_osi_setup(char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff8271e036)
Location: drivers/acpi/osi.c:99
Inline: False
Direct callers:
  - drivers/acpi/osi.c:dmi_disable_osi_win8
  - drivers/acpi/osi.c:dmi_disable_osi_win7
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_enable_osi_linux
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:acpi_osi_setup_linux
  - drivers/acpi/osi.c:acpi_osi_setup_linux
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
```
**Symbols:**

```
ffffffff8271e036-ffffffff8271e13e: acpi_osi_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_osi_setup(char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff828d6061)
Location: drivers/acpi/osi.c:106
Inline: False
Direct callers:
  - drivers/acpi/osi.c:dmi_disable_osi_win8
  - drivers/acpi/osi.c:dmi_disable_osi_win7
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_enable_osi_linux
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:acpi_osi_setup_linux
  - drivers/acpi/osi.c:acpi_osi_setup_linux
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
```
**Symbols:**

```
ffffffff828d6061-ffffffff828d6169: acpi_osi_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_osi_setup(char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff828efec0)
Location: drivers/acpi/osi.c:93
Inline: False
Direct callers:
  - drivers/acpi/osi.c:dmi_disable_osi_win8
  - drivers/acpi/osi.c:dmi_disable_osi_win7
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_enable_osi_linux
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:acpi_osi_setup_linux
  - drivers/acpi/osi.c:acpi_osi_setup_linux
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
```
**Symbols:**

```
ffffffff828efec0-ffffffff828effc5: acpi_osi_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_osi_setup(char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff828f9031)
Location: drivers/acpi/osi.c:93
Inline: False
Direct callers:
  - drivers/acpi/osi.c:dmi_disable_osi_win8
  - drivers/acpi/osi.c:dmi_disable_osi_win7
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_enable_osi_linux
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:acpi_osi_setup_linux
  - drivers/acpi/osi.c:acpi_osi_setup_linux
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
```
**Symbols:**

```
ffffffff828f9031-ffffffff828f9136: acpi_osi_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_osi_setup(char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff82d101d9)
Location: drivers/acpi/osi.c:93
Inline: False
Direct callers:
  - drivers/acpi/osi.c:dmi_disable_osi_win8
  - drivers/acpi/osi.c:dmi_disable_osi_win7
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:__acpi_osi_setup_linux
  - drivers/acpi/osi.c:__acpi_osi_setup_linux
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
```
**Symbols:**

```
ffffffff82d101d9-ffffffff82d102de: acpi_osi_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_osi_setup(char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff82ffdca9)
Location: drivers/acpi/osi.c:93
Inline: False
Direct callers:
  - drivers/acpi/osi.c:dmi_disable_osi_win8
  - drivers/acpi/osi.c:dmi_disable_osi_win7
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:__acpi_osi_setup_linux
  - drivers/acpi/osi.c:__acpi_osi_setup_linux
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
```
**Symbols:**

```
ffffffff82ffdca9-ffffffff82ffddae: acpi_osi_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_osi_setup(char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff832089d6)
Location: drivers/acpi/osi.c:93
Inline: False
Direct callers:
  - drivers/acpi/osi.c:dmi_disable_osi_win8
  - drivers/acpi/osi.c:dmi_disable_osi_win7
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:__acpi_osi_setup_linux
  - drivers/acpi/osi.c:__acpi_osi_setup_linux
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
```
**Symbols:**

```
ffffffff832089d6-ffffffff83208adb: acpi_osi_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_osi_setup(char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff832f0c20)
Location: drivers/acpi/osi.c:93
Inline: False
Direct callers:
  - drivers/acpi/osi.c:dmi_disable_osi_win8
  - drivers/acpi/osi.c:dmi_disable_osi_win7
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:__acpi_osi_setup_linux
  - drivers/acpi/osi.c:__acpi_osi_setup_linux
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
```
**Symbols:**

```
ffffffff832f0c20-ffffffff832f0d57: acpi_osi_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_osi_setup(char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff834a8bc0)
Location: drivers/acpi/osi.c:93
Inline: False
Direct callers:
  - drivers/acpi/osi.c:dmi_disable_osi_win8
  - drivers/acpi/osi.c:dmi_disable_osi_win7
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:__acpi_osi_setup_linux
  - drivers/acpi/osi.c:__acpi_osi_setup_linux
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
```
**Symbols:**

```
ffffffff834a8bc0-ffffffff834a8d11: acpi_osi_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_osi_setup(char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff83ee02b0)
Location: drivers/acpi/osi.c:69
Inline: False
Direct callers:
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/osi.c:dmi_disable_osi_win8
  - drivers/acpi/osi.c:dmi_disable_osi_win7
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_enable_osi_linux
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
```
**Symbols:**

```
ffffffff83ee02b0-ffffffff83ee0440: acpi_osi_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_osi_setup(char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff83705d50)
Location: drivers/acpi/osi.c:69
Inline: False
Direct callers:
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/osi.c:dmi_disable_osi_win8
  - drivers/acpi/osi.c:dmi_disable_osi_win7
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_enable_osi_linux
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
```
**Symbols:**

```
ffffffff83705d50-ffffffff83705ee0: acpi_osi_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_osi_setup(char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff83939280)
Location: drivers/acpi/osi.c:69
Inline: False
Direct callers:
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/osi.c:dmi_disable_osi_win8
  - drivers/acpi/osi.c:dmi_disable_osi_win7
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_enable_osi_linux
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
```
**Symbols:**

```
ffffffff83939280-ffffffff8393945c: acpi_osi_setup (STB_GLOBAL)
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
void acpi_osi_setup(char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffff80001147c0d8)
Location: drivers/acpi/osi.c:93
Inline: False
Direct callers:
  - drivers/acpi/osi.c:dmi_disable_osi_win8
  - drivers/acpi/osi.c:dmi_disable_osi_win7
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_enable_osi_linux
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
```
**Symbols:**

```
ffff80001147c0d8-ffff80001147c230: acpi_osi_setup (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void acpi_osi_setup(char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff828e1d9d)
Location: drivers/acpi/osi.c:93
Inline: False
Direct callers:
  - drivers/acpi/osi.c:dmi_disable_osi_win8
  - drivers/acpi/osi.c:dmi_disable_osi_win7
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_enable_osi_linux
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:acpi_osi_setup_linux
  - drivers/acpi/osi.c:acpi_osi_setup_linux
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
```
**Symbols:**

```
ffffffff828e1d9d-ffffffff828e1ea2: acpi_osi_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void acpi_osi_setup(char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff828d9dcd)
Location: drivers/acpi/osi.c:93
Inline: False
Direct callers:
  - drivers/acpi/osi.c:dmi_disable_osi_win8
  - drivers/acpi/osi.c:dmi_disable_osi_win7
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_enable_osi_linux
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:acpi_osi_setup_linux
  - drivers/acpi/osi.c:acpi_osi_setup_linux
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
```
**Symbols:**

```
ffffffff828d9dcd-ffffffff828d9ed2: acpi_osi_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_osi_setup(char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff828f4c2d)
Location: drivers/acpi/osi.c:93
Inline: False
Direct callers:
  - drivers/acpi/osi.c:dmi_disable_osi_win8
  - drivers/acpi/osi.c:dmi_disable_osi_win7
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_enable_osi_linux
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:acpi_osi_setup_linux
  - drivers/acpi/osi.c:acpi_osi_setup_linux
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
```
**Symbols:**

```
ffffffff828f4c2d-ffffffff828f4d32: acpi_osi_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_osi_setup(char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff828fa085)
Location: drivers/acpi/osi.c:93
Inline: False
Direct callers:
  - drivers/acpi/osi.c:dmi_disable_osi_win8
  - drivers/acpi/osi.c:dmi_disable_osi_win7
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_disable_osi_vista
  - drivers/acpi/osi.c:dmi_enable_osi_linux
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:acpi_osi_setup_linux
  - drivers/acpi/osi.c:acpi_osi_setup_linux
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
  - drivers/acpi/osi.c:__acpi_osi_setup_darwin
```
**Symbols:**

```
ffffffff828fa085-ffffffff828fa18a: acpi_osi_setup (STB_GLOBAL)
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
