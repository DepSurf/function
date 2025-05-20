# Function: <code>__mctp_dev_get</code>

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
struct mctp_dev *__mctp_dev_get(const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mctp/device.c (ffffffff81e387a5)
Location: net/mctp/device.c:31
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_get_link_af_size
Direct callers:
  - net/mctp/device.c:mctp_dump_addrinfo
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_local_output
```
**Symbols:**

```
ffffffff81e38610-ffffffff81e3867b: __mctp_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct mctp_dev *__mctp_dev_get(const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mctp/device.c (ffffffff82011a75)
Location: net/mctp/device.c:31
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_get_link_af_size
Direct callers:
  - net/mctp/device.c:mctp_dump_addrinfo
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_local_output
```
**Symbols:**

```
ffffffff820118a0-ffffffff8201190b: __mctp_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct mctp_dev *__mctp_dev_get(const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mctp/device.c (ffffffff8208e865)
Location: net/mctp/device.c:31
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_get_link_af_size
Direct callers:
  - net/mctp/device.c:mctp_dump_addrinfo
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_local_output
```
**Symbols:**

```
ffffffff8208e680-ffffffff8208e6fc: __mctp_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct mctp_dev *__mctp_dev_get(const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mctp/device.c (ffffffff82164d55)
Location: net/mctp/device.c:31
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_get_link_af_size
Direct callers:
  - net/mctp/device.c:mctp_dump_addrinfo
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_local_output
```
**Symbols:**

```
ffffffff82164b70-ffffffff82164bec: __mctp_dev_get (STB_GLOBAL)
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
