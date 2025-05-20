# Function: <code>retpoline_module_ok</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool retpoline_module_ok(bool has_retpoline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81041c60)
Location: arch/x86/kernel/cpu/bugs.c:101
Inline: False
Direct callers:
  - kernel/module.c:layout_and_allocate
```
**Symbols:**

```
ffffffff81041c60-ffffffff81041c95: retpoline_module_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool retpoline_module_ok(bool has_retpoline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff810438e0)
Location: arch/x86/kernel/cpu/bugs.c:224
Inline: False
Direct callers:
  - kernel/module.c:layout_and_allocate
```
**Symbols:**

```
ffffffff810438e0-ffffffff81043915: retpoline_module_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool retpoline_module_ok(bool has_retpoline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81045060)
Location: arch/x86/kernel/cpu/bugs.c:221
Inline: False
Direct callers:
  - kernel/module.c:layout_and_allocate
```
**Symbols:**

```
ffffffff81045060-ffffffff81045094: retpoline_module_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool retpoline_module_ok(bool has_retpoline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (0)
Location: arch/x86/kernel/cpu/bugs.c:375
Inline: False
Direct callers:
  - kernel/module.c:layout_and_allocate
```
**Symbols:**

```
ffffffff81047ee5-ffffffff81047efd: retpoline_module_ok.cold (STB_LOCAL)
ffffffff81047a90-ffffffff81047aba: retpoline_module_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
bool retpoline_module_ok(bool has_retpoline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (0)
Location: arch/x86/kernel/cpu/bugs.c:497
Inline: False
Direct callers:
  - kernel/module.c:check_modinfo
```
**Symbols:**

```
ffffffff81048775-ffffffff8104878d: retpoline_module_ok.cold (STB_LOCAL)
ffffffff810482d0-ffffffff810482fa: retpoline_module_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool retpoline_module_ok(bool has_retpoline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (0)
Location: arch/x86/kernel/cpu/bugs.c:600
Inline: False
Direct callers:
  - kernel/module.c:check_modinfo
```
**Symbols:**

```
ffffffff8104c81b-ffffffff8104c833: retpoline_module_ok.cold (STB_LOCAL)
ffffffff8104be70-ffffffff8104be9b: retpoline_module_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool retpoline_module_ok(bool has_retpoline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (0)
Location: arch/x86/kernel/cpu/bugs.c:598
Inline: False
Direct callers:
  - kernel/module.c:check_modinfo
```
**Symbols:**

```
ffffffff81bd50b8-ffffffff81bd50d0: retpoline_module_ok.cold (STB_LOCAL)
ffffffff8104b3b0-ffffffff8104b3db: retpoline_module_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool retpoline_module_ok(bool has_retpoline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (0)
Location: arch/x86/kernel/cpu/bugs.c:598
Inline: False
Direct callers:
  - kernel/module.c:check_modinfo
```
**Symbols:**

```
ffffffff81bc746e-ffffffff81bc7486: retpoline_module_ok.cold (STB_LOCAL)
ffffffff8104d120-ffffffff8104d14b: retpoline_module_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool retpoline_module_ok(bool has_retpoline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (0)
Location: arch/x86/kernel/cpu/bugs.c:636
Inline: False
Direct callers:
  - kernel/module.c:check_modinfo
```
**Symbols:**

```
ffffffff81c9ac2b-ffffffff81c9ac43: retpoline_module_ok.cold (STB_LOCAL)
ffffffff81054780-ffffffff810547ab: retpoline_module_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool retpoline_module_ok(bool has_retpoline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (0)
Location: arch/x86/kernel/cpu/bugs.c:960
Inline: False
Direct callers:
  - kernel/module/main.c:check_modinfo
```
**Symbols:**

```
ffffffff81e4a0cd-ffffffff81e4a0e5: retpoline_module_ok.cold (STB_LOCAL)
ffffffff81060440-ffffffff8106046e: retpoline_module_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool retpoline_module_ok(bool has_retpoline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8106eb90)
Location: arch/x86/kernel/cpu/bugs.c:997
Inline: False
Direct callers:
  - kernel/module/main.c:check_modinfo
```
**Symbols:**

```
ffffffff8106eb90-ffffffff8106ebdb: retpoline_module_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool retpoline_module_ok(bool has_retpoline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81070450)
Location: arch/x86/kernel/cpu/bugs.c:1109
Inline: False
Direct callers:
  - kernel/module/main.c:module_augment_kernel_taints
```
**Symbols:**

```
ffffffff81070450-ffffffff8107049b: retpoline_module_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool retpoline_module_ok(bool has_retpoline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81077d30)
Location: arch/x86/kernel/cpu/bugs.c:1174
Inline: False
Direct callers:
  - kernel/module/main.c:module_augment_kernel_taints
```
**Symbols:**

```
ffffffff81077d30-ffffffff81077d7b: retpoline_module_ok (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: include/linux/module.h:878
Inline: True
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
In kernel/module.c (0)
Location: include/linux/module.h:878
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
In kernel/module.c (0)
Location: include/linux/module.h:878
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
In kernel/module.c (0)
Location: include/linux/module.h:878
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
bool retpoline_module_ok(bool has_retpoline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (0)
Location: arch/x86/kernel/cpu/bugs.c:497
Inline: False
Direct callers:
  - kernel/module.c:check_modinfo
```
**Symbols:**

```
ffffffff810488e5-ffffffff810488fd: retpoline_module_ok.cold (STB_LOCAL)
ffffffff81048440-ffffffff8104846a: retpoline_module_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
bool retpoline_module_ok(bool has_retpoline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (0)
Location: arch/x86/kernel/cpu/bugs.c:497
Inline: False
Direct callers:
  - kernel/module.c:check_modinfo
```
**Symbols:**

```
ffffffff81037c55-ffffffff81037c6d: retpoline_module_ok.cold (STB_LOCAL)
ffffffff810377a0-ffffffff810377ca: retpoline_module_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
bool retpoline_module_ok(bool has_retpoline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (0)
Location: arch/x86/kernel/cpu/bugs.c:497
Inline: False
Direct callers:
  - kernel/module.c:check_modinfo
```
**Symbols:**

```
ffffffff81048725-ffffffff8104873d: retpoline_module_ok.cold (STB_LOCAL)
ffffffff81048280-ffffffff810482aa: retpoline_module_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
bool retpoline_module_ok(bool has_retpoline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (0)
Location: arch/x86/kernel/cpu/bugs.c:497
Inline: False
Direct callers:
  - kernel/module.c:check_modinfo
```
**Symbols:**

```
ffffffff81049b35-ffffffff81049b4d: retpoline_module_ok.cold (STB_LOCAL)
ffffffff81049690-ffffffff810496ba: retpoline_module_ok (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
