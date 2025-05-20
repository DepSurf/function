# Function: <code>mctp_dev_hold</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void mctp_dev_hold(struct mctp_dev *mdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mctp/device.c (ffffffff81e38b35)
Location: net/mctp/device.c:308
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_dev_set_key
Direct callers:
  - net/mctp/route.c:mctp_route_add
  - net/mctp/neigh.c:mctp_rtm_newneigh
```
**Symbols:**

```
ffffffff81e386a0-ffffffff81e3870c: mctp_dev_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mctp_dev_hold(struct mctp_dev *mdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mctp/device.c (ffffffff82011e15)
Location: net/mctp/device.c:308
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_dev_set_key
Direct callers:
  - net/mctp/route.c:mctp_route_add
```
**Symbols:**

```
ffffffff82011950-ffffffff820119bc: mctp_dev_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mctp_dev_hold(struct mctp_dev *mdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mctp/device.c (ffffffff8208ebf5)
Location: net/mctp/device.c:308
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_dev_set_key
Direct callers:
  - net/mctp/route.c:mctp_route_add
```
**Symbols:**

```
ffffffff8208e740-ffffffff8208e7ac: mctp_dev_hold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mctp_dev_hold(struct mctp_dev *mdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mctp/device.c (ffffffff821650e5)
Location: net/mctp/device.c:308
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_dev_set_key
Direct callers:
  - net/mctp/route.c:mctp_route_add
```
**Symbols:**

```
ffffffff82164c30-ffffffff82164c9c: mctp_dev_hold (STB_GLOBAL)
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
