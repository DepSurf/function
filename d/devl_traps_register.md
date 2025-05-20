# Function: <code>devl_traps_register</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devl_traps_register(struct devlink *devlink, const struct devlink_trap *traps, size_t traps_count, void *priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81e3f82d)
Location: net/core/devlink.c:12393
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_traps_register
Direct callers:
  - net/core/devlink.c:devlink_traps_register
```
**Symbols:**

```
ffffffff81e3f3c0-ffffffff81e3f78c: devl_traps_register.part.0 (STB_LOCAL)
ffffffff820ad303-ffffffff820ad318: devl_traps_register.part.0.cold (STB_LOCAL)
ffffffff81e3f7a0-ffffffff81e3f7e9: devl_traps_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devl_traps_register(struct devlink *devlink, const struct devlink_trap *traps, size_t traps_count, void *priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/devlink/leftover.c (ffffffff82040011)
Location: net/devlink/leftover.c:8988
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_traps_register
Direct callers:
  - net/devlink/leftover.c:devlink_traps_register
```
**Symbols:**

```
ffffffff8203fb80-ffffffff8203ff4c: devl_traps_register.part.0 (STB_LOCAL)
ffffffff82136605-ffffffff8213661a: devl_traps_register.part.0.cold (STB_LOCAL)
ffffffff8203ff60-ffffffff8203ffd4: devl_traps_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int devl_traps_register(struct devlink *devlink, const struct devlink_trap *traps, size_t traps_count, void *priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/devlink/trap.c (ffffffff82116ad1)
Location: net/devlink/trap.c:1355
Inline: True
Inline callers:
  - net/devlink/trap.c:devlink_traps_register
Direct callers:
  - net/devlink/trap.c:devlink_traps_register
```
**Symbols:**

```
ffffffff82116620-ffffffff82116a04: devl_traps_register.part.0 (STB_LOCAL)
ffffffff82218775-ffffffff8221878a: devl_traps_register.part.0.cold (STB_LOCAL)
ffffffff82116a20-ffffffff82116a94: devl_traps_register (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
