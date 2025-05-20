# Function: <code>suspend_set_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int suspend_set_state(struct regulator_dev *rdev, struct regulator_state *rstate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff814d7e20)
Location: drivers/regulator/core.c:757
Inline: False
Direct callers:
  - drivers/regulator/core.c:suspend_prepare
  - drivers/regulator/core.c:suspend_prepare
  - drivers/regulator/core.c:suspend_prepare
```
**Symbols:**

```
ffffffff814d7e20-ffffffff814d804c: suspend_set_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int suspend_set_state(struct regulator_dev *rdev, struct regulator_state *rstate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81528d60)
Location: drivers/regulator/core.c:732
Inline: False
Direct callers:
  - drivers/regulator/core.c:suspend_prepare
  - drivers/regulator/core.c:suspend_prepare
  - drivers/regulator/core.c:suspend_prepare
```
**Symbols:**

```
ffffffff81528d60-ffffffff81528f81: suspend_set_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int suspend_set_state(struct regulator_dev *rdev, struct regulator_state *rstate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81555210)
Location: drivers/regulator/core.c:733
Inline: False
Direct callers:
  - drivers/regulator/core.c:suspend_prepare
  - drivers/regulator/core.c:suspend_prepare
  - drivers/regulator/core.c:suspend_prepare
```
**Symbols:**

```
ffffffff81555210-ffffffff81555431: suspend_set_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int suspend_set_state(struct regulator_dev *rdev, struct regulator_state *rstate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815697a0)
Location: drivers/regulator/core.c:733
Inline: False
Direct callers:
  - drivers/regulator/core.c:suspend_prepare
  - drivers/regulator/core.c:suspend_prepare
  - drivers/regulator/core.c:suspend_prepare
```
**Symbols:**

```
ffffffff815697a0-ffffffff815699ca: suspend_set_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int suspend_set_state(struct regulator_dev *rdev, struct regulator_state *rstate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815cd970)
Location: drivers/regulator/core.c:733
Inline: False
Direct callers:
  - drivers/regulator/core.c:suspend_prepare
  - drivers/regulator/core.c:suspend_prepare
  - drivers/regulator/core.c:suspend_prepare
```
**Symbols:**

```
ffffffff815cd970-ffffffff815cdba3: suspend_set_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int suspend_set_state(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:803
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_suspend_late
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81606110-ffffffff81606254: suspend_set_state (STB_LOCAL)
ffffffff8160c422-ffffffff8160c506: suspend_set_state.cold.43 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int suspend_set_state(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:996
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81621400-ffffffff81621544: suspend_set_state (STB_LOCAL)
ffffffff81628b02-ffffffff81628be6: suspend_set_state.cold.49 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int suspend_set_state(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:978
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81656070-ffffffff8165625f: suspend_set_state (STB_LOCAL)
ffffffff8165ccc6-ffffffff8165cd0d: suspend_set_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int suspend_set_state(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:984
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff816785a0-ffffffff8167878a: suspend_set_state (STB_LOCAL)
ffffffff8167f3f6-ffffffff8167f43d: suspend_set_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int suspend_set_state(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:987
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff8172bfe0-ffffffff8172c13c: suspend_set_state (STB_LOCAL)
ffffffff817302dc-ffffffff8173034f: suspend_set_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int suspend_set_state(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff800010841280)
Location: drivers/regulator/core.c:984
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffff800010841280-ffff800010841488: suspend_set_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int suspend_set_state(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c094a8e0)
Location: drivers/regulator/core.c:984
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
c094a8e0-c094aae4: suspend_set_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int suspend_set_state(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008db750)
Location: drivers/regulator/core.c:984
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
c0000000008db750-c0000000008dba18: suspend_set_state (STB_LOCAL)
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
In drivers/regulator/core.c (ffffffe00052797e)
Location: drivers/regulator/core.c:984
Inline: True
Inline callers:
  - drivers/regulator/core.c:set_machine_constraints
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
In drivers/regulator/core.c (ffffffff816430a7)
Location: drivers/regulator/core.c:984
Inline: True
Inline callers:
  - drivers/regulator/core.c:set_machine_constraints
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int suspend_set_state(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:984
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff8161e480-ffffffff8161e66a: suspend_set_state (STB_LOCAL)
ffffffff816252d6-ffffffff8162531d: suspend_set_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int suspend_set_state(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:984
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff8166c3e0-ffffffff8166c5ca: suspend_set_state (STB_LOCAL)
ffffffff81673236-ffffffff8167327d: suspend_set_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int suspend_set_state(struct regulator_dev *rdev, suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/core.c (0)
Location: drivers/regulator/core.c:984
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81686a10-ffffffff81686bfa: suspend_set_state (STB_LOCAL)
ffffffff8168d896-ffffffff8168d8dd: suspend_set_state.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>suspend_state_t state</code>
</li>
<li>
<b>Param removed. </b>
<code>struct regulator_state *rstate</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
