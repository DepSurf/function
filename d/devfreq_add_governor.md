# Function: <code>devfreq_add_governor</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int devfreq_add_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff816ecc10)
Location: drivers/devfreq/devfreq.c:654
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_init
  - drivers/devfreq/governor_performance.c:devfreq_performance_init
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_init
```
**Symbols:**

```
ffffffff816ecc10-ffffffff816ecdaf: devfreq_add_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int devfreq_add_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81751ad0)
Location: drivers/devfreq/devfreq.c:785
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_init
  - drivers/devfreq/governor_performance.c:devfreq_performance_init
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_init
  - drivers/devfreq/governor_passive.c:devfreq_passive_init
```
**Symbols:**

```
ffffffff81751ad0-ffffffff81751c6a: devfreq_add_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int devfreq_add_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8177d8a0)
Location: drivers/devfreq/devfreq.c:797
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_init
  - drivers/devfreq/governor_performance.c:devfreq_performance_init
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_init
  - drivers/devfreq/governor_passive.c:devfreq_passive_init
```
**Symbols:**

```
ffffffff8177d8a0-ffffffff8177da3a: devfreq_add_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int devfreq_add_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8179c3e0)
Location: drivers/devfreq/devfreq.c:792
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_init
  - drivers/devfreq/governor_performance.c:devfreq_performance_init
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_init
  - drivers/devfreq/governor_passive.c:devfreq_passive_init
```
**Symbols:**

```
ffffffff8179c3e0-ffffffff8179c57b: devfreq_add_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int devfreq_add_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81812620)
Location: drivers/devfreq/devfreq.c:853
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_init
  - drivers/devfreq/governor_performance.c:devfreq_performance_init
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_init
  - drivers/devfreq/governor_passive.c:devfreq_passive_init
```
**Symbols:**

```
ffffffff81812620-ffffffff818127ca: devfreq_add_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int devfreq_add_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:856
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_init
  - drivers/devfreq/governor_performance.c:devfreq_performance_init
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_init
  - drivers/devfreq/governor_passive.c:devfreq_passive_init
```
**Symbols:**

```
ffffffff8185dcb9-ffffffff8185dcf7: devfreq_add_governor.cold.17 (STB_LOCAL)
ffffffff8185c520-ffffffff8185c69e: devfreq_add_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int devfreq_add_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:985
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_init
  - drivers/devfreq/governor_performance.c:devfreq_performance_init
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_init
  - drivers/devfreq/governor_passive.c:devfreq_passive_init
```
**Symbols:**

```
ffffffff8187d6d2-ffffffff8187d710: devfreq_add_governor.cold.22 (STB_LOCAL)
ffffffff8187ba60-ffffffff8187bbde: devfreq_add_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int devfreq_add_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:998
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_init
  - drivers/devfreq/governor_performance.c:devfreq_performance_init
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_init
  - drivers/devfreq/governor_passive.c:devfreq_passive_init
```
**Symbols:**

```
ffffffff818c7a0a-ffffffff818c7ad8: devfreq_add_governor.cold (STB_LOCAL)
ffffffff818c5cb0-ffffffff818c5d96: devfreq_add_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int devfreq_add_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:997
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_init
  - drivers/devfreq/governor_performance.c:devfreq_performance_init
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_init
  - drivers/devfreq/governor_passive.c:devfreq_passive_init
```
**Symbols:**

```
ffffffff818f9ed0-ffffffff818f9f9e: devfreq_add_governor.cold (STB_LOCAL)
ffffffff818f91f0-ffffffff818f92d6: devfreq_add_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int devfreq_add_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:1144
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_init
  - drivers/devfreq/governor_performance.c:devfreq_performance_init
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_init
  - drivers/devfreq/governor_passive.c:devfreq_passive_init
```
**Symbols:**

```
ffffffff819d08ff-ffffffff819d09cd: devfreq_add_governor.cold (STB_LOCAL)
ffffffff819cf060-ffffffff819cf146: devfreq_add_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int devfreq_add_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:1225
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_init
  - drivers/devfreq/governor_performance.c:devfreq_performance_init
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_init
  - drivers/devfreq/governor_passive.c:devfreq_passive_init
```
**Symbols:**

```
ffffffff81c2f204-ffffffff81c2f2d4: devfreq_add_governor.cold (STB_LOCAL)
ffffffff819cec40-ffffffff819ced34: devfreq_add_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int devfreq_add_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:1243
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_init
  - drivers/devfreq/governor_performance.c:devfreq_performance_init
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_init
  - drivers/devfreq/governor_passive.c:devfreq_passive_init
```
**Symbols:**

```
ffffffff81c214c9-ffffffff81c21599: devfreq_add_governor.cold (STB_LOCAL)
ffffffff819b3da0-ffffffff819b3e94: devfreq_add_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int devfreq_add_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:1243
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_init
  - drivers/devfreq/governor_performance.c:devfreq_performance_init
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_init
  - drivers/devfreq/governor_passive.c:devfreq_passive_init
```
**Symbols:**

```
ffffffff81d33032-ffffffff81d33102: devfreq_add_governor.cold (STB_LOCAL)
ffffffff81a62980-ffffffff81a62a74: devfreq_add_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int devfreq_add_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:1247
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_init
  - drivers/devfreq/governor_performance.c:devfreq_performance_init
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_init
  - drivers/devfreq/governor_passive.c:devfreq_passive_init
```
**Symbols:**

```
ffffffff81eff4d3-ffffffff81eff59e: devfreq_add_governor.cold (STB_LOCAL)
ffffffff81bd3dc0-ffffffff81bd3ec4: devfreq_add_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devfreq_add_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81d7fd80)
Location: drivers/devfreq/devfreq.c:1249
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_init
  - drivers/devfreq/governor_performance.c:devfreq_performance_init
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_init
  - drivers/devfreq/governor_passive.c:devfreq_passive_init
```
**Symbols:**

```
ffffffff81d7fd80-ffffffff81d7ff4e: devfreq_add_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devfreq_add_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81dee110)
Location: drivers/devfreq/devfreq.c:1250
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_init
  - drivers/devfreq/governor_performance.c:devfreq_performance_init
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_init
  - drivers/devfreq/governor_passive.c:devfreq_passive_init
```
**Symbols:**

```
ffffffff81dee110-ffffffff81dee2de: devfreq_add_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devfreq_add_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81ea45c0)
Location: drivers/devfreq/devfreq.c:1271
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_init
  - drivers/devfreq/governor_performance.c:devfreq_performance_init
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_init
  - drivers/devfreq/governor_passive.c:devfreq_passive_init
```
**Symbols:**

```
ffffffff81ea45c0-ffffffff81ea478e: devfreq_add_governor (STB_GLOBAL)
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
int devfreq_add_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffff800010b84870)
Location: drivers/devfreq/devfreq.c:997
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_init
  - drivers/devfreq/governor_performance.c:devfreq_performance_init
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_init
  - drivers/devfreq/governor_passive.c:devfreq_passive_init
```
**Symbols:**

```
ffff800010b84870-ffff800010b84a28: devfreq_add_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devfreq_add_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (c0c68a00)
Location: drivers/devfreq/devfreq.c:997
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_init
  - drivers/devfreq/governor_performance.c:devfreq_performance_init
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_init
  - drivers/devfreq/governor_passive.c:devfreq_passive_init
```
**Symbols:**

```
c0c68a00-c0c68ba8: devfreq_add_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devfreq_add_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (c000000000c63e40)
Location: drivers/devfreq/devfreq.c:997
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_init
  - drivers/devfreq/governor_performance.c:devfreq_performance_init
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_init
  - drivers/devfreq/governor_passive.c:devfreq_passive_init
```
**Symbols:**

```
c000000000c63e40-c000000000c640fc: devfreq_add_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devfreq_add_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffe00072df96)
Location: drivers/devfreq/devfreq.c:997
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_init
  - drivers/devfreq/governor_performance.c:devfreq_performance_init
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_init
  - drivers/devfreq/governor_passive.c:devfreq_passive_init
```
**Symbols:**

```
ffffffe00072df96-ffffffe00072e120: devfreq_add_governor (STB_GLOBAL)
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
int devfreq_add_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:997
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_init
  - drivers/devfreq/governor_performance.c:devfreq_performance_init
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_init
  - drivers/devfreq/governor_passive.c:devfreq_passive_init
```
**Symbols:**

```
ffffffff8189b200-ffffffff8189b2ce: devfreq_add_governor.cold (STB_LOCAL)
ffffffff8189a520-ffffffff8189a606: devfreq_add_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int devfreq_add_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:997
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_init
  - drivers/devfreq/governor_performance.c:devfreq_performance_init
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_init
  - drivers/devfreq/governor_passive.c:devfreq_passive_init
```
**Symbols:**

```
ffffffff818586d0-ffffffff8185879e: devfreq_add_governor.cold (STB_LOCAL)
ffffffff818579f0-ffffffff81857ad6: devfreq_add_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int devfreq_add_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:997
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_init
  - drivers/devfreq/governor_performance.c:devfreq_performance_init
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_init
  - drivers/devfreq/governor_passive.c:devfreq_passive_init
```
**Symbols:**

```
ffffffff818ea8f0-ffffffff818ea9be: devfreq_add_governor.cold (STB_LOCAL)
ffffffff818e9c10-ffffffff818e9cf6: devfreq_add_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int devfreq_add_governor(struct devfreq_governor *governor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:997
Inline: False
Direct callers:
  - drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_init
  - drivers/devfreq/governor_performance.c:devfreq_performance_init
  - drivers/devfreq/governor_powersave.c:devfreq_powersave_init
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_init
  - drivers/devfreq/governor_passive.c:devfreq_passive_init
```
**Symbols:**

```
ffffffff8190b970-ffffffff8190ba3e: devfreq_add_governor.cold (STB_LOCAL)
ffffffff8190ac90-ffffffff8190ad76: devfreq_add_governor (STB_GLOBAL)
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
