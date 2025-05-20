# Function: <code>thermal_genl_send_event</code>

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
int thermal_genl_send_event(enum thermal_genl_event event, struct param *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff8195f7e0)
Location: drivers/thermal/thermal_netlink.c:226
Inline: False
Direct callers:
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_gov_change
  - drivers/thermal/thermal_netlink.c:thermal_notify_cdev_delete
  - drivers/thermal/thermal_netlink.c:thermal_notify_cdev_add
  - drivers/thermal/thermal_netlink.c:thermal_notify_cdev_state_update
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_trip_change
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_trip_delete
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_trip_add
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_trip_up
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_trip_down
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_disable
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_enable
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_delete
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_create
```
**Symbols:**

```
ffffffff8195f7e0-ffffffff8195f8fd: thermal_genl_send_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int thermal_genl_send_event(enum thermal_genl_event event, struct param *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81942d40)
Location: drivers/thermal/thermal_netlink.c:226
Inline: False
Direct callers:
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_gov_change
  - drivers/thermal/thermal_netlink.c:thermal_notify_cdev_delete
  - drivers/thermal/thermal_netlink.c:thermal_notify_cdev_add
  - drivers/thermal/thermal_netlink.c:thermal_notify_cdev_state_update
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_trip_change
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_trip_delete
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_trip_add
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_trip_up
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_trip_down
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_disable
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_enable
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_delete
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_create
```
**Symbols:**

```
ffffffff81942d40-ffffffff81942e5c: thermal_genl_send_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int thermal_genl_send_event(enum thermal_genl_event event, struct param *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff819e7560)
Location: drivers/thermal/thermal_netlink.c:226
Inline: False
Direct callers:
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_gov_change
  - drivers/thermal/thermal_netlink.c:thermal_notify_cdev_delete
  - drivers/thermal/thermal_netlink.c:thermal_notify_cdev_add
  - drivers/thermal/thermal_netlink.c:thermal_notify_cdev_state_update
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_trip_change
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_trip_delete
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_trip_add
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_trip_up
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_trip_down
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_disable
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_enable
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_delete
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_create
```
**Symbols:**

```
ffffffff819e7560-ffffffff819e76a2: thermal_genl_send_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int thermal_genl_send_event(enum thermal_genl_event event, struct param *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81b4cd70)
Location: drivers/thermal/thermal_netlink.c:271
Inline: False
Direct callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cpu_capability_event
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_gov_change
  - drivers/thermal/thermal_netlink.c:thermal_notify_cdev_delete
  - drivers/thermal/thermal_netlink.c:thermal_notify_cdev_add
  - drivers/thermal/thermal_netlink.c:thermal_notify_cdev_state_update
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_trip_change
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_trip_delete
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_trip_add
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_trip_up
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_trip_down
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_disable
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_enable
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_delete
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_create
```
**Symbols:**

```
ffffffff81b4cd70-ffffffff81b4cee3: thermal_genl_send_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int thermal_genl_send_event(enum thermal_genl_event event, struct param *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81ce4a50)
Location: drivers/thermal/thermal_netlink.c:271
Inline: False
Direct callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cpu_capability_event
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_gov_change
  - drivers/thermal/thermal_netlink.c:thermal_notify_cdev_delete
  - drivers/thermal/thermal_netlink.c:thermal_notify_cdev_add
  - drivers/thermal/thermal_netlink.c:thermal_notify_cdev_state_update
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_trip_change
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_trip_delete
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_trip_add
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_trip_up
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_trip_down
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_disable
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_enable
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_delete
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_create
```
**Symbols:**

```
ffffffff81ce4a50-ffffffff81ce4bc3: thermal_genl_send_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int thermal_genl_send_event(enum thermal_genl_event event, struct param *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81d4d020)
Location: drivers/thermal/thermal_netlink.c:271
Inline: False
Direct callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cpu_capability_event
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_gov_change
  - drivers/thermal/thermal_netlink.c:thermal_notify_cdev_delete
  - drivers/thermal/thermal_netlink.c:thermal_notify_cdev_add
  - drivers/thermal/thermal_netlink.c:thermal_notify_cdev_state_update
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_trip_change
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_trip_delete
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_trip_add
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_trip_up
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_trip_down
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_disable
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_enable
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_delete
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_create
```
**Symbols:**

```
ffffffff81d4d020-ffffffff81d4d193: thermal_genl_send_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int thermal_genl_send_event(enum thermal_genl_event event, struct param *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81e03ed0)
Location: drivers/thermal/thermal_netlink.c:270
Inline: False
Direct callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cpu_capability_event
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_gov_change
  - drivers/thermal/thermal_netlink.c:thermal_notify_cdev_delete
  - drivers/thermal/thermal_netlink.c:thermal_notify_cdev_add
  - drivers/thermal/thermal_netlink.c:thermal_notify_cdev_state_update
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_trip_change
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_trip_up
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_trip_down
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_disable
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_enable
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_delete
  - drivers/thermal/thermal_netlink.c:thermal_notify_tz_create
```
**Symbols:**

```
ffffffff81e03ed0-ffffffff81e04050: thermal_genl_send_event (STB_LOCAL)
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
