# Function: <code>mmc_pm_notify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mmc_pm_notify(struct notifier_block *notify_block, long unsigned int mode, void *unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff816c1480)
Location: drivers/mmc/core/core.c:2768
Inline: False
```
**Symbols:**

```
ffffffff816c1480-ffffffff816c157f: mmc_pm_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mmc_pm_notify(struct notifier_block *notify_block, long unsigned int mode, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817239a0)
Location: drivers/mmc/core/core.c:2830
Inline: False
```
**Symbols:**

```
ffffffff817239a0-ffffffff81723a9f: mmc_pm_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mmc_pm_notify(struct notifier_block *notify_block, long unsigned int mode, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81756860)
Location: drivers/mmc/core/core.c:2925
Inline: False
```
**Symbols:**

```
ffffffff81756860-ffffffff8175695f: mmc_pm_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mmc_pm_notify(struct notifier_block *notify_block, long unsigned int mode, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817747a0)
Location: drivers/mmc/core/core.c:2740
Inline: False
```
**Symbols:**

```
ffffffff817747a0-ffffffff817748a1: mmc_pm_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mmc_pm_notify(struct notifier_block *notify_block, long unsigned int mode, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817ea9d0)
Location: drivers/mmc/core/core.c:2936
Inline: False
```
**Symbols:**

```
ffffffff817ea9d0-ffffffff817eaafa: mmc_pm_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mmc_pm_notify(struct notifier_block *notify_block, long unsigned int mode, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81833920)
Location: drivers/mmc/core/core.c:2770
Inline: False
```
**Symbols:**

```
ffffffff81833920-ffffffff81833a4a: mmc_pm_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mmc_pm_notify(struct notifier_block *notify_block, long unsigned int mode, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8185f8b0)
Location: drivers/mmc/core/core.c:2713
Inline: False
```
**Symbols:**

```
ffffffff8185f8b0-ffffffff8185f9da: mmc_pm_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mmc_pm_notify(struct notifier_block *notify_block, long unsigned int mode, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:2401
Inline: False
```
**Symbols:**

```
ffffffff818a3450-ffffffff818a355d: mmc_pm_notify (STB_LOCAL)
ffffffff818a40c8-ffffffff818a40e2: mmc_pm_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int mmc_pm_notify(struct notifier_block *notify_block, long unsigned int mode, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:2400
Inline: False
```
**Symbols:**

```
ffffffff818d57d0-ffffffff818d58dd: mmc_pm_notify (STB_LOCAL)
ffffffff818d6547-ffffffff818d6561: mmc_pm_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int mmc_pm_notify(struct notifier_block *notify_block, long unsigned int mode, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:2354
Inline: False
```
**Symbols:**

```
ffffffff819a8180-ffffffff819a82b9: mmc_pm_notify (STB_LOCAL)
ffffffff819a8e4c-ffffffff819a8e66: mmc_pm_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int mmc_pm_notify(struct notifier_block *notify_block, long unsigned int mode, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:2374
Inline: False
```
**Symbols:**

```
ffffffff819ab370-ffffffff819ab4c4: mmc_pm_notify (STB_LOCAL)
ffffffff81c2a27d-ffffffff81c2a297: mmc_pm_notify.cold (STB_LOCAL)
```
</details>
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
int mmc_pm_notify(struct notifier_block *notify_block, long unsigned int mode, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffff800010b2f120)
Location: drivers/mmc/core/core.c:2400
Inline: False
```
**Symbols:**

```
ffff800010b2f120-ffff800010b2f360: mmc_pm_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mmc_pm_notify(struct notifier_block *notify_block, long unsigned int mode, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c0c0a558)
Location: drivers/mmc/core/core.c:2400
Inline: False
```
**Symbols:**

```
c0c0a558-c0c0a6b4: mmc_pm_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mmc_pm_notify(struct notifier_block *notify_block, long unsigned int mode, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c000000000c28ba0)
Location: drivers/mmc/core/core.c:2400
Inline: False
```
**Symbols:**

```
c000000000c28ba0-c000000000c28dcc: mmc_pm_notify (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int mmc_pm_notify(struct notifier_block *notify_block, long unsigned int mode, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:2400
Inline: False
```
**Symbols:**

```
ffffffff81879190-ffffffff8187929d: mmc_pm_notify (STB_LOCAL)
ffffffff81879f07-ffffffff81879f21: mmc_pm_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int mmc_pm_notify(struct notifier_block *notify_block, long unsigned int mode, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:2400
Inline: False
```
**Symbols:**

```
ffffffff818ca630-ffffffff818ca73d: mmc_pm_notify (STB_LOCAL)
ffffffff818cb3a7-ffffffff818cb3c1: mmc_pm_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int mmc_pm_notify(struct notifier_block *notify_block, long unsigned int mode, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:2400
Inline: False
```
**Symbols:**

```
ffffffff818e7150-ffffffff818e725d: mmc_pm_notify (STB_LOCAL)
ffffffff818e7ec7-ffffffff818e7ee1: mmc_pm_notify.cold (STB_LOCAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
