# Function: <code>mce_usable_address</code>

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
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810453ad)
Location: arch/x86/kernel/cpu/mcheck/mce.c:940
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
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
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045295)
Location: arch/x86/kernel/cpu/mcheck/mce.c:527
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
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
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81046eb7)
Location: arch/x86/kernel/cpu/mcheck/mce.c:552
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045eb0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:482
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
```
**Symbols:**

```
ffffffff81045eb0-ffffffff81045efa: mce_usable_address.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810496d0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:491
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
```
**Symbols:**

```
ffffffff810496d0-ffffffff8104971a: mce_usable_address.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104bf20)
Location: arch/x86/kernel/cpu/mcheck/mce.c:488
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
```
**Symbols:**

```
ffffffff8104bf20-ffffffff8104bf6a: mce_usable_address.isra.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int mce_usable_address(struct mce *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81049600)
Location: arch/x86/kernel/cpu/mce/core.c:486
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
**Symbols:**

```
ffffffff81049600-ffffffff8104964e: mce_usable_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int mce_usable_address(struct mce *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c5c0)
Location: arch/x86/kernel/cpu/mce/core.c:486
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
**Symbols:**

```
ffffffff8104c5c0-ffffffff8104c60e: mce_usable_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int mce_usable_address(struct mce *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104cf80)
Location: arch/x86/kernel/cpu/mce/core.c:486
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
**Symbols:**

```
ffffffff8104cf80-ffffffff8104cfce: mce_usable_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int mce_usable_address(struct mce *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810521a0)
Location: arch/x86/kernel/cpu/mce/core.c:468
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
**Symbols:**

```
ffffffff810521a0-ffffffff810521f5: mce_usable_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int mce_usable_address(struct mce *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810512d0)
Location: arch/x86/kernel/cpu/mce/core.c:534
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
**Symbols:**

```
ffffffff810512d0-ffffffff81051325: mce_usable_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int mce_usable_address(struct mce *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81052a40)
Location: arch/x86/kernel/cpu/mce/core.c:534
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
**Symbols:**

```
ffffffff81052a40-ffffffff81052a95: mce_usable_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int mce_usable_address(struct mce *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105b000)
Location: arch/x86/kernel/cpu/mce/core.c:543
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
**Symbols:**

```
ffffffff8105b000-ffffffff8105b055: mce_usable_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int mce_usable_address(struct mce *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81067b10)
Location: arch/x86/kernel/cpu/mce/core.c:468
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - drivers/ras/cec.c:cec_notifier
```
**Symbols:**

```
ffffffff81067b10-ffffffff81067b6f: mce_usable_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int mce_usable_address(struct mce *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81077090)
Location: arch/x86/kernel/cpu/mce/core.c:468
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - drivers/ras/cec.c:cec_notifier
```
**Symbols:**

```
ffffffff81077090-ffffffff810770ef: mce_usable_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int mce_usable_address(struct mce *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810792a0)
Location: arch/x86/kernel/cpu/mce/core.c:462
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - drivers/ras/cec.c:cec_notifier
```
**Symbols:**

```
ffffffff810792a0-ffffffff81079301: mce_usable_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool mce_usable_address(struct mce *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81080540)
Location: arch/x86/kernel/cpu/mce/core.c:487
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - drivers/ras/cec.c:cec_notifier
```
**Symbols:**

```
ffffffff81080540-ffffffff8108058f: mce_usable_address (STB_GLOBAL)
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
int mce_usable_address(struct mce *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d0f0)
Location: arch/x86/kernel/cpu/mce/core.c:486
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
**Symbols:**

```
ffffffff8104d0f0-ffffffff8104d13e: mce_usable_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int mce_usable_address(struct mce *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103c570)
Location: arch/x86/kernel/cpu/mce/core.c:486
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
**Symbols:**

```
ffffffff8103c570-ffffffff8103c5be: mce_usable_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int mce_usable_address(struct mce *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104cf30)
Location: arch/x86/kernel/cpu/mce/core.c:486
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
**Symbols:**

```
ffffffff8104cf30-ffffffff8104cf7e: mce_usable_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int mce_usable_address(struct mce *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e340)
Location: arch/x86/kernel/cpu/mce/core.c:486
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
**Symbols:**

```
ffffffff8104e340-ffffffff8104e38e: mce_usable_address (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
