# Function: <code>wait_for_panic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void wait_for_panic();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8107ce29)
Location: arch/x86/kernel/cpu/mcheck/mce.c:279
Inline: False
```
**Symbols:**

```
ffffffff8107ce29-ffffffff8107ce71: wait_for_panic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void wait_for_panic();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8107e915)
Location: arch/x86/kernel/cpu/mcheck/mce.c:323
Inline: False
```
**Symbols:**

```
ffffffff8107e915-ffffffff8107e95d: wait_for_panic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void wait_for_panic();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81082fac)
Location: arch/x86/kernel/cpu/mcheck/mce.c:348
Inline: False
```
**Symbols:**

```
ffffffff81082fac-ffffffff81082ff4: wait_for_panic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void wait_for_panic();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104809e)
Location: arch/x86/kernel/cpu/mcheck/mce.c:279
Inline: False
```
**Symbols:**

```
ffffffff8104809e-ffffffff810480e6: wait_for_panic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void wait_for_panic();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104bafe)
Location: arch/x86/kernel/cpu/mcheck/mce.c:288
Inline: False
```
**Symbols:**

```
ffffffff8104bafe-ffffffff8104bb44: wait_for_panic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void wait_for_panic();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:285
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_panic
```
**Symbols:**

```
ffffffff8104b980-ffffffff8104b9aa: wait_for_panic (STB_LOCAL)
ffffffff8104e43d-ffffffff8104e45e: wait_for_panic.cold.40 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void wait_for_panic();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/kernel/cpu/mce/core.c:283
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
**Symbols:**

```
ffffffff81049040-ffffffff8104906a: wait_for_panic (STB_LOCAL)
ffffffff8104bb2d-ffffffff8104bb4e: wait_for_panic.cold.40 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wait_for_panic();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104ebd3)
Location: arch/x86/kernel/cpu/mce/core.c:300
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
**Symbols:**

```
ffffffff8104cb40-ffffffff8104cb6c: wait_for_panic (STB_LOCAL)
ffffffff8104ebd3-ffffffff8104ebf4: wait_for_panic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wait_for_panic();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104f560)
Location: arch/x86/kernel/cpu/mce/core.c:300
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
**Symbols:**

```
ffffffff8104d4e0-ffffffff8104d50c: wait_for_panic (STB_LOCAL)
ffffffff8104f560-ffffffff8104f581: wait_for_panic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void wait_for_panic();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/kernel/cpu/mce/core.c:282
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
**Symbols:**

```
ffffffff81051350-ffffffff8105137c: wait_for_panic (STB_LOCAL)
ffffffff81053a09-ffffffff81053a2a: wait_for_panic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void wait_for_panic();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/kernel/cpu/mce/core.c:285
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
**Symbols:**

```
ffffffff81050610-ffffffff8105063c: wait_for_panic (STB_LOCAL)
ffffffff81bd558d-ffffffff81bd55ae: wait_for_panic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void wait_for_panic();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/kernel/cpu/mce/core.c:285
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
**Symbols:**

```
ffffffff81052130-ffffffff8105215a: wait_for_panic (STB_LOCAL)
ffffffff81bc79c6-ffffffff81bc79e7: wait_for_panic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void wait_for_panic();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/kernel/cpu/mce/core.c:285
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
**Symbols:**

```
ffffffff8105a590-ffffffff8105a5ba: wait_for_panic (STB_LOCAL)
ffffffff81c9b53c-ffffffff81c9b55d: wait_for_panic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void wait_for_panic();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/kernel/cpu/mce/core.c:224
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timed_out
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
**Symbols:**

```
ffffffff81066fd0-ffffffff81067002: wait_for_panic (STB_LOCAL)
ffffffff81e4ab87-ffffffff81e4aba8: wait_for_panic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void wait_for_panic();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81076650)
Location: arch/x86/kernel/cpu/mce/core.c:224
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timed_out
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
**Symbols:**

```
ffffffff81076650-ffffffff8107669e: wait_for_panic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wait_for_panic();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810788d0)
Location: arch/x86/kernel/cpu/mce/core.c:218
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timed_out
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
**Symbols:**

```
ffffffff810788d0-ffffffff8107891e: wait_for_panic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void wait_for_panic();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8107fd80)
Location: arch/x86/kernel/cpu/mce/core.c:220
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timed_out
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
**Symbols:**

```
ffffffff8107fd80-ffffffff8107fdce: wait_for_panic (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wait_for_panic();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104f6c0)
Location: arch/x86/kernel/cpu/mce/core.c:300
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
**Symbols:**

```
ffffffff8104d650-ffffffff8104d67c: wait_for_panic (STB_LOCAL)
ffffffff8104f6c0-ffffffff8104f6e1: wait_for_panic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wait_for_panic();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103ebca)
Location: arch/x86/kernel/cpu/mce/core.c:300
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
**Symbols:**

```
ffffffff8103c890-ffffffff8103c8b6: wait_for_panic (STB_LOCAL)
ffffffff8103ebca-ffffffff8103ebeb: wait_for_panic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wait_for_panic();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104f510)
Location: arch/x86/kernel/cpu/mce/core.c:300
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
**Symbols:**

```
ffffffff8104d490-ffffffff8104d4bc: wait_for_panic (STB_LOCAL)
ffffffff8104f510-ffffffff8104f531: wait_for_panic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wait_for_panic();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81050950)
Location: arch/x86/kernel/cpu/mce/core.c:300
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
**Symbols:**

```
ffffffff8104e8c0-ffffffff8104e8f3: wait_for_panic (STB_LOCAL)
ffffffff81050950-ffffffff81050971: wait_for_panic.cold (STB_LOCAL)
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
