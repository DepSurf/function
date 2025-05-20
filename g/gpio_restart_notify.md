# Function: <code>gpio_restart_notify</code>

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
In <code>6.2</code>: Absent ⚠️
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int gpio_restart_notify(struct notifier_block *this, long unsigned int mode, void *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/reset/gpio-restart.c (ffff800010ac97d0)
Location: drivers/power/reset/gpio-restart.c:26
Inline: False
```
**Symbols:**

```
ffff800010ac97d0-ffff800010ac98ac: gpio_restart_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gpio_restart_notify(struct notifier_block *this, long unsigned int mode, void *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/reset/gpio-restart.c (c0baa47c)
Location: drivers/power/reset/gpio-restart.c:26
Inline: False
```
**Symbols:**

```
c0baa47c-c0baa580: gpio_restart_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int gpio_restart_notify(struct notifier_block *this, long unsigned int mode, void *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/reset/gpio-restart.c (c000000000bab660)
Location: drivers/power/reset/gpio-restart.c:26
Inline: False
```
**Symbols:**

```
c000000000bab660-c000000000bab70c: gpio_restart_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int gpio_restart_notify(struct notifier_block *this, long unsigned int mode, void *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/reset/gpio-restart.c (ffffffe0006c78c4)
Location: drivers/power/reset/gpio-restart.c:26
Inline: False
```
**Symbols:**

```
ffffffe0006c78c4-ffffffe0006c7974: gpio_restart_notify (STB_LOCAL)
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
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
