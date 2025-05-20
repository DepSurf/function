# Function: <code>mctp_key_alloc</code>

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
struct mctp_sk_key *mctp_key_alloc(struct mctp_sock *msk, mctp_eid_t local, mctp_eid_t peer, u8 tag, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mctp/route.c (ffffffff81e38ca0)
Location: net/mctp/route.c:133
Inline: False
Direct callers:
  - net/mctp/route.c:mctp_alloc_local_tag
  - net/mctp/route.c:mctp_route_input
```
**Symbols:**

```
ffffffff81e38ca0-ffffffff81e38d14: mctp_key_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct mctp_sk_key *mctp_key_alloc(struct mctp_sock *msk, mctp_eid_t local, mctp_eid_t peer, u8 tag, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mctp/route.c (ffffffff82013070)
Location: net/mctp/route.c:133
Inline: False
Direct callers:
  - net/mctp/route.c:mctp_alloc_local_tag
  - net/mctp/route.c:mctp_route_input
```
**Symbols:**

```
ffffffff82013070-ffffffff8201314c: mctp_key_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct mctp_sk_key *mctp_key_alloc(struct mctp_sock *msk, mctp_eid_t local, mctp_eid_t peer, u8 tag, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mctp/route.c (ffffffff8208fe90)
Location: net/mctp/route.c:133
Inline: False
Direct callers:
  - net/mctp/route.c:mctp_alloc_local_tag
  - net/mctp/route.c:mctp_route_input
```
**Symbols:**

```
ffffffff8208fe90-ffffffff8208ff6c: mctp_key_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct mctp_sk_key *mctp_key_alloc(struct mctp_sock *msk, mctp_eid_t local, mctp_eid_t peer, u8 tag, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mctp/route.c (ffffffff821663a0)
Location: net/mctp/route.c:133
Inline: False
Direct callers:
  - net/mctp/route.c:mctp_alloc_local_tag
  - net/mctp/route.c:mctp_route_input
```
**Symbols:**

```
ffffffff821663a0-ffffffff821664ab: mctp_key_alloc (STB_LOCAL)
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
