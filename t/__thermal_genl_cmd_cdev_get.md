# Function: <code>__thermal_genl_cmd_cdev_get</code>

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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __thermal_genl_cmd_cdev_get(struct thermal_cooling_device *cdev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_netlink.c (0)
Location: drivers/thermal/thermal_netlink.c:499
Inline: False
```
**Symbols:**

```
ffffffff8195f9a0-ffffffff8195fa40: __thermal_genl_cmd_cdev_get (STB_LOCAL)
ffffffff81c25caa-ffffffff81c25cc2: __thermal_genl_cmd_cdev_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __thermal_genl_cmd_cdev_get(struct thermal_cooling_device *cdev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81942f00)
Location: drivers/thermal/thermal_netlink.c:499
Inline: False
```
**Symbols:**

```
ffffffff81942f00-ffffffff81942f8d: __thermal_genl_cmd_cdev_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __thermal_genl_cmd_cdev_get(struct thermal_cooling_device *cdev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff819e78d0)
Location: drivers/thermal/thermal_netlink.c:500
Inline: False
```
**Symbols:**

```
ffffffff819e78d0-ffffffff819e795d: __thermal_genl_cmd_cdev_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __thermal_genl_cmd_cdev_get(struct thermal_cooling_device *cdev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81b4d1b0)
Location: drivers/thermal/thermal_netlink.c:554
Inline: False
```
**Symbols:**

```
ffffffff81b4d1b0-ffffffff81b4d246: __thermal_genl_cmd_cdev_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __thermal_genl_cmd_cdev_get(struct thermal_cooling_device *cdev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81ce4ee0)
Location: drivers/thermal/thermal_netlink.c:554
Inline: False
```
**Symbols:**

```
ffffffff81ce4ee0-ffffffff81ce4f76: __thermal_genl_cmd_cdev_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __thermal_genl_cmd_cdev_get(struct thermal_cooling_device *cdev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81d4d4b0)
Location: drivers/thermal/thermal_netlink.c:551
Inline: False
```
**Symbols:**

```
ffffffff81d4d4b0-ffffffff81d4d546: __thermal_genl_cmd_cdev_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __thermal_genl_cmd_cdev_get(struct thermal_cooling_device *cdev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81e041b0)
Location: drivers/thermal/thermal_netlink.c:542
Inline: False
```
**Symbols:**

```
ffffffff81e041b0-ffffffff81e04246: __thermal_genl_cmd_cdev_get (STB_LOCAL)
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
