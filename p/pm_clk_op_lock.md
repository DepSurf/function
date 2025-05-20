# Function: <code>pm_clk_op_lock</code>

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
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pm_clk_op_lock(struct pm_subsys_data *psd, long unsigned int *flags, const char *fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/clock_ops.c (0)
Location: drivers/base/power/clock_ops.c:86
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:pm_clk_suspend
```
**Symbols:**

```
ffffffff817cce20-ffffffff817cceba: pm_clk_op_lock (STB_LOCAL)
ffffffff81c0122c-ffffffff81c01254: pm_clk_op_lock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pm_clk_op_lock(struct pm_subsys_data *psd, long unsigned int *flags, const char *fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/clock_ops.c (0)
Location: drivers/base/power/clock_ops.c:86
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:pm_clk_suspend
```
**Symbols:**

```
ffffffff81857400-ffffffff8185749a: pm_clk_op_lock (STB_LOCAL)
ffffffff81d04145-ffffffff81d0416d: pm_clk_op_lock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pm_clk_op_lock(struct pm_subsys_data *psd, long unsigned int *flags, const char *fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/clock_ops.c (0)
Location: drivers/base/power/clock_ops.c:86
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:pm_clk_suspend
```
**Symbols:**

```
ffffffff8199d8d0-ffffffff8199d96f: pm_clk_op_lock (STB_LOCAL)
ffffffff81ecca67-ffffffff81ecca8f: pm_clk_op_lock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pm_clk_op_lock(struct pm_subsys_data *psd, long unsigned int *flags, const char *fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/clock_ops.c (ffffffff81b0f020)
Location: drivers/base/power/clock_ops.c:86
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:pm_clk_suspend
```
**Symbols:**

```
ffffffff81b0f020-ffffffff81b0f0e4: pm_clk_op_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pm_clk_op_lock(struct pm_subsys_data *psd, long unsigned int *flags, const char *fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/clock_ops.c (ffffffff81b5d0d0)
Location: drivers/base/power/clock_ops.c:86
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:pm_clk_suspend
```
**Symbols:**

```
ffffffff81b5d0d0-ffffffff81b5d1aa: pm_clk_op_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pm_clk_op_lock(struct pm_subsys_data *psd, long unsigned int *flags, const char *fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/clock_ops.c (ffffffff81bb0980)
Location: drivers/base/power/clock_ops.c:86
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:pm_clk_suspend
```
**Symbols:**

```
ffffffff81bb0980-ffffffff81bb0a5a: pm_clk_op_lock (STB_LOCAL)
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
