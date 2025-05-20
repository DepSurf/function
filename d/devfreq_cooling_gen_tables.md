# Function: <code>devfreq_cooling_gen_tables</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff817a626d)
Location: drivers/thermal/devfreq_cooling.c:419
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff817edced)
Location: drivers/thermal/devfreq_cooling.c:419
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff81819bbd)
Location: drivers/thermal/devfreq_cooling.c:419
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
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
In drivers/thermal/devfreq_cooling.c (ffffffff8185bd66)
Location: drivers/thermal/devfreq_cooling.c:419
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
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
In drivers/thermal/devfreq_cooling.c (ffffffff8188d876)
Location: drivers/thermal/devfreq_cooling.c:419
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devfreq_cooling_gen_tables(struct devfreq_cooling_device *dfc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff8195c0a0)
Location: drivers/thermal/devfreq_cooling.c:385
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
**Symbols:**

```
ffffffff8195c0a0-ffffffff8195c3de: devfreq_cooling_gen_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devfreq_cooling_gen_tables(struct devfreq_cooling_device *dfc, int num_opps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff81962a00)
Location: drivers/thermal/devfreq_cooling.c:315
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
**Symbols:**

```
ffffffff81962a00-ffffffff81962af6: devfreq_cooling_gen_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devfreq_cooling_gen_tables(struct devfreq_cooling_device *dfc, int num_opps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff81946000)
Location: drivers/thermal/devfreq_cooling.c:310
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
**Symbols:**

```
ffffffff81946000-ffffffff819460f6: devfreq_cooling_gen_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int devfreq_cooling_gen_tables(struct devfreq_cooling_device *dfc, int num_opps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff819eaa10)
Location: drivers/thermal/devfreq_cooling.c:310
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
**Symbols:**

```
ffffffff819eaa10-ffffffff819eab06: devfreq_cooling_gen_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int devfreq_cooling_gen_tables(struct devfreq_cooling_device *dfc, int num_opps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff81b50830)
Location: drivers/thermal/devfreq_cooling.c:321
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
**Symbols:**

```
ffffffff81b50830-ffffffff81b50934: devfreq_cooling_gen_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devfreq_cooling_gen_tables(struct devfreq_cooling_device *dfc, int num_opps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff81ce87d0)
Location: drivers/thermal/devfreq_cooling.c:317
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
**Symbols:**

```
ffffffff81ce87d0-ffffffff81ce88d4: devfreq_cooling_gen_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devfreq_cooling_gen_tables(struct devfreq_cooling_device *dfc, int num_opps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff81d50f90)
Location: drivers/thermal/devfreq_cooling.c:317
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
**Symbols:**

```
ffffffff81d50f90-ffffffff81d51094: devfreq_cooling_gen_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devfreq_cooling_gen_tables(struct devfreq_cooling_device *dfc, int num_opps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff81e07ce0)
Location: drivers/thermal/devfreq_cooling.c:317
Inline: False
Direct callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
**Symbols:**

```
ffffffff81e07ce0-ffffffff81e07de4: devfreq_cooling_gen_tables (STB_LOCAL)
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
In drivers/thermal/devfreq_cooling.c (ffff800010add160)
Location: drivers/thermal/devfreq_cooling.c:419
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
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
In drivers/thermal/devfreq_cooling.c (c0bbd6d0)
Location: drivers/thermal/devfreq_cooling.c:419
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
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
In drivers/thermal/devfreq_cooling.c (c000000000bc59b8)
Location: drivers/thermal/devfreq_cooling.c:419
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
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
In drivers/thermal/devfreq_cooling.c (ffffffe0006d6410)
Location: drivers/thermal/devfreq_cooling.c:419
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff818336f6)
Location: drivers/thermal/devfreq_cooling.c:419
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff817fad86)
Location: drivers/thermal/devfreq_cooling.c:419
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff81882d26)
Location: drivers/thermal/devfreq_cooling.c:419
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
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
In drivers/thermal/devfreq_cooling.c (ffffffff8189e7e6)
Location: drivers/thermal/devfreq_cooling.c:419
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int num_opps</code>
</li>
</ul>
</details>
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
