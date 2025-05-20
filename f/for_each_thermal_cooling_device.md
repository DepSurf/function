# Function: <code>for_each_thermal_cooling_device</code>

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
int for_each_thermal_cooling_device(int (*cb)(struct thermal_cooling_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8195c8a0)
Location: drivers/thermal/thermal_core.c:638
Inline: False
Direct callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
```
**Symbols:**

```
ffffffff8195c8a0-ffffffff8195c922: for_each_thermal_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int for_each_thermal_cooling_device(int (*cb)(struct thermal_cooling_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81940020)
Location: drivers/thermal/thermal_core.c:589
Inline: False
Direct callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
```
**Symbols:**

```
ffffffff81940020-ffffffff819400a2: for_each_thermal_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int for_each_thermal_cooling_device(int (*cb)(struct thermal_cooling_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff819e4940)
Location: drivers/thermal/thermal_core.c:536
Inline: False
Direct callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
```
**Symbols:**

```
ffffffff819e4940-ffffffff819e49c2: for_each_thermal_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int for_each_thermal_cooling_device(int (*cb)(struct thermal_cooling_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81b49b40)
Location: drivers/thermal/thermal_core.c:538
Inline: False
Direct callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
```
**Symbols:**

```
ffffffff81b49b40-ffffffff81b49bce: for_each_thermal_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int for_each_thermal_cooling_device(int (*cb)(struct thermal_cooling_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81ce12b0)
Location: drivers/thermal/thermal_core.c:529
Inline: False
Direct callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
```
**Symbols:**

```
ffffffff81ce12b0-ffffffff81ce133e: for_each_thermal_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int for_each_thermal_cooling_device(int (*cb)(struct thermal_cooling_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81d49520)
Location: drivers/thermal/thermal_core.c:524
Inline: False
Direct callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
```
**Symbols:**

```
ffffffff81d49520-ffffffff81d495ae: for_each_thermal_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int for_each_thermal_cooling_device(int (*cb)(struct thermal_cooling_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81e00330)
Location: drivers/thermal/thermal_core.c:565
Inline: False
Direct callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_cdev_get
```
**Symbols:**

```
ffffffff81e00330-ffffffff81e003be: for_each_thermal_cooling_device (STB_GLOBAL)
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
