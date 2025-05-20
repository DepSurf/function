# Function: <code>thermal_notify_cdev_add</code>

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
int thermal_notify_cdev_add(int cdev_id, const char *name, int cdev_max_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81960150)
Location: drivers/thermal/thermal_netlink.c:336
Inline: False
```
**Symbols:**

```
ffffffff81960150-ffffffff819601aa: thermal_notify_cdev_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int thermal_notify_cdev_add(int cdev_id, const char *name, int cdev_max_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff819436a0)
Location: drivers/thermal/thermal_netlink.c:336
Inline: False
```
**Symbols:**

```
ffffffff819436a0-ffffffff819436fa: thermal_notify_cdev_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int thermal_notify_cdev_add(int cdev_id, const char *name, int cdev_max_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff819e8070)
Location: drivers/thermal/thermal_netlink.c:336
Inline: False
```
**Symbols:**

```
ffffffff819e8070-ffffffff819e80ca: thermal_notify_cdev_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int thermal_notify_cdev_add(int cdev_id, const char *name, int cdev_max_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81b4da00)
Location: drivers/thermal/thermal_netlink.c:381
Inline: False
```
**Symbols:**

```
ffffffff81b4da00-ffffffff81b4da69: thermal_notify_cdev_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int thermal_notify_cdev_add(int cdev_id, const char *name, int cdev_max_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81ce5820)
Location: drivers/thermal/thermal_netlink.c:381
Inline: False
```
**Symbols:**

```
ffffffff81ce5820-ffffffff81ce5889: thermal_notify_cdev_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int thermal_notify_cdev_add(int cdev_id, const char *name, int cdev_max_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81d4ddf0)
Location: drivers/thermal/thermal_netlink.c:381
Inline: False
```
**Symbols:**

```
ffffffff81d4ddf0-ffffffff81d4de59: thermal_notify_cdev_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int thermal_notify_cdev_add(const struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81e04a50)
Location: drivers/thermal/thermal_netlink.c:375
Inline: False
```
**Symbols:**

```
ffffffff81e04a50-ffffffff81e04abf: thermal_notify_cdev_add (STB_GLOBAL)
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
<b>Param removed. </b>
<code>int cdev_id</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *name</code>
</li>
<li>
<b>Param removed. </b>
<code>int cdev_max_state</code>
</li>
</ul>
</details>
</li>
</ul>
