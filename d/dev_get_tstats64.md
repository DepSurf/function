# Function: <code>dev_get_tstats64</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dev_get_tstats64(struct net_device *dev, struct rtnl_link_stats64 *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a00100)
Location: net/core/dev.c:10548
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_get_stats64
```
**Symbols:**

```
ffffffff81a00100-ffffffff81a00135: dev_get_tstats64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dev_get_tstats64(struct net_device *dev, struct rtnl_link_stats64 *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e6670)
Location: net/core/dev.c:10720
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_get_stats64
```
**Symbols:**

```
ffffffff819e6670-ffffffff819e66a5: dev_get_tstats64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dev_get_tstats64(struct net_device *dev, struct rtnl_link_stats64 *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a96bf0)
Location: net/core/dev.c:10727
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_get_stats64
```
**Symbols:**

```
ffffffff81a96bf0-ffffffff81a96c25: dev_get_tstats64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dev_get_tstats64(struct net_device *dev, struct rtnl_link_stats64 *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c0cee0)
Location: net/core/dev.c:10500
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_get_stats64
```
**Symbols:**

```
ffffffff81c0cee0-ffffffff81c0cf1e: dev_get_tstats64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dev_get_tstats64(struct net_device *dev, struct rtnl_link_stats64 *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc17b0)
Location: net/core/dev.c:10479
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_get_stats64
```
**Symbols:**

```
ffffffff81dc17b0-ffffffff81dc17ee: dev_get_tstats64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dev_get_tstats64(struct net_device *dev, struct rtnl_link_stats64 *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e30fd0)
Location: net/core/dev.c:10491
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_get_stats64
```
**Symbols:**

```
ffffffff81e30fd0-ffffffff81e3100e: dev_get_tstats64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dev_get_tstats64(struct net_device *dev, struct rtnl_link_stats64 *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81eef6d0)
Location: net/core/dev.c:10701
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_get_stats64
```
**Symbols:**

```
ffffffff81eef6d0-ffffffff81eef70e: dev_get_tstats64 (STB_GLOBAL)
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
