# Function: <code>teo_update</code>

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
In drivers/cpuidle/governors/teo.c (ffffffff8189f083)
Location: drivers/cpuidle/governors/teo.c:119
Inline: True
Inline callers:
  - drivers/cpuidle/governors/teo.c:teo_select
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
In drivers/cpuidle/governors/teo.c (ffffffff818d15f1)
Location: drivers/cpuidle/governors/teo.c:117
Inline: True
Inline callers:
  - drivers/cpuidle/governors/teo.c:teo_select
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void teo_update(struct cpuidle_driver *drv, struct cpuidle_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governors/teo.c (ffffffff819a3840)
Location: drivers/cpuidle/governors/teo.c:117
Inline: False
Direct callers:
  - drivers/cpuidle/governors/teo.c:teo_select
```
**Symbols:**

```
ffffffff819a3840-ffffffff819a397e: teo_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void teo_update(struct cpuidle_driver *drv, struct cpuidle_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governors/teo.c (ffffffff819a6820)
Location: drivers/cpuidle/governors/teo.c:117
Inline: False
Direct callers:
  - drivers/cpuidle/governors/teo.c:teo_select
```
**Symbols:**

```
ffffffff819a6820-ffffffff819a695e: teo_update (STB_LOCAL)
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
In drivers/cpuidle/governors/teo.c (ffffffff8198b887)
Location: drivers/cpuidle/governors/teo.c:117
Inline: True
Inline callers:
  - drivers/cpuidle/governors/teo.c:teo_select
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void teo_update(struct cpuidle_driver *drv, struct cpuidle_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governors/teo.c (ffffffff81a364d0)
Location: drivers/cpuidle/governors/teo.c:160
Inline: False
Direct callers:
  - drivers/cpuidle/governors/teo.c:teo_select
```
**Symbols:**

```
ffffffff81a364d0-ffffffff81a367f6: teo_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void teo_update(struct cpuidle_driver *drv, struct cpuidle_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governors/teo.c (ffffffff81ba2f50)
Location: drivers/cpuidle/governors/teo.c:160
Inline: False
Direct callers:
  - drivers/cpuidle/governors/teo.c:teo_select
```
**Symbols:**

```
ffffffff81ba2f50-ffffffff81ba328d: teo_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void teo_update(struct cpuidle_driver *drv, struct cpuidle_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governors/teo.c (ffffffff81d44ec0)
Location: drivers/cpuidle/governors/teo.c:160
Inline: False
Direct callers:
  - drivers/cpuidle/governors/teo.c:teo_select
```
**Symbols:**

```
ffffffff81d44ec0-ffffffff81d451fd: teo_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void teo_update(struct cpuidle_driver *drv, struct cpuidle_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governors/teo.c (ffffffff81daf360)
Location: drivers/cpuidle/governors/teo.c:227
Inline: False
Direct callers:
  - drivers/cpuidle/governors/teo.c:teo_select
```
**Symbols:**

```
ffffffff81daf360-ffffffff81daf736: teo_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void teo_update(struct cpuidle_driver *drv, struct cpuidle_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governors/teo.c (ffffffff81e67420)
Location: drivers/cpuidle/governors/teo.c:228
Inline: False
Direct callers:
  - drivers/cpuidle/governors/teo.c:teo_select
```
**Symbols:**

```
ffffffff81e67420-ffffffff81e67889: teo_update (STB_LOCAL)
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
In drivers/cpuidle/governors/teo.c (ffff800010b2a0b8)
Location: drivers/cpuidle/governors/teo.c:117
Inline: True
Inline callers:
  - drivers/cpuidle/governors/teo.c:teo_select
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
In drivers/cpuidle/governors/teo.c (c0c04b44)
Location: drivers/cpuidle/governors/teo.c:117
Inline: True
Inline callers:
  - drivers/cpuidle/governors/teo.c:teo_select
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
In drivers/cpuidle/governors/teo.c (c000000000c21dc0)
Location: drivers/cpuidle/governors/teo.c:117
Inline: True
Inline callers:
  - drivers/cpuidle/governors/teo.c:teo_select
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
In drivers/cpuidle/governors/teo.c (ffffffff81874fb3)
Location: drivers/cpuidle/governors/teo.c:117
Inline: True
Inline callers:
  - drivers/cpuidle/governors/teo.c:teo_select
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
In drivers/cpuidle/governors/teo.c (ffffffff8183ee81)
Location: drivers/cpuidle/governors/teo.c:117
Inline: True
Inline callers:
  - drivers/cpuidle/governors/teo.c:teo_select
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/governors/teo.c (ffffffff818e2f01)
Location: drivers/cpuidle/governors/teo.c:117
Inline: True
Inline callers:
  - drivers/cpuidle/governors/teo.c:teo_select
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
