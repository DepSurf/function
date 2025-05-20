# Function: <code>s2idle_enter</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff810e0b5d)
Location: kernel/power/suspend.c:77
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
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
In kernel/power/suspend.c (ffffffff810e9508)
Location: kernel/power/suspend.c:78
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
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
In kernel/power/suspend.c (ffffffff810f4b28)
Location: kernel/power/suspend.c:84
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
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
In kernel/power/suspend.c (ffffffff810fcdfa)
Location: kernel/power/suspend.c:88
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
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
In kernel/power/suspend.c (ffffffff81109266)
Location: kernel/power/suspend.c:88
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void s2idle_enter();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff81113b60)
Location: kernel/power/suspend.c:88
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
```
**Symbols:**

```
ffffffff81113b60-ffffffff81113d15: s2idle_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void s2idle_enter();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff81110830)
Location: kernel/power/suspend.c:88
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
```
**Symbols:**

```
ffffffff81110830-ffffffff811109b8: s2idle_enter (STB_LOCAL)
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
In kernel/power/suspend.c (ffffffff811112d2)
Location: kernel/power/suspend.c:88
Inline: True
Inline callers:
  - kernel/power/suspend.c:s2idle_loop
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
In kernel/power/suspend.c (ffffffff81130d2b)
Location: kernel/power/suspend.c:88
Inline: True
Inline callers:
  - kernel/power/suspend.c:s2idle_loop
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
In kernel/power/suspend.c (ffffffff81152525)
Location: kernel/power/suspend.c:88
Inline: True
Inline callers:
  - kernel/power/suspend.c:s2idle_loop
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
In kernel/power/suspend.c (ffffffff811817af)
Location: kernel/power/suspend.c:90
Inline: True
Inline callers:
  - kernel/power/suspend.c:s2idle_loop
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
In kernel/power/suspend.c (ffffffff81192792)
Location: kernel/power/suspend.c:90
Inline: True
Inline callers:
  - kernel/power/suspend.c:s2idle_loop
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
In kernel/power/suspend.c (ffffffff811a1182)
Location: kernel/power/suspend.c:90
Inline: True
Inline callers:
  - kernel/power/suspend.c:s2idle_loop
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
In kernel/power/suspend.c (ffff800010170624)
Location: kernel/power/suspend.c:88
Inline: True
Inline callers:
  - kernel/power/suspend.c:s2idle_loop
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
In kernel/power/suspend.c (c03bb658)
Location: kernel/power/suspend.c:88
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
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
In kernel/power/suspend.c (c0000000001c8f78)
Location: kernel/power/suspend.c:88
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff810f296a)
Location: kernel/power/suspend.c:88
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
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
In kernel/power/suspend.c (ffffffff810ff736)
Location: kernel/power/suspend.c:88
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
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
In kernel/power/suspend.c (ffffffff8110aa46)
Location: kernel/power/suspend.c:88
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
