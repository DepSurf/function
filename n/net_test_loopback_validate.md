# Function: <code>net_test_loopback_validate</code>

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
int net_test_loopback_validate(struct sk_buff *skb, struct net_device *ndev, struct packet_type *pt, struct net_device *orig_ndev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/selftests.c (ffffffff81a36460)
Location: net/core/selftests.c:170
Inline: False
```
**Symbols:**

```
ffffffff81a36460-ffffffff81a36645: net_test_loopback_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int net_test_loopback_validate(struct sk_buff *skb, struct net_device *ndev, struct packet_type *pt, struct net_device *orig_ndev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/selftests.c (0)
Location: net/core/selftests.c:170
Inline: False
```
**Symbols:**

```
ffffffff81aec130-ffffffff81aec323: net_test_loopback_validate (STB_LOCAL)
ffffffff81d38296-ffffffff81d382ab: net_test_loopback_validate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int net_test_loopback_validate(struct sk_buff *skb, struct net_device *ndev, struct packet_type *pt, struct net_device *orig_ndev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/selftests.c (0)
Location: net/core/selftests.c:170
Inline: False
```
**Symbols:**

```
ffffffff81c6eae0-ffffffff81c6ecde: net_test_loopback_validate (STB_LOCAL)
ffffffff81f04c78-ffffffff81f04c8d: net_test_loopback_validate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int net_test_loopback_validate(struct sk_buff *skb, struct net_device *ndev, struct packet_type *pt, struct net_device *orig_ndev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/selftests.c (0)
Location: net/core/selftests.c:170
Inline: False
```
**Symbols:**

```
ffffffff81e26820-ffffffff81e26a1e: net_test_loopback_validate (STB_LOCAL)
ffffffff820acd1c-ffffffff820acd31: net_test_loopback_validate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int net_test_loopback_validate(struct sk_buff *skb, struct net_device *ndev, struct packet_type *pt, struct net_device *orig_ndev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/selftests.c (0)
Location: net/core/selftests.c:170
Inline: False
```
**Symbols:**

```
ffffffff81e9bdc0-ffffffff81e9bfbe: net_test_loopback_validate (STB_LOCAL)
ffffffff8212e41b-ffffffff8212e430: net_test_loopback_validate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int net_test_loopback_validate(struct sk_buff *skb, struct net_device *ndev, struct packet_type *pt, struct net_device *orig_ndev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/selftests.c (0)
Location: net/core/selftests.c:170
Inline: False
```
**Symbols:**

```
ffffffff81f5e520-ffffffff81f5e71e: net_test_loopback_validate (STB_LOCAL)
ffffffff822101fa-ffffffff8221020f: net_test_loopback_validate.cold (STB_LOCAL)
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
