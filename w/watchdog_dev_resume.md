# Function: <code>watchdog_dev_resume</code>

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
int watchdog_dev_resume(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff819ee000)
Location: drivers/watchdog/watchdog_dev.c:1261
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:watchdog_pm_notifier
```
**Symbols:**

```
ffffffff819ee000-ffffffff819ee063: watchdog_dev_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int watchdog_dev_resume(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81b54960)
Location: drivers/watchdog/watchdog_dev.c:1267
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:watchdog_pm_notifier
```
**Symbols:**

```
ffffffff81b54960-ffffffff81b549c9: watchdog_dev_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int watchdog_dev_resume(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81ced700)
Location: drivers/watchdog/watchdog_dev.c:1279
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:watchdog_pm_notifier
```
**Symbols:**

```
ffffffff81ced700-ffffffff81ced769: watchdog_dev_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int watchdog_dev_resume(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81d56440)
Location: drivers/watchdog/watchdog_dev.c:1300
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:watchdog_pm_notifier
```
**Symbols:**

```
ffffffff81d56440-ffffffff81d564a9: watchdog_dev_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int watchdog_dev_resume(struct watchdog_device *wdd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81e0d350)
Location: drivers/watchdog/watchdog_dev.c:1299
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:watchdog_pm_notifier
```
**Symbols:**

```
ffffffff81e0d350-ffffffff81e0d3b9: watchdog_dev_resume (STB_GLOBAL)
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
