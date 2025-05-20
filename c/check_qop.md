# Function: <code>check_qop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int check_qop(struct sem_array *sma, int semnum, struct sem_queue *q, bool count_zero);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81326c80)
Location: ipc/sem.c:1016
Inline: False
Direct callers:
  - ipc/sem.c:count_semcnt
  - ipc/sem.c:count_semcnt
```
**Symbols:**

```
ffffffff81326c80-ffffffff81326d0b: check_qop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/sem.c (ffffffff8135c380)
Location: ipc/sem.c:1012
Inline: True
Direct callers:
  - ipc/sem.c:count_semcnt
  - ipc/sem.c:count_semcnt
```
**Symbols:**

```
ffffffff8135c380-ffffffff8135c401: check_qop.constprop.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/sem.c (ffffffff81372a20)
Location: ipc/sem.c:1008
Inline: True
Direct callers:
  - ipc/sem.c:count_semcnt
  - ipc/sem.c:count_semcnt
```
**Symbols:**

```
ffffffff81372a20-ffffffff81372aa1: check_qop.constprop.21 (STB_LOCAL)
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
In ipc/sem.c (ffffffff81385e10)
Location: ipc/sem.c:1019
Inline: True
Direct callers:
  - ipc/sem.c:count_semcnt
  - ipc/sem.c:count_semcnt
```
**Symbols:**

```
ffffffff81385e10-ffffffff81385e90: check_qop.constprop.16 (STB_LOCAL)
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
In ipc/sem.c (ffffffff813aa720)
Location: ipc/sem.c:1022
Inline: True
Direct callers:
  - ipc/sem.c:count_semcnt
  - ipc/sem.c:count_semcnt
```
**Symbols:**

```
ffffffff813aa720-ffffffff813aa7a0: check_qop.constprop.17 (STB_LOCAL)
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
In ipc/sem.c (0)
Location: ipc/sem.c:1058
Inline: True
Direct callers:
  - ipc/sem.c:count_semcnt
  - ipc/sem.c:count_semcnt
```
**Symbols:**

```
ffffffff813d95d0-ffffffff813d9622: check_qop.constprop.24 (STB_LOCAL)
ffffffff813dd565-ffffffff813dd593: check_qop.constprop.24.cold.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1057
Inline: True
Direct callers:
  - ipc/sem.c:count_semcnt
  - ipc/sem.c:count_semcnt
```
**Symbols:**

```
ffffffff813f3c20-ffffffff813f3c72: check_qop.constprop.24 (STB_LOCAL)
ffffffff813f7bf2-ffffffff813f7c20: check_qop.constprop.24.cold.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1053
Inline: True
Direct callers:
  - ipc/sem.c:count_semcnt
  - ipc/sem.c:count_semcnt
```
**Symbols:**

```
ffffffff81420070-ffffffff814200c3: check_qop.constprop.0 (STB_LOCAL)
ffffffff814240d6-ffffffff81424104: check_qop.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1053
Inline: True
Direct callers:
  - ipc/sem.c:count_semcnt
  - ipc/sem.c:count_semcnt
```
**Symbols:**

```
ffffffff81439e70-ffffffff81439ec3: check_qop.constprop.0 (STB_LOCAL)
ffffffff8143de2c-ffffffff8143de5a: check_qop.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/sem.c (ffffffff8148a0ef)
Location: ipc/sem.c:1069
Inline: True
Inline callers:
  - ipc/sem.c:count_semcnt
Direct callers:
  - ipc/sem.c:count_semcnt
```
**Symbols:**

```
ffffffff8148a000-ffffffff8148a051: check_qop.constprop.0.isra.0 (STB_LOCAL)
ffffffff8148eae7-ffffffff8148eb15: check_qop.constprop.0.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/sem.c (ffffffff814a770f)
Location: ipc/sem.c:1068
Inline: True
Inline callers:
  - ipc/sem.c:count_semcnt
Direct callers:
  - ipc/sem.c:count_semcnt
```
**Symbols:**

```
ffffffff814a7620-ffffffff814a7671: check_qop.constprop.0.isra.0 (STB_LOCAL)
ffffffff81befaa1-ffffffff81befacf: check_qop.constprop.0.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/sem.c (ffffffff814ad64f)
Location: ipc/sem.c:1070
Inline: True
Inline callers:
  - ipc/sem.c:count_semcnt
Direct callers:
  - ipc/sem.c:count_semcnt
```
**Symbols:**

```
ffffffff814ad560-ffffffff814ad5b1: check_qop.constprop.0.isra.0 (STB_LOCAL)
ffffffff81be1b48-ffffffff81be1b76: check_qop.constprop.0.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/sem.c (ffffffff81505b1f)
Location: ipc/sem.c:1073
Inline: True
Inline callers:
  - ipc/sem.c:count_semcnt
Direct callers:
  - ipc/sem.c:count_semcnt
```
**Symbols:**

```
ffffffff81505a20-ffffffff81505a86: check_qop.constprop.0.isra.0 (STB_LOCAL)
ffffffff81cd29f1-ffffffff81cd2a34: check_qop.constprop.0.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/sem.c (ffffffff815977b9)
Location: ipc/sem.c:1072
Inline: True
Inline callers:
  - ipc/sem.c:count_semcnt
Direct callers:
  - ipc/sem.c:count_semcnt
```
**Symbols:**

```
ffffffff81597520-ffffffff8159759a: check_qop.constprop.0.isra.0 (STB_LOCAL)
ffffffff81e85b4c-ffffffff81e85b8f: check_qop.constprop.0.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/sem.c (ffffffff81640909)
Location: ipc/sem.c:1072
Inline: True
Inline callers:
  - ipc/sem.c:count_semcnt
Direct callers:
  - ipc/sem.c:count_semcnt
```
**Symbols:**

```
ffffffff81640620-ffffffff816406c1: check_qop.constprop.0.isra.0 (STB_LOCAL)
ffffffff82072d4a-ffffffff82072d5f: check_qop.constprop.0.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/sem.c (ffffffff81678e5a)
Location: ipc/sem.c:1072
Inline: True
Inline callers:
  - ipc/sem.c:count_semcnt
Direct callers:
  - ipc/sem.c:count_semcnt
```
**Symbols:**

```
ffffffff81678b40-ffffffff81678be1: check_qop.isra.0 (STB_LOCAL)
ffffffff820f29a1-ffffffff820f29b6: check_qop.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/sem.c (ffffffff816b524a)
Location: ipc/sem.c:1072
Inline: True
Inline callers:
  - ipc/sem.c:count_semcnt
Direct callers:
  - ipc/sem.c:count_semcnt
```
**Symbols:**

```
ffffffff816b4f30-ffffffff816b4fd1: check_qop.isra.0 (STB_LOCAL)
ffffffff821cfc51-ffffffff821cfc66: check_qop.isra.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/sem.c (ffff800010521650)
Location: ipc/sem.c:1053
Inline: True
Direct callers:
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffff800010521650-ffff8000105216d8: check_qop.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/sem.c (c06dc6a4)
Location: ipc/sem.c:1053
Inline: True
Direct callers:
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
c06dc6a4-c06dc734: check_qop.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/sem.c (c00000000066ae70)
Location: ipc/sem.c:1053
Inline: True
Direct callers:
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
c00000000066ae70-c00000000066af24: check_qop.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/sem.c (ffffffe0003878c8)
Location: ipc/sem.c:1053
Inline: True
Direct callers:
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffe0003878c8-ffffffe00038793c: check_qop.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1053
Inline: True
Direct callers:
  - ipc/sem.c:count_semcnt
  - ipc/sem.c:count_semcnt
```
**Symbols:**

```
ffffffff81432450-ffffffff814324a3: check_qop.constprop.0 (STB_LOCAL)
ffffffff8143640c-ffffffff8143643a: check_qop.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1053
Inline: True
Direct callers:
  - ipc/sem.c:count_semcnt
  - ipc/sem.c:count_semcnt
```
**Symbols:**

```
ffffffff81422ed0-ffffffff81422f23: check_qop.constprop.0 (STB_LOCAL)
ffffffff81426e8c-ffffffff81426eba: check_qop.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1053
Inline: True
Direct callers:
  - ipc/sem.c:count_semcnt
  - ipc/sem.c:count_semcnt
```
**Symbols:**

```
ffffffff8142e5f0-ffffffff8142e643: check_qop.constprop.0 (STB_LOCAL)
ffffffff814325ac-ffffffff814325da: check_qop.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1053
Inline: True
Direct callers:
  - ipc/sem.c:count_semcnt
  - ipc/sem.c:count_semcnt
```
**Symbols:**

```
ffffffff81445950-ffffffff814459a3: check_qop.constprop.0 (STB_LOCAL)
ffffffff81449678-ffffffff814496a6: check_qop.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
