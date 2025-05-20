# Function: <code>mce_disable_error_reporting</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mce_disable_error_reporting();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810435d0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:2060
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_syscore_suspend
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_syscore_shutdown
```
**Symbols:**

```
ffffffff810435d0-ffffffff81043630: mce_disable_error_reporting (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mce_disable_error_reporting();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81043700)
Location: arch/x86/kernel/cpu/mcheck/mce.c:2141
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_syscore_shutdown
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_syscore_suspend
```
**Symbols:**

```
ffffffff81043700-ffffffff81043769: mce_disable_error_reporting (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mce_disable_error_reporting();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045150)
Location: arch/x86/kernel/cpu/mcheck/mce.c:2206
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_syscore_shutdown
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_syscore_suspend
```
**Symbols:**

```
ffffffff81045150-ffffffff810451b9: mce_disable_error_reporting (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mce_disable_error_reporting();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810452b0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:1938
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_syscore_shutdown
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_syscore_suspend
```
**Symbols:**

```
ffffffff810452b0-ffffffff81045310: mce_disable_error_reporting (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mce_disable_error_reporting();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81048b90)
Location: arch/x86/kernel/cpu/mcheck/mce.c:1950
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_syscore_shutdown
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_syscore_suspend
```
**Symbols:**

```
ffffffff81048b90-ffffffff81048bf6: mce_disable_error_reporting (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mce_disable_error_reporting();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104b4c0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:1946
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_syscore_shutdown
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_syscore_suspend
```
**Symbols:**

```
ffffffff8104b4c0-ffffffff8104b522: mce_disable_error_reporting (STB_LOCAL)
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
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/kernel/cpu/mce/core.c:1967
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104bc44)
Location: arch/x86/kernel/cpu/mce/core.c:2000
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c604)
Location: arch/x86/kernel/cpu/mce/core.c:2000
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff81052b28)
Location: arch/x86/kernel/cpu/mce/core.c:2125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff81051988)
Location: arch/x86/kernel/cpu/mce/core.c:2201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff81053158)
Location: arch/x86/kernel/cpu/mce/core.c:2212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105bb0c)
Location: arch/x86/kernel/cpu/mce/core.c:2275
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff81067fc0)
Location: arch/x86/kernel/cpu/mce/core.c:2289
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff810776a0)
Location: arch/x86/kernel/cpu/mce/core.c:2289
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff81079916)
Location: arch/x86/kernel/cpu/mce/core.c:2305
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff81081566)
Location: arch/x86/kernel/cpu/mce/core.c:2334
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c774)
Location: arch/x86/kernel/cpu/mce/core.c:2000
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103cdb4)
Location: arch/x86/kernel/cpu/mce/core.c:2000
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c5b4)
Location: arch/x86/kernel/cpu/mce/core.c:2000
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d9c4)
Location: arch/x86/kernel/cpu/mce/core.c:2000
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
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
</ul>
