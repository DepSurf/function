# Function: <code>klp_check_stack</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (0)
Location: kernel/livepatch/transition.c:241
Inline: False
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
In kernel/livepatch/transition.c (ffffffff811035b6)
Location: kernel/livepatch/transition.c:266
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_switch_task
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
In kernel/livepatch/transition.c (ffffffff8110bae7)
Location: kernel/livepatch/transition.c:254
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_switch_task
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
In kernel/livepatch/transition.c (ffffffff811172d7)
Location: kernel/livepatch/transition.c:254
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_switch_task
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
In kernel/livepatch/transition.c (ffffffff8112158f)
Location: kernel/livepatch/transition.c:242
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
In kernel/livepatch/transition.c (ffffffff8112dbaf)
Location: kernel/livepatch/transition.c:242
Inline: True
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
In kernel/livepatch/transition.c (ffffffff8113c170)
Location: kernel/livepatch/transition.c:242
Inline: True
```
**Symbols:**

```
ffffffff8113c170-ffffffff8113c312: klp_check_stack.constprop.0 (STB_LOCAL)
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
In kernel/livepatch/transition.c (ffffffff81136880)
Location: kernel/livepatch/transition.c:242
Inline: True
```
**Symbols:**

```
ffffffff81136880-ffffffff81136a22: klp_check_stack.constprop.0 (STB_LOCAL)
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
In kernel/livepatch/transition.c (ffffffff811376d2)
Location: kernel/livepatch/transition.c:243
Inline: True
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
In kernel/livepatch/transition.c (0)
Location: kernel/livepatch/transition.c:243
Inline: True
```
**Symbols:**

```
ffffffff8115a370-ffffffff8115a51e: klp_check_stack.constprop.0 (STB_LOCAL)
ffffffff81caffd2-ffffffff81caffe6: klp_check_stack.constprop.0.cold (STB_LOCAL)
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
In kernel/livepatch/transition.c (ffffffff81183d3c)
Location: kernel/livepatch/transition.c:241
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
In kernel/livepatch/transition.c (ffffffff811bef68)
Location: kernel/livepatch/transition.c:241
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
In kernel/livepatch/transition.c (ffffffff811d180c)
Location: kernel/livepatch/transition.c:263
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
In kernel/livepatch/transition.c (ffffffff811e648c)
Location: kernel/livepatch/transition.c:263
Inline: True
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
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (c0000000001f2a3c)
Location: kernel/livepatch/transition.c:242
Inline: True
```
</details>
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
In kernel/livepatch/transition.c (ffffffff8112618f)
Location: kernel/livepatch/transition.c:242
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
In kernel/livepatch/transition.c (ffffffff81118bef)
Location: kernel/livepatch/transition.c:242
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
In kernel/livepatch/transition.c (ffffffff8112407f)
Location: kernel/livepatch/transition.c:242
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
In kernel/livepatch/transition.c (ffffffff811306bf)
Location: kernel/livepatch/transition.c:242
Inline: True
```
</details>
</li>
</ul>

## Differences
