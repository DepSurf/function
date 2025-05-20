# Function: <code>__reset_control_get_from_lookup</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct reset_control *__reset_control_get_from_lookup(struct device *dev, const char *con_id, bool shared, bool optional);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8160e920)
Location: drivers/reset/core.c:545
Inline: False
Direct callers:
  - drivers/reset/core.c:__device_reset
```
**Symbols:**

```
ffffffff8160e920-ffffffff8160eb8d: __reset_control_get_from_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct reset_control *__reset_control_get_from_lookup(struct device *dev, const char *con_id, bool shared, bool optional);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8162b110)
Location: drivers/reset/core.c:546
Inline: False
Direct callers:
  - drivers/reset/core.c:__device_reset
```
**Symbols:**

```
ffffffff8162b110-ffffffff8162b37d: __reset_control_get_from_lookup (STB_LOCAL)
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
In drivers/reset/core.c (ffffffff8165f0d6)
Location: drivers/reset/core.c:685
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
In drivers/reset/core.c (ffffffff816817c4)
Location: drivers/reset/core.c:684
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct reset_control *__reset_control_get_from_lookup(struct device *dev, const char *con_id, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81732980)
Location: drivers/reset/core.c:685
Inline: False
Direct callers:
  - drivers/reset/core.c:__device_reset
```
**Symbols:**

```
ffffffff81732980-ffffffff81732ae9: __reset_control_get_from_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct reset_control *__reset_control_get_from_lookup(struct device *dev, const char *con_id, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8174eb40)
Location: drivers/reset/core.c:759
Inline: False
Direct callers:
  - drivers/reset/core.c:__device_reset
```
**Symbols:**

```
ffffffff8174eb40-ffffffff8174eca9: __reset_control_get_from_lookup (STB_LOCAL)
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
In drivers/reset/core.c (ffffffff81732861)
Location: drivers/reset/core.c:896
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get
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
In drivers/reset/core.c (ffffffff817b3161)
Location: drivers/reset/core.c:896
Inline: True
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
In drivers/reset/core.c (ffffffff818eebcd)
Location: drivers/reset/core.c:897
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
In drivers/reset/core.c (ffffffff81a4683d)
Location: drivers/reset/core.c:897
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
In drivers/reset/core.c (ffffffff81a909dd)
Location: drivers/reset/core.c:897
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
In drivers/reset/core.c (ffffffff81ae344d)
Location: drivers/reset/core.c:900
Inline: True
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
In drivers/reset/core.c (ffff80001084c684)
Location: drivers/reset/core.c:684
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get
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
In drivers/reset/core.c (c09589a4)
Location: drivers/reset/core.c:684
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get
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
In drivers/reset/core.c (c0000000008ec0c4)
Location: drivers/reset/core.c:684
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get
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
In drivers/reset/core.c (ffffffe00052be86)
Location: drivers/reset/core.c:684
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get
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
In drivers/reset/core.c (ffffffff81647244)
Location: drivers/reset/core.c:684
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
In drivers/reset/core.c (ffffffff816276a4)
Location: drivers/reset/core.c:684
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
In drivers/reset/core.c (ffffffff81675604)
Location: drivers/reset/core.c:684
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
In drivers/reset/core.c (ffffffff8168fc64)
Location: drivers/reset/core.c:684
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
