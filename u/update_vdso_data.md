# Function: <code>update_vdso_data</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/vsyscall.c (ffffffff8113ddc8)
Location: kernel/time/vsyscall.c:16
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:update_vsyscall
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
In kernel/time/vsyscall.c (ffffffff8114997b)
Location: kernel/time/vsyscall.c:16
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:update_vsyscall
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
In kernel/time/vsyscall.c (ffffffff811598ea)
Location: kernel/time/vsyscall.c:16
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:update_vsyscall
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
In kernel/time/vsyscall.c (ffffffff8115587a)
Location: kernel/time/vsyscall.c:18
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:update_vsyscall
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
In kernel/time/vsyscall.c (ffffffff81156cb9)
Location: kernel/time/vsyscall.c:18
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:update_vsyscall
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
In kernel/time/vsyscall.c (0)
Location: kernel/time/vsyscall.c:18
Inline: True
Direct callers:
  - kernel/time/vsyscall.c:update_vsyscall
```
**Symbols:**

```
ffffffff8117b960-ffffffff8117bacb: update_vdso_data.constprop.0 (STB_LOCAL)
ffffffff81cb21c5-ffffffff81cb228a: update_vdso_data.constprop.0.cold (STB_LOCAL)
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
In kernel/time/vsyscall.c (0)
Location: kernel/time/vsyscall.c:18
Inline: True
Direct callers:
  - kernel/time/vsyscall.c:update_vsyscall
```
**Symbols:**

```
ffffffff811b1010-ffffffff811b1182: update_vdso_data.constprop.0 (STB_LOCAL)
ffffffff81e6370c-ffffffff81e637d1: update_vdso_data.constprop.0.cold (STB_LOCAL)
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
In kernel/time/vsyscall.c (0)
Location: kernel/time/vsyscall.c:18
Inline: True
Direct callers:
  - kernel/time/vsyscall.c:update_vsyscall
```
**Symbols:**

```
ffffffff811f1c60-ffffffff811f1dd2: update_vdso_data.constprop.0 (STB_LOCAL)
ffffffff8205bdf1-ffffffff8205beb6: update_vdso_data.constprop.0.cold (STB_LOCAL)
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
In kernel/time/vsyscall.c (0)
Location: kernel/time/vsyscall.c:18
Inline: True
Direct callers:
  - kernel/time/vsyscall.c:update_vsyscall
```
**Symbols:**

```
ffffffff81206410-ffffffff81206582: update_vdso_data.constprop.0 (STB_LOCAL)
ffffffff820da600-ffffffff820da6bd: update_vdso_data.constprop.0.cold (STB_LOCAL)
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
In kernel/time/vsyscall.c (0)
Location: kernel/time/vsyscall.c:18
Inline: True
Direct callers:
  - kernel/time/vsyscall.c:update_vsyscall
```
**Symbols:**

```
ffffffff8121d620-ffffffff8121d792: update_vdso_data.constprop.0 (STB_LOCAL)
ffffffff821b6170-ffffffff821b622d: update_vdso_data.constprop.0.cold (STB_LOCAL)
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
In kernel/time/vsyscall.c (ffff8000101b615c)
Location: kernel/time/vsyscall.c:16
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:update_vsyscall
```
</details>
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
In kernel/time/vsyscall.c (ffffffff81141f9b)
Location: kernel/time/vsyscall.c:16
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:update_vsyscall
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
In kernel/time/vsyscall.c (ffffffff811352fb)
Location: kernel/time/vsyscall.c:16
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:update_vsyscall
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
In kernel/time/vsyscall.c (ffffffff8113fe4b)
Location: kernel/time/vsyscall.c:16
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:update_vsyscall
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
In kernel/time/vsyscall.c (ffffffff8114c97b)
Location: kernel/time/vsyscall.c:16
Inline: True
Inline callers:
  - kernel/time/vsyscall.c:update_vsyscall
```
</details>
</li>
</ul>

## Differences
