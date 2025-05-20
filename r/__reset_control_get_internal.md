# Function: <code>__reset_control_get_internal</code>

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
In drivers/reset/core.c (0)
Location: drivers/reset/core.c:279
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
In drivers/reset/core.c (0)
Location: drivers/reset/core.c:379
Inline: False
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
In drivers/reset/core.c (ffffffff8160ea56)
Location: drivers/reset/core.c:409
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_from_lookup
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
In drivers/reset/core.c (ffffffff8162b246)
Location: drivers/reset/core.c:409
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_from_lookup
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
In drivers/reset/core.c (ffffffff8165f1eb)
Location: drivers/reset/core.c:539
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
In drivers/reset/core.c (ffffffff816818ed)
Location: drivers/reset/core.c:538
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct reset_control *__reset_control_get_internal(struct reset_controller_dev *rcdev, unsigned int index, bool shared, bool acquired);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81732850)
Location: drivers/reset/core.c:539
Inline: False
Direct callers:
  - drivers/reset/core.c:__reset_control_get_from_lookup
```
**Symbols:**

```
ffffffff81732850-ffffffff81732979: __reset_control_get_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct reset_control *__reset_control_get_internal(struct reset_controller_dev *rcdev, unsigned int index, bool shared, bool acquired);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8174ea10)
Location: drivers/reset/core.c:613
Inline: False
Direct callers:
  - drivers/reset/core.c:__reset_control_get_from_lookup
```
**Symbols:**

```
ffffffff8174ea10-ffffffff8174eb39: __reset_control_get_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct reset_control *__reset_control_get_internal(struct reset_controller_dev *rcdev, unsigned int index, bool shared, bool acquired);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81732690)
Location: drivers/reset/core.c:747
Inline: False
Direct callers:
  - drivers/reset/core.c:__reset_control_get
```
**Symbols:**

```
ffffffff81732690-ffffffff817327d2: __reset_control_get_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct reset_control *__reset_control_get_internal(struct reset_controller_dev *rcdev, unsigned int index, bool shared, bool acquired);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (0)
Location: drivers/reset/core.c:748
Inline: False
```
**Symbols:**

```
ffffffff817b2f80-ffffffff817b30d2: __reset_control_get_internal (STB_LOCAL)
ffffffff81cf85ff-ffffffff81cf8657: __reset_control_get_internal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct reset_control *__reset_control_get_internal(struct reset_controller_dev *rcdev, unsigned int index, bool shared, bool acquired);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (0)
Location: drivers/reset/core.c:749
Inline: False
```
**Symbols:**

```
ffffffff818ee9d0-ffffffff818eeb26: __reset_control_get_internal (STB_LOCAL)
ffffffff81ec06fc-ffffffff81ec0752: __reset_control_get_internal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct reset_control *__reset_control_get_internal(struct reset_controller_dev *rcdev, unsigned int index, bool shared, bool acquired);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (0)
Location: drivers/reset/core.c:749
Inline: False
```
**Symbols:**

```
ffffffff81a46630-ffffffff81a46786: __reset_control_get_internal (STB_LOCAL)
ffffffff82094e62-ffffffff82094eb8: __reset_control_get_internal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct reset_control *__reset_control_get_internal(struct reset_controller_dev *rcdev, unsigned int index, bool shared, bool acquired);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (0)
Location: drivers/reset/core.c:749
Inline: False
```
**Symbols:**

```
ffffffff81a907e0-ffffffff81a9092e: __reset_control_get_internal (STB_LOCAL)
ffffffff82115c87-ffffffff82115cdd: __reset_control_get_internal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct reset_control *__reset_control_get_internal(struct reset_controller_dev *rcdev, unsigned int index, bool shared, bool acquired);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (0)
Location: drivers/reset/core.c:749
Inline: False
```
**Symbols:**

```
ffffffff81ae3220-ffffffff81ae33a0: __reset_control_get_internal (STB_LOCAL)
ffffffff821f398d-ffffffff821f39e3: __reset_control_get_internal.cold (STB_LOCAL)
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
struct reset_control *__reset_control_get_internal(struct reset_controller_dev *rcdev, unsigned int index, bool shared, bool acquired);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffff80001084c320)
Location: drivers/reset/core.c:538
Inline: False
Direct callers:
  - drivers/reset/core.c:__reset_control_get
  - drivers/reset/core.c:__of_reset_control_get
```
**Symbols:**

```
ffff80001084c320-ffff80001084c438: __reset_control_get_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct reset_control *__reset_control_get_internal(struct reset_controller_dev *rcdev, unsigned int index, bool shared, bool acquired);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (c0958674)
Location: drivers/reset/core.c:538
Inline: False
Direct callers:
  - drivers/reset/core.c:__reset_control_get
  - drivers/reset/core.c:__of_reset_control_get
```
**Symbols:**

```
c0958674-c0958778: __reset_control_get_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct reset_control *__reset_control_get_internal(struct reset_controller_dev *rcdev, unsigned int index, bool shared, bool acquired);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (c0000000008eb860)
Location: drivers/reset/core.c:538
Inline: False
Direct callers:
  - drivers/reset/core.c:__reset_control_get
  - drivers/reset/core.c:__of_reset_control_get
```
**Symbols:**

```
c0000000008eb860-c0000000008eba40: __reset_control_get_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct reset_control *__reset_control_get_internal(struct reset_controller_dev *rcdev, unsigned int index, bool shared, bool acquired);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffe00052bc08)
Location: drivers/reset/core.c:538
Inline: False
Direct callers:
  - drivers/reset/core.c:__reset_control_get
  - drivers/reset/core.c:__of_reset_control_get
```
**Symbols:**

```
ffffffe00052bc08-ffffffe00052bce0: __reset_control_get_internal (STB_LOCAL)
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
In drivers/reset/core.c (ffffffff8164736d)
Location: drivers/reset/core.c:538
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
In drivers/reset/core.c (ffffffff816277cd)
Location: drivers/reset/core.c:538
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
In drivers/reset/core.c (ffffffff8167572d)
Location: drivers/reset/core.c:538
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
In drivers/reset/core.c (ffffffff8168fd8d)
Location: drivers/reset/core.c:538
Inline: True
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
<b>Arch</b>
<ul>
</ul>
