# Function: <code>tps65086_restart_notify</code>

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
int tps65086_restart_notify(struct notifier_block *this, long unsigned int mode, void *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/reset/tps65086-restart.c (0)
Location: drivers/power/reset/tps65086-restart.c:17
Inline: False
```
**Symbols:**

```
ffffffff819db7a0-ffffffff819db7f3: tps65086_restart_notify (STB_LOCAL)
ffffffff81d26298-ffffffff81d262b6: tps65086_restart_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tps65086_restart_notify(struct notifier_block *this, long unsigned int mode, void *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/reset/tps65086-restart.c (0)
Location: drivers/power/reset/tps65086-restart.c:17
Inline: False
```
**Symbols:**

```
ffffffff81b3f250-ffffffff81b3f2af: tps65086_restart_notify (STB_LOCAL)
ffffffff81ef20eb-ffffffff81ef2109: tps65086_restart_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int tps65086_restart_notify(struct notifier_block *this, long unsigned int mode, void *cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/reset/tps65086-restart.c (ffffffff81cd5750)
Location: drivers/power/reset/tps65086-restart.c:17
Inline: True
```
**Symbols:**

```
ffffffff81cd5750-ffffffff81cd57d9: tps65086_restart_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int tps65086_restart_notify(struct notifier_block *this, long unsigned int mode, void *cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/reset/tps65086-restart.c (ffffffff81d3d3e0)
Location: drivers/power/reset/tps65086-restart.c:17
Inline: True
```
**Symbols:**

```
ffffffff81d3d3e0-ffffffff81d3d469: tps65086_restart_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int tps65086_restart_notify(struct notifier_block *this, long unsigned int mode, void *cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/reset/tps65086-restart.c (ffffffff81df3d30)
Location: drivers/power/reset/tps65086-restart.c:17
Inline: True
```
**Symbols:**

```
ffffffff81df3d30-ffffffff81df3db9: tps65086_restart_notify (STB_LOCAL)
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
