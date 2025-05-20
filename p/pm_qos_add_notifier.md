# Function: <code>pm_qos_add_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pm_qos_add_notifier(int pm_qos_class, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810cbea0)
Location: kernel/power/qos.c:556
Inline: False
```
**Symbols:**

```
ffffffff810cbea0-ffffffff810cbec2: pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pm_qos_add_notifier(int pm_qos_class, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810d09b0)
Location: kernel/power/qos.c:565
Inline: False
```
**Symbols:**

```
ffffffff810d09b0-ffffffff810d09d2: pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pm_qos_add_notifier(int pm_qos_class, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810d7420)
Location: kernel/power/qos.c:556
Inline: False
```
**Symbols:**

```
ffffffff810d7420-ffffffff810d7442: pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pm_qos_add_notifier(int pm_qos_class, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810d6460)
Location: kernel/power/qos.c:556
Inline: False
```
**Symbols:**

```
ffffffff810d6460-ffffffff810d6482: pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pm_qos_add_notifier(int pm_qos_class, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810de3f0)
Location: kernel/power/qos.c:556
Inline: False
```
**Symbols:**

```
ffffffff810de3f0-ffffffff810de412: pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pm_qos_add_notifier(int pm_qos_class, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810e6a50)
Location: kernel/power/qos.c:557
Inline: False
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_init
```
**Symbols:**

```
ffffffff810e6a50-ffffffff810e6a72: pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pm_qos_add_notifier(int pm_qos_class, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810f2050)
Location: kernel/power/qos.c:546
Inline: False
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_init
```
**Symbols:**

```
ffffffff810f2050-ffffffff810f2072: pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pm_qos_add_notifier(int pm_qos_class, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810fa530)
Location: kernel/power/qos.c:547
Inline: False
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_init
```
**Symbols:**

```
ffffffff810fa530-ffffffff810fa552: pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pm_qos_add_notifier(int pm_qos_class, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff81106310)
Location: kernel/power/qos.c:499
Inline: False
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_init
```
**Symbols:**

```
ffffffff81106310-ffffffff81106332: pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int pm_qos_add_notifier(int pm_qos_class, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffff80001016cae8)
Location: kernel/power/qos.c:499
Inline: False
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_init
```
**Symbols:**

```
ffff80001016cae8-ffff80001016cb2c: pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pm_qos_add_notifier(int pm_qos_class, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (c03b7d64)
Location: kernel/power/qos.c:499
Inline: False
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_init
```
**Symbols:**

```
c03b7d64-c03b7d94: pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pm_qos_add_notifier(int pm_qos_class, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (c0000000001c4120)
Location: kernel/power/qos.c:499
Inline: False
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_init
```
**Symbols:**

```
c0000000001c4120-c0000000001c416c: pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pm_qos_add_notifier(int pm_qos_class, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffe00010c674)
Location: kernel/power/qos.c:499
Inline: False
```
**Symbols:**

```
ffffffe00010c674-ffffffe00010c6b6: pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int pm_qos_add_notifier(int pm_qos_class, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810ff620)
Location: kernel/power/qos.c:499
Inline: False
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_init
```
**Symbols:**

```
ffffffff810ff620-ffffffff810ff642: pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pm_qos_add_notifier(int pm_qos_class, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810ef810)
Location: kernel/power/qos.c:499
Inline: False
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_init
```
**Symbols:**

```
ffffffff810ef810-ffffffff810ef832: pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pm_qos_add_notifier(int pm_qos_class, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810fc7e0)
Location: kernel/power/qos.c:499
Inline: False
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_init
```
**Symbols:**

```
ffffffff810fc7e0-ffffffff810fc802: pm_qos_add_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pm_qos_add_notifier(int pm_qos_class, struct notifier_block *notifier);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff81107a10)
Location: kernel/power/qos.c:499
Inline: False
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_init
```
**Symbols:**

```
ffffffff81107a10-ffffffff81107a32: pm_qos_add_notifier (STB_GLOBAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
