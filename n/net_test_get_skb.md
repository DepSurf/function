# Function: <code>net_test_get_skb</code>

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
struct sk_buff *net_test_get_skb(struct net_device *ndev, struct net_packet_attrs *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/selftests.c (ffffffff81a36100)
Location: net/core/selftests.c:54
Inline: False
Direct callers:
  - net/core/selftests.c:__net_test_loopback
```
**Symbols:**

```
ffffffff81a36100-ffffffff81a3645a: net_test_get_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct sk_buff *net_test_get_skb(struct net_device *ndev, struct net_packet_attrs *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/selftests.c (0)
Location: net/core/selftests.c:54
Inline: False
Direct callers:
  - net/core/selftests.c:__net_test_loopback
```
**Symbols:**

```
ffffffff81aebd80-ffffffff81aec128: net_test_get_skb (STB_LOCAL)
ffffffff81d381f1-ffffffff81d38296: net_test_get_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct sk_buff *net_test_get_skb(struct net_device *ndev, struct net_packet_attrs *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/selftests.c (0)
Location: net/core/selftests.c:54
Inline: False
Direct callers:
  - net/core/selftests.c:__net_test_loopback
```
**Symbols:**

```
ffffffff81c6e720-ffffffff81c6ead6: net_test_get_skb (STB_LOCAL)
ffffffff81f04bda-ffffffff81f04c78: net_test_get_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct sk_buff *net_test_get_skb(struct net_device *ndev, struct net_packet_attrs *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/selftests.c (0)
Location: net/core/selftests.c:54
Inline: False
Direct callers:
  - net/core/selftests.c:__net_test_loopback
```
**Symbols:**

```
ffffffff81e26450-ffffffff81e26806: net_test_get_skb (STB_LOCAL)
ffffffff820acc7e-ffffffff820acd1c: net_test_get_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct sk_buff *net_test_get_skb(struct net_device *ndev, struct net_packet_attrs *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/selftests.c (0)
Location: net/core/selftests.c:54
Inline: False
Direct callers:
  - net/core/selftests.c:__net_test_loopback
```
**Symbols:**

```
ffffffff81e9b9f0-ffffffff81e9bda7: net_test_get_skb (STB_LOCAL)
ffffffff8212e37d-ffffffff8212e41b: net_test_get_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct sk_buff *net_test_get_skb(struct net_device *ndev, struct net_packet_attrs *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/selftests.c (0)
Location: net/core/selftests.c:54
Inline: False
Direct callers:
  - net/core/selftests.c:__net_test_loopback
```
**Symbols:**

```
ffffffff81f5e150-ffffffff81f5e507: net_test_get_skb (STB_LOCAL)
ffffffff8221015c-ffffffff822101fa: net_test_get_skb.cold (STB_LOCAL)
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
