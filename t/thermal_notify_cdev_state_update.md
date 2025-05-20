# Function: <code>thermal_notify_cdev_state_update</code>

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
int thermal_notify_cdev_state_update(int cdev_id, int cdev_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff819600f0)
Location: drivers/thermal/thermal_netlink.c:329
Inline: False
Direct callers:
  - drivers/thermal/thermal_helpers.c:thermal_cdev_update
```
**Symbols:**

```
ffffffff819600f0-ffffffff81960146: thermal_notify_cdev_state_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int thermal_notify_cdev_state_update(int cdev_id, int cdev_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81943640)
Location: drivers/thermal/thermal_netlink.c:329
Inline: False
Direct callers:
  - drivers/thermal/thermal_helpers.c:__thermal_cdev_update
```
**Symbols:**

```
ffffffff81943640-ffffffff81943696: thermal_notify_cdev_state_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int thermal_notify_cdev_state_update(int cdev_id, int cdev_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff819e8010)
Location: drivers/thermal/thermal_netlink.c:329
Inline: False
Direct callers:
  - drivers/thermal/thermal_helpers.c:__thermal_cdev_update
```
**Symbols:**

```
ffffffff819e8010-ffffffff819e8066: thermal_notify_cdev_state_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int thermal_notify_cdev_state_update(int cdev_id, int cdev_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81b4d9a0)
Location: drivers/thermal/thermal_netlink.c:374
Inline: False
Direct callers:
  - drivers/thermal/thermal_helpers.c:__thermal_cdev_update
```
**Symbols:**

```
ffffffff81b4d9a0-ffffffff81b4da00: thermal_notify_cdev_state_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int thermal_notify_cdev_state_update(int cdev_id, int cdev_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81ce57b0)
Location: drivers/thermal/thermal_netlink.c:374
Inline: False
Direct callers:
  - drivers/thermal/thermal_helpers.c:__thermal_cdev_update
```
**Symbols:**

```
ffffffff81ce57b0-ffffffff81ce5810: thermal_notify_cdev_state_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int thermal_notify_cdev_state_update(int cdev_id, int cdev_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81d4dd80)
Location: drivers/thermal/thermal_netlink.c:374
Inline: False
Direct callers:
  - drivers/thermal/thermal_helpers.c:__thermal_cdev_update
```
**Symbols:**

```
ffffffff81d4dd80-ffffffff81d4dde0: thermal_notify_cdev_state_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int thermal_notify_cdev_state_update(const struct thermal_cooling_device *cdev, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81e049d0)
Location: drivers/thermal/thermal_netlink.c:367
Inline: False
Direct callers:
  - drivers/thermal/thermal_helpers.c:__thermal_cdev_update
```
**Symbols:**

```
ffffffff81e049d0-ffffffff81e04a33: thermal_notify_cdev_state_update (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct thermal_cooling_device *cdev</code>
</li>
<li>
<b>Param added. </b>
<code>int state</code>
</li>
<li>
<b>Param removed. </b>
<code>int cdev_id</code>
</li>
<li>
<b>Param removed. </b>
<code>int cdev_state</code>
</li>
</ul>
</details>
</li>
</ul>
