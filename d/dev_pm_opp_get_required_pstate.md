# Function: <code>dev_pm_opp_get_required_pstate</code>

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
unsigned int dev_pm_opp_get_required_pstate(struct dev_pm_opp *opp, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:161
Inline: False
```
**Symbols:**

```
ffffffff81c1b099-ffffffff81c1b0b4: dev_pm_opp_get_required_pstate.cold (STB_LOCAL)
ffffffff81975b10-ffffffff81975b65: dev_pm_opp_get_required_pstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
unsigned int dev_pm_opp_get_required_pstate(struct dev_pm_opp *opp, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:161
Inline: False
```
**Symbols:**

```
ffffffff81d2b0ba-ffffffff81d2b0e9: dev_pm_opp_get_required_pstate.cold (STB_LOCAL)
ffffffff81a1e9f0-ffffffff81a1ea6e: dev_pm_opp_get_required_pstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
unsigned int dev_pm_opp_get_required_pstate(struct dev_pm_opp *opp, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:186
Inline: False
```
**Symbols:**

```
ffffffff81ef7264-ffffffff81ef7291: dev_pm_opp_get_required_pstate.cold (STB_LOCAL)
ffffffff81b87300-ffffffff81b87390: dev_pm_opp_get_required_pstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
unsigned int dev_pm_opp_get_required_pstate(struct dev_pm_opp *opp, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:230
Inline: False
```
**Symbols:**

```
ffffffff820a898d-ffffffff820a89a2: dev_pm_opp_get_required_pstate.cold (STB_LOCAL)
ffffffff81d26ae0-ffffffff81d26b67: dev_pm_opp_get_required_pstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
unsigned int dev_pm_opp_get_required_pstate(struct dev_pm_opp *opp, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:227
Inline: False
```
**Symbols:**

```
ffffffff82129b86-ffffffff82129bb0: dev_pm_opp_get_required_pstate.cold (STB_LOCAL)
ffffffff81d8fe60-ffffffff81d8ff20: dev_pm_opp_get_required_pstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
unsigned int dev_pm_opp_get_required_pstate(struct dev_pm_opp *opp, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:226
Inline: False
```
**Symbols:**

```
ffffffff8220b8cf-ffffffff8220b8f9: dev_pm_opp_get_required_pstate.cold (STB_LOCAL)
ffffffff81e474f0-ffffffff81e475b0: dev_pm_opp_get_required_pstate (STB_GLOBAL)
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
