# Function: <code>mctp_route_remove_local</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
int mctp_route_remove_local(struct mctp_dev *mdev, mctp_eid_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mctp/route.c (ffffffff81e3b130)
Location: net/mctp/route.c:1047
Inline: False
Direct callers:
  - net/mctp/device.c:mctp_rtm_deladdr
```
**Symbols:**

```
ffffffff81e3b130-ffffffff81e3b157: mctp_route_remove_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mctp_route_remove_local(struct mctp_dev *mdev, mctp_eid_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mctp/route.c (ffffffff82014730)
Location: net/mctp/route.c:1055
Inline: False
Direct callers:
  - net/mctp/device.c:mctp_rtm_deladdr
```
**Symbols:**

```
ffffffff82014730-ffffffff82014757: mctp_route_remove_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mctp_route_remove_local(struct mctp_dev *mdev, mctp_eid_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mctp/route.c (ffffffff82091550)
Location: net/mctp/route.c:1055
Inline: False
Direct callers:
  - net/mctp/device.c:mctp_rtm_deladdr
```
**Symbols:**

```
ffffffff82091550-ffffffff82091577: mctp_route_remove_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mctp_route_remove_local(struct mctp_dev *mdev, mctp_eid_t addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mctp/route.c (ffffffff82167af0)
Location: net/mctp/route.c:1071
Inline: False
Direct callers:
  - net/mctp/device.c:mctp_rtm_deladdr
```
**Symbols:**

```
ffffffff82167af0-ffffffff82167b17: mctp_route_remove_local (STB_GLOBAL)
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
