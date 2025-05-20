# Function: <code>opp_debug_remove_one</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void opp_debug_remove_one(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (ffffffff817d6200)
Location: drivers/opp/debugfs.c:33
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_put
```
**Symbols:**

```
ffffffff817d6200-ffffffff817d6214: opp_debug_remove_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void opp_debug_remove_one(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (ffffffff8181eee0)
Location: drivers/opp/debugfs.c:33
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_put
```
**Symbols:**

```
ffffffff8181eee0-ffffffff8181eef4: opp_debug_remove_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void opp_debug_remove_one(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (ffffffff8184ad80)
Location: drivers/opp/debugfs.c:33
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_kref_release
```
**Symbols:**

```
ffffffff8184ad80-ffffffff8184ad94: opp_debug_remove_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void opp_debug_remove_one(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (ffffffff8188df10)
Location: drivers/opp/debugfs.c:30
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_kref_release
```
**Symbols:**

```
ffffffff8188df10-ffffffff8188df24: opp_debug_remove_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void opp_debug_remove_one(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (ffffffff818c00a0)
Location: drivers/opp/debugfs.c:30
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_kref_release
```
**Symbols:**

```
ffffffff818c00a0-ffffffff818c00b4: opp_debug_remove_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void opp_debug_remove_one(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (ffffffff81992150)
Location: drivers/opp/debugfs.c:30
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:_opp_remove_all_static
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff81992150-ffffffff81992164: opp_debug_remove_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void opp_debug_remove_one(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (ffffffff819953e0)
Location: drivers/opp/debugfs.c:30
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff819953e0-ffffffff819953f4: opp_debug_remove_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void opp_debug_remove_one(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (ffffffff8197a050)
Location: drivers/opp/debugfs.c:30
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_set_opp
```
**Symbols:**

```
ffffffff8197a050-ffffffff8197a064: opp_debug_remove_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void opp_debug_remove_one(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (ffffffff81a23060)
Location: drivers/opp/debugfs.c:30
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_set_opp
```
**Symbols:**

```
ffffffff81a23060-ffffffff81a23074: opp_debug_remove_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void opp_debug_remove_one(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (ffffffff81b8c210)
Location: drivers/opp/debugfs.c:31
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_set_opp
```
**Symbols:**

```
ffffffff81b8c210-ffffffff81b8c22a: opp_debug_remove_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void opp_debug_remove_one(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (ffffffff81d2bb10)
Location: drivers/opp/debugfs.c:31
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_set_opp
```
**Symbols:**

```
ffffffff81d2bb10-ffffffff81d2bb2a: opp_debug_remove_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void opp_debug_remove_one(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (ffffffff81d94dc0)
Location: drivers/opp/debugfs.c:31
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_set_opp
```
**Symbols:**

```
ffffffff81d94dc0-ffffffff81d94dda: opp_debug_remove_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void opp_debug_remove_one(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (ffffffff81e4c8d0)
Location: drivers/opp/debugfs.c:31
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_remove_all
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:_opp_table_kref_release
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:dev_pm_opp_find_level_ceil
```
**Symbols:**

```
ffffffff81e4c8d0-ffffffff81e4c8ea: opp_debug_remove_one (STB_GLOBAL)
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
void opp_debug_remove_one(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (ffff800010b1c990)
Location: drivers/opp/debugfs.c:30
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_kref_release
```
**Symbols:**

```
ffff800010b1c990-ffff800010b1c9bc: opp_debug_remove_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void opp_debug_remove_one(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (c0bf7144)
Location: drivers/opp/debugfs.c:30
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_kref_release
```
**Symbols:**

```
c0bf7144-c0bf7164: opp_debug_remove_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void opp_debug_remove_one(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (c000000000c0f290)
Location: drivers/opp/debugfs.c:30
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_kref_release
```
**Symbols:**

```
c000000000c0f290-c000000000c0f2c8: opp_debug_remove_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void opp_debug_remove_one(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (ffffffe000704942)
Location: drivers/opp/debugfs.c:30
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_kref_release
```
**Symbols:**

```
ffffffe000704942-ffffffe00070496c: opp_debug_remove_one (STB_GLOBAL)
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
void opp_debug_remove_one(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (ffffffff818647c0)
Location: drivers/opp/debugfs.c:30
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_kref_release
```
**Symbols:**

```
ffffffff818647c0-ffffffff818647d4: opp_debug_remove_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void opp_debug_remove_one(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (ffffffff8182d470)
Location: drivers/opp/debugfs.c:30
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_kref_release
```
**Symbols:**

```
ffffffff8182d470-ffffffff8182d484: opp_debug_remove_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void opp_debug_remove_one(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (ffffffff818b5550)
Location: drivers/opp/debugfs.c:30
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_kref_release
```
**Symbols:**

```
ffffffff818b5550-ffffffff818b5564: opp_debug_remove_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void opp_debug_remove_one(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (ffffffff818d1800)
Location: drivers/opp/debugfs.c:30
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_kref_release
```
**Symbols:**

```
ffffffff818d1800-ffffffff818d1814: opp_debug_remove_one (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
