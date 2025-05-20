# Function: <code>net_selftest</code>

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
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void net_selftest(struct net_device *ndev, struct ethtool_test *etest, u64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/selftests.c (0)
Location: net/core/selftests.c:357
Inline: False
```
**Symbols:**

```
ffffffff81c24164-ffffffff81c2417e: net_selftest.cold (STB_LOCAL)
ffffffff81a36010-ffffffff81a360ae: net_selftest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void net_selftest(struct net_device *ndev, struct ethtool_test *etest, u64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/selftests.c (0)
Location: net/core/selftests.c:369
Inline: False
```
**Symbols:**

```
ffffffff81d381d8-ffffffff81d381f1: net_selftest.cold (STB_LOCAL)
ffffffff81aebc60-ffffffff81aebd08: net_selftest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void net_selftest(struct net_device *ndev, struct ethtool_test *etest, u64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/selftests.c (0)
Location: net/core/selftests.c:369
Inline: False
```
**Symbols:**

```
ffffffff81f04bc1-ffffffff81f04bda: net_selftest.cold (STB_LOCAL)
ffffffff81c6e5e0-ffffffff81c6e696: net_selftest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void net_selftest(struct net_device *ndev, struct ethtool_test *etest, u64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/selftests.c (ffffffff81e262c0)
Location: net/core/selftests.c:369
Inline: False
```
**Symbols:**

```
ffffffff81e262c0-ffffffff81e263a2: net_selftest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void net_selftest(struct net_device *ndev, struct ethtool_test *etest, u64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/selftests.c (ffffffff81e9b860)
Location: net/core/selftests.c:369
Inline: False
```
**Symbols:**

```
ffffffff81e9b860-ffffffff81e9b942: net_selftest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void net_selftest(struct net_device *ndev, struct ethtool_test *etest, u64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/selftests.c (ffffffff81f5dfd0)
Location: net/core/selftests.c:369
Inline: False
```
**Symbols:**

```
ffffffff81f5dfd0-ffffffff81f5e0b2: net_selftest (STB_GLOBAL)
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
