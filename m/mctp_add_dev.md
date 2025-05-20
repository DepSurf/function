# Function: <code>mctp_add_dev</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct mctp_dev *mctp_add_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mctp/device.c (0)
Location: net/mctp/device.c:340
Inline: False
Direct callers:
  - net/mctp/device.c:mctp_register_netdev
  - net/mctp/device.c:mctp_dev_notify
```
**Symbols:**

```
ffffffff81e38310-ffffffff81e383dd: mctp_add_dev (STB_LOCAL)
ffffffff81f10d0d-ffffffff81f10d21: mctp_add_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct mctp_dev *mctp_add_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mctp/device.c (0)
Location: net/mctp/device.c:340
Inline: False
Direct callers:
  - net/mctp/device.c:mctp_register_netdev
  - net/mctp/device.c:mctp_dev_notify
```
**Symbols:**

```
ffffffff82011570-ffffffff8201163d: mctp_add_dev (STB_LOCAL)
ffffffff820b6ff3-ffffffff820b7007: mctp_add_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct mctp_dev *mctp_add_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mctp/device.c (0)
Location: net/mctp/device.c:340
Inline: False
Direct callers:
  - net/mctp/device.c:mctp_register_netdev
  - net/mctp/device.c:mctp_dev_notify
```
**Symbols:**

```
ffffffff8208e350-ffffffff8208e41d: mctp_add_dev (STB_LOCAL)
ffffffff8213839c-ffffffff821383b0: mctp_add_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct mctp_dev *mctp_add_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mctp/device.c (0)
Location: net/mctp/device.c:340
Inline: False
Direct callers:
  - net/mctp/device.c:mctp_register_netdev
  - net/mctp/device.c:mctp_dev_notify
```
**Symbols:**

```
ffffffff82164810-ffffffff82164910: mctp_add_dev (STB_LOCAL)
ffffffff8221a239-ffffffff8221a24d: mctp_add_dev.cold (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
