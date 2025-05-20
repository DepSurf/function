# Function: <code>tpm_read_log_of</code>

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
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_eventlog.c (0)
Location: drivers/char/tpm/tpm_eventlog.h:87
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1_eventlog.c (0)
Location: drivers/char/tpm/tpm_eventlog.h:128
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1_eventlog.c (0)
Location: drivers/char/tpm/tpm_eventlog.h:129
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/common.c (0)
Location: drivers/char/tpm/eventlog/common.h:21
Inline: True
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
In drivers/char/tpm/eventlog/common.c (0)
Location: drivers/char/tpm/eventlog/common.h:21
Inline: True
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
In drivers/char/tpm/eventlog/common.c (0)
Location: drivers/char/tpm/eventlog/common.h:21
Inline: True
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
In drivers/char/tpm/eventlog/common.c (0)
Location: drivers/char/tpm/eventlog/common.h:21
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/common.c (0)
Location: drivers/char/tpm/eventlog/common.h:21
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/common.c (0)
Location: drivers/char/tpm/eventlog/common.h:21
Inline: True
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
In drivers/char/tpm/eventlog/common.c (0)
Location: drivers/char/tpm/eventlog/common.h:21
Inline: True
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
In drivers/char/tpm/eventlog/common.c (0)
Location: drivers/char/tpm/eventlog/common.h:21
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/common.c (0)
Location: drivers/char/tpm/eventlog/common.h:21
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/common.c (0)
Location: drivers/char/tpm/eventlog/common.h:21
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/common.c (0)
Location: drivers/char/tpm/eventlog/common.h:21
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/common.c (0)
Location: drivers/char/tpm/eventlog/common.h:21
Inline: True
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
int tpm_read_log_of(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/of.c (ffff8000108c04d8)
Location: drivers/char/tpm/eventlog/of.c:20
Inline: False
Direct callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffff8000108c04d8-ffff8000108c0648: tpm_read_log_of (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tpm_read_log_of(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/of.c (c09b8db0)
Location: drivers/char/tpm/eventlog/of.c:20
Inline: False
Direct callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
c09b8db0-c09b8efc: tpm_read_log_of (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tpm_read_log_of(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/of.c (c000000000962270)
Location: drivers/char/tpm/eventlog/of.c:20
Inline: False
Direct callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
c000000000962270-c000000000962438: tpm_read_log_of (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tpm_read_log_of(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/of.c (ffffffe000571e5e)
Location: drivers/char/tpm/eventlog/of.c:20
Inline: False
Direct callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffe000571e5e-ffffffe00057201c: tpm_read_log_of (STB_GLOBAL)
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
In drivers/char/tpm/eventlog/common.c (0)
Location: drivers/char/tpm/eventlog/common.h:21
Inline: True
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
In drivers/char/tpm/eventlog/common.c (0)
Location: drivers/char/tpm/eventlog/common.h:21
Inline: True
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
In drivers/char/tpm/eventlog/common.c (0)
Location: drivers/char/tpm/eventlog/common.h:21
Inline: True
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
In drivers/char/tpm/eventlog/common.c (0)
Location: drivers/char/tpm/eventlog/common.h:21
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
