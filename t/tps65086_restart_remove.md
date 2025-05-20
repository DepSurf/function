# Function: <code>tps65086_restart_remove</code>

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
int tps65086_restart_remove(struct platform_device *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/reset/tps65086-restart.c (0)
Location: drivers/power/reset/tps65086-restart.c:65
Inline: False
```
**Symbols:**

```
ffffffff819db770-ffffffff819db797: tps65086_restart_remove (STB_LOCAL)
ffffffff81d26275-ffffffff81d26298: tps65086_restart_remove.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tps65086_restart_remove(struct platform_device *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/reset/tps65086-restart.c (0)
Location: drivers/power/reset/tps65086-restart.c:65
Inline: False
```
**Symbols:**

```
ffffffff81b3f210-ffffffff81b3f243: tps65086_restart_remove (STB_LOCAL)
ffffffff81ef20c8-ffffffff81ef20eb: tps65086_restart_remove.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tps65086_restart_remove(struct platform_device *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/reset/tps65086-restart.c (ffffffff81cd5650)
Location: drivers/power/reset/tps65086-restart.c:65
Inline: False
```
**Symbols:**

```
ffffffff81cd5650-ffffffff81cd569f: tps65086_restart_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tps65086_restart_remove(struct platform_device *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/reset/tps65086-restart.c (ffffffff81d3d2e0)
Location: drivers/power/reset/tps65086-restart.c:65
Inline: False
```
**Symbols:**

```
ffffffff81d3d2e0-ffffffff81d3d32f: tps65086_restart_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tps65086_restart_remove(struct platform_device *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/reset/tps65086-restart.c (ffffffff81df3c20)
Location: drivers/power/reset/tps65086-restart.c:65
Inline: False
```
**Symbols:**

```
ffffffff81df3c20-ffffffff81df3c7e: tps65086_restart_remove (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
</ul>
