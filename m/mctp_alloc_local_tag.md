# Function: <code>mctp_alloc_local_tag</code>

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
struct mctp_sk_key *mctp_alloc_local_tag(struct mctp_sock *msk, mctp_eid_t daddr, mctp_eid_t saddr, bool manual, u8 *tagp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mctp/route.c (0)
Location: net/mctp/route.c:594
Inline: False
Direct callers:
  - net/mctp/af_mctp.c:mctp_ioctl
  - net/mctp/route.c:mctp_local_output
```
**Symbols:**

```
ffffffff81f10e09-ffffffff81f10e44: mctp_alloc_local_tag.cold (STB_LOCAL)
ffffffff81e3a6b0-ffffffff81e3a97b: mctp_alloc_local_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct mctp_sk_key *mctp_alloc_local_tag(struct mctp_sock *msk, mctp_eid_t daddr, mctp_eid_t saddr, bool manual, u8 *tagp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mctp/route.c (0)
Location: net/mctp/route.c:602
Inline: False
Direct callers:
  - net/mctp/af_mctp.c:mctp_ioctl
  - net/mctp/route.c:mctp_local_output
```
**Symbols:**

```
ffffffff820b70b9-ffffffff820b70f4: mctp_alloc_local_tag.cold (STB_LOCAL)
ffffffff82013c60-ffffffff82013f25: mctp_alloc_local_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct mctp_sk_key *mctp_alloc_local_tag(struct mctp_sock *msk, mctp_eid_t daddr, mctp_eid_t saddr, bool manual, u8 *tagp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mctp/route.c (0)
Location: net/mctp/route.c:602
Inline: False
Direct callers:
  - net/mctp/af_mctp.c:mctp_ioctl
  - net/mctp/route.c:mctp_local_output
```
**Symbols:**

```
ffffffff82138468-ffffffff821384a3: mctp_alloc_local_tag.cold (STB_LOCAL)
ffffffff82090ae0-ffffffff82090db0: mctp_alloc_local_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct mctp_sk_key *mctp_alloc_local_tag(struct mctp_sock *msk, mctp_eid_t daddr, mctp_eid_t saddr, bool manual, u8 *tagp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mctp/route.c (0)
Location: net/mctp/route.c:602
Inline: False
Direct callers:
  - net/mctp/af_mctp.c:mctp_ioctl
  - net/mctp/route.c:mctp_local_output
```
**Symbols:**

```
ffffffff8221a305-ffffffff8221a340: mctp_alloc_local_tag.cold (STB_LOCAL)
ffffffff82167020-ffffffff821672f0: mctp_alloc_local_tag (STB_GLOBAL)
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
