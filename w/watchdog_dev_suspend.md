# Function: <code>watchdog_dev_suspend</code>

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
<summary>In <code>5.15</code>: ✅</summary>

```c
int watchdog_dev_suspend(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff819edf70)
Location: drivers/watchdog/watchdog_dev.c:1234
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:watchdog_pm_notifier
```
**Symbols:**

```
ffffffff819edf70-ffffffff819ee000: watchdog_dev_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int watchdog_dev_suspend(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81b548c0)
Location: drivers/watchdog/watchdog_dev.c:1240
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:watchdog_pm_notifier
```
**Symbols:**

```
ffffffff81b548c0-ffffffff81b5495c: watchdog_dev_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int watchdog_dev_suspend(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81ced650)
Location: drivers/watchdog/watchdog_dev.c:1252
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:watchdog_pm_notifier
```
**Symbols:**

```
ffffffff81ced650-ffffffff81ced6ec: watchdog_dev_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int watchdog_dev_suspend(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81d56390)
Location: drivers/watchdog/watchdog_dev.c:1273
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:watchdog_pm_notifier
```
**Symbols:**

```
ffffffff81d56390-ffffffff81d5642c: watchdog_dev_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int watchdog_dev_suspend(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81e0d2a0)
Location: drivers/watchdog/watchdog_dev.c:1272
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:watchdog_pm_notifier
```
**Symbols:**

```
ffffffff81e0d2a0-ffffffff81e0d33c: watchdog_dev_suspend (STB_GLOBAL)
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
