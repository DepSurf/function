# Function: <code>i2c_dw_set_timings_master</code>

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
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81801f25)
Location: drivers/i2c/busses/i2c-designware-master.c:35
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
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
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81843755)
Location: drivers/i2c/busses/i2c-designware-master.c:35
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
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
In drivers/i2c/busses/i2c-designware-master.c (ffffffff818750d5)
Location: drivers/i2c/busses/i2c-designware-master.c:35
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int i2c_dw_set_timings_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: drivers/i2c/busses/i2c-designware-master.c:36
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
**Symbols:**

```
ffffffff81949460-ffffffff819497b9: i2c_dw_set_timings_master (STB_LOCAL)
ffffffff81949f5d-ffffffff81949f8d: i2c_dw_set_timings_master.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int i2c_dw_set_timings_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: drivers/i2c/busses/i2c-designware-master.c:36
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
**Symbols:**

```
ffffffff8194f020-ffffffff8194f379: i2c_dw_set_timings_master (STB_LOCAL)
ffffffff81c25016-ffffffff81c25046: i2c_dw_set_timings_master.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int i2c_dw_set_timings_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: drivers/i2c/busses/i2c-designware-master.c:40
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
**Symbols:**

```
ffffffff81932c30-ffffffff81932f6d: i2c_dw_set_timings_master (STB_LOCAL)
ffffffff81c17098-ffffffff81c170d2: i2c_dw_set_timings_master.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int i2c_dw_set_timings_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: drivers/i2c/busses/i2c-designware-master.c:40
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
**Symbols:**

```
ffffffff819d5fe0-ffffffff819d631a: i2c_dw_set_timings_master (STB_LOCAL)
ffffffff81d25d2d-ffffffff81d25d67: i2c_dw_set_timings_master.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int i2c_dw_set_timings_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: drivers/i2c/busses/i2c-designware-master.c:40
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
**Symbols:**

```
ffffffff81b38b20-ffffffff81b38e6d: i2c_dw_set_timings_master (STB_LOCAL)
ffffffff81ef1ab8-ffffffff81ef1af0: i2c_dw_set_timings_master.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int i2c_dw_set_timings_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81cce440)
Location: drivers/i2c/busses/i2c-designware-master.c:40
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
**Symbols:**

```
ffffffff81cce440-ffffffff81cce7be: i2c_dw_set_timings_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int i2c_dw_set_timings_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81d36210)
Location: drivers/i2c/busses/i2c-designware-master.c:40
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
**Symbols:**

```
ffffffff81d36210-ffffffff81d36588: i2c_dw_set_timings_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int i2c_dw_set_timings_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81debfd0)
Location: drivers/i2c/busses/i2c-designware-master.c:41
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
**Symbols:**

```
ffffffff81debfd0-ffffffff81dec348: i2c_dw_set_timings_master (STB_LOCAL)
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
In drivers/i2c/busses/i2c-designware-master.c (ffff800010ab9e90)
Location: drivers/i2c/busses/i2c-designware-master.c:35
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
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
In drivers/i2c/busses/i2c-designware-master.c (c0b9953c)
Location: drivers/i2c/busses/i2c-designware-master.c:35
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
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
In drivers/i2c/busses/i2c-designware-master.c (c000000000b9ce10)
Location: drivers/i2c/busses/i2c-designware-master.c:35
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
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
In drivers/i2c/busses/i2c-designware-master.c (ffffffe0006be7ae)
Location: drivers/i2c/busses/i2c-designware-master.c:35
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
</details>
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
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8186a585)
Location: drivers/i2c/busses/i2c-designware-master.c:35
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
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
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81884515)
Location: drivers/i2c/busses/i2c-designware-master.c:35
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
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
