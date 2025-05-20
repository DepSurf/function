# Function: <code>dev_fetch_sw_netstats</code>

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
void dev_fetch_sw_netstats(struct rtnl_link_stats64 *s, const struct pcpu_sw_netstats *netstats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a00090)
Location: net/core/dev.c:10513
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_tstats64
```
**Symbols:**

```
ffffffff81a00090-ffffffff81a000f3: dev_fetch_sw_netstats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dev_fetch_sw_netstats(struct rtnl_link_stats64 *s, const struct pcpu_sw_netstats *netstats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e6600)
Location: net/core/dev.c:10685
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_tstats64
```
**Symbols:**

```
ffffffff819e6600-ffffffff819e6663: dev_fetch_sw_netstats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dev_fetch_sw_netstats(struct rtnl_link_stats64 *s, const struct pcpu_sw_netstats *netstats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a96b60)
Location: net/core/dev.c:10692
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_tstats64
```
**Symbols:**

```
ffffffff81a96b60-ffffffff81a96be7: dev_fetch_sw_netstats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dev_fetch_sw_netstats(struct rtnl_link_stats64 *s, const struct pcpu_sw_netstats *netstats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c0ce30)
Location: net/core/dev.c:10465
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_tstats64
```
**Symbols:**

```
ffffffff81c0ce30-ffffffff81c0ced2: dev_fetch_sw_netstats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dev_fetch_sw_netstats(struct rtnl_link_stats64 *s, const struct pcpu_sw_netstats *netstats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc16e0)
Location: net/core/dev.c:10444
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_tstats64
```
**Symbols:**

```
ffffffff81dc16e0-ffffffff81dc1796: dev_fetch_sw_netstats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dev_fetch_sw_netstats(struct rtnl_link_stats64 *s, const struct pcpu_sw_netstats *netstats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e30f00)
Location: net/core/dev.c:10456
Inline: False
Direct callers:
  - net/core/dev.c:dev_get_tstats64
```
**Symbols:**

```
ffffffff81e30f00-ffffffff81e30fb6: dev_fetch_sw_netstats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dev_fetch_sw_netstats(struct rtnl_link_stats64 *s, const struct pcpu_sw_netstats *netstats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81eef600)
Location: net/core/dev.c:10666
Inline: False
Direct callers:
  - drivers/net/netkit.c:netkit_get_stats
  - net/core/dev.c:dev_get_tstats64
```
**Symbols:**

```
ffffffff81eef600-ffffffff81eef6b6: dev_fetch_sw_netstats (STB_GLOBAL)
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
