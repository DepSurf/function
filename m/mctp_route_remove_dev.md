# Function: <code>mctp_route_remove_dev</code>

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
void mctp_route_remove_dev(struct mctp_dev *mdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mctp/route.c (0)
Location: net/mctp/route.c:1053
Inline: False
Direct callers:
  - net/mctp/device.c:mctp_dev_notify
```
**Symbols:**

```
ffffffff81f10eb0-ffffffff81f10ec4: mctp_route_remove_dev.cold (STB_LOCAL)
ffffffff81e3b160-ffffffff81e3b23d: mctp_route_remove_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void mctp_route_remove_dev(struct mctp_dev *mdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mctp/route.c (0)
Location: net/mctp/route.c:1061
Inline: False
Direct callers:
  - net/mctp/device.c:mctp_dev_notify
```
**Symbols:**

```
ffffffff820b7160-ffffffff820b7174: mctp_route_remove_dev.cold (STB_LOCAL)
ffffffff82014770-ffffffff8201484d: mctp_route_remove_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void mctp_route_remove_dev(struct mctp_dev *mdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mctp/route.c (0)
Location: net/mctp/route.c:1061
Inline: False
Direct callers:
  - net/mctp/device.c:mctp_dev_notify
```
**Symbols:**

```
ffffffff821384f3-ffffffff82138507: mctp_route_remove_dev.cold (STB_LOCAL)
ffffffff82091590-ffffffff8209166d: mctp_route_remove_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void mctp_route_remove_dev(struct mctp_dev *mdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mctp/route.c (0)
Location: net/mctp/route.c:1077
Inline: False
Direct callers:
  - net/mctp/device.c:mctp_dev_notify
```
**Symbols:**

```
ffffffff8221a3ac-ffffffff8221a3c0: mctp_route_remove_dev.cold (STB_LOCAL)
ffffffff82167b30-ffffffff82167c0d: mctp_route_remove_dev (STB_GLOBAL)
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
