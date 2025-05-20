# Function: <code>dev_eth_ioctl</code>

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
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81ad0965)
Location: net/core/dev_ioctl.c:243
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81c4e4a3)
Location: net/core/dev_ioctl.c:245
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81e03529)
Location: net/core/dev_ioctl.c:245
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_eth_ioctl(struct net_device *dev, struct ifreq *ifr, unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81e75760)
Location: net/core/dev_ioctl.c:241
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_set_hwtstamp
```
**Symbols:**

```
ffffffff81e75760-ffffffff81e757b9: dev_eth_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dev_eth_ioctl(struct net_device *dev, struct ifreq *ifr, unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev_ioctl.c (ffffffff81f35380)
Location: net/core/dev_ioctl.c:242
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:generic_hwtstamp_ioctl_lower
  - net/core/dev_ioctl.c:dev_set_hwtstamp
```
**Symbols:**

```
ffffffff81f35380-ffffffff81f353d9: dev_eth_ioctl (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
