# Function: <code>tk_set_xtime</code>

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
In kernel/time/timekeeping.c (ffffffff810f5267)
Location: kernel/time/timekeeping.c:84
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_settimeofday64
  - kernel/time/timekeeping.c:timekeeping_init
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
In kernel/time/timekeeping.c (ffffffff81fa9521)
Location: kernel/time/timekeeping.c:84
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:do_settimeofday64
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
In kernel/time/timekeeping.c (ffffffff81fe504c)
Location: kernel/time/timekeeping.c:84
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:do_settimeofday64
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
In kernel/time/timekeeping.c (ffffffff820c5cfb)
Location: kernel/time/timekeeping.c:90
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:do_settimeofday64
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
In kernel/time/timekeeping.c (ffffffff826ce3a1)
Location: kernel/time/timekeeping.c:109
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:do_settimeofday64
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
In kernel/time/timekeeping.c (ffffffff826f8b0d)
Location: kernel/time/timekeeping.c:109
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
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
In kernel/time/timekeeping.c (ffffffff828af9f6)
Location: kernel/time/timekeeping.c:115
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
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
In kernel/time/timekeeping.c (ffffffff828c8588)
Location: kernel/time/timekeeping.c:116
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
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
In kernel/time/timekeeping.c (ffffffff828d0b66)
Location: kernel/time/timekeeping.c:116
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
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
In kernel/time/timekeeping.c (ffffffff82cf1aa8)
Location: kernel/time/timekeeping.c:116
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
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
In kernel/time/timekeeping.c (ffffffff82fde543)
Location: kernel/time/timekeeping.c:136
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
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
In kernel/time/timekeeping.c (ffffffff831e906d)
Location: kernel/time/timekeeping.c:136
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
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
In kernel/time/timekeeping.c (ffffffff8116a3f3)
Location: kernel/time/timekeeping.c:136
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_init
```
**Symbols:**

```
ffffffff81169340-ffffffff8116937e: tk_set_xtime.constprop.0 (STB_LOCAL)
ffffffff81cb0bad-ffffffff81cb0bca: tk_set_xtime.constprop.0.cold (STB_LOCAL)
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
In kernel/time/timekeeping.c (ffffffff8119ea62)
Location: kernel/time/timekeeping.c:138
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_settimeofday64
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_init
```
**Symbols:**

```
ffffffff8119cf90-ffffffff8119cfdc: tk_set_xtime.constprop.0 (STB_LOCAL)
ffffffff81e62145-ffffffff81e62162: tk_set_xtime.constprop.0.cold (STB_LOCAL)
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
In kernel/time/timekeeping.c (ffffffff83eae00c)
Location: kernel/time/timekeeping.c:138
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:do_settimeofday64
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
In kernel/time/timekeeping.c (ffffffff836d308a)
Location: kernel/time/timekeeping.c:138
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:do_settimeofday64
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
In kernel/time/timekeeping.c (ffffffff83904e4a)
Location: kernel/time/timekeeping.c:138
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:do_settimeofday64
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
In kernel/time/timekeeping.c (ffff800011448aac)
Location: kernel/time/timekeeping.c:116
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
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
In kernel/time/timekeeping.c (c1522b58)
Location: kernel/time/timekeeping.c:116
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
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
In kernel/time/timekeeping.c (c00000000136dcb0)
Location: kernel/time/timekeeping.c:116
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
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
In kernel/time/timekeeping.c (ffffffe00000a022)
Location: kernel/time/timekeeping.c:116
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
```
</details>
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
In kernel/time/timekeeping.c (ffffffff828b9a17)
Location: kernel/time/timekeeping.c:116
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
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
In kernel/time/timekeeping.c (ffffffff828b1f68)
Location: kernel/time/timekeeping.c:116
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
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
In kernel/time/timekeeping.c (ffffffff828cc79a)
Location: kernel/time/timekeeping.c:116
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
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
In kernel/time/timekeeping.c (ffffffff828d1b94)
Location: kernel/time/timekeeping.c:116
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
```
</details>
</li>
</ul>

## Differences
