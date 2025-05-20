# Function: <code>vlan_for_each</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vlan_for_each(struct net_device *dev, int (*action)(struct net_device *, int, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (ffffffff819ec5d0)
Location: net/8021q/vlan_core.c:226
Inline: False
```
**Symbols:**

```
ffffffff819ec5d0-ffffffff819ec6b2: vlan_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vlan_for_each(struct net_device *dev, int (*action)(struct net_device *, int, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (ffffffff81a5b770)
Location: net/8021q/vlan_core.c:226
Inline: False
```
**Symbols:**

```
ffffffff81a5b770-ffffffff81a5b852: vlan_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vlan_for_each(struct net_device *dev, int (*action)(struct net_device *, int, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (ffffffff81a923a0)
Location: net/8021q/vlan_core.c:226
Inline: False
```
**Symbols:**

```
ffffffff81a923a0-ffffffff81a92483: vlan_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vlan_for_each(struct net_device *dev, int (*action)(struct net_device *, int, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (ffffffff81b8d850)
Location: net/8021q/vlan_core.c:226
Inline: False
```
**Symbols:**

```
ffffffff81b8d850-ffffffff81b8d933: vlan_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vlan_for_each(struct net_device *dev, int (*action)(struct net_device *, int, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (ffffffff81b9d4c0)
Location: net/8021q/vlan_core.c:226
Inline: False
```
**Symbols:**

```
ffffffff81b9d4c0-ffffffff81b9d5da: vlan_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vlan_for_each(struct net_device *dev, int (*action)(struct net_device *, int, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (ffffffff81b8c5d0)
Location: net/8021q/vlan_core.c:227
Inline: False
```
**Symbols:**

```
ffffffff81b8c5d0-ffffffff81b8c6ea: vlan_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vlan_for_each(struct net_device *dev, int (*action)(struct net_device *, int, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/8021q/vlan_core.c (0)
Location: net/8021q/vlan_core.c:227
Inline: False
```
**Symbols:**

```
ffffffff81d41b2f-ffffffff81d41b44: vlan_for_each.cold (STB_LOCAL)
ffffffff81c588f0-ffffffff81c58a58: vlan_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vlan_for_each(struct net_device *dev, int (*action)(struct net_device *, int, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/8021q/vlan_core.c (0)
Location: net/8021q/vlan_core.c:227
Inline: False
```
**Symbols:**

```
ffffffff81f0e45b-ffffffff81f0e470: vlan_for_each.cold (STB_LOCAL)
ffffffff81dfa010-ffffffff81dfa15f: vlan_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int vlan_for_each(struct net_device *dev, int (*action)(struct net_device *, int, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/8021q/vlan_core.c (0)
Location: net/8021q/vlan_core.c:227
Inline: False
```
**Symbols:**

```
ffffffff820b54d0-ffffffff820b54e5: vlan_for_each.cold (STB_LOCAL)
ffffffff81fce710-ffffffff81fce85f: vlan_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int vlan_for_each(struct net_device *dev, int (*action)(struct net_device *, int, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/8021q/vlan_core.c (0)
Location: net/8021q/vlan_core.c:227
Inline: False
```
**Symbols:**

```
ffffffff82136a0a-ffffffff82136a1f: vlan_for_each.cold (STB_LOCAL)
ffffffff8204a060-ffffffff8204a1ad: vlan_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int vlan_for_each(struct net_device *dev, int (*action)(struct net_device *, int, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/8021q/vlan_core.c (0)
Location: net/8021q/vlan_core.c:227
Inline: False
```
**Symbols:**

```
ffffffff822187ba-ffffffff822187cf: vlan_for_each.cold (STB_LOCAL)
ffffffff8211bf20-ffffffff8211c06d: vlan_for_each (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int vlan_for_each(struct net_device *dev, int (*action)(struct net_device *, int, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (ffff800010d600e8)
Location: net/8021q/vlan_core.c:226
Inline: False
```
**Symbols:**

```
ffff800010d600e8-ffff800010d601fc: vlan_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vlan_for_each(struct net_device *dev, int (*action)(struct net_device *, int, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (c0e5fc18)
Location: net/8021q/vlan_core.c:226
Inline: False
Direct callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open
```
**Symbols:**

```
c0e5fc18-c0e5fd18: vlan_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vlan_for_each(struct net_device *dev, int (*action)(struct net_device *, int, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (c000000000e9b020)
Location: net/8021q/vlan_core.c:226
Inline: False
```
**Symbols:**

```
c000000000e9b020-c000000000e9b1c4: vlan_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vlan_for_each(struct net_device *dev, int (*action)(struct net_device *, int, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (ffffffe0008955a0)
Location: net/8021q/vlan_core.c:226
Inline: False
```
**Symbols:**

```
ffffffe0008955a0-ffffffe000895680: vlan_for_each (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int vlan_for_each(struct net_device *dev, int (*action)(struct net_device *, int, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (ffffffff81a31a30)
Location: net/8021q/vlan_core.c:226
Inline: False
```
**Symbols:**

```
ffffffff81a31a30-ffffffff81a31b13: vlan_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vlan_for_each(struct net_device *dev, int (*action)(struct net_device *, int, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (ffffffff819eec20)
Location: net/8021q/vlan_core.c:226
Inline: False
```
**Symbols:**

```
ffffffff819eec20-ffffffff819eed03: vlan_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vlan_for_each(struct net_device *dev, int (*action)(struct net_device *, int, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (ffffffff81a9d5e0)
Location: net/8021q/vlan_core.c:226
Inline: False
```
**Symbols:**

```
ffffffff81a9d5e0-ffffffff81a9d6c3: vlan_for_each (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vlan_for_each(struct net_device *dev, int (*action)(struct net_device *, int, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/8021q/vlan_core.c (ffffffff81aa97e0)
Location: net/8021q/vlan_core.c:226
Inline: False
```
**Symbols:**

```
ffffffff81aa97e0-ffffffff81aa98c3: vlan_for_each (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
