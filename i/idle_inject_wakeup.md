# Function: <code>idle_inject_wakeup</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void idle_inject_wakeup(struct idle_inject_device *ii_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/powercap/idle_inject.c (ffffffff81883c40)
Location: drivers/powercap/idle_inject.c:83
Inline: False
Direct callers:
  - drivers/powercap/idle_inject.c:idle_inject_start
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
```
**Symbols:**

```
ffffffff81883c40-ffffffff81883c9e: idle_inject_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void idle_inject_wakeup(struct idle_inject_device *ii_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/powercap/idle_inject.c (ffffffff818ce340)
Location: drivers/powercap/idle_inject.c:83
Inline: False
Direct callers:
  - drivers/powercap/idle_inject.c:idle_inject_start
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
```
**Symbols:**

```
ffffffff818ce340-ffffffff818ce3a2: idle_inject_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void idle_inject_wakeup(struct idle_inject_device *ii_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/powercap/idle_inject.c (ffffffff81900730)
Location: drivers/powercap/idle_inject.c:83
Inline: False
Direct callers:
  - drivers/powercap/idle_inject.c:idle_inject_start
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
```
**Symbols:**

```
ffffffff81900730-ffffffff81900792: idle_inject_wakeup (STB_LOCAL)
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
In drivers/powercap/idle_inject.c (ffffffff819d77a0)
Location: drivers/powercap/idle_inject.c:85
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_start
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
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
In drivers/powercap/idle_inject.c (ffffffff819d68e0)
Location: drivers/powercap/idle_inject.c:86
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_start
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
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
In drivers/powercap/idle_inject.c (ffffffff819bca60)
Location: drivers/powercap/idle_inject.c:86
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_start
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
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
In drivers/powercap/idle_inject.c (ffffffff81a6bf14)
Location: drivers/powercap/idle_inject.c:86
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_start
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
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
In drivers/powercap/idle_inject.c (ffffffff81bdc9c3)
Location: drivers/powercap/idle_inject.c:86
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_start
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void idle_inject_wakeup(struct idle_inject_device *ii_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/powercap/idle_inject.c (ffffffff81d87b10)
Location: drivers/powercap/idle_inject.c:86
Inline: False
Direct callers:
  - drivers/powercap/idle_inject.c:idle_inject_start
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
```
**Symbols:**

```
ffffffff81d87b10-ffffffff81d87b9f: idle_inject_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void idle_inject_wakeup(struct idle_inject_device *ii_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/powercap/idle_inject.c (ffffffff81df6060)
Location: drivers/powercap/idle_inject.c:102
Inline: False
Direct callers:
  - drivers/powercap/idle_inject.c:idle_inject_start
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
```
**Symbols:**

```
ffffffff81df6060-ffffffff81df60ef: idle_inject_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void idle_inject_wakeup(struct idle_inject_device *ii_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/powercap/idle_inject.c (ffffffff81eac750)
Location: drivers/powercap/idle_inject.c:102
Inline: False
Direct callers:
  - drivers/powercap/idle_inject.c:idle_inject_start
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
```
**Symbols:**

```
ffffffff81eac750-ffffffff81eac7df: idle_inject_wakeup (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void idle_inject_wakeup(struct idle_inject_device *ii_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/powercap/idle_inject.c (ffff800010b8ff28)
Location: drivers/powercap/idle_inject.c:83
Inline: False
Direct callers:
  - drivers/powercap/idle_inject.c:idle_inject_start
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
```
**Symbols:**

```
ffff800010b8ff28-ffff800010b8ffc0: idle_inject_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void idle_inject_wakeup(struct idle_inject_device *ii_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/powercap/idle_inject.c (c0c79fb4)
Location: drivers/powercap/idle_inject.c:83
Inline: False
Direct callers:
  - drivers/powercap/idle_inject.c:idle_inject_start
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
```
**Symbols:**

```
c0c79fb4-c0c7a02c: idle_inject_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void idle_inject_wakeup(struct idle_inject_device *ii_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/powercap/idle_inject.c (c000000000c6f0c0)
Location: drivers/powercap/idle_inject.c:83
Inline: False
Direct callers:
  - drivers/powercap/idle_inject.c:idle_inject_start
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
```
**Symbols:**

```
c000000000c6f0c0-c000000000c6f1a0: idle_inject_wakeup (STB_LOCAL)
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
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void idle_inject_wakeup(struct idle_inject_device *ii_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/powercap/idle_inject.c (ffffffff818f1150)
Location: drivers/powercap/idle_inject.c:83
Inline: False
Direct callers:
  - drivers/powercap/idle_inject.c:idle_inject_start
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
```
**Symbols:**

```
ffffffff818f1150-ffffffff818f11b2: idle_inject_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void idle_inject_wakeup(struct idle_inject_device *ii_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/powercap/idle_inject.c (ffffffff819121d0)
Location: drivers/powercap/idle_inject.c:83
Inline: False
Direct callers:
  - drivers/powercap/idle_inject.c:idle_inject_start
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
```
**Symbols:**

```
ffffffff819121d0-ffffffff81912232: idle_inject_wakeup (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
