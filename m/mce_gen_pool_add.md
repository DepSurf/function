# Function: <code>mce_gen_pool_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mce_gen_pool_add(struct mce *mce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce-genpool.c (ffffffff81046e50)
Location: arch/x86/kernel/cpu/mcheck/mce-genpool.c:52
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_log
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_log
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
```
**Symbols:**

```
ffffffff81046e50-ffffffff81046f25: mce_gen_pool_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mce_gen_pool_add(struct mce *mce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce-genpool.c (ffffffff81047060)
Location: arch/x86/kernel/cpu/mcheck/mce-genpool.c:98
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_log
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_log
```
**Symbols:**

```
ffffffff81047060-ffffffff81047135: mce_gen_pool_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mce_gen_pool_add(struct mce *mce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce-genpool.c (ffffffff81048be0)
Location: arch/x86/kernel/cpu/mcheck/mce-genpool.c:98
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_log
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_log
```
**Symbols:**

```
ffffffff81048be0-ffffffff81048cd1: mce_gen_pool_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mce_gen_pool_add(struct mce *mce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce-genpool.c (ffffffff81048570)
Location: arch/x86/kernel/cpu/mcheck/mce-genpool.c:98
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_log
```
**Symbols:**

```
ffffffff81048570-ffffffff81048661: mce_gen_pool_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mce_gen_pool_add(struct mce *mce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce-genpool.c (ffffffff8104bfa0)
Location: arch/x86/kernel/cpu/mcheck/mce-genpool.c:98
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_log
```
**Symbols:**

```
ffffffff8104bfa0-ffffffff8104c099: mce_gen_pool_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int mce_gen_pool_add(struct mce *mce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce-genpool.c (0)
Location: arch/x86/kernel/cpu/mcheck/mce-genpool.c:98
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_log
```
**Symbols:**

```
ffffffff8104ee0c-ffffffff8104ee22: mce_gen_pool_add.cold.0 (STB_LOCAL)
ffffffff8104eca0-ffffffff8104ed89: mce_gen_pool_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int mce_gen_pool_add(struct mce *mce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/genpool.c (0)
Location: arch/x86/kernel/cpu/mce/genpool.c:98
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:mce_log
```
**Symbols:**

```
ffffffff8104c4dc-ffffffff8104c4f2: mce_gen_pool_add.cold.1 (STB_LOCAL)
ffffffff8104c370-ffffffff8104c459: mce_gen_pool_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mce_gen_pool_add(struct mce *mce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/genpool.c (0)
Location: arch/x86/kernel/cpu/mce/genpool.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:mce_log
```
**Symbols:**

```
ffffffff8104f401-ffffffff8104f417: mce_gen_pool_add.cold (STB_LOCAL)
ffffffff8104f270-ffffffff8104f376: mce_gen_pool_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int mce_gen_pool_add(struct mce *mce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/genpool.c (0)
Location: arch/x86/kernel/cpu/mce/genpool.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:mce_log
```
**Symbols:**

```
ffffffff8104fd81-ffffffff8104fd97: mce_gen_pool_add.cold (STB_LOCAL)
ffffffff8104fbf0-ffffffff8104fcf6: mce_gen_pool_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int mce_gen_pool_add(struct mce *mce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/genpool.c (0)
Location: arch/x86/kernel/cpu/mce/genpool.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
**Symbols:**

```
ffffffff8105428f-ffffffff810542a5: mce_gen_pool_add.cold (STB_LOCAL)
ffffffff810540f0-ffffffff81054204: mce_gen_pool_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int mce_gen_pool_add(struct mce *mce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/genpool.c (0)
Location: arch/x86/kernel/cpu/mce/genpool.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
**Symbols:**

```
ffffffff81bd589b-ffffffff81bd58b1: mce_gen_pool_add.cold (STB_LOCAL)
ffffffff81053050-ffffffff81053164: mce_gen_pool_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int mce_gen_pool_add(struct mce *mce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/genpool.c (0)
Location: arch/x86/kernel/cpu/mce/genpool.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
**Symbols:**

```
ffffffff81bc7cff-ffffffff81bc7d15: mce_gen_pool_add.cold (STB_LOCAL)
ffffffff81054940-ffffffff81054a54: mce_gen_pool_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mce_gen_pool_add(struct mce *mce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/genpool.c (0)
Location: arch/x86/kernel/cpu/mce/genpool.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
**Symbols:**

```
ffffffff81c9b8f4-ffffffff81c9b90a: mce_gen_pool_add.cold (STB_LOCAL)
ffffffff8105d290-ffffffff8105d3a4: mce_gen_pool_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mce_gen_pool_add(struct mce *mce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/genpool.c (0)
Location: arch/x86/kernel/cpu/mce/genpool.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
**Symbols:**

```
ffffffff81e4adb1-ffffffff81e4adc2: mce_gen_pool_add.cold (STB_LOCAL)
ffffffff810697c0-ffffffff810698dc: mce_gen_pool_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mce_gen_pool_add(struct mce *mce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff810794a0)
Location: arch/x86/kernel/cpu/mce/genpool.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
**Symbols:**

```
ffffffff810794a0-ffffffff810795c6: mce_gen_pool_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mce_gen_pool_add(struct mce *mce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8107b750)
Location: arch/x86/kernel/cpu/mce/genpool.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
**Symbols:**

```
ffffffff8107b750-ffffffff8107b876: mce_gen_pool_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mce_gen_pool_add(struct mce *mce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff81082c10)
Location: arch/x86/kernel/cpu/mce/genpool.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
**Symbols:**

```
ffffffff81082c10-ffffffff81082d36: mce_gen_pool_add (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int mce_gen_pool_add(struct mce *mce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/genpool.c (0)
Location: arch/x86/kernel/cpu/mce/genpool.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:mce_log
```
**Symbols:**

```
ffffffff8104fe81-ffffffff8104fe97: mce_gen_pool_add.cold (STB_LOCAL)
ffffffff8104fcf0-ffffffff8104fdf6: mce_gen_pool_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int mce_gen_pool_add(struct mce *mce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/genpool.c (0)
Location: arch/x86/kernel/cpu/mce/genpool.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:mce_log
```
**Symbols:**

```
ffffffff8103f3e1-ffffffff8103f3f7: mce_gen_pool_add.cold (STB_LOCAL)
ffffffff8103f250-ffffffff8103f356: mce_gen_pool_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int mce_gen_pool_add(struct mce *mce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/genpool.c (0)
Location: arch/x86/kernel/cpu/mce/genpool.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:mce_log
```
**Symbols:**

```
ffffffff8104fd31-ffffffff8104fd47: mce_gen_pool_add.cold (STB_LOCAL)
ffffffff8104fba0-ffffffff8104fca6: mce_gen_pool_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int mce_gen_pool_add(struct mce *mce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/genpool.c (0)
Location: arch/x86/kernel/cpu/mce/genpool.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:mce_log
```
**Symbols:**

```
ffffffff81051171-ffffffff81051187: mce_gen_pool_add.cold (STB_LOCAL)
ffffffff81050fe0-ffffffff810510e6: mce_gen_pool_add (STB_GLOBAL)
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
