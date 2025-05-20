# Function: <code>powercap_register_zone</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct powercap_zone *powercap_register_zone(struct powercap_zone *power_zone, struct powercap_control_type *control_type, const char *name, struct powercap_zone *parent, const struct powercap_zone_ops *ops, int nr_constraints, struct powercap_zone_constraint_ops *const_ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/powercap/powercap_sys.c (ffffffff816f2860)
Location: drivers/powercap/powercap_sys.c:494
Inline: True
```
**Symbols:**

```
ffffffff816f2860-ffffffff816f2e4f: powercap_register_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct powercap_zone *powercap_register_zone(struct powercap_zone *power_zone, struct powercap_control_type *control_type, const char *name, struct powercap_zone *parent, const struct powercap_zone_ops *ops, int nr_constraints, const struct powercap_zone_constraint_ops *const_ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/powercap/powercap_sys.c (ffffffff81757880)
Location: drivers/powercap/powercap_sys.c:494
Inline: True
```
**Symbols:**

```
ffffffff81757880-ffffffff81757e73: powercap_register_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct powercap_zone *powercap_register_zone(struct powercap_zone *power_zone, struct powercap_control_type *control_type, const char *name, struct powercap_zone *parent, const struct powercap_zone_ops *ops, int nr_constraints, const struct powercap_zone_constraint_ops *const_ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/powercap/powercap_sys.c (ffffffff81783e60)
Location: drivers/powercap/powercap_sys.c:494
Inline: True
```
**Symbols:**

```
ffffffff81783e60-ffffffff81784453: powercap_register_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct powercap_zone *powercap_register_zone(struct powercap_zone *power_zone, struct powercap_control_type *control_type, const char *name, struct powercap_zone *parent, const struct powercap_zone_ops *ops, int nr_constraints, const struct powercap_zone_constraint_ops *const_ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/powercap/powercap_sys.c (ffffffff817a2c40)
Location: drivers/powercap/powercap_sys.c:494
Inline: True
```
**Symbols:**

```
ffffffff817a2c40-ffffffff817a3261: powercap_register_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct powercap_zone *powercap_register_zone(struct powercap_zone *power_zone, struct powercap_control_type *control_type, const char *name, struct powercap_zone *parent, const struct powercap_zone_ops *ops, int nr_constraints, const struct powercap_zone_constraint_ops *const_ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/powercap/powercap_sys.c (ffffffff81819d80)
Location: drivers/powercap/powercap_sys.c:494
Inline: True
```
**Symbols:**

```
ffffffff81819d80-ffffffff8181a3db: powercap_register_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct powercap_zone *powercap_register_zone(struct powercap_zone *power_zone, struct powercap_control_type *control_type, const char *name, struct powercap_zone *parent, const struct powercap_zone_ops *ops, int nr_constraints, const struct powercap_zone_constraint_ops *const_ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/powercap/powercap_sys.c (ffffffff81863e30)
Location: drivers/powercap/powercap_sys.c:494
Inline: True
```
**Symbols:**

```
ffffffff81863e30-ffffffff8186448f: powercap_register_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct powercap_zone *powercap_register_zone(struct powercap_zone *power_zone, struct powercap_control_type *control_type, const char *name, struct powercap_zone *parent, const struct powercap_zone_ops *ops, int nr_constraints, const struct powercap_zone_constraint_ops *const_ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/powercap/powercap_sys.c (ffffffff818835c0)
Location: drivers/powercap/powercap_sys.c:494
Inline: True
```
**Symbols:**

```
ffffffff818835c0-ffffffff81883c1f: powercap_register_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct powercap_zone *powercap_register_zone(struct powercap_zone *power_zone, struct powercap_control_type *control_type, const char *name, struct powercap_zone *parent, const struct powercap_zone_ops *ops, int nr_constraints, const struct powercap_zone_constraint_ops *const_ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/powercap/powercap_sys.c (ffffffff818cdc60)
Location: drivers/powercap/powercap_sys.c:482
Inline: True
```
**Symbols:**

```
ffffffff818cdc60-ffffffff818ce1f1: powercap_register_zone.part.0 (STB_LOCAL)
ffffffff818ce200-ffffffff818ce309: powercap_register_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct powercap_zone *powercap_register_zone(struct powercap_zone *power_zone, struct powercap_control_type *control_type, const char *name, struct powercap_zone *parent, const struct powercap_zone_ops *ops, int nr_constraints, const struct powercap_zone_constraint_ops *const_ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/powercap/powercap_sys.c (ffffffff81900050)
Location: drivers/powercap/powercap_sys.c:482
Inline: True
```
**Symbols:**

```
ffffffff81900050-ffffffff819005e1: powercap_register_zone.part.0 (STB_LOCAL)
ffffffff819005f0-ffffffff819006f9: powercap_register_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct powercap_zone *powercap_register_zone(struct powercap_zone *power_zone, struct powercap_control_type *control_type, const char *name, struct powercap_zone *parent, const struct powercap_zone_ops *ops, int nr_constraints, const struct powercap_zone_constraint_ops *const_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/powercap/powercap_sys.c (ffffffff819d7000)
Location: drivers/powercap/powercap_sys.c:482
Inline: False
```
**Symbols:**

```
ffffffff819d7000-ffffffff819d741a: powercap_register_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct powercap_zone *powercap_register_zone(struct powercap_zone *power_zone, struct powercap_control_type *control_type, const char *name, struct powercap_zone *parent, const struct powercap_zone_ops *ops, int nr_constraints, const struct powercap_zone_constraint_ops *const_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/powercap/powercap_sys.c (ffffffff819d6400)
Location: drivers/powercap/powercap_sys.c:481
Inline: False
```
**Symbols:**

```
ffffffff819d6400-ffffffff819d681a: powercap_register_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct powercap_zone *powercap_register_zone(struct powercap_zone *power_zone, struct powercap_control_type *control_type, const char *name, struct powercap_zone *parent, const struct powercap_zone_ops *ops, int nr_constraints, const struct powercap_zone_constraint_ops *const_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/powercap/powercap_sys.c (ffffffff819bc4d0)
Location: drivers/powercap/powercap_sys.c:481
Inline: False
Direct callers:
  - drivers/powercap/dtpm.c:dtpm_register
  - drivers/powercap/dtpm.c:dtpm_register
```
**Symbols:**

```
ffffffff819bc4d0-ffffffff819bc996: powercap_register_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct powercap_zone *powercap_register_zone(struct powercap_zone *power_zone, struct powercap_control_type *control_type, const char *name, struct powercap_zone *parent, const struct powercap_zone_ops *ops, int nr_constraints, const struct powercap_zone_constraint_ops *const_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/powercap/powercap_sys.c (0)
Location: drivers/powercap/powercap_sys.c:481
Inline: False
Direct callers:
  - drivers/powercap/dtpm.c:dtpm_register
  - drivers/powercap/dtpm.c:dtpm_register
```
**Symbols:**

```
ffffffff81d34229-ffffffff81d3423d: powercap_register_zone.cold (STB_LOCAL)
ffffffff81a6b910-ffffffff81a6bde2: powercap_register_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct powercap_zone *powercap_register_zone(struct powercap_zone *power_zone, struct powercap_control_type *control_type, const char *name, struct powercap_zone *parent, const struct powercap_zone_ops *ops, int nr_constraints, const struct powercap_zone_constraint_ops *const_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/powercap/powercap_sys.c (0)
Location: drivers/powercap/powercap_sys.c:481
Inline: False
```
**Symbols:**

```
ffffffff81f00623-ffffffff81f00638: powercap_register_zone.cold (STB_LOCAL)
ffffffff81bdc3c0-ffffffff81bdc87d: powercap_register_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct powercap_zone *powercap_register_zone(struct powercap_zone *power_zone, struct powercap_control_type *control_type, const char *name, struct powercap_zone *parent, const struct powercap_zone_ops *ops, int nr_constraints, const struct powercap_zone_constraint_ops *const_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/powercap/powercap_sys.c (0)
Location: drivers/powercap/powercap_sys.c:482
Inline: False
```
**Symbols:**

```
ffffffff820aa690-ffffffff820aa6a5: powercap_register_zone.cold (STB_LOCAL)
ffffffff81d874d0-ffffffff81d879b8: powercap_register_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct powercap_zone *powercap_register_zone(struct powercap_zone *power_zone, struct powercap_control_type *control_type, const char *name, struct powercap_zone *parent, const struct powercap_zone_ops *ops, int nr_constraints, const struct powercap_zone_constraint_ops *const_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/powercap/powercap_sys.c (0)
Location: drivers/powercap/powercap_sys.c:482
Inline: False
```
**Symbols:**

```
ffffffff8212bb7b-ffffffff8212bb90: powercap_register_zone.cold (STB_LOCAL)
ffffffff81df5940-ffffffff81df5e28: powercap_register_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct powercap_zone *powercap_register_zone(struct powercap_zone *power_zone, struct powercap_control_type *control_type, const char *name, struct powercap_zone *parent, const struct powercap_zone_ops *ops, int nr_constraints, const struct powercap_zone_constraint_ops *const_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/powercap/powercap_sys.c (0)
Location: drivers/powercap/powercap_sys.c:482
Inline: False
```
**Symbols:**

```
ffffffff8220d810-ffffffff8220d825: powercap_register_zone.cold (STB_LOCAL)
ffffffff81eac000-ffffffff81eac51a: powercap_register_zone (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct powercap_zone *powercap_register_zone(struct powercap_zone *power_zone, struct powercap_control_type *control_type, const char *name, struct powercap_zone *parent, const struct powercap_zone_ops *ops, int nr_constraints, const struct powercap_zone_constraint_ops *const_ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/powercap/powercap_sys.c (ffff800010b8f938)
Location: drivers/powercap/powercap_sys.c:482
Inline: True
```
**Symbols:**

```
ffff800010b8f938-ffff800010b8fdd4: powercap_register_zone.part.0 (STB_LOCAL)
ffff800010b8fdd8-ffff800010b8fee8: powercap_register_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct powercap_zone *powercap_register_zone(struct powercap_zone *power_zone, struct powercap_control_type *control_type, const char *name, struct powercap_zone *parent, const struct powercap_zone_ops *ops, int nr_constraints, const struct powercap_zone_constraint_ops *const_ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/powercap/powercap_sys.c (c0c799a4)
Location: drivers/powercap/powercap_sys.c:482
Inline: True
```
**Symbols:**

```
c0c799a4-c0c79e80: powercap_register_zone.part.0 (STB_LOCAL)
c0c79e80-c0c79f80: powercap_register_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct powercap_zone *powercap_register_zone(struct powercap_zone *power_zone, struct powercap_control_type *control_type, const char *name, struct powercap_zone *parent, const struct powercap_zone_ops *ops, int nr_constraints, const struct powercap_zone_constraint_ops *const_ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/powercap/powercap_sys.c (c000000000c6e870)
Location: drivers/powercap/powercap_sys.c:482
Inline: True
```
**Symbols:**

```
c000000000c6e870-c000000000c6eea8: powercap_register_zone.part.0 (STB_LOCAL)
c000000000c6eeb0-c000000000c6f074: powercap_register_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct powercap_zone *powercap_register_zone(struct powercap_zone *power_zone, struct powercap_control_type *control_type, const char *name, struct powercap_zone *parent, const struct powercap_zone_ops *ops, int nr_constraints, const struct powercap_zone_constraint_ops *const_ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/powercap/powercap_sys.c (ffffffe0007353e4)
Location: drivers/powercap/powercap_sys.c:482
Inline: True
```
**Symbols:**

```
ffffffe0007353e4-ffffffe0007357fc: powercap_register_zone.part.0 (STB_LOCAL)
ffffffe0007357fc-ffffffe0007358fa: powercap_register_zone (STB_GLOBAL)
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
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct powercap_zone *powercap_register_zone(struct powercap_zone *power_zone, struct powercap_control_type *control_type, const char *name, struct powercap_zone *parent, const struct powercap_zone_ops *ops, int nr_constraints, const struct powercap_zone_constraint_ops *const_ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/powercap/powercap_sys.c (ffffffff818f0a70)
Location: drivers/powercap/powercap_sys.c:482
Inline: True
```
**Symbols:**

```
ffffffff818f0a70-ffffffff818f1001: powercap_register_zone.part.0 (STB_LOCAL)
ffffffff818f1010-ffffffff818f1119: powercap_register_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct powercap_zone *powercap_register_zone(struct powercap_zone *power_zone, struct powercap_control_type *control_type, const char *name, struct powercap_zone *parent, const struct powercap_zone_ops *ops, int nr_constraints, const struct powercap_zone_constraint_ops *const_ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/powercap/powercap_sys.c (ffffffff81911af0)
Location: drivers/powercap/powercap_sys.c:482
Inline: True
```
**Symbols:**

```
ffffffff81911af0-ffffffff81912081: powercap_register_zone.part.0 (STB_LOCAL)
ffffffff81912090-ffffffff81912199: powercap_register_zone (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct powercap_zone_constraint_ops *const_ops</code> ➡️ <code>const struct powercap_zone_constraint_ops *const_ops</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
