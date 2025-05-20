# Function: <code>mctp_do_fragment_route</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
int mctp_do_fragment_route(struct mctp_route *rt, struct sk_buff *skb, unsigned int mtu, u8 tag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mctp/route.c (ffffffff81e38ed0)
Location: net/mctp/route.c:759
Inline: False
Direct callers:
  - net/mctp/route.c:mctp_local_output
```
**Symbols:**

```
ffffffff81e38ed0-ffffffff81e39124: mctp_do_fragment_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mctp_do_fragment_route(struct mctp_route *rt, struct sk_buff *skb, unsigned int mtu, u8 tag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mctp/route.c (ffffffff820121f0)
Location: net/mctp/route.c:767
Inline: False
Direct callers:
  - net/mctp/route.c:mctp_local_output
```
**Symbols:**

```
ffffffff820121f0-ffffffff82012444: mctp_do_fragment_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mctp_do_fragment_route(struct mctp_route *rt, struct sk_buff *skb, unsigned int mtu, u8 tag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mctp/route.c (ffffffff8208efe0)
Location: net/mctp/route.c:767
Inline: False
Direct callers:
  - net/mctp/route.c:mctp_local_output
```
**Symbols:**

```
ffffffff8208efe0-ffffffff8208f234: mctp_do_fragment_route (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mctp_do_fragment_route(struct mctp_route *rt, struct sk_buff *skb, unsigned int mtu, u8 tag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mctp/route.c (ffffffff821654c0)
Location: net/mctp/route.c:777
Inline: False
Direct callers:
  - net/mctp/route.c:mctp_local_output
```
**Symbols:**

```
ffffffff821654c0-ffffffff82165714: mctp_do_fragment_route (STB_LOCAL)
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
