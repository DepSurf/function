# Function: <code>watchdog_set_last_hw_keepalive</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int watchdog_set_last_hw_keepalive(struct watchdog_device *wdd, unsigned int last_ping_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff819641a0)
Location: drivers/watchdog/watchdog_dev.c:1152
Inline: False
```
**Symbols:**

```
ffffffff819641a0-ffffffff819641ec: watchdog_set_last_hw_keepalive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int watchdog_set_last_hw_keepalive(struct watchdog_device *wdd, unsigned int last_ping_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff819485c0)
Location: drivers/watchdog/watchdog_dev.c:1152
Inline: False
```
**Symbols:**

```
ffffffff819485c0-ffffffff8194860c: watchdog_set_last_hw_keepalive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int watchdog_set_last_hw_keepalive(struct watchdog_device *wdd, unsigned int last_ping_ms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff819ed5d3)
Location: drivers/watchdog/watchdog_dev.c:1161
Inline: True
```
**Symbols:**

```
ffffffff81d274f1-ffffffff81d27505: watchdog_set_last_hw_keepalive.cold (STB_LOCAL)
ffffffff819ed590-ffffffff819ed606: watchdog_set_last_hw_keepalive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int watchdog_set_last_hw_keepalive(struct watchdog_device *wdd, unsigned int last_ping_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (0)
Location: drivers/watchdog/watchdog_dev.c:1167
Inline: False
```
**Symbols:**

```
ffffffff81ef3384-ffffffff81ef3398: watchdog_set_last_hw_keepalive.cold (STB_LOCAL)
ffffffff81b53e80-ffffffff81b53f0e: watchdog_set_last_hw_keepalive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int watchdog_set_last_hw_keepalive(struct watchdog_device *wdd, unsigned int last_ping_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (0)
Location: drivers/watchdog/watchdog_dev.c:1179
Inline: False
```
**Symbols:**

```
ffffffff820a7d72-ffffffff820a7d86: watchdog_set_last_hw_keepalive.cold (STB_LOCAL)
ffffffff81cecf30-ffffffff81cecfbe: watchdog_set_last_hw_keepalive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int watchdog_set_last_hw_keepalive(struct watchdog_device *wdd, unsigned int last_ping_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (0)
Location: drivers/watchdog/watchdog_dev.c:1200
Inline: False
```
**Symbols:**

```
ffffffff82129150-ffffffff82129164: watchdog_set_last_hw_keepalive.cold (STB_LOCAL)
ffffffff81d55c50-ffffffff81d55cde: watchdog_set_last_hw_keepalive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int watchdog_set_last_hw_keepalive(struct watchdog_device *wdd, unsigned int last_ping_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (0)
Location: drivers/watchdog/watchdog_dev.c:1199
Inline: False
```
**Symbols:**

```
ffffffff8220ab39-ffffffff8220ab4d: watchdog_set_last_hw_keepalive.cold (STB_LOCAL)
ffffffff81e0cb60-ffffffff81e0cbee: watchdog_set_last_hw_keepalive (STB_GLOBAL)
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
