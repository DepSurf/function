# Function: <code>__mctp_key_done_in</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __mctp_key_done_in(struct mctp_sk_key *key, struct net *net, long unsigned int flags, long unsigned int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mctp/route.c (0)
Location: net/mctp/route.c:212
Inline: False
Direct callers:
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
```
**Symbols:**

```
ffffffff81e39ef0-ffffffff81e3a064: __mctp_key_done_in (STB_LOCAL)
ffffffff81f10daf-ffffffff81f10dd9: __mctp_key_done_in.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __mctp_key_done_in(struct mctp_sk_key *key, struct net *net, long unsigned int flags, long unsigned int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mctp/route.c (0)
Location: net/mctp/route.c:220
Inline: False
Direct callers:
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
```
**Symbols:**

```
ffffffff82013550-ffffffff820136c5: __mctp_key_done_in (STB_LOCAL)
ffffffff820b707a-ffffffff820b70a4: __mctp_key_done_in.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __mctp_key_done_in(struct mctp_sk_key *key, struct net *net, long unsigned int flags, long unsigned int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mctp/route.c (0)
Location: net/mctp/route.c:220
Inline: False
Direct callers:
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
```
**Symbols:**

```
ffffffff82090370-ffffffff820904e5: __mctp_key_done_in (STB_LOCAL)
ffffffff82138429-ffffffff82138453: __mctp_key_done_in.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __mctp_key_done_in(struct mctp_sk_key *key, struct net *net, long unsigned int flags, long unsigned int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mctp/route.c (0)
Location: net/mctp/route.c:220
Inline: False
Direct callers:
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
```
**Symbols:**

```
ffffffff821668b0-ffffffff82166a25: __mctp_key_done_in (STB_LOCAL)
ffffffff8221a2c6-ffffffff8221a2f0: __mctp_key_done_in.cold (STB_LOCAL)
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
