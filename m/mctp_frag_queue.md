# Function: <code>mctp_frag_queue</code>

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
int mctp_frag_queue(struct mctp_sk_key *key, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mctp/route.c (ffffffff81e38bc0)
Location: net/mctp/route.c:279
Inline: False
Direct callers:
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
```
**Symbols:**

```
ffffffff81e38bc0-ffffffff81e38c99: mctp_frag_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mctp_frag_queue(struct mctp_sk_key *key, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mctp/route.c (ffffffff82011eb0)
Location: net/mctp/route.c:287
Inline: False
Direct callers:
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
```
**Symbols:**

```
ffffffff82011eb0-ffffffff82011f89: mctp_frag_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mctp_frag_queue(struct mctp_sk_key *key, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mctp/route.c (ffffffff8208ec90)
Location: net/mctp/route.c:287
Inline: False
Direct callers:
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
```
**Symbols:**

```
ffffffff8208ec90-ffffffff8208ed69: mctp_frag_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mctp_frag_queue(struct mctp_sk_key *key, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mctp/route.c (ffffffff82165180)
Location: net/mctp/route.c:287
Inline: False
Direct callers:
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
```
**Symbols:**

```
ffffffff82165180-ffffffff82165259: mctp_frag_queue (STB_LOCAL)
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
