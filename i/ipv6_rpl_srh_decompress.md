# Function: <code>ipv6_rpl_srh_decompress</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ipv6_rpl_srh_decompress(struct ipv6_rpl_sr_hdr *outhdr, const struct ipv6_rpl_sr_hdr *inhdr, const struct in6_addr *daddr, unsigned char n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/rpl.c (ffffffff81b728b0)
Location: net/ipv6/rpl.c:38
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
**Symbols:**

```
ffffffff81b728b0-ffffffff81b7298c: ipv6_rpl_srh_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ipv6_rpl_srh_decompress(struct ipv6_rpl_sr_hdr *outhdr, const struct ipv6_rpl_sr_hdr *inhdr, const struct in6_addr *daddr, unsigned char n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/rpl.c (ffffffff81b81620)
Location: net/ipv6/rpl.c:38
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
**Symbols:**

```
ffffffff81b81620-ffffffff81b816fc: ipv6_rpl_srh_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ipv6_rpl_srh_decompress(struct ipv6_rpl_sr_hdr *outhdr, const struct ipv6_rpl_sr_hdr *inhdr, const struct in6_addr *daddr, unsigned char n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/rpl.c (ffffffff81b70230)
Location: net/ipv6/rpl.c:38
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
**Symbols:**

```
ffffffff81b70230-ffffffff81b7030c: ipv6_rpl_srh_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ipv6_rpl_srh_decompress(struct ipv6_rpl_sr_hdr *outhdr, const struct ipv6_rpl_sr_hdr *inhdr, const struct in6_addr *daddr, unsigned char n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/rpl.c (ffffffff81c38510)
Location: net/ipv6/rpl.c:38
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
**Symbols:**

```
ffffffff81c38510-ffffffff81c385ec: ipv6_rpl_srh_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ipv6_rpl_srh_decompress(struct ipv6_rpl_sr_hdr *outhdr, const struct ipv6_rpl_sr_hdr *inhdr, const struct in6_addr *daddr, unsigned char n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/rpl.c (ffffffff81dd6290)
Location: net/ipv6/rpl.c:38
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
**Symbols:**

```
ffffffff81dd6290-ffffffff81dd6385: ipv6_rpl_srh_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ipv6_rpl_srh_decompress(struct ipv6_rpl_sr_hdr *outhdr, const struct ipv6_rpl_sr_hdr *inhdr, const struct in6_addr *daddr, unsigned char n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/rpl.c (ffffffff81fa7b50)
Location: net/ipv6/rpl.c:38
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
**Symbols:**

```
ffffffff81fa7b50-ffffffff81fa7c45: ipv6_rpl_srh_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ipv6_rpl_srh_decompress(struct ipv6_rpl_sr_hdr *outhdr, const struct ipv6_rpl_sr_hdr *inhdr, const struct in6_addr *daddr, unsigned char n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/rpl.c (ffffffff820083c0)
Location: net/ipv6/rpl.c:32
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
**Symbols:**

```
ffffffff820083c0-ffffffff820084b5: ipv6_rpl_srh_decompress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ipv6_rpl_srh_decompress(struct ipv6_rpl_sr_hdr *outhdr, const struct ipv6_rpl_sr_hdr *inhdr, const struct in6_addr *daddr, unsigned char n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/rpl.c (ffffffff820d72e0)
Location: net/ipv6/rpl.c:32
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
**Symbols:**

```
ffffffff820d72e0-ffffffff820d73d5: ipv6_rpl_srh_decompress (STB_GLOBAL)
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
