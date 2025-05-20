# Function: <code>_regulator_get_current_limit_unlocked</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8162288d)
Location: drivers/regulator/core.c:4066
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:_regulator_get_current_limit
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
In drivers/regulator/core.c (ffffffff8165c895)
Location: drivers/regulator/core.c:4086
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:_regulator_get_current_limit
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
In drivers/regulator/core.c (ffffffff816794c5)
Location: drivers/regulator/core.c:4096
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:_regulator_get_current_limit
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
In drivers/regulator/core.c (ffffffff81729767)
Location: drivers/regulator/core.c:4136
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_get_current_limit
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:regulator_uA_show
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
In drivers/regulator/core.c (ffffffff81746277)
Location: drivers/regulator/core.c:4274
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_get_current_limit
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:regulator_uA_show
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
In drivers/regulator/core.c (ffffffff81729d67)
Location: drivers/regulator/core.c:4276
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_get_current_limit
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:regulator_uA_show
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
In drivers/regulator/core.c (ffffffff817a96b4)
Location: drivers/regulator/core.c:4399
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_get_current_limit
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:microamps_show
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
In drivers/regulator/core.c (ffffffff818e55de)
Location: drivers/regulator/core.c:4444
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_get_current_limit
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:microamps_show
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
In drivers/regulator/core.c (ffffffff81a3d50e)
Location: drivers/regulator/core.c:4474
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_get_current_limit
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:microamps_show
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
In drivers/regulator/core.c (ffffffff81a87672)
Location: drivers/regulator/core.c:4540
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_get_current_limit
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:microamps_show
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
In drivers/regulator/core.c (ffffffff81ad9d62)
Location: drivers/regulator/core.c:4546
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:regulator_get_current_limit
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:microamps_show
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
In drivers/regulator/core.c (ffff800010841b48)
Location: drivers/regulator/core.c:4096
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:_regulator_get_current_limit
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
In drivers/regulator/core.c (c094bc0c)
Location: drivers/regulator/core.c:4096
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:_regulator_get_current_limit
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
In drivers/regulator/core.c (c0000000008dca98)
Location: drivers/regulator/core.c:4096
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:_regulator_get_current_limit
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
In drivers/regulator/core.c (ffffffe000523b60)
Location: drivers/regulator/core.c:4096
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:_regulator_get_current_limit
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
In drivers/regulator/core.c (ffffffff8163efc5)
Location: drivers/regulator/core.c:4096
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:_regulator_get_current_limit
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
In drivers/regulator/core.c (ffffffff8161f3a5)
Location: drivers/regulator/core.c:4096
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:_regulator_get_current_limit
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
In drivers/regulator/core.c (ffffffff8166d305)
Location: drivers/regulator/core.c:4096
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:_regulator_get_current_limit
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
In drivers/regulator/core.c (ffffffff81687965)
Location: drivers/regulator/core.c:4096
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show_subtree
  - drivers/regulator/core.c:_regulator_get_current_limit
```
</details>
</li>
</ul>

## Differences
