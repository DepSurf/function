# Function: <code>__tcp_md5_do_add</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __tcp_md5_do_add(struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen, int l3index, u8 flags, const u8 *newkey, u8 newkeylen, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (0)
Location: net/ipv4/tcp_ipv4.c:1180
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_key_copy
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_add
```
**Symbols:**

```
ffffffff81eccee0-ffffffff81ecd254: __tcp_md5_do_add (STB_LOCAL)
ffffffff820af96f-ffffffff820af9b7: __tcp_md5_do_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __tcp_md5_do_add(struct sock *sk, const union tcp_md5_addr *addr, int family, u8 prefixlen, int l3index, u8 flags, const u8 *newkey, u8 newkeylen, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (0)
Location: net/ipv4/tcp_ipv4.c:1187
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_key_copy
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_add
```
**Symbols:**

```
ffffffff81f2bbc0-ffffffff81f2bf34: __tcp_md5_do_add (STB_LOCAL)
ffffffff82130ceb-ffffffff82130d33: __tcp_md5_do_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __tcp_md5_do_add(struct sock *sk, const union tcp_ao_addr *addr, int family, u8 prefixlen, int l3index, u8 flags, const u8 *newkey, u8 newkeylen, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (0)
Location: net/ipv4/tcp_ipv4.c:1347
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_key_copy
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_add
```
**Symbols:**

```
ffffffff81ff0980-ffffffff81ff0ce0: __tcp_md5_do_add (STB_LOCAL)
ffffffff822124bf-ffffffff82212517: __tcp_md5_do_add.cold (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const union tcp_md5_addr *addr</code> ➡️ <code>const union tcp_ao_addr *addr</code>
</li>
</ul>
</details>
</li>
</ul>
