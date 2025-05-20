# Function: <code>pm_clk_list_unlock</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pm_clk_list_unlock(struct pm_subsys_data *psd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/clock_ops.c (ffffffff817cca60)
Location: drivers/base/power/clock_ops.c:64
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_destroy
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
```
**Symbols:**

```
ffffffff817cca60-ffffffff817cca82: pm_clk_list_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pm_clk_list_unlock(struct pm_subsys_data *psd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/clock_ops.c (ffffffff818571d0)
Location: drivers/base/power/clock_ops.c:64
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_destroy
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
```
**Symbols:**

```
ffffffff818571d0-ffffffff818571f2: pm_clk_list_unlock (STB_LOCAL)
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
In drivers/base/power/clock_ops.c (ffffffff8199d81c)
Location: drivers/base/power/clock_ops.c:64
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_destroy
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
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
In drivers/base/power/clock_ops.c (ffffffff81b0ef4c)
Location: drivers/base/power/clock_ops.c:64
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_destroy
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
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
In drivers/base/power/clock_ops.c (ffffffff81b5cffc)
Location: drivers/base/power/clock_ops.c:64
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_destroy
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
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
In drivers/base/power/clock_ops.c (ffffffff81bb08ac)
Location: drivers/base/power/clock_ops.c:64
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_destroy
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
