# Function: <code>__net_test_loopback</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __net_test_loopback(struct net_device *ndev, struct net_packet_attrs *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/selftests.c (ffffffff81a36650)
Location: net/core/selftests.c:240
Inline: False
Direct callers:
  - net/core/selftests.c:net_test_phy_loopback_tcp
  - net/core/selftests.c:net_test_phy_loopback_udp
```
**Symbols:**

```
ffffffff81a36650-ffffffff81a3677d: __net_test_loopback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __net_test_loopback(struct net_device *ndev, struct net_packet_attrs *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/selftests.c (ffffffff81aec330)
Location: net/core/selftests.c:240
Inline: False
Direct callers:
  - net/core/selftests.c:net_test_phy_loopback_tcp
  - net/core/selftests.c:net_test_phy_loopback_udp_mtu
  - net/core/selftests.c:net_test_phy_loopback_udp
```
**Symbols:**

```
ffffffff81aec330-ffffffff81aec45d: __net_test_loopback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __net_test_loopback(struct net_device *ndev, struct net_packet_attrs *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/selftests.c (ffffffff81c6ece0)
Location: net/core/selftests.c:240
Inline: False
Direct callers:
  - net/core/selftests.c:net_test_phy_loopback_tcp
  - net/core/selftests.c:net_test_phy_loopback_udp_mtu
  - net/core/selftests.c:net_test_phy_loopback_udp
```
**Symbols:**

```
ffffffff81c6ece0-ffffffff81c6ee0f: __net_test_loopback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __net_test_loopback(struct net_device *ndev, struct net_packet_attrs *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/selftests.c (ffffffff81e26a30)
Location: net/core/selftests.c:240
Inline: False
Direct callers:
  - net/core/selftests.c:net_test_phy_loopback_tcp
  - net/core/selftests.c:net_test_phy_loopback_udp_mtu
  - net/core/selftests.c:net_test_phy_loopback_udp
```
**Symbols:**

```
ffffffff81e26a30-ffffffff81e26b5f: __net_test_loopback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __net_test_loopback(struct net_device *ndev, struct net_packet_attrs *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/selftests.c (ffffffff81e9bfd0)
Location: net/core/selftests.c:240
Inline: False
Direct callers:
  - net/core/selftests.c:net_test_phy_loopback_tcp
  - net/core/selftests.c:net_test_phy_loopback_udp_mtu
  - net/core/selftests.c:net_test_phy_loopback_udp
```
**Symbols:**

```
ffffffff81e9bfd0-ffffffff81e9c0ff: __net_test_loopback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __net_test_loopback(struct net_device *ndev, struct net_packet_attrs *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/selftests.c (ffffffff81f5e730)
Location: net/core/selftests.c:240
Inline: False
Direct callers:
  - net/core/selftests.c:net_test_phy_loopback_tcp
  - net/core/selftests.c:net_test_phy_loopback_udp_mtu
  - net/core/selftests.c:net_test_phy_loopback_udp
```
**Symbols:**

```
ffffffff81f5e730-ffffffff81f5e88e: __net_test_loopback (STB_LOCAL)
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
