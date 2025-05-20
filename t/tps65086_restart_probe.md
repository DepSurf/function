# Function: <code>tps65086_restart_probe</code>

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
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tps65086_restart_probe(struct platform_device *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/reset/tps65086-restart.c (0)
Location: drivers/power/reset/tps65086-restart.c:40
Inline: False
```
**Symbols:**

```
ffffffff819db800-ffffffff819db85f: tps65086_restart_probe (STB_LOCAL)
ffffffff81d262b6-ffffffff81d262d8: tps65086_restart_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tps65086_restart_probe(struct platform_device *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/reset/tps65086-restart.c (0)
Location: drivers/power/reset/tps65086-restart.c:40
Inline: False
```
**Symbols:**

```
ffffffff81b3f2b0-ffffffff81b3f31c: tps65086_restart_probe (STB_LOCAL)
ffffffff81ef2109-ffffffff81ef212b: tps65086_restart_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tps65086_restart_probe(struct platform_device *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/reset/tps65086-restart.c (ffffffff81cd56b0)
Location: drivers/power/reset/tps65086-restart.c:40
Inline: False
```
**Symbols:**

```
ffffffff81cd56b0-ffffffff81cd5737: tps65086_restart_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tps65086_restart_probe(struct platform_device *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/reset/tps65086-restart.c (ffffffff81d3d340)
Location: drivers/power/reset/tps65086-restart.c:40
Inline: False
```
**Symbols:**

```
ffffffff81d3d340-ffffffff81d3d3c7: tps65086_restart_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tps65086_restart_probe(struct platform_device *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/reset/tps65086-restart.c (ffffffff81df3c90)
Location: drivers/power/reset/tps65086-restart.c:40
Inline: False
```
**Symbols:**

```
ffffffff81df3c90-ffffffff81df3d17: tps65086_restart_probe (STB_LOCAL)
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
