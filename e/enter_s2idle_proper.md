# Function: <code>enter_s2idle_proper</code>

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
In drivers/cpuidle/cpuidle.c (ffffffff817e4093)
Location: drivers/cpuidle/cpuidle.c:131
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
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
In drivers/cpuidle/cpuidle.c (ffffffff8182d2af)
Location: drivers/cpuidle/cpuidle.c:131
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
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
In drivers/cpuidle/cpuidle.c (ffffffff8185928f)
Location: drivers/cpuidle/cpuidle.c:131
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
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
In drivers/cpuidle/cpuidle.c (ffffffff8189cbcf)
Location: drivers/cpuidle/cpuidle.c:131
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
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
In drivers/cpuidle/cpuidle.c (ffffffff818ceeef)
Location: drivers/cpuidle/cpuidle.c:131
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void enter_s2idle_proper(struct cpuidle_driver *drv, struct cpuidle_device *dev, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff819a1490)
Location: drivers/cpuidle/cpuidle.c:136
Inline: False
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
**Symbols:**

```
ffffffff819a1490-ffffffff819a1557: enter_s2idle_proper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void enter_s2idle_proper(struct cpuidle_driver *drv, struct cpuidle_device *dev, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff819a44e0)
Location: drivers/cpuidle/cpuidle.c:137
Inline: False
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
**Symbols:**

```
ffffffff819a44e0-ffffffff819a45c3: enter_s2idle_proper (STB_LOCAL)
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
In drivers/cpuidle/cpuidle.c (ffffffff8198932c)
Location: drivers/cpuidle/cpuidle.c:137
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
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
In drivers/cpuidle/cpuidle.c (ffffffff81a3369c)
Location: drivers/cpuidle/cpuidle.c:137
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void enter_s2idle_proper(struct cpuidle_driver *drv, struct cpuidle_device *dev, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff81b9f1f0)
Location: drivers/cpuidle/cpuidle.c:137
Inline: False
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
**Symbols:**

```
ffffffff81b9f1f0-ffffffff81b9f38a: enter_s2idle_proper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void enter_s2idle_proper(struct cpuidle_driver *drv, struct cpuidle_device *dev, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff81d40be0)
Location: drivers/cpuidle/cpuidle.c:139
Inline: False
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
**Symbols:**

```
ffffffff81d40be0-ffffffff81d40d7a: enter_s2idle_proper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void enter_s2idle_proper(struct cpuidle_driver *drv, struct cpuidle_device *dev, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff82142120)
Location: drivers/cpuidle/cpuidle.c:140
Inline: False
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
**Symbols:**

```
ffffffff82142120-ffffffff821422a7: enter_s2idle_proper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void enter_s2idle_proper(struct cpuidle_driver *drv, struct cpuidle_device *dev, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff82224810)
Location: drivers/cpuidle/cpuidle.c:140
Inline: False
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
**Symbols:**

```
ffffffff82224810-ffffffff82224997: enter_s2idle_proper (STB_LOCAL)
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
In drivers/cpuidle/cpuidle.c (ffff800010b26c58)
Location: drivers/cpuidle/cpuidle.c:131
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
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
In drivers/cpuidle/cpuidle.c (c0c01a2c)
Location: drivers/cpuidle/cpuidle.c:131
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
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
In drivers/cpuidle/cpuidle.c (c000000000c1dd10)
Location: drivers/cpuidle/cpuidle.c:131
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
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
In drivers/cpuidle/cpuidle.c (ffffffff8183c78f)
Location: drivers/cpuidle/cpuidle.c:131
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
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
In drivers/cpuidle/cpuidle.c (ffffffff818c439f)
Location: drivers/cpuidle/cpuidle.c:131
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
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
In drivers/cpuidle/cpuidle.c (ffffffff818e071f)
Location: drivers/cpuidle/cpuidle.c:131
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
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
