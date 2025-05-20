# Function: <code>__down_trylock_console_sem</code>

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
In kernel/printk/printk.c (ffffffff810d7176)
Location: kernel/printk/printk.c:108
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unblank
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
In kernel/printk/printk.c (ffffffff810ded24)
Location: kernel/printk/printk.c:214
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unblank
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
In kernel/printk/printk.c (ffffffff810e5284)
Location: kernel/printk/printk.c:214
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unblank
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
In kernel/printk/printk.c (ffffffff810e26b0)
Location: kernel/printk/printk.c:217
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff810e26b0-ffffffff810e26fd: __down_trylock_console_sem.isra.19 (STB_LOCAL)
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
In kernel/printk/printk.c (ffffffff810ea570)
Location: kernel/printk/printk.c:217
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff810ea570-ffffffff810ea5bd: __down_trylock_console_sem.isra.19 (STB_LOCAL)
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
In kernel/printk/printk.c (ffffffff810f2640)
Location: kernel/printk/printk.c:214
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff810f2640-ffffffff810f268d: __down_trylock_console_sem.isra.18 (STB_LOCAL)
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
In kernel/printk/printk.c (ffffffff810fdc80)
Location: kernel/printk/printk.c:208
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff810fdc80-ffffffff810fdccd: __down_trylock_console_sem.isra.18 (STB_LOCAL)
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
In kernel/printk/printk.c (ffffffff811063b0)
Location: kernel/printk/printk.c:216
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff811063b0-ffffffff811063fb: __down_trylock_console_sem.isra.0 (STB_LOCAL)
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
In kernel/printk/printk.c (ffffffff81112740)
Location: kernel/printk/printk.c:226
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff81112740-ffffffff8111278b: __down_trylock_console_sem.isra.0 (STB_LOCAL)
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
In kernel/printk/printk.c (ffffffff811205e6)
Location: kernel/printk/printk.c:225
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unblank
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
In kernel/printk/printk.c (ffffffff8111b586)
Location: kernel/printk/printk.c:226
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unblank
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
In kernel/printk/printk.c (ffffffff8111bc66)
Location: kernel/printk/printk.c:226
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unblank
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
In kernel/printk/printk.c (ffffffff8113bc96)
Location: kernel/printk/printk.c:226
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unblank
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
In kernel/printk/printk.c (ffffffff8115bfc0)
Location: kernel/printk/printk.c:235
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_trylock_spinning
```
**Symbols:**

```
ffffffff8115bfc0-ffffffff8115c014: __down_trylock_console_sem.constprop.0 (STB_LOCAL)
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
In kernel/printk/printk.c (ffffffff8118ea20)
Location: kernel/printk/printk.c:316
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_trylock_spinning
```
**Symbols:**

```
ffffffff8118ea20-ffffffff8118ea7a: __down_trylock_console_sem.constprop.0 (STB_LOCAL)
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
In kernel/printk/printk.c (ffffffff811a04f0)
Location: kernel/printk/printk.c:318
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_trylock_spinning
```
**Symbols:**

```
ffffffff811a04f0-ffffffff811a054a: __down_trylock_console_sem.isra.0 (STB_LOCAL)
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
In kernel/printk/printk.c (ffffffff811af510)
Location: kernel/printk/printk.c:312
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_trylock_spinning
```
**Symbols:**

```
ffffffff811af510-ffffffff811af56a: __down_trylock_console_sem.isra.0 (STB_LOCAL)
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
In kernel/printk/printk.c (ffff800010172ca0)
Location: kernel/printk/printk.c:226
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffff800010172ca0-ffff800010172d04: __down_trylock_console_sem.isra.0 (STB_LOCAL)
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
In kernel/printk/printk.c (c03c5580)
Location: kernel/printk/printk.c:226
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_unblank
```
**Symbols:**

```
c03c5580-c03c55c4: __down_trylock_console_sem.constprop.0 (STB_LOCAL)
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
In kernel/printk/printk.c (c0000000001cc1c0)
Location: kernel/printk/printk.c:226
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
c0000000001cc1c0-c0000000001cc244: __down_trylock_console_sem.isra.0 (STB_LOCAL)
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
In kernel/printk/printk.c (ffffffe00010ec48)
Location: kernel/printk/printk.c:226
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffe00010ec48-ffffffe00010ec9c: __down_trylock_console_sem.isra.0 (STB_LOCAL)
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
In kernel/printk/printk.c (ffffffff8110ad20)
Location: kernel/printk/printk.c:226
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff8110ad20-ffffffff8110ad6b: __down_trylock_console_sem.isra.0 (STB_LOCAL)
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
In kernel/printk/printk.c (ffffffff810fb6d0)
Location: kernel/printk/printk.c:226
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff810fb6d0-ffffffff810fb707: __down_trylock_console_sem.isra.0 (STB_LOCAL)
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
In kernel/printk/printk.c (ffffffff81108c10)
Location: kernel/printk/printk.c:226
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff81108c10-ffffffff81108c5b: __down_trylock_console_sem.isra.0 (STB_LOCAL)
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
In kernel/printk/printk.c (ffffffff81114240)
Location: kernel/printk/printk.c:226
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff81114240-ffffffff8111428b: __down_trylock_console_sem.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
