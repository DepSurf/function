# Function: <code>watchdog_worker_should_ping</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff817354b0)
Location: drivers/watchdog/watchdog_dev.c:198
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff817a71a0)
Location: drivers/watchdog/watchdog_dev.c:199
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
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
In drivers/watchdog/watchdog_dev.c (ffffffff817eec10)
Location: drivers/watchdog/watchdog_dev.c:210
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
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
In drivers/watchdog/watchdog_dev.c (ffffffff8181aae0)
Location: drivers/watchdog/watchdog_dev.c:210
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
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
In drivers/watchdog/watchdog_dev.c (ffffffff8185ccdd)
Location: drivers/watchdog/watchdog_dev.c:221
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
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
In drivers/watchdog/watchdog_dev.c (ffffffff8188eaed)
Location: drivers/watchdog/watchdog_dev.c:220
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8195d78d)
Location: drivers/watchdog/watchdog_dev.c:220
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8196413d)
Location: drivers/watchdog/watchdog_dev.c:218
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8194855d)
Location: drivers/watchdog/watchdog_dev.c:218
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool watchdog_worker_should_ping(struct watchdog_core_data *wd_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff819ed200)
Location: drivers/watchdog/watchdog_dev.c:198
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_resume
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_suspend
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
```
**Symbols:**

```
ffffffff819ed200-ffffffff819ed24e: watchdog_worker_should_ping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool watchdog_worker_should_ping(struct watchdog_core_data *wd_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81b53b10)
Location: drivers/watchdog/watchdog_dev.c:198
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_resume
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_suspend
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
```
**Symbols:**

```
ffffffff81b53b10-ffffffff81b53b76: watchdog_worker_should_ping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool watchdog_worker_should_ping(struct watchdog_core_data *wd_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81ceca70)
Location: drivers/watchdog/watchdog_dev.c:203
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_resume
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_suspend
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
```
**Symbols:**

```
ffffffff81ceca70-ffffffff81cecad6: watchdog_worker_should_ping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool watchdog_worker_should_ping(struct watchdog_core_data *wd_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81d55790)
Location: drivers/watchdog/watchdog_dev.c:204
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_resume
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_suspend
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
```
**Symbols:**

```
ffffffff81d55790-ffffffff81d557f6: watchdog_worker_should_ping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool watchdog_worker_should_ping(struct watchdog_core_data *wd_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81e0c6a0)
Location: drivers/watchdog/watchdog_dev.c:204
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_resume
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_suspend
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
```
**Symbols:**

```
ffffffff81e0c6a0-ffffffff81e0c706: watchdog_worker_should_ping (STB_LOCAL)
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
In drivers/watchdog/watchdog_dev.c (ffff800010adf6b8)
Location: drivers/watchdog/watchdog_dev.c:220
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
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
In drivers/watchdog/watchdog_dev.c (c0bc12f0)
Location: drivers/watchdog/watchdog_dev.c:220
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
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
In drivers/watchdog/watchdog_dev.c (c000000000bc78d8)
Location: drivers/watchdog/watchdog_dev.c:220
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
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
In drivers/watchdog/watchdog_dev.c (ffffffe0006d753c)
Location: drivers/watchdog/watchdog_dev.c:220
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
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
In drivers/watchdog/watchdog_dev.c (ffffffff8183496d)
Location: drivers/watchdog/watchdog_dev.c:220
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
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
In drivers/watchdog/watchdog_dev.c (ffffffff817fbffd)
Location: drivers/watchdog/watchdog_dev.c:220
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
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
In drivers/watchdog/watchdog_dev.c (ffffffff81883f9d)
Location: drivers/watchdog/watchdog_dev.c:220
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
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
In drivers/watchdog/watchdog_dev.c (ffffffff8189fa5d)
Location: drivers/watchdog/watchdog_dev.c:220
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
```
</details>
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
