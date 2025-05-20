# Function: <code>i8042_pnp_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff81fb1a73)
Location: drivers/input/serio/i8042-x86ia64io.h:938
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff81fde5c9)
Location: drivers/input/serio/i8042-x86ia64io.h:938
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff8201c1da)
Location: drivers/input/serio/i8042-x86ia64io.h:970
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
In drivers/input/serio/i8042.c (ffffffff820febb6)
Location: drivers/input/serio/i8042-x86ia64io.h:1006
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
In drivers/input/serio/i8042.c (ffffffff82708423)
Location: drivers/input/serio/i8042-x86ia64io.h:1027
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
In drivers/input/serio/i8042.c (ffffffff82731a98)
Location: drivers/input/serio/i8042-x86ia64io.h:1034
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_init
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
In drivers/input/serio/i8042.c (ffffffff828eafa6)
Location: drivers/input/serio/i8042-x86ia64io.h:1034
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_init
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
In drivers/input/serio/i8042.c (ffffffff82906276)
Location: drivers/input/serio/i8042-x86ia64io.h:1030
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_platform_init
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
In drivers/input/serio/i8042.c (ffffffff8290fc7b)
Location: drivers/input/serio/i8042-x86ia64io.h:1030
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_platform_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int i8042_pnp_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff82d232ba)
Location: drivers/input/serio/i8042-x86ia64io.h:1079
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_platform_init
```
**Symbols:**

```
ffffffff82d232ba-ffffffff82d235be: i8042_pnp_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int i8042_pnp_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff83011106)
Location: drivers/input/serio/i8042-x86ia64io.h:1131
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_platform_init
```
**Symbols:**

```
ffffffff83011106-ffffffff8301140a: i8042_pnp_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int i8042_pnp_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff8321c0f3)
Location: drivers/input/serio/i8042-x86ia64io.h:1132
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_init
```
**Symbols:**

```
ffffffff8321c0f3-ffffffff8321c3f7: i8042_pnp_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int i8042_pnp_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff83305c48)
Location: drivers/input/serio/i8042-x86ia64io.h:1164
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_platform_init
```
**Symbols:**

```
ffffffff83305c48-ffffffff83305f8e: i8042_pnp_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int i8042_pnp_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff834beda9)
Location: drivers/input/serio/i8042-x86ia64io.h:1164
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_platform_init
```
**Symbols:**

```
ffffffff834beda9-ffffffff834bf0de: i8042_pnp_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int i8042_pnp_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff83efd070)
Location: drivers/input/serio/i8042-acpipnpio.h:1439
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_platform_init
```
**Symbols:**

```
ffffffff83efd070-ffffffff83efd484: i8042_pnp_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int i8042_pnp_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff83722e50)
Location: drivers/input/serio/i8042-acpipnpio.h:1482
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_platform_init
```
**Symbols:**

```
ffffffff83722e50-ffffffff83723264: i8042_pnp_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int i8042_pnp_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff83956c80)
Location: drivers/input/serio/i8042-acpipnpio.h:1512
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_platform_init
```
**Symbols:**

```
ffffffff83956c80-ffffffff83957094: i8042_pnp_init (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff828f5e94)
Location: drivers/input/serio/i8042-x86ia64io.h:1030
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_platform_init
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
In drivers/input/serio/i8042.c (ffffffff828ede81)
Location: drivers/input/serio/i8042-x86ia64io.h:1030
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_platform_init
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
In drivers/input/serio/i8042.c (ffffffff8290a812)
Location: drivers/input/serio/i8042-x86ia64io.h:1030
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_platform_init
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
In drivers/input/serio/i8042.c (ffffffff82910cdd)
Location: drivers/input/serio/i8042-x86ia64io.h:1030
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_platform_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
