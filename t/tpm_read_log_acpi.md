# Function: <code>tpm_read_log_acpi</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tpm_read_log_acpi(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_acpi.c (ffffffff815a7620)
Location: drivers/char/tpm/tpm_acpi.c:49
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff815a7620-ffffffff815a7755: tpm_read_log_acpi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tpm_read_log_acpi(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_acpi.c (ffffffff815bd2a0)
Location: drivers/char/tpm/tpm_acpi.c:49
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1_eventlog.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff815bd2a0-ffffffff815bd3e2: tpm_read_log_acpi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tpm_read_log_acpi(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_acpi.c (ffffffff81623730)
Location: drivers/char/tpm/tpm_acpi.c:49
Inline: False
Direct callers:
  - drivers/char/tpm/tpm1_eventlog.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff81623730-ffffffff81623872: tpm_read_log_acpi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tpm_read_log_acpi(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/acpi.c (ffffffff8165d500)
Location: drivers/char/tpm/eventlog/acpi.c:50
Inline: False
Direct callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff8165d500-ffffffff8165d645: tpm_read_log_acpi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tpm_read_log_acpi(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/acpi.c (ffffffff8167b9c0)
Location: drivers/char/tpm/eventlog/acpi.c:50
Inline: False
Direct callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff8167b9c0-ffffffff8167bb05: tpm_read_log_acpi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tpm_read_log_acpi(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/eventlog/acpi.c (0)
Location: drivers/char/tpm/eventlog/acpi.c:45
Inline: False
Direct callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff816b271f-ffffffff816b273f: tpm_read_log_acpi.cold (STB_LOCAL)
ffffffff816b25f0-ffffffff816b271f: tpm_read_log_acpi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int tpm_read_log_acpi(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/eventlog/acpi.c (0)
Location: drivers/char/tpm/eventlog/acpi.c:45
Inline: False
Direct callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff816d53ff-ffffffff816d541f: tpm_read_log_acpi.cold (STB_LOCAL)
ffffffff816d52d0-ffffffff816d53ff: tpm_read_log_acpi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int tpm_read_log_acpi(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/eventlog/acpi.c (0)
Location: drivers/char/tpm/eventlog/acpi.c:45
Inline: False
Direct callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff817896f4-ffffffff81789714: tpm_read_log_acpi.cold (STB_LOCAL)
ffffffff817895c0-ffffffff817896f4: tpm_read_log_acpi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int tpm_read_log_acpi(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/eventlog/acpi.c (0)
Location: drivers/char/tpm/eventlog/acpi.c:45
Inline: False
Direct callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff81c0a8a6-ffffffff81c0a8c7: tpm_read_log_acpi.cold (STB_LOCAL)
ffffffff817a04e0-ffffffff817a0668: tpm_read_log_acpi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int tpm_read_log_acpi(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/eventlog/acpi.c (0)
Location: drivers/char/tpm/eventlog/acpi.c:66
Inline: False
Direct callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff81bfc379-ffffffff81bfc39a: tpm_read_log_acpi.cold (STB_LOCAL)
ffffffff817831c0-ffffffff8178338e: tpm_read_log_acpi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tpm_read_log_acpi(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/eventlog/acpi.c (0)
Location: drivers/char/tpm/eventlog/acpi.c:66
Inline: False
Direct callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff81cfd0a9-ffffffff81cfd0ca: tpm_read_log_acpi.cold (STB_LOCAL)
ffffffff81809be0-ffffffff81809dae: tpm_read_log_acpi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tpm_read_log_acpi(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/eventlog/acpi.c (0)
Location: drivers/char/tpm/eventlog/acpi.c:66
Inline: False
Direct callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff81ec5968-ffffffff81ec5989: tpm_read_log_acpi.cold (STB_LOCAL)
ffffffff81949b60-ffffffff81949d4a: tpm_read_log_acpi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tpm_read_log_acpi(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/acpi.c (ffffffff81aad190)
Location: drivers/char/tpm/eventlog/acpi.c:66
Inline: False
Direct callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff81aad190-ffffffff81aad3c5: tpm_read_log_acpi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tpm_read_log_acpi(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/acpi.c (ffffffff81af8a00)
Location: drivers/char/tpm/eventlog/acpi.c:67
Inline: False
Direct callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff81af8a00-ffffffff81af8c3f: tpm_read_log_acpi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tpm_read_log_acpi(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/acpi.c (ffffffff81b4c020)
Location: drivers/char/tpm/eventlog/acpi.c:67
Inline: False
Direct callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff81b4c020-ffffffff81b4c25f: tpm_read_log_acpi (STB_GLOBAL)
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
int tpm_read_log_acpi(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/acpi.c (ffff8000108c01c8)
Location: drivers/char/tpm/eventlog/acpi.c:45
Inline: False
Direct callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffff8000108c01c8-ffff8000108c02fc: tpm_read_log_acpi (STB_GLOBAL)
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
In drivers/char/tpm/eventlog/common.c (0)
Location: drivers/char/tpm/eventlog/common.h:13
Inline: True
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
In drivers/char/tpm/eventlog/common.c (0)
Location: drivers/char/tpm/eventlog/common.h:13
Inline: True
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
In drivers/char/tpm/eventlog/common.c (0)
Location: drivers/char/tpm/eventlog/common.h:13
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int tpm_read_log_acpi(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/eventlog/acpi.c (0)
Location: drivers/char/tpm/eventlog/acpi.c:45
Inline: False
Direct callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff8169ae4f-ffffffff8169ae6f: tpm_read_log_acpi.cold (STB_LOCAL)
ffffffff8169ad20-ffffffff8169ae4f: tpm_read_log_acpi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int tpm_read_log_acpi(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/eventlog/acpi.c (0)
Location: drivers/char/tpm/eventlog/acpi.c:45
Inline: False
Direct callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff8167883f-ffffffff8167885f: tpm_read_log_acpi.cold (STB_LOCAL)
ffffffff81678710-ffffffff8167883f: tpm_read_log_acpi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int tpm_read_log_acpi(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/eventlog/acpi.c (0)
Location: drivers/char/tpm/eventlog/acpi.c:45
Inline: False
Direct callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff816c90bf-ffffffff816c90df: tpm_read_log_acpi.cold (STB_LOCAL)
ffffffff816c8f90-ffffffff816c90bf: tpm_read_log_acpi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int tpm_read_log_acpi(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/eventlog/acpi.c (0)
Location: drivers/char/tpm/eventlog/acpi.c:45
Inline: False
Direct callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff816e359f-ffffffff816e35bf: tpm_read_log_acpi.cold (STB_LOCAL)
ffffffff816e3470-ffffffff816e359f: tpm_read_log_acpi (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
