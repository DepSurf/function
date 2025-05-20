# Function: <code>mctp_local_output</code>

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
int mctp_local_output(struct sock *sk, struct mctp_route *rt, struct sk_buff *skb, mctp_eid_t daddr, u8 req_tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mctp/route.c (0)
Location: net/mctp/route.c:841
Inline: False
Direct callers:
  - net/mctp/af_mctp.c:mctp_sendmsg
```
**Symbols:**

```
ffffffff81f10e44-ffffffff81f10eb0: mctp_local_output.cold (STB_LOCAL)
ffffffff81e3ac70-ffffffff81e3b0fa: mctp_local_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mctp_local_output(struct sock *sk, struct mctp_route *rt, struct sk_buff *skb, mctp_eid_t daddr, u8 req_tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mctp/route.c (0)
Location: net/mctp/route.c:849
Inline: False
Direct callers:
  - net/mctp/af_mctp.c:mctp_sendmsg
```
**Symbols:**

```
ffffffff820b70f4-ffffffff820b7160: mctp_local_output.cold (STB_LOCAL)
ffffffff82014250-ffffffff820146da: mctp_local_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mctp_local_output(struct sock *sk, struct mctp_route *rt, struct sk_buff *skb, mctp_eid_t daddr, u8 req_tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mctp/route.c (0)
Location: net/mctp/route.c:849
Inline: False
Direct callers:
  - net/mctp/af_mctp.c:mctp_sendmsg
```
**Symbols:**

```
ffffffff821384a3-ffffffff821384f3: mctp_local_output.cold (STB_LOCAL)
ffffffff820910e0-ffffffff820914fb: mctp_local_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mctp_local_output(struct sock *sk, struct mctp_route *rt, struct sk_buff *skb, mctp_eid_t daddr, u8 req_tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mctp/route.c (0)
Location: net/mctp/route.c:859
Inline: False
Direct callers:
  - net/mctp/af_mctp.c:mctp_sendmsg
```
**Symbols:**

```
ffffffff8221a340-ffffffff8221a3ac: mctp_local_output.cold (STB_LOCAL)
ffffffff82167610-ffffffff82167a9f: mctp_local_output (STB_GLOBAL)
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
