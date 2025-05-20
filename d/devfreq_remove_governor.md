# Function: <code>devfreq_remove_governor</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int devfreq_remove_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff816ecdb0)
Location: drivers/devfreq/devfreq.c:719
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_exit
  - drivers/devfreq/governor_performance.c:devfreq_performance_exit
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_exit
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_exit
```
**Symbols:**

```
ffffffff816ecdb0-ffffffff816ecf0f: devfreq_remove_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int devfreq_remove_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81751c70)
Location: drivers/devfreq/devfreq.c:850
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_exit
  - drivers/devfreq/governor_performance.c:devfreq_performance_exit
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_exit
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_exit
  - drivers/devfreq/governor_passive.c:devfreq_passive_exit
```
**Symbols:**

```
ffffffff81751c70-ffffffff81751dd2: devfreq_remove_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int devfreq_remove_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8177da40)
Location: drivers/devfreq/devfreq.c:862
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_exit
  - drivers/devfreq/governor_performance.c:devfreq_performance_exit
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_exit
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_exit
  - drivers/devfreq/governor_passive.c:devfreq_passive_exit
```
**Symbols:**

```
ffffffff8177da40-ffffffff8177dba2: devfreq_remove_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int devfreq_remove_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8179c580)
Location: drivers/devfreq/devfreq.c:857
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_exit
  - drivers/devfreq/governor_performance.c:devfreq_performance_exit
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_exit
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_exit
  - drivers/devfreq/governor_passive.c:devfreq_passive_exit
```
**Symbols:**

```
ffffffff8179c580-ffffffff8179c6e2: devfreq_remove_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int devfreq_remove_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff818127d0)
Location: drivers/devfreq/devfreq.c:918
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_exit
  - drivers/devfreq/governor_performance.c:devfreq_performance_exit
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_exit
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_exit
  - drivers/devfreq/governor_passive.c:devfreq_passive_exit
```
**Symbols:**

```
ffffffff818127d0-ffffffff8181293c: devfreq_remove_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int devfreq_remove_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:921
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_exit
  - drivers/devfreq/governor_performance.c:devfreq_performance_exit
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_exit
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_exit
  - drivers/devfreq/governor_passive.c:devfreq_passive_exit
```
**Symbols:**

```
ffffffff8185dcf7-ffffffff8185dd2f: devfreq_remove_governor.cold.18 (STB_LOCAL)
ffffffff8185c6a0-ffffffff8185c7d6: devfreq_remove_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int devfreq_remove_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:1050
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_exit
  - drivers/devfreq/governor_performance.c:devfreq_performance_exit
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_exit
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_exit
  - drivers/devfreq/governor_passive.c:devfreq_passive_exit
```
**Symbols:**

```
ffffffff8187d710-ffffffff8187d748: devfreq_remove_governor.cold.23 (STB_LOCAL)
ffffffff8187bbe0-ffffffff8187bd16: devfreq_remove_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int devfreq_remove_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:1063
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_exit
  - drivers/devfreq/governor_performance.c:devfreq_performance_exit
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_exit
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_exit
  - drivers/devfreq/governor_passive.c:devfreq_passive_exit
```
**Symbols:**

```
ffffffff818c7ad8-ffffffff818c7b5b: devfreq_remove_governor.cold (STB_LOCAL)
ffffffff818c5da0-ffffffff818c5e91: devfreq_remove_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int devfreq_remove_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:1062
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_exit
  - drivers/devfreq/governor_performance.c:devfreq_performance_exit
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_exit
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_exit
  - drivers/devfreq/governor_passive.c:devfreq_passive_exit
```
**Symbols:**

```
ffffffff818f9f9e-ffffffff818fa021: devfreq_remove_governor.cold (STB_LOCAL)
ffffffff818f92e0-ffffffff818f93d1: devfreq_remove_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int devfreq_remove_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:1209
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_exit
  - drivers/devfreq/governor_performance.c:devfreq_performance_exit
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_exit
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_exit
  - drivers/devfreq/governor_passive.c:devfreq_passive_exit
```
**Symbols:**

```
ffffffff819d09cd-ffffffff819d0a50: devfreq_remove_governor.cold (STB_LOCAL)
ffffffff819cf150-ffffffff819cf241: devfreq_remove_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int devfreq_remove_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:1290
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_exit
  - drivers/devfreq/governor_performance.c:devfreq_performance_exit
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_exit
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_exit
  - drivers/devfreq/governor_passive.c:devfreq_passive_exit
```
**Symbols:**

```
ffffffff81c2f2d4-ffffffff81c2f354: devfreq_remove_governor.cold (STB_LOCAL)
ffffffff819ced40-ffffffff819cee32: devfreq_remove_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int devfreq_remove_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:1308
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_exit
  - drivers/devfreq/governor_performance.c:devfreq_performance_exit
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_exit
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_exit
  - drivers/devfreq/governor_passive.c:devfreq_passive_exit
```
**Symbols:**

```
ffffffff81c21599-ffffffff81c21619: devfreq_remove_governor.cold (STB_LOCAL)
ffffffff819b3ea0-ffffffff819b3f92: devfreq_remove_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int devfreq_remove_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:1308
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_exit
  - drivers/devfreq/governor_performance.c:devfreq_performance_exit
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_exit
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_exit
  - drivers/devfreq/governor_passive.c:devfreq_passive_exit
```
**Symbols:**

```
ffffffff81d33102-ffffffff81d33182: devfreq_remove_governor.cold (STB_LOCAL)
ffffffff81a62a80-ffffffff81a62b72: devfreq_remove_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int devfreq_remove_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:1338
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_remove_governor
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_exit
  - drivers/devfreq/governor_performance.c:devfreq_performance_exit
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_exit
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_exit
  - drivers/devfreq/governor_passive.c:devfreq_passive_exit
```
**Symbols:**

```
ffffffff81eff59e-ffffffff81eff61d: devfreq_remove_governor.cold (STB_LOCAL)
ffffffff81bd3ed0-ffffffff81bd3fcf: devfreq_remove_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devfreq_remove_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81d7ff60)
Location: drivers/devfreq/devfreq.c:1340
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_remove_governor
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_exit
  - drivers/devfreq/governor_performance.c:devfreq_performance_exit
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_exit
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_exit
  - drivers/devfreq/governor_passive.c:devfreq_passive_exit
```
**Symbols:**

```
ffffffff81d7ff60-ffffffff81d800d3: devfreq_remove_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devfreq_remove_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81dee2f0)
Location: drivers/devfreq/devfreq.c:1341
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_remove_governor
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_exit
  - drivers/devfreq/governor_performance.c:devfreq_performance_exit
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_exit
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_exit
  - drivers/devfreq/governor_passive.c:devfreq_passive_exit
```
**Symbols:**

```
ffffffff81dee2f0-ffffffff81dee463: devfreq_remove_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devfreq_remove_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81ea47a0)
Location: drivers/devfreq/devfreq.c:1362
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_remove_governor
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_exit
  - drivers/devfreq/governor_performance.c:devfreq_performance_exit
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_exit
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_exit
  - drivers/devfreq/governor_passive.c:devfreq_passive_exit
```
**Symbols:**

```
ffffffff81ea47a0-ffffffff81ea4913: devfreq_remove_governor (STB_GLOBAL)
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
int devfreq_remove_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffff800010b84a28)
Location: drivers/devfreq/devfreq.c:1062
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_exit
  - drivers/devfreq/governor_performance.c:devfreq_performance_exit
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_exit
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_exit
  - drivers/devfreq/governor_passive.c:devfreq_passive_exit
```
**Symbols:**

```
ffff800010b84a28-ffff800010b84bb0: devfreq_remove_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devfreq_remove_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (c0c68ba8)
Location: drivers/devfreq/devfreq.c:1062
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_exit
  - drivers/devfreq/governor_performance.c:devfreq_performance_exit
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_exit
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_exit
  - drivers/devfreq/governor_passive.c:devfreq_passive_exit
```
**Symbols:**

```
c0c68ba8-c0c68d0c: devfreq_remove_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devfreq_remove_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (c000000000c64100)
Location: drivers/devfreq/devfreq.c:1062
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_exit
  - drivers/devfreq/governor_performance.c:devfreq_performance_exit
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_exit
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_exit
  - drivers/devfreq/governor_passive.c:devfreq_passive_exit
```
**Symbols:**

```
c000000000c64100-c000000000c6438c: devfreq_remove_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devfreq_remove_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffe00072e120)
Location: drivers/devfreq/devfreq.c:1062
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_exit
  - drivers/devfreq/governor_performance.c:devfreq_performance_exit
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_exit
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_exit
  - drivers/devfreq/governor_passive.c:devfreq_passive_exit
```
**Symbols:**

```
ffffffe00072e120-ffffffe00072e278: devfreq_remove_governor (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int devfreq_remove_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:1062
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_exit
  - drivers/devfreq/governor_performance.c:devfreq_performance_exit
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_exit
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_exit
  - drivers/devfreq/governor_passive.c:devfreq_passive_exit
```
**Symbols:**

```
ffffffff8189b2ce-ffffffff8189b351: devfreq_remove_governor.cold (STB_LOCAL)
ffffffff8189a610-ffffffff8189a701: devfreq_remove_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int devfreq_remove_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:1062
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_exit
  - drivers/devfreq/governor_performance.c:devfreq_performance_exit
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_exit
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_exit
  - drivers/devfreq/governor_passive.c:devfreq_passive_exit
```
**Symbols:**

```
ffffffff8185879e-ffffffff81858821: devfreq_remove_governor.cold (STB_LOCAL)
ffffffff81857ae0-ffffffff81857bd1: devfreq_remove_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int devfreq_remove_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:1062
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_exit
  - drivers/devfreq/governor_performance.c:devfreq_performance_exit
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_exit
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_exit
  - drivers/devfreq/governor_passive.c:devfreq_passive_exit
```
**Symbols:**

```
ffffffff818ea9be-ffffffff818eaa41: devfreq_remove_governor.cold (STB_LOCAL)
ffffffff818e9d00-ffffffff818e9df1: devfreq_remove_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int devfreq_remove_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:1062
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_exit
  - drivers/devfreq/governor_performance.c:devfreq_performance_exit
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_exit
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_exit
  - drivers/devfreq/governor_passive.c:devfreq_passive_exit
```
**Symbols:**

```
ffffffff8190ba3e-ffffffff8190bac1: devfreq_remove_governor.cold (STB_LOCAL)
ffffffff8190ad80-ffffffff8190ae71: devfreq_remove_governor (STB_GLOBAL)
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
