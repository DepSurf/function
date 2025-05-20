# Function: <code>ps_get_cur_charge_cntl_limit</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
int ps_get_cur_charge_cntl_limit(struct thermal_cooling_device *tcd, long unsigned int *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff8184e530)
Location: drivers/power/supply/power_supply_core.c:911
Inline: False
```
**Symbols:**

```
ffffffff8184e530-ffffffff8184e5a6: ps_get_cur_charge_cntl_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ps_get_cur_charge_cntl_limit(struct thermal_cooling_device *tcd, long unsigned int *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff8187ff70)
Location: drivers/power/supply/power_supply_core.c:911
Inline: False
```
**Symbols:**

```
ffffffff8187ff70-ffffffff8187ffe6: ps_get_cur_charge_cntl_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ps_get_cur_charge_cntl_limit(struct thermal_cooling_device *tcd, long unsigned int *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff8194ef70)
Location: drivers/power/supply/power_supply_core.c:984
Inline: False
```
**Symbols:**

```
ffffffff8194ef70-ffffffff8194efec: ps_get_cur_charge_cntl_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ps_get_cur_charge_cntl_limit(struct thermal_cooling_device *tcd, long unsigned int *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81954950)
Location: drivers/power/supply/power_supply_core.c:1008
Inline: False
```
**Symbols:**

```
ffffffff81954950-ffffffff819549cc: ps_get_cur_charge_cntl_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ps_get_cur_charge_cntl_limit(struct thermal_cooling_device *tcd, long unsigned int *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81938840)
Location: drivers/power/supply/power_supply_core.c:1008
Inline: False
```
**Symbols:**

```
ffffffff81938840-ffffffff819388bc: ps_get_cur_charge_cntl_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ps_get_cur_charge_cntl_limit(struct thermal_cooling_device *tcd, long unsigned int *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (0)
Location: drivers/power/supply/power_supply_core.c:1031
Inline: False
```
**Symbols:**

```
ffffffff819dcd20-ffffffff819dcdab: ps_get_cur_charge_cntl_limit (STB_LOCAL)
ffffffff81d26390-ffffffff81d263a4: ps_get_cur_charge_cntl_limit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ps_get_cur_charge_cntl_limit(struct thermal_cooling_device *tcd, long unsigned int *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_core.c (0)
Location: drivers/power/supply/power_supply_core.c:1204
Inline: False
```
**Symbols:**

```
ffffffff81b41120-ffffffff81b411bd: ps_get_cur_charge_cntl_limit (STB_LOCAL)
ffffffff81ef21d0-ffffffff81ef21e4: ps_get_cur_charge_cntl_limit.cold (STB_LOCAL)
```
</details>
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
int ps_get_cur_charge_cntl_limit(struct thermal_cooling_device *tcd, long unsigned int *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffff800010acb8f8)
Location: drivers/power/supply/power_supply_core.c:911
Inline: False
```
**Symbols:**

```
ffff800010acb8f8-ffff800010acb990: ps_get_cur_charge_cntl_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ps_get_cur_charge_cntl_limit(struct thermal_cooling_device *tcd, long unsigned int *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (c0bac928)
Location: drivers/power/supply/power_supply_core.c:911
Inline: False
```
**Symbols:**

```
c0bac928-c0bac9b8: ps_get_cur_charge_cntl_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ps_get_cur_charge_cntl_limit(struct thermal_cooling_device *tcd, long unsigned int *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (c000000000badf00)
Location: drivers/power/supply/power_supply_core.c:911
Inline: False
```
**Symbols:**

```
c000000000badf00-c000000000badfcc: ps_get_cur_charge_cntl_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ps_get_cur_charge_cntl_limit(struct thermal_cooling_device *tcd, long unsigned int *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffe0006c9330)
Location: drivers/power/supply/power_supply_core.c:911
Inline: False
```
**Symbols:**

```
ffffffe0006c9330-ffffffe0006c9394: ps_get_cur_charge_cntl_limit (STB_LOCAL)
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
int ps_get_cur_charge_cntl_limit(struct thermal_cooling_device *tcd, long unsigned int *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff818284e0)
Location: drivers/power/supply/power_supply_core.c:911
Inline: False
```
**Symbols:**

```
ffffffff818284e0-ffffffff81828556: ps_get_cur_charge_cntl_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ps_get_cur_charge_cntl_limit(struct thermal_cooling_device *tcd, long unsigned int *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff817efb70)
Location: drivers/power/supply/power_supply_core.c:911
Inline: False
```
**Symbols:**

```
ffffffff817efb70-ffffffff817efbe6: ps_get_cur_charge_cntl_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ps_get_cur_charge_cntl_limit(struct thermal_cooling_device *tcd, long unsigned int *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81875420)
Location: drivers/power/supply/power_supply_core.c:911
Inline: False
```
**Symbols:**

```
ffffffff81875420-ffffffff81875496: ps_get_cur_charge_cntl_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ps_get_cur_charge_cntl_limit(struct thermal_cooling_device *tcd, long unsigned int *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81890dc0)
Location: drivers/power/supply/power_supply_core.c:911
Inline: False
```
**Symbols:**

```
ffffffff81890dc0-ffffffff81890e36: ps_get_cur_charge_cntl_limit (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
