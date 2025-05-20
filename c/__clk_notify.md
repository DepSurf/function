# Function: <code>__clk_notify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __clk_notify(struct clk_core *core, long unsigned int msg, long unsigned int old_rate, long unsigned int new_rate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816e4b60)
Location: drivers/clk/clk.c:905
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_recalc_rates
  - drivers/clk/clk.c:clk_propagate_rate_change
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:clk_change_rate
```
**Symbols:**

```
ffffffff816e4b60-ffffffff816e4bff: __clk_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __clk_notify(struct clk_core *core, long unsigned int msg, long unsigned int old_rate, long unsigned int new_rate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81749320)
Location: drivers/clk/clk.c:954
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_propagate_rate_change
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffff81749320-ffffffff817493bf: __clk_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __clk_notify(struct clk_core *core, long unsigned int msg, long unsigned int old_rate, long unsigned int new_rate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81531ba0)
Location: drivers/clk/clk.c:954
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_propagate_rate_change
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffff81531ba0-ffffffff81531c3f: __clk_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __clk_notify(struct clk_core *core, long unsigned int msg, long unsigned int old_rate, long unsigned int new_rate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81544cd0)
Location: drivers/clk/clk.c:954
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_propagate_rate_change
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffff81544cd0-ffffffff81544d74: __clk_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __clk_notify(struct clk_core *core, long unsigned int msg, long unsigned int old_rate, long unsigned int new_rate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815a80b0)
Location: drivers/clk/clk.c:1027
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_propagate_rate_change
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffff815a80b0-ffffffff815a8154: __clk_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __clk_notify(struct clk_core *core, long unsigned int msg, long unsigned int old_rate, long unsigned int new_rate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815dfeb0)
Location: drivers/clk/clk.c:1236
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_propagate_rate_change
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffff815dfeb0-ffffffff815dff54: __clk_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __clk_notify(struct clk_core *core, long unsigned int msg, long unsigned int old_rate, long unsigned int new_rate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815f9df0)
Location: drivers/clk/clk.c:1342
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_propagate_rate_change
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffff815f9df0-ffffffff815f9e94: __clk_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __clk_notify(struct clk_core *core, long unsigned int msg, long unsigned int old_rate, long unsigned int new_rate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8162c1b0)
Location: drivers/clk/clk.c:1460
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_propagate_rate_change
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffff8162c1b0-ffffffff8162c254: __clk_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __clk_notify(struct clk_core *core, long unsigned int msg, long unsigned int old_rate, long unsigned int new_rate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8164d720)
Location: drivers/clk/clk.c:1468
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_propagate_rate_change
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffff8164d720-ffffffff8164d7c4: __clk_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __clk_notify(struct clk_core *core, long unsigned int msg, long unsigned int old_rate, long unsigned int new_rate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816fc2f0)
Location: drivers/clk/clk.c:1472
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_propagate_rate_change
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffff816fc2f0-ffffffff816fc39b: __clk_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __clk_notify(struct clk_core *core, long unsigned int msg, long unsigned int old_rate, long unsigned int new_rate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff817191f0)
Location: drivers/clk/clk.c:1481
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_propagate_rate_change
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffff817191f0-ffffffff8171929b: __clk_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __clk_notify(struct clk_core *core, long unsigned int msg, long unsigned int old_rate, long unsigned int new_rate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816fa500)
Location: drivers/clk/clk.c:1502
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_propagate_rate_change
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffff816fa500-ffffffff816fa5a4: __clk_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __clk_notify(struct clk_core *core, long unsigned int msg, long unsigned int old_rate, long unsigned int new_rate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81774a40)
Location: drivers/clk/clk.c:1502
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_propagate_rate_change
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffff81774a40-ffffffff81774ae4: __clk_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __clk_notify(struct clk_core *core, long unsigned int msg, long unsigned int old_rate, long unsigned int new_rate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff818aa6f0)
Location: drivers/clk/clk.c:1516
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_propagate_rate_change
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffff818aa6f0-ffffffff818aa7a8: __clk_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __clk_notify(struct clk_core *core, long unsigned int msg, long unsigned int old_rate, long unsigned int new_rate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff819f5b80)
Location: drivers/clk/clk.c:1691
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_propagate_rate_change
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffff819f5b80-ffffffff819f5c38: __clk_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __clk_notify(struct clk_core *core, long unsigned int msg, long unsigned int old_rate, long unsigned int new_rate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a3e300)
Location: drivers/clk/clk.c:1736
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_propagate_rate_change
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffff81a3e300-ffffffff81a3e3b8: __clk_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __clk_notify(struct clk_core *core, long unsigned int msg, long unsigned int old_rate, long unsigned int new_rate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a89bf0)
Location: drivers/clk/clk.c:1736
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_propagate_rate_change
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffff81a89bf0-ffffffff81a89ca8: __clk_notify (STB_LOCAL)
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
int __clk_notify(struct clk_core *core, long unsigned int msg, long unsigned int old_rate, long unsigned int new_rate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107bc2f8)
Location: drivers/clk/clk.c:1468
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_propagate_rate_change
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffff8000107bc2f8-ffff8000107bc3bc: __clk_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __clk_notify(struct clk_core *core, long unsigned int msg, long unsigned int old_rate, long unsigned int new_rate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08e878c)
Location: drivers/clk/clk.c:1468
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_propagate_rate_change
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
c08e878c-c08e8848: __clk_notify (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __clk_notify(struct clk_core *core, long unsigned int msg, long unsigned int old_rate, long unsigned int new_rate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050b696)
Location: drivers/clk/clk.c:1468
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_propagate_rate_change
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffe00050b696-ffffffe00050b724: __clk_notify (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int __clk_notify(struct clk_core *core, long unsigned int msg, long unsigned int old_rate, long unsigned int new_rate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81613780)
Location: drivers/clk/clk.c:1468
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_propagate_rate_change
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffff81613780-ffffffff81613824: __clk_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __clk_notify(struct clk_core *core, long unsigned int msg, long unsigned int old_rate, long unsigned int new_rate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81607cb0)
Location: drivers/clk/clk.c:1468
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_propagate_rate_change
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffff81607cb0-ffffffff81607d54: __clk_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __clk_notify(struct clk_core *core, long unsigned int msg, long unsigned int old_rate, long unsigned int new_rate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81641560)
Location: drivers/clk/clk.c:1468
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_propagate_rate_change
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffff81641560-ffffffff81641604: __clk_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __clk_notify(struct clk_core *core, long unsigned int msg, long unsigned int old_rate, long unsigned int new_rate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8165b940)
Location: drivers/clk/clk.c:1468
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_propagate_rate_change
  - drivers/clk/clk.c:__clk_speculate_rates
  - drivers/clk/clk.c:__clk_recalc_rates
```
**Symbols:**

```
ffffffff8165b940-ffffffff8165b9e4: __clk_notify (STB_LOCAL)
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
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
