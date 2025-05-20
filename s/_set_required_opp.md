# Function: <code>_set_required_opp</code>

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
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int _set_required_opp(struct device *dev, struct device *pd_dev, struct dev_pm_opp *opp, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:782
Inline: False
Direct callers:
  - drivers/opp/core.c:_set_required_opps
  - drivers/opp/core.c:_set_required_opps
  - drivers/opp/core.c:_set_required_opps
```
**Symbols:**

```
ffffffff81991670-ffffffff819916c6: _set_required_opp (STB_LOCAL)
ffffffff81c28ede-ffffffff81c28f0c: _set_required_opp.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int _set_required_opp(struct device *dev, struct device *pd_dev, struct dev_pm_opp *opp, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:866
Inline: False
Direct callers:
  - drivers/opp/core.c:_set_required_opps
  - drivers/opp/core.c:_set_required_opps
  - drivers/opp/core.c:_set_required_opps
```
**Symbols:**

```
ffffffff81975c40-ffffffff81975c96: _set_required_opp (STB_LOCAL)
ffffffff81c1b0e2-ffffffff81c1b110: _set_required_opp.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int _set_required_opp(struct device *dev, struct device *pd_dev, struct dev_pm_opp *opp, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:866
Inline: False
Direct callers:
  - drivers/opp/core.c:_set_required_opps
  - drivers/opp/core.c:_set_required_opps
  - drivers/opp/core.c:_set_required_opps
```
**Symbols:**

```
ffffffff81a1e8f0-ffffffff81a1e946: _set_required_opp (STB_LOCAL)
ffffffff81d2b042-ffffffff81d2b070: _set_required_opp.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int _set_required_opp(struct device *dev, struct device *pd_dev, struct dev_pm_opp *opp, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1011
Inline: False
Direct callers:
  - drivers/opp/core.c:_set_required_opps
  - drivers/opp/core.c:_set_required_opps
  - drivers/opp/core.c:_set_required_opps
```
**Symbols:**

```
ffffffff81b87290-ffffffff81b872f5: _set_required_opp (STB_LOCAL)
ffffffff81ef7234-ffffffff81ef7264: _set_required_opp.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int _set_required_opp(struct device *dev, struct device *pd_dev, struct dev_pm_opp *opp, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d26a20)
Location: drivers/opp/core.c:938
Inline: False
Direct callers:
  - drivers/opp/core.c:_set_required_opps
  - drivers/opp/core.c:_set_required_opps
  - drivers/opp/core.c:_set_required_opps
```
**Symbols:**

```
ffffffff81d26a20-ffffffff81d26ac8: _set_required_opp (STB_LOCAL)
```
</details>
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
</ul>
