# Function: <code>__dtpm_rebalance_weight</code>

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
void __dtpm_rebalance_weight(struct dtpm *dtpm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/powercap/dtpm.c (ffffffff819ba6a0)
Location: drivers/powercap/dtpm.c:93
Inline: False
Direct callers:
  - drivers/powercap/dtpm.c:__dtpm_add_power
  - drivers/powercap/dtpm.c:__dtpm_sub_power
  - drivers/powercap/dtpm.c:__dtpm_rebalance_weight
```
**Symbols:**

```
ffffffff819ba6a0-ffffffff819ba737: __dtpm_rebalance_weight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __dtpm_rebalance_weight(struct dtpm *dtpm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/powercap/dtpm.c (ffffffff81a697b0)
Location: drivers/powercap/dtpm.c:93
Inline: False
Direct callers:
  - drivers/powercap/dtpm.c:__dtpm_add_power
  - drivers/powercap/dtpm.c:__dtpm_sub_power
  - drivers/powercap/dtpm.c:__dtpm_rebalance_weight
```
**Symbols:**

```
ffffffff81a697b0-ffffffff81a69844: __dtpm_rebalance_weight (STB_LOCAL)
```
</details>
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
